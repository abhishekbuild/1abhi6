## Hi, I'm Abhishek

AI Engineer at a veterinary-tech startup building AI-powered practice management software for clinics. I build production AI agents, and the parts that make them dependable: evaluation, tracing and guardrails.

Based in Hyderabad, India.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhishekbuild-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishekbuild)
![Profile views](https://komarev.com/ghpvc/?username=abhishekbuild&base=2143&label=Profile%20views&color=555555&style=flat)

---

### Current work

**Clinical co-pilot for vets** · *live*
A chat assistant vets use during their day. I built the orchestrator and the sub-agents for patient-profile summaries, generative UI, inventory, tasks and appointments, along with voice input using Pipecat. In launch week, vets asked it 446 questions and used voice input 150 times.
`LangGraph` `FastAPI` `Azure App Service`

**Post-visit follow-up agent** · *in QA, launching to clinics November 2026*
An agent that follows up with pet owners after a visit. It proposes bookings and reschedules for staff to approve, escalates urgent cases, and hands anything unclear to a person. I built it on my own, from PRD to QA: 13 agent tools, around 310 automated tests, and every model call traced in Langfuse.
- 32-scenario multi-turn eval suite; all 12 safety scenarios pass, 92% of samples overall
- Correctly attributes messages in multi-pet households 36/36 times, versus 10/36 for name matching
- In pre-production testing: p95 reply latency down 52%, cost per reply down 27%, 94–96% prompt-cache hit rate

`Claude` `Vercel AI SDK` `Convex` `Langfuse`

### Side projects

**[Slop Signal](https://slopsignal.dev)** · *live*
A Chrome extension that flags AI-generated posts in your feed. It only checks posts you actually scroll to, caches results for seven days and never stores post text, which keeps each check at roughly $0.00006. 36 users and 7,500+ posts labeled so far.
`TypeScript` `WXT` `Manifest V3`

**[TabCake](https://tabcake.com)** · *launching soon*
A product built on an end-to-end RAG pipeline: classification, chunking, embeddings, retrieval and reranking, with evals and versioned prompts.
`Next.js` `TypeScript` `RAG`

### Background

Before moving into AI engineering I founded and ran Unarrow Digital, an agency that served 20+ clients with a team of eight. That's where I learned to judge software by whether people use it, not by how it's built.

### Tools I work with

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI agents & LLMs**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel%20AI%20SDK-000000?style=flat-square&logo=vercel&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic%20Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat-square)
![Pipecat](https://img.shields.io/badge/Pipecat-333333?style=flat-square)
**Evals & observability**

![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square)
![Application Insights](https://img.shields.io/badge/Application%20Insights-0078D4?style=flat-square)

**Backend & data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-EE342F?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![MS SQL Server](https://img.shields.io/badge/MS%20SQL%20Server-CC2927?style=flat-square)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Chrome Extensions](https://img.shields.io/badge/Chrome%20Extensions-4285F4?style=flat-square&logo=googlechrome&logoColor=white)

**Cloud & tooling**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### Activity

[![GitHub streak](https://streak-stats.demolab.com/?user=abhishekbuild&hide_border=true)](https://git.io/streak-stats)

Most of my work lives in private repositories. If you'd like to see how something is built, I'm happy to walk you through the code.
