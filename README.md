# Hi there 👋 I'm Bigduu

**AI agent developer.** I build local-first agents that can break down tasks, use tools, stream their work, retain useful context, and turn repeated work into automation — on infrastructure you can run and inspect yourself.

Years of production engineering across JVM services and Rust systems shape this work. I now build the ecosystem below in tight implementation and review loops with the agents themselves: **Bodhi helps build Bodhi.**

## 🤖 The Bodhi AI ecosystem

These are the main projects I am actively developing:

| Project | What it is |
|---|---|
| 🧭 **[Jiandu](https://github.com/bigduu/Jiandu)** | Small, agent-independent, filesystem-backed memory: a Rust library plus one stdio MCP `memory` tool for Session, Project, and Global memory. |
| 🎋 **[Bamboo-agent](https://github.com/bigduu/Bamboo-agent)** | A local-first AI agent runtime in Rust. It owns sessions, tools, skills, sub-agents, workflows, schedules, and context policy behind HTTP and streaming APIs. |
| 🧘 **[Bodhi-AI](https://github.com/bigduu/Bodhi-AI)** | The desktop agent app: a Tauri shell around the Bamboo runtime and Lotus interface. |
| 🪷 **[Lotus](https://github.com/bigduu/Lotus)** | The React interface for live reasoning, tool calls, tasks, projects, and agent control. **[lotus-next](https://github.com/bigduu/lotus-next)** is its mobile-first companion track. |
| ✨ **[Nova](https://github.com/bigduu/Nova)** | A self-contained Rust MCP server for macOS screenshots, Set-of-Mark targeting, OCR, mouse, and keyboard control. |
| 🏔 **[Zenith](https://github.com/bigduu/Zenith)** | The workspace that coordinates the repositories, architecture, roadmap, and release train. |
| 🏯 **[Pavilion](https://github.com/bigduu/Pavilion)** | The bilingual 中文/English website and long-form product and architecture documentation. |

## 🧠 What I care about in agents

- **Local-first and private** — your model keys, your data, and your machine; cloud services are optional.
- **Transparency over magic** — make model output, tool calls, state changes, and failures visible.
- **Shared memory with a narrow boundary** — durable filesystem memory through a small MCP surface, with product-specific context policy kept in the agent runtime.
- **Real work, not just chat** — task decomposition, sub-agents, schedules, workflows, and desktop control.
- **Agent-native development** — parallel implementation, adversarial review, exact acceptance checks, and automated follow-through as daily practice.
- **Clear implementation boundaries** — Rust for local execution and durable services; MCP where different agents need a shared interface.

## 🛠 Stack

**Daily drivers:** Rust · TypeScript/React · Tauri · Go · MCP · HTTP/SSE/WebSocket

**Also fluent in:** Java · Kotlin · Scala · Vue.js

## 📫 Contact

Feel free to reach out at [mugeng.du@gmail.com](mailto:mugeng.du@gmail.com).

---

<a href="https://github.com/bigduu">
  <img src="https://komarev.com/ghpvc/?username=bigduu&style=flat-square" alt="Profile views" />
</a>

---

<!-- Self-hosted github-readme-stats (own Vercel instance + PAT: no shared rate limit). -->
![Bigduu's GitHub stats](https://github-readme-stats-bigduu.vercel.app/api?username=bigduu&show_icons=true&theme=dark)

[![Top languages](https://github-readme-stats-bigduu.vercel.app/api/top-langs/?username=bigduu&theme=dark)](https://github.com/bigduu)

[![Bigduu's contributions](https://ghchart.rshah.org/40c463/bigduu)](https://github.com/bigduu)
