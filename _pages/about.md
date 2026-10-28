---
permalink: /
title: "个人主页"
excerpt: "刘云龙，厦门大学航空航天学院自动化系副教授、博士生导师"
author_profile: true

---

刘云龙，厦门大学航空航天学院自动化系副教授、博士生导师，曾在加州大学洛杉矶分校（UCLA）计算机系访问，入选福建省高层次人才。研究方向包括人工智能、（深度）强化学习与智能决策，关注机器学习在具身智能、医疗健康等领域的应用。相关成果以第一作者或通讯作者发表于 CCF 推荐的 A、B 类会议及相关领域重要期刊，包括 ICML、IJCAI、AAMAS，以及《IEEE Robotics and Automation Letters》《Neural Networks》《International Journal of Approximate Reasoning》《Information Sciences》《Knowledge-Based Systems》等。

学术服务方面，曾任 IJCAI Program Committee Board 成员（2022–2024），并担任 AAAI（2019–2025）、IJCAI（2017、2021–2024）、UAI（2021–2025）、AAMAS（2020）和 ICDM（2024）程序委员会委员。长期为 NeurIPS、ICML、ICLR、ICRA、IROS 等会议，以及《IEEE Transactions on Cybernetics》《IEEE Transactions on Neural Networks and Learning Systems》《ACM Transactions on Intelligent Systems and Technology》《Neural Networks》《IEEE Transactions on Systems, Man, and Cybernetics: Systems》《Information Sciences》《Applied Intelligence》《IEEE Robotics and Automation Letters》《控制与决策》等期刊审稿，曾获 ICML、UAI 等会议 Top Reviewer。

承担多项国家自然科学基金面上项目、省部级项目及企业合作开发课题，并担任国家自然科学基金通讯评议专家、教育部学位中心论文评审专家和中国自动化学会自适应动态规划与强化学习专业委员会委员。曾为厦门市商务局、厦门市软件协会、厦门市自贸区、厦门金圆集团等单位开展项目评审。团队在工业和信息化部火炬中心等单位举办的2025年第十四届中国创新创业大赛首届具身智能专业赛中获初创组优胜奖，进入300余支参赛队伍前11名。指导学生在2023年腾讯开悟人工智能全国公开赛高级赛道决赛中获第四名，在AAMAS 2023、2024（CCF B类）非完全信息卡牌游戏竞赛中分别获第四名、第二名，并获2023年全国大学生冰壶人工智能挑战赛一等奖。

主讲《信息论》《概率图模型理论及应用》《计算机网络》等课程。毕业学生继续攻读博士学位或就职于阿里达摩院、滴滴出行、华为、TP-Link、兴业银行及高校等单位。

<section class="profile-section profile-news-section" id="news">
  <h2>近期动态</h2>
  <ul class="profile-news-list">
    {% for item in site.data.news %}
    <li class="profile-news-item">
      <div class="profile-news-meta">
        <span class="profile-news-date">{{ item.date }}</span>
        <span class="profile-news-category">{% if page.url contains '/about-en/' %}{{ item.category_en }}{% else %}{{ item.category_zh }}{% endif %}</span>
      </div>
      <div class="profile-news-content">
        <p class="profile-news-heading">
          {% if item.url %}<a href="{{ item.url }}">{% endif %}{% if page.url contains '/about-en/' %}{{ item.title_en }}{% else %}{{ item.title_zh }}{% endif %}{% if item.url %}</a>{% endif %}
        </p>
        <p class="profile-news-summary">{% if page.url contains '/about-en/' %}{{ item.summary_en }}{% else %}{{ item.summary_zh }}{% endif %}</p>
      </div>
    </li>
    {% endfor %}
  </ul>
</section>

## 招生信息

欢迎对（深度）强化学习及其在具身智能、电子游戏、医疗健康等领域的应用，以及网络安全开发与应用感兴趣的硕士生、博士生和博士后加入团队。课题组提供系统的科研训练，并有与企业合作的产品级开发项目。欢迎发送邮件至 ylliu AT xmu.edu.cn 联系；请将简历作为邮件附件直接发送，避免使用云附件，以便通过手机邮箱查看。

实验室研究部分成果视频展示可参考<https://space.bilibili.com/1688395866>.
