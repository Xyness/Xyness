<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:0D1117&height=220&section=header&text=XYNESS&fontColor=58A6FF&fontSize=70&fontAlignY=33&desc=CS%20%E2%80%A2%20Big%20Data%20%E2%80%A2%20AI%20%E2%80%A2%20Security&descColor=8B949E&descSize=18&descAlignY=55&animation=fadeIn" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Building+production-grade+tools+that+solve+real+problems;End-to-end+delivery+%E2%80%94+from+architecture+to+deployment;Exploring+systems%2C+understanding+what's+underneath)](https://git.io/typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-xyness.github.io-58A6FF?style=flat-square&logo=safari&logoColor=white)](https://xyness.github.io/)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/Contact-xyness@icloud.com-58A6FF?style=flat-square&logo=maildotru&logoColor=white)](mailto:xyness@icloud.com)

**French** 🇫🇷 &nbsp; **English** 🇬🇧 &nbsp; **Spanish** 🇪🇸

</div>

<br/>

> **CS, Big Data & AI student** building production-grade software end to end. I design and ship solutions across **artificial intelligence**, **big data engineering**, **cybersecurity**, and **full-stack development** — with security as a first-class concern. Every project ships with Docker. I always want to understand what's underneath.

---

## Featured Projects

<table>
  <tr><td>
    <h3><a href="https://github.com/Xyness/AlphaWatch">AlphaWatch</a> &nbsp;·&nbsp; AI Market Intelligence Agent</h3>
    <p>Autonomous AI agent that monitors financial markets, generates multi-source analysis reports, and detects market sentiment shifts in real time.</p>
    <p><b>Architecture:</b> 5-node LangGraph pipeline — Planner → Search → Reader → Analyst → Writer. Autonomous scheduling via APScheduler. Full mock mode for zero-config demos.</p>
    <p>
      <code>Next.js</code> <code>React</code> <code>TypeScript</code> <code>Tailwind CSS</code> <code>Python</code> <code>FastAPI</code> <code>LangGraph</code> <code>LangChain</code> <code>OpenAI</code> <code>PostgreSQL</code> <code>Docker</code>
    </p>
  </td></tr>
  <tr><td>
    <h3><a href="https://github.com/Xyness/Sentinel">Sentinel</a> &nbsp;·&nbsp; Big Data Anomaly Detection Platform</h3>
    <p>Real-time Big Data platform analyzing cryptocurrency market streams to automatically detect suspicious behavior using unsupervised machine learning.</p>
    <p><b>Pipeline:</b> Data Generator → Kafka → Spark Structured Streaming (Java) → Parquet → Isolation Forest ML → FastAPI → Streamlit dashboard. Dual mode: simulated data with injected anomalies + live Binance WebSocket feed.</p>
    <p>
      <code>Python</code> <code>Java</code> <code>Apache Spark</code> <code>Kafka</code> <code>FastAPI</code> <code>Scikit-learn</code> <code>Streamlit</code> <code>Plotly</code> <code>Parquet</code> <code>Docker</code>
    </p>
  </td></tr>
  <tr><td>
    <h3><a href="https://github.com/Xyness/Phantom">Phantom</a> &nbsp;·&nbsp; Security Reconnaissance Framework</h3>
    <p>Full-stack attack surface analysis framework combining a Rust async port scanner, Python recon modules, and an interactive Next.js risk dashboard.</p>
    <p><b>Capabilities:</b> Async TCP scanning + banner grabbing, DNS recon &amp; zone transfer detection, TLS certificate analysis, HTTP security header scoring, OSINT (WHOIS, ASN, certificate transparency), CVE matching, weighted risk scoring (0–100), HTML-to-PDF report generation. Authorization-gated by design.</p>
    <p>
      <code>Rust</code> <code>Tokio</code> <code>Python</code> <code>FastAPI</code> <code>TypeScript</code> <code>Next.js</code> <code>Tailwind CSS</code> <code>PostgreSQL</code> <code>SQLAlchemy</code> <code>Docker</code>
    </p>
  </td></tr>
  <tr><td>
    <h3><a href="https://github.com/Xyness/Archer">Archer</a> &nbsp;·&nbsp; Real-Time Face Recognition System</h3>
    <p>Face recognition system with a sci-fi HUD overlay — detects and identifies faces from a live webcam feed in real time with a futuristic canvas-rendered interface.</p>
    <p><b>How it works:</b> Browser captures frames → FastAPI processes via InsightFace (SCRFD detection + ArcFace 512-dim embeddings) → cosine similarity matching against stored identities → HUD overlay rendered on canvas. Multi-photo support per person, configurable threshold.</p>
    <p>
      <code>Python</code> <code>FastAPI</code> <code>InsightFace</code> <code>ArcFace</code> <code>ONNX Runtime</code> <code>OpenCV</code> <code>SQLite</code> <code>JavaScript</code> <code>Canvas API</code>
    </p>
  </td></tr>
  <tr><td>
    <h3><a href="https://github.com/Xyness/GitPulse">GitPulse</a> &nbsp;·&nbsp; GitHub Activity Visualizer &nbsp; <a href="https://git-pulse-virid.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-58A6FF?style=flat-square&logo=vercel&logoColor=white" alt="Live Demo"/></a></h3>
    <p>Interactive GitHub profile visualization tool featuring constellation graphs (repos as a star map), animated contribution heatmaps, language timeline streamgraphs, GitHub Wrapped, compare mode, and embeddable widgets. Dynamic OG image generation.</p>
    <p>
      <code>TypeScript</code> <code>Next.js</code> <code>Tailwind CSS</code> <code>shadcn/ui</code> <code>D3.js</code> <code>Framer Motion</code> <code>GitHub GraphQL API</code> <code>Vercel</code>
    </p>
  </td></tr>
  <tr><td>
    <h3><a href="https://github.com/Xyness/PaperChat">PaperChat</a> &nbsp;·&nbsp; RAG PDF Chatbot</h3>
    <p>RAG-powered chatbot that answers questions from uploaded PDFs using semantic search and LLMs. Supports both cloud and local inference.</p>
    <p><b>Features:</b> ChromaDB vector store, automatic chunking with deduplication, source references with page numbers, conversation history. Dual LLM support — OpenAI (GPT-4o-mini) or Ollama (Llama 3) for fully local usage.</p>
    <p>
      <code>Python</code> <code>FastAPI</code> <code>LangChain</code> <code>ChromaDB</code> <code>OpenAI</code> <code>Ollama</code> <code>Streamlit</code> <code>Docker</code>
    </p>
  </td></tr>
  <tr><td>
    <h3><a href="https://github.com/Xyness/SimpleClaimSystem">SimpleClaimSystem</a> &nbsp;·&nbsp; Open-Source Minecraft Plugin &nbsp; <img src="https://img.shields.io/github/stars/Xyness/SimpleClaimSystem?style=flat-square&color=58A6FF" alt="Stars"/> <img src="https://img.shields.io/github/forks/Xyness/SimpleClaimSystem?style=flat-square&color=8B949E" alt="Forks"/></h3>
    <p>Chunk-based territory protection plugin for Minecraft servers. Active community with 30+ stars, listed on SpigotMC, complete Gitbook wiki, and Discord support server. Compatible with Paper, Folia, Purpur, and Spigot (1.18+).</p>
    <p>
      <code>Java</code> <code>PaperMC</code> <code>Folia</code> <code>Spigot</code> <code>PlaceholderAPI</code> <code>Vault</code> <code>Dynmap</code> <code>Bluemap</code>
    </p>
  </td></tr>
