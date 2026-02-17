# AEGIS Architecture

## Main Process (src/main/) — НЕ ТРОГАЕМ при Svelte миграции
- main.js — orchestrator, IPC, lifecycle
- preload.js — IPC bridge (window.aegis)
- process-scanner.js — AI agent detection
- process-utils.js — parent chain resolution
- file-watcher.js — chokidar + sensitive files
- network-monitor.js — TCP + DNS
- config-manager.js — settings persistence
- baselines.js — session averages
- anomaly-detector.js — deviation scoring
- ai-analysis.js — Anthropic API
- audit-logger.js — JSONL logs
- exports.js — JSON/CSV/HTML export
- tray-icon.js — system tray

## Renderer (src/renderer/) — SVELTE 5 + VITE
- Legacy vanilla JS renderer removed (Step 19): 20 JS + 1 HTML deleted
- Legacy CSS removed (Step 19): 9 CSS files in src/styles/ deleted, directory removed
- src/renderer/app.html — Vite entry point
- src/renderer/main.js — Svelte mount
- src/renderer/App.svelte — root component
- src/renderer/lib/stores/ipc.js — IPC bridge as Svelte stores (agents, events, stats, network, anomalies, resourceUsage)
- src/renderer/lib/styles/global.css — Global reset, body, scrollbar, selection, focus-visible, Google Fonts import
- src/renderer/lib/styles/tokens.css — M3 design tokens (colors, typography, shape, motion)
- src/renderer/lib/components/Header.svelte — fixed top bar: shield score, agents, files, uptime pills (M3 tokens)
- src/renderer/lib/components/Footer.svelte — fixed bottom bar: CPU, memory, heap, scan interval (M3 tokens)
- src/renderer/lib/components/TabBar.svelte — 4-tab pill navigation (Shield/Activity/Rules/Reports)
- src/renderer/lib/components/AgentCard.svelte — individual agent card: name, PID, trust grade badge, risk score, trust bar, parent chain
- src/renderer/lib/utils/risk-scoring.js — calculateRiskScore (log2 curve), getTrustGrade, getTimeDecayWeight
- src/renderer/lib/stores/risk.js — enrichedAgents derived store (agents + events + anomalies + network → riskScore, trustGrade)
- src/renderer/lib/components/AgentPanel.svelte — scrollable agent list from enrichedAgents store, empty state
- src/renderer/lib/components/Radar.svelte — canvas radar: concentric rings, sweep arm (4s rotation), agent dots by riskScore, glow, AEGIS center label, responsive
- src/renderer/lib/components/Timeline.svelte — SVG timeline: last 100 events as 4px color-coded dots on horizontal time axis, severity colors, hover tooltips, responsive
- src/renderer/lib/components/ShieldTab.svelte — column layout: top-row (Radar 60% + AgentPanel 40%), Timeline full-width below, stacks vertically <768px
- src/renderer/lib/components/FeedFilters.svelte — filter bar: agent dropdown (from enrichedAgents), severity pills (all/critical/high/medium/low), type pills (all/file/network), $bindable state
- src/renderer/lib/components/ActivityFeed.svelte — scrollable event list: unified file events + network connections, severity classification (critical/_denied, high/sensitive, medium/deleted, low/normal), newest-first, 200 event cap
- src/renderer/lib/components/NetworkPanel.svelte — network connections list: agent/domain/port/state/classification badge, filter by agent + classification pills, sort by agent/domain/class, 3-tier classify (safe/unknown/flagged)
- src/renderer/lib/components/ActivityTab.svelte — Feed/Network toggle pills, shows FeedFilters+ActivityFeed or NetworkPanel
- src/renderer/lib/components/ProtectionPresets.svelte — 4 preset pill buttons (Paranoid/Strict/Balanced/Developer), active highlight, emits onApply with preset config
- src/renderer/lib/components/PermissionsGrid.svelte — 6 categories × 3 states grid, agent selector from enrichedAgents, tri-state buttons, auto-save via IPC
- src/renderer/lib/components/RulesTab.svelte — sub-toggle (Permissions | Agent Database), composed: ProtectionPresets + PermissionsGrid or AgentDatabaseCrud
- src/renderer/lib/components/AgentDatabase.svelte — agent database table: 88 agents, search/filter input, category filter pills (9 categories), sortable columns (Name/Category/Detection/Risk), scrollable body with fixed header, action buttons for custom agents
- src/renderer/lib/components/AgentDatabaseCrud.svelte — CRUD wrapper: Add Custom Agent modal form (name/process/category/risk/description), edit/delete for custom agents, import/export via IPC, delete confirmation dialog
- src/renderer/lib/components/Reports.svelte — stats summary cards (Total Events/Agents Detected/Avg Risk Score/Uptime), top 10 most active agents table (Name/Events/Risk Score/Grade), export buttons (JSON/CSV/HTML Report)
- src/renderer/lib/components/AuditLog.svelte — audit stats cards (Total Entries/Log Size/Date Range) via getAuditStats IPC, View Logs Directory + Export Full Audit buttons
- src/renderer/lib/components/ThreatAnalysis.svelte — AI threat analysis UI: session/agent radio toggle, agent dropdown from enrichedAgents, Run Analysis button with pulse animation, results display (risk rating hero, summary, findings with severity color-coding, recommendations), Open Full Report button
- src/renderer/lib/utils/threat-report.js — printable HTML threat report generation (extracted from ThreatAnalysis)
- src/renderer/lib/components/ReportsTab.svelte — sub-toggle (Overview | Audit Log | Threat Analysis), composed: Reports or AuditLog or ThreatAnalysis
- src/renderer/lib/components/Settings.svelte — settings modal: scan interval slider, notifications toggle, API key input with show/hide, custom patterns textarea, loads/saves via IPC
- src/renderer/lib/stores/theme.js — theme store (writable, 'dark'/'light') with localStorage persistence + toggleTheme()

## Shared (src/shared/)
- constants.js — sensitive rules, ignore patterns
- agent-database.json — 88 agent signatures