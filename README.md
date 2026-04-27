<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║          debjit dey · full-stack engineer                ║
║          building systems that hold under pressure       ║
╚══════════════════════════════════════════════════════════╝
```

</div>

---

### `whoami`

Full-stack engineer with ~1 year of production experience across two companies — frontend performance, backend services, cloud deployments. I own features end to end, from schema design to CI/CD pipeline. Currently heads-down on AI-first tooling and distributed systems.

Not a tutorial-follower. I read source code, trace errors through logs, and ship things that work.

---

### Stack

```typescript
const debjit = {
  primary:   ["TypeScript", "Next.js", "React", "Node.js", "PostgreSQL"],
  secondary: ["Python", "MongoDB", "MySQL", "Redis", "React Native"],
  cloud:     ["AWS (EC2, S3)", "Docker", "GCP"],
  tools:     ["Socket.io", "REST", "WebSockets", "Jest", "CI/CD"],
  apis:      ["OpenAI", "Google Gemini", "Razorpay"],
};
```

---

### Experience

**Valk Technologies & Solutions** · Full-Stack Developer · `Dec 2024 – Sep 2025`
- Cut time-to-interactive ~35–40% across 3 client Next.js apps via SSR + route-level code splitting (Lighthouse-verified)
- Designed and maintained Node.js/Express REST services across 50+ endpoints in 3 independently deployable services
- Reduced high-traffic query latency ~60% on MySQL/MongoDB — audited slow-query logs, killed N+1 patterns, added composite indexes
- Triaged and hotfixed production incidents via structured log tracing; zero data loss, zero-downtime restarts

**Collabtalent LLC** · Frontend Engineer (Contract) · `Apr 2024 – Nov 2024`
- Led full Angular → React migration, consolidated fragmented component architecture into unified state management; cut onboarding from ~3 weeks to ~5 days
- Integrated streaming LLM APIs with async fetch + non-blocking UI; retry logic cut user-facing timeout errors ~70%
- Built WCAG-AA compliant responsive layouts verified across Chrome, Firefox, Safari, and mobile viewports

---

### Projects

#### [`GrindNode`](https://github.com/debjit450) — AI Coding Interview Prep Platform
`React 18` `TypeScript` `PostgreSQL` `Deno` `Docker` `AWS EC2` `Gemini API` `Razorpay`

Sandboxed code execution platform with a custom judge engine — not a string-diff wrapper. Handles floating-point tolerance, tree/graph structure validation, and edge cases LeetCode-style runners miss. Four isolated language runtimes via Docker on EC2, per-subscription CPU/memory quotas. Monaco editor wired to Gemini for context-aware hints; reduced average time-to-solve ~25%.

Payment infra runs on Razorpay with idempotent webhook listeners — prorated upgrades, downgrades, automated invoicing.

---

#### [`StableJSON`](https://github.com/debjit450/stablejson) — JSON Utility Suite · `stablejson.vercel.app`
`React 18` `TypeScript` `Vite` `Tailwind CSS` `shadcn/ui`

Browser-native JSON toolkit — no backend, no data collection, no accounts. Validates, formats, minifies, diffs, sorts, and analyzes JSON entirely client-side. Features include JSONPath querying, TypeScript interface generation, Zod schema inference, CSV export, and a command palette (⌘K). Used by developers who don't want their API responses going through someone's server.

---

#### [`gitwit`](https://github.com/debjit450/gitwit) — AI Git Commit Generator · `npm install -g gitwit`
`Node.js` `OpenAI API` `CLI`

One command. Reads your `git diff --cached`, understands what changed, generates a [Conventional Commits](https://conventionalcommits.org/)-compliant message. No config, no friction. Supports `--commit` flag for single-command stage-and-commit workflows. Uses `gpt-4o-mini` — fast and cheap on purpose.

```bash
git add . && gitwit --commit
# → feat(auth): add OAuth login support
```

---

### Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=debjit450&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&icon_color=58a6ff)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=debjit450&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e)

</div>

---

### Certifications

- **Google Cloud Digital Leader** — Google Cloud, Dec 2023

---

### Links

| | |
|---|---|
| 🌐 Portfolio | [debjit-dey-2026.vercel.app](https://debjit-dey-2026.vercel.app) |
| 💼 LinkedIn | [linkedin.com/in/debjit-dey](https://www.linkedin.com/in/debjit-dey) |
| 🐙 GitHub | [github.com/debjit450](https://github.com/debjit450) |
| 📬 Email | debjitdey450@gmail.com |

---

<div align="center">
<sub>I write code that ships, not code that demos.</sub>
</div>
