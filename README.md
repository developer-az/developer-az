
<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=2500&pause=6500&color=888888&center=true&vCenter=true&width=500&lines=Hi+%F0%9F%91%8B+I%27m+Anthony+Zhou" alt="Hi, I'm Anthony Zhou" />
  </a>
</h1>

<p align="center">
  <strong>Software Engineering · Full-Stack & Data Systems</strong><br>
  B.S. in Information Science @ University of Maryland · May 2027<br>
  Building reliable APIs, transactional systems, and data-driven products with Java, TypeScript, Python, and PostgreSQL.<br>
  <strong>Open to 2027 new-grad software engineering roles in Boston, DC, and New York.</strong>
</p>

<p align="center">
  <a href="https://www.anthony-zhou.com"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/anthony--zhou"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:azhou112@terpmail.umd.edu"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://youtube.com/@anthonyzhou"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white" alt="YouTube" /></a>
</p>

## About me

- 💼 **Software Engineering Intern, Kin2College** (Summer 2026): Engineered Express REST APIs with JWT authentication and role-based authorization, implemented scheduled PostgreSQL notification processing with audit logging and duplicate-send prevention, and secured data access by moving client-side database mutations behind server-enforced functions. Established GitHub Actions CI and branch protection to enforce automated validation.

- 🛰️ **Software Engineer Intern, Development Monitors** (Summer 2025): Developed Python-based geospatial data pipelines and a QGIS integration to process satellite and UAV imagery, extract building and waterway features, and persist structured geographic data in PostgreSQL for analysis and visualization across international development projects.

- 🔗 **Software Development Intern, allBETs** (2025): Validated payment processing and fraud-prevention behavior across web and mobile platforms, tested transaction edge cases ahead of an iOS release, and contributed Solidity smart contract logic.

- 🌱 **Open source, [go-fast-cdn](https://github.com/kevinanielsen/go-fast-cdn)**: Recent open-source work as part of the CodePath AI Engineering Capstone.

- 🧑‍🏫 **Undergraduate course aide** for Computer Networking & Systems (INST346) and Object-Oriented Programming in Python (INST326): Help students troubleshoot Linux/SSH environments, PowerShell automation, Wireshark packet captures, and Python programming assignments.

## Featured projects

| Project | Engineering highlights | Stack |
|---|---|---|
| **[p2p-ledger](https://github.com/developer-az/p2p-ledger)** · [Assistant demo](https://ledger.anthony-zhou.com) | Double-entry payments system designed around transactional correctness and concurrency safety. Implemented idempotent transfers, deterministic row-lock ordering to prevent deadlocks, and database-enforced ledger invariants. Used a transactional outbox to coordinate committed transactions with asynchronous event delivery. Added HTTP 503 load shedding after k6 testing exposed JVM memory exhaustion at 500 req/s on a 512 MB container. Integrated an LLM-powered assistant with server-enforced, account-scoped tool execution. | Java, Spring Boot, PostgreSQL, Kafka / AWS SQS, TypeScript, k6 |
| **[Racket Form](https://racketform.anthony-zhou.com)** | Interactive tennis biomechanics and equipment analysis platform. Built 3D skeletal stroke visualization with corrected joint-transform calculations, including resolving elbow rotation artifacts during animation. Aggregates racket specifications and professional usage data through Next.js API routes, computes equipment scores from measurable attributes, and maintains player profiles using local-first persistence with cloud synchronization. | Next.js, TypeScript, React Three Fiber, PostgreSQL |
| **[UMD Tennis Court Alerts](https://github.com/developer-az/tennis-court-reserve-umd)** | Automated reservation availability monitoring and notification service. Implemented scheduled availability checks, verified email subscriptions, and one-click unsubscribe functionality. Integrated GitHub Actions CI to run TypeScript checks, unit tests, and production builds on pushes to `main`. | Next.js, TypeScript, Upstash Redis, Resend, Vercel |
| **[Portfolio](https://www.anthony-zhou.com)** | Interactive personal website featuring scroll-driven transitions, WebGL-rendered backgrounds, an expandable resume interface, and a Spotify Wrapped-inspired development activity visualization. | Next.js, Framer Motion, GSAP, Three.js, Sass |

## Tech stack

**Languages**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)

**Backend & data**<br>
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-404D59?style=for-the-badge&logo=express&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Testing & reliability**<br>
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-548B54?style=for-the-badge&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Cloud & DevOps**<br>
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Amazon ECS](https://img.shields.io/badge/Amazon_ECS-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white)
![Amazon EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![AWS IAM](https://img.shields.io/badge/AWS_IAM-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0DB7ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**AI-assisted development & agentic workflows**<br>
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/OpenAI_Codex-412991?style=for-the-badge&logo=openai&logoColor=white)
![Hermes Agent](https://img.shields.io/badge/Hermes_Agent-374151?style=for-the-badge&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

In my daily development workflow I leverage a personalized AI agent setup. I always follow up with to manually do code analysis, refactoring, and debugging every day and am versed in automated tests, and CI pipelines.

## GitHub stats

<p align="center">
  <a href="https://github.com/developer-az"><img height="165" src="https://commit-warrior.vercel.app/api/stats?username=developer-az&theme=professional&show_icons=true&hide_rank=true" alt="GitHub stats" /></a>
  <img height="165" src="https://commit-warrior.vercel.app/api/top-langs?username=developer-az&theme=professional&layout=compact" alt="Top languages" />
</p>
