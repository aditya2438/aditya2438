<div align="center">

<!-- HERO BANNER -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero.svg">
  <img src="assets/hero.svg" alt="Aditya Chouhan — Java Backend Developer &amp; Distributed Systems Engineer" width="100%">
</picture>

<br/>

<!-- DYNAMIC ANIMATED TYPING SVG -->
<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&duration=3200&pause=800&color=E5B5C7&center=true&vCenter=true&width=950&height=70&repeat=true&lines=Java+Backend+Developer+%E2%80%A2+Distributed+Systems+Engineer;Spring+Boot+3.3+%7C+Apache+Kafka+%7C+Redis+Caching;Pessimistic+Locking+%E2%80%A2+PostgreSQL+3NF+ACID+Design;High-Throughput+APIs+%E2%80%A2+Sub-25ms+Response+Latency;Spring+AI+Integration+%E2%80%A2+Docker+Containerization" alt="Typing SVG" />

<br/>

<!-- ACADEMIC & LOCATION PILLS -->
<p align="center">
  <img src="https://img.shields.io/badge/B.Tech-Computer_Science_%26_Engineering-701A3D?style=for-the-badge&labelColor=190B12" alt="B.Tech Computer Science &amp; Engineering" />
  <img src="https://img.shields.io/badge/SVVV_Indore-2022--2026-451126?style=for-the-badge&labelColor=190B12" alt="Shri Vaishnav Vidyapeeth Vishwavidyalaya" />
  <img src="https://img.shields.io/badge/Location-Madhya_Pradesh%2C_India-701A3D?style=for-the-badge&labelColor=190B12" alt="Location" />
</p>

<!-- TRANSMISSION & SOCIAL BADGES -->
<p align="center">
  <a href="https://linkedin.com/in/aditya-chouhan" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Aditya_Chouhan-701A3D?style=for-the-badge&logo=linkedin&logoColor=F8F0F3" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:adityachouhan2446@gmail.com">
    <img src="https://img.shields.io/badge/Email-adityachouhan2446%40gmail.com-451126?style=for-the-badge&logo=gmail&logoColor=F8F0F3" alt="Email" />
  </a>
  &nbsp;
  <a href="https://github.com/aditya2438">
    <img src="https://img.shields.io/badge/GitHub-aditya2438-190B12?style=for-the-badge&logo=github&logoColor=F8F0F3" alt="GitHub" />
  </a>
</p>

<!-- REAL-TIME TELEMETRY COUNTERS -->
<p align="center">
  <a href="https://github.com/aditya2438">
    <img src="https://komarev.com/ghpvc/?username=aditya2438&label=PROFILE+VIEWS&style=for-the-badge&color=701a3d" alt="Profile Views" />
  </a>
  &nbsp;
  <a href="https://github.com/aditya2438">
    <img src="https://img.shields.io/github/followers/aditya2438?style=for-the-badge&color=701A3D&labelColor=190B12&logo=github&label=FOLLOWERS" alt="Followers" />
  </a>
  &nbsp;
  <a href="https://github.com/aditya2438?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-Public_Projects-451126?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
  </a>
</p>

</div>

---

### <img src="assets/section-about.svg" alt="01 // Architectural Profile" width="100%" />

> **"Resilient distributed backends are built on deterministic state transitions, asynchronous decoupling, and zero single-points-of-failure."**

I am a **Java Backend Developer & Software Engineer** focused on architecting scalable microservices, low-latency transaction pipelines, and distributed event-driven systems. My core engineering practices center on **Java 21**, **Spring Boot 3.3**, asynchronous stream processing with **Apache Kafka**, and in-memory caching with **Redis**.

- 🎓 **Academic Grounding**: Pursuing **B.Tech in Computer Science & Engineering** (2022 – 2026) at **Shri Vaishnav Vidyapeeth Vishwavidyalaya, Indore** (CGPA: 6.98 / 10.0).
- ⚙️ **Architectural Focus**: Decoupled microservices with Dead-Letter Queues (DLQ), strict 3NF schema modeling with ACID compliance, and Spring AI integrations.
- ⚡ **High Concurrency & Latency Optimization**: Database query indexing, pessimistic row-level locking for inventory integrity, and Redis distributed caching sustaining sub-25ms response windows.
- 📍 **Base**: Ujjain / Indore, Madhya Pradesh, India — *Available for Backend & Software Engineering Opportunities*.

<br/>

#### 🎯 Open To
`Java Backend Development` • `Distributed Systems Engineering` • `Microservices Architecture` • `Software Engineering` • `Cloud-Native Backend`

<br/>

---

### <img src="assets/section-projects.svg" alt="02 // System Architectures" width="100%" />

<table>
<tr>
<td width="50%" valign="top">

### 🛒 FairCart
**AI-Powered Distributed E-Commerce & Smart Cart Platform**

