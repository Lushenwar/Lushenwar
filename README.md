<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0e7490,100:22d3ee&height=200&section=header&text=Ryan%20Qi&fontColor=e2f6fb&fontSize=58&fontAlignY=36&desc=Software%20Engineer%20%C2%B7%20Infrastructure%20%C2%B7%20SRE&descSize=18&descAlignY=58&descColor=7dd3fc" width="100%" />

<p align="center">
  <img src="https://img.shields.io/badge/University%20of%20Waterloo-Math%20%C2%B7%20Data%20Science-000000?style=flat-square&logo=googlescholar&logoColor=22d3ee&labelColor=0d1117" alt="Waterloo Math, Data Science" />
  <img src="https://img.shields.io/badge/Waterloo,%20ON-Canada-0e7490?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0d1117" alt="Location" />
</p>

<p align="center">
  <a href="https://ryanqiportfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-22d3ee?style=for-the-badge&logo=vercel&logoColor=0d1117" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ryan-qi/"><img src="https://img.shields.io/badge/LinkedIn-0e7490?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:r28qi@uwaterloo.ca"><img src="https://img.shields.io/badge/Email-155e75?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Lushenwar"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=22d3ee" alt="GitHub" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Lushenwar&label=Profile%20Views&color=0e7490&style=flat-square" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Lushenwar?label=Followers&style=flat-square&color=0e7490&labelColor=0d1117&logo=github" alt="Followers" />
  <img src="https://img.shields.io/github/stars/Lushenwar?label=Stars&style=flat-square&color=0e7490&labelColor=0d1117&logo=github" alt="Stars" />
</p>

---

## Featured Projects

<details open>
<summary><b>⛴️ Ferryman</b> · Zero-Downtime Postgres Migrator</summary>

<br>

A Go CLI that orchestrates zero-downtime Postgres cutovers. It backfills in parallel ctid page ranges, streams live changes through logical replication, and only cuts over once replication lag clears its prechecks.

