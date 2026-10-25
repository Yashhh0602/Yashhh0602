<div align="center">

```
██╗   ██╗ █████╗ ███████╗██╗  ██╗██╗   ██╗ █████╗ ██████╗ ██████╗ ██╗  ██╗ █████╗ ███╗   ██╗
╚██╗ ██╔╝██╔══██╗██╔════╝██║  ██║██║   ██║██╔══██╗██╔══██╗██╔══██╗██║  ██║██╔══██╗████╗  ██║
 ╚████╔╝ ███████║███████╗███████║██║   ██║███████║██████╔╝██║  ██║███████║███████║██╔██╗ ██║
  ╚██╔╝  ██╔══██║╚════██║██╔══██║╚██╗ ██╔╝██╔══██║██╔══██╗██║  ██║██╔══██║██╔══██║██║╚██╗██║
   ██║   ██║  ██║███████║██║  ██║ ╚████╔╝ ██║  ██║██║  ██║██████╔╝██║  ██║██║  ██║██║ ╚████║
   ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝
```

### Backend Engineer · Production AI Systems · Open to Full Time Roles

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-v2-phi-tan.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashvardhan-khanduja07/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vardhan.yash265@gmail.com)

</div>

---

## `$ whoami`

```yaml
name:        Yashvardhan Khanduja
role:        Backend engineer who builds and ships AI systems
education:   B.Tech CSE (Cyber Security), Manipal Institute of Technology, Bengaluru (Jan 2026)
location:    Bangalore, India
stack:       Python, Node.js, FastAPI, Express, PostgreSQL, AWS, Docker
experience:
  - Quantum & Systems Engineer Intern @ DRDO, Ministry of Defence
  - Cybersecurity Intern @ Academor
  - Freelance: Lead Management System for Biotech Client
achievements:
  - 🥇 1st place / 120 participants, University Crypto Hunt (cryptography CTF)
  - 🛡️ TryHackMe ADEPT rank, top 15% globally
  - ⚽ Vice Captain, University Football Team
status:      Open to full time backend and AI engineering roles
```

I build backends that hold up: multi tenant access control, paginated APIs over large datasets, multi agent LLM pipelines, and the AWS infrastructure to run them.

---

## `$ ls -la ./experience`

### 🔬 Quantum & Systems Engineer Intern, DRDO, Ministry of Defence
`Mar 2025 to Sep 2025 · Delhi`

- Built GPU accelerated quantum simulation pipelines with **CUDA-Q** on multi GPU systems, **40% throughput gain**
- Containerized the compute environment with **Docker**, cutting setup time by **60%**

### 🔐 Cybersecurity Intern, Academor
`Apr 2024 to Aug 2024 · Remote`

- Built network traffic analysis pipelines with **Scapy** and **Pandas** for anomaly detection
- Built ETL pipelines for security datasets and **Power BI** dashboards for monitoring

### 💼 Freelance Backend Engineer, Biotech Client
`Oct 2026 to present`

- Building a multi company lead management system solo, end to end: **Node.js, Express, PostgreSQL**
- Role based access across Admin, Team Leader and Employee, with leads, follow up tasks and reports modules

---

## `$ ls -la ./projects`

### 🤖 [Agentic Research Assistant](https://github.com/Yashhh0602/agentic-research-amd-scaffold)
> 4 agent RAG pipeline built for the AMD AI DevMaster Hackathon.

- Retrieval, planning, tool execution and synthesis agents with dependency aware concurrent scheduling
- **4.08x throughput, 1.17x latency** improvement over sequential execution, measured with reproducible benchmarks on AMD ROCm via vLLM
- Traced ungrounded outputs in about half of test runs to a model capability ceiling and fixed it with a separate, larger synthesis model

`Python` `FastAPI` `Next.js` `PostgreSQL` `pgvector` `vLLM` `Docker` `AMD ROCm`

---

### ⚡ [CodeVector](https://github.com/Yashhh0602/codevector) · [Live demo](https://codevector-2.onrender.com)
> FastAPI backend with cursor based pagination over a 200k+ row PostgreSQL dataset, with AWS infrastructure in Terraform.

- Composite index and opaque cursor tokens for stable, fast pagination
- Migrated from Render/Neon to **AWS ECS Fargate, RDS, ALB, IAM and CloudWatch**, all defined in **Terraform**
- Torn down after validation to avoid cost. Live demo runs on Render (first load may take ~30s)

`Python` `FastAPI` `PostgreSQL` `AWS` `Terraform` `Docker`

---

### 🏢 [Employee Management System](https://github.com/Yashhh0602/Employee-Management-System)
> HR backend where the hard parts are access control and data integrity.