</table>

<p align="right"><a href="https://github.com/Xyness?tab=repositories"><b>Browse all repositories →</b></a></p>

---

## Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)

**Data & AI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**DevOps & Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Security**

![Application Security](https://img.shields.io/badge/Application_Security-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)
![Server Auditing](https://img.shields.io/badge/Server_Auditing-7B42BC?style=flat-square&logo=vault&logoColor=white)

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Xyness&show_icons=true&bg_color=0D1117&border_color=161B22&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF" height="170"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Xyness&layout=compact&bg_color=0D1117&border_color=161B22&title_color=58A6FF&text_color=C9D1D9" height="170"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Xyness&background=0D1117&border=161B22&stroke=161B22&ring=58A6FF&fire=58A6FF&currStreakNum=C9D1D9&sideNums=C9D1D9&currStreakLabel=58A6FF&sideLabels=58A6FF&dates=8B949E"/>

</div>

---

<div align="center">

<br/>

**Open to interesting projects & collaborations**

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-xyness.github.io-58A6FF?style=for-the-badge&logo=safari&logoColor=white)](https://xyness.github.io/)
&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/Email-xyness@icloud.com-58A6FF?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:xyness@icloud.com)

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=Xyness&color=58A6FF&style=flat-square&label=Profile+Views)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:0D1117&height=100&section=footer" width="100%"/>

</div>
