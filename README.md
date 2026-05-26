<h1 align="center">Hi, I'm Taha Zaidi</h1>

<p align="center">
  <b>AI Engineer</b> · Building multi-agent systems, RAG pipelines, and on-chain primitives<br/>
  CS @ FAST NUCES Karachi · Class of 2027 · Rector's Gold Medal · 3× Dean's List
</p>

<p align="center">
  <a href="https://tahazaidi.me"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-tahazaidi.me-0A0A0A?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://linkedin.com/in/taha-zaidii"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:tahazaidi2004@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Karachi-Pakistan-0A0A0A?style=for-the-badge&logo=googlemaps&logoColor=white">
</p>

---

### About

I build at the intersection of **agentic AI** and **decentralized systems** — most of my recent work sits in multi-agent orchestration, RAG, and full-stack production deploys, with active exploration of on-chain primitives and Web3 infrastructure through hackathon sprints.

Outside engineering: led 40+ person marketing teams, closed **PKR 1 Crore+** in B2B sponsorships for Pakistan's largest student tech festival (a 25-year revenue record), designed brand systems for events with 2,500+ attendees, and ran a freelance creative book of 50+ paid projects. The engineering + product + GTM combination is the bet.

> **Currently focused on:** multi-agent architectures · LLM orchestration · RAG over hybrid stores · agent ↔ chain interop · production deploys that don't break at 3 AM

---

### Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/taha-zaidii/baymax.app">Baymax.app</a></h4>
      <p><b>Multi-Agent AI Career-Coaching Platform</b></p>
      <p>Hierarchical multi-agent system with 5 specialized agents — Resume Analyzer, Voice Interview Coach, Job Scout, Roadmap Planner, Memory — orchestrated over LLaMA 3.3 70B via Groq. RAG over ChromaDB for resume↔JD semantic matching, real-time Whisper STT voice interviews, and a CSP-based 90-day roadmap planner (AC-3 + backtracking with MRV/LCV/forward-checking). Shipped to production.</p>
      <p><code>CrewAI</code> <code>LangChain</code> <code>LangGraph</code> <code>FastAPI</code> <code>Next.js</code> <code>ChromaDB</code> <code>Groq</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/taha-zaidii/Ustaad-E-Mazdoor">Ustaad (E-Mazdoor)</a></h4>
      <p><b>AI-Powered Recruitment & Service Marketplace</b></p>
      <p>Full-stack platform addressing Pakistan's $80B+ informal labor market. Hybrid recommender (TF-IDF + cosine for content-based, matrix factorization for collaborative filtering) benchmarked on Hit-Rate@5 / MRR. Backend tuned with Redis cache-aside + PostgreSQL GIN/B-tree indexes — <b>p95 latency from ~800ms to under 200ms</b>. 11 design patterns implemented across the codebase.</p>
      <p><code>Next.js 16</code> <code>React 19</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>Redis</code> <code>scikit-learn</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/taha-zaidii/Vyse">Vyse</a></h4>
      <p><b>Real-Time AI Workplace Safety Intelligence</b></p>
      <p>Scalable safety-monitoring platform — YOLOv8 detection + MediaPipe facial-landmark analysis (eye-aspect-ratio drowsiness detection) over live camera feeds. Modular 4-agent architecture (Vision, Risk, Alert, Analytics) with event-driven decision engine, ByteTrack persistent identities, YAML temporal rule engine, and async video-inference pipeline. Postgres + TimescaleDB persistence; ONNX/TensorRT export path for Jetson edge deploy.</p>
      <p><code>YOLOv8</code> <code>MediaPipe</code> <code>ByteTrack</code> <code>FastAPI</code> <code>TimescaleDB</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/taha-zaidii/RetroLang">RetroLang</a></h4>
      <p><b>Hand-Built Compiler for a Retro-Arcade DSL</b></p>
      <p>Declarative DSL where a single <code>.retro</code> file compiles through six classical compiler phases (DFA lexer → recursive-descent parser → semantic analyzer → dual IR → optimizer → codegen) into a playable Tetris or Snake game. Includes Vercel-deployed browser runtime that mirrors the compiled output byte-for-byte. 16-test suite, full language manual, formal CFG.</p>
      <p><code>Python</code> <code>Compiler Construction</code> <code>DSL</code> <code>pygame</code> <code>Vercel</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/taha-zaidii/AeroWatch">AeroWatch</a></h4>
      <p><b>UAV Weather Intelligence Dashboard</b></p>
      <p>Real-time weather + telemetry dashboard purpose-built for drone operators — live battery/altitude/airspeed, interactive tactical map with geofence overlay and weather cells, wind/gust alerts, control panel with guarded RTH and emergency landing, plus a live Fitts' law and time-on-task HCI benchmark for operator-interface evaluation.</p>
      <p><code>Vite</code> <code>React 18</code> <code>TypeScript</code> <code>Custom Tile Renderer</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/taha-zaidii/ShopSense">ShopSense</a></h4>
      <p><b>Neural Collaborative Filtering Recommender</b></p>
      <p>Personalized product recommender combining Generalized Matrix Factorization (latent factors) and a Multi-Layer Perceptron (non-linear user↔item interactions) under the NeuMF architecture from He et al. (2017). Evaluated on Precision@K, Recall@K, NDCG, plus regression metrics (MAE/MSE/RMSE) against an Amazon Electronics dataset.</p>
      <p><code>TensorFlow</code> <code>NeuMF</code> <code>Flask</code> <code>Jupyter</code></p>
    </td>
  </tr>