- Field level RBAC that blocks salary tampering
- Self referencing org hierarchy with circular reporting prevention
- Both covered by **Jest** and **Supertest**, run in **GitHub Actions** CI against a live Postgres service container

`Node.js` `Express` `PostgreSQL` `Jest` `Supertest` `GitHub Actions` `Docker` `Kubernetes`

---

### 🧠 [MindVault](https://github.com/Yashhh0602/Minvault-AI)
> Self hosted AI knowledge base with semantic search, auto summarization and tagging.

- 5 Docker services: Next.js, FastAPI, PostgreSQL with pgvector, Redis, Ollama for local LLM inference

`Next.js` `FastAPI` `PostgreSQL` `pgvector` `Redis` `Ollama` `Docker Compose`

---

### 🥩 [NoFeeSwap MEV Suite](https://github.com/Yashhh0602/nofeeswap-mev-suite)
> Full stack Web3 DeFi app on the NoFeeSwap zero fee AMM, with on chain pool management and a live MEV sandwich bot.

- TypeScript bot watching the mempool over WebSocket, parsing pending calldata and executing front run/back run bundles with precise nonce and gas ordering
- Next.js frontend with wagmi/viem against a local Anvil chain

`Solidity` `TypeScript` `Next.js` `wagmi` `viem` `ethers.js` `Foundry` `Anvil`

---

### 🔒 [HashGuard](https://github.com/Yashhh0602/hashguard)
> SHA256 file integrity checker, plus a benchmark showing why SHA256 is wrong for passwords.

- About 1M SHA256 ops/sec vs about 2 bcrypt ops/sec, built after winning the Crypto Hunt to go deeper

`Python` `SHA256` `bcrypt`

---

### More

| Project | What it is | Stack |
|---|---|---|
| [AI Dungeon Master](https://github.com/Yashhh0602/AI-Dungeon-Master) | RPG engine where a local LLM narrates and returns structured state deltas, sub 2s responses | FastAPI, React, TypeScript, Ollama, SQLite |
| [Real Time Messaging Platform](https://github.com/Yashhh0602/Chat-app) | WebSocket messaging backend with JWT auth and RBAC | Node.js, Express, Socket.IO, MongoDB |
| [MERN Learning Platform](https://github.com/Yashhh0602/mern-learning-platform) | Video course platform with optimistic UI rollback and resume from timestamp | React, Node.js, Express, MongoDB, Docker |
| [BurnTrack](https://github.com/Yashhh0602/burntrack) · [Live](https://burntrack-phi.vercel.app/) | MET based calorie calculator with server side Claude API coaching tips | Next.js, Tailwind, Vercel |
| Autonomous Traffic Monitoring | Multi object detection and tracking for traffic scenes | YOLOv8, DeepSort, OpenCV, Python |
| [Shopify Custom Section](https://github.com/Yashhh0602/shopify-custom-sections) | Product grid with Quick View modal | Shopify Liquid, CSS, JS |

---

## `$ cat ./tech-stack.json`

```json
{
  "languages":    ["Python", "JavaScript", "TypeScript", "SQL", "Solidity"],
  "backend":      ["FastAPI", "Node.js", "Express", "Django", "Django REST Framework", "REST APIs", "Socket.IO"],
  "data":         ["PostgreSQL", "pgvector", "Redis", "MongoDB", "SQLite"],
  "ai_ml":        ["RAG", "Multi agent systems", "vLLM", "Ollama", "Claude API", "Prompt engineering", "AMD ROCm", "CUDA-Q", "YOLOv8"],
  "cloud_devops": ["AWS (ECS Fargate, RDS, ALB, IAM, CloudWatch)", "Terraform", "Docker", "Docker Compose", "Kubernetes", "GitHub Actions"],
  "frontend":     ["React", "Next.js", "Tailwind CSS"],
  "web3":         ["Solidity", "ethers.js", "wagmi", "viem", "Foundry", "Anvil"],
  "testing":      ["Jest", "Supertest"],
  "security":     ["Scapy", "Wireshark", "bcrypt", "CTF"]
}
```

---

## `$ github-stats --user Yashhh0602`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Yashhh0602&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&count_private=true)

</div>

---

## `$ contact --hire`

Looking for full time **backend** and **AI engineering** roles.

📬 **[vardhan.yash265@gmail.com](mailto:vardhan.yash265@gmail.com)** · **[LinkedIn](https://www.linkedin.com/in/yashvardhan-khanduja07/)** · **[Portfolio](https://portfolio-v2-phi-tan.vercel.app/)**
