---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a visiting researcher at [Statistical and Relational Artificial Intelligence (StarAI) lab](http://starai.cs.ucla.edu/members/) in UCLA, led by professor [Guy Van den Broeck](http://web.cs.ucla.edu/~guyvdb/). My research passion is on the intersection of reinforcement learning (RL) and tractable inference models that add domain knowledge as well as model uncertainty in the environment. Before joining StarAI lab, I was a machine learning intern at Seattle AI Lab, Kwai Inc. During my internship, I worked on game AI and reinforcement learning. Before that, I completed my BS in Automation at the school of automation science and electrical engineering in [Beihang University](https://ev.buaa.edu.cn/) (BUAA), working under the advisement of professor [Yuanjun Laili](http://shi.buaa.edu.cn/yunglynn/en/index.htm).

Education
======
* **Beihang University** School of Automation Science and Electrical Engineering

    Bachler of Science in Automation, Sep. 2015 - Jun. 2019 [transcript](https://liuanji.github.io/files/Transcript of Academic Record - Anji Liu.pdf)

Experience
======
* **StarAI Lab, UCLA**

    Visiting researcher, Aug. 2019 - Present.

* **Seattle AI Lab, Kwai Inc.**

    Research intern, Dec. 2018 - Jul. 2019

Research proposal
======
My main research passion is on 

Research projects
======
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