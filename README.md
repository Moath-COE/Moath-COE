<a href="https://moaz-coe.com">
  <img src="cover.png" alt="Moaz Abdelaziz, AI Engineer. I build AI products that deliver real value." width="100%">
</a>

<p align="center">
  <a href="https://moaz-coe.com"><img src="https://img.shields.io/badge/🌐_moaz--coe.com-121a33?style=for-the-badge&labelColor=0b1020" alt="Website: moaz-coe.com"></a>
  <a href="https://www.linkedin.com/in/moaz-abdelaziz-7a8461236/"><img src="https://img.shields.io/badge/LinkedIn-121a33?style=for-the-badge&logo=linkedin&logoColor=a5b3dc" alt="LinkedIn"></a>
  <a href="https://x.com/Moath_COE"><img src="https://img.shields.io/badge/X-121a33?style=for-the-badge&logo=x&logoColor=a5b3dc" alt="X"></a>
  <a href="https://www.youtube.com/@MoathAbdelaziz/"><img src="https://img.shields.io/badge/YouTube-121a33?style=for-the-badge&logo=youtube&logoColor=a5b3dc" alt="YouTube"></a>
</p>

## Hi, I'm Moaz

I'm an AI engineer based in Riyadh. I build and ship real-time voice AI and agent systems. My most recent work is a bilingual Arabic/English AI voice tutor that nearly 200 students have used. I graduated from KFUPM with a BSc in Computer Engineering (Second Honors) and hold two AWS certifications.

I start from the problem rather than the model. I use an LLM only where it earns its place, measure it with evaluation datasets and traces, and use plain, testable code everywhere else.

