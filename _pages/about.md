---
layout: single
permalink: /
title: "个人主页"
excerpt: "刘云龙，厦门大学航空航天学院自动化系副教授、博士生导师"
author_profile: false
classes: chinese-profile-page
---

<div class="english-profile">

  <header class="profile-hero">
    <p class="profile-eyebrow">厦门大学 · 航空航天学院</p>
    <p class="profile-role">自动化系副教授 · 博士生导师</p>
    <p class="profile-lead">我致力于研究面向智能体的学习与决策方法，并将其应用于具身智能、无人系统、医疗健康和复杂动态环境。</p>
    <div class="profile-actions">
      <a class="profile-button profile-button-primary" href="mailto:ylliu@xmu.edu.cn">联系我</a>
      <a class="profile-button" href="/publications/">学术论文</a>
      <a class="profile-button" href="/students/">学生与校友</a>
      <a class="profile-button" href="/service/">学术服务</a>
      <a class="profile-button" href="https://space.bilibili.com/1688395866">实验室视频</a>
    </div>
  </header>

  <section class="profile-section profile-news-section" id="news">
    <h2>近期动态</h2>
    <ul class="profile-news-list">
      {% for item in site.data.news %}
      <li class="profile-news-item">
        <div class="profile-news-meta">
          <span class="profile-news-date">{{ item.date }}</span>
          <span class="profile-news-category">{{ item.category_zh }}</span>
        </div>
        <div class="profile-news-content">
          <p class="profile-news-heading">
            {% if item.url %}<a href="{{ item.url }}">{% endif %}{{ item.title_zh }}{% if item.url %}</a>{% endif %}
          </p>
          <p class="profile-news-summary">{{ item.summary_zh }}</p>
        </div>
      </li>
      {% endfor %}
    </ul>
  </section>

  <section class="profile-section">
    <h2>个人简介</h2>
    <p>我现任厦门大学航空航天学院自动化系副教授、博士生导师，曾任美国加州大学洛杉矶分校（UCLA）计算机系访问学者，入选福建省高层次人才。</p>
    <p>研究成果以第一作者或通讯作者发表于 ICML、IJCAI、AAMAS，以及 <em>IEEE Robotics and Automation Letters</em>、<em>Neural Networks</em>、<em>International Journal of Approximate Reasoning</em>、<em>Information Sciences</em>、<em>Knowledge-Based Systems</em> 等国际会议和期刊。承担多项国家自然科学基金面上项目、省部级项目及企业合作开发课题。</p>
    <p>曾获工业和信息化部火炬中心等单位举办的 2025 年中国创新创业大赛首届具身智能专业赛初创组优胜奖（300 多支队伍中排名前 11）。指导学生在腾讯开悟人工智能全国公开赛、AAMAS 非完全信息卡牌游戏竞赛和全国大学生冰壶人工智能挑战赛等赛事中取得优异成绩。</p>
  </section>

  <section class="profile-section">
    <h2>研究方向</h2>
    <div class="profile-tags" aria-label="研究方向">
      <span>人工智能</span>
      <span>深度强化学习</span>
      <span>表征学习</span>
      <span>序贯决策</span>
      <span>具身智能</span>
      <span>自主导航与避障</span>
      <span>医疗健康决策</span>
      <span>交通信号控制</span>
    </div>
    <p>研究聚焦强化学习理论与方法，包括表征学习、奖励设计和模仿学习，并面向复杂动态及极端环境中的无人系统导航、避障与决策等任务开展应用研究。</p>
  </section>

  <section class="profile-section">
    <h2>学术服务</h2>
    <div class="profile-card-grid">
      <div class="profile-card">
        <h3>学术会议程序委员会</h3>
        <ul>
          <li>IJCAI 程序委员会 Board 成员，2022–2024</li>
          <li>AAAI：2019–2025</li>
          <li>IJCAI：2017、2021–2024</li>
          <li>UAI：2021–2025</li>
          <li>AAMAS：2020；ICDM：2024</li>
        </ul>
      </div>
      <div class="profile-card">
        <h3>会议与期刊审稿</h3>
        <p><strong>会议：</strong>NeurIPS（NIPS）2016、2024–2025；IROS 2020；ICRA；ICML 2025；ICLR 2025。</p>
        <p><strong>期刊：</strong><em>IEEE Transactions on Cybernetics</em>、<em>IEEE Transactions on Neural Networks and Learning Systems</em>、<em>IEEE Transactions on Systems, Man, and Cybernetics: Systems</em>、<em>ACM Transactions on Intelligent Systems and Technology</em>、<em>Neural Networks</em>、<em>Information Sciences</em>、<em>Applied Intelligence</em>、<em>IEEE Robotics and Automation Letters</em>、《控制与决策》等。</p>
      </div>
    </div>
    <p>担任 ICML、UAI 等人工智能顶会 Top Reviewer；国家自然科学基金通讯评议专家、教育部学位中心论文评审专家；厦门市商务局、厦门市软件协会、厦门市自贸区、厦门金圆集团等单位项目评审专家；中国自动化学会自适应动态规划与强化学习专业委员会委员、CCF-AI 多智能体系统学组委员。<a href="/service/">查看学术服务详情</a>。</p>
  </section>

  <section class="profile-section">
    <h2>代表性奖励与学生成果</h2>
    <p>指导学生取得的部分成绩：</p>
    <ul class="profile-awards">
      <li><strong>2025 年中国创新创业大赛首届具身智能专业赛：</strong>初创组优胜奖，300 多支参赛队伍中排名前 11。</li>
      <li><strong>2024 年 AAMAS 非完全信息卡牌游戏竞赛：</strong>亚军；团队在 2023 年获第四名。</li>
      <li><strong>2024 年腾讯开悟人工智能全国公开赛智能交通信号灯决赛：</strong>第 13 名。</li>
      <li><strong>2023 年腾讯开悟人工智能全国公开赛博弈算法高级赛道：</strong>决赛第四名。</li>
      <li><strong>2023 年全国大学生冰壶人工智能挑战赛：</strong>一等奖。</li>
    </ul>
  </section>

  <section class="profile-section profile-two-column">
    <div>
      <h2>教学</h2>
      <p>主讲《信息论》《概率图模型理论及应用》《计算机网络》等课程。</p>
    </div>
    <div>
      <h2>学生与校友</h2>
      <p>毕业学生选择继续攻读博士学位，或就职于阿里达摩院、滴滴出行、华为、TP-Link、兴业银行及高校等单位。</p>
      <a class="profile-text-link" href="/students/">查看学生年级与毕业去向 →</a>
    </div>
  </section>

  <section class="profile-section profile-join">
    <p class="profile-eyebrow">欢迎硕士生、博士生与博士后加入</p>
    <h2>加入课题组</h2>
    <p>欢迎对强化学习及其在具身智能、电子游戏、医疗健康、网络安全等领域应用感兴趣的优秀硕士生、博士生和博士后加入团队。课题组提供系统的科研训练，也开展与企业合作的产品级开发项目。</p>
    <div class="profile-actions">
      <a class="profile-button profile-button-primary" href="mailto:ylliu@xmu.edu.cn">邮件联系</a>
      <a class="profile-button" href="/service/">学术服务</a>
    </div>
    <p class="profile-note">邮件联系时请将简历直接作为附件发送，而不是使用云附件，方便在手机邮箱中查看。</p>
  </section>

  <nav class="language-switch" aria-label="语言切换">
    <a href="/" lang="zh" aria-current="page">中文</a>
    <span aria-hidden="true">/</span>
    <a href="/about-en/" lang="en">English</a>
  </nav>
</div>
