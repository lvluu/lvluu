### Hi, I'm Luu Van Loi

Senior full-stack engineer in Da Nang, Vietnam. Java / Spring Boot, React, Kubernetes, and a lot of AI-assisted engineering lately. Open to remote roles.

[luuvanloi@duck.com](mailto:luuvanloi@duck.com) · [lvluu.is-a.dev](https://lvluu.is-a.dev/) · [LinkedIn](https://www.linkedin.com/in/luuvanloi/)

---

### What I work on

I like owning a feature all the way down: the data model, the Spring Boot service, the React screen, the Helm chart it ships in, and the CI check that stops it from breaking next month.

At work I build a large enterprise web app. Recent things I've built there:

- Spring Boot + PostgreSQL backend. Computed fields kept fresh through a transactional outbox, RBAC driven by a YAML role model, per-tenant numbering, Infinispan-backed `@Cacheable` caches.
- React with Redux + Redux Saga and TypeScript, Zod on every REST boundary, Vitest and Playwright for tests.
- Performance work. I moved the rich-text editor and OpenLayers out of the startup bundle with lazy routes, batched saga RPCs, stopped polling in hidden tabs and turned on the rspack persistent cache. My perf PRs carry before/after timings and RPC counts, because otherwise nobody believes them.
- Delivery: Helmfile deployments to Kubernetes, Keycloak, Jenkins pipelines, and a Python (`uv`) tooling workspace for linting, seeding and data migration.
- The AI setup the team ships with: a spec-driven workflow, Claude Code agents working in isolated git worktrees, a linter that turns our conventions into CI rules, automated browser verification on every PR with screenshot evidence, and a webhook watcher that wakes an agent when CI goes red or a reviewer comments.

The AI part is what I spend most of my thinking on right now. Agents write plenty of code. What I care about is making them show it works, and making them stop and ask when they can't.

### Side projects

| Project | What it is | Stack |
|---|---|---|
| [webhook-notifier](https://github.com/lvluu/webhook-notifier) | Horizontally scalable webhook delivery with per-tenant fair scheduling, retries, HMAC-SHA256 signing and a circuit breaker | Go |
| [git-ctx](https://github.com/lvluu/git-ctx) | Git identity profiles, directory rules and worktree sync from the CLI | Go |
| [PandaEnglish](https://panda-english.space/) | IELTS practice platform with AI feedback on all four skills (team project, I own the API) | TanStack Start, Hono/tRPC, Cloudflare Workers |
| [Smarter](https://smarter.chickeninkitchen.workers.dev/) | Knowledge feed that swaps doomscrolling for spaced repetition | React 19, Hono, Cloudflare Workers, D1 |
| [Primavista](https://primavista.chickeninkitchen.workers.dev/) | Local-first sight-reading practice for piano | React, Vite, IndexedDB, MusicXML |

In my free time I play with Proxmox, Linux and self-hosting.

---

### Tech stack

**Languages:** `Java` · `TypeScript` · `Go` · `Python` · `Rust` · `SQL`  
**Backend:** `Spring Boot` · `Node.js` · `Hono` · `Keycloak` · `Infinispan`  
**Databases:** `PostgreSQL` · `MySQL` · `Redis` · `SQLite` · `Cloudflare D1` · `MongoDB`  
**Frontend:** `React` · `Redux Saga` · `Vite` · `rspack` · `Zod` · `Playwright` · `Vitest`  
**DevOps & Cloud:** `AWS` · `Kubernetes` · `Helm` · `Helmfile` · `Docker / Podman` · `Terraform` · `Ansible` · `Jenkins` · `GitHub Actions` · `Grafana` · `Prometheus` · `Cloudflare Workers`  
**AI tooling:** `Claude Code` · `MCP servers` · `multi-agent orchestration` · `LLM provider fallback chains`  
**Homelab:** `Proxmox` · `Linux` · `networking` · `virtualization` · `monitoring`