> Event-driven microservices architecture handling high-concurrency order workflows, AI price negotiation, and sub-25ms response windows.

```
[ Auth Service ] ──┐
[ Cart Service ] ──┼──> [ Apache Kafka Event Stream ] ──> [ Inventory / Orders ]
[ Catalog Svc  ] ──┘         └── Dead-Letter Queue (DLQ)       └── PostgreSQL (3NF)
```

- **Distributed Event Streams**: Decoupled 5 microservices (`Auth`, `Catalog`, `Cart`, `Order`, `Inventory`) communicating asynchronously via Apache Kafka with Dead-Letter Queues (DLQ) for fault-tolerant dispatching.
- **Spring AI Deal Negotiation**: Embedded Spring AI with Large Language Models for real-time dynamic deal negotiation, personalized recommendations, and cart abandonment anomaly detection.
- **Sub-25ms Caching Layer**: Engineered Redis distributed caching for session and cart state, cutting primary database read overhead by **55%** under simulated flash-sale loads.
- **ACID & Pessimistic Locking**: Designed normalized (3NF) PostgreSQL schemas via Hibernate/JPA, implementing pessimistic write locking to prevent inventory overselling race conditions.
- **Containerized Security**: Enforced stateless JWT & OAuth2 RBAC; containerized all microservices with Docker.

<br/>

<div>
  <img src="https://img.shields.io/badge/Java_21-451126?style=flat-square&logo=openjdk&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Spring_Boot_3.3-701A3D?style=flat-square&logo=springboot&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Spring_AI-451126?style=flat-square&logo=spring&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Apache_Kafka-190B12?style=flat-square&logo=apachekafka&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Redis-701A3D?style=flat-square&logo=redis&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/PostgreSQL-451126?style=flat-square&logo=postgresql&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Docker-190B12?style=flat-square&logo=docker&logoColor=E5B5C7" />
</div>

<br/>

