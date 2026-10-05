# Hi, I'm bigduu 👋

**AI agent developer.** I build local-first agents that break down tasks, use tools, stream their work, keep useful memory, and turn repeated work into automation — on infrastructure you can run and inspect yourself.

Years of production engineering across JVM services and Rust systems shape this work. I now build the ecosystem below in tight implementation and review loops with the agents themselves: **Bodhi helps build Bodhi.**

Based in Hangzhou. Open to interesting collaborations.

## Bodhi — local-first AI agent workbench

[Bodhi](https://github.com/bigduu/Zenith) is a desktop agent you can actually watch work: every tool call is visible, risky actions ask first, and memory stays on your machine.

**Install on macOS (Homebrew):**

```sh
brew tap bigduu/tap
brew trust bigduu/tap
brew install --cask bigduu/tap/bodhi
```

That installs the [Bodhi desktop app](https://github.com/bigduu/Bodhi-AI) and the [Jiandu](https://github.com/bigduu/Jiandu) + [Nova](https://github.com/bigduu/Nova) CLI tools. Windows / Linux / manual macOS builds: [Bodhi releases](https://github.com/bigduu/Bodhi-AI/releases/latest).

| Project | One-line value | Link |
|---|---|---|
| **Bodhi** | Desktop app — hand it a task, watch every step | [Bodhi-AI](https://github.com/bigduu/Bodhi-AI) |
| **Bamboo** | Rust agent runtime: sessions, tools, skills, MCP, sub-agents, workflows | [Bamboo-agent](https://github.com/bigduu/Bamboo-agent) |
| **Nova** `v0.3.0` | Let any MCP agent use your real Mac or Windows apps | [Nova](https://github.com/bigduu/Nova) · `brew install bigduu/tap/nova` |
| **Jiandu** `v0.3.0` | One shared local memory for Claude Code, Codex, Cursor, and Bodhi | [Jiandu](https://github.com/bigduu/Jiandu) · `brew install bigduu/tap/jiandu` |
| **Magpie** `v0.1.2` | Drive Bamboo from Telegram or Feishu/Lark | [Magpie](https://github.com/bigduu/Magpie) · `brew install bigduu/tap/magpie` |
| **Zenith** | Monorepo index, roadmap, and release train for the suite | [Zenith](https://github.com/bigduu/Zenith) |

CLI-only install (no desktop app):

```sh
brew tap bigduu/tap
brew install bigduu/tap/nova     # macOS
brew install bigduu/tap/jiandu   # compiles from source tag
brew install bigduu/tap/magpie   # macOS / Linux x86_64
```

Tap docs: [bigduu/homebrew-tap](https://github.com/bigduu/homebrew-tap).

## What I care about in agents

- **Local-first and private** — your model keys, your data, your machine; cloud is optional.
- **Transparency over magic** — make model output, tool calls, state changes, and failures visible.
- **Shared memory with a narrow boundary** — durable filesystem memory through a small MCP surface.
- **Real work, not just chat** — task decomposition, sub-agents, schedules, workflows, and desktop control.
- **Agent-native development** — parallel implementation, adversarial review, exact acceptance checks.
- **Clear boundaries** — Rust for local execution; MCP where different agents need a shared interface.

## Stack

**Daily:** Rust · TypeScript/React · Tauri · Go · MCP · HTTP/SSE/WebSocket

**Also fluent in:** Java · Kotlin · Scala · Vue.js

## Contact

[mugeng.du@gmail.com](mailto:mugeng.du@gmail.com) · [GitHub](https://github.com/bigduu)

---

<a href="https://github.com/bigduu">
  <img src="https://komarev.com/ghpvc/?username=bigduu&style=flat-square" alt="Profile views" />
</a>

---

<!-- Self-hosted github-readme-stats (own Vercel instance + PAT: no shared rate limit). -->
![Bigduu's GitHub stats](https://github-readme-stats-bigduu.vercel.app/api?username=bigduu&show_icons=true&theme=dark)

[![Top languages](https://github-readme-stats-bigduu.vercel.app/api/top-langs/?username=bigduu&theme=dark)](https://github.com/bigduu)

[![Bigduu's contributions](https://ghchart.rshah.org/40c463/bigduu)](https://github.com/bigduu)
