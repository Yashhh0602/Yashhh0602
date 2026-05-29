<div align="center">

```
██╗   ██╗ █████╗ ███████╗██╗  ██╗██╗   ██╗ █████╗ ██████╗ ██████╗ ██╗  ██╗ █████╗ ███╗   ██╗
╚██╗ ██╔╝██╔══██╗██╔════╝██║  ██║██║   ██║██╔══██╗██╔══██╗██╔══██╗██║  ██║██╔══██╗████╗  ██║
 ╚████╔╝ ███████║███████╗███████║██║   ██║███████║██████╔╝██║  ██║███████║███████║██╔██╗ ██║
  ╚██╔╝  ██╔══██║╚════██║██╔══██║╚██╗ ██╔╝██╔══██║██╔══██╗██║  ██║██╔══██║██╔══██║██║╚██╗██║
   ██║   ██║  ██║███████║██║  ██║ ╚████╔╝ ██║  ██║██║  ██║██████╔╝██║  ██║██║  ██║██║ ╚████║
   ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝
```

### Full-Stack Engineer · AI/ML · Full Stack Development · Open to Full-Time Roles

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-v2-phi-tan.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashvardhan-khanduja07/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yashhh0602)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vardhan.yash265@gmail.com)

</div>

---

## `$ whoami`

```yaml
name:         Yashvardhan Khanduja
education:    B.Tech CSE — Manipal Institute of Technology, Bengaluru (Jan 2026)
location:     Bangalore, India
experience:
  - Quantum & Systems Engineer Intern @ DRDO, Ministry of Defence
  - Cybersecurity Intern @ Academor
focus:
  - Full-Stack Engineering (React, Next.js, Node.js, FastAPI)
  - AI / ML & GenAI (LLMs, local inference, computer vision, prompt engineering)
  - Web3 & DeFi (Solidity, MEV, AMM protocols, wagmi/viem)
  - Distributed Systems & Real-Time Data Pipelines
status:       Open to full-time roles
achievements:
  - 🥇 1st place / 120 participants — University Crypto Hunt
  - 🏆 8th place / 45 teams — M# Hackathon
  - ⚽ Vice Captain, University Football Team
```

I build across the full stack — distributed backends, real-time pipelines, on-chain DeFi protocols, and AI-powered applications. I enjoy the intersection of low-level engineering and high-impact product thinking.

---

## `$ ls -la ./experience`

### 🔬 Quantum & Systems Engineer Intern — DRDO, Ministry of Defence
`Apr 2025 – Sep 2025 · Delhi`

- Engineered GPU-accelerated quantum simulation pipelines using **CUDA-Q**, executing 8–12 qubit circuits across multi-GPU architectures — **40% efficiency gain**
- Containerized compute environments with **Docker**, enabling reproducible deployments across 12+ heterogeneous systems
- Designed distributed **Python** workflows handling 500+ parallel executions — **35% latency reduction**

### 🔐 Cybersecurity Intern — Academor
`Apr 2024 – Aug 2024 · Remote`

- Built network traffic analysis pipelines using **Scapy + Pandas + Wireshark**, processing 2M+ packets/session for anomaly detection
- Automated **OWASP**-aligned vulnerability scanning across 20+ apps, identifying 35+ critical issues
- Built **Power BI** dashboards for real-time security monitoring and insights

---

## `$ ls -la ./projects`

### 🥩 [NoFeeSwap MEV Suite](https://github.com/Yashhh0602/nofeeswap-mev-suite)
> Full-stack Web3 DeFi app on the NoFeeSwap zero-fee AMM with on-chain pool management and a live MEV sandwich attack bot.

- Next.js frontend with wagmi/viem for real-time on-chain interactions against a local Anvil blockchain
- TypeScript MEV bot monitoring the Ethereum mempool — executes front-run/back-run bundles with precise nonce and gas ordering
- Mempool subscription via WebSocket, parsing pending calldata to identify profitable sandwich opportunities

`Solidity` `TypeScript` `Next.js` `wagmi` `viem` `ethers.js` `Foundry` `Anvil`

---

