---
layout: single
permalink: /about-en/
title: "Yunlong Liu"
excerpt: "Yunlong Liu, Associate Professor and Ph.D. Supervisor at Xiamen University."
author: "Yunlong Liu"
author_profile: true
description: "Yunlong Liu, Associate Professor at Xiamen University. Research in reinforcement learning, embodied intelligence, autonomous systems, and decision-making."
---

Yunlong Liu is an Associate Professor and Ph.D. Supervisor in the Department of Automation, School of Aerospace Engineering, Xiamen University. He was a Visiting Scholar in the Department of Computer Science at the University of California, Los Angeles (UCLA), and is recognized as a High-Level Talent of Fujian Province. His research interests include artificial intelligence, (deep) reinforcement learning, intelligent decision-making, and machine learning applications in embodied intelligence and healthcare. His work has appeared as first-author or corresponding-author publications at ICML, IJCAI, and AAMAS, and in leading journals including *IEEE Robotics and Automation Letters*, *Neural Networks*, *International Journal of Approximate Reasoning*, *Information Sciences*, and *Knowledge-Based Systems*. He served on the IJCAI Program Committee Board (2022–2024), and as a program committee member for AAAI (2019–2025), IJCAI (2017, 2021–2024), UAI (2021–2025), AAMAS (2020), and ICDM (2024). He reviews for leading conferences and journals, including *IEEE Transactions on Cybernetics*, *IEEE Transactions on Neural Networks and Learning Systems*, *ACM Transactions on Intelligent Systems and Technology*, *Neural Networks*, *IEEE Transactions on Systems, Man, and Cybernetics: Systems*, *Information Sciences*, NeurIPS (NIPS) 2016 and 2024–2025, IROS 2020, ICRA, ICLR 2025, ICML 2025, *Applied Intelligence*, *IEEE Robotics and Automation Letters*, and *Control and Decision*. He has been recognized as a Top Reviewer by leading AI conferences such as ICML and UAI. He leads projects funded by the National Natural Science Foundation of China, provincial and ministerial programs, and industry partners. His service also includes proposal and thesis reviews and committee roles in the Chinese Association of Automation and CCF-AI. In 2025, his team received an Excellence Award in the inaugural Embodied Intelligence track of the China Innovation and Entrepreneurship Competition, placing among the top 11 of more than 300 teams. His students have earned awards in the Tencent Kaiwu AI National Open Competition, the AAMAS non-perfect-information card-game competition, and the National College Student AI Curling Challenge. He teaches *Information Theory*, *Probabilistic Graphical Models: Theory and Applications*, and *Computer Networks*. Graduates have continued to doctoral study or joined organizations including Alibaba DAMO Academy, DiDi, Huawei, TP-Link, Industrial Bank, and universities.

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

I welcome motivated master's and Ph.D. students, as well as postdoctoral researchers, interested in reinforcement learning and its applications in embodied intelligence, video games, healthcare, and cybersecurity. My group offers systematic research training and product-level development projects in collaboration with companies. To get in touch, email ylliu@xmu.edu.cn. Please attach your CV directly to the email rather than using a cloud-hosted attachment, which may not preview well on mobile devices.

Explore research videos from the [XMU-DMU Lab channel](https://www.youtube.com/@XMU-DMU-Lab).
