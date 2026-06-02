# claude-zero-to-hero

A structured, deep-dive curriculum to master **Claude and the full Anthropic ecosystem** — built for developers, not casual users. From prompting fundamentals all the way to Claude Code, Skills, MCP, the API, RAG, and agent engineering.

This repo is both my **learning journal** and the home of my growing, reusable **`SKILL.md` library**.

---

## Why this exists

Most "learn Claude" content stops at prompt tips. The goal here is to go deep enough to *build* with the entire stack efficiently — and to develop my own trusted, reusable skills instead of depending on third-party ones (which carry prompt-injection / backdoor risk).

The curriculum is designed to match or exceed Anthropic Academy's developer-relevant courses.

## How it works

The course lives inside a Claude **Project**. The file [`project-instructions.md`](./project-instructions.md) goes into that project's custom instructions — it tells Claude who I am, how to teach, and the full lesson map.

Each **Chat** covers a set of **Lessons** and usually ends with a hands-on **Exercise**. Every few chats there's a **Mini-Exam** or **Capstone**. To start a session, I just open a new chat in the project and say *"This is Chat N"* — Claude already knows what to teach and at what depth.

## Curriculum

| Chat | Lessons | Focus | Time |
|------|---------|-------|------|
| 1 | 1–3 | Foundations: how Claude works, AI Fluency (4D), prompting | ~6h |
| 2 | 4–5 | Projects, Artifacts, Memory, Extended Thinking, search | ~4.5h |
| 3 | 6–7 | Advanced prompting, structured outputs, multimodal/long context | ~4.5h |
| ▶ Exam 1 | — | Foundations + interface + prompting | ~3h |
| 4 | 8–9 | Claude Code: setup, core loop, essential commands | ~5h |
| 5 | 10–11 | CLAUDE.md, Plan Mode, hooks, full command reference | ~5h |
| 6 | 12–13 | Skills + building a reusable library + security | ~6h |
| 7 | 14–15 | Subagents, Agent Teams, agentic workflow patterns | ~5h |
| ▶ Exam 2 | — | Claude Code + Skills + Subagents | ~3h |
| 8 | 16–17 | MCP: concepts + building servers/clients | ~6h |
| 9 | 18–19 | Claude API core + tools / structure / extended features | ~6h |
| 10 | 20–21 | RAG + Claude Agent SDK & orchestration | ~6h |
| 11 | 22–23 | Cowork, Computer Use, channels & integrations | ~5h |
| 12 | 24–25 | Token economics, deployment (Bedrock/Vertex), responsible AI | ~5h |
| ▶ Capstone | — | Dry run of a real multi-app platform | ~6–8h |

**Total: ~80–90 hours** (≈ 3–4 weeks at a steady pace).

## Repo structure

```
claude-zero-to-hero/
├── README.md                 # this file
├── project-instructions.md   # paste into the Claude Project's instructions
├── notes/                    # my notes per lesson
├── exercises/                # exercise + exam solutions
└── skills/                   # my reusable SKILL.md library (the long-term payoff)
```

## Progress

- [ ] Chat 1 — Foundations
- [ ] Chat 2 — Claude.ai product surface
- [ ] Chat 3 — Advanced prompting
- [ ] Mini-Exam 1
- [ ] Chat 4 — Claude Code fundamentals
- [ ] Chat 5 — Claude Code power features
- [ ] Chat 6 — Skills
- [ ] Chat 7 — Subagents & agentic workflows
- [ ] Mini-Exam 2
- [ ] Chat 8 — MCP
- [ ] Chat 9 — Claude API
- [ ] Chat 10 — RAG & Agent SDK
- [ ] Chat 11 — Cowork, Computer Use & integrations
- [ ] Chat 12 — Efficiency, cost & production
- [ ] Final Capstone

---

*Curriculum mapped to Anthropic Academy's developer track. Optional companion resource: the official [`anthropics/courses`](https://github.com/anthropics/courses) Jupyter notebooks.*