# Mateusz Bochyński

### I'd rather build the system than draw the building.

MSc Arch → Agentic Engineer. I ship agent systems from spec to production.
Architecture taught me to hunt bottlenecks. AI gave me the tools to kill them.

→ **Full case studies, process, contact: [mateuszbochynski.com](https://mateuszbochynski.com?utm_source=github&utm_medium=profile&utm_campaign=readme-hero)**

---

## Current work

- **[Atlas Hotel Assistant](https://mateuszbochynski.com/en/builds/atlas-hotel-assistant?utm_source=github&utm_medium=profile&utm_campaign=readme-atlas):** Production AI assistant serving two hotels. I indexed 304 procedures via Index-First Search over curated Q&A pairs. No vector embeddings. Precision over similarity.

- **[Personal AI Agent](https://mateuszbochynski.com/en/builds/personal-ai-agent?utm_source=github&utm_medium=profile&utm_campaign=readme-chadli):** 24/7 agent running on a home Ubuntu server, navigating a 3,800-node Obsidian knowledge graph via wikilinks. Three-layer memory, cross-tool adapters, Telegram, Slack, and Discord channels.

- **[Rhino 8 Image Studio](https://mateuszbochynski.com/en/builds/ai-image-studio?utm_source=github&utm_medium=profile&utm_campaign=readme-ris)** · [code](https://github.com/Bochyn/Rhino-8-Image-Studio): Desktop plugin for Rhino 8 that captures 3D viewports and generates photorealistic renders through Gemini and fal.ai. A plugin-based model layer lets me ship new AI models the same day they drop.

- **[IFC Inspector](https://mateuszbochynski.com/en/builds/ifc-inspector?utm_source=github&utm_medium=profile&utm_campaign=readme-ifc)** · [code](https://github.com/Bochyn/IFC-Inspector): Terminal BIM file inspector in pure Rust with a hand-written STEP/ISO-10303 parser. Audits a 45 MB Revit export in 2 seconds instead of 2 minutes.

- **[Homelab Infrastructure](https://mateuszbochynski.com/en/builds/homelab-infrastructure?utm_source=github&utm_medium=profile&utm_campaign=readme-homelab):** Self-hosted three-machine platform serving 86k photos, media, finances, and a local AI interface. Docker stack behind Cloudflare Tunnel, zero open inbound ports, GPU offload from NAS to laptop.

Also shipping: **[MonoReader](https://mateuszbochynski.com/en/builds/monoreader?utm_source=github&utm_medium=profile&utm_campaign=readme-monoreader)**, a lightweight Windows markdown reader in Tauri + Rust. 4.1 MB binary, published on the Microsoft Store.

---

## How I work with AI

The problem with most AI coding workflows is simple: the agent forgets. Between sessions, between files, between decisions. Every new conversation starts from zero, re-reads the codebase, re-invents architecture we settled last week, and confidently rewrites code it has already rewritten twice.

So I treat every project as an **Obsidian vault**, not a folder of files.

**The repo is a knowledge graph.** Every module, decision, convention, and open task is a markdown note with wikilinks to what it connects to. The agent navigates this graph like a wiki: follow `[[auth]]` to find the auth node, follow `[[api]]` to find the API node. No blind grep, no guessing. The graph is the map.

**Memory lives in the repo, not in the chat.** At the end of every session I compact the transcript into a priority-tagged log that lives in the repo next to the code: 🔴 architectural decisions, 🟡 conventions, 🟢 minor notes. Next session starts with an onboarding step: the agent reads the log and the graph before doing anything. It knows what we decided last Tuesday, which bugs are still open, where the previous session left off. Even after `/clear`. Even next month.

**One workflow across every tool.** Because the graph and memory live in the vault instead of inside one specific CLI, I'm not locked into a single agent. Same project, same context, same memory: Claude Code, Codex, Gemini CLI, OpenCode. Whichever model is strongest for the task, that's the one I reach for.

Underneath all of it, one rule: **I assume the model doesn't know that it knows.** Language models speak about facts and confabulations with the same certainty. I stay the consciousness they don't have: I gather sources, I curate the graph, I hand the agent precise boundaries where it can operate without guessing. I set the direction. The model is my hands at the keyboard.

→ See this method in production: [Personal AI Agent case study](https://mateuszbochynski.com/en/builds/personal-ai-agent?utm_source=github&utm_medium=profile&utm_campaign=readme-method)

---

## Open to

I'm looking for teams where the hard part is translating a messy domain into a system that actually runs. AI startups, B2B tools, AEC tech: anywhere the problem is the workflow, not the framework.

[mateuszbochynski.com](https://mateuszbochynski.com?utm_source=github&utm_medium=profile&utm_campaign=readme-contact) · [LinkedIn](https://www.linkedin.com/in/mateusz-bochyński) · [@MateuszM8](https://x.com/MateuszM8) · [m8@mateuszbochynski.com](mailto:m8@mateuszbochynski.com)