📝 I write about what I build, including the trade-offs, numbers and mistakes, at **[moaz-coe.com](https://moaz-coe.com)** in Arabic and English.

## What I'm good at

- **Real-time voice AI:** streaming speech-to-text, LLM and text-to-speech pipelines on LiveKit Agents, with Deepgram, ElevenLabs and Cartesia, kept under 900 ms.
- **AI agents and LLM systems:** tool calling, multi-model and event-driven architectures, LangGraph workflows, and deciding where a model belongs and where deterministic code is better.
- **Evaluation and observability:** hand-labelled datasets, replay harnesses, A/B tests, and Langfuse traces for latency, quality and cost per session.
- **Backend and full stack:** Node.js and TypeScript, Python with FastAPI, PostgreSQL with Drizzle and Prisma, Next.js and tRPC.
- **Shipping:** Vitest and pytest suites, GitHub Actions CI/CD, Docker, Linux and AWS.

## Experience

**AI Engineer · [Becan](https://becan.app)** (formerly Chapter-14) · Nov 2025 – Nov 2026

- Built a real-time **bilingual AI voice tutor** on the LiveKit Agents SDK: Deepgram STT → LLM → ElevenLabs TTS, under 900 ms, across 350+ sessions and 50+ hours.
- Designed an **event-driven, multi-model architecture**: a tool-calling tutor agent, a speech-to-board classifier and a board assistant. Deterministic code, not the LLM, owns lesson progress and quiz state.
- Replaced an LLM "director" with a **typed classifier** that answers in about 100 ms, syncing the live teaching board to the tutor's speech while cutting latency and cost.
- Built the **evaluation loop**: a hand-labelled dataset, a replay harness, a 43-run baseline, and a live A/B test that showed about 92% precision in both languages.
- Built the platform backend in Node.js and TypeScript: 30+ REST endpoints, a 17-table PostgreSQL schema, 300+ Vitest tests, and CI/CD to staging and production.

**Full-Stack Web Developer Intern · [Shatib](https://shatib.sa)** · May – Aug 2025
Built features for a production procurement platform with Next.js, TypeScript, tRPC and Prisma, including a customer onboarding flow integrated with the company's ERP.

## Selected projects

| Project | What it is | Built with |
| --- | --- | --- |
| **Computerizer** | A web platform that helps people choose PC parts, with a blog and OAuth sign-in. I contributed to the Django backend and built the Next.js frontend ([backend](https://github.com/Computerizer/Backend) · [frontend](https://github.com/Computerizer/React-Frontend)). | Python, Django, PostgreSQL, Azure, Next.js |
| **[Hakamony](https://github.com/Hakamony/source)** | An Arabic, mobile-first app for organising pickup games: fair teams, match schedules across fields, and bill splitting. I maintained the repository, set up CI/CD, and reviewed most of the 88 PRs ([live](https://hakamony.vercel.app/)). | Next.js, Tailwind, GitHub Actions |
| **[KFUPM Computer Club website](https://github.com/Razorback360/CC_Website)** | The website of the KFUPM Computer Club, built with the club's dev team on the T3 stack ([live](https://cc-kfupm-website.vercel.app)). | Next.js, tRPC, Prisma, NextAuth, PostgreSQL |
| **[Becan web app](https://github.com/Moath-COE/me-bcn-full-stack)** | The web app and REST API behind Becan, a voice tutor for university students: authentication with TOTP two-factor and an admin audit log, the course catalog, enrollments, plans with usage allowances, and the live session screen that renders the tutor's board. The API is tested against a real PostgreSQL database ([live](https://me-bcn-full-stack.vercel.app)). | Next.js, React, Express, TypeScript, PostgreSQL, Drizzle, Better Auth |
| **[Moaz-Code](https://github.com/Moath-COE/moaz-code)** | A CLI coding agent that teaches you to code instead of coding for you: it explains the why, reviews your code and asks for the test first, then leaves the keyboard to you. Written from scratch with an agent loop, a tool registry (Read, Write, Bash), `SKILL.md` skills, and a read-only dev container. | Python, OpenRouter, Docker |

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-121a33?style=flat-square&logo=python&logoColor=a5b3dc" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-121a33?style=flat-square&logo=typescript&logoColor=a5b3dc" alt="TypeScript">
  <img src="https://img.shields.io/badge/LiveKit_Agents-121a33?style=flat-square" alt="LiveKit Agents">
  <img src="https://img.shields.io/badge/LangGraph-121a33?style=flat-square&logo=langchain&logoColor=a5b3dc" alt="LangGraph">
  <img src="https://img.shields.io/badge/Deepgram-121a33?style=flat-square" alt="Deepgram">
  <img src="https://img.shields.io/badge/ElevenLabs-121a33?style=flat-square&logo=elevenlabs&logoColor=a5b3dc" alt="ElevenLabs">
  <img src="https://img.shields.io/badge/Langfuse-121a33?style=flat-square" alt="Langfuse">
  <img src="https://img.shields.io/badge/Ollama-121a33?style=flat-square&logo=ollama&logoColor=a5b3dc" alt="Ollama">
  <img src="https://img.shields.io/badge/Node.js-121a33?style=flat-square&logo=nodedotjs&logoColor=a5b3dc" alt="Node.js">
  <img src="https://img.shields.io/badge/FastAPI-121a33?style=flat-square&logo=fastapi&logoColor=a5b3dc" alt="FastAPI">
  <img src="https://img.shields.io/badge/Next.js-121a33?style=flat-square&logo=nextdotjs&logoColor=a5b3dc" alt="Next.js">
  <img src="https://img.shields.io/badge/PostgreSQL-121a33?style=flat-square&logo=postgresql&logoColor=a5b3dc" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Vitest-121a33?style=flat-square&logo=vitest&logoColor=a5b3dc" alt="Vitest">
  <img src="https://img.shields.io/badge/GitHub_Actions-121a33?style=flat-square&logo=githubactions&logoColor=a5b3dc" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Docker-121a33?style=flat-square&logo=docker&logoColor=a5b3dc" alt="Docker">
  <img src="https://img.shields.io/badge/Proxmox-121a33?style=flat-square&logo=proxmox&logoColor=a5b3dc" alt="Proxmox">
  <img src="https://img.shields.io/badge/AWS-121a33?style=flat-square&logo=amazonwebservices&logoColor=a5b3dc" alt="AWS">
</p>

<sub>AWS Certified Solutions Architect – Associate · AWS Certified Cloud Practitioner</sub>

## Currently

- 🔨 Building **Hassas**, from the PRD to its first working agent.
- ✍️ Writing up my projects as case studies on [moaz-coe.com](https://moaz-coe.com).
- 🧪 Running local models on my home lab.

<p align="center"><sub>◆ &nbsp;Open to conversations about voice AI, agents, and AI products.&nbsp; ◆ &nbsp;<a href="https://moaz-coe.com">moaz-coe.com</a></sub></p>
