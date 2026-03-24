# Trinetra Vision

**Trinetra** is a full-stack, full-working-model code generation platform.
It turns a plain-English product description into a complete, deployable software system —
not just UI components, but every layer: frontend, backend, database, third-party API wiring,
deployment configuration, and a generated architecture document that matches the code.

## The Problem We Solve

Every vibe coding tool today produces a **beautiful skeleton**: great-looking UI with
no real wiring underneath. APIs are stubbed. Databases are mocked. Authentication is a
`// TODO`. Deployment is left as homework.

Trinetra changes that. One prompt. One `docker compose up`. Everything works.

## The Three Eyes

Trinetra is named for the Sanskrit concept of the third eye — seeing beyond the visible surface.
It operates on three generative layers:

1. **Interface** — Frontend components, routing, state management
2. **Logic & Integration** — Backend services, real third-party API wiring, database schemas
3. **Architecture & Infrastructure** — Docker, Kubernetes, CI/CD, secrets management, observability

## Core Differentiators

| Existing tools | Trinetra |
|---|---|
| Frontend only, or frontend + stub backend | Full stack, every layer |
| API integrations stubbed with TODO | Real SDK calls, real OAuth, real error handling |
| No deployment config | Docker Compose + K8s manifests generated |
| No architecture documentation | `ARCHITECTURE.md` generated and kept in sync |
| No test coverage | Integration + unit tests that actually pass |
| Developer still does 80% of the work | Developer reviews, not rebuilds |

## Key Innovations

- **Architecture Interview** — 5-7 targeted questions resolve ambiguity before any code is written
- **System Blueprint** — machine-readable service contract shared by all generation agents
- **Multi-Agent Pipeline** — Architect, Frontend, Backend, Integration, DevOps, Test, and Review agents, each specialized
- **Wiring Validator** — static analysis that checks every declared dependency is actually wired in code before delivery
- **TTFR metric** — Time to First Real Request; every generation is measured and must pass a 5-minute threshold
- **Explode Mode** — start minimal, expand incrementally with `trinetra expand --add-auth`, `--add-payments`, etc.

## Relationship to OpenClaw

OpenClaw runs tasks at runtime. Trinetra generates systems before runtime.
They are complementary: use Trinetra to generate a new OpenClaw plugin, fully wired
with SDK calls, tests, and documentation.

## Full Research Document

See [`docs/trinetra-product-research.md`](docs/trinetra-product-research.md) for:
- Detailed landscape analysis of all major vibe coding tools
- Side-by-side capability comparison table
- Full system architecture diagrams
- System Blueprint JSON schema
- Wiring Validator rule examples
- Phased roadmap (Phases 1–3)
- Technical stack decisions
- Go-to-market strategy

---

*Status: Research & Vision | Version: 1.0*
