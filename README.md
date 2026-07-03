<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&section=header&text=kaduoxzero&fontSize=56&fontAlignY=36&desc=Java%20Backend%20%7C%20Microservices%20%7C%20Distributed%20Systems%20%7C%20AI%20Engineering&descSize=18&descAlignY=58&animation=fadeIn&color=0:0D1117,45:1F6FEB,100:8A2BE2&fontColor=FFFFFF" alt="kaduoxzero profile header" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2600&pause=900&color=58A6FF&center=true&vCenter=true&width=940&lines=Java+Backend+%2B+Spring+Cloud+Alibaba;Microservices+%2B+Middleware+Integration;RAG+%2B+Agent+Workflow+%2B+AI+Engineering;Keep+building.+Keep+shipping." alt="typing svg" />

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

当前主页展示 `kaduoxzero` 账号下的公开仓库、重点项目实践和 GitHub 动态数据。第三方图表只接入公开仓库，避免私有仓库或未公开项目导致空白数据。

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
      <h3>SpikeGuard <sub>本地/私有实践</sub></h3>
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

## 公开仓库矩阵

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>核心公开项目</h3>
      <p>
        <a href="https://github.com/kaduoxzero/SemiRisk">SemiRisk</a> ·
        <a href="https://github.com/kaduoxzero/YunLanHome">YunLanHome</a> ·
        <a href="https://github.com/kaduoxzero/WebAI-Tlias">WebAI-Tlias</a> ·
        <a href="https://github.com/kaduoxzero/kaduoxzero">kaduoxzero</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Jzo2o 微服务拆分</h3>
      <p>
        <a href="https://github.com/kaduoxzero/jzo2o-api">jzo2o-api</a> ·
        <a href="https://github.com/kaduoxzero/jzo2o-gateway">jzo2o-gateway</a> ·
        <a href="https://github.com/kaduoxzero/jzo2o-customer">jzo2o-customer</a> ·
        <a href="https://github.com/kaduoxzero/jzo2o-market">jzo2o-market</a> ·
        <a href="https://github.com/kaduoxzero/jzo2o-order">jzo2o-order</a> ·
        <a href="https://github.com/kaduoxzero/jzo2o-trade">jzo2o-trade</a> ·
        <a href="https://github.com/kaduoxzero/jzo2o-publics">jzo2o-publics</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>基础设施与前端</h3>
      <p>
        <a href="https://github.com/kaduoxzero/jzo2o-foundations">jzo2o-foundations</a> ·
        <a href="https://github.com/kaduoxzero/jzo2o-framework">jzo2o-framework</a> ·
        <a href="https://github.com/kaduoxzero/jzo2o-front">jzo2o-front</a> ·
        <a href="https://github.com/kaduoxzero/obsidian-i18n-resources">obsidian-i18n-resources</a> ·
        <a href="https://github.com/kaduoxzero/obsidian-translations">obsidian-translations</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>公开数据接入</h3>
      <p>Star History 接入 SemiRisk、YunLanHome、WebAI-Tlias、jzo2o-front；GitHub Summary Cards 接入账号公开贡献数据。</p>
    </td>
  </tr>
</table>

---

## 🛠 技术栈聚焦

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ Backend</h3>
      <p>
        <img src="https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
        <img src="https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
        <img src="https://img.shields.io/badge/Spring%20Cloud-Alibaba-00A1E9?style=for-the-badge&logo=alibabacloud&logoColor=white" alt="Spring Cloud Alibaba" />
        <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Spring Security" />
        <img src="https://img.shields.io/badge/MyBatis--Plus-1AAD1A?style=for-the-badge&logo=mybatis&logoColor=white" alt="MyBatis-Plus" />
        <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />
        <img src="https://img.shields.io/badge/REST%20API-009688?style=for-the-badge&logo=api&logoColor=white" alt="REST API" />
        <img src="https://img.shields.io/badge/RBAC-333333?style=for-the-badge&logo=auth0&logoColor=white" alt="RBAC" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🗄️ Middleware</h3>
      <p>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
        <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Elasticsearch" />
        <img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white" alt="MinIO" />
        <img src="https://img.shields.io/badge/Nacos-00A1E9?style=for-the-badge&logo=alibabacloud&logoColor=white" alt="Nacos" />
        <img src="https://img.shields.io/badge/Sentinel-00A1E9?style=for-the-badge&logo=alibabacloud&logoColor=white" alt="Sentinel" />
        <img src="https://img.shields.io/badge/Seata-00A1E9?style=for-the-badge&logo=alibabacloud&logoColor=white" alt="Seata" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎨 Frontend</h3>
      <p>
        <img src="https://img.shields.io/badge/Vue-3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue 3" />
        <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
        <img src="https://img.shields.io/badge/Element%20Plus-409EFF?style=for-the-badge&logo=element&logoColor=white" alt="Element Plus" />
        <img src="https://img.shields.io/badge/Vant-1989FA?style=for-the-badge&logo=vant&logoColor=white" alt="Vant" />
        <img src="https://img.shields.io/badge/ECharts-AA344D?style=for-the-badge&logo=apacheecharts&logoColor=white" alt="ECharts" />
        <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js" />
        <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios" />
        <img src="https://img.shields.io/badge/Vue%20Router-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue Router" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🚀 DevOps &amp; AI</h3>
      <p>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
        <img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose" />
        <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
        <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
        <img src="https://img.shields.io/badge/Zipkin-FE9800?style=for-the-badge&logo=zipkin&logoColor=white" alt="Zipkin" />
        <img src="https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white" alt="Kibana" />
        <img src="https://img.shields.io/badge/DeepSeek-000000?style=for-the-badge&logo=openai&logoColor=white" alt="DeepSeek API" />
        <img src="https://img.shields.io/badge/Spring%20AI-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring AI" />
        <img src="https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge&logo=openai&logoColor=white" alt="RAG" />
      </p>
    </td>
  </tr>