| | |
| :--- | :--- |
| **Stack** | Go · PostgreSQL · Logical Replication · Docker · GitHub Actions |
| **Scale** | Parallel backfill across ctid page ranges with live change streaming |
| **Safety** | Replication-lag gating, enforced DDL ordering, automated rollback to source state |
| **Reliability** | CI runs every migration against seeded Postgres instances |
| **Repository** | [Lushenwar/Ferryman](https://github.com/Lushenwar/Ferryman) |

</details>

<details open>
<summary><b>🛡️ Sentinel</b> · AI-Boosted Incident Response</summary>

<br>

An incident-response engine that cross-references git history against error logs to find the commit that broke production, then writes the diagnosis and postmortem for you.

| | |
| :--- | :--- |
| **Stack** | FastAPI · Next.js · TypeScript · PostgreSQL · RAG |
| **Performance** | Faulty commit surfaced as top candidate in ~13s; root-cause diagnosis in ~14s |
| **Coverage** | DB failures, memory leaks, null pointers, and other bug classes |
| **Automation** | RAG over runbooks; postmortems auto-posted to Slack when error rates cross thresholds |
| **Repository** | [Lushenwar/Sentinel](https://github.com/Lushenwar/Sentinel) |

</details>

---

## About

I'm a Math (Data Science) student at the **University of Waterloo** focused on **infrastructure and site reliability engineering**. I like the systems that keep everything else running: database migrations that can't lose data, incident tooling that finds the bad commit before a human does, and real-time code with bounded, predictable behavior.

My background spans embedded C++ flight software, a production clinical portal serving 400+ staff, and multi-agent AI pipelines. The common thread is correctness under load and knowing exactly what happens when something fails.

**Open to:** infrastructure, SRE, and backend engineering internships.

---

## Tech Stack

**Languages**

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c,go,typescript,javascript,java,bash&theme=dark" alt="Languages" />
</p>

**Frameworks**

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,fastapi,pytorch&theme=dark" alt="Frameworks" />
  <br>
  <img src="https://img.shields.io/badge/LangGraph-0e7490?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
</p>

**Data, Cloud &amp; Infrastructure**

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,aws,docker,githubactions,git,linux&theme=dark" alt="Data, Cloud and Infrastructure" />
  <br>
  <img src="https://img.shields.io/badge/Snowflake-0e7490?style=flat-square&logo=snowflake&logoColor=white" alt="Snowflake" />
</p>

---

## Engineering Focus

<div align="center">

| Domain | Proficiency | Details |
| :--- | :---: | :--- |
| **Infrastructure / SRE** | ●●●●○ | Zero-downtime migrations, logical replication, incident response, CI gating |
| **Backend Systems** | ●●●●○ | FastAPI, Express, PostgreSQL schemas, role-based access control |
| **Systems Programming** | ●●●●○ | Real-time C++, no dynamic allocation in control loops, build optimization |
| **Applied AI** | ●●●○○ | RAG pipelines, multi-agent LangGraph orchestration, K-Means clustering |

</div>

---

## Experience

**Software Engineer Intern** · Mon Sheong Foundation
`May 2026 – Aug 2026`

Digitized fully paper-based care workflows into an end-to-end clinical portal.
- Built the Next.js / Node.js portal, cutting patient record retrieval time by 40% across daily nursing operations.
- Engineered role-based access control for Express APIs and PostgreSQL schemas, scoping every query by role for 400+ staff across 30 roles.
- Built real-time React dashboards with automated threshold-triggered alerts for clinical metrics.

<sub>`Next.js` `Node.js` `Express` `PostgreSQL` `RBAC` `React`</sub>

<br>

**Embedded Flight Software Developer** · Waterloo Aerial Robotics Group (WARG)
`Sep 2025 – Jan 2026`

- Removed dynamic memory allocation from the real-time control loop of C++ flight modules for deterministic, bounded execution.
- Restructured header dependency trees and build scripts, reducing firmware compile time by 25%.
- Optimized IMU sensor fusion filters to eliminate jitter, reaching 95% signal consistency.

<sub>`C++` `Embedded` `Real-Time Systems` `Build Systems` `Sensor Fusion`</sub>

<br>

**Research Lead** · UpNxxt (via Riipen Labs)
`May 2026 – Jun 2026`

- Led UX research for the AI Sandbox, analyzing competitor engagement loops to cut onboarding friction.
- Designed child-first mechanics adopted into the roadmap, contributing to a 15% DAU lift over six months.

<sub>`UX Research` `Product Strategy` `Retention`</sub>

---

## Achievements

<div align="center">

| Recognition | Details |
| :--- | :--- |
| 🥇 **1st Place, GenAI Genesis 2026** | [Eco-Pulse](https://github.com/Lushenwar/Eco-Pulse): urban heat planner over 178K land parcels |
| 🏆 **Winner, DeerHacks V** | [LOCATR](https://github.com/Lushenwar/LOCATR): 6-agent LangGraph venue planner, <1s cached |
| 🏆 **Best Use of Snowflake** | CxC 2026 |
| 🎖️ **Finalist, 4 Tracks** | YHacks Spring 2026 |
| 🥉 **3rd Place, Beginner Stream** | Hack404 |

</div>

---

## GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=Lushenwar&show_icons=true&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=22d3ee&text_color=9fb3c8&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Lushenwar&hide_border=true&background=0d1117&stroke=22d3ee&ring=22d3ee&fire=22d3ee&currStreakLabel=22d3ee&sideLabels=9fb3c8&dates=546e7a&currStreakNum=e2f6fb&sideNums=e2f6fb" alt="GitHub Streak" />
</p>

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Lushenwar&layout=compact&hide_border=true&bg_color=0d1117&title_color=22d3ee&text_color=9fb3c8&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Lushenwar/Lushenwar/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" width="100%" />
</p>

<p align="center">
  <img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D Contribution Graph" width="100%" />
</p>

---

## Current Focus

```yaml
learning:    [ distributed systems, database internals, observability ]
building:    [ zero-downtime data tooling, incident response automation ]
exploring:   [ Kubernetes, SLOs and error budgets, chaos engineering ]
open_to:     [ infrastructure / SRE / backend internships ]
```

---

## Connect

<p align="center">
  <a href="mailto:r28qi@uwaterloo.ca"><img src="https://img.shields.io/badge/Gmail-155e75?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://www.linkedin.com/in/ryan-qi/"><img src="https://img.shields.io/badge/LinkedIn-0e7490?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/Lushenwar"><img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=22d3ee" alt="GitHub" /></a>
  <a href="https://ryanqiportfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-22d3ee?style=for-the-badge&logo=vercel&logoColor=0d1117" alt="Portfolio" /></a>
</p>

<p align="center"><i>Build systems that fail safely.</i></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,50:0e7490,100:0d1117&height=120&section=footer" width="100%" />
