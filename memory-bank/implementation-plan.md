# Implementation Plan — AEGIS

> Последнее обновление: 2026-02-17

## Текущий стек

Electron 33 + Vanilla JS + CSS. Нет build step, нет фреймворков. 20 renderer скриптов загружаются через `<script>` tags.

## Планы миграции

Пока нет активного плана миграции. Текущая архитектура (Vanilla JS) стабильна и работает.

### Если будет миграция на Svelte + Vite:

**Предварительные шаги:**
1. Добавить Vite как dev dependency
2. Настроить vite.config.js для Electron renderer
3. Конвертировать `index.html` → Svelte App.svelte entry point
4. Мигрировать каждый renderer скрипт → Svelte компонент

**Порядок миграции (по зависимостям):**
1. `state.js` → Svelte stores ($state)
2. `helpers.js` → утилитарный модуль (без изменений)
3. `theme.js` → ThemeToggle.svelte
4. `risk-scoring.js` → утилитарный модуль
5. Radar: `radar-state` + `radar-draw` + `radar-engine` → Radar.svelte (canvas)
6. `permissions.js` → Permissions.svelte
7. Agent DB: `agent-database-ui` + `agent-database-crud` → AgentDatabase.svelte
8. `agent-panel` + `agent-render` → AgentList.svelte + AgentCard.svelte
9. `activity-feed` → ActivityFeed.svelte
10. `network-panel` → NetworkPanel.svelte
11. `timeline` → Timeline.svelte
12. `reports` → Reports.svelte
13. `threat-analysis` → ThreatAnalysis.svelte
14. `settings` + `analysis` → Settings.svelte
15. `app.js` → App.svelte (final wiring)

**Тест на каждый шаг:** запуск `npm start`, проверка что tab работает без ошибок в console.

**Решение пока не принято** — Vanilla JS работает, миграция нужна только если:
- Кодовая база вырастет >15K lines renderer
- Нужен SSR или code splitting
- Появятся сложные reactive state dependencies

## Текущие приоритеты

1. GitHub launch prep (push, issues, releases, CI/CD)
2. electron-builder packaging
3. Cross-platform support
