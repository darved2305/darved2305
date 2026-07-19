<div align="center">

# Darshan Ved

**Full-Stack Engineer · Data Science Undergrad · Mumbai**

Finalist at 8+ national hackathons · Currently building algorithmic trading infrastructure

<a href="https://darshanved.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/darshan-ved-38075632a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://github.com/darved2305"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="mailto:darshanmved@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## About

Computer Science and Engineering undergrad at **Dwarkadas J. Sanghvi College of Engineering**, specializing in Data Science.

I build backend systems that carry real load: market data pipelines feeding live algorithmic strategies, lead intelligence engines that replace manual work outright, and health platforms that turn raw lab reports into something a person can actually read. Most of what I ship is measured — latency, Lighthouse, conversion, coordination hours removed — because unmeasured work is indistinguishable from work that didn't happen.

Currently deep in **Java DSA**, **system design**, **backend architecture**, and **generative AI integrations**.

---

## Experience

### Backend Developer Intern · Apt, Algo Trading
`Jul 2026 – Present · Remote`

Building the broker-facing backend that carries an algorithmic strategy from code to live automated execution, spanning market data ingestion through to real orders placed for real traders.

- Migrated market data pipelines from **AWS S3** to **EBS**-backed storage, cutting read latency on the hot path that live strategies depend on for entry and exit decisions
- Built a **strategy SDK** so a strategy authored in code deploys straight into automated execution, and debugged the **SQS → Lambda → ECS** pipeline behind it across queueing, invocation, and container rollout

### SDE Intern · Motilal Oswal Financial Services Ltd
`May 2026 – Jul 2026 · Mumbai, Maharashtra`

- Shipped a full-stack **lead deduplication and filtering tool** in **React.js** and **Node.js/Express**, letting business teams strip existing clients out of incoming marketing lead lists before a single sales call was made
- Engineered the backend matching layer and tuned the **SQL** queries behind it to cross-reference every incoming lead batch against millions of existing customer records in one automated pass
- Integrated third-party **data validation APIs** to auto-verify customer PAN and Aadhaar details at ingestion, rejecting fake and malformed entries before they could reach the CRM

### Software Developer Intern · Pelorus Occupational Therapy
`Jan 2026 – Jun 2026 · Melbourne, Australia · Remote`

- Replaced manual patient discovery with a **TypeScript** lead-discovery agent monitoring public **Reddit, Facebook, and Whirlpool** posts, polling every **15–20 minutes** to stay inside rate limits and harvesting **1,200+** raw interactions, fingerprint-deduplicated into **PostgreSQL**
- Integrated the **Facebook Graph API**, **Apify**, and **SERP API** to surface occupational-therapy intent across **Melbourne and Adelaide**, ranked by multi-signal intent scoring and a **4-tier priority classifier**
- Delivered a role-based **React** admin dashboard for lead prioritization, deduplication, filtering, and outreach tracking, cutting therapist coordination work by **50%**

### Full Stack Engineer · Shreshth Sugamaya Governance LLP
`Feb 2026 – Apr 2026 · Mumbai, Maharashtra`

- Owned full-stack delivery end to end, architecting the **REST APIs** and restructuring the database query paths behind them so the frontend read what it needed in one round trip instead of several
- Enforced testing and debug pipelines across a hybrid development environment, holding **zero-downtime deployments** and stable interfaces under load through every release

### Frontend Developer Intern · Theta Sound
`Sep 2025 – Jan 2026 · Chennai, Tamil Nadu · Remote`

- Removed performance bottlenecks across high-traffic **Next.js** pages using component-level code splitting and lazy hydration, lifting Lighthouse scores by **40%+**
- Eliminated **Cumulative Layout Shift** regressions by **60%+** across every breakpoint, holding the interface stable under load on both desktop and mobile
- Shipped a reusable **WCAG 2.1 AA**-compliant **React** design system on a structured weekly release cadence, compressing Figma-to-production turnaround by **30%** and lifting session engagement **35%+**

### Software Developer Intern · Parmar Properties
`Jun 2025 – Sep 2025 · Mumbai, Maharashtra`

- Removed the human from lead qualification with a real-time **AI voice agent** on **GPT-4o Realtime** and **FastAPI WebSockets**, automating STT/TTS intent routing, scheduling, and follow-up triggers at **sub-300ms** latency and cutting manual effort **60%**
- Engineered a **CRM lead capture pipeline** enriching every live inbound call into **PostgreSQL** with algorithmic intent scores and structured call summaries
- Rebuilt the landing pages with lazy hydration and asset compression, lifting Lighthouse scores by **45%** and inbound conversion rates by **30%**

---

## Featured Projects

