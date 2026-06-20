<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=7d2ae8,3f00e5&height=220&section=header&text=Sidharth%20Shangonda&fontSize=50&fontColor=ffffff&fontAlignY=40&animation=twinkle" alt="Header Banner" />
</p>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A855F7&center=true&vCenter=true&width=450&lines=B.Tech+in+AI+%26+Data+Science;IIT+Patna+Undergraduate;Building+Backend+%26+AI+Systems" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/IIT%20Patna-B.Tech%20Artificial%20Intelligence-4F46E5?style=for-the-badge&logo=education&logoColor=white" alt="IIT Patna" />
  <img src="https://img.shields.io/badge/Location-Patna%20%7C%20India-6366F1?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location" />
</div>

<br/>

<div align="center">
  <a href="https://linkedin.com/in/sidharth-shangonda-63145336a" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:sidharthshangonda@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/sidharth-shangonda">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=sidharth-shangonda&color=a855f7&style=flat-square&label=Profile+Views" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/sidharth-shangonda?color=a855f7&label=Followers&style=flat-square" alt="Followers" />
  <img src="https://img.shields.io/github/stars/sidharth-shangonda?color=a855f7&label=Stars&style=flat-square" alt="Stars" />
</div>

---

## 🔮 About Me

I am an **Artificial Intelligence undergraduate at IIT Patna** focusing on Artificial Intelligence and Data Science. I spend my time exploring machine learning pipelines, core data structures, algorithms, databases, and building data-driven systems.

*   🎓 **Education:** Pursuing a Bachelor of Technology (B.Tech) in Artificial Intelligence at the Indian Institute of Technology Patna.
*   🚀 **Backend Systems:** Designing efficient API services, relational models, database scaling, and telemetry architectures.
*   🧠 **AI & DB Systems:** Exploring vector retrieval pipelines (pgvector), trace ingestion mechanisms, and semantic search utilities.
*   📊 **Problem Solver:** Deepening my knowledge of core computer science fundamentals and algorithms, with 150+ solved tasks on LeetCode.

---

## 🛠️ Technical Stack

### 💻 Languages
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,ts,js,c,cpp,html,css,postgres" alt="Languages" />
  </a>
</p>

### 🎨 Frontend
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,vite,tailwind" alt="Frontend" />
  </a>
</p>

### ⚙️ Backend & Databases
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,mongodb,redis,prisma" alt="Backend & Databases" />
  </a>
</p>

### ☁️ Cloud, DevOps & Tooling
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=docker,aws,git,prometheus,grafana,postman" alt="DevOps & Tooling" />
  </a>
</p>

---

## 🧠 AI & Systems Expertise

| Domain | Proficiency | Details |
| :--- | :--- | :--- |
| **Semantic Search & Vector DBs** | Intermediate | Engineered pgvector integration with OpenAI embeddings, implementing hybrid ranking with importance and recency scores. |
| **LLM Observability** | Basic | Built trace ingestion APIs and anomaly detection systems for hallucination risks, tool failures, and cost/latency spikes. |
| **Core AI & Data Structures** | Basic | Implementation of AI search logic, database schemas, and structured file state trees. |

---

## 📁 Featured Projects

