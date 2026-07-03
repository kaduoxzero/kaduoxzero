<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&section=header&text=kaduoxzero&fontSize=56&fontAlignY=36&desc=Java%20Backend%20%7C%20Microservices%20%7C%20Distributed%20Systems%20%7C%20AI%20Engineering&descSize=18&descAlignY=58&animation=fadeIn&color=0:0D1117,45:1F6FEB,100:8A2BE2&fontColor=FFFFFF" alt="kaduoxzero profile header" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2600&pause=900&color=58A6FF&center=true&vCenter=true&width=940&lines=Java+Backend+%2B+Spring+Cloud+Alibaba;SpikeGuard+Microservices+%2B+Distributed+Transactions;RAG+%2B+Agent+Workflow+%2B+AI+Engineering;Keep+building.+Keep+shipping." alt="typing svg" />

<p>
  <a href="https://github.com/kaduoxzero"><img src="https://img.shields.io/badge/GitHub-kaduoxzero-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
  <img src="https://img.shields.io/github/followers/kaduoxzero?style=for-the-badge&logo=github&label=Followers" alt="GitHub followers" />
  <img src="https://img.shields.io/github/stars/kaduoxzero?affiliations=OWNER%2CCOLLABORATOR&style=for-the-badge&logo=github&label=Stars" alt="GitHub stars" />
  <img src="https://komarev.com/ghpvc/?username=kaduoxzero&style=for-the-badge&color=blueviolet" alt="Profile views" />
</p>

<p>
  <img src="https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring%20Cloud-Alibaba-00A1E9?style=for-the-badge&logo=alibabacloud&logoColor=white" alt="Spring Cloud Alibaba" />
  <img src="https://img.shields.io/badge/Vue-3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue 3" />
  <img src="https://img.shields.io/badge/Docker-Project%20Practice-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

<p>
  <img src="https://img.shields.io/github/actions/workflow/status/kaduoxzero/kaduoxzero/Metrics.yml?branch=main&label=Metrics&logo=githubactions&style=flat-square" alt="Metrics workflow" />
  <img src="https://img.shields.io/github/actions/workflow/status/kaduoxzero/kaduoxzero/grid-snake.yml?branch=main&label=Snake&logo=githubactions&style=flat-square" alt="Snake workflow" />
  <img src="https://img.shields.io/github/actions/workflow/status/kaduoxzero/kaduoxzero/profile-3d.yml?branch=main&label=3D%20Graph&logo=githubactions&style=flat-square" alt="3D workflow" />
</p>

</div>

---

## About me

围绕 **Java 后端开发、微服务架构、分布式中间件和 AI 工程化** 做项目实践，偏向把业务系统从接口、缓存、消息、检索、可观测性到前端联调整体跑通。

当前主页展示 `kaduoxzero` 账号下的公开项目、工程实践方向和 GitHub 动态数据。

关注方向：

- **后端工程**：Java 21、Spring Boot 3、Spring Cloud Alibaba、MyBatis/MyBatis-Plus、接口设计、权限控制、业务分层。
- **微服务与分布式**：Nacos、Gateway、Sentinel、Seata、RabbitMQ、Redis、PostgreSQL/MySQL、Elasticsearch。
- **工程化与联调**：Docker Compose、Maven 多模块、Prometheus/Grafana、Zipkin、Kibana、GitHub Actions、前后端联调。
- **AI 工程化**：DeepSeek API、Spring AI、RAG、向量检索、知识库问答、报告生成、Agent 流程编排。

---

## 代表项目

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/kaduoxzero/SpikeGuard">SpikeGuard</a></h3>
      <p>面向商城与秒杀场景的 <strong>微服务电商系统实践</strong>，重点覆盖网关鉴权、商品与库存、订单交易、优惠券、秒杀限流、异步消息和可观测性。</p>
      <ul>
        <li>基于 Spring Cloud Alibaba 拆分网关、认证、商品、订单、交易、营销等后端模块。</li>
        <li>Redis + Lua 处理高并发库存扣减、重复提交控制和热点数据缓存。</li>
        <li>RabbitMQ 承接异步下单、事件通知和削峰，降低核心链路数据库压力。</li>
        <li>整合 Nacos、Sentinel、Seata、Zipkin、Prometheus/Grafana、ELK，支撑本地联调与观测。</li>
      </ul>
      <p><strong>技术：</strong>Java 21、Spring Boot 3、Spring Cloud Alibaba、PostgreSQL、Redis、RabbitMQ、Nacos、Sentinel、Seata、Vue 3、Vant、Element Plus、Docker。</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/kaduoxzero/SemiRisk">SemiRisk</a></h3>
      <p>面向半导体供应链风险管理的 <strong>AI 智能监测平台</strong>，围绕风险事件、供应商数据、预警中心、知识库问答和 AI 报告组织业务闭环。</p>
      <ul>
        <li>构建风险采集、风险识别、智能分析、告警与报告生成链路。</li>
        <li>使用 Elasticsearch dense_vector / RRF 支撑 RAG 检索与知识库问答。</li>
        <li>通过 RabbitMQ 和线程池隔离 AI 任务，降低长耗时任务对业务链路的影响。</li>
        <li>Vue 3 + Three.js 展示企业画像、风险地图、供应链关系和风险详情。</li>
      </ul>
      <p><strong>技术：</strong>Java 21、Spring Boot 3、Spring Cloud Alibaba、Vue 3、Three.js、MySQL、Redis、Elasticsearch、MinIO、RabbitMQ、Nacos、Docker。</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/kaduoxzero/YunLanHome">YunLanHome</a></h3>
      <p>互联网 O2O 家政服务平台方向的 <strong>分布式业务系统实践</strong>，重点练习高并发业务、分布式一致性和微服务边界设计。</p>
      <ul>
        <li>Redis + Lua 处理抢券库存扣减和重复领取。</li>
        <li>RabbitMQ 异步写入，降低数据库直接压力。</li>
        <li>状态机、策略模式、分布式事务拆解订单流转。</li>
        <li>Redis Geo / Redisson 处理附近匹配和多人抢单。</li>
      </ul>
      <p><strong>模块：</strong>jzo2o-foundations、jzo2o-api、jzo2o-gateway、jzo2o-customer、jzo2o-market、jzo2o-order、jzo2o-trade、jzo2o-publics。</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/kaduoxzero/WebAI-Tlias">WebAI-Tlias</a></h3>
      <p>基于 Spring Boot + Vue 3 的 <strong>教务管理系统</strong>，用于练习前后端分离、JWT 登录、基础 CRUD、文件上传和操作日志。</p>
      <ul>
        <li>JWT + 拦截器实现接口访问控制。</li>
        <li>MyBatis / MyBatis-Plus 完成分页筛选和业务 CRUD。</li>
        <li>阿里云 OSS 处理头像与资料上传。</li>
        <li>Spring AOP 自动记录关键操作日志。</li>
      </ul>
      <p><strong>方向：</strong>Spring Boot、Vue 3、Element Plus、JWT、MyBatis、OSS、AOP。</p>
    </td>
  </tr>
