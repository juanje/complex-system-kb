---
tags: [complexity, simulation, modeling]
created: 2026-04-18
updated: 2026-04-18
---

# Agent-Based Models

Agent-based models (ABMs) are computer simulations where each agent is individually represented with its own characteristics, behavior rules, and position in space. Rather than modeling a system through aggregate equations and flows, ABMs build the system from the bottom up: define each agent, define the rules governing their interactions, press play, and observe what emerges. This approach makes ABMs currently the most powerful tool for understanding complex systems, because they capture the three dimensions that matter most — agent diversity, spatial localization, and emergent behavior from local interactions.

## Key points
- **ABMs vs. dynamic systems models:** Traditional dynamic systems models focus on flows and stocks (aggregate quantities moving between compartments). ABMs add two critical dimensions: agent diversity (each agent is different, with its own characteristics) and spatial localization (where agents are located influences how they interact). Because proximity and individuality produce different interaction patterns, ABMs generate more realistic emergent behaviors.
- **The modeling process itself teaches you about the system.** The effort of defining a system faithfully enough to build an ABM — deciding which agents to include, what rules they follow, what variables matter — forces a deep engagement with how the system actually works. Experts consider this one of the main advantages of ABMs, beyond the simulation results themselves.
- **ABMs allow safe experimentation.** You can test different scenarios, vary parameters, inject perturbations, and observe how the system evolves under conditions that would be impossible, unethical, or too expensive to test in reality.
- **Every model is a simplification.** As Alfred Korzybski said, "the map is not the territory." An ABM must contain enough information to be useful and representative, but must be simplified enough to work with. If a simulation becomes so simple that it is deterministic, it has been oversimplified and is no longer representative of the complex system.

## Examples
- **Wolf-sheep ecosystem model:** Each wolf and sheep is represented individually with characteristics (age, size, health status) and behavior rules (eat, reproduce if surplus, move toward food, flee from predators). Running the simulation reveals emergent phenomena: pack formation, population cycles, and climate effects on the ecosystem — none of which were explicitly programmed, all arising from local interactions.
- **Schelling segregation model (1971):** The first ABM ever used to explain a complex system phenomenon. Each agent has a tolerance threshold and moves when dissatisfied with its neighborhood composition. The emergent result — complete segregation from tolerant individuals — demonstrated the power of bottom-up modeling to reveal counterintuitive system dynamics.
- **Games as human ABMs:** Games and play serve a function analogous to ABMs for systems involving strong agents (humans). Like ABMs, games simulate situations where agent interactions are key — but unlike ABMs, games help agents understand rules and the system from the inside rather than observing from outside.

## Connections
- [schelling-segregation-model.md](schelling-segregation-model.md) — The foundational ABM that demonstrated how micro-level tolerance produces macro-level segregation.
- [self-organization.md](self-organization.md) — ABMs simulate self-organization by implementing local rules and observing emergent global patterns.
- [agents.md](agents.md) — Agents are the fundamental units that ABMs represent individually, each with its own state and behavior rules.
- [network-science.md](network-science.md) — ABMs naturally produce emergent network structures as agents interact and form connections.
- [Play](../play-and-games/play-in-complex-systems.md) — Play and games are the human-scale equivalent of ABMs, allowing strong agents to simulate and explore system dynamics from the inside.
- [dynamic-equilibrium.md](dynamic-equilibrium.md) — ABMs often reveal dynamic equilibrium: populations and variables fluctuating around stable patterns rather than reaching static states.
