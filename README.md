**Software Architect · Backend / Full-Stack Engineer**

I take products from a customer's first meeting to a system that runs in production.
6 years across requirements, architecture, implementation, and operations.
Raised in Japan; have worked between Japanese clients and Korean engineering teams.

Lately: building RAG with **Upstage Embed 2** and **Solar Pro** over ~650K documents, wired by hand, no framework.

[Portfolio](https://blosseden.com/ko) | [Email](mailto:sua0326@gmail.com)

---

## Stack

**Languages**

<img src="https://skillicons.dev/icons?i=ts,java,kotlin,py,go,php" />

**Backend**

<img src="https://skillicons.dev/icons?i=nestjs,express,spring,django,fastapi" />

![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)

**Data**

<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,mongodb,dynamodb,supabase,kafka" />

![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white)

**Cloud & Infra**

<img src="https://skillicons.dev/icons?i=aws,gcp,cloudflare,vercel,docker,kubernetes,nginx,terraform,linux" />

**CI/CD & Observability**

<img src="https://skillicons.dev/icons?i=githubactions,gitlab,jenkins,grafana,prometheus" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,remix,vue,angular,jquery" />

**Desktop & Mobile**

<img src="https://skillicons.dev/icons?i=electron,flutter" />

**AI & ML**

<img src="https://skillicons.dev/icons?i=sklearn" />

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Upstage Embed 2](https://img.shields.io/badge/Upstage-Embed%202-6B4EFF?style=for-the-badge)
![Upstage Solar Pro](https://img.shields.io/badge/Upstage-Solar%20Pro-6B4EFF?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-Vector%20Search-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

---

## Selected Work

### RAG, end to end (2026)
*Add-on project for Visual Art Communication Agency*
- Embedded ~650K live-stream notices with **Upstage Embed 2**, stored and searched in **PostgreSQL + pgvector**
- **Solar Pro** answers with citations to the source notices
- No RAG framework: every piece connected directly through the APIs
- Evaluated retrieval ranking and answer citations against a question set

### Real-time live-stream analytics (solo: design, build, run)
- Collects chat, donation, and join/leave events in real time
- Redis leases assign one collector per stream to cut duplicate collection
- Restores the last valid value on failure to keep metrics continuous
- Detects high-value donations and alerts within **1 second**

### B2B SaaS for Japanese clients (Technical Manager)
- Owned client needs from the first sales meeting through requirements and technical design
- Designed and built multi-tenant architecture that keeps each client's data isolated

### E-commerce performance
- Main page load **2.9s → 0.51s**, review lookup **1.9s → 0.211s** through query and cache optimization

---

## Languages
Japanese (native) | Korean (native) | English (reading; basic conversation) | Chinese (HSK 5)