### Lumea — AI Health Companion Platform
[![Repo](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/darved2305/Lumea)

`React` `TypeScript` `FastAPI` `PostgreSQL` `ChromaDB` `Neo4j` `PaddleOCR` `OpenRouter` `ElevenLabs` `Gemini` `Three.js` `Docker`

A health companion that reads your medical reports and tells you what actually needs attention.

- **Physics Twin scoring engine** on **PaddleOCR** + pdfplumber ingests uploaded medical reports and computes **0–100 Health Indices** across **6 organ systems** through clinical normalization
- Auto-detects **10 conditions** with severity mapping, turning a wall of raw lab values into a ranked, plain-language read
- Streams SVG body-impact overlays onto a **Three.js** 3D viewer via live **SSE** telemetry at 2-second intervals, so a flagged marker lights up the organ system it belongs to
- **Mem0** + **Graphiti** persistent knowledge graph on **Neo4j** enables **cross-session contradiction detection** across a patient history spanning many reports
- Voice agent combining Web Speech STT, **Gemini**-powered **RAG**, and ElevenLabs TTS with emergency detection
- Medicine Finder querying a **600,000-entry** Jan Aushadhi drug catalog with live pharmacy lookup

### Synapse — Decentralized AI Model Marketplace
[![Repo](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/darved2305/Synapse)

`Solidity 0.8.26` `Next.js 15` `FastAPI` `Python` `Lit Protocol v7` `IPFS` `Ponder v7` `OpenZeppelin v5`

Model ownership on-chain: list a model, control who runs it, earn on every call.

- **6 Solidity 0.8.26 contracts** deployed to Ethereum Sepolia
- **ERC-721** model NFTs with **10-payee revenue splits**, per-call escrow with pull-payment settlement, **EWMA** staked node selection, **ERC-5192** soulbound reputation badges
- Real **HuggingFace** pipeline execution on staked nodes with **Lit Protocol v7** per-token access control and **IPFS** encrypted weight delivery — model files stay private while payments and ownership stay publicly verifiable
- **FastAPI** orchestrator with **SIWE** wallet auth and nonce-serialized settlement signing to keep concurrent payouts from racing
- **Ponder v7 GraphQL** indexer plus a **LangChain** wrapper published to PyPI, so agents can call marketplace models as ordinary tools
- Full **Next.js 15** App Router frontend across **20+ pages**: wallet login, model discovery, upload, purchase, ownership dashboard

---

## Technologies

**Languages**

<img src="https://go-skill-icons.vercel.app/api/icons?i=java,python,c,mysql,javascript,typescript&perline=6" alt="Languages" />

**Frameworks**

<img src="https://go-skill-icons.vercel.app/api/icons?i=spring,react,nextjs,nodejs,express,fastapi&perline=6" alt="Frameworks" />

**Backend & Tools**

<img src="https://go-skill-icons.vercel.app/api/icons?i=kafka,docker,prisma,postman,git,github&perline=6" alt="Backend and Tools" />

**Cloud & Databases**

<img src="https://go-skill-icons.vercel.app/api/icons?i=aws,postgres,mongodb,firebase,neo4j,redis&perline=6" alt="Cloud and Databases" />

**AI & ML**

<img src="https://go-skill-icons.vercel.app/api/icons?i=langchain,openai,huggingface,pytorch&perline=4" alt="AI and ML" />

<sub>Also: REST APIs · JWT · AWS Lambda, EC2, S3 · ChromaDB · RAG · LangGraph · Multi-Agent Systems</sub>

---

## Achievements

| Placement | Event | Host |
|---|---|---|
| **2nd Runner-Up** | TechnoGrad 3.0 | DJSCE Mumbai |
| **1st Runner-Up** | CO-Code 2.0 | DJSCE Mumbai |
| **Top 10** | Megathon 2025 | IIIT Hyderabad |
| **Top 13 Finalist** | Redact 2025 | SPIT Mumbai |
| **Finalist** | Odoo × Amalthea Hackathon | IIT Gandhinagar |
| **Top 40** of 200+ teams | DataHack 3.0 | DJSCE Mumbai |

Finalist at **8+ national hackathons** overall.

---

## Beyond Code

**Creatives Co-Committee Member** · DJS S4DS · `Sep 2025 – Apr 2026`
UI/UX, posters, and graphics for technical events and society initiatives.

**Technical Co-Committee Member** · DJSCE Trinity · `Aug 2025 – Jan 2026`
Ran technical events and contributed to the official fest website; organized hackathons and coding competitions end to end.

---

## Stats

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=darved2305&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=darved2305&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=darved2305&theme=tokyonight&hide_border=true" alt="Streak" />

</div>

---

<div align="center">

**Mumbai, India** · [darshanmved@gmail.com](mailto:darshanmved@gmail.com) · [darshanved.vercel.app](https://darshanved.vercel.app/)

</div>
