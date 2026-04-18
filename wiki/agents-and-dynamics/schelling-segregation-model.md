---
tags: [complexity, social-systems, simulation]
created: 2026-04-18
updated: 2026-04-18
---

# Schelling Segregation Model

In 1971, Nobel Prize-winning economist Thomas Schelling developed what is considered the first agent-based model used to explain phenomena in complex systems. The model demonstrates one of the most counterintuitive insights in complexity science: individually tolerant agents can produce a fully segregated system. Each agent in the model is comfortable with up to 65% different neighbors — they would only move if fewer than 35% of neighbors are similar to them. Yet the system-level outcome is complete segregation into homogeneous neighborhoods.

## Key points
- **Micro-tolerance produces macro-segregation.** Each agent is individually tolerant, but when a dissatisfied agent moves, it changes the environment for others. This triggers a feedback loop: one agent's move makes another agent's neighborhood less diverse, pushing that agent past its threshold, causing another move, and so on. The cascade drives increasing separation even though no individual agent wants segregation.
- **This was the first agent-based model.** Schelling's model established a foundational methodology for studying complex systems: represent each agent individually with its own characteristics and rules, then observe what emerges from their interactions. This bottom-up approach revealed dynamics invisible to aggregate statistical analysis.
- **Diversity of thresholds accelerates the process.** When agents have different tolerance thresholds, the ones with the lowest thresholds move first. Their movement pushes others past their thresholds, creating cascading, avalanche-like changes that dramatically accelerate segregation. This demonstrates how threshold diversity amplifies system-level dynamics.
- **The model reveals the divergence between micro and macro behavior.** You cannot predict system-level outcomes by studying individual agent preferences — the whole behaves in a fundamentally different way from its parts. This is a core principle of complex systems that the Schelling model made concrete and demonstrable.

## Examples
- **Schelling's original city model:** Agents represent people with different characteristics (race, political views, religion) living in a city grid. Each tolerates diversity but moves when too few similar neighbors exist nearby. Over iterative rounds, the tolerant agents self-segregate into homogeneous neighborhoods — a result none of them individually desired or intended.
- **Cascading threshold effects in demonstrations:** In a peaceful demonstration where participants have tolerance thresholds ranging from 1 to 10, a single small event can trigger a cascading escalation. The person with threshold 1 reacts first, their reaction pushes the person with threshold 2 past their limit, and so on — the same cascade mechanism that drives Schelling's segregation also explains how peaceful gatherings can rapidly escalate into violence.

## Connections
- [agent-based-models.md](agent-based-models.md) — The Schelling model is the foundational example of agent-based modeling, establishing the methodology that ABMs still follow.
- [threshold.md](threshold.md) — Thresholds are the core mechanism driving the Schelling model's dynamics: agents move when their tolerance threshold is crossed.
- [self-organization.md](self-organization.md) — Segregation in the model is not designed or imposed — it emerges from self-organization through local agent decisions.
- [Emergence](../system-properties/emergence.md) — The model is a textbook demonstration of emergence: system-level segregation is a qualitatively different outcome from individual-level tolerance.
- [externality.md](externality.md) — Each agent's move creates externalities for neighbors, changing their environment and potentially pushing them past their own thresholds.