### 🎲 [AI Dungeon Master](https://github.com/Yashhh0602/AI-Dungeon-Master)
> Full-stack AI RPG where a locally-hosted LLM acts as a real-time Dungeon Master — dynamic narratives, character stats, and persistent game state.

- FastAPI backend with SQLite persistence for character stats, inventory, XP, combat state, and story history
- Custom prompt system instructing the LLM to narrate in D&D style and return structured state deltas
- React + TypeScript frontend with real-time chat, animated HP/XP bars, character sheet sidebar, and combat panel
- Runs **entirely locally** via Ollama — zero API costs, zero cloud dependency

`Python` `FastAPI` `React` `TypeScript` `Ollama` `qwen2.5` `SQLite` `GenAI`

---

## `$ ls -la ./projects`

### 🥩 [Mini-Lms](https://github.com/Yashhh0602/mini-lms)
> A full-stack Learning Management System built with the MERN stack. Users can browse video modules, track completion progress, and resume videos from where they left off.

- Optimistic UI with rollback — UI updates instantly on "Mark as Complete", reverts silently if API fails. No loading spinners, smooth UX.
- Video resume state — exact timestamp saved on pause, restored when you revisit the module. Both bonus features implemented.
- Clean separation of concerns — controllers, routes, models all separate. Context API for shared state, 3 MongoDB collections with proper relationships.

`React` `Vite` `Node.js` `Express.js` `Context APi` `MongoDB Atlas` `Docker` `Docker Compose`

---

### 💬 Distributed Real-Time Messaging Platform
> Scalable backend supporting 100+ concurrent users with sub-100ms latency, real-time analytics, and role-based access control.

- REST APIs + WebSocket communication achieving **sub-100ms latency** for 100+ concurrent users
- JWT-based auth and RBAC for secure channels; DB optimized with indexing and connection pooling — **99.9% uptime**
- Async data pipelines via **Apache Spark** for engagement analytics dashboards

`Node.js` `Express` `MongoDB` `Socket.IO` `Apache Spark` `JWT`

---

### 🚗 Autonomous Traffic Monitoring Dashboard
> Real-time object detection and tracking with 95% accuracy across multi-object traffic scenarios.

- Detection pipeline using **YOLOv8 + DeepSort** — 95% accuracy across multi-object scenarios
- Processed 10,000+ frames; generated live KPIs: vehicle density, directional flow, and forecasting insights

`YOLOv8` `DeepSort` `OpenCV` `Python`

---

## `$ cat ./tech-stack.json`

```json
{
  "languages":      ["Python", "TypeScript", "JavaScript", "Solidity", "Java", "C++"],
  "frontend":       ["React", "Next.js", "HTML", "CSS", "wagmi", "viem"],
  "backend":        ["Node.js", "Express", "FastAPI", "Django", "Flask", "GraphQL", "WebSockets"],
  "web3":           ["Solidity", "ethers.js", "wagmi", "viem", "Foundry", "Hardhat", "MEV", "DeFi"],
  "ai_ml":          ["Ollama", "LLM integration", "Prompt Engineering", "YOLOv8", "OpenCV", "Pandas", "NumPy"],
  "data":           ["Apache Spark", "PostgreSQL", "MySQL", "MongoDB", "Redis", "Power BI"],
  "cloud_devops":   ["AWS", "GCP", "Azure", "Docker", "Kubernetes", "CI/CD", "GitHub Actions", "CUDA-Q"],
  "cybersecurity":  ["Wireshark", "Scapy", "Kali Linux", "OWASP", "Snort", "Metasploit"]
}
```

---

## `$ github-stats --user Yashhh0602`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Yashhh0602&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Yashhh0602&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8)

</div>

---

## `$ contact --hire`

I'm actively looking for full-time roles in **full-stack engineering**, **AI/ML**, or **Web3 development**.

📬 **[vardhan.yash265@gmail.com](mailto:vardhan.yash265@gmail.com)** · **[LinkedIn](https://www.linkedin.com/in/yashvardhan-khanduja07/)** · **[Portfolio](https://portfolio-v2-phi-tan.vercel.app/)** · **[+91 6230680703](tel:+916230680703)**

---

<div align="center">
<sub>Built with terminal aesthetic and a lot of coffee ☕</sub>
</div>
