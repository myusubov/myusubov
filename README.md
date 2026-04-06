<img src="https://9nghnaawajmv9mqf.public.blob.vercel-storage.com/github-header-banner.png" alt="GitHub Banner" width="100%" />

<h1 align="center">Murad Yusubov | Full-Stack Engineer</h1>
<p align="center">
Full-Stack Engineer building state-heavy product applications with scalable architecture and thoughtful AI integration.
</p>

---

## About Me

I’m a Full-Stack Engineer focused on Next.js, Node.js, and event-driven backend workflows.

My strongest work is around systems that need more than standard CRUD: long-running AI jobs, real-time progress updates, queue-based processing, and backend architectures that stay predictable under production pressure.

I care about clear system boundaries, reliability, and practical engineering decisions over buzzwords.

**Current focus:** TailorCV, asynchronous AI pipelines, and scalable Node.js backends.

---

## Featured Project

### [TailorCV](https://github.com/myusubov/tailorcv) | Async AI Resume Pipeline
AI-assisted resume platform built to process technical proof-of-work through a queue-driven architecture instead of blocking synchronous requests.

**Live:** [tailorcv.xyz](https://tailorcv.xyz)

#### What makes it technically interesting

- **Asynchronous job architecture:** Built a BullMQ-based pipeline to handle long-running LLM workloads without request timeouts.
- **Real-time progress updates:** Streamed worker progress to the client using Redis Pub/Sub and Server-Sent Events.
- **Context compression:** Reduced token usage by ~40% by pruning noisy repository data while preserving high-signal technical context.
- **Separation of concerns:** Decoupled request intake, background execution, and client updates into distinct layers for more predictable behavior.
- **AI grounded in structured inputs:** Built the generation flow around normalized technical evidence rather than freeform prompting.

#### Core stack

- Next.js 16
- React 19
- Node.js / Express
- PostgreSQL + Prisma
- Redis
- BullMQ
- OpenAI SDK
- SSE

---

## Selected Work

I’ve also built and shipped supporting full-stack projects around client workflows and data-heavy interfaces, but TailorCV is the main project where my backend and systems thinking are most visible.

For current professional work, I’ve been leading frontend and systems-heavy implementation on an AI-native CRM, including complex data views, pipeline interactions, and schema-driven UI architecture. :contentReference[oaicite:0]{index=0}

---

## Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript, SQL, Python |
| **Frontend** | Next.js, React, TanStack Query, Tailwind CSS |
| **Backend** | Node.js, Express, PostgreSQL, Prisma |
| **Infrastructure** | Redis, BullMQ, SSE, Vercel, Docker |
| **Validation & State** | Zod, Zustand |
| **AI** | OpenAI SDK, context compression, structured prompt pipelines |

---

## What I Optimize For

- **Clear system design:** predictable data flow, separation between request handling and background execution
- **Reliability:** queue-based processing, graceful failure handling, reduced timeout risk
- **Performance:** minimizing unnecessary work across API, worker, and client update paths
- **Technical clarity:** systems that are understandable to maintain, not just impressive to describe

---

## Current Direction

I’m most interested in remote engineering work involving:

- Next.js and Node.js product engineering
- Event-driven architecture
- Real-time systems
- AI-assisted product infrastructure
- Backend-heavy full-stack roles where system design matters

---

## Connect

- **Portfolio:** [muradyusubov.dev](https://muradyusubov.dev)
- **LinkedIn:** [linkedin.com/in/murad-yusubov](https://linkedin.com/in/murad-yusubov/)
- **Email:** me@muradyusubov.dev