</table>

---

### Tech Stack

**Languages**
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white">
<img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
</p>

**AI · Agentic Systems · ML**
<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square">
<img src="https://img.shields.io/badge/CrewAI-FF6B35?style=flat-square">
<img src="https://img.shields.io/badge/LlamaIndex-4B0082?style=flat-square">
<img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
<img src="https://img.shields.io/badge/Groq-F55036?style=flat-square">
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square">
<img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square">
</p>

**Blockchain · Web3**
<p>
<img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white">
<img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white">
<img src="https://img.shields.io/badge/Hardhat-FFF100?style=flat-square">
<img src="https://img.shields.io/badge/Foundry-000000?style=flat-square">
<img src="https://img.shields.io/badge/ethers.js-2535A0?style=flat-square">
<img src="https://img.shields.io/badge/IPFS-65C2CB?style=flat-square&logo=ipfs&logoColor=white">
<img src="https://img.shields.io/badge/Web3-F16822?style=flat-square&logo=web3.js&logoColor=white">
</p>

**Web · Backend**
<p>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
</p>

**Data · Infrastructure**
<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
<img src="https://img.shields.io/badge/pgvector-336791?style=flat-square">
<img src="https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square">
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white">
<img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
</p>

**Design · Product**
<p>
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white">
<img src="https://img.shields.io/badge/After%20Effects-9999FF?style=flat-square&logo=adobeaftereffects&logoColor=black">
<img src="https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white">
<img src="https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white">
</p>

---

### Hackathons & Sprints

- **AI Mustaqbil 2.0 — Global Youth Agentic AI Hackathon** (NASTP Karachi, 2026) — 24-hour multi-agent AI sprint
- **Wirefluid's "Entangled" — Pakistan's Biggest Blockchain Hackathon** — end-to-end on-chain applications under sprint conditions
- Multiple other AI / blockchain hackathons — full-stack agentic systems and on-chain primitives

---

### Beyond the code

- **Director, Marketing & Brand Partnerships — PROCOM '26** (FAST NUCES). Led a 40+ person marketing team for Pakistan's largest student tech festival. Closed 50+ corporate sponsorships totaling **PKR 1 Crore+** — an all-time revenue record in PROCOM's 25-year history.
- **Executive Head, Branding & Design — ACM NUCES.** Led complete rebrand and on-ground identity for Developers Day 2025 (2,500+ attendees, 30+ companies).
- **Tech Consultant — Bytes Platform (Denton, TX).** Shipped 10+ client solutions for US-based businesses including veteran-owned SMBs.
- **Director, Operations — FAST Creators Fest.** Orchestrated FAST's first creative festival (1,000+ attendees, 25+ vendors). Closed Sony as title sponsor.
- **President — Nixor Student Government (2023).** Elected student body head.
- **Freelance creative since 2022** — 50+ paid projects, 5-star ratings, clients across Pakistan / US / Australia.

---

### Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=taha-zaidii&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=tokyonight">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=taha-zaidii&layout=compact&hide_border=true&langs_count=8&theme=tokyonight">
</p>

---

<p align="center">
  <i>Open to: AI engineering roles · agentic systems research · Web3 / on-chain builds · founder collaborations · interesting freelance.</i><br/>
  <a href="mailto:tahazaidi2004@gmail.com"><b>Let's talk →</b></a>
</p>
