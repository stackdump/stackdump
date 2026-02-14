# Stackdump

Hi, I'm Matt York — engineer, blockchain researcher, and creator of [pflow.xyz](https://pflow.xyz), a Petri net toolkit for modeling complex systems.

![Matt York - profile](./profile.jpg)

## What I'm Building

[**pflow**](https://github.com/pflow-xyz) — an ecosystem of tools that treat Petri nets as a universal abstraction for state machines, workflows, and verifiable computation.

| Project | What it does |
|---------|-------------|
| [pflow-xyz](https://github.com/pflow-xyz/pflow-xyz) | Browser-based visual editor and ODE simulator |
| [go-pflow](https://github.com/pflow-xyz/go-pflow) | Go library — modeling, simulation, process mining, ZK proofs |
| [petri-pilot](https://github.com/pflow-xyz/petri-pilot) | MCP server for AI-assisted design and deterministic full-stack codegen |
| [pflow-jl](https://github.com/pflow-xyz/pflow-jl) | Julia framework for Petri net visualization and analysis |

**Try it:** [18 interactive demos](https://pilot.pflow.xyz) — games, workflows, scientific models, and more.

## How It Works

A Petri net model defines places (states), transitions (actions), and arcs (connections). From that single JSON-LD file:

- **go-pflow** simulates it — discrete-event, continuous-time ODE, or ZK proof generation
- **petri-pilot** generates a full-stack app — Go backend, ES modules frontend, GraphQL API
- **pflow-xyz** lets you build and edit it visually in the browser

The LLM designs models. Templates produce apps. No LLM-generated code in the output.

## Mission

Petri nets provide **transparent, deterministic logic** — the model itself is the explanation. I'm working to make them practical and accessible through open tools, minimal dependencies, and visual interfaces.

- Vanilla JS/ES modules, Go backends, SQLite — no framework bloat
- Dual execution (Go + JS) for verifiable correctness
- Content-addressed storage (IPFS CIDv1) for immutable models
- ZK proofs for trustless state transition verification

## Links

- **Visual Editor**: [pflow.xyz](https://pflow.xyz)
- **Interactive Demos**: [pilot.pflow.xyz](https://pilot.pflow.xyz)
- **Blog**: [blog.stackdump.com](https://blog.stackdump.com)
- **Organization**: [github.com/pflow-xyz](https://github.com/pflow-xyz)