<details>
  <summary><b>🤖 AI Agent Observability Platform</b></summary>
  <br/>
  
  An enterprise-grade telemetry and diagnostic platform for tracking, auditing, and optimizing AI agents.

  | Attribute | Details |
  | :--- | :--- |
  | **Stack** | NestJS, PostgreSQL, Redis, Prisma, pgvector, Prometheus, Grafana, Docker |
  | **Scale** | Queue-driven asynchronous trace ingestion using BullMQ returning HTTP 202 Accepted |
  | **Performance** | Optimized ingestion pipelines to minimize runtime agent latency overhead |
  | **Security** | Multi-tenant isolation enforced via PostgreSQL Row-Level Security (RLS) and HMAC-signed webhooks |
  | **Impact** | Actionable insight dashboards tracking token usage, hallucination risk, and cost metrics |
  | **Repository** | [GitHub Repository](https://github.com/sidharth-shangonda/AI-Agent-Observability-Platform) |

  ### Professional Breakdown
  Designed and implemented a distributed trace ingestion service capturing detailed execution steps of LLM tools. Leveraging Redis queues and BullMQ workers, the platform safely decouples logging from agent runtime performance. It incorporates vector search (pgvector) for semantic memory querying and provides comprehensive observability using Prometheus scraping and Grafana dashboards.
</details>

<br/>

<details>
  <summary><b>📦 Custom VCS & GitHub Clone</b></summary>
  <br/>
  
  A custom command-line version control system combined with a web-based repository dashboard.

  | Attribute | Details |
  | :--- | :--- |
  | **Stack** | React, Node.js, Express.js, MongoDB, Mongoose, AWS S3, Socket.IO, yargs |
  | **Scale** | Full CLI implementation mapping core version control features; 18+ REST endpoints |
  | **Performance** | Quick snapshot diffing and staging storage utilizing UUID-based directories |
  | **Security** | Robust JWT auth and bcrypt hashing across client-web and CLI integrations |
  | **Impact** | Deep architectural understanding of file state trees, delta tracking, and remote sync |
  | **Repository** | [GitHub Repository](https://github.com/sidharth-shangonda/Custom-Version-Control-system-) |

  ### Professional Breakdown
  Engineered a custom CLI in Node.js mimicking core git operations (init, add, commit, push, pull). Designed the web service using React and Primer design system elements to sync commit history. Standardized authentication protocols across CLI commands and web APIs, utilizing AWS S3 as the remote object store for repository snapshot assets.
</details>

<br/>

<details>
  <summary><b>📚 Library Management System</b></summary>
  <br/>
  
  A full-stack web application streamlining campus book search, session-based issue/return tracking, and user dashboards.

  | Attribute | Details |
  | :--- | :--- |
  | **Stack** | Node.js, Express.js, MySQL, EJS Templates, CSS, express-session |
  | **Scale** | Multi-tenant user login and query pagination handling 50+ book listings per offset request |
  | **Performance** | Optimized query lookup utilizing MySQL connection pooling (limit 10 concurrent pools) |
  | **Security** | Session-based authentication safeguards and parameterized query shielding against SQL Injection |
  | **Impact** | Unified admin and member dashboard reducing book issue/return tracking times |
  | **Repository** | [GitHub Repository](https://github.com/sidharth-shangonda/Smart-Library-Management) |

  ### Professional Breakdown
  Created an end-to-end library administration backend exposing routes for registration, user profile querying, book search with pagination limits, and active issue tracking. Leveraged relational MySQL databases hosted with connection pool configurations, and integrated EJS views to construct a dynamic, responsive client dashboard.
</details>

---

## 💼 Experience

### **Independent Developer** | Academic & Open Source Projects (IIT Patna)
*2024 — Present*
> Developing data-driven systems, custom command-line utilities, and database applications.

*   Designed queue-driven telemetry ingestion frameworks processing high-frequency log events asynchronously.
*   Enforced multi-tenant isolation rules using PostgreSQL Row-Level Security (RLS) policies and HMAC verification gates.
*   Developed filesystem command-line utilities using Node.js, managing snapshots and remote object storage (AWS S3) synchronization.
*   Strengthened computer science fundamentals by solving 150+ algorithmic tasks and mentoring team members on database designs.

`TypeScript` `Node.js` `PostgreSQL` `Redis` `Prisma` `Docker` `System Design`

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
| :---: | :--- |
| 💼 **Deloitte Data Analytics** | Completed the Data Analytics Job Simulation via Forage, tackling tasks in data analysis and forensic technology (June 2026). |
| 🧩 **LeetCode Solver** | Completed 150+ data structure and algorithm challenges with optimal space/time complexity. |
| 🌟 **HackerRank Certificate** | Earned the Problem Solving (Intermediate) Certificate, demonstrating algorithmic proficiency. |

</div>

---

## 📊 Coding Profiles

<div align="center">
  <a href="https://leetcode.com/u/sidharth_LC/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-Sidharth__LC-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" />
  </a>
  <a href="https://www.hackerrank.com/profile/sidrockz192" target="_blank">
    <img src="https://img.shields.io/badge/HackerRank-sidrockz192-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank" />
  </a>
  <a href="https://codeforces.com/profile/sidrockz" target="_blank">
    <img src="https://img.shields.io/badge/Codeforces-sidrockz-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" />
  </a>
</div>

---

## 📈 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sidharth-shangonda&show_icons=true&title_color=a855f7&icon_color=6366f1&text_color=c084fc&bg_color=0d1117&border_color=a855f7&cache_seconds=1800&v=2" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sidharth-shangonda&currStreakNum=a855f7&sideNums=6366f1&sideLabels=c084fc&dates=ffffff&ring=a855f7&fire=6366f1&bg=0d1117&stroke=a855f7&v=2" alt="GitHub Streak Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sidharth-shangonda&layout=compact&title_color=a855f7&icon_color=6366f1&text_color=c084fc&bg_color=0d1117&border_color=a855f7&cache_seconds=1800&v=2" alt="Top Languages" />
</p>

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=sidharth-shangonda&theme=dracula&no-background=true&no-border=true&margin-w=15&margin-h=15&v=2" alt="GitHub Trophies" />
</p>

---

## 📅 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sidharth-shangonda&theme=react-dark&bg_color=0d1117&color=a855f7&line=6366f1&point=c084fc&v=2" alt="Activity Graph" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/sidharth-shangonda/sidharth-shangonda/output/github-contribution-grid-snake.svg" alt="Snake Game Grid" />
</p>

---

## 🎯 Current Focus

```yaml
learning: "Advanced Telemetry Pipelines, System Design, AI Systems Architecture"
building: "Scalable backend architectures and AI agent memory grids"
exploring: "AI Agent memory networks and distributed queue workers (Redis/BullMQ)"
open_to: "AI/ML & Data Science Internships"
```

---

## 🔌 Connect With Me

<div align="center">
  <a href="mailto:sidharthshangonda@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-sidharthshangonda@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://linkedin.com/in/sidharth-shangonda-63145336a" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Sidharth%20Shangonda-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/sidharth-shangonda" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-sidharth--shangonda-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

---

<p align="center">
  <i>"Scalability is not an afterthought, it is the foundation of digital longevity."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=7d2ae8,3f00e5&height=120&section=footer" alt="Footer Banner" />
</p>
