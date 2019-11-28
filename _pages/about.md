---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a visiting researcher at [Statistical and Relational Artificial Intelligence (StarAI) lab](http://starai.cs.ucla.edu/members/) in UCLA, led by professor [Guy Van den Broeck](http://web.cs.ucla.edu/~guyvdb/). My research passion is on the intersection of reinforcement learning (RL) and tractable inference models that add domain knowledge as well as model uncertainty in the environment. Before joining StarAI lab, I was a machine learning intern at Seattle AI Lab, Kwai Inc. My supervisor was [Ji Liu](https://scholar.google.com/citations?user=RRzVwKkAAAAJ&hl=zh-CN) and [Jianshu Chen](https://chenjianshu.github.io/). During my internship, I worked on game AI and reinforcement learning. Before that, I earned my B.S. degree in Automation at the school of automation science and electrical engineering in [Beihang University](https://ev.buaa.edu.cn/) (BUAA), working under the advisement of professor [Yuanjun Laili](http://shi.buaa.edu.cn/yunglynn/en/index.htm).

Research interests
======
My current research passion is on building autonomous agent that learns to act rationally in various environments, which is generally referred to as reinforcement learning (RL). I have worked on [finding efficient ways to explore RL environments](https://liuanji.github.io/publication/2019-09-05-AAC) and [deploying novel parallelization Monte Carlo Tree Search (MCTS) algorithms for large scale Game AI tasks](https://liuanji.github.io/publication/2019-09-25-P-UCT). I am also deeply impressed by probabilistic inference models and many other machine learning models. Please see my [research proposal](https://liuanji.github.io/research) for details.

Education
======
* **Beihang University** School of Automation Science and Electrical Engineering

    Bachler of Science in Automation, Sep. 2015 - Jun. 2019 ([transcript](https://liuanji.github.io/files/transcript.pdf))

Experience
======
* **StarAI Lab, UCLA** (Aug. 2019 - Present)

    **Title:** visiting researcher
    **Research topic:** Tractable inference on probabilistic graphical models, and its application on reinforcement learning.

* **Seattle AI Lab, Kwai Inc.** (Dec. 2018 - Jul. 2019)

    **Title:** Machine Learning intern
    **Project:** User pass rate prediction system for a level-oriented mobile game “joy city”. The system is powered by a game AI using reinforcement learning (RL) and Monte Carlo tree search (MCTS) that achieves master-level performance in the mobile game.

Research projects
======
* **Research on Model-based Reinforcement Learning**

    Solving the environment model’s inaccuracy problem in model-based reinforcement learning with tractable probabilistic inference models. The main idea is that by propagating environment model’s uncertainty over multiple time steps, we can both improve multi-step prediction and be able to quantify the uncertainty, which allows principled tradeoff between using environment model for planning and using on-policy methods.

* **Research on Parallelizing Monte Carlo Tree Search**

    Designed a novel parallelization algorithm for Monte Carlo Tree Search as well as a practical system implementation to achieve linear speed up while suffering negligible performance degradation. The key idea is to make use of the information from unobserved samples to guide the node selection process in the tree search.
    
* **Research on Exploration Strategy of Continuous Control Tasks**

    Disentangled the policy learning and exploration process in continuous control reinforcement learning tasks by separately design two policies that maximize their respective objectives, which offers policy optimality as well as effective exploration. The resultant model out-performs state-of-the-art approaches in various benchmarks.
    
* **Research on Improving State Representations for Reinforcement Learning**

    Built a learning model to extract location of moving objects in visual RL tasks automatically without the need of supervision or labeled samples, which provide high-level state-representations that accelerate reinforcement learning significantly.
    
* **Research on Improving Fully Connected Neural Networks**

    Studied the fundamentals of neural networks and programmed a neural network package from scratch in MATLAB. The package contains most commonly used layers in neural networks and it is easy to modify. Proposed a balance gate controlled neural network that out-performs traditional fully-connected neural network in both regression tasks and classification tasks.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>