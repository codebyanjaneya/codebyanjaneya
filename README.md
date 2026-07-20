<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e14,50:0d7377,100:14ffec&height=200&section=header&text=Anjaneya%20Tiwari&fontColor=14ffec&fontSize=52&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Developer%20%C2%B7%20AI%20Engineer%20%C2%B7%20Cybersecurity&descSize=18&descAlignY=58&descColor=8b96a8" alt="Anjaneya Tiwari" />

[![Portfolio](https://img.shields.io/badge/Portfolio-codebyanjaneya.github.io-14ffec?style=flat-square&logo=githubpages&logoColor=black&labelColor=0a0e14)](https://codebyanjaneya.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-anjaneya--tiwari-0a66c2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0a0e14)](https://linkedin.com/in/anjaneya-tiwari)
[![Email](https://img.shields.io/badge/Email-anjaneyatiwarii@gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0a0e14)](mailto:anjaneyatiwarii@gmail.com)
[![Location](https://img.shields.io/badge/Delhi-India-8b96a8?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0a0e14)](#)

</div>

```bash
$ whoami
> Anjaneya Tiwari  —  building resilient backends, intelligent agents, and secure systems.

$ cat ~/.focus
> Backend & AI Systems · Distributed concurrency · LLM-powered automation · Cybersecurity
```

---

## > Currently Building

<div align="center">

[![Now Building](https://img.shields.io/badge/⚡_NOW_BUILDING-H.E.R.C.S-14ffec?style=for-the-badge&labelColor=0a0e14)](https://github.com/codebyanjaneya)
[![Status](https://img.shields.io/badge/STATUS-ACTIVE_DEVELOPMENT-0d7377?style=for-the-badge&labelColor=0a0e14)](https://github.com/codebyanjaneya)

</div>

**H.E.R.C.S** - *a fully-local, JARVIS-style AI voice assistant living on the desktop.*

Clap twice - or say **"wake up Hercs"** — and it wakes, listens, thinks and talks back in a **cloned voice**, while a cinematic holographic HUD pulses in sync with every state. LLM tool-calling lets it actually *run* the machine: launching apps, controlling volume, taking screenshots, reading system vitals. Speech-to-text and voice cloning run 100% offline on-device.

```bash
$ hercs --pipeline
> wake(clap|voice) ──▶ whisper.stt ──▶ llama-3.3-70b(tools) ──▶ xtts-v2.cloned_voice
> hud.state: idle → listening → processing → speaking → success   # live holographic ring-core
```

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Whisper](https://img.shields.io/badge/faster--whisper_STT-412991?style=flat-square&logo=openai&logoColor=white)
![Groq Llama 3.3](https://img.shields.io/badge/Groq_Llama_3.3-F55036?style=flat-square&logo=meta&logoColor=white)
![XTTS-v2](https://img.shields.io/badge/Coqui_XTTS--v2_Voice_Clone-0d7377?style=flat-square&logo=audiomack&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Canvas HUD](https://img.shields.io/badge/Holographic_HUD-Canvas_2D-E34F26?style=flat-square&logo=html5&logoColor=white)
![Tool Calling](https://img.shields.io/badge/LLM_Tool_Calling-desktop_automation-14ffec?style=flat-square&logo=windowsterminal&logoColor=black&labelColor=0a0e14)

---

## > Experience

**Software Engineer Intern · Full-Stack Developer** - *Gleska Private Limited*  `Jul 2026 – Present` | New Delhi · Hybrid
- Building and maintaining backend & frontend modules for **Business MALL** across its product pillars — InstantHire, DPR-to-BIM, Financial Management, and the Autonomous Software Lifecycle platform.
- Shipping clean, well-documented, testable features while taking part in code reviews, sprint planning, and daily stand-ups.
- Collaborating with product and design teams to translate requirements into working software across development and staging environments.

**Backend & AI Systems Intern** - *Telogo Communications Ltd*  `Sep 2025 – Mar 2026` | Noida
- Engineered an IVR system and async worker pools for high-concurrency telephony workloads.
- Designed and shipped **LoadPulse**, a real-time concurrency & observability platform.

**Software Development Intern** - *Motivus Innovation Pvt. Ltd.*  `Feb 2025 – Jul 2025` | Noida

- Developed and enhanced software modules for AI-powered sustainability and energy management platforms focused on ESG reporting and renewable energy solutions.
- Built and integrated REST APIs, database-driven features, and user-facing components across multiple products improving platform functionality.
- Researched and evaluated AI and ML applications for energy analytics, carbon management, and sustainability monitoring.
- Optimized application performance and resolved software issues, contributing to improved system reliability and user experience.

---

## > Projects

### 1. LoadPulse, Real-time Concurrency & Observability Platform
Architected an async backend simulating high-concurrency request handling with FastAPI worker pools and token-bucket rate limiting. Benchmarked at 1000+ concurrent sessions with graceful degradation. Live observability dashboard streams p50/p95/p99 latency, queue depth, and worker utilization over WebSockets every 500ms. Deployed on AWS EC2 with NGINX reverse proxy and SSL.

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-loadpulse--dashboard.vercel.app-brightgreen?style=flat-square&logo=vercel)](https://loadpulse-dashboard.vercel.app) | [GitHub](https://github.com/codebyanjaneya/loadpulse)

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi) ![asyncio](https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react) ![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=flat-square) ![WebSockets](https://img.shields.io/badge/WebSockets-black?style=flat-square) ![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonaws)

### 2. AutoApply Bot, Recruitment Automation SaaS
A multi-tenant Telegram bot that automates the full job-hunt loop: parsing resumes, matching candidates to openings with Groq Llama 4, and drafting personalized recruiter outreach. n8n workflows orchestrate scraping and timed follow-up sequences, while Razorpay handles tiered subscription billing per tenant. Each user's data and daily quotas are isolated in PostgreSQL, and the bot runs around the clock on AWS EC2.

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-autoapply--landing--sand.vercel.app-brightgreen?style=flat-square&logo=vercel)](https://autoapply-landing-sand.vercel.app/)

![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Groq Llama 4](https://img.shields.io/badge/Groq_Llama_4-F55036?style=flat-square&logo=meta&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)

### 3. AgentForge, Multi-Agent AI Operating System
A simulated company run by 7 autonomous LLM agents (CEO, Sales, Marketing, and others) that delegate tasks and message each other through a Redis-backed event bus. A FastAPI backend coordinates agent state and task queues, while a Next.js digital-twin dashboard visualizes decisions and inter-agent conversations as they happen. Agent memory and full conversation history persist in PostgreSQL, so any run can be replayed and audited later.

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-agentforge--omega--topaz.vercel.app-brightgreen?style=flat-square&logo=vercel)](https://agentforge-omega-topaz.vercel.app/)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![LLM API](https://img.shields.io/badge/LLM_API-412991?style=flat-square&logo=openai&logoColor=white)

### 4. AI-PhishGuard, Phishing Detection Platform
A phishing detector that pairs a scikit-learn classifier trained on URL and domain features with a Groq LLM pass for contextual reasoning, then cross-checks each verdict against VirusTotal and WHOIS signals. Handles both single-URL real-time scans and bulk CSV runs, exporting auto-generated PDF threat reports for each batch. The React/TypeScript frontend talks to a Flask API deployed behind NGINX on AWS EC2.

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-ai--phishguard.web.app-brightgreen?style=flat-square&logo=firebase)](https://ai-phishguard.web.app/)

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React TS](https://img.shields.io/badge/React_TS-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=meta&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=flat-square&logo=virustotal&logoColor=white)

### 5. DermaCam AI, Dermatology Assistant
A Flutter app that runs 7 vision models (HuggingFace + Roboflow) to classify skin conditions at 93–96% accuracy straight from a phone camera. A Hinglish voice assistant walks users through each diagnosis and care steps conversationally, making it usable for non-English speakers. Redis caches inference results to cut repeat latency, and the project qualified for HackIndia Spark 4 2026 Round 2.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Roboflow](https://img.shields.io/badge/Roboflow-6706CE?style=flat-square&logo=roboflow&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

---

## > Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend**
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django REST](https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**AI / ML**
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-412991?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-FF6F00?style=flat-square&logo=langchain&logoColor=white)
![Groq Llama 4](https://img.shields.io/badge/Groq_Llama_4-F55036?style=flat-square&logo=meta&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![CNNs](https://img.shields.io/badge/CNNs-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Cloud / DevOps**
![AWS](https://img.shields.io/badge/AWS_EC2_·_SNS_·_SES-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat-square&logo=gunicorn&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

**Security**
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=flat-square&logo=virustotal&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![OSINT](https://img.shields.io/badge/OSINT-0a0e14?style=flat-square&logo=tryhackme&logoColor=white)
![WHOIS](https://img.shields.io/badge/WHOIS_API-2C2C2C?style=flat-square&logo=icloud&logoColor=white)

**Automation**
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4F00?style=flat-square&logo=zapier&logoColor=white)
![Browser Automation](https://img.shields.io/badge/Browser_Automation-2EAD33?style=flat-square&logo=playwright&logoColor=white)

## `> most used`

<div align="center">

![Python](https://img.shields.io/badge/Python-35%25-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-20%25-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-15%25-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-12%25-0175C2?style=flat-square&logo=dart&logoColor=white)
![HTML%2FCSS](https://img.shields.io/badge/HTML%2FCSS-10%25-E34F26?style=flat-square&logo=html5&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-8%25-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

</div>

---

## > Achievements

```
[✓] HackIndia Spark 4 2026 — Round 2 Qualifier
[✓] Vibecon India — Round 2 (10,000+ participants)
[✓] Selected — GSSoC 2026 & SSOC 2026 (Open Source Contributor)
```

---

<div align="center">

> **"Build systems that bend under pressure — never ones that break."**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:14ffec,50:0d7377,100:0a0e14&height=120&section=footer" alt="" />

</div>
