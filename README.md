<h1 align="left">Hi 👋, I'm Jose</h1>
<h3 align="left"><strong>A Mexican Electronics Engineer and Software Engineer (Backend, Cloud Infrastructure & AI Agents) based in a rainy and techie city, Seattle, WA.</strong><br>
I bring the heat from a rainy city, building smart solutions from the hardware up to the cloud.
</h3>

I am an innovator who loves a good challenge, whether building innovative tech or tracking down a rare Pokémon card. My passion is combining cloud infrastructure, AI agents, and hardware to build smart and efficient systems that get the job done faster 😎🤖🦾.

- 🔭 I'm currently exploring new opportunities as a **Software Engineer** focused on backend, cloud infrastructure, or AI agents. I have nearly 4 years of industry experience across Mexico and the United States:
  - **Microsoft** (2022–2025): built Python Hardware-in-the-Loop validation pipelines for Azure servers (~10,000 machines), containerized telemetry services, and Azure CI/CD automation that cut failure rates from ~30% to ~10%.
  - **Globant** (2021–2022): designed middleware and REST APIs for 8 client projects across AWS, GCP, and Azure, including a FastAPI booking app serving 1,000–2,000 daily users.
- 🤖 I'm currently building **LLM agents and self-hosted model serving**, plus reinforcement learning experiments (DQN, A2C, PPO).
- 🌱 I'm also taking an ***iOS App Development course***.
- 😄 Interests: learning new things (everything! Including Music Theory and Cooking).
- 😄 Pronouns: He/Him 💁🏻‍♂️
- ⚡ Fun facts:
   - I love matcha.
   - I am also a Bachata and Salsa dancer! 🕺🏻
   - I love to spoil my Wife (and poke her 👀)

<h3 align="left">Let's Chat!</h3>
<p align="left">
Email: joslo2345contact@gmail.com<br>
LinkedIn: <a href="https://www.linkedin.com/in/jose-lopez23/">Jose Lopez</a><br>
Tips: <a href="https://ko-fi.com/joslo2345">Buy me a coffee on Ko-fi ☕</a>
</p>

<h1>🚀 Featured Projects</h1>

### [GPU Fleet Incident Assistant](https://github.com/joslo2345/incident-assistant)
An AI agent that detects GPU faults in fleet telemetry, diagnoses each one with cited repair runbooks, and holds risky repairs for human approval.
- Streaming telemetry pipeline (FastAPI, Kafka, TimescaleDB) replaying a real Alibaba GPU cluster trace across 64 GPUs. The anomaly detector catches 99% of injected faults at 100% precision.
- Tool-calling LLM agent (Qwen3 via Ollama, MCP) with hybrid RAG search (pgvector + PostgreSQL full-text). A held-out eval harness raised diagnosis accuracy from 76% to 88% and fix accuracy from 60% to 92%, at $0 model cost per incident.
- React/TypeScript web app and Slack bot with role-based approvals and an audit log, deployed with Docker, Helm on Kubernetes, Terraform (Azure AKS), and GitHub Actions CI with security scanning.

### [Self-Hosted LLM Serving & Cost Analysis](https://github.com/joslo2345/self-hosted-model)
- Served an open LLM with vLLM on Kubernetes (Helm, Terraform). Switching to it was config-only, and it got 23/25 diagnoses right.
- Autoscaled on queue depth (KEDA, Prometheus, Grafana). The hosted fallback finished all 4 of 4 kill tests.
- Load-tested with replayed agent traffic: prefix caching doubled throughput, and break-even vs. a hosted API is ~170 incidents/day.

<h1>🛠️ Technologies and Tools</h1>

<h2>Languages</h2>

![](https://img.shields.io/badge/Languages-Python,_Go,_TypeScript,_JavaScript,_C++,_Rust,_SQL,_Bash-blue)<br>

<h2>Backend & Frontend</h2>

![](https://img.shields.io/badge/Backend-FastAPI,_Django,_Flask,_Node.js,_Express-blue)<br>
![](https://img.shields.io/badge/Frontend-React,_Next.js,_Tailwind_CSS-blue)<br>

<h2>AI & ML</h2>

![](https://img.shields.io/badge/LLM-Agents,_RAG,_MCP,_LLM_Evaluation-blue)<br>
![](https://img.shields.io/badge/Serving_%26_Frameworks-Ollama,_vLLM,_PyTorch-blue)<br>
![](https://img.shields.io/badge/Reinforcement_Learning-DQN,_A2C,_PPO-blue)<br>
![](https://img.shields.io/badge/AI_Dev_Tools-Claude_Code,_Cursor,_Copilot-blue)<br>

<h2>Cloud & DevOps</h2>

![](https://img.shields.io/badge/Cloud-Azure,_AWS,_Google_Cloud-blue)<br>
![](https://img.shields.io/badge/Containers-Docker,_Kubernetes,_Helm,_KEDA-blue)<br>
![](https://img.shields.io/badge/IaC_%26_CI%2FCD-Terraform,_GitHub_Actions,_Azure_Pipelines-blue)<br>
![](https://img.shields.io/badge/Observability-Prometheus,_Grafana-blue)<br>

<h2>Data</h2>

![](https://img.shields.io/badge/Databases-PostgreSQL,_TimescaleDB,_pgvector,_MySQL,_MongoDB,_Azure_Cosmos_DB-blue)<br>
![](https://img.shields.io/badge/Streaming_%26_Analytics-Kafka,_Pandas,_NumPy,_Power_BI-blue)<br>

<h2>Hardware & Systems</h2>

![](https://img.shields.io/badge/Validation-HITL,_FPGA,_GPU,_CPU,_BMC_Qualification,_Server_Telemetry-blue)<br>
![](https://img.shields.io/badge/Graphics-OpenGL,_SDL3-blue)<br>
![](https://img.shields.io/badge/Others-Arduino,_MATLAB,_OpenCV-blue)<br>

<h2>Tools & OS</h2>

![](https://img.shields.io/badge/Tools-Git,_Shell_Scripting,_Postman,_Selenium,_Jest-blue)<br>
![](https://img.shields.io/badge/Operating_Systems-Linux,_macOS,_Windows-blue)<br>
