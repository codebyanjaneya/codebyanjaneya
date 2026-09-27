# Anjaneya Tiwari

Full-Stack Developer · AI Engineer · Automation Engineer · Cybersecurity

[Portfolio](https://codebyanjaneya.github.io) · [LinkedIn](https://linkedin.com/in/anjaneya-tiwari) · [Email](mailto:anjaneyatiwarii@gmail.com) · Delhi, India

I work on backend and AI systems, from high-concurrency services to automation tools and research applications.

## Currently Building

### H.E.R.C.S

A desktop voice assistant that runs speech-to-text and voice cloning locally. It wakes on a clap or the phrase “wake up Hercs,” responds in a cloned voice, and uses a Canvas 2D HUD to show its state. LLM tool-calling lets it launch apps, control volume, take screenshots, and read system vitals.

`wake → faster-whisper → Groq Llama 3.3 tool calls → Coqui XTTS-v2`

Stack: Python, faster-whisper, Groq Llama 3.3, Coqui XTTS-v2, PyTorch, CUDA, Canvas 2D

[Project updates](https://github.com/codebyanjaneya)

## Experience

### Research & Development Intern · RootStock Technologies
*Aug 2026–Present · IIIT Research Centre*

- Built a real-time robotic-arm simulator in React and Three.js (react-three-fiber), with 6-DOF forward kinematics, labeled joints J1–J6, live joint-angle telemetry, and an automated pick-and-place cycle.
- Built a multi-user email-triage engine with FastAPI and Gmail OAuth PKCE. Its rules-first classifier uses Groq Llama 3.3 70B; semantic search runs over BAAI bge embeddings using fastembed and SQLite.
- Profiled deep-learning inference and data workloads on multi-GPU CUDA servers, tuning batch throughput and VRAM use for research experiments.

### Software Engineer Intern · Full-Stack Developer · Gleska Private Limited
*Jun 2026–Aug 2026 · New Delhi, hybrid*

- Built a PostGIS worker-matching engine using `ST_DistanceSphere` and geoalchemy2. A single query ranks workers by proximity (50%), rating (30%), and experience (20%); the search radius expands from 10 km to 30 km, and offers expire after two minutes.
- Developed a dispatch lifecycle with dual four-digit OTP checks for arrival and completion, plus atomic offer cancellation, using async FastAPI, SQLAlchemy, and PostgreSQL.
- Integrated webhook-driven Cashfree payments, subscription gating, and Cashfree KYC for Udyam verification, with Supabase JWT authentication and secure document storage.

### Backend & AI Systems Intern · Telogo Communications Ltd
*Sep 2025–Mar 2026 · Noida*

- Developed an IVR speech-processing pipeline to improve recognition across Indian accents and dialects.
- Built concurrent call handling with async task queues, worker pools, and auto-scaling cloud services.
- Reached sub-two-second response latency using streaming transcription, model warm-up, and pre-cached voice responses.
- Developed LoadPulse, a concurrency and observability platform using FastAPI, asyncio worker pools, and token-bucket rate limiting.
- Benchmarked more than 1,000 concurrent requests with graceful degradation and controlled traffic shaping.
- Built a React, Recharts, and WebSockets dashboard streaming latency, queue depth, and worker utilization.

### Software Development Intern · Motivus Innovation Pvt. Ltd.
*Feb 2025–Jul 2025 · Noida*

- Shipped REST APIs and PostgreSQL-backed modules for an AI-driven ESG and sustainability-reporting platform, covering schema design, API contracts, testing, and deployment.
- Prototyped and evaluated ML models for renewable-energy analytics and automated carbon accounting, turning consumption data into sustainability metrics and reports.

## Projects

### LoadPulse · Concurrency and Observability

Async FastAPI worker pools and token-bucket rate limiting, benchmarked at more than 1,000 concurrent sessions with graceful degradation. The dashboard streams p50/p95/p99 latency, queue depth, and worker utilization over WebSockets every 500 ms. Deployed on AWS EC2 behind NGINX with SSL.

[Live demo](https://loadpulse-dashboard.vercel.app) · [GitHub](https://github.com/codebyanjaneya/loadpulse)

Stack: FastAPI, asyncio, React, Recharts, WebSockets, AWS EC2, NGINX

### AutoApply Bot · Recruitment Automation SaaS

A multi-tenant Telegram bot that parses resumes, matches candidates to jobs with Groq Llama 4, and drafts recruiter outreach. n8n orchestrates scraping and timed follow-ups; Razorpay handles tiered subscriptions. PostgreSQL isolates user data and daily quotas. Runs on AWS EC2.

[Live demo](https://autoapply-landing-sand.vercel.app/)

Stack: Telegram, n8n, Groq Llama 4, Razorpay, PostgreSQL, AWS EC2

### AgentForge · Multi-Agent AI System

A simulated company run by seven LLM agents, including CEO, Sales, and Marketing agents. They delegate tasks and communicate through a Redis event bus. FastAPI coordinates agent state and task queues; a Next.js dashboard visualizes decisions and conversations. PostgreSQL stores agent memory and conversation history for replay and audit.

[Live demo](https://agentforge-omega-topaz.vercel.app/)

Stack: FastAPI, Next.js, Redis, PostgreSQL, LLM APIs

### AI-PhishGuard · Phishing Detection

A scikit-learn classifier uses URL and domain features, followed by a Groq LLM pass for contextual reasoning. Verdicts are checked against VirusTotal and WHOIS signals. Supports real-time single-URL scans and bulk CSV runs, with PDF threat reports. The React/TypeScript frontend uses a Flask API deployed behind NGINX on AWS EC2.

[Live demo](https://ai-phishguard.web.app/)

Stack: Flask, React, TypeScript, scikit-learn, Groq, AWS EC2, VirusTotal, WHOIS

### DermaCam AI · Dermatology Assistant

A Flutter app that runs seven Hugging Face and Roboflow vision models to classify skin conditions from a phone camera, with reported accuracy of 93–96%. A Hinglish voice assistant explains diagnoses and care steps. Redis caches inference results. Qualified for HackIndia Spark 4 2026 Round 2.

Stack: Flutter, Hugging Face, Roboflow, Redis

### LLM-Gate · Code and Infrastructure Validation

A GitHub Actions pipeline checks LLM-generated Terraform and application code against five Open Policy Agent (OPA/Rego) security rules. A Selenium and PyTest feedback loop prompts Groq Llama 3.3 70B to fix flagged violations; the reported trust score improved from 66% to 100%.

[GitHub](https://github.com/codebyanjaneya/LLM-Gate)

Stack: Python, Terraform, OPA/Rego, GitHub Actions, Groq Llama 3.3, Selenium, PyTest

## Technical Skills

- **Languages:** Python, Dart, JavaScript, TypeScript, Bash
- **Backend:** Flask, Django REST, FastAPI
- **AI/ML:** Prompt engineering, RAG pipelines, Groq Llama 4, Hugging Face, OpenCV, CNNs
- **Cloud and DevOps:** AWS EC2, SNS, SES; Docker, NGINX, Gunicorn, GitHub Actions
- **Databases:** PostgreSQL, Redis, Firebase
- **Frontend:** React, Flutter, Next.js
- **Security:** VirusTotal, Burp Suite, OSINT, WHOIS API
- **Automation:** n8n, Zapier, browser automation

## Most Used Languages

Python 35% · TypeScript 20% · JavaScript 15% · Dart 12% · HTML/CSS 10% · Bash 8%

## Achievements

- HackIndia Spark 4 2026: Round 2 qualifier
- Vibecon India: Round 2, among 10,000+ participants
- Selected for GSSoC 2026 and SSOC 2026 as an open-source contributor
