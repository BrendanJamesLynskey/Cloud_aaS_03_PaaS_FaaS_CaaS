# 🛠 PaaS · FaaS · CaaS — Managed Compute

Deck **03 of 6** in the [Cloud `*aaS` series](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub). The managed-compute middle — Heroku-style and frontend PaaS, "run my container" CaaS, managed Kubernetes, FaaS / serverless and edge functions, with a head-to-head decision matrix.

## ▶ [Open the Presentation](https://brendanjameslynskey.github.io/Cloud_aaS_03_PaaS_FaaS_CaaS/)

## 🧭 [Series hub](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub)

---

## Contents

| # | Topic | Description |
|---|-------|-------------|
| 01 | Title | git push → live URL |
| 02 | Topics | PaaS / CaaS / FaaS / choice |
| 03 | The managed-compute spectrum | Bottom-to-top diagram of unit, control, scale-to-0, billing |
| 04 | Heroku-style PaaS | Heroku, Render, Fly, Railway, Koyeb — feature/price comparison |
| 05 | Hyperscaler PaaS | Beanstalk, App Runner, App Engine, App Service — and the Beanstalk warning |
| 06 | Frontend-shaped PaaS | Vercel, Netlify, Cloudflare Pages — same-day frontends, framework lock-in |
| 07 | Buildpacks · Dockerfiles · Nixpacks | Three approaches, build-in-PaaS vs build-in-CI |
| 08 | "Run my container" CaaS | Cloud Run / Fargate / App Runner / Container Apps / Fly Machines / CF Containers — comparison table |
| 09 | Managed Kubernetes | EKS / GKE / AKS, Autopilot / Auto Mode, critical add-ons, the cost truth |
| 10 | FaaS — how a Lambda actually runs | Caller → frontend → worker μVM → handler diagram, cold/warm/burst paths |
| 11 | Cold starts | What contributes, mitigations, p50/p99 numbers across runtimes |
| 12 | Edge FaaS — V8 isolates | Workers / Edge Functions / Deno Deploy / Compute@Edge, KV / D1 / Durable Objects |
| 13 | Event-driven patterns | Queues, storage, DBs, orchestration (Step Functions, Temporal), idempotency, DLQs |
| 14 | Cost comparison | Same workload across IaaS / K8s / CaaS / PaaS / FaaS, where the curve flips |
| 15 | Deployment strategies | Rolling, blue/green, canary, feature flags, the forgotten DB-migration half |
| 16 | Decision matrix | "You are…" → recommended layer, with reasoning |
| 17 | Anti-patterns | Lambda-for-everything, K8s-for-everything, Vercel-as-backend, free-tier-runaway |
| 18 | Summary | Three takeaways &amp; next-deck pointer |

---

## Slide Controls

| Action | Key |
|--------|-----|
| Next / Previous | `→` `←` or swipe |
| Overview | `Esc` |
| Fullscreen | `F` |
| Speaker notes | `S` |
| Export to PDF | append `?print-pdf` to URL, then print |

## Technology

[Reveal.js 4.6](https://revealjs.com) · [highlight.js](https://highlightjs.org) · Playfair Display + DM Sans + JetBrains Mono · inline SVG diagrams. Single self-contained `index.html`.

## See also

- Previous in series: [Cloud_aaS_02_IaaS_Foundations](https://github.com/BrendanJamesLynskey/Cloud_aaS_02_IaaS_Foundations) — the layer underneath
- Next in series: [Cloud_aaS_04_SaaS_Architecture](https://github.com/BrendanJamesLynskey/Cloud_aaS_04_SaaS_Architecture) — the layer above
- [Deploying with Docker](https://github.com/BrendanJamesLynskey/Deploying_with_Docker) — what you put on these platforms
- [Deploying Web Applications](https://github.com/BrendanJamesLynskey/Deploying_Web_Applications) — beginner introduction
- [Introduction to CI/CD](https://github.com/BrendanJamesLynskey/Introduction_to_CI_CD) — the pipeline that drives every deploy
- [Docker series](https://github.com/BrendanJamesLynskey/Software#docker) — building images for these platforms

## License

Educational use. Code examples provided as-is.
