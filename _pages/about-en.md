---
layout: single
permalink: /about-en/
title: "Yunlong Liu"
excerpt: "Yunlong Liu, Associate Professor and Ph.D. Supervisor at Xiamen University."
author: "Yunlong Liu"
author_profile: true
description: "Yunlong Liu, Associate Professor at Xiamen University. Research in reinforcement learning, embodied intelligence, autonomous systems, and decision-making."
---

I am an Associate Professor and Ph.D. Supervisor in the Department of Automation, School of Aerospace Engineering, Xiamen University. I was a Visiting Scholar in the Department of Computer Science at the University of California, Los Angeles (UCLA), and am recognized as a High-Level Talent of Fujian Province. My research focuses on artificial intelligence, deep reinforcement learning, and intelligent decision-making, with applications in embodied intelligence and healthcare.

My work has appeared as first- or corresponding-author papers at ICML, IJCAI, and AAMAS, and in journals including *IEEE Robotics and Automation Letters*, *Neural Networks*, *International Journal of Approximate Reasoning*, *Information Sciences*, and *Knowledge-Based Systems*. My academic service includes a term on the IJCAI Program Committee Board (2022–2024) and program committee appointments at AAAI, IJCAI, UAI, AAMAS, and ICDM. I have also reviewed for major AI and robotics conferences and journals, and have been recognized as a Top Reviewer by ICML and UAI. I lead projects funded by the National Natural Science Foundation of China, provincial and ministerial programs, and industry partners.

I teach *Information Theory*, *Probabilistic Graphical Models: Theory and Applications*, and *Computer Networks*. My students have received awards in the Tencent Kaiwu AI National Open Competition, the AAMAS non-perfect-information card-game competition, and the National College Student AI Curling Challenge. Graduates have gone on to doctoral study or joined organizations including Alibaba DAMO Academy, DiDi, Huawei, TP-Link, Industrial Bank, and universities.

<section class="profile-section profile-news-section" id="news">
  <h2>News</h2>
  <ul class="profile-news-list">
    {% for item in site.data.news %}
    <li class="profile-news-item">
      <div class="profile-news-meta">
        <span class="profile-news-date">{{ item.date }}</span>
        <span class="profile-news-category">{{ item.category_en }}</span>
      </div>
      <div class="profile-news-content">
        <p class="profile-news-heading">
          {% if item.url %}<a href="{{ item.url }}">{% endif %}{{ item.title_en }}{% if item.url %}</a>{% endif %}
        </p>
        <p class="profile-news-summary">{{ item.summary_en }}</p>
      </div>
    </li>
    {% endfor %}
  </ul>
</section>

## Prospective Students

I welcome motivated master's and Ph.D. students, as well as postdoctoral researchers, interested in reinforcement learning and its applications to embodied intelligence, video games, healthcare, and cybersecurity. My group offers systematic research training and opportunities to contribute to product-oriented projects with industry partners. To get in touch, email ylliu@xmu.edu.cn and attach your CV directly to the message so it can be viewed easily on mobile devices.

Explore research videos from the [XMU-DMU Lab channel](https://www.youtube.com/@XMU-DMU-Lab).
