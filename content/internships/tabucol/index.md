---
title: "RL and Tabu Search for Graph Coloring Problems"
subtitle: ""
summary: "Learning to solve graph coloring problems and exploring ideas combining RL and tabu search for combinatorial optimization." 
date: "2020-11-20T00:00:00+01:00"
draft: false
share: false
commentable: false
editable: false
weight: 10
# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---

**Supervisors**:  [Philippe Preux](https://philippe-preux.github.io/), [Nathan Grinsztajn](https://nathangrinsztajn.github.io/)

**Duration**: 5 to 6 months

**When**: Spring-Summer 2021

**Where**:  [Scool](https://team.inria.fr/scool/) (previously [SequeL](http://sequel.lille.inria.fr/)), Inria Lille, Villeneuve d'Ascq, France

**Expected background**: master in CS, specialized in machine learning.

**Keywords**: reinforcement learning, combinatorial optimization, experimental.

**Context**:
Reinforcement learning is a sub-field of machine learning in which we aim at designing agents that learn to act. Acting usually involves performing a sequence of actions in order to achieve a goal. Examples are countless; games are good examples, like Pacman or chess in which the player has to perform a series of actions either to reach a maximal score, or to defeat his opponent. Applications of RL go way beyond games.

Recently, there were trials to use RL  to solve hard combinatorial problems. Some major examples (and successes) are GO, Rubiks Cube, Scheduling, Maximum Independent Set (MIS), Maximum Coverage (MC), Minimum Vertex Cover (MVC)... Graph coloring, however useful in practice (bandwidth allocation, scheduling...) and difficult, received less attention. State of the art graph coloring solvers still mainly rely on tabu search (tabucol), and hand-crafted heuristics. It is to be expected that hybriding RL and tabu search will provide more efficient algorithms.

**What**:
The goal of this internship is to:
- Study the literature of this problem. This includes deep reinforcement learning, graph neural networks, graph coloring, tabu search.
- Perform an experimental assessment of the ideas.
- Explore new ideas on combining RL and tabu search (or other search algorithms). This exploration can be theoretical or algorithmic.

**Bibliography**:
- Sutton, Barto,  [Reinforcement Learning, an Introduction](http://incompleteideas.net/book/the-book.html), 2nd edition, 2018
- A. Hertz, D. de Werra, [Using tabu search techniques for graph coloring](https://link.springer.com/article/10.1007/BF02239976). _Computing_  **39,** 345–351 (1987).

**Working environment**:  [Scool](https://team.inria.fr/scool/) (previously [SequeL](http://sequel.lille.inria.fr/)) is a well-known research group in reinforcement learning and bandits. It is composed of 5 permanent researchers, 20+ PhD students, a couple of post-docs and engineers. Scool provides a very rich and stimulating for doing cutting-edge research in RL.
