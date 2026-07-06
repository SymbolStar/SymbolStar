# Hi, I'm SymbolStar 👋

📍 **China** | 📱 **Mobile Developer** | 🤖 **AI Agent Tinkerer**

![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Android](https://img.shields.io/badge/-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/-iOS-000000?style=flat-square&logo=apple&logoColor=white)
![Metal](https://img.shields.io/badge/-Metal-8E8E93?style=flat-square&logo=apple&logoColor=white)

> Crafting native mobile experiences and exploring the intersection of graphics, AI agents, and developer tooling.

## 🌍 Open Source Contributions

Contributor to:

- 🦞 **[openclaw/openclaw](https://github.com/openclaw/openclaw)** — Personal AI assistant, any OS / any platform _(4 merged PRs)_
- 🤖 **[Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** — Accessible AI for everyone _(2 merged PRs)_
- 🔁 **[n8n-io/n8n](https://github.com/n8n-io/n8n)** — Fair-code workflow automation with native AI
- 💬 **[open-webui/open-webui](https://github.com/open-webui/open-webui)** — User-friendly AI interface (Ollama / OpenAI API)

## What I'm Doing

- 🤖 **AI Agents & MCP** — Building MCP servers and tooling around AI coding agents (OpenClaw, Claude Code, etc.)
- 📱 **Mobile Development** — Native Android & iOS apps with focus on performance and UX
- 🎨 **Graphics Programming** — Diving into SceneKit, Metal, and the iOS rendering pipeline

## 🆕 Recent Work

- 🔨 **[OpenForge](https://github.com/SymbolStar/OpenForge)** — Multi-agent task tracker for OpenClaw. Threads are tasks, `@agent` assigns the next worker, Slack-style three-pane UI, JSONL event log, zero runtime dependencies. Turns a shared inbox into a durable work queue for cooperating AI agents.
- 🎨 **[dashboard-design-system](https://github.com/SymbolStar/dashboard-design-system)** — Tiny design tokens + utility classes for data dashboards. Light/dark themes, 4px grid, status colors, no build step — drop the CSS in and go.
- 📊 **[gemma4-mac-mini-bench](https://github.com/SymbolStar/gemma4-mac-mini-bench)** — Full benchmark of Google Gemma 4 (E4B + 12B) on Mac mini M4 / 32GB: short tasks, long-context, vision, OpenCode integration, and the pitfalls you hit along the way.
- 🐦 **[magpie](https://github.com/SymbolStar/magpie)** — Lightweight A-share monitoring daemon: watchlist, price & fund-flow alerts, K-line, 龙虎榜, agent-friendly HTTP API. Feishu notifier + OpenClaw skill integration.
  - npm: [`@symbolstar/magpie`](https://www.npmjs.com/package/@symbolstar/magpie) · ClawHub: `clawhub install magpie`
- 🚢 **[shipcheck](https://github.com/SymbolStar/shipcheck)** — Best-effort pre-publish PII & secret check for npm packages, OpenClaw skills, and local repos. Catches leaked tokens, emails, identities before you `npm publish`.
  - npm: [`@symbolstar/shipcheck`](https://www.npmjs.com/package/@symbolstar/shipcheck)
- 📬 **[gmail-mcp](https://github.com/SymbolStar/gmail-mcp)** — MCP stdio server that lets AI assistants read your Gmail (list / get / search / labels). OAuth read-only.
  - npm: [`@symbolstar/gmail-mcp`](https://www.npmjs.com/package/@symbolstar/gmail-mcp) — `npx @symbolstar/gmail-mcp auth`
- 🦗 **[hopper](https://github.com/SymbolStar/hopper)** — Lightweight task pool for multi-agent coordination. MCP server + CLI, SQLite-backed, optimistic concurrency, dependency tracking.
- 🧠 **[synapse](https://github.com/SymbolStar/synapse)** — Local MCP server that indexes AI coding sessions (Claude Code / OpenCode / OpenClaw) into one searchable database. Shared memory across tools.

### 🔒 Private (in-progress)

- ⌨️ **SymbolInput** _(private)_ — macOS menu-bar tool: click into any app's text field, describe what you want in Chinese in a floating panel, and get the correct English written back automatically. Multi-provider (local Anthropic-/OpenAI-/Ollama-style + DeepSeek), streaming, Accessibility-based text injection, Option+A to grab selected text.
- 🏥 **FamilyHealth** _(private)_ — iOS app for managing a family's medicines and medical records. Auto-intake from photos (VisionKit + OCR), structured medicine/record parsing (date, hospital, department, diagnosis), SwiftData persistence, per-family-member scoping.

## 🧩 Published Skills

OpenClaw agent skills I've published on [ClawHub](https://clawhub.ai):

- 🧹 **[xcode-cache-cleaner](https://clawhub.ai/symbolstar/xcode-cache-cleaner)** — Scan and clean build caches for iOS/macOS developers. First-class Xcode support (DerivedData, iOS/watchOS/tvOS/macOS DeviceSupport, CoreSimulator) plus per-project cleanup (SPM, Pods, node_modules, Gradle, Rust, Python).
  - Install: `clawhub install xcode-cache-cleaner`
- 🪟 **[agent-tab-title](https://clawhub.ai/symbolstar/agent-tab-title)** — Local zero-build patch for OpenClaw Control UI: makes the browser tab title follow the active agent (e.g. `Milly · OpenClaw`) so multi-agent operators can disambiguate tabs in the browser tab strip and Cmd-` switcher. Mirrors upstream PR [openclaw/openclaw#80944](https://github.com/openclaw/openclaw/pull/80944) as an out-of-tree override.
  - Install: `clawhub install agent-tab-title`
- 🔔 **[echo-cue](https://clawhub.ai/symbolstar/echo-cue)** — Local zero-build patch for OpenClaw Control UI: plays a short Web Audio chime when an assistant reply finishes streaming, so you notice replies even from a background tab. In-page floating 🔔 picker with 11 sound presets (Basic / Animal Crossing / Super Mario / Retro) and per-row Preview. Locally nicknamed **echo**. Stop-gap mirror of upstream PR [openclaw/openclaw#73894](https://github.com/openclaw/openclaw/pull/73894) (issue [#69186](https://github.com/openclaw/openclaw/issues/69186)); auto-skips itself once upstream lands.
  - Source: [SymbolStar/echoCue](https://github.com/SymbolStar/echoCue) · Install: `clawhub install echo-cue`

## Interests

- 🤖 AI agents、MCP 协议、agent 间协作
- 🧊 计算机图形学 & GPU 渲染管线
- 📱 跨平台移动开发
- 🛠️ 开发者工具与效率提升

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SymbolStar&show_icons=true&theme=default&hide_border=true" alt="GitHub Stats" />
</p>
