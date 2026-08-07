# Plumbline Studio

**Build it true.** A plumb line doesn't guess at vertical — it shows it. Plumbline Studio builds AI-assisted business tools the same way: every product answers to verification infrastructure we also built, so "it works" is demonstrated, not claimed.

Software studio in Roanoke, VA, founded by Kyle Knight.

## The showcase

- **[Plumb-bob](https://github.com/Plumbline-Studio/Plumb-bob)** — agentic verification engine for CI. Every PR is tested three ways: does it work (goal-directed browser testing), does it match the documented system (procedure-drift detection), and should it exist this way (principle gates that can veto a merge). Ships as a reusable GitHub Action.
- **[plumb-bob-console](https://github.com/Plumbline-Studio/plumb-bob-console)** — the run-report dashboard for Plumb-bob. Cloudflare Workers + Hono + D1/R2, schema-driven ingest.
- **[tool-maker-app](https://github.com/Plumbline-Studio/tool-maker-app)** — SME-to-software translation engine: record conversations with subject-matter experts, watch gap analysis fill in, produce code-ready briefs. Next.js, Supabase, pgvector, offline-capable PWA. [Live](https://app.toolwright.dev).
- **[OWT-community](https://github.com/Plumbline-Studio/OWT-community)** — community platform for makers. Next.js 15 on Cloudflare Workers, Supabase with row-level security everywhere, entitlements enforced in the database, deliberately anti-attention feed design. [Live](https://oldworldtrade.shop).
- **[Amoeba](https://github.com/Plumbline-Studio/Amoeba)** — 3D particle-life simulation. WebGL2 instanced rendering, structure-of-arrays physics with 27-cell spatial hashing, experimental GPU transform-feedback path. [Live demo](https://plumbline-studio.github.io/Amoeba/).
- **[bootlegger-k9](https://github.com/Plumbline-Studio/bootlegger-k9)** — client PWA (marketing site, gated video portal, admin pipeline, invoicing) with every third-party service behind a clean swap-in adapter.
- **[true-vertical](https://github.com/Plumbline-Studio/true-vertical)** — a published method for turning a psychological evaluation into a personalized operating manual, built for clinicians to hand to clients. CC BY 4.0.

## Elsewhere

[toolwright.dev](https://toolwright.dev) · kyle@toolwright.dev
