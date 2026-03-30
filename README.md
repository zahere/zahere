# Zaher Khateeb | AI/ML Engineer
 
**Founder of [AgentiCraft](https://agenticraft.ai)** — an 8-layer service mesh for production multi-agent systems.
 
I specialize in multi-agent systems architecture, LLM infrastructure, and distributed systems reliability. My work sits at the intersection of formal methods and production engineering — building systems that are provably correct, not just empirically okay.
 
---
 
### What I've Built
 
**[AgentiCraft](https://agenticraft.ai)** — designed and built solo over 18 months:
 
- **Data Plane (Layer 2):** ~70K-line Rust proxy across 7 crates — 28-layer middleware pipeline, Thompson Sampling routing across 17 LLM providers via PyO3, MCP/A2A codec handlers, CUSUM circuit breakers. 1,340+ tests, zero clippy warnings.
- **Control Plane (Layer 3):** 40+ Python mesh services, 50+ agent presets, 9 communication backends
- **Runtime (Layer 4):** Go-based Kubernetes operator, Docker, subprocess, and edge adapters
- **Foundation (Layer 0):** Formal verification engine — CSP process algebra, multiparty session types, CTL model checking, probabilistic verification. **[Open source](https://github.com/agenticraft/agenticraft-foundation)** (1,300+ tests, 8 modules, Apache 2.0)
- **Working Product (Layer 7):** Multi-agent Telegram bot with 3 agents (financial, calendar, research), persistent memory, HITL approval workflows
 
Full architecture spans Layers 0–7 with NATS transport (L1), craft CLI and SDK (L5), and declarative app framework (L6).
 
---
 
### Current Research
 
**Fault-Dependent Resilience in Multi-Agent LLM Systems**
 
Extending classical network reliability theory to stochastic agent quality. The core result: an iff characterization of when topology choice actually matters — crash-stop faults make all mesh topologies equivalent (a mathematical identity), while Byzantine faults break that equivalence in ways determined by the coordination protocol, not the graph structure.
 
Validated across ~34,000 LLM experiments spanning 13 coordination topologies, two fault regimes, two task domains, and two model generations.
 
**Standalone libraries from this research:**
 
| Library | Description |
|---------|-------------|
| [stochastic-circuit-breaker](https://github.com/zahere/stochastic-circuit-breaker) | CUSUM-optimal circuit breaker for LLM agents and stochastic systems. 4-state FSM with provably minimax detection delay. |
| [reliability-polynomials](https://github.com/zahere/reliability-polynomials) | Generalized reliability polynomials where coefficients encode quality, not just connectivity. Fault-dependent crossover analysis. |
 
---
 
### Technical Focus
 
**Multi-Agent Systems** — mesh coordination architecture, fault-dependent topology selection, Byzantine fault tolerance for LLM systems, stochastic service mesh, MCP/A2A protocol integration
 
**Formal Methods** — session type theory for deadlock-freedom guarantees, runtime property verification, CSP process algebra, refinement checking
 
**LLM Infrastructure** — provider-agnostic inference abstraction, statistical circuit breakers with CUSUM-optimal change detection, quality-weighted reliability theory
 
**Distributed Systems** — consensus protocols, fault injection and fault modeling, observability, Kubernetes-native deployment
 
---
 
### Tech Stack
 
**Languages:** Python, Rust, Go, C++, TypeScript, SQL, Bash
 
**AI/ML:** PyTorch, RAG, fine-tuning (LoRA, QLoRA), LLM evaluation, OpenTelemetry
 
**Infrastructure:** Kubernetes, Docker, Helm, NATS JetStream, gRPC/Protobuf, Nuitka, CI/CD, PostgreSQL, Redis, Qdrant
 
**Cloud:** AWS, GCP, Azure, Nebius AI Cloud
 
---
 
### Background
 
- B.Sc. Industrial Engineering & Management (Data Science concentration) — Tel Aviv University
- AI Performance Engineering — Nebius Academy, Tel Aviv University (current, 2026)
- Advanced Data Science & AI Program — Nebius Academy (Y-DATA), Tel Aviv University
- Previously: AI & Infrastructure Engineer at Visual Arena (Gothenburg, Sweden)

---

[![Website](https://img.shields.io/badge/agenticraft.ai-0D9488?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA2NCA2NCIgd2lkdGg9IjY0IiBoZWlnaHQ9IjY0Ij48cG9seWdvbiBwb2ludHM9IjM5LDcgNTMsMjQgMzYsMjgiIGZpbGw9IndoaXRlIiBvcGFjaXR5PSIwLjg1Ii8+PHBvbHlnb24gcG9pbnRzPSIzOSw3IDEyLDMzIDM2LDI4IiBmaWxsPSJ3aGl0ZSIgb3BhY2l0eT0iMC43Ii8+PHBvbHlnb24gcG9pbnRzPSI1MywyNCA0Nyw0OSAzNiwyOCIgZmlsbD0id2hpdGUiIG9wYWNpdHk9IjAuNzUiLz48cG9seWdvbiBwb2ludHM9IjQ3LDQ5IDIyLDU0IDM2LDI4IiBmaWxsPSJ3aGl0ZSIgb3BhY2l0eT0iMC45Ii8+PHBvbHlnb24gcG9pbnRzPSIyMiw1NCAxMiwzMyAzNiwyOCIgZmlsbD0id2hpdGUiIG9wYWNpdHk9IjAuOTUiLz48Y2lyY2xlIGN4PSIzOSIgY3k9IjciIHI9IjMiIGZpbGw9IndoaXRlIi8+PGNpcmNsZSBjeD0iNTMiIGN5PSIyNCIgcj0iMi44IiBmaWxsPSJ3aGl0ZSIvPjxjaXJjbGUgY3g9IjQ3IiBjeT0iNDkiIHI9IjIuOCIgZmlsbD0id2hpdGUiLz48Y2lyY2xlIGN4PSIyMiIgY3k9IjU0IiByPSIyLjgiIGZpbGw9IndoaXRlIi8+PGNpcmNsZSBjeD0iMTIiIGN5PSIzMyIgcj0iMyIgZmlsbD0id2hpdGUiLz48Y2lyY2xlIGN4PSIzNiIgY3k9IjI4IiByPSIzLjIiIGZpbGw9IndoaXRlIi8+PC9zdmc+)](https://agenticraft.ai)
[![AgentiCraft](https://img.shields.io/badge/GitHub-AgentiCraft-181717?style=for-the-badge&logo=github)](https://github.com/agenticraft)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/zahere/)
