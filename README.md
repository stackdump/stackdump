# Stackdump

Hi, I'm Matt York — a programmer first, math hobbyist second. By day I build blockchain transaction ingestion and agentic tooling for protocol integrations at [Anchorage Digital](https://www.anchorage.com). By night I've spent about a decade on **pflow**: treating Petri nets as a universal intermediate representation for event-driven systems.

![Matt York - profile](./profile.jpg)

## What I'm Building

| Project | What it does |
|---------|-------------|
| [sim.pflow.xyz](https://sim.pflow.xyz) | Auto-formalizer — informal spec in, executable model out, with a proof and a fidelity verdict. Also an MCP server, so LLMs can show their work in a format you can inspect. |
| [beats.bitwrap.io](https://beats.bitwrap.io) | Generative music running on Petri net execution — Euclidean rhythms, Markov chains, content-addressed tracks you can share by CID |
| [dj.bitwrap.io](https://dj.bitwrap.io) | Native macOS DJ app built on the beats engine |
| [pflow.xyz](https://pflow.xyz) | Browser-based visual editor, ODE simulator, and JSON-LD schema endpoint |
| [pflow native](https://github.com/pflow-xyz/pflow-native) | Native desktop editor built on pflow-rs — model, simulate, and visualize nets offline |
| [go-pflow](https://github.com/pflow-xyz/go-pflow) · [pflow-rs](https://github.com/pflow-xyz/pflow-rs) | Core libraries — modeling, simulation, process mining, ZK proofs |

## The Ideas

- **The model is the explanation.** A ledger already *is* a Petri net — double-entry bookkeeping is token conservation. Make the structure explicit and correctness becomes something that can't be otherwise, not something you check.
- **Three independent witnesses.** The same net is checked in Lean, proven in Groth16 ZK circuits, and run as an ODE simulation. When all three agree, that's structural evidence, not a test pass.
- **Past-tense computation.** The tropical (max-plus) semiring summarizes what has fired; predicates constrain what can fire next; the current marking is the boundary between them.
- **Models over prose.** LLMs are good at extracting the latent structure of a system from plain language. Landing that structure in a simulatable model makes their contribution auditable.

Long form: [*Petri Nets as a Universal Abstraction*](https://book.pflow.xyz) — 18 chapters, from first principles through ZK verification.

## Links

- **Blog**: [blog.stackdump.com](https://blog.stackdump.com)
- **Book**: [book.pflow.xyz](https://book.pflow.xyz)
- **Editor**: [pflow.xyz](https://pflow.xyz)
- **Organization**: [github.com/pflow-xyz](https://github.com/pflow-xyz)
