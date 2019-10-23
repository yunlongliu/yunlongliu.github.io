---
layout: archive
title: "Research Proposal"
permalink: /research/
author_profile: true
---

My main research passion is on building autonomous agent that learns to act rationally in various environments, which is generally referred to as reinforcement learning (RL). I have worked on [finding efficient ways to explore RL environments](https://liuanji.github.io/publication/2019-09-05-AAC) and [deploying novel parallelization Monte Carlo Tree Search (MCTS) algorithms for large scale Game AI tasks](https://liuanji.github.io/publication/2019-09-25-P-UCT).

For me, one of the promising but under-explored areas in RL is model-based reinforcement learning (MBRL). In addition to learning policy or value function, MBRL uses a learned transition model to improve learning performance. One well-recognized benefit of MBRL is to reduce sample complexity, greatly lower the need to interact with the real environment. Moreover, MBRL can even provide a principled exploration strategy.

However, learning the world model is hard, and it is even harder to get things right in MBRL. In most cases, even if a low-error world model is available, directly planning on it produces bad policy. The following are three main reasons: (i) small model errors accumulate during roll-out and at the end provides "garbage" states; (ii) most world models (e.g. deep neural networks) learn the expected next state, which is not necessarily a valid state; (iii) world models are not aware of their uncertainty. 

Among the three problems, I think (i) is generally unavoidable. Even if we are able to cut-off big errors sometimes, we are generally not able to learn a model good enough to have small multi-step error, let alone the affection caused by insufficient exploration (lack of training data) in some regions. Therefore, (ii) and (iii) should be the main focus of MBRL. In the literature, there are many people focusing on solving these two problems mainly using deep neural networks. However, since neural nets sacrifices many things on the inference side (e.g. well-defined and calibrated uncertainty) for expressiveness, it does not solve (ii) and (iii) well.

I was then attracted by tractable probabilistic models (TPMs), which are probabilistic models that enable polynomial time (in most cases, linear time) computation of marginal, MAP, expectation, etc. Indeed, they are not as expressive as neural networks, but solving MBRL purely from increasing model expressiveness seems impractical. One apparent reason is that these models need tremendous amount of data, which opposes the principle of MBRL - increase sample efficiency. I am working on getting one step forward towards solving MBRL using Probabilistic Sentential Decision Diagrams (PSDD), a TPM that enables tractable computation of many advanced queries (e.g. moments, KL divergence). It is exciting that we may be able to gain benefit from inaccurate world models in general tasks.

