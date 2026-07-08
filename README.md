# tpj-collective

## Personal projects
| Repo | What it is |
|---|---|
| [ongresso-app](https://github.com/tpj-collective/ongresso-app) *(private)* | Ongresso unified docs reference app — Next.js |
| [tpj-training-app](https://github.com/tpj-collective/tpj-training-app) *(private)* | TPJ Training System — mobile-first PWA, React 18 + Vite + TypeScript + Tailwind + Zustand |
| [ai-developer-manual](https://github.com/tpj-collective/ai-developer-manual) | First-principles manual teaching modern software development — computer fundamentals, security, Git, AI agents, professional workflows |

## AI agent skills & tools
Forked tools that extend Claude Code and other AI coding agents.

### 🎨 Design Skill Pipeline
Four tools chained into one frontend design + verification workflow, bundled as git submodules in **[design-skill-pipeline](https://github.com/tpj-collective/design-skill-pipeline)**:

1. **[npxskillui](https://github.com/tpj-collective/npxskillui)** — Extract: reverse-engineers an existing site/repo's design system into a `.skill` file
2. **[ui-ux-pro-max-skill](https://github.com/tpj-collective/ui-ux-pro-max-skill)** — Generate: reasoning engine that proposes a tailored design system from a plain-language brief
3. **[impeccable](https://github.com/tpj-collective/impeccable)** — Critique/Polish: audits output against 45 anti-pattern rules to avoid generic "AI slop" design
4. **[playwright-cli](https://github.com/tpj-collective/playwright-cli)** — Verify: drives a real browser to confirm the built UI actually works

Use `design-skill-pipeline` for the full workflow; each numbered repo above also stands alone.

### Standalone skills
| Repo | What it does |
|---|---|
| [graphify](https://github.com/tpj-collective/graphify) | Turns a codebase (code, docs, PDFs, images, video) into a queryable knowledge graph |
| [claude-mem](https://github.com/tpj-collective/claude-mem) | Gives Claude Code persistent memory across sessions |
