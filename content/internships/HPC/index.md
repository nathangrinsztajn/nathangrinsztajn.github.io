---
title: "RL for Dynamic Task Graph Scheduling"
subtitle: ""
summary: "Task Graph Scheduling is the activity that consists in mapping a task graph onto a target platform: nodes denote computational tasks, and edges model precedence constraints between tasks.
When the full graph is unknown at the beginning of the scheduling (e.g. because of user interactions), known heuristics fall short. We propose to study and implement a RL approach to solve this kind of task." 
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
Combinatorial Optimization Problems (COP) constitute an important family of fundamental problems: traveling salesman, vehicle routing problem, stable marriage , graph coloring, task scheduling, and many others.
There are various algorithmic approaches, ranging from (provably) exact methods (*e.g.* based on tree search, linear programming...) to non (provably) exact/approximate methods (heuristics and meta-heuristics). Those methods are able to solve large scale COPs, but they require a careful investigation of the problem.

On the other hand, real world applications bring another set of challenges: inherent uncertainty in the definition of the problem and randomness in the process dynamics.
Task Graph Scheduling consists in mapping a task graph onto a target platform: nodes denote computational tasks, and edges model precedence constraints between tasks.
When the full graph is unknown at the beginning of the scheduling (e.g. because of user interactions), known heuristics fall short. We propose to study and implement a RL approach to solve this kind of task.

**What**:
The goal of this internship is to:
- Study the literature of this problem. This includes deep reinforcement learning, graph neural networks, task graph scheduling.
- Perform an experimental assessment of these ideas.
- Explore new ideas on combining RL and dynamic graphs (*e.g.* the Canadian Traveller Problem (CTP)). This exploration can be theoretical or algorithmic.

**Bibliography**:
- Sutton, Barto,  [Reinforcement Learning, an Introduction](http://incompleteideas.net/book/the-book.html), 2nd edition, 2018
- Aditya  Paliwal et al, [Reinforced  genetic  algorithmlearning  for  optimizing  computation  graphs](https://arxiv.org/abs/1905.02494). InProc.  ICLR,  page  24,2020
- Grinsztajn et al, [Geometric Deep Reinforcement Learning for Dynamic DAG Scheduling](https://arxiv.org/abs/2011.04333). Advances in IEEE ADPRL (ADPRL 2020).

**Working environment**:  [Scool](https://team.inria.fr/scool/) (previously [SequeL](http://sequel.lille.inria.fr/)) is a well-known research group in reinforcement learning and bandits. It is composed of 5 permanent researchers, 20+ PhD students, a couple of post-docs and engineers. Scool provides a very rich and stimulating for doing cutting-edge research in RL.
