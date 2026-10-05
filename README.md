<p align="center">
  <img src="./assets/banner.jpg" alt="bigduu: Building Bodhi, a local-first AI agent workbench. A forest with a bodhi tree, bamboo, a lotus river and magpies." width="100%" />
</p>

<p align="center">
  <a href="https://github.com/bigduu/Zenith"><img src="https://img.shields.io/badge/Bodhi-local--first%20agent%20workbench-2ea44f?style=flat-square" alt="Bodhi" /></a>
  <a href="https://github.com/bigduu/homebrew-tap"><img src="https://img.shields.io/badge/brew-bigduu%2Ftap-blue?style=flat-square&logo=homebrew&logoColor=white" alt="Homebrew tap" /></a>
  <a href="mailto:mugeng.du@gmail.com"><img src="https://img.shields.io/badge/email-mugeng.du%40gmail.com-lightgrey?style=flat-square" alt="Email" /></a>
  <a href="https://github.com/bigduu"><img src="https://komarev.com/ghpvc/?username=bigduu&style=flat-square&label=profile%20views" alt="Profile views" /></a>
</p>

**AI agent developer** in Hangzhou. I build **[Bodhi](https://github.com/bigduu/Zenith)** — a local-first agent workbench you can watch work: every tool call is visible, risky actions ask first, and memory stays on your machine.

Years of JVM services and Rust systems inform the stack. I ship the suite below in tight loops with the agents themselves: **Bodhi helps build Bodhi.**

## Quick install (macOS)

```sh
brew tap bigduu/tap
brew trust bigduu/tap          # required so the cask can pull formula deps
brew install --cask bigduu/tap/bodhi
```

That installs the [Bodhi desktop app](https://github.com/bigduu/Bodhi-AI) plus the [Jiandu](https://github.com/bigduu/Jiandu) and [Nova](https://github.com/bigduu/Nova) CLIs. Windows / Linux / manual macOS builds: [Bodhi releases](https://github.com/bigduu/Bodhi-AI/releases/latest).

CLI-only (no desktop app):

```sh
brew tap bigduu/tap
brew install bigduu/tap/nova     # macOS
brew install bigduu/tap/jiandu   # builds from source tag (needs Rust)
brew install bigduu/tap/magpie   # macOS / Linux x86_64 — Telegram / Feishu bridge
```

Tap docs: [bigduu/homebrew-tap](https://github.com/bigduu/homebrew-tap).

## The Bodhi suite

| | Project | What it is | Get it |
|:-:|---|---|---|
| 🪷 | **[Bodhi](https://github.com/bigduu/Bodhi-AI)** | Desktop app — hand it a task, watch every step | `brew install --cask bigduu/tap/bodhi` |
| 🎋 | **[Bamboo](https://github.com/bigduu/Bamboo-agent)** | Rust agent runtime: sessions, tools, skills, MCP, sub-agents, workflows | Bundled with Bodhi · [repo](https://github.com/bigduu/Bamboo-agent) |
| 🖥️ | **[Nova](https://github.com/bigduu/Nova)** `v0.3.0` | Computer-use MCP — let any agent drive real Mac / Windows apps | `brew install bigduu/tap/nova` |
| 🧠 | **[Jiandu](https://github.com/bigduu/Jiandu)** `v0.3.0` | Shared local filesystem memory for Claude Code, Codex, Cursor, Bodhi | `brew install bigduu/tap/jiandu` |
| 🐦 | **[Magpie](https://github.com/bigduu/Magpie)** `v0.1.2` | Drive Bamboo from Telegram or Feishu / Lark | `brew install bigduu/tap/magpie` |
| 🗺️ | **[Zenith](https://github.com/bigduu/Zenith)** | Monorepo index, roadmap, and release train | [Zenith](https://github.com/bigduu/Zenith) |

## Now

- Shipping **Bodhi** as the default way to run the suite on a Mac (`brew` cask + tap).
- **Nova v0.3.0** and **Jiandu v0.3.0** out — computer use + shared memory for any MCP host.
- **Magpie v0.1.2** bridges Telegram / Feishu into Bamboo sessions.
- Tightening docs, Homebrew packaging, and release notes so "clone → brew → work" stays one path.

## What I care about in agents

- **Local-first and private** — your model keys, your data, your machine; cloud is optional.
- **Transparency over magic** — make model output, tool calls, state changes, and failures visible.
- **Shared memory with a narrow boundary** — durable filesystem memory through a small MCP surface.
- **Real work, not just chat** — task decomposition, sub-agents, schedules, workflows, and desktop control.
- **Agent-native development** — parallel implementation, adversarial review, exact acceptance checks.
- **Clear boundaries** — Rust for local execution; MCP where different agents need a shared interface.

## Stack

**Daily:** Rust · TypeScript / React · Tauri · Go · MCP · HTTP / SSE / WebSocket

**Also:** Java · Kotlin · Scala · Vue.js

## Contact

[mugeng.du@gmail.com](mailto:mugeng.du@gmail.com) · [GitHub](https://github.com/bigduu) · Open to interesting collaborations.

---

<!-- Self-hosted github-readme-stats (own Vercel instance + PAT: no shared rate limit). -->
<p align="center">
  <img src="https://github-readme-stats-bigduu.vercel.app/api?username=bigduu&show_icons=true&theme=dark&hide_border=true" alt="bigduu GitHub stats" />
  <img src="https://github-readme-stats-bigduu.vercel.app/api/top-langs/?username=bigduu&layout=compact&theme=dark&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://ghchart.rshah.org/40c463/bigduu" alt="bigduu contributions" />
</p>