🔗 **Repository**: [github.com/aditya2438/Faircart](https://github.com/aditya2438/Faircart)

</td>
<td width="50%" valign="top">

### 🛠️ FixMate (Fixora)
**On-Demand Local Service Booking Marketplace**

> Multi-role service platform with Haversine spherical geo-proximity routing, collision-free slot booking, and automated job state machines.

```
[ Customer / Admin / Pro ] ──> [ Stateless JJWT Gateway ]
                                         │
        ┌────────────────────────────────┴────────────────────────┐
        ▼                                                         ▼
[ Haversine Geo-Proximity ]                             [ 5-Stage Job Lifecycle ]
(Ujjain • Indore • Bhopal)                              BOOKED ➔ IN_PROGRESS ➔ PAID
```

- **Multi-Role Role-Based Architecture**: Production-ready service marketplace serving distinct dashboards (`Customer`, `Service Pro`, `Admin`) secured by stateless JJWT authentication and BCrypt password encryption.
- **Haversine Geo-Proximity Routing**: Designed location-aware service discovery calculating radial distances via the Haversine formula across city clusters (Ujjain, Indore, Bhopal) with collision-free slot reservations.
- **Relational Schema Rigor**: Architected **17 normalized (3NF) tables** in MySQL 8.0 with composite B-Tree indexes, foreign key cascading, and ACID stored procedures for dispute auditing.
- **Automated 5-Stage Job Pipeline**: Engineered an automated state machine (`BOOKED` → `ASSIGNED` → `IN_PROGRESS` → `COMPLETED` → `PAID`) with real-time status tracking; deployed on Render.

<br/>

<div>
  <img src="https://img.shields.io/badge/Java_21-451126?style=flat-square&logo=openjdk&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Spring_Boot_3.3-701A3D?style=flat-square&logo=springboot&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Spring_Security-451126?style=flat-square&logo=springsecurity&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/MySQL_8.0-190B12?style=flat-square&logo=mysql&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Redis-701A3D?style=flat-square&logo=redis&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-451126?style=flat-square&logo=tailwindcss&logoColor=E5B5C7" />
  <img src="https://img.shields.io/badge/Render-190B12?style=flat-square&logo=render&logoColor=E5B5C7" />
</div>

<br/>

🔗 **Repository**: [github.com/aditya2438/Fixora](https://github.com/aditya2438/Fixora)

</td>
</tr>
</table>

<br/>

---

### <img src="assets/section-skills.svg" alt="03 // Technical Specifications" width="100%" />

#### ⚡ Visual Technology Stack

<p align="left">
  <strong>Languages:</strong><br/>
  <img src="https://skillicons.dev/icons?i=java,cpp,js,html,css&theme=dark" alt="Languages" />
</p>

<p align="left">
  <strong>Backend &amp; Distributed Systems:</strong><br/>
  <img src="https://skillicons.dev/icons?i=spring,kafka,hibernate&theme=dark" alt="Backend &amp; Distributed" />
</p>

<p align="left">
  <strong>Databases &amp; Caching:</strong><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,redis,mongodb,supabase&theme=dark" alt="Databases &amp; Caching" />
</p>

<p align="left">
  <strong>DevOps, Tooling &amp; Cloud:</strong><br/>
  <img src="https://skillicons.dev/icons?i=docker,git,github,maven,gradle,postman,idea,vscode&theme=dark" alt="DevOps &amp; Tools" />
</p>

<br/>

#### 🏷️ Detailed Competency Badges

<table width="100%">
<tr>
  <td width="25%" valign="top"><strong>Languages</strong></td>
  <td>
    <img src="https://img.shields.io/badge/Java_21_/_17-451126?style=for-the-badge&logo=openjdk&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/SQL-701A3D?style=for-the-badge&logo=postgresql&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/JavaScript_ES6+-190B12?style=for-the-badge&logo=javascript&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/C++-451126?style=for-the-badge&logo=cplusplus&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/HTML5_/_CSS3-701A3D?style=for-the-badge&logo=html5&logoColor=E5B5C7" />
  </td>
</tr>
<tr>
  <td width="25%" valign="top"><strong>Backend &amp; Distributed</strong></td>
  <td>
    <img src="https://img.shields.io/badge/Spring_Boot_3.3-451126?style=for-the-badge&logo=springboot&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Spring_Security-701A3D?style=for-the-badge&logo=springsecurity&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Spring_AI-190B12?style=for-the-badge&logo=spring&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Hibernate_JPA-451126?style=for-the-badge&logo=hibernate&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/RESTful_APIs-701A3D?style=for-the-badge&logo=fastapi&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Microservices-190B12?style=for-the-badge&logo=diagram-project&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/JDBC_&_JSP-451126?style=for-the-badge&logo=java&logoColor=E5B5C7" />
  </td>
</tr>
<tr>
  <td width="25%" valign="top"><strong>Databases &amp; Caching</strong></td>
  <td>
    <img src="https://img.shields.io/badge/PostgreSQL-451126?style=for-the-badge&logo=postgresql&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/MySQL_8.0_(3NF)-701A3D?style=for-the-badge&logo=mysql&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Redis_(Cache_/_DLQ)-190B12?style=for-the-badge&logo=redis&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/MongoDB-451126?style=for-the-badge&logo=mongodb&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Supabase-701A3D?style=for-the-badge&logo=supabase&logoColor=E5B5C7" />
  </td>
</tr>
<tr>
  <td width="25%" valign="top"><strong>Cloud, DevOps &amp; Tools</strong></td>
  <td>
    <img src="https://img.shields.io/badge/Docker-451126?style=for-the-badge&logo=docker&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Apache_Kafka-701A3D?style=for-the-badge&logo=apachekafka&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Git_&_GitHub-190B12?style=for-the-badge&logo=github&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Maven_&_Gradle-451126?style=for-the-badge&logo=apachemaven&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Postman-701A3D?style=for-the-badge&logo=postman&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/JUnit_5_&_Mockito-190B12?style=for-the-badge&logo=testinglibrary&logoColor=E5B5C7" />
    <img src="https://img.shields.io/badge/Render_&_Vercel-451126?style=for-the-badge&logo=render&logoColor=E5B5C7" />
  </td>
</tr>
<tr>
  <td width="25%" valign="top"><strong>Core Disciplines</strong></td>
  <td>
    <code>Data Structures &amp; Algorithms (DSA)</code> • <code>Object-Oriented Design (OOPs)</code> • <code>System Design Basics</code> • <code>Database Indexing (B-Tree)</code> • <code>JWT &amp; OAuth2 RBAC</code> • <code>Pessimistic / Optimistic Locking</code> • <code>CI/CD Fundamentals</code>
  </td>
</tr>
</table>

<br/>

---

### <img src="assets/section-focus.svg" alt="04 // Current Focus &amp; Matrix" width="100%" />

```yaml
Architectural Systems:
  - Java 21 & Modern Spring Boot 3.3 Ecosystem
  - Distributed Microservices & Asynchronous Event Streams
  - Apache Kafka Message Broker with Dead-Letter Queues (DLQ)
  - Fault-Tolerant System Decoupling & Service Discovery

Data Integrity & High Concurrency:
  - Normalized Relational Modeling (3NF) in PostgreSQL & MySQL 8.0
  - Pessimistic Row-Level Locking to Prevent Inventory Overwrites
  - Distributed In-Memory Caching with Redis (<25ms Latency)
  - Composite B-Tree Indexing & Stored Procedures for Auditing

Actively Engineering & Exploring:
  - Spring AI & LLM Model Integration for Business Automations
  - Containerization with Docker & Cloud Production Workflows
  - Spherical Geo-Proximity Algorithms (Haversine Formula)

Open To Roles:
  - Java Backend Developer
  - Distributed Systems Engineer
  - Microservices & Cloud Architect
  - Software Development Engineer (SDE)
```

<br/>

---

### <img src="assets/section-achievements.svg" alt="05 // Verified Recognition" width="100%" />

| Milestone / Certification | Authority & Scope | Focus & Verification |
| :--- | :--- | :--- |
| **Accenture Innovation Challenge 2024** | **Accenture** • National Hackathon | Explored and engineered enterprise-grade corporate technology solutions and system prototypes. |
| **Cloud Computing & Java Programming** | **NPTEL / IIT Kharagpur** | Rigorous specialization in distributed cloud paradigms, virtualization, networking, and enterprise Java. |
| **Relational Databases & MySQL** | **Oracle** | Deep verification in 3NF schema design, ACID transactions, B-Tree index optimization, and stored procedures. |

<br/>

---

### <img src="assets/section-experience.svg" alt="06 // Professional Tracks" width="100%" />

- 💼 **Virtual Internship — Flipr Labs**: Completed comprehensive web development tracks focusing on scalable backend architectures, high-performance REST APIs, and production deployment standards.
- 💡 **Industry Training — Infosys Springboard**: Mastered enterprise computing foundations, modern Java backend principles, and distributed web system evaluations.
- 🔍 **Academic Evaluation — OneVarsity**: Assessed full-stack project criteria and microservices performance benchmarks.

<br/>

---

### <img src="assets/section-activity.svg" alt="07 // Contribution Metrics" width="100%" />

<div align="center">

<!-- CONTRIBUTION SNAKE ANIMATION & GENUINE HEATMAP -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aditya2438/aditya2438/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aditya2438/aditya2438/output/github-snake.svg">
  <img src="https://ghchart.rshah.org/C77B9B/aditya2438" alt="Aditya Chouhan GitHub Contributions Heatmap" width="100%" />
</picture>

<br/><br/>

<!-- REAL-TIME BURGUNDY GITHUB STATISTICS & STREAK -->
<table border="0" align="center">
  <tr>
    <td align="center" valign="middle">
      <img src="https://github-readme-stats.vercel.app/api?username=aditya2438&show_icons=true&bg_color=10070C&title_color=E5B5C7&text_color=F8F0F3&icon_color=C77B9B&border_color=451126&include_all_commits=true" alt="Aditya Chouhan GitHub Stats" height="195" />
    </td>
    <td align="center" valign="middle">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=aditya2438&background=10070C&border=451126&stroke=C77B9B&ring=701A3D&fire=C77B9B&currStreakNum=F8F0F3&sideNums=E5B5C7&currStreakLabel=C77B9B&sideLabels=9D7286&dates=9D7286" alt="Aditya Chouhan Streak Stats" height="195" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" valign="middle">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aditya2438&layout=compact&bg_color=10070C&title_color=E5B5C7&text_color=F8F0F3&border_color=451126" alt="Aditya Chouhan Top Languages" width="360" />
    </td>
  </tr>
</table>

<p align="center">
  <sub><em>Metrics and contribution telemetry stream directly from the GitHub API via verified SVG visualizers.</em></sub>
</p>

</div>

<br/>

---

### <img src="assets/section-connect.svg" alt="08 // Transmission Channels" width="100%" />

<div align="center">

<!-- CODING & PROFESSIONAL PROFILES -->
<p align="center">
  <a href="https://github.com/aditya2438" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-aditya2438-190B12?style=for-the-badge&logo=github&logoColor=F8F0F3" alt="GitHub" />
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/aditya-chouhan" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Aditya_Chouhan-701A3D?style=for-the-badge&logo=linkedin&logoColor=F8F0F3" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/adityachouhan/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-Aditya_Chouhan-FFA116?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=190B12" alt="LeetCode" />
  </a>
</p>

<table align="center">
| Channel | Destination / Endpoint | Scope |
| :--- | :--- | :--- |
| **LinkedIn** | [linkedin.com/in/aditya-chouhan](https://linkedin.com/in/aditya-chouhan) | Engineering discussions, technical writings & networking |
| **Email** | [adityachouhan2446@gmail.com](mailto:adityachouhan2446@gmail.com) | Direct inquiries, system conversations & job opportunities |
| **GitHub** | [github.com/aditya2438](https://github.com/aditya2438) | Source repositories, microservice codebases & architectures |
| **Location** | Ujjain & Indore, Madhya Pradesh, India | Open to on-site, hybrid, or remote engineering positions |
</table>

<br/>

<!-- MINIMAL ANIMATED SVG FOOTER -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/footer.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/footer.svg">
  <img src="assets/footer.svg" alt="Aditya Chouhan — Engineered for Resilience" width="100%">
</picture>

</div>
