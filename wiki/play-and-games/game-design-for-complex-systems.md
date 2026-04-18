---
tags: [learning, complexity, simulation]
created: 2026-04-18
updated: 2026-04-18
---

# Game Design for Complex Systems

Game design for complex systems is a practical framework for creating games that serve as simplified simulations of complex systems. By deliberately manipulating design variables -- constraints, rules, space, agent density, objectives -- and iterating across rounds, a designer can help agents learn about system dynamics and help themselves understand how the system actually works. The act of designing a game is itself a form of system analysis: choosing what to include and what to leave out forces a deep engagement with the system's structure.

## Key points

- **Three objective levels operate simultaneously.** Every game designed for complex systems works at three levels: (1) the designer's learning objective -- what they want to discover about the system; (2) the game's global task -- what participants collectively try to achieve; and (3) each agent's individual objective -- which may or may not be known to other agents. These three levels interact, and the tensions between them generate the emergent dynamics that make the game informative.
- **Design variables are the levers.** The key variables a designer manipulates are constraints (time, space, connections between agents, agent density, agent diversity), rules (what agents can and cannot do), and task (the objective and focus of attention). Each variable can be independently varied to observe different system behaviors.
- **Iteration reveals system dynamics.** The power of this framework lies in systematic variation: changing objectives for each actor, modifying design variables, and introducing perturbations or mid-game changes across rounds. Because systems respond non-linearly to parameter changes, each iteration reveals new information about how the system self-organizes. Designers gain understanding not just from game outcomes but from the process of designing itself.
- **Different games for different agents.** Games for "new agents" (children, novices) focus on learning rules, perceiving other agents, and calibrating basic reactions. Games for "experienced agents" (adults, experts) focus on destabilizing established attractors, improving perception, and increasing response flexibility. The same system can be explored through very different games depending on the agents' experience level.

## Examples

- **Lego team project.** A game using Lego construction to explore team dynamics. Iterations include: starting with small independent teams, then forming larger teams, then swapping roles within teams, then mixing co-located and remote agents, then introducing disruptive agents, then changing objectives mid-project. Each iteration modifies a different design variable (agent density, diversity, constraints, objectives) and reveals a different aspect of how teams self-organize.
- **Shoulder mobility game.** Holding a weight plate like a teacup and moving it above the head and below the arm without "spilling." Iterations include: restricting trunk movement (adding a constraint), maximizing trunk movement (removing a constraint), adding a tennis ball on the plate (increasing task difficulty and focus of attention), varying speed (changing temporal constraints), and increasing weight (modifying load). Each variation forces the body to self-organize differently around the same basic task, revealing how movement systems respond to changing conditions.

## Connections

- [play-in-complex-systems.md](play-in-complex-systems.md) -- Game design formalizes the principles of play for intentional learning and system exploration
- [calibration.md](calibration.md) -- Well-designed games create the conditions for calibration of perception-action responses
- [../agents-and-dynamics/self-organization.md](../agents-and-dynamics/self-organization.md) -- Games reveal how agents self-organize under different conditions
- [../complex-problems/system-influence-parameters.md](../complex-problems/system-influence-parameters.md) -- Design variables map directly to the parameters through which systems can be influenced (objectives, focus, limits, constraints)
- [../agents-and-dynamics/exploration-vs-exploitation.md](../agents-and-dynamics/exploration-vs-exploitation.md) -- Games for novices emphasize exploration; games for experts destabilize exploitation patterns
- [../system-properties/attractors.md](../system-properties/attractors.md) -- Iterating game variables reveals attractor patterns and helps destabilize rigid ones
