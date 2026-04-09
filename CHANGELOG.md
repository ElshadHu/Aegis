# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [0.11.0-alpha](https://github.com/ElshadHu/Aegis/compare/aegis-v0.10.0-alpha...aegis-v0.11.0-alpha) (2026-04-09)


### Features

* **a11y:** add keyboard shortcuts and accessibility improvements ([#51](https://github.com/ElshadHu/Aegis/issues/51)) ([1037eed](https://github.com/ElshadHu/Aegis/commit/1037eed5a39222c0092a458fd47b2876b4e96261)), closes [#17](https://github.com/ElshadHu/Aegis/issues/17)
* activity feed process grouping with expandable details ([aa4d371](https://github.com/ElshadHu/Aegis/commit/aa4d371826ae988125698f386421750bb4ce11b9))
* add ci-monitor skill for CI watching and repo health ([bc5c860](https://github.com/ElshadHu/Aegis/commit/bc5c860fcd51a10836def814a5a4ff7a5afa6764))
* add JSDoc type annotations using shared type definitions ([bf76346](https://github.com/ElshadHu/Aegis/commit/bf763465dde1efeb8b5c67d8b3ce24531d45670a))
* add pr-monitor and ci-monitor skills with /loop support ([#91](https://github.com/ElshadHu/Aegis/issues/91)) ([2766c10](https://github.com/ElshadHu/Aegis/commit/2766c109ccc167cabe61e265d175187eb9723676))
* add pr-monitor skill for PR triage and /loop monitoring ([77b959d](https://github.com/ElshadHu/Aegis/commit/77b959d0f3aa2a8b61f01a67fb2dbf1e3ef5cc88))
* add TypeScript type definitions for all data structures ([f5e7c44](https://github.com/ElshadHu/Aegis/commit/f5e7c447550235239a8543a04c38b72bff2fc38e))
* add vis-timeline and d3 dependencies ([90de782](https://github.com/ElshadHu/Aegis/commit/90de7823bbe771fc5bf6f6ac7cbe4bf3e5655c6d))
* AEGIS v0.1.0-alpha — AI Agent Privacy Shield ([f8f8f58](https://github.com/ElshadHu/Aegis/commit/f8f8f583364d696415a82dbadd39a3d76831d6af))
* AgentGraph component with force-directed layout ([196a4f7](https://github.com/ElshadHu/Aegis/commit/196a4f79acfe9ceee85811ae5477d7c3c80d0f98))
* **agents:** add 8 new agent signatures to database ([#50](https://github.com/ElshadHu/Aegis/issues/50)) ([f29ebc0](https://github.com/ElshadHu/Aegis/commit/f29ebc0bbfaae55a17a3367c9307e8a3c9d39ec7))
* **agents:** add OpenClaw (formerly Moltbot/Clawdbot) to agent database ([1f80379](https://github.com/ElshadHu/Aegis/commit/1f80379559cc16608f5bba38600740a81d85aacb))
* AgentStatsPanel — sortable agent statistics table ([30a8c1e](https://github.com/ElshadHu/Aegis/commit/30a8c1edafd4b45cde287ba4f937c82c5aa5b9e3))
* **ci:** automated releases with release-please ([#58](https://github.com/ElshadHu/Aegis/issues/58)) ([209b68f](https://github.com/ElshadHu/Aegis/commit/209b68f268caed1522c3beb9f90237b431ff13ce))
* clickable file paths (reveal in explorer) + copyable network addresses ([4c34d2b](https://github.com/ElshadHu/Aegis/commit/4c34d2b099a11dfc1a3639bd35c77375beae2177))
* Command Palette (Ctrl+K) — fuzzy search, keyboard nav, 22 commands ([994e691](https://github.com/ElshadHu/Aegis/commit/994e69194b73b9127bad21d2c8f7a66c69f36d59))
* **command-palette:** add command palette store ([7adce84](https://github.com/ElshadHu/Aegis/commit/7adce843c673da088f5e8953fdabc851093010d5))
* **command-palette:** add CommandPalette UI component ([78b4eba](https://github.com/ElshadHu/Aegis/commit/78b4ebaeebe461810f0a48dc2337776d40789763))
* **command-palette:** add fuzzy search with tests ([068cf2b](https://github.com/ElshadHu/Aegis/commit/068cf2b32eff0fc87c2788f7e23f19c279448eed))
* **command-palette:** add types and command registry ([b80c242](https://github.com/ElshadHu/Aegis/commit/b80c242effa9c0c84cfed45a398f3ce705354f4e))
* **command-palette:** integrate with App and wire actions ([a238836](https://github.com/ElshadHu/Aegis/commit/a2388366f9912c53d51a44ccfc4c1ede24833d5d))
* **community:** false positive marking, agent DB contribution, scan badge (#P4.15-17) ([06f3e50](https://github.com/ElshadHu/Aegis/commit/06f3e504d6c30a1baa2a69e992c43b4e7b73da11))
* container/VM + local LLM detection (88→95 agents) ([cd94a54](https://github.com/ElshadHu/Aegis/commit/cd94a544b0023f4d3634ee7e107f13070a2b8d6a))
* **core:** HTTP scoring, user-agent detection, API indicator, HW accel toggle (#P4.11-14) ([bd3379b](https://github.com/ElshadHu/Aegis/commit/bd3379b2ca0ff7b43c1ae8d9b658e9e61c768eee))
* cross-platform support (macOS/Linux), unified UI scaling, and comprehensive test suite ([#37](https://github.com/ElshadHu/Aegis/issues/37)) ([0b48269](https://github.com/ElshadHu/Aegis/commit/0b48269b83a77c44305d620f49c2be68223d0b2d))
* **demo:** add browser-only demo mode and development guide (closes [#10](https://github.com/ElshadHu/Aegis/issues/10)) ([a71285e](https://github.com/ElshadHu/Aegis/commit/a71285ed9563304b4ae745cabed51a5dd36b1be7))
* **demo:** add browser-only demo mode with simulated agent data ([a86958e](https://github.com/ElshadHu/Aegis/commit/a86958ea42b17b3530d4be7f131d0d020ba4e3b2)), closes [#10](https://github.com/ElshadHu/Aegis/issues/10)
* **demo:** enrich demo — 12 agents, 25 events, informative banner ([#69](https://github.com/ElshadHu/Aegis/issues/69)) ([727161f](https://github.com/ElshadHu/Aegis/commit/727161fc8a79f3292eefd4ca83bfcd60f0604687))
* **demo:** enrich demo with 12 agents, 25 events, informative banner ([f82139c](https://github.com/ElshadHu/Aegis/commit/f82139c7b8e4240c215714344ebb571aef4e4bf3))
* **demo:** polish all tabs for browser demo — mock data for Rules, Reports, Settings ([2c428c0](https://github.com/ElshadHu/Aegis/commit/2c428c034642ffa75838401a960b50f096c1f73c))
* **demo:** polish all tabs for browser demo ([#68](https://github.com/ElshadHu/Aegis/issues/68)) ([11815b2](https://github.com/ElshadHu/Aegis/commit/11815b2ba7792749052cb7d06e84f191dcb3711a))
* **detection:** add local LLM runtime detection (Ollama, LM Studio, vLLM, llama.cpp) — 97 agents ([22e27c6](https://github.com/ElshadHu/Aegis/commit/22e27c681807bfec5fe9b00203c2b47ea201dddf))
* EventFeed — live terminal-style event stream ([adaa4f7](https://github.com/ElshadHu/Aegis/commit/adaa4f7f8c243460e14c5f37b6b604cd6c716909))
* expand agent database with Qwen-Agent, CodeWhisperer aliases, Gemini CLI patterns ([#46](https://github.com/ElshadHu/Aegis/issues/46)) ([2bbf048](https://github.com/ElshadHu/Aegis/commit/2bbf0483158d5e708ed2a44af32a4154c5b3bf3b))
* fancy aegis UI redesign v0.5.0-alpha (F1.1-F4.3) ([6e281cf](https://github.com/ElshadHu/Aegis/commit/6e281cf695a7e3267e3b1f074d39a4d76adbc765))
* **file-watcher:** add configurable ignore list for .git/node_modules ([#11](https://github.com/ElshadHu/Aegis/issues/11)) ([71d9fc7](https://github.com/ElshadHu/Aegis/commit/71d9fc7e433c7eb8ef17a2437b1d1ffd18358b3f))
* **i18n:** add internationalization support with English base ([5e4a74d](https://github.com/ElshadHu/Aegis/commit/5e4a74dfc9414d9cb26feec280dc203a39195158))
* **i18n:** add internationalization support with English base ([#53](https://github.com/ElshadHu/Aegis/issues/53)) ([177f728](https://github.com/ElshadHu/Aegis/commit/177f7280077ad024b41f5b8520226c8473df3a1d))
* **i18n:** add internationalization support with English base ([#53](https://github.com/ElshadHu/Aegis/issues/53)) ([077df0a](https://github.com/ElshadHu/Aegis/commit/077df0a82a0ea2fc3bcadbeb4f3eb1e40dfd8745))
* integrate LLM runtime detection into scan pipeline + CLI JSON output (--scan-json) ([3d06145](https://github.com/ElshadHu/Aegis/commit/3d0614501e3e54d859c5a88ad840851fc0858218))
* **ipc:** add event batching to prevent UI freeze on high-frequency events ([01e2faa](https://github.com/ElshadHu/Aegis/commit/01e2faa66611955aedaccd39f7baf2c66b54495d))
* launch readiness — CSP fix, OpenClaw integration, README enhancement, cleanup ([b226fe6](https://github.com/ElshadHu/Aegis/commit/b226fe6757716d5811688449ed67bc1dbd5827a1))
* move Timeline and Graph to separate tabs with bug fixes ([17e3cba](https://github.com/ElshadHu/Aegis/commit/17e3cbab21e3ee4f3884dbeb9413ba7f9272a4d2))
* multi-dimensional scoring, LLM runtime detection, CLI ([08cec6f](https://github.com/ElshadHu/Aegis/commit/08cec6fd2d0fd4d1210df1ff9d7179327a89c5c2))
* Phase 1 — AI agent config file protection (Hudson Rock threat vector) ([215a709](https://github.com/ElshadHu/Aegis/commit/215a709322771f46101552a3a1654a497be8b34d))
* Phase 2 — behavioral anomaly detection with baseline deviation alerts ([c9f3f1b](https://github.com/ElshadHu/Aegis/commit/c9f3f1bed012eab30224a8ea33f5d1cee9873b05))
* Phase 3 — AI-powered threat analysis via Anthropic API ([e89be17](https://github.com/ElshadHu/Aegis/commit/e89be17c3339a2f2f4946b96372f60a5d9e94a62))
* Phase 4+5 — real-time timeline, dashboard metrics, persistent audit logging ([35b26cc](https://github.com/ElshadHu/Aegis/commit/35b26cc903b091cca7bd33f91aac692b26fe18c0))
* redesign AgentCard, FeedFilters, and Timeline UI ([2a92c31](https://github.com/ElshadHu/Aegis/commit/2a92c3162ff46f180382b3049b05424fa1d81dec))
* **rules:** add IPC endpoints + hot-reload watcher for YAML rules [R4] ([d2371e2](https://github.com/ElshadHu/Aegis/commit/d2371e2e41f4b0c4574293776a6bdc7d63486ba1))
* **rules:** add Moltbot legacy and OpenClaw config detection rules ([b685890](https://github.com/ElshadHu/Aegis/commit/b68589056407cfe3607f0a4312cd6625b2576fc0))
* **rules:** add YAML rule loader with JSON Schema validation [R1] ([0c3bd2c](https://github.com/ElshadHu/Aegis/commit/0c3bd2cc90a787ee599fa66ec6aa41ed68316598))
* **rules:** migrate all SENSITIVE_RULES to typed YAML rulesets [R2] ([4703a9c](https://github.com/ElshadHu/Aegis/commit/4703a9c383d91cce0c3d7c78a25ff4969f82170a))
* **rules:** wire rule-loader into file-watcher, deprecate SENSITIVE_RULES [R3] ([2f30668](https://github.com/ElshadHu/Aegis/commit/2f30668bf49fc4d1bfb0c42e2c47d18299f7b535))
* **rules:** YAML rulesets with hot-reload and IPC (R1-R4) ([0bccc50](https://github.com/ElshadHu/Aegis/commit/0bccc506b760377c41bece8a462a4597250d688d))
* **scoring:** multi-dimensional anomaly scoring (network/fs/process/baseline) ([bb9afd0](https://github.com/ElshadHu/Aegis/commit/bb9afd0cbfbadc0c3f7721077dc928e9a7a0da62))
* show unique agent count vs process count in header and reports ([#55](https://github.com/ElshadHu/Aegis/issues/55)) ([30f0ea9](https://github.com/ElshadHu/Aegis/commit/30f0ea957423c81a59d37a0941e856fbcb521e9f)), closes [#53](https://github.com/ElshadHu/Aegis/issues/53)
* solar system radar with lightning effects ([2323b1b](https://github.com/ElshadHu/Aegis/commit/2323b1b0c684aad72e109a219b5ef4892355840c))
* Stats tab, cleanup Timeline/Feed, Follow in Activity (#timeline-graph) ([7be2b7d](https://github.com/ElshadHu/Aegis/commit/7be2b7d7a28ce8731c53eef6922291b993a16ab5))
* toast notification system ([#15](https://github.com/ElshadHu/Aegis/issues/15)) ([e0e1d6e](https://github.com/ElshadHu/Aegis/commit/e0e1d6edd3831e7bead8697b0c27796d32a8af0f))
* TypeScript infrastructure — tsconfig, 34 types, ESLint TS, ESM test migration, JSDoc annotations (P5-B.0) ([ddc1096](https://github.com/ElshadHu/Aegis/commit/ddc1096081a55166e4f1f8de384dbc6a7657dc81))
* **ui:** add background atmosphere effect [F4.3] ([cbbab33](https://github.com/ElshadHu/Aegis/commit/cbbab333525a662442e3ba1aa79c69e157913a4a))
* **ui:** add design system tokens and local fonts [F1.1] ([4536f65](https://github.com/ElshadHu/Aegis/commit/4536f65a0c91c7b07dd2a2a8d249a86235c241f4))
* **ui:** add feed item animations and severity colors [F3.1] ([2ff34b0](https://github.com/ElshadHu/Aegis/commit/2ff34b0ed5a9a1126c00a75e551a24771064f50a))
* **ui:** add footer mini charts for CPU and memory [F3.2] ([9e9bbf2](https://github.com/ElshadHu/Aegis/commit/9e9bbf2f54a597c411d11c7977d90d04559a4394))
* **ui:** add risk ring SVG gauge with glow and pulse [F4.1] ([39ba0f5](https://github.com/ElshadHu/Aegis/commit/39ba0f5e7248f3ace2b110e7aa7801daa1162e09))
* **ui:** add skeleton loading for pre-scan state ([0f188e6](https://github.com/ElshadHu/Aegis/commit/0f188e67ff41819e58ef8f77c521e42f62cac179))
* **ui:** add skeleton loading states for ActivityTab and RulesTab ([a074a3d](https://github.com/ElshadHu/Aegis/commit/a074a3d150c89790c9abac97fa07829259773a6a))
* **ui:** add sparkline SVG component [F2.1] ([dd6e5ee](https://github.com/ElshadHu/Aegis/commit/dd6e5ee6f1042a9cd0b411404f098798f58a28d2))
* **ui:** add summary cards component with animated counters and trend arrows [F1.3] ([05921d6](https://github.com/ElshadHu/Aegis/commit/05921d6af01dd5b4fcdeef759e32966162b45b51))
* **ui:** add summary cards component with threat metrics [F1.3] ([624bc95](https://github.com/ElshadHu/Aegis/commit/624bc95f3fa2c733ed5efea5edd35e4d0a3cc047))
* **ui:** add tab switch transitions [F3.3] ([0a23a58](https://github.com/ElshadHu/Aegis/commit/0a23a58d80d373bacd12e0bc2c8a859ca0307a0a))
* **ui:** add trust badge component [F2.2] ([a5caae0](https://github.com/ElshadHu/Aegis/commit/a5caae031df1592dd126030b45302ff58a2cf2d5))
* **ui:** copy PID, relative time, path truncation, autoscroll (#P4.1-5) ([5335990](https://github.com/ElshadHu/Aegis/commit/5335990661450960a5b389a68f0a67641364e86b))
* **ui:** redesign agent card with sparkline, badge, spotlight [F2.3] ([33497bb](https://github.com/ElshadHu/Aegis/commit/33497bbbd8b1ada4e103d9077a002df8399d2aa9))
* **ui:** redesign Shield tab with bento grid layout [F1.2] ([55649f1](https://github.com/ElshadHu/Aegis/commit/55649f1696d7a84cd67e7fa5852cc123992c60cd))
* **ui:** threat flash, hotkeys, open location, OOM protect, zip export (#P4.6-10) ([60c8163](https://github.com/ElshadHu/Aegis/commit/60c81636a31869b165de40922e56adf6a572fe17))
* **ui:** typography pass — consistent font tokens across all components [F4.2] ([2514e6f](https://github.com/ElshadHu/Aegis/commit/2514e6f3016a7c092412355a2a4cbed50c181c87))
* VisTimeline component with agent groups and event items ([64d8e4b](https://github.com/ElshadHu/Aegis/commit/64d8e4bc7b213d018ca1a8d17f8a0ec38b8bf282))


### Bug Fixes

* add missing await in ipc-handlers.test.js:346 ([559f87a](https://github.com/ElshadHu/Aegis/commit/559f87af08433e202ececfd726967ef2590a85f4))
* add PID validation to POSIX platform functions and IPC boundary ([1933134](https://github.com/ElshadHu/Aegis/commit/1933134fbb2b2bdc89eda3fdbde7e2943f213955))
* address critical issues from PR [#37](https://github.com/ElshadHu/Aegis/issues/37) code review ([e2a4308](https://github.com/ElshadHu/Aegis/commit/e2a4308b73a76ebc611cb7f11e1d139f4b2c25a5))
* **ci:** resolve svelte-check, eslint errors for command palette and ipc ([78da6b3](https://github.com/ElshadHu/Aegis/commit/78da6b3f553acdd820983b2b1d826b299288c155))
* clean up tab navigation ([36acc0e](https://github.com/ElshadHu/Aegis/commit/36acc0e03400f02337b12411bfa13b5759ed15fd))
* cleanup  timers and reactive loop in Timeline ([9093247](https://github.com/ElshadHu/Aegis/commit/909324795bfa4e51eeb905c89e0b7cfa9e588560))
* convert svelte components to JSDoc style for eslint compatibility ([91e60de](https://github.com/ElshadHu/Aegis/commit/91e60deaf6ca5b35ae9015bcac9b2ec90cec458f))
* correct author name ([9559248](https://github.com/ElshadHu/Aegis/commit/9559248efd9cf0cd8f6ff15f06d67052a789d5bf))
* critical issues from PR [#37](https://github.com/ElshadHu/Aegis/issues/37) code review ([da97ce3](https://github.com/ElshadHu/Aegis/commit/da97ce3bba08f4a15104c6bec2b9f5ba04d6e56f))
* deduplicate agent dropdown entries ([#98](https://github.com/ElshadHu/Aegis/issues/98)) ([f0b6c19](https://github.com/ElshadHu/Aegis/commit/f0b6c1978fcd8cd18a57bb91cbf45f84eac8fdd4))
* deduplicate agents in dropdowns, cards, and reports table ([52cfdc0](https://github.com/ElshadHu/Aegis/commit/52cfdc0d1dec19bf3056cb4920ff5f25d7bd7617))
* **docs:** update broken file references in design-system skill ([5071384](https://github.com/ElshadHu/Aegis/commit/50713848d262ff8b4f342dcc4de544f9e5db362c))
* **docs:** update test counts, productName, lint rule ([b7ea871](https://github.com/ElshadHu/Aegis/commit/b7ea8715bf621203114fe005813e6f8062573a17))
* group agent cards by name, show PIDs inside expand ([d720443](https://github.com/ElshadHu/Aegis/commit/d720443d0c9b18e014fd69f5e937105bdd773c39))
* guard getStats against undefined scanner during early IPC ([b82102e](https://github.com/ElshadHu/Aegis/commit/b82102e5caa2d65a801a1a77c58eca936e35a6ad))
* integrate annotateWorkingDirs into periodic and startup scan pipelines ([#44](https://github.com/ElshadHu/Aegis/issues/44)) ([56ba0aa](https://github.com/ElshadHu/Aegis/commit/56ba0aab5f404c58f0231367d92bce2c296ea77f)), closes [#2](https://github.com/ElshadHu/Aegis/issues/2)
* **ipc:** add try-catch to all async ipc handlers ([63c6044](https://github.com/ElshadHu/Aegis/commit/63c604407989a651e0577314fd01e53addfef2dc))
* lazy init settings/baselines path — resolve app.getPath crash on startup ([d61ea42](https://github.com/ElshadHu/Aegis/commit/d61ea42d700e022dca0f05d5852c4811a99272ae))
* **lint:** configure eslint-plugin-svelte with TypeScript parser ([0b7d078](https://github.com/ElshadHu/Aegis/commit/0b7d0781879f501d0f77e7c43201db187ea8e2bb))
* **lint:** configure eslint-plugin-svelte with TypeScript parser ([11bd59a](https://github.com/ElshadHu/Aegis/commit/11bd59ad25531a93c5d0d18f48116b393181d911))
* **lint:** replace Map with plain object in agent grouping ([6715d8b](https://github.com/ElshadHu/Aegis/commit/6715d8b2ffe0c10e40c921e8d0fd00033990bf17))
* **lint:** replace Map with plain object in agent grouping ([#99](https://github.com/ElshadHu/Aegis/issues/99)) ([43b8510](https://github.com/ElshadHu/Aegis/commit/43b8510d16952e578a960e214624ea8785f35425))
* **lint:** use SvelteSet for reactive set in App.svelte ([60ac923](https://github.com/ElshadHu/Aegis/commit/60ac9236cfa70a127488d8f89c66150c1d68673a))
* **memory:** add caps to prevAnomalyKeys, knownHandles, eventDedupMap, dnsCache ([3813f30](https://github.com/ElshadHu/Aegis/commit/3813f30eebae22ded1fd8be49e8df34c0fa9bd9d))
* move tray.init to critical path before ready-to-show ([1628a2c](https://github.com/ElshadHu/Aegis/commit/1628a2cc4dfef14680d569b83967ab35af4abf9b))
* platform index test compares export shape instead of function toString (CJS/ESM interop) ([1d54b7f](https://github.com/ElshadHu/Aegis/commit/1d54b7f8b40ad0bdedd6936677b3ca6956daf755))
* platform index test uses function identity comparison compatible with CJS/ESM interop ([3030dac](https://github.com/ElshadHu/Aegis/commit/3030dac34be8a95f00117da0704a8384646366ab))
* port risk scoring rebalance to Svelte + remove legacy files ([f934bc1](https://github.com/ElshadHu/Aegis/commit/f934bc11ff7fb88368971a9acbd02fe6c122dcc1))
* **preload:** return cleanup functions for all IPC listeners ([3d174c5](https://github.com/ElshadHu/Aegis/commit/3d174c513cbe2b4aa78b15b9f3d7f0ef14c99d67))
* radar canvas visibility — increase grid/label/sweep opacity ([dd8dc03](https://github.com/ElshadHu/Aegis/commit/dd8dc03d6ab65d6389d495353dcfe39e4071111d))
* radar canvas visibility — increase grid/label/sweep opacity for dark theme ([06061af](https://github.com/ElshadHu/Aegis/commit/06061af5732bf92c6565c96c489c4e95ca88e22a))
* radar centering + light theme visibility ([2cc0c5b](https://github.com/ElshadHu/Aegis/commit/2cc0c5b051b777b80bf9b24f3db4a382098b4655))
* radar dark background ([079a62e](https://github.com/ElshadHu/Aegis/commit/079a62e28d8efe2e04b11a3f6c7aefb4b16d3792))
* rebalance risk scoring — self-access exemption, dedup, diminishing returns ([f0a0890](https://github.com/ElshadHu/Aegis/commit/f0a0890a8ef87c180312acd60abf8a821b5089d1))
* remove duplicate/wrong author name ([56cb88f](https://github.com/ElshadHu/Aegis/commit/56cb88fb2fac72075fecb3af69d751f19a8ea008))
* remove Event Timeline from Shield tab ([d50c8a6](https://github.com/ElshadHu/Aegis/commit/d50c8a626ea96603022376bfa7a8a90f567cf7c3))
* remove unused path import in anomaly-detector ([63f03e1](https://github.com/ElshadHu/Aegis/commit/63f03e13765390b647d2549ddeab5b9be277f25c))
* remove WSL from agent DB, add event dedup (30s window) ([80afb62](https://github.com/ElshadHu/Aegis/commit/80afb6256577a66e255d0469829906882f1e476d))
* **renderer:** suppress import.meta TS1470 in ipc store ([e65cf4c](https://github.com/ElshadHu/Aegis/commit/e65cf4c49f45986e7a377fa85cb7f7ed543e4d2c))
* replace hardcoded colors with design tokens, update docs ([327f231](https://github.com/ElshadHu/Aegis/commit/327f231fcf6fae351a15ed9ed8b9e2f949497cb0))
* resolve 10 UI bugs from full audit ([3eaed03](https://github.com/ElshadHu/Aegis/commit/3eaed03ef82f651a88ec927996b06a157b799d0a))
* resolve 4 HIGH issues from PR [#37](https://github.com/ElshadHu/Aegis/issues/37) code review ([#41](https://github.com/ElshadHu/Aegis/issues/41)) ([9d33a70](https://github.com/ElshadHu/Aegis/commit/9d33a7072684fec51306b1892dbe4f5096a50273))
* resolve a11y and CSS build warnings ([ea5667e](https://github.com/ElshadHu/Aegis/commit/ea5667e7457755dd7318714591dc344110e43bba))
* resolve black screen in packaged exe (CSP + path fix) ([ea3e786](https://github.com/ElshadHu/Aegis/commit/ea3e78628ac53f9b838dfe0e883e10fd1cfd3c45))
* resolve PR [#52](https://github.com/ElshadHu/Aegis/issues/52) review — CSS dupe, cleanup leak, split demo-pools, add tests ([76479d1](https://github.com/ElshadHu/Aegis/commit/76479d1eb6d83abb6c582d303de2347855dee43c))
* robust JSON extraction for AI threat analysis ([232fcb6](https://github.com/ElshadHu/Aegis/commit/232fcb65e7308004a402993744f8625fb82a0946))
* **scanner:** graceful EPERM handling prevents crash on elevated processes ([59ed6f0](https://github.com/ElshadHu/Aegis/commit/59ed6f05be221797e56704a8e9f9792d50d97c05))
* **security:** catch block fallbacks + navigation lock ([5f9859a](https://github.com/ElshadHu/Aegis/commit/5f9859a18f6c776d7b413dcc0a4ada09392f0486))
* **security:** encrypt API key at rest using Electron safeStorage ([db7b15d](https://github.com/ElshadHu/Aegis/commit/db7b15d86a04b1acf528b6388c2f7781c7e0b34d))
* **security:** encrypt API key at rest using Electron safeStorage ([8dba03c](https://github.com/ElshadHu/Aegis/commit/8dba03c0ed0f6c044df5c2e10a542b25ef5f7c89))
* **security:** explicit sandbox, CSP hardening, symlink protection, timer cleanup ([4e77fcc](https://github.com/ElshadHu/Aegis/commit/4e77fcc2ea8f1efea59dbba2795f3addecbab963))
* **security:** explicit sandbox, CSP hardening, symlink protection, timer cleanup ([52e301d](https://github.com/ElshadHu/Aegis/commit/52e301d49949cfba11246ef9bb8da138038afda6))
* **security:** harden IPC handlers — HTML injection, path traversal, process authorization ([3d123dc](https://github.com/ElshadHu/Aegis/commit/3d123dc399607f371d0ea47a9780b02016606f88))
* **security:** harden IPC handlers — HTML injection, path traversal, process authorization ([c653b75](https://github.com/ElshadHu/Aegis/commit/c653b75bb50e2758f547993188aa427b7168122a))
* **security:** replace swallowed exceptions with console.error fallback ([08acfe1](https://github.com/ElshadHu/Aegis/commit/08acfe19af0c74d82662b36953f6d628de02a77f))
* **security:** restrict BrowserWindow navigation and new-window ([e96a94f](https://github.com/ElshadHu/Aegis/commit/e96a94fa31778fc5acc582c499ac96b248292ae9))
* **security:** sanitize LLM prompt inputs against injection ([cfc3877](https://github.com/ElshadHu/Aegis/commit/cfc38771d9578c556eb595109691d18e4323e15d))
* **security:** sanitize LLM prompt inputs against injection ([75840be](https://github.com/ElshadHu/Aegis/commit/75840be130a9fa4791135f247aeb5467867b201e))
* **security:** tighten CSP from permissive default-src * to strict self-only policy ([c4f195e](https://github.com/ElshadHu/Aegis/commit/c4f195ed9bddb48a9f7eb3c18693b45804f6b017))
* **security:** validate IPC inputs — settings, config import, false positives, regex ([b97de54](https://github.com/ElshadHu/Aegis/commit/b97de545c8b4627d1c8ae219da7445c0d83fd37d))
* **security:** validate IPC inputs — settings, config import, false positives, regex ([7dbf914](https://github.com/ElshadHu/Aegis/commit/7dbf91425a2f1b23733dd285f0d905199ce323e5))
* settings modal — add export/import config buttons ([298d522](https://github.com/ElshadHu/Aegis/commit/298d522764c16060f27b06a51ca71b3934e24442))
* split oversized files, fix bg flash, cleanup, update CLAUDE.md ([ead74d6](https://github.com/ElshadHu/Aegis/commit/ead74d6c11fb143a59a5089714910372a82aa5ae))
* suppress import.meta TS1470 in ipc.ts ([918f4bc](https://github.com/ElshadHu/Aegis/commit/918f4bc1b3f5b8dedb3e997f7b404c0218eaacb5))
* **test:** replace tautological formatBytes tests with boundary and behavioral assertions ([18e1c52](https://github.com/ElshadHu/Aegis/commit/18e1c52255720311de21ea6e23064de2b1d69403))
* **test:** replace tautological formatBytes tests with boundary and behavioral assertions ([70ebc36](https://github.com/ElshadHu/Aegis/commit/70ebc3658776510667c26a384542a306b5afacf2))
* threat analysis JSON parsing, table header overlap, version bump ([cb032c0](https://github.com/ElshadHu/Aegis/commit/cb032c0d9e192cf6ca445d4fbf0990da0f0c6c88))
* tune graph simulation forces and layout (WIP) ([f9a25d9](https://github.com/ElshadHu/Aegis/commit/f9a25d942bd9c089d6a7a648fe2dd74e73d5b27e))
* **ui:** deduplicate agent dropdown with count in brackets ([67e2b20](https://github.com/ElshadHu/Aegis/commit/67e2b20f7c5fe8ca13479903e0c862679b44e74b))
* **ui:** defer ReportsTab rendering to prevent UI freeze ([3c5e3ff](https://github.com/ElshadHu/Aegis/commit/3c5e3fff392c1f14f08157f9e60c92188cf94698))
* **ui:** fix uptime text overflow and pin feed filters (L1, L2) ([6ab41f6](https://github.com/ElshadHu/Aegis/commit/6ab41f688e788594a178c6b19fb02978888b24da))
* **ui:** improve contrast for warning-level readability issues (W1-W4) ([564a32b](https://github.com/ElshadHu/Aegis/commit/564a32b13123cab403be3aa440cd0052601400e0))
* **ui:** layout fixes + skeleton loading states + ReportsTab freeze fix ([49b1e2b](https://github.com/ElshadHu/Aegis/commit/49b1e2b1f11738c2a85f3ae25f578d98f48b0c91))
* **ui:** replace hardcoded rgba colors with design tokens + eslint-plugin-svelte ([cd9d6c7](https://github.com/ElshadHu/Aegis/commit/cd9d6c7a33b989da5ed89ecbb15e1135d5e69dea))
* **ui:** resolve 7 critical contrast issues (WCAG AA) ([a949093](https://github.com/ElshadHu/Aegis/commit/a94909342ac368239800214da135e975b74008eb))
* **ui:** resolve 7 critical contrast issues from visual audit ([c66a4eb](https://github.com/ElshadHu/Aegis/commit/c66a4eb6ebfaae182ebb341e2e76dfc4f93cadd4))
* **ui:** show unique agent count in Total Agents card ([d2b9b73](https://github.com/ElshadHu/Aegis/commit/d2b9b73b3513922c8b4082db23492929e52e34b5))
* **ui:** show unique agent count instead of process count in Total Agents card ([c686fe4](https://github.com/ElshadHu/Aegis/commit/c686fe4d5742733ec1fdf9296f731140cbf508df))
* unset ELECTRON_RUN_AS_NODE in start script for IDE terminal compatibility ([915fe2f](https://github.com/ElshadHu/Aegis/commit/915fe2f501bf7a006e99c46c0e70b40362ff0bea))
* update broken file references in design-system skill ([#100](https://github.com/ElshadHu/Aegis/issues/100)) ([aae8906](https://github.com/ElshadHu/Aegis/commit/aae89069f2a5500fc4f0cabd8df5e5ede154791c))


### Performance

* add depth limits to chokidar watchers (18s-&gt;2s) ([29f6bc1](https://github.com/ElshadHu/Aegis/commit/29f6bc1647e6695c88a0f990efefd8a4959f9646))
* batch PowerShell CWD lookup (54 spawns-&gt;1) ([3ac7132](https://github.com/ElshadHu/Aegis/commit/3ac7132965232bcbcfa1efe9da48374f28e33e4f))
* comprehensive performance optimization (A-J) ([1a32aa6](https://github.com/ElshadHu/Aegis/commit/1a32aa6b987cb49cc5bd959ec948464ba526e166))
* **css:** reduce backdrop-filter from 33 to 5 instances ([ccf0992](https://github.com/ElshadHu/Aegis/commit/ccf0992d940e98fa9b4022d884ee3ff5db7e3860))
* **css:** replace width transitions with transform scaleX ([1d467d9](https://github.com/ElshadHu/Aegis/commit/1d467d940a9060105df53686fc80dda893c7c29a))
* defer file watchers and lazy-load modules for faster startup ([e5eb91f](https://github.com/ElshadHu/Aegis/commit/e5eb91fbbcd0f1941c6677b7d99cb635bed49058))
* defer non-critical module loading until after ready-to-show ([11dbdc0](https://github.com/ElshadHu/Aegis/commit/11dbdc021c78ce8b9d4d10783fcb669fb4a4c52c))
* defer non-critical startup ops phase 2 (+150-400ms) ([40cb31b](https://github.com/ElshadHu/Aegis/commit/40cb31be3fae08d2bef90256f8183f071fac4354))
* **demo:** stagger initial seeding + delay intervals ([#70](https://github.com/ElshadHu/Aegis/issues/70)) ([566cb11](https://github.com/ElshadHu/Aegis/commit/566cb11588c92cd4bc89d6efd1bee6fe95ddb5ee))
* **demo:** stagger initial seeding + delay intervals to prevent startup freeze ([d7adf1e](https://github.com/ElshadHu/Aegis/commit/d7adf1e385790a00a70acb89e808651493160648))
* eliminate dev server fallback on production start (~2s boot improvement) ([683711f](https://github.com/ElshadHu/Aegis/commit/683711f31593fe3aebc1b6946f779835fcc4d41e))
* eliminate tab switch lag — show/hide pattern, IPC batching, enrichedAgents cache ([d4f6a54](https://github.com/ElshadHu/Aegis/commit/d4f6a54c4129f8e70e7cddee5c2e73feeeb25fad))
* fix startup freeze + dead code cleanup + renderer optimizations (120s-&gt;1s) ([5b2382c](https://github.com/ElshadHu/Aegis/commit/5b2382c97ed1c3e0b7d58acbd4ab07928df89c62))
* **ipc:** route stats-update and file-access through existing batchers ([bed7246](https://github.com/ElshadHu/Aegis/commit/bed72466a5c1283fb0ed85b2aa9dcf51a87f8f82))
* lazy module loading + skeleton UI (eliminate perceived startup lag) ([3895a56](https://github.com/ElshadHu/Aegis/commit/3895a56104f76a760d937faf8dca3a88a8cf56b5))
* **main:** replace O(n) filters with running counters in getStats ([e6df4b8](https://github.com/ElshadHu/Aegis/commit/e6df4b824c001e69ab45cd06ce0a73d442935d63))
* pre-build events index to eliminate O(N*M) in AgentCard ([265f671](https://github.com/ElshadHu/Aegis/commit/265f6714ae195be8caaf25113c19e3a7bfeae063))
* reduce IPC flood at startup — chokidar exclusions, warmup ramp-up, network debounce, stats batch 1s ([1a57271](https://github.com/ElshadHu/Aegis/commit/1a57271fb2d6f4f4f0d70bb4b97fe56a959c3bce))
* **renderer:** coalesce scan-batch store updates into single tick ([35c444b](https://github.com/ElshadHu/Aegis/commit/35c444b1b02122885650a397d8bc380cae0d3679))
* replace sync fs reads with in-memory counters in loggers ([083a193](https://github.com/ElshadHu/Aegis/commit/083a1934e871402fe6d759412867081d29b5864d))
* **rules:** add category index for O(1) rule lookup by category ([b552fb4](https://github.com/ElshadHu/Aegis/commit/b552fb4ec8a27e1c2a84da3656bd778e35bc3ca3))
* skip store updates in hidden tabs — active prop propagation ([0fa30fa](https://github.com/ElshadHu/Aegis/commit/0fa30fa67d01710e44fd33166a45ac94488476ef))
* skip store updates in hidden tabs — active prop propagation ([ec4b77e](https://github.com/ElshadHu/Aegis/commit/ec4b77e0cc0b367ef7c9de9a37d9b090f8adbbdc))


### Code Refactoring

* DRY platform code + align test API contracts ([#43](https://github.com/ElshadHu/Aegis/issues/43)) ([a77b14d](https://github.com/ElshadHu/Aegis/commit/a77b14d0493a0d3070ca3373faf595df015fb601))
* extract IPC handlers from main.js + fresh screenshot ([bcc6839](https://github.com/ElshadHu/Aegis/commit/bcc683938beeb4c39f9e3fa233036f61cafeaabb))
* integrate VisTimeline into main dashboard ([75fe69d](https://github.com/ElshadHu/Aegis/commit/75fe69d9bf3de96f0004f0690095151dfd353e7c))
* merge Feed into Activity tab ([1f1a84b](https://github.com/ElshadHu/Aegis/commit/1f1a84b7bb8915167bb73211ebec0282536d4d09))
* remove 12 dead exports, 11 dead CSS vars, @types/electron ([dc33f95](https://github.com/ElshadHu/Aegis/commit/dc33f9500633c1ac7bba937f595cdb08b1b8446a))
* remove 17 dead IPC channels ([9b68a84](https://github.com/ElshadHu/Aegis/commit/9b68a845a40f519de8f0249ead9fb4546c8a42ad))
* **renderer:** consolidate 1s timers into shared tick store ([caf0ae6](https://github.com/ElshadHu/Aegis/commit/caf0ae6249c6546759a0742032cbaff854808ad3))
* **renderer:** consolidate effects, add rAF cleanup ([220c587](https://github.com/ElshadHu/Aegis/commit/220c5879e8b53b536059194a3df26fdb3d17d3b3))
* **renderer:** migrate 4 store files to TypeScript ([11caf43](https://github.com/ElshadHu/Aegis/commit/11caf43d1a256d22ef49c861c025e3783870b9a9))
* **renderer:** migrate ipc store to TypeScript ([af92a0c](https://github.com/ElshadHu/Aegis/commit/af92a0cd640257bc07d8b210964da9cbfc2c6f6c))
* **renderer:** migrate risk store to TypeScript ([a162123](https://github.com/ElshadHu/Aegis/commit/a1621235a6100270b42a973556c45f98bc38d73b))
* **renderer:** migrate theme store to TypeScript ([1d61582](https://github.com/ElshadHu/Aegis/commit/1d615823d00f08366d0c90832ef56d512a61c97c))
* **renderer:** migrate toast store to TypeScript ([2436c1a](https://github.com/ElshadHu/Aegis/commit/2436c1ac4d515ab12e0ff3055ab9a8aa6c97da73))
* simplify — align all components to M3 tokens ([b02a41f](https://github.com/ElshadHu/Aegis/commit/b02a41f006b935baae90a708a55d5aa8800861a0))
* simplify AgentCard — extract gradeToColor, consolidate pidAction ([1dea62a](https://github.com/ElshadHu/Aegis/commit/1dea62ab091623ba429ff3f283e8b50ebb5f0278))
* simplify steps 12-15 ([501f88e](https://github.com/ElshadHu/Aegis/commit/501f88e1f4b7bdf3a7bb9b431529960de206719a))
* split 4 large files into focused modules ([3c696fb](https://github.com/ElshadHu/Aegis/commit/3c696fb83e5cef28ea535f1458b6e023f290c760))
* split 4 large files into focused modules ([b91f8fb](https://github.com/ElshadHu/Aegis/commit/b91f8fb685baea76772b316a0a1ce687939e3198)), closes [#3](https://github.com/ElshadHu/Aegis/issues/3)
* split AgentDatabaseCrud.svelte into sub-components ([ace8f81](https://github.com/ElshadHu/Aegis/commit/ace8f81384e6b5a916eb9a09928cad45b3a2aa05))
* split GroupedFeed.svelte into sub-components ([e96429c](https://github.com/ElshadHu/Aegis/commit/e96429cf76a22e94b8b98bc41275d725ced65c57))
* split Timeline.svelte into sub-components ([cfcae99](https://github.com/ElshadHu/Aegis/commit/cfcae99ace23b00835f858e6a45e6360fabb9d8a))
* update tab navigation (Stats + Feed) ([da900f2](https://github.com/ElshadHu/Aegis/commit/da900f21409e2faeab92210dbaae3c0812374a9b))


### Documentation

* add /loop tasks and new skills to CLAUDE.md ([5c2fb21](https://github.com/ElshadHu/Aegis/commit/5c2fb2173fad46f3b2ccb44f8db3b487ea1ddfe9))
* add AGENTS.md for AI agent contributors ([7e20e38](https://github.com/ElshadHu/Aegis/commit/7e20e38ee50dd38f97aa8fa7b2169c9fffde6f21))
* add animated demo GIF to README ([#34](https://github.com/ElshadHu/Aegis/issues/34)) ([98840b7](https://github.com/ElshadHu/Aegis/commit/98840b7e60e566b7d2dcc986c4d7142350e63352))
* add CHANGELOG.md (Keep a Changelog format) ([49da167](https://github.com/ElshadHu/Aegis/commit/49da1671cb794022e03c23385496ce8176e7009d))
* add CI badge to README ([0e420e0](https://github.com/ElshadHu/Aegis/commit/0e420e0966f5b69c649aa8c589a500a14546c6c9))
* add competitor comparison table ([5b0bcf3](https://github.com/ElshadHu/Aegis/commit/5b0bcf3c3ddfc82a8d395df6d7409534afd974c0))
* add development guide with tech stack best practices ([2c3a9ff](https://github.com/ElshadHu/Aegis/commit/2c3a9ffd10393b2438377f2b4997feb5b342b2be))
* add new skills to aegis-context reference ([a4e621e](https://github.com/ElshadHu/Aegis/commit/a4e621e99a7a587c705ff892ed80e99ca9c99212))
* add ROADMAP.md with master plan ([193c717](https://github.com/ElshadHu/Aegis/commit/193c717cb1faf2dc51917f68034a63929800a629))
* add security audit report and social preview assets ([9176620](https://github.com/ElshadHu/Aegis/commit/91766201bde10eed6b3042709e861e6604dc8a89))
* add social preview template ([7df62a2](https://github.com/ElshadHu/Aegis/commit/7df62a2bae0b8fd9b783389b40cfc7a76d1fe7f7))
* add social preview template ([249308e](https://github.com/ElshadHu/Aegis/commit/249308e429676c604d63af55a20fa7212b2e5179))
* add SUPPORT.md, label good-first-issues ([f7e3292](https://github.com/ElshadHu/Aegis/commit/f7e32922769802a02c3377f873e2493e5c64bb4f))
* add test groups breakdown table to README ([ec1df0b](https://github.com/ElshadHu/Aegis/commit/ec1df0bde124398433c2b4115986db85b6665571))
* add travisbreaks to contributors, update agent count to 106 ([36a0d53](https://github.com/ElshadHu/Aegis/commit/36a0d53dc7d9e193d175138f624094d137a58a96))
* add trimmed demo GIF for README ([cd48910](https://github.com/ElshadHu/Aegis/commit/cd4891072a7baaaec97df53914890cecbae99a54))
* add trimmed demo GIF to README ([#34](https://github.com/ElshadHu/Aegis/issues/34)) ([e4d28ac](https://github.com/ElshadHu/Aegis/commit/e4d28ac6906cf7ce3be84b31790da00d1d4aab19))
* add TypeScript guidelines to CONTRIBUTING.md ([b911eb3](https://github.com/ElshadHu/Aegis/commit/b911eb3163437501424f31352a23fed869442499))
* add TypeScript rules to CLAUDE.md ([07fa950](https://github.com/ElshadHu/Aegis/commit/07fa950a51bfb9b97f74f7e5c0baddc5059cc231))
* add UI screenshots for Activity, Rules, Reports, Settings ([0085b60](https://github.com/ElshadHu/Aegis/commit/0085b60730bc074c1597a652ea9e568bb89a6b08))
* add UI screenshots for all tabs ([#34](https://github.com/ElshadHu/Aegis/issues/34)) ([a403aea](https://github.com/ElshadHu/Aegis/commit/a403aeaf6eb06eaa85f54f7abc95bc11bf6565c1))
* add UI screenshots to README ([9311a71](https://github.com/ElshadHu/Aegis/commit/9311a71181d2b051caabf2ba17c2a74d35e00236))
* bump supported version to 0.3.x in SECURITY.md ([dc348b8](https://github.com/ElshadHu/Aegis/commit/dc348b83455aef2b006b4ca02afd6a38517bc022))
* document demo mode in README Quick Start section ([947991b](https://github.com/ElshadHu/Aegis/commit/947991ba15340d0de5db6d4d1bb1b0aba41407c9))
* document demo mode in README Quick Start section ([e125a6c](https://github.com/ElshadHu/Aegis/commit/e125a6c6c8bf3728b2ac4fbb642336b7d5f52a66)), closes [#76](https://github.com/ElshadHu/Aegis/issues/76)
* Fancy UI screenshots + capture script ([#67](https://github.com/ElshadHu/Aegis/issues/67)) ([399af5b](https://github.com/ElshadHu/Aegis/commit/399af5b6e7d4257dec07fb92a9386c660498f284))
* fix all placeholders, outdated info, and garbled UTF-8 for public launch ([d6846e9](https://github.com/ElshadHu/Aegis/commit/d6846e955d3cfd99c4af72d2dec1378bb1300b20))
* fix case-sensitive dir name in CONTRIBUTING.md ([8f30909](https://github.com/ElshadHu/Aegis/commit/8f3090946040fae703755a937499eac622c78535))
* fix stack description — Svelte 5, not vanilla JS ([6403094](https://github.com/ElshadHu/Aegis/commit/64030942109ea7b02f779d9a9e9f0757cd091b2b))
* optimize aegis-context description + update context after PR [#95](https://github.com/ElshadHu/Aegis/issues/95) ([17d574d](https://github.com/ElshadHu/Aegis/commit/17d574dded821b3fafff5b67ab869c7dcfd31254))
* overhaul Download section — honest install, release table, fix 404 GIF ([9be38ca](https://github.com/ElshadHu/Aegis/commit/9be38ca496d04c4bdd0d2ad4321f94cde4450f0a))
* polish README for Dev.to launch — tighten badges, update test count to 489, clean changelog ([afc5f52](https://github.com/ElshadHu/Aegis/commit/afc5f52c22e1de2aca95e0004f11839e8163b33d))
* polish README for public launch ([88f23c6](https://github.com/ElshadHu/Aegis/commit/88f23c64b0a5296b88e04ce4a81f75d570a21715))
* polish README, fresh screenshots, update contributors and changelog ([3c6d41b](https://github.com/ElshadHu/Aegis/commit/3c6d41b15d2ab7ddb53e3d032e04bee09669271c))
* post-release badges, links, counts update for v0.3.1-alpha ([9e908a7](https://github.com/ElshadHu/Aegis/commit/9e908a76fd4c1cb8682407116e54ac9ec6b7b727))
* pre-release update all documentation for v0.3.1-alpha ([93d19ae](https://github.com/ElshadHu/Aegis/commit/93d19ae6484fe13c04174ec73fd7654be7980c81))
* README download section + rebuild installer with radar fix ([97a106e](https://github.com/ElshadHu/Aegis/commit/97a106e242f2faec477f5c4c4d1aaf586bf28c51))
* README, CONTRIBUTING, SECURITY, ARCHITECTURE — Independent AI Oversight Layer ([f6eb185](https://github.com/ElshadHu/Aegis/commit/f6eb185c0a1234363946e09b17fae158189a2715))
* README, CONTRIBUTING, SECURITY, ARCHITECTURE for open-source launch ([e023be6](https://github.com/ElshadHu/Aegis/commit/e023be6254770ece6a4c42a812babdd75af06628))
* **readme:** add OpenClaw context and concrete threat framing ([fca3163](https://github.com/ElshadHu/Aegis/commit/fca316387048e7c5201f0d95cbf7f4715527a8e1))
* **readme:** add Quick Demo section and set GitHub topics ([07fb06a](https://github.com/ElshadHu/Aegis/commit/07fb06ac7844548360eaf3274cd7ac8bc150a7da))
* **readme:** add star CTA and enterprise contact section ([89bb3b1](https://github.com/ElshadHu/Aegis/commit/89bb3b13927d807dfbb6ca59552e63715d96e702))
* **readme:** add v0.8.0-alpha to release history ([dbc7c21](https://github.com/ElshadHu/Aegis/commit/dbc7c21b72160e5e6394cdca08dca6412f92321d))
* **readme:** add v0.8.0-alpha to release history, fix CSP description ([8e04eb6](https://github.com/ElshadHu/Aegis/commit/8e04eb63be5012d9d5d120df6235361127162a0b))
* **readme:** update Star History chart to timeline format ([20bb034](https://github.com/ElshadHu/Aegis/commit/20bb034a18c4b172f317dac69cc63583f4b2c6f2))
* **readme:** update Star History chart to timeline format ([415c791](https://github.com/ElshadHu/Aegis/commit/415c79147189a641b30a841c58a518d94bfdeffa))
* **security:** update supported versions to 0.8.x ([2adba1a](https://github.com/ElshadHu/Aegis/commit/2adba1a2e52d4c4a906f61f821e7cc20eedd4c1e))
* sync context files for v0.4.0-alpha — update counts, version, limits ([0000389](https://github.com/ElshadHu/Aegis/commit/00003892efee2b5e68ef4b63f3fa690466692614))
* sync context files for v0.5.0-alpha ([1d8934d](https://github.com/ElshadHu/Aegis/commit/1d8934df9c90e2a34e7147ba9bf31b0f1248d19d))
* sync context files for v0.5.0-alpha ([1daea76](https://github.com/ElshadHu/Aegis/commit/1daea76fb571a88ae831b6c20c9d99c978e770d1))
* sync test counts and versions across all documentation ([43cae91](https://github.com/ElshadHu/Aegis/commit/43cae9173708d5986675a1e0fe50298929ccca00))
* sync test counts and versions across all documentation ([c0331cc](https://github.com/ElshadHu/Aegis/commit/c0331cc40f32c033aef1f67d3c769a09ed311fda))
* update AGENTS.md — 106 agent signatures ([17dfeff](https://github.com/ElshadHu/Aegis/commit/17dfeff4253cc14b97431b067912a6b7ebb6dcf5))
* update AGENTS.md + CLAUDE.md for llm-runtime-detector, cli.js, 98 agents ([be40cc8](https://github.com/ElshadHu/Aegis/commit/be40cc83e43012214b29ca2069c6b9243b6b1ae5))
* update all metadata to v0.10.0-alpha ([82a8a8a](https://github.com/ElshadHu/Aegis/commit/82a8a8a28fcd9b645be9157fadb80317b994cfaf))
* update all metadata to v0.10.0-alpha (707 tests, 23 modules, 43 components) ([a08b08f](https://github.com/ElshadHu/Aegis/commit/a08b08f9b48f028bd11da1cba0a38170670c1105))
* update ARCHITECTURE.md — 106 agents, 49 IPC channels, add toast store ([bbe729b](https://github.com/ElshadHu/Aegis/commit/bbe729b43318b8da930edba36ad1f7fb3780a1c4))
* update ARCHITECTURE.md to match Svelte codebase and current features ([8b95afa](https://github.com/ElshadHu/Aegis/commit/8b95afa1e3813d4c9d457e7c00ca6033162bcbc1))
* update audit docs — add resolution status tables for v0.3.0-alpha ([fa9539c](https://github.com/ElshadHu/Aegis/commit/fa9539c33392c93c750c4fa312a7ed2d83d7a9a7))
* update CHANGELOG.md — add Unreleased section, fix counts to 106 agents 436 tests ([c776adb](https://github.com/ElshadHu/Aegis/commit/c776adb1cf1543ca140cfc6fe6a340d929d2ed6b))
* update CLAUDE.md — 106 agents, 429 tests ([b8ecee1](https://github.com/ElshadHu/Aegis/commit/b8ecee1f54a0e56001f938ab9665cf021d2722c8))
* update CLAUDE.md — 436 tests, 19 modules, 32 components, 39 IPC channels ([c55e73c](https://github.com/ElshadHu/Aegis/commit/c55e73ceeeabe60261977a60ef767c4381c6bf25))
* update context files for P5-B.0 completion, boot perf fix, and TS workflow ([84d6dea](https://github.com/ElshadHu/Aegis/commit/84d6dea29686e955f050d9130a3acf93533234c2))
* update context for Stats tab and tab cleanup ([957e742](https://github.com/ElshadHu/Aegis/commit/957e742886da8c5fc74a941405e4af9e15cb8ea2))
* update project context to v0.8.2-alpha (v16) ([f3d6287](https://github.com/ElshadHu/Aegis/commit/f3d62875cd06ff4049d2dcdc485282b3c00af1bf))
* update project context to v0.8.2-alpha (v16) ([bab4d7e](https://github.com/ElshadHu/Aegis/commit/bab4d7e6fff5273feca04b4ce5c77f2080160e69))
* update README for v0.2.0-alpha Svelte stack ([0fa5fde](https://github.com/ElshadHu/Aegis/commit/0fa5fdefaf910523ad4def92426692061bbad8e2))
* update README for v0.7.0-alpha (568 tests, YAML rulesets, Fancy UI) ([1bdc885](https://github.com/ElshadHu/Aegis/commit/1bdc8857c0347eb87f3c74805cf5caa17083752d))
* update README for v0.7.0-alpha (568 tests, YAML rulesets, Fancy UI) ([9cae813](https://github.com/ElshadHu/Aegis/commit/9cae81358fbdda53cceb851f0acb21df0f36f3c0))
* update README.md — 106 agents, 436 tests, fix template links, add demo mode ([1e6ec3a](https://github.com/ElshadHu/Aegis/commit/1e6ec3af269ba979a9b7133dcd6e3d6b81b53506))
* update screenshot for launch ([84f20b8](https://github.com/ElshadHu/Aegis/commit/84f20b84b9dc71e2ef0e124cfa4d4c2f813d3c7c))
* update screenshots to v0.10.0 Fancy UI ([28835d6](https://github.com/ElshadHu/Aegis/commit/28835d68fa573f4abe33ba7ce0416d1a77e11e38))
* update screenshots to v0.10.0 Fancy UI ([224fcd3](https://github.com/ElshadHu/Aegis/commit/224fcd356055d9e6f5a94fface5badc5e6d8f7b8))
* update screenshots with Fancy UI v0.5.0 ([710585c](https://github.com/ElshadHu/Aegis/commit/710585c4f9106fcc14aaa35d24e9ac9abf7f7971))
* update screenshots with Fancy UI v0.7.0, add capture script, fix gitignore ([3c2030c](https://github.com/ElshadHu/Aegis/commit/3c2030cc79bde00cb99282cd9f3f90b76836371c))
* update test count to 489, add Skills section to CLAUDE.md ([c95c608](https://github.com/ElshadHu/Aegis/commit/c95c608e6d47989fa3fc50f4e37b26090ec0a055))
* update test counts and changelog for EPERM handling ([1c0d75b](https://github.com/ElshadHu/Aegis/commit/1c0d75ba01bda6efb4d93707d8db09ce4c8dd195))
* update test counts and changelog for IPC batching ([719f69d](https://github.com/ElshadHu/Aegis/commit/719f69d862af8ddf401e7055d56aff354714de82))
* update test counts and changelog for startup perf fix ([7997c0b](https://github.com/ElshadHu/Aegis/commit/7997c0bd2920299b0d5728ff19c0a803298e86d1))

## [0.10.0-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.9.1-alpha...aegis-v0.10.0-alpha) (2026-03-09)


### Features

* Command Palette (Ctrl+K) — fuzzy search, keyboard nav, 22 commands ([994e691](https://github.com/antropos17/Aegis/commit/994e69194b73b9127bad21d2c8f7a66c69f36d59))
* **command-palette:** add command palette store ([7adce84](https://github.com/antropos17/Aegis/commit/7adce843c673da088f5e8953fdabc851093010d5))
* **command-palette:** add CommandPalette UI component ([78b4eba](https://github.com/antropos17/Aegis/commit/78b4ebaeebe461810f0a48dc2337776d40789763))
* **command-palette:** add fuzzy search with tests ([068cf2b](https://github.com/antropos17/Aegis/commit/068cf2b32eff0fc87c2788f7e23f19c279448eed))
* **command-palette:** add types and command registry ([b80c242](https://github.com/antropos17/Aegis/commit/b80c242effa9c0c84cfed45a398f3ce705354f4e))
* **command-palette:** integrate with App and wire actions ([a238836](https://github.com/antropos17/Aegis/commit/a2388366f9912c53d51a44ccfc4c1ede24833d5d))


### Bug Fixes

* **ci:** resolve svelte-check, eslint errors for command palette and ipc ([78da6b3](https://github.com/antropos17/Aegis/commit/78da6b3f553acdd820983b2b1d826b299288c155))
* **renderer:** suppress import.meta TS1470 in ipc store ([e65cf4c](https://github.com/antropos17/Aegis/commit/e65cf4c49f45986e7a377fa85cb7f7ed543e4d2c))
* **security:** explicit sandbox, CSP hardening, symlink protection, timer cleanup ([4e77fcc](https://github.com/antropos17/Aegis/commit/4e77fcc2ea8f1efea59dbba2795f3addecbab963))
* **security:** explicit sandbox, CSP hardening, symlink protection, timer cleanup ([52e301d](https://github.com/antropos17/Aegis/commit/52e301d49949cfba11246ef9bb8da138038afda6))
* **security:** harden IPC handlers — HTML injection, path traversal, process authorization ([3d123dc](https://github.com/antropos17/Aegis/commit/3d123dc399607f371d0ea47a9780b02016606f88))
* **security:** harden IPC handlers — HTML injection, path traversal, process authorization ([c653b75](https://github.com/antropos17/Aegis/commit/c653b75bb50e2758f547993188aa427b7168122a))
* **security:** sanitize LLM prompt inputs against injection ([cfc3877](https://github.com/antropos17/Aegis/commit/cfc38771d9578c556eb595109691d18e4323e15d))
* **security:** sanitize LLM prompt inputs against injection ([75840be](https://github.com/antropos17/Aegis/commit/75840be130a9fa4791135f247aeb5467867b201e))
* **security:** validate IPC inputs — settings, config import, false positives, regex ([b97de54](https://github.com/antropos17/Aegis/commit/b97de545c8b4627d1c8ae219da7445c0d83fd37d))
* **security:** validate IPC inputs — settings, config import, false positives, regex ([7dbf914](https://github.com/antropos17/Aegis/commit/7dbf91425a2f1b23733dd285f0d905199ce323e5))
* suppress import.meta TS1470 in ipc.ts ([918f4bc](https://github.com/antropos17/Aegis/commit/918f4bc1b3f5b8dedb3e997f7b404c0218eaacb5))


### Code Refactoring

* **renderer:** migrate 4 store files to TypeScript ([11caf43](https://github.com/antropos17/Aegis/commit/11caf43d1a256d22ef49c861c025e3783870b9a9))
* **renderer:** migrate ipc store to TypeScript ([af92a0c](https://github.com/antropos17/Aegis/commit/af92a0cd640257bc07d8b210964da9cbfc2c6f6c))
* **renderer:** migrate risk store to TypeScript ([a162123](https://github.com/antropos17/Aegis/commit/a1621235a6100270b42a973556c45f98bc38d73b))
* **renderer:** migrate theme store to TypeScript ([1d61582](https://github.com/antropos17/Aegis/commit/1d615823d00f08366d0c90832ef56d512a61c97c))
* **renderer:** migrate toast store to TypeScript ([2436c1a](https://github.com/antropos17/Aegis/commit/2436c1ac4d515ab12e0ff3055ab9a8aa6c97da73))

## [0.9.1-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.9.0-alpha...aegis-v0.9.1-alpha) (2026-03-09)


### Bug Fixes

* deduplicate agent dropdown entries ([#98](https://github.com/antropos17/Aegis/issues/98)) ([f0b6c19](https://github.com/antropos17/Aegis/commit/f0b6c1978fcd8cd18a57bb91cbf45f84eac8fdd4))
* **docs:** update broken file references in design-system skill ([5071384](https://github.com/antropos17/Aegis/commit/50713848d262ff8b4f342dcc4de544f9e5db362c))
* **lint:** replace Map with plain object in agent grouping ([6715d8b](https://github.com/antropos17/Aegis/commit/6715d8b2ffe0c10e40c921e8d0fd00033990bf17))
* **lint:** replace Map with plain object in agent grouping ([#99](https://github.com/antropos17/Aegis/issues/99)) ([43b8510](https://github.com/antropos17/Aegis/commit/43b8510d16952e578a960e214624ea8785f35425))
* **ui:** deduplicate agent dropdown with count in brackets ([67e2b20](https://github.com/antropos17/Aegis/commit/67e2b20f7c5fe8ca13479903e0c862679b44e74b))
* update broken file references in design-system skill ([#100](https://github.com/antropos17/Aegis/issues/100)) ([aae8906](https://github.com/antropos17/Aegis/commit/aae89069f2a5500fc4f0cabd8df5e5ede154791c))


### Performance

* **rules:** add category index for O(1) rule lookup by category ([b552fb4](https://github.com/antropos17/Aegis/commit/b552fb4ec8a27e1c2a84da3656bd778e35bc3ca3))


### Documentation

* optimize aegis-context description + update context after PR [#95](https://github.com/antropos17/Aegis/issues/95) ([17d574d](https://github.com/antropos17/Aegis/commit/17d574dded821b3fafff5b67ab869c7dcfd31254))

## [0.9.0-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.8.2-alpha...aegis-v0.9.0-alpha) (2026-03-08)


### Features

* add ci-monitor skill for CI watching and repo health ([bc5c860](https://github.com/antropos17/Aegis/commit/bc5c860fcd51a10836def814a5a4ff7a5afa6764))
* add pr-monitor and ci-monitor skills with /loop support ([#91](https://github.com/antropos17/Aegis/issues/91)) ([2766c10](https://github.com/antropos17/Aegis/commit/2766c109ccc167cabe61e265d175187eb9723676))
* add pr-monitor skill for PR triage and /loop monitoring ([77b959d](https://github.com/antropos17/Aegis/commit/77b959d0f3aa2a8b61f01a67fb2dbf1e3ef5cc88))


### Bug Fixes

* **security:** catch block fallbacks + navigation lock ([5f9859a](https://github.com/antropos17/Aegis/commit/5f9859a18f6c776d7b413dcc0a4ada09392f0486))
* **security:** encrypt API key at rest using Electron safeStorage ([db7b15d](https://github.com/antropos17/Aegis/commit/db7b15d86a04b1acf528b6388c2f7781c7e0b34d))
* **security:** encrypt API key at rest using Electron safeStorage ([8dba03c](https://github.com/antropos17/Aegis/commit/8dba03c0ed0f6c044df5c2e10a542b25ef5f7c89))
* **security:** replace swallowed exceptions with console.error fallback ([08acfe1](https://github.com/antropos17/Aegis/commit/08acfe19af0c74d82662b36953f6d628de02a77f))
* **security:** restrict BrowserWindow navigation and new-window ([e96a94f](https://github.com/antropos17/Aegis/commit/e96a94fa31778fc5acc582c499ac96b248292ae9))


### Documentation

* add /loop tasks and new skills to CLAUDE.md ([5c2fb21](https://github.com/antropos17/Aegis/commit/5c2fb2173fad46f3b2ccb44f8db3b487ea1ddfe9))
* add new skills to aegis-context reference ([a4e621e](https://github.com/antropos17/Aegis/commit/a4e621e99a7a587c705ff892ed80e99ca9c99212))
* add security audit report and social preview assets ([9176620](https://github.com/antropos17/Aegis/commit/91766201bde10eed6b3042709e861e6604dc8a89))
* update project context to v0.8.2-alpha (v16) ([f3d6287](https://github.com/antropos17/Aegis/commit/f3d62875cd06ff4049d2dcdc485282b3c00af1bf))
* update project context to v0.8.2-alpha (v16) ([bab4d7e](https://github.com/antropos17/Aegis/commit/bab4d7e6fff5273feca04b4ce5c77f2080160e69))

## [0.8.2-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.8.1-alpha...aegis-v0.8.2-alpha) (2026-03-08)


### Bug Fixes

* **test:** replace tautological formatBytes tests with boundary and behavioral assertions ([18e1c52](https://github.com/antropos17/Aegis/commit/18e1c52255720311de21ea6e23064de2b1d69403))
* **test:** replace tautological formatBytes tests with boundary and behavioral assertions ([70ebc36](https://github.com/antropos17/Aegis/commit/70ebc3658776510667c26a384542a306b5afacf2))

## [0.8.1-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.8.0-alpha...aegis-v0.8.1-alpha) (2026-03-08)


### Documentation

* document demo mode in README Quick Start section ([947991b](https://github.com/antropos17/Aegis/commit/947991ba15340d0de5db6d4d1bb1b0aba41407c9))
* document demo mode in README Quick Start section ([e125a6c](https://github.com/antropos17/Aegis/commit/e125a6c6c8bf3728b2ac4fbb642336b7d5f52a66)), closes [#76](https://github.com/antropos17/Aegis/issues/76)
* **readme:** add v0.8.0-alpha to release history ([dbc7c21](https://github.com/antropos17/Aegis/commit/dbc7c21b72160e5e6394cdca08dca6412f92321d))
* **readme:** add v0.8.0-alpha to release history, fix CSP description ([8e04eb6](https://github.com/antropos17/Aegis/commit/8e04eb63be5012d9d5d120df6235361127162a0b))
* **readme:** update Star History chart to timeline format ([20bb034](https://github.com/antropos17/Aegis/commit/20bb034a18c4b172f317dac69cc63583f4b2c6f2))
* **readme:** update Star History chart to timeline format ([415c791](https://github.com/antropos17/Aegis/commit/415c79147189a641b30a841c58a518d94bfdeffa))

## [0.8.0-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.7.0-alpha...aegis-v0.8.0-alpha) (2026-03-05)


### Features

* **demo:** enrich demo — 12 agents, 25 events, informative banner ([#69](https://github.com/antropos17/Aegis/issues/69)) ([bd01ac8](https://github.com/antropos17/Aegis/commit/bd01ac87b8888446e77dac223b33cbc937b5b461))
* **demo:** enrich demo with 12 agents, 25 events, informative banner ([a03b7b0](https://github.com/antropos17/Aegis/commit/a03b7b0b4112aac7da5efc58f17566ff56f36a86))
* **demo:** polish all tabs for browser demo — mock data for Rules, Reports, Settings ([d18d95a](https://github.com/antropos17/Aegis/commit/d18d95a17a3b35511c31fe2a4e26a516ce2526d0))
* **demo:** polish all tabs for browser demo ([#68](https://github.com/antropos17/Aegis/issues/68)) ([e41fae2](https://github.com/antropos17/Aegis/commit/e41fae21a63ccded456c5ebac477b897eaba343e))
* **ui:** add skeleton loading states for ActivityTab and RulesTab ([30bbe1b](https://github.com/antropos17/Aegis/commit/30bbe1bab1552414faa4d514b53063e4efda09cb))


### Bug Fixes

* **ipc:** add try-catch to all async ipc handlers ([dc22669](https://github.com/antropos17/Aegis/commit/dc2266922c2b862171ccb6b369d6317164a1f6b6))
* **lint:** use SvelteSet for reactive set in App.svelte ([a4b0cfd](https://github.com/antropos17/Aegis/commit/a4b0cfd6ddded14ffa35124a298fa5024bdfd72f))
* **memory:** add caps to prevAnomalyKeys, knownHandles, eventDedupMap, dnsCache ([b5cde3b](https://github.com/antropos17/Aegis/commit/b5cde3bd72ce1d04672b3cc1c1b92f4f7c61c42b))
* **preload:** return cleanup functions for all IPC listeners ([e0ecd76](https://github.com/antropos17/Aegis/commit/e0ecd765131d5ddadaf2cc4cee7eb18cda258973))
* **ui:** defer ReportsTab rendering to prevent UI freeze ([5f3e03f](https://github.com/antropos17/Aegis/commit/5f3e03f5cc6b72fc35fb8284127c3e9da656ee8c))
* **ui:** fix uptime text overflow and pin feed filters (L1, L2) ([c033572](https://github.com/antropos17/Aegis/commit/c033572605e444714d15b52450e6188cfa854b5a))
* **ui:** improve contrast for warning-level readability issues (W1-W4) ([ee2bf38](https://github.com/antropos17/Aegis/commit/ee2bf389cedd0c960edb624e4feac734fef4bb5b))
* **ui:** layout fixes + skeleton loading states + ReportsTab freeze fix ([858951f](https://github.com/antropos17/Aegis/commit/858951fec96b63eed684764bdd691d561e5fe561))
* **ui:** resolve 7 critical contrast issues (WCAG AA) ([f889c55](https://github.com/antropos17/Aegis/commit/f889c555f4808662f3840db49ae4fa2c34172cf3))
* **ui:** resolve 7 critical contrast issues from visual audit ([e635975](https://github.com/antropos17/Aegis/commit/e6359758e4d79e359110e6ca91f07e9feb440f5d))


### Performance

* comprehensive performance optimization (A-J) ([aaadf08](https://github.com/antropos17/Aegis/commit/aaadf08119cee59d6c1544d17109d06a3e19d718))
* **css:** reduce backdrop-filter from 33 to 5 instances ([77e5374](https://github.com/antropos17/Aegis/commit/77e5374f68baf818b4f60bafd8535f32b2088a85))
* **css:** replace width transitions with transform scaleX ([e63377d](https://github.com/antropos17/Aegis/commit/e63377db57308c830e3f34da963a84374fc2e83e))
* **demo:** stagger initial seeding + delay intervals ([#70](https://github.com/antropos17/Aegis/issues/70)) ([f709d72](https://github.com/antropos17/Aegis/commit/f709d727d4e2290f67cda5dd43cdb752fd4f4b2d))
* **demo:** stagger initial seeding + delay intervals to prevent startup freeze ([c2731f6](https://github.com/antropos17/Aegis/commit/c2731f658c0c8b802716f5543e722df8c4a787ec))
* **ipc:** route stats-update and file-access through existing batchers ([3c1bb4c](https://github.com/antropos17/Aegis/commit/3c1bb4c73e5a2e6b89a882a3419e01ac648aea9f))
* **main:** replace O(n) filters with running counters in getStats ([09ba8e6](https://github.com/antropos17/Aegis/commit/09ba8e6de632725d637d6dcb759195c7b32f8be6))
* **renderer:** coalesce scan-batch store updates into single tick ([58b6827](https://github.com/antropos17/Aegis/commit/58b6827f7ef0f1d9b081ca64d0332d76c3ce5257))


### Code Refactoring

* **renderer:** consolidate 1s timers into shared tick store ([2c46303](https://github.com/antropos17/Aegis/commit/2c46303b346e8a61d3aff8e45feed0c2e7b29503))
* **renderer:** consolidate effects, add rAF cleanup ([7eed9f2](https://github.com/antropos17/Aegis/commit/7eed9f263bf11a215ddea43e2d56bbaded73d7ac))


### Documentation

* Fancy UI screenshots + capture script ([#67](https://github.com/antropos17/Aegis/issues/67)) ([4aa089c](https://github.com/antropos17/Aegis/commit/4aa089ca739f81ab5da9420e06d6dd8e7a84ab16))
* overhaul Download section — honest install, release table, fix 404 GIF ([8297c57](https://github.com/antropos17/Aegis/commit/8297c5740fb5efd701da1f49f044750f7108b8a8))
* sync test counts and versions across all documentation ([ed63d87](https://github.com/antropos17/Aegis/commit/ed63d876a5f19adf159422f581f9a17976b2851a))
* sync test counts and versions across all documentation ([02c3d18](https://github.com/antropos17/Aegis/commit/02c3d18255a057cf5de7bcc3da03bac81cf2702d))
* update README for v0.7.0-alpha (568 tests, YAML rulesets, Fancy UI) ([e533a5c](https://github.com/antropos17/Aegis/commit/e533a5c1d4339b74f80bff016435ff17c0f49ada))
* update README for v0.7.0-alpha (568 tests, YAML rulesets, Fancy UI) ([8fe3e4b](https://github.com/antropos17/Aegis/commit/8fe3e4b47956e6d2f53c850fee9cf429253dee51))
* update screenshots with Fancy UI v0.5.0 ([d04cd99](https://github.com/antropos17/Aegis/commit/d04cd99a9f72d108213bb7bdf4f419f27ed6a53b))
* update screenshots with Fancy UI v0.7.0, add capture script, fix gitignore ([b8acd46](https://github.com/antropos17/Aegis/commit/b8acd460bb17974f3ce56ded7999001f23374514))

## [0.7.0-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.6.0-alpha...aegis-v0.7.0-alpha) (2026-03-04)


### Features

* **rules:** add IPC endpoints + hot-reload watcher for YAML rules [R4] ([e986358](https://github.com/antropos17/Aegis/commit/e986358783d865d88ee8d8890aef5e9f4bd700dd))
* **rules:** add YAML rule loader with JSON Schema validation [R1] ([db2b496](https://github.com/antropos17/Aegis/commit/db2b496f7776a5417c3f5965fdfdb299532aade6))
* **rules:** migrate all SENSITIVE_RULES to typed YAML rulesets [R2] ([20fce07](https://github.com/antropos17/Aegis/commit/20fce07682642ab2c02ed40b5e8eb3c23fb08a23))
* **rules:** wire rule-loader into file-watcher, deprecate SENSITIVE_RULES [R3] ([74500dd](https://github.com/antropos17/Aegis/commit/74500dd76c59bc3edb2080946c49c72297a554e3))
* **rules:** YAML rulesets with hot-reload and IPC (R1-R4) ([3c9072f](https://github.com/antropos17/Aegis/commit/3c9072f8eb81d8df1dae86c23dc74aff8c68aa9d))

## [0.6.0-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.5.0-alpha...aegis-v0.6.0-alpha) (2026-03-03)


### Features

* **ui:** add skeleton loading for pre-scan state ([cf02d81](https://github.com/antropos17/Aegis/commit/cf02d81742a2d3b83aff44085311dd233c5932ba))


### Bug Fixes

* cleanup  timers and reactive loop in Timeline ([8637f5a](https://github.com/antropos17/Aegis/commit/8637f5a43415f98bf8b7c6c6dbc0cc2e40891e53))
* guard getStats against undefined scanner during early IPC ([eba8091](https://github.com/antropos17/Aegis/commit/eba80919665769f923e1b0fd9ee2734a1becdbbd))
* move tray.init to critical path before ready-to-show ([e9972ad](https://github.com/antropos17/Aegis/commit/e9972adfa03af0dc59fdacb08dff268acf4b5b2d))


### Performance

* add depth limits to chokidar watchers (18s-&gt;2s) ([9c5812f](https://github.com/antropos17/Aegis/commit/9c5812faf011bd6730b4fca57a646d73ecc5c5aa))
* batch PowerShell CWD lookup (54 spawns-&gt;1) ([cb414b1](https://github.com/antropos17/Aegis/commit/cb414b158c90a85ee1805c7e6cbef6b6987cea7b))
* defer non-critical module loading until after ready-to-show ([0d1d22e](https://github.com/antropos17/Aegis/commit/0d1d22e2d9dd300e5f2df6c812064a499529254a))
* fix startup freeze + dead code cleanup + renderer optimizations (120s-&gt;1s) ([09bb6ca](https://github.com/antropos17/Aegis/commit/09bb6caf351cc133c3ad92a84de2707ee34b3a73))
* lazy module loading + skeleton UI (eliminate perceived startup lag) ([e3d0880](https://github.com/antropos17/Aegis/commit/e3d088091a434d00f4f1230fcaba5850c8a638fc))
* pre-build events index to eliminate O(N*M) in AgentCard ([12e4772](https://github.com/antropos17/Aegis/commit/12e4772b10455c34368838fd579d426e8c1cab52))
* replace sync fs reads with in-memory counters in loggers ([47a926f](https://github.com/antropos17/Aegis/commit/47a926ff3e823e9727514ba3e05a7bcc8b63c2e3))


### Code Refactoring

* remove 12 dead exports, 11 dead CSS vars, @types/electron ([c7b5f8b](https://github.com/antropos17/Aegis/commit/c7b5f8bd8693298a2b80b4fb603259bae609a58a))
* remove 17 dead IPC channels ([f1555bf](https://github.com/antropos17/Aegis/commit/f1555bf0eaf8813e992d36b7fdb1c444c2bf50ed))


### Documentation

* sync context files for v0.5.0-alpha ([c28b7f7](https://github.com/antropos17/Aegis/commit/c28b7f7e5dd52eca24c9a16177ef5cc476b7088a))
* sync context files for v0.5.0-alpha ([e4d89c9](https://github.com/antropos17/Aegis/commit/e4d89c97fe93a1fa521a10be6d102bf2621a3f4b))

## [0.5.0-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.4.0-alpha...aegis-v0.5.0-alpha) (2026-03-03)


### Features

* add vis-timeline and d3 dependencies ([652917c](https://github.com/antropos17/Aegis/commit/652917c6d0f6b23fe2123ae4b0e6e37c489edab6))
* AgentGraph component with force-directed layout ([1d14ccd](https://github.com/antropos17/Aegis/commit/1d14ccd6458b685373942858787da9a6de128209))
* AgentStatsPanel — sortable agent statistics table ([6108ed5](https://github.com/antropos17/Aegis/commit/6108ed5bee594fb13a84b10b1ebe7a7e460b9b23))
* EventFeed — live terminal-style event stream ([5b1b61a](https://github.com/antropos17/Aegis/commit/5b1b61aeb00f316ddd28b09c1258c67c05ca04f2))
* fancy aegis UI redesign v0.5.0-alpha (F1.1-F4.3) ([f5c461c](https://github.com/antropos17/Aegis/commit/f5c461c534f64e64939b946fb3dd34e71fdf6076))
* move Timeline and Graph to separate tabs with bug fixes ([acc99b1](https://github.com/antropos17/Aegis/commit/acc99b15f1ac2c2c4aad7a47ade468a92e730ae9))
* Stats tab, cleanup Timeline/Feed, Follow in Activity (#timeline-graph) ([752a6d8](https://github.com/antropos17/Aegis/commit/752a6d8b1208a4a80c3390c31f608529a92565fd))
* **ui:** add background atmosphere effect [F4.3] ([6306d19](https://github.com/antropos17/Aegis/commit/6306d19824e22f974630672c727bad857f62a760))
* **ui:** add design system tokens and local fonts [F1.1] ([7c6fec6](https://github.com/antropos17/Aegis/commit/7c6fec620827861149df89961a3c0e2e8bb85012))
* **ui:** add feed item animations and severity colors [F3.1] ([fdb2544](https://github.com/antropos17/Aegis/commit/fdb2544f7d66a1d78467e1abcb917febf39062e6))
* **ui:** add footer mini charts for CPU and memory [F3.2] ([3a1fa6d](https://github.com/antropos17/Aegis/commit/3a1fa6d0d50d801f853205a390843733dba860b8))
* **ui:** add risk ring SVG gauge with glow and pulse [F4.1] ([fe08cad](https://github.com/antropos17/Aegis/commit/fe08cad1dff7818a2d3326d1d6a5be2d15d80d47))
* **ui:** add sparkline SVG component [F2.1] ([b29e24a](https://github.com/antropos17/Aegis/commit/b29e24a04e2a0f0ebdd7653c66df514f6f5aa478))
* **ui:** add summary cards component with animated counters and trend arrows [F1.3] ([909e7b3](https://github.com/antropos17/Aegis/commit/909e7b349da2fd9f57a17773e56627255266c412))
* **ui:** add summary cards component with threat metrics [F1.3] ([42f7e76](https://github.com/antropos17/Aegis/commit/42f7e76a103f52832e5a4f3bd0cfc2e1cf158236))
* **ui:** add tab switch transitions [F3.3] ([01d4c2d](https://github.com/antropos17/Aegis/commit/01d4c2d02b426b613e70c153eec400dfdaa38e51))
* **ui:** add trust badge component [F2.2] ([60ef2ed](https://github.com/antropos17/Aegis/commit/60ef2edf0b1e82c03044ebf58eb8ff54df7de151))
* **ui:** redesign agent card with sparkline, badge, spotlight [F2.3] ([3ccd1b5](https://github.com/antropos17/Aegis/commit/3ccd1b5fa0270edaebdb9c913b49ec8b2c30989f))
* **ui:** redesign Shield tab with bento grid layout [F1.2] ([06b876d](https://github.com/antropos17/Aegis/commit/06b876d5ceda1d76531480d3ba326bc1bbe837e4))
* **ui:** typography pass — consistent font tokens across all components [F4.2] ([cbf8446](https://github.com/antropos17/Aegis/commit/cbf844656eaeced81b24fae22a55db53c4217b14))
* VisTimeline component with agent groups and event items ([b7adbe0](https://github.com/antropos17/Aegis/commit/b7adbe0e3abd8a0bdab8654a44c55f01d861d172))


### Bug Fixes

* clean up tab navigation ([8893d84](https://github.com/antropos17/Aegis/commit/8893d84fd517f07ee64b0aa20e6f1fb4f66f6271))
* convert svelte components to JSDoc style for eslint compatibility ([13dd271](https://github.com/antropos17/Aegis/commit/13dd2716002539aad6af341f8b57dfcef153f166))
* **lint:** configure eslint-plugin-svelte with TypeScript parser ([45e4343](https://github.com/antropos17/Aegis/commit/45e434356ba5f430dfd9f4a1cbbb5d8adaabac08))
* **lint:** configure eslint-plugin-svelte with TypeScript parser ([f91c721](https://github.com/antropos17/Aegis/commit/f91c72122054f140bba41af754d6591a4f7dbb49))
* remove Event Timeline from Shield tab ([a58144c](https://github.com/antropos17/Aegis/commit/a58144cd2c2542b53c44343b9ab920b4061dcf4e))
* tune graph simulation forces and layout (WIP) ([a8a8773](https://github.com/antropos17/Aegis/commit/a8a8773eaeaa6027d2b816230f9abc9eefc9bc3f))


### Code Refactoring

* integrate VisTimeline into main dashboard ([b84d734](https://github.com/antropos17/Aegis/commit/b84d7344e9d825931bfbf78689e1aa8f04984cc4))
* merge Feed into Activity tab ([6acb3e7](https://github.com/antropos17/Aegis/commit/6acb3e7f5c2c26baff9a8851dd606bda48ff680c))
* update tab navigation (Stats + Feed) ([33a4d70](https://github.com/antropos17/Aegis/commit/33a4d7069f7d142ecf36c5a25abd4225220b7f3c))


### Documentation

* polish README for Dev.to launch — tighten badges, update test count to 489, clean changelog ([5b5d9f4](https://github.com/antropos17/Aegis/commit/5b5d9f491a2174a1bf417361d85aa5d3cafd5e66))
* sync context files for v0.4.0-alpha — update counts, version, limits ([cc1a362](https://github.com/antropos17/Aegis/commit/cc1a362327d1de682451f78d030970d619e6f1d3))
* update context for Stats tab and tab cleanup ([ab82f90](https://github.com/antropos17/Aegis/commit/ab82f90000783e37171999518ca95d908633edc8))

## [0.4.0-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.3.1-alpha...aegis-v0.4.0-alpha) (2026-03-03)


### Features

* add JSDoc type annotations using shared type definitions ([a737a08](https://github.com/antropos17/Aegis/commit/a737a084de64bc95aa6298ea1df719c9e6eb1601))
* add TypeScript type definitions for all data structures ([f36fea9](https://github.com/antropos17/Aegis/commit/f36fea9d33da676ee4215eb8b0f2d4427a173c77))
* redesign AgentCard, FeedFilters, and Timeline UI ([d177e68](https://github.com/antropos17/Aegis/commit/d177e687a3c23cf9019b7f7a05cf216dc5773b1f))
* TypeScript infrastructure — tsconfig, 34 types, ESLint TS, ESM test migration, JSDoc annotations (P5-B.0) ([c480a73](https://github.com/antropos17/Aegis/commit/c480a73d4dacaf7d13db859ff0b2142a24ecd3cc))


### Bug Fixes

* add missing await in ipc-handlers.test.js:346 ([0570652](https://github.com/antropos17/Aegis/commit/0570652f4fec77a72f2e8900395146f0e9ac7179))
* add PID validation to POSIX platform functions and IPC boundary ([b0fc17b](https://github.com/antropos17/Aegis/commit/b0fc17b560cfab55c70aed5264203312a9004cd9))
* deduplicate agents in dropdowns, cards, and reports table ([73b55a1](https://github.com/antropos17/Aegis/commit/73b55a1e3e7c71f33f1b49be4e985e99b2675483))
* platform index test compares export shape instead of function toString (CJS/ESM interop) ([fa75cb4](https://github.com/antropos17/Aegis/commit/fa75cb442b6cc5c9bee409929b72de380db8a26f))
* platform index test uses function identity comparison compatible with CJS/ESM interop ([5690d5d](https://github.com/antropos17/Aegis/commit/5690d5d2991306b9f19f4f1e572f21b7f98d4b7f))
* resolve a11y and CSS build warnings ([6a91fff](https://github.com/antropos17/Aegis/commit/6a91fff12b57339fc90c69a9f707d8afd34402e7))


### Performance

* eliminate dev server fallback on production start (~2s boot improvement) ([dbe466e](https://github.com/antropos17/Aegis/commit/dbe466e146179792057f02e32b934ebddbfbd348))
* eliminate tab switch lag — show/hide pattern, IPC batching, enrichedAgents cache ([c29f593](https://github.com/antropos17/Aegis/commit/c29f5935b2d6022f6dc7a2d3b243ec33b9508396))
* reduce IPC flood at startup — chokidar exclusions, warmup ramp-up, network debounce, stats batch 1s ([8106bee](https://github.com/antropos17/Aegis/commit/8106beedfd1a0b56e48943e1d695423414cd110d))
* skip store updates in hidden tabs — active prop propagation ([b2cfde9](https://github.com/antropos17/Aegis/commit/b2cfde9ef4eef8a10c2ec37ae885f3fca26735b7))
* skip store updates in hidden tabs — active prop propagation ([fc50527](https://github.com/antropos17/Aegis/commit/fc50527961837886a47b4766e7bdef772d9c6b3d))


### Code Refactoring

* split AgentDatabaseCrud.svelte into sub-components ([a3bb506](https://github.com/antropos17/Aegis/commit/a3bb506d1398a0ffc182092f2b7a5fbd6808ee7e))
* split GroupedFeed.svelte into sub-components ([e71d24f](https://github.com/antropos17/Aegis/commit/e71d24f6a470d471e055f1cd05a44fe8a670c6c3))
* split Timeline.svelte into sub-components ([36b1999](https://github.com/antropos17/Aegis/commit/36b1999184efba2fa278f180cf133b49c9d5d79f))


### Documentation

* add TypeScript guidelines to CONTRIBUTING.md ([0d8345a](https://github.com/antropos17/Aegis/commit/0d8345a924adbe42ef28d545383d9a3fd7b2132a))
* add TypeScript rules to CLAUDE.md ([cd75102](https://github.com/antropos17/Aegis/commit/cd75102c284147ffe415b67af8c13d5bfce37791))
* post-release badges, links, counts update for v0.3.1-alpha ([940cded](https://github.com/antropos17/Aegis/commit/940cded42a52b44d888eda29b5a838d834ba0d60))
* update context files for P5-B.0 completion, boot perf fix, and TS workflow ([38c2180](https://github.com/antropos17/Aegis/commit/38c2180bd85fc1901e8e6a27672248f8017888bf))
* update test count to 489, add Skills section to CLAUDE.md ([384bcc0](https://github.com/antropos17/Aegis/commit/384bcc00f39e07749f5e6ab06088ccc101b83b57))

## [0.3.1-alpha](https://github.com/antropos17/Aegis/compare/aegis-v0.3.0-alpha...aegis-v0.3.1-alpha) (2026-03-02)


### Features

* **a11y:** add keyboard shortcuts and accessibility improvements ([#51](https://github.com/antropos17/Aegis/issues/51)) ([8a996e4](https://github.com/antropos17/Aegis/commit/8a996e407508352ad3d15d4acb15fbfa0bd56505)), closes [#17](https://github.com/antropos17/Aegis/issues/17)
* activity feed process grouping with expandable details ([c573b69](https://github.com/antropos17/Aegis/commit/c573b69c4cc62dde1ba86f5df0f70130b8972e63))
* AEGIS v0.1.0-alpha — AI Agent Privacy Shield ([a398591](https://github.com/antropos17/Aegis/commit/a3985910faaa41426d822c6464d427a4a6d3d53e))
* **agents:** add 8 new agent signatures to database ([#50](https://github.com/antropos17/Aegis/issues/50)) ([484353f](https://github.com/antropos17/Aegis/commit/484353fb20bf39e3be0cea1f311b44e4dc91ba0e))
* **ci:** automated releases with release-please ([#58](https://github.com/antropos17/Aegis/issues/58)) ([7120694](https://github.com/antropos17/Aegis/commit/7120694a785413b55b3471dc3d55b646bb59b86c))
* clickable file paths (reveal in explorer) + copyable network addresses ([e0fd69c](https://github.com/antropos17/Aegis/commit/e0fd69c4f3b55c44b438235c938a5146f918037b))
* **community:** false positive marking, agent DB contribution, scan badge (#P4.15-17) ([73851fc](https://github.com/antropos17/Aegis/commit/73851fc5f760252087aa1df8e451a9dceb1394cb))
* container/VM + local LLM detection (88→95 agents) ([dbfa1c1](https://github.com/antropos17/Aegis/commit/dbfa1c10bd853149b58dfb8efff69d87a758d38f))
* **core:** HTTP scoring, user-agent detection, API indicator, HW accel toggle (#P4.11-14) ([e7d3958](https://github.com/antropos17/Aegis/commit/e7d39584dfe8e9ba3eaa461f0e1d76774c8038f4))
* cross-platform support (macOS/Linux), unified UI scaling, and comprehensive test suite ([#37](https://github.com/antropos17/Aegis/issues/37)) ([4abfe6f](https://github.com/antropos17/Aegis/commit/4abfe6fe436a1383a3e47fe14f988cd8d4aab067))
* **demo:** add browser-only demo mode and development guide (closes [#10](https://github.com/antropos17/Aegis/issues/10)) ([d8e682d](https://github.com/antropos17/Aegis/commit/d8e682dc5bdb995f991d3eb53327cb3205d16da7))
* **demo:** add browser-only demo mode with simulated agent data ([1269416](https://github.com/antropos17/Aegis/commit/12694167c2ff5164897227f5ebfc0222cf20a944)), closes [#10](https://github.com/antropos17/Aegis/issues/10)
* **detection:** add local LLM runtime detection (Ollama, LM Studio, vLLM, llama.cpp) — 97 agents ([84a0e99](https://github.com/antropos17/Aegis/commit/84a0e99894d5f03268c2632b22460c5c85f3c55c))
* expand agent database with Qwen-Agent, CodeWhisperer aliases, Gemini CLI patterns ([#46](https://github.com/antropos17/Aegis/issues/46)) ([d589c3f](https://github.com/antropos17/Aegis/commit/d589c3f207d6b5f88648fb28352f2730e4d4f71f))
* **file-watcher:** add configurable ignore list for .git/node_modules ([#11](https://github.com/antropos17/Aegis/issues/11)) ([febc626](https://github.com/antropos17/Aegis/commit/febc626055879d33435f326c197de815b3c5ceb3))
* **i18n:** add internationalization support with English base ([b967a74](https://github.com/antropos17/Aegis/commit/b967a7416745415c2efe2aa5199beeb0afc0899d))
* **i18n:** add internationalization support with English base ([#53](https://github.com/antropos17/Aegis/issues/53)) ([8b82929](https://github.com/antropos17/Aegis/commit/8b829296f0a8ae1b074f0daccdd815bf6a33fb1c))
* **i18n:** add internationalization support with English base ([#53](https://github.com/antropos17/Aegis/issues/53)) ([71ea7d3](https://github.com/antropos17/Aegis/commit/71ea7d322a1f62541b4b67f191ed42fe6f3ef3fb))
* integrate LLM runtime detection into scan pipeline + CLI JSON output (--scan-json) ([2ae6b02](https://github.com/antropos17/Aegis/commit/2ae6b02b878a7532e033159a3b11eaaef3eb0dd7))
* **ipc:** add event batching to prevent UI freeze on high-frequency events ([48063cd](https://github.com/antropos17/Aegis/commit/48063cd586d016b27ad28a57b830f9825575e06c))
* multi-dimensional scoring, LLM runtime detection, CLI ([d28fa3b](https://github.com/antropos17/Aegis/commit/d28fa3b0a3458674b574d666e3e8f8c971b943f6))
* Phase 1 — AI agent config file protection (Hudson Rock threat vector) ([3936c50](https://github.com/antropos17/Aegis/commit/3936c501823c2b8aa8d79a27d6ea3bebbaf419bc))
* Phase 2 — behavioral anomaly detection with baseline deviation alerts ([ddb9e8c](https://github.com/antropos17/Aegis/commit/ddb9e8c25d4cc9c59f8951b89a0b568230b19b29))
* Phase 3 — AI-powered threat analysis via Anthropic API ([3af65c5](https://github.com/antropos17/Aegis/commit/3af65c5694f0692be5b4ab0978f4ae1887684009))
* Phase 4+5 — real-time timeline, dashboard metrics, persistent audit logging ([a332209](https://github.com/antropos17/Aegis/commit/a332209792296aa417d22179d746ddea60415961))
* **scoring:** multi-dimensional anomaly scoring (network/fs/process/baseline) ([26d3e64](https://github.com/antropos17/Aegis/commit/26d3e647861f739564078952a8cd03a32418b2d9))
* show unique agent count vs process count in header and reports ([#55](https://github.com/antropos17/Aegis/issues/55)) ([0a57d45](https://github.com/antropos17/Aegis/commit/0a57d452654461b8b38b42043ca63475e740c48e)), closes [#53](https://github.com/antropos17/Aegis/issues/53)
* solar system radar with lightning effects ([407b061](https://github.com/antropos17/Aegis/commit/407b06165364df0a5df24374cef53fa0a550cb22))
* toast notification system ([#15](https://github.com/antropos17/Aegis/issues/15)) ([11fec75](https://github.com/antropos17/Aegis/commit/11fec756be1cd3d7f71ed89d1ceaca9b97111820))
* **ui:** copy PID, relative time, path truncation, autoscroll (#P4.1-5) ([922fdbd](https://github.com/antropos17/Aegis/commit/922fdbd88b99d7160a5255cc919a7c0ed66f42a0))
* **ui:** threat flash, hotkeys, open location, OOM protect, zip export (#P4.6-10) ([be898a2](https://github.com/antropos17/Aegis/commit/be898a241c0fed5ff5b9db89f27035a4e0215f10))


### Bug Fixes

* address critical issues from PR [#37](https://github.com/antropos17/Aegis/issues/37) code review ([3ab4fac](https://github.com/antropos17/Aegis/commit/3ab4fac6c541c485331d8c5bde6dc7ae0d45e29f))
* correct author name ([921f2d2](https://github.com/antropos17/Aegis/commit/921f2d26f737300fbe2e2a730840ad3728b1c47d))
* critical issues from PR [#37](https://github.com/antropos17/Aegis/issues/37) code review ([f43a7e9](https://github.com/antropos17/Aegis/commit/f43a7e97156da3f6d3adf6af3b1ef8788f904f38))
* **docs:** update test counts, productName, lint rule ([235f493](https://github.com/antropos17/Aegis/commit/235f493a534cac749e5d0190b28e43ddae455a24))
* group agent cards by name, show PIDs inside expand ([c7b5800](https://github.com/antropos17/Aegis/commit/c7b58004b50d333a33313e26ed8d85d2f67f3764))
* integrate annotateWorkingDirs into periodic and startup scan pipelines ([#44](https://github.com/antropos17/Aegis/issues/44)) ([72a3022](https://github.com/antropos17/Aegis/commit/72a30229e1afc6b681dd1ad268f75efea0999169)), closes [#2](https://github.com/antropos17/Aegis/issues/2)
* lazy init settings/baselines path — resolve app.getPath crash on startup ([8ca7817](https://github.com/antropos17/Aegis/commit/8ca78177c40cc02cd10c068876bd5d3ccb176011))
* port risk scoring rebalance to Svelte + remove legacy files ([207eb5c](https://github.com/antropos17/Aegis/commit/207eb5c623923bef06b55e2f9cc4ac566c9eeb94))
* radar canvas visibility — increase grid/label/sweep opacity ([052af52](https://github.com/antropos17/Aegis/commit/052af5220f92062d1a7bd25e2a8306fd0e8a5472))
* radar canvas visibility — increase grid/label/sweep opacity for dark theme ([72980fb](https://github.com/antropos17/Aegis/commit/72980fb4960c47e864668e147d72bc6421cc82c3))
* radar centering + light theme visibility ([07511f8](https://github.com/antropos17/Aegis/commit/07511f8821e5684d7477d8b6a995b1203d0c5a6d))
* radar dark background ([2e5403a](https://github.com/antropos17/Aegis/commit/2e5403a764a85b7a0871d7cc540e6e2cf24491bc))
* rebalance risk scoring — self-access exemption, dedup, diminishing returns ([054ff8b](https://github.com/antropos17/Aegis/commit/054ff8baca086802ce1b2cd4526395b3f5c73201))
* remove duplicate/wrong author name ([9afe1a2](https://github.com/antropos17/Aegis/commit/9afe1a2547faa7ad76bd42a3321e23e04d3f4894))
* remove unused path import in anomaly-detector ([950677a](https://github.com/antropos17/Aegis/commit/950677a28c78a1fadc1c4c15dc850235e13d2906))
* remove WSL from agent DB, add event dedup (30s window) ([7b1b5cf](https://github.com/antropos17/Aegis/commit/7b1b5cf2680951b3b45f7e47224b0b89be8d0be6))
* replace hardcoded colors with design tokens, update docs ([1cd9945](https://github.com/antropos17/Aegis/commit/1cd9945d10b3d338ab1023c42e53d739fbe781b8))
* resolve 10 UI bugs from full audit ([4607c9b](https://github.com/antropos17/Aegis/commit/4607c9b58cfe687c28a057e96a078022924ac514))
* resolve 4 HIGH issues from PR [#37](https://github.com/antropos17/Aegis/issues/37) code review ([#41](https://github.com/antropos17/Aegis/issues/41)) ([700486c](https://github.com/antropos17/Aegis/commit/700486c72ce5948a9aa39cee3f9a11235b9ca8db))
* resolve black screen in packaged exe (CSP + path fix) ([c42839b](https://github.com/antropos17/Aegis/commit/c42839bbac70c0a2b55773f9fba43088eb748eb0))
* resolve PR [#52](https://github.com/antropos17/Aegis/issues/52) review — CSS dupe, cleanup leak, split demo-pools, add tests ([1ed2237](https://github.com/antropos17/Aegis/commit/1ed22376720f8686274059c2f4cac2fe4797e98c))
* robust JSON extraction for AI threat analysis ([40a5930](https://github.com/antropos17/Aegis/commit/40a5930c766567caf5e9cf27f602b49202d748db))
* **scanner:** graceful EPERM handling prevents crash on elevated processes ([c42a483](https://github.com/antropos17/Aegis/commit/c42a483c1dc7be7e5d065cd134222d40949bac00))
* settings modal — add export/import config buttons ([25ff634](https://github.com/antropos17/Aegis/commit/25ff634e96f937582d2d98eab9f5ae9a6adc6de4))
* split oversized files, fix bg flash, cleanup, update CLAUDE.md ([e089e4b](https://github.com/antropos17/Aegis/commit/e089e4b9dc4242b3857eff38d80ad04ff24cb660))
* threat analysis JSON parsing, table header overlap, version bump ([577ff7c](https://github.com/antropos17/Aegis/commit/577ff7c586aa6ec33ece445fac69b98a6b431968))
* **ui:** replace hardcoded rgba colors with design tokens + eslint-plugin-svelte ([566f251](https://github.com/antropos17/Aegis/commit/566f2512f21b3cff17522f8d1e2537c284217e7c))
* unset ELECTRON_RUN_AS_NODE in start script for IDE terminal compatibility ([ee4b65a](https://github.com/antropos17/Aegis/commit/ee4b65abafc890b7792ba1d6335c96f0d1888833))


### Performance

* defer file watchers and lazy-load modules for faster startup ([e6a87cd](https://github.com/antropos17/Aegis/commit/e6a87cdebc7e39535d5f8c4e77ece847715fe104))
* defer non-critical startup ops phase 2 (+150-400ms) ([4390ca3](https://github.com/antropos17/Aegis/commit/4390ca3456754c6d8edeea6902b868870c07444d))


### Code Refactoring

* DRY platform code + align test API contracts ([#43](https://github.com/antropos17/Aegis/issues/43)) ([6cb45b7](https://github.com/antropos17/Aegis/commit/6cb45b7b9a3613ae6277d28c3a3d5237adfbe9bc))
* extract IPC handlers from main.js + fresh screenshot ([1e75bbb](https://github.com/antropos17/Aegis/commit/1e75bbb52783f1d8f920a4729010beaa38fef872))
* simplify — align all components to M3 tokens ([c968e23](https://github.com/antropos17/Aegis/commit/c968e236c10e76b9a606307188c1ae46fcd29987))
* simplify AgentCard — extract gradeToColor, consolidate pidAction ([1db102d](https://github.com/antropos17/Aegis/commit/1db102d26e530acd888a6fb49bb5ab53441ed570))
* simplify steps 12-15 ([09e60a5](https://github.com/antropos17/Aegis/commit/09e60a54c34ffe9c1ecc9c9bbd596a7b340328a5))
* split 4 large files into focused modules ([578c490](https://github.com/antropos17/Aegis/commit/578c49096a7f907d1a4368c3663aa36d6ee08048))
* split 4 large files into focused modules ([d6fccff](https://github.com/antropos17/Aegis/commit/d6fccff24048dad643fd3d620d6b090e4e253e92)), closes [#3](https://github.com/antropos17/Aegis/issues/3)


### Documentation

* add AGENTS.md for AI agent contributors ([4fa07f1](https://github.com/antropos17/Aegis/commit/4fa07f14b7a959e7f72c6bd63129b9779ad7b4f6))
* add animated demo GIF to README ([#34](https://github.com/antropos17/Aegis/issues/34)) ([dc8c97a](https://github.com/antropos17/Aegis/commit/dc8c97acbb0d26a73300fa875ed34567f2cf5ad0))
* add CHANGELOG.md (Keep a Changelog format) ([220596e](https://github.com/antropos17/Aegis/commit/220596efbf3810a7d1ab8193f3a4206bdb8836b6))
* add CI badge to README ([8c1b8ef](https://github.com/antropos17/Aegis/commit/8c1b8ef10cfa3d3a4349d859e4199db833c6e6e2))
* add competitor comparison table ([cf452dd](https://github.com/antropos17/Aegis/commit/cf452dd72814a82cba5018145ad3ce8093333bf2))
* add development guide with tech stack best practices ([988c48d](https://github.com/antropos17/Aegis/commit/988c48d32295dda9588167cd0fc09a22cbe22658))
* add ROADMAP.md with master plan ([df67dee](https://github.com/antropos17/Aegis/commit/df67dee5d46b5eba9a910f67757a615de14a1270))
* add SUPPORT.md, label good-first-issues ([b4d1d85](https://github.com/antropos17/Aegis/commit/b4d1d85ea0046183cd7593e118d08e561ee3cf36))
* add test groups breakdown table to README ([0093b1c](https://github.com/antropos17/Aegis/commit/0093b1c2d43b88b6a4495763a734042ec4aa8858))
* add travisbreaks to contributors, update agent count to 106 ([e8ccaf0](https://github.com/antropos17/Aegis/commit/e8ccaf0645785830d33d4608f8850da01589c942))
* add trimmed demo GIF for README ([7c08bea](https://github.com/antropos17/Aegis/commit/7c08bea219f1cb8821a3f1aee54984724e46b3e7))
* add trimmed demo GIF to README ([#34](https://github.com/antropos17/Aegis/issues/34)) ([138da08](https://github.com/antropos17/Aegis/commit/138da08eebadc109ff0ce30cd30156ae582451ec))
* add UI screenshots for Activity, Rules, Reports, Settings ([d934722](https://github.com/antropos17/Aegis/commit/d9347227b1a580a9746a72fac55efb685ceb6522))
* add UI screenshots for all tabs ([#34](https://github.com/antropos17/Aegis/issues/34)) ([7214196](https://github.com/antropos17/Aegis/commit/72141961670a6a4b05d1f985c942d45af09b83b0))
* add UI screenshots to README ([419a386](https://github.com/antropos17/Aegis/commit/419a3863fac5e2a382e51f2b7431a0dff3b76f2e))
* bump supported version to 0.3.x in SECURITY.md ([40e3f32](https://github.com/antropos17/Aegis/commit/40e3f323740e20083d71e3b37a867431dd9bc07c))
* fix all placeholders, outdated info, and garbled UTF-8 for public launch ([28bce5a](https://github.com/antropos17/Aegis/commit/28bce5ac74be18f1290d4f77624f7d52c70dbd02))
* fix case-sensitive dir name in CONTRIBUTING.md ([9f36bb2](https://github.com/antropos17/Aegis/commit/9f36bb26a97e9008ff480db20acf0d83ba25b43a))
* fix stack description — Svelte 5, not vanilla JS ([0fc5ca2](https://github.com/antropos17/Aegis/commit/0fc5ca2c5dd0d5f264bc6d1c31219e8b86e858af))
* polish README for public launch ([f07d79e](https://github.com/antropos17/Aegis/commit/f07d79ec2520470b91dfa4cff78ea767bce9e123))
* polish README, fresh screenshots, update contributors and changelog ([1470407](https://github.com/antropos17/Aegis/commit/1470407d649914a5acad0d65c3a4cb8e1cf8cabe))
* pre-release update all documentation for v0.3.1-alpha ([bb4a8e1](https://github.com/antropos17/Aegis/commit/bb4a8e1829c0f96a639f5cd7b4a51da7875a95f4))
* README download section + rebuild installer with radar fix ([d948897](https://github.com/antropos17/Aegis/commit/d9488977dfc559d7b51505950c448b37523ff8a6))
* README, CONTRIBUTING, SECURITY, ARCHITECTURE — Independent AI Oversight Layer ([e276229](https://github.com/antropos17/Aegis/commit/e276229d2aaa6bf64729d6a42a57863ef015a3a6))
* README, CONTRIBUTING, SECURITY, ARCHITECTURE for open-source launch ([7df67c2](https://github.com/antropos17/Aegis/commit/7df67c26c1ed3527f285d4872f40ee1a338a9e8b))
* update AGENTS.md — 106 agent signatures ([713ba5a](https://github.com/antropos17/Aegis/commit/713ba5aec9a708d9ef7828238d26d00f28a27460))
* update AGENTS.md + CLAUDE.md for llm-runtime-detector, cli.js, 98 agents ([b2b7805](https://github.com/antropos17/Aegis/commit/b2b78055c6f17d9adca2de025f440d4155545a14))
* update ARCHITECTURE.md — 106 agents, 49 IPC channels, add toast store ([e0cdb8b](https://github.com/antropos17/Aegis/commit/e0cdb8bf7692b49b8ce1cb0f762733390a8bc448))
* update ARCHITECTURE.md to match Svelte codebase and current features ([4506a51](https://github.com/antropos17/Aegis/commit/4506a514380119adad8d4253a2613e81885dfe69))
* update audit docs — add resolution status tables for v0.3.0-alpha ([822104e](https://github.com/antropos17/Aegis/commit/822104ed2ef493277fed8859a7434f0d7e796526))
* update CHANGELOG.md — add Unreleased section, fix counts to 106 agents 436 tests ([2bf6267](https://github.com/antropos17/Aegis/commit/2bf62678cdcc84634d53fa10407f76dc1fc1035b))
* update CLAUDE.md — 106 agents, 429 tests ([964fd8d](https://github.com/antropos17/Aegis/commit/964fd8dc11c86aba02a4dd8322428209ad22503d))
* update CLAUDE.md — 436 tests, 19 modules, 32 components, 39 IPC channels ([c608122](https://github.com/antropos17/Aegis/commit/c6081224cda34e09b7e1516bfba1910127d8a0e2))
* update memory-bank notes ([708cfb2](https://github.com/antropos17/Aegis/commit/708cfb2489613a7f9b9a24fa6e9b4d31cdc7053b))
* update progress after github push ([326b6dd](https://github.com/antropos17/Aegis/commit/326b6dda565bcc053907a85bae633d9d359d1e27))
* update README for v0.2.0-alpha Svelte stack ([447f9d0](https://github.com/antropos17/Aegis/commit/447f9d073b3fda6f8f77d1cdeceebb8fb315e08c))
* update README.md — 106 agents, 436 tests, fix template links, add demo mode ([c3d7e7d](https://github.com/antropos17/Aegis/commit/c3d7e7dd5edfc69504c5aad501aa042fd5b0f1dc))
* update screenshot for launch ([df1b352](https://github.com/antropos17/Aegis/commit/df1b352ef16e8ccf1a19b65863b7d95a3cab0db8))
* update test counts and changelog for EPERM handling ([ff66877](https://github.com/antropos17/Aegis/commit/ff66877dd51df3258d5505a592ab50bbe682ca6e))
* update test counts and changelog for IPC batching ([823db91](https://github.com/antropos17/Aegis/commit/823db91b6efe9a9480db608729b0516c1b664550))
* update test counts and changelog for startup perf fix ([8c384a1](https://github.com/antropos17/Aegis/commit/8c384a12dfe0da8e2aa20de8e7dc3024e198e05a))

## [0.3.0-alpha] - 2026-02-28

### Added
- Multi-dimensional anomaly scoring (4 axes: Network, FileSystem, Process, Baseline)
- Local LLM runtime detection (Ollama localhost:11434, LM Studio localhost:1234)
- CLI interface with JSON output (--scan-json, --version, --help)
- 106 agent signatures including local-llm-runtime category
- 408 tests across 25 test files (up from 130/12)
- Dynamic version display in Footer via IPC
- Contributors section in README with avatars
- Trust signal badges, Table of Contents, navigation bar
- "What AEGIS Does / Does NOT Do" section
- "Building from Source" section
- Star History chart
- CODEOWNERS file
- FUNDING.yml

### Changed
- README completely rewritten following open-source best practices
- All badges unified to flat-square style
- Screenshots moved from screenshots/ to docs/screenshots/

### Fixed
- Hardcoded version in Footer.svelte → dynamic IPC-based
- Agent count: 94 → 98 across all files
- Test count: 130/12 → 408/23
- Removed completed items from Roadmap (electron-builder, Mac/Linux, local LLMs)

## [0.2.0-alpha] - 2026-02-24

### Added
- Full Svelte 5 + Vite 7 rewrite with `$state`/`$derived`/`$effect` runes replacing vanilla JS renderer
- IPC bridge as Svelte reactive stores (`ipc.js`, `risk.js`, `theme.js`)
- 4-tab navigation: Shield, Activity, Rules, Reports
- Canvas radar with agent dots, sweep arm, connection lines at 60fps
- Risk scoring derived store with weighted time-decay model and trust grades (A+ through F)
- Agent card expandable details with sparklines, session duration, parent chain, and action tabs
- SVG horizontal timeline in Shield tab (last 100 events as color-coded dots)
- Network panel with Feed/Network toggle in Activity tab
- Activity feed process grouping with expandable details
- Clickable file paths (reveal in explorer) and copyable network addresses
- AI agent config file protection for 27 agent config directories (Hudson Rock threat vector)
- Behavioral anomaly detection with baseline deviation alerts (5 weighted factors, 0-100 scoring)
- AI-powered threat analysis via Anthropic API (per-agent and full session analysis)
- Real-time timeline, dashboard metrics, persistent JSONL audit logging with daily rotation
- Container/VM and local LLM detection expanding agent database from 88 to 95 agents
- Settings modal with export/import config buttons
- CSP header and network connections store cap (500 max)
- Protection presets (Paranoid/Strict/Balanced/Developer) and per-agent permissions grid
- Agent Database Manager with custom add/edit/delete and import/export
- Reports tab with aggregate stat cards, JSON/CSV/HTML export, and audit log viewer
- Printable HTML threat reports
- GitHub Actions CI/CD lint + build workflow
- electron-builder config for Windows NSIS installer with procedural shield icon
- macOS build compatibility
- GitHub issue templates, PR template, CODE_OF_CONDUCT
- Responsive min-width and electron window constraints
- Tab transitions and micro-interactions
- M3 design tokens with neumorphic glassmorphism (Plus Jakarta Sans + DM Sans + DM Mono)
- UI screenshots added to README for all tabs
- README, CONTRIBUTING, SECURITY, ARCHITECTURE docs for open-source launch
- CI badge in README

### Fixed
- Risk scoring rebalance — self-access exemption, dedup, diminishing returns
- Radar canvas visibility — increased grid/label/sweep opacity for dark theme
- Radar centering and light theme visibility
- Black screen in packaged exe (CSP + path fix)
- Threat analysis JSON parsing and robust JSON extraction
- Table header overlap in threat analysis view
- `sendToRenderer` crash on shutdown
- Hardcoded `#fff` colors in 4 Svelte components breaking dark theme
- Removed WSL from agent DB, added event dedup (30s window)
- `icon.ico` to `icon.png` for electron-builder NSIS packaging
- Lazy init settings/baselines path — resolved `app.getPath` crash on startup
- Unset `ELECTRON_RUN_AS_NODE` in start script for IDE terminal compatibility
- Dev server port fixed to 5174
- Nested ternary in Header, dead import in Footer
- Duplicate/wrong author name in package metadata
- CI YAML syntax error in lint step
- 10 UI bugs resolved from full audit pass

### Changed
- Complete UI rewrite from vanilla JS to Svelte 5 component architecture (22 components)
- Premium dark minimal redesign with glassmorphism panels, blur, translucent surfaces
- Header compact redesign with shield score, agent/file counts, theme toggle
- Footer merged with system stats (version, uptime, MEM/HEAP/SCAN)
- Agent card compact redesign with trust bars and grouped-by-name display
- Shield tab bento grid layout
- Activity tab compact feed with network panel merged
- Rules tab visual polish with presets/permissions/database sections
- Extracted IPC handlers from main.js into dedicated modules
- Renamed `app.html` to `index.html` and updated Vite config
- Removed legacy vanilla JS renderer and old CSS
- Cleaned config-manager.js and aligned all components to M3 tokens

## [0.1.0-alpha] - 2026-02-15

### Added
- Initial release — AI Agent Privacy Shield for Windows
- AI agent process detection via `tasklist /FO CSV` with pattern matching
- File monitoring via chokidar for sensitive directories (`.ssh`, `.aws`, `.gnupg`, `.kube`, `.docker`, `.azure`, `.env*`)
- Handle-based file scanning via PowerShell for per-process file attribution
- Network monitoring via `Get-NetTCPConnection` with DNS reverse lookup
- Sensitive file classification against 70+ rules
- Per-agent risk scoring with time-decay model
- System tray with procedural shield icon and native notifications
- Dark mode dashboard with real-time agent monitoring
- Process control (Kill/Suspend/Resume per agent)
- Settings persistence via JSON in Electron userData directory
- Secure IPC bridge via contextBridge with context isolation