</table>

---

## 📊 GitHub 数据总览

<div align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=kaduoxzero&theme=tokyonight" alt="kaduoxzero GitHub stats" />
  <img width="49%" src="https://streak-stats.demolab.com?user=kaduoxzero&theme=tokyonight&hide_border=true" alt="kaduoxzero GitHub streak" />
</div>

<div align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kaduoxzero&theme=tokyonight" alt="repos per language" />
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=kaduoxzero&theme=tokyonight&utcOffset=8" alt="kaduoxzero productive time" />
</div>

<div align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=kaduoxzero&theme=tokyonight" alt="most commit language" />
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kaduoxzero&theme=tokyonight" alt="kaduoxzero profile summary" />
</div>

<div align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/calendar?username=kaduoxzero&theme=tokyonight" alt="kaduoxzero calendar heatmap" />
</div>

<div align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/isocalendar?username=kaduoxzero&theme=tokyonight&duration=full-year" alt="kaduoxzero isocalendar" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kaduoxzero&theme=github-compact&hide_border=true&area=true" width="100%" alt="kaduoxzero GitHub activity graph" />
</div>

---

<!-- ## GitHub Metrics (暂时注释，待 METRICS_TOKEN 修复后恢复)

<div align="center">
  <img src="./github-metrics.svg" width="100%" alt="kaduoxzero GitHub Metrics" />
</div>

--- -->

## 动态贡献图

> **提示：** 以下 Snake 动画和 3D 贡献图依赖 GitHub 静态资源托管，需在 GitHub 网页端查看完整效果。

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

## 📌 近期项目进展

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🚀 SpikeGuard 微服务电商系统</h4>
      <p>
        <img src="https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
        <img src="https://img.shields.io/badge/Spring%20Cloud-Alibaba-00A1E9?style=flat-square&logo=alibabacloud&logoColor=white" alt="Spring Cloud Alibaba" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      </p>
      <p>完成从单体到微服务的架构升级，集成 Spring Cloud Alibaba、Nacos、Sentinel、Seata，覆盖网关鉴权、库存高并发、异步消息和全链路观测。</p>
    </td>
    <td width="50%" valign="top">
      <h4>🤖 AI 风控引擎 (SemiRisk)</h4>
      <p>
        <img src="https://img.shields.io/badge/DeepSeek-API-000000?style=flat-square&logo=openai&logoColor=white" alt="DeepSeek" />
        <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch" />
        <img src="https://img.shields.io/badge/Vue-3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue 3" />
        <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white" alt="Three.js" />
        <img src="https://img.shields.io/badge/RAG-FF6F00?style=flat-square&logo=openai&logoColor=white" alt="RAG" />
      </p>
      <p>基于 LangGraph + DeepSeek API 构建智能风险评估工作流，实现 RAG 知识库问答、向量检索和 AI 报告自动生成。</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🏠 YunLanHome O2O 家政平台</h4>
      <p>
        <img src="https://img.shields.io/badge/Redis%20Geo-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis Geo" />
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
        <img src="https://img.shields.io/badge/Seata-00A1E9?style=flat-square&logo=alibabacloud&logoColor=white" alt="Seata" />
        <img src="https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
      </p>
      <p>练习高并发业务场景：Redis Geo 附近匹配、RabbitMQ 异步削峰、分布式事务保障订单流转一致性。</p>
    </td>
    <td width="50%" valign="top">
      <h4>🛠️ 工程化与 CI/CD</h4>
      <p>
        <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
        <img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Compose" />
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
        <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
      </p>
      <p>GitHub Actions 自动化 Metrics / Snake / 3D 贡献图生成；Docker Compose 一键部署中间件；Prometheus + Grafana 可观测性体系。</p>
    </td>
  </tr>
</table>

> 所有统计图和动态 SVG 均读取 GitHub 公开数据或由 GitHub Actions 自动生成；私有仓库不会接入第三方公开统计图。

---

## 联系方式

GitHub 公开主页：[@kaduoxzero](https://github.com/kaduoxzero)

Email：liulizhi64@gmail.com

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:8A2BE2,55:1F6FEB,100:0D1117" alt="footer" />

</div>