</table>

---

## 技术栈聚焦

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Backend</h3>
      <p>Java、Spring Boot、Spring Cloud Alibaba、Spring Security、MyBatis / MyBatis-Plus、REST API、JWT、RBAC。</p>
    </td>
    <td width="50%" valign="top">
      <h3>Middleware</h3>
      <p>PostgreSQL、MySQL、Redis、RabbitMQ、Elasticsearch、MinIO、Nacos、Sentinel、Seata。</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Frontend</h3>
      <p>Vue 3、Vite、Element Plus、Vant、ECharts、Three.js、Axios、Vue Router。</p>
    </td>
    <td width="50%" valign="top">
      <h3>DevOps &amp; AI</h3>
      <p>Docker、Docker Compose、Maven、GitHub Actions、Prometheus、Grafana、Zipkin、Kibana、DeepSeek API、Spring AI、RAG、Agent Workflow。</p>
    </td>
  </tr>
</table>

---

## GitHub 数据总览

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=kaduoxzero&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=false" alt="kaduoxzero GitHub stats" />
  <img width="49%" src="https://streak-stats.demolab.com?user=kaduoxzero&theme=tokyonight&hide_border=true" alt="kaduoxzero GitHub streak" />
</div>

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kaduoxzero&layout=compact&theme=tokyonight&hide_border=true&langs_count=10" alt="kaduoxzero top languages" />
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=kaduoxzero&theme=tokyonight&utcOffset=8" alt="kaduoxzero productive time" />
</div>

<div align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kaduoxzero&theme=tokyonight" alt="kaduoxzero profile summary" />
</div>

<div align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kaduoxzero&theme=tokyonight" alt="repos per language" />
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=kaduoxzero&theme=tokyonight" alt="most commit language" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kaduoxzero&theme=github-compact&hide_border=true&area=true" width="100%" alt="kaduoxzero GitHub activity graph" />
</div>

---

## GitHub Metrics

<div align="center">
  <img src="./github-metrics.svg" width="100%" alt="kaduoxzero GitHub Metrics" />
</div>

---

## 动态贡献图

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kaduoxzero/kaduoxzero/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kaduoxzero/kaduoxzero/output/github-contribution-grid-snake.svg" />
    <img width="100%" alt="kaduoxzero contribution grid snake animation" src="https://raw.githubusercontent.com/kaduoxzero/kaduoxzero/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

<br />

<div align="center">
  <img src="./profile-3d-contrib/profile-green-animate.svg" width="100%" alt="kaduoxzero 3D Contribution Graph" />
</div>

---

## 成就与 Star 趋势

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=kaduoxzero&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&margin-h=8&column=7" width="100%" alt="kaduoxzero GitHub Profile Trophy" />
</div>

<br />

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=kaduoxzero/SpikeGuard,kaduoxzero/SemiRisk,kaduoxzero/YunLanHome&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=kaduoxzero/SpikeGuard,kaduoxzero/SemiRisk,kaduoxzero/YunLanHome&type=Date" />
    <img width="100%" alt="Star History Chart" src="https://api.star-history.com/svg?repos=kaduoxzero/SpikeGuard,kaduoxzero/SemiRisk,kaduoxzero/YunLanHome&type=Date" />
  </picture>
</div>

> 所有统计图和动态 SVG 均读取 GitHub 公开数据或由 GitHub Actions 自动生成。

---

## 联系方式

GitHub 公开主页：[@kaduoxzero](https://github.com/kaduoxzero)

Email：liulizhi64@gmail.com

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:8A2BE2,55:1F6FEB,100:0D1117" alt="footer" />

</div>
