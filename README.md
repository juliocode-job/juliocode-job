# Mid GenAI Engineer | Building Production-Ready AI Systems That Scale

**GenAI Engineer at Capgemini**, focused on building enterprise-grade AI systems that move from experimentation to real, scalable products.

I work at the intersection of **LLMs, product thinking, and cloud architecture**, helping teams go beyond proofs of concept into reliable, secure, and observable GenAI solutions aligned with real business constraints.

My expertise spans **end-to-end AI architecture, Agentic Systems, and LLMOps**, with hands-on experience designing, deploying, and maintaining production-ready AI workflows. I frequently bridge technical teams and business stakeholders to ensure feasibility, robustness, and long-term value — not demos for demos' sake.

Certified as a **Microsoft Azure AI Engineer**, with additional AI-focused credentials, I emphasize applied AI, observability, governance, and measurable outcomes in regulated and enterprise environments.

---

## 📊 Selected Impact

| Metric | Result |
|--------|--------|
| Automation efficiency for business processes | **+40%** |
| Data classification and extraction workflows | **+50% faster** |
| Conversational AI accuracy | **+35%** |
| Solution relevance using RAG and vector databases | **+30%** |

---

## 🛠️ Technical Stack

**Languages & Backend:** Python, Node.js, TypeScript, FastAPI

**LLMs & Frameworks:** LangChain, LangGraph, CrewAI, AutoGen, LlamaIndex

**Cloud & Infrastructure:** Azure AI Foundry, AWS, GCP, Docker, Kubernetes, Redis (queues & caching)

**Data & Retrieval:** MongoDB, PostgreSQL, Vector Databases (Pinecone, Qdrant, Milvus, ChromaDB)

**Observability & Evaluation:** LangSmith, tracing, prompt evaluation, monitoring, custom metrics

**Additional:** OpenAI (GPT-4), Anthropic (Claude), n8n, Git

---

## 🎓 Certifications

- **Microsoft Azure AI Engineer Associate (AI-102)**
- **Databricks Generative AI Engineer Associate**
- **Google Generative AI Leader (GCP)**
- Salesforce AI Specialist
- Salesforce AI Associate
- Oracle AI Foundations
- Microsoft Azure AI Fundamentals (AI-900)

---

## 🏆 Featured Projects

A selection of key projects demonstrating end-to-end AI solution delivery. Each includes the business problem, solution architecture, technologies used, and measurable impact.

### 🏢 AI-Powered Procurement Intelligence Platform — Enterprise Microservices

**Problem:** A Fortune 500 telecom provider needed to process thousands of government tenders efficiently. Manual PDF ingestion, data extraction, and classification created bottlenecks, while batch uploads caused system timeouts and silent failures in the AI pipeline compromised data integrity.

**Solution:** Contributed to an enterprise-grade microservices platform featuring LLM-based data extraction, semantic embeddings, and real-time analytics. Implemented MongoDB-based job queues with HPA scaling, exponential backoff retry mechanisms, and circuit breaker patterns. Built comprehensive observability with correlation ID tracking across services and structured logging for production debugging.

**Stack:** TypeScript, Node.js, Fastify, MongoDB, LangChain, Azure OpenAI, Azure Kubernetes Service (AKS), Azure DevOps, Docker, Zod, Pino

**Impact:** Eliminated timeouts on batch uploads (50+ documents). Reduced integration delays through comprehensive API documentation. Enabled zero-downtime deployments with blue-green strategy and automated rollbacks.

---

### 🔧 AI-Powered Pull Request Automation — Autonomous Code Fixing System

**Problem:** Development teams spend significant time on repetitive bug fixes and manual PR creation. Error-to-fix cycles are slow, and there's no systematic way to ensure proposed changes are safe and minimal before human review.

**Solution:** Built an end-to-end automation system that transforms error reports into validated pull requests. Uses Claude Opus for error analysis and constraint planning, Claude Sonnet for minimal diff generation. Features a 6-layer validation system (status, confidence, diff existence, language consistency, change limits, line verification) with safe fallbacks and review flagging for uncertain fixes.

**Stack:** n8n, Claude Opus, Claude Sonnet, GitHub API, Webhooks

**Impact:** Automated the entire error-to-PR pipeline while keeping humans in the loop. PRs include AI justification and confidence levels. System tracks approval/rejection outcomes for continuous improvement.

---

### 🎯 Agentic Market Research Team — Autonomous AI Intelligence System

**Problem:** Companies struggle to understand their customers' psychological drivers, losing deals to competitors who "speak their language." Traditional market research delivers generic personas that miss unconscious motivations. Managing multiple AI agents typically requires complex orchestration and lacks persistent learning.

**Solution:** Architected a Level 5 autonomous agent system with 6 specialized AI agents that decode customer psychology at depth. Features persistent memory via Qdrant vector database, enabling agents to learn from every interaction. Agents collaborate through LangGraph workflows, accessible through natural Slack commands for non-technical users.

**Stack:** Python, LangChain, LangGraph, Anthropic Claude, Qdrant, Slack Bolt, Sentence Transformers, FastAPI, Docker

**Impact:** 3x higher conversion rates using extracted language patterns. Reduced market research time from weeks to hours with continuous autonomous improvement.

---

### 🚀 AI-Enhanced Todo List — Full Stack Solution with Dual Interface

**Problem:** Traditional todo apps lack intelligence to help users complete tasks effectively. Users create vague tasks without actionable guidance, leading to procrastination. Teams needed both web and conversational interfaces across different contexts.

**Solution:** Built a full-stack todo application with AI enhancement that transforms simple task entries into actionable plans. Features dual interfaces: Next.js web app for visual management and n8n-powered chatbot for conversational task creation, sharing the same Supabase database.

**Stack:** Next.js 14, TypeScript, React 18, Supabase (PostgreSQL), OpenAI GPT-3.5, n8n, Vercel, Tailwind CSS

**Impact:** Users complete tasks 40% faster with AI-generated guidance. Dual-interface approach increased task creation by 60%.

---

### 🧠 TeamBrain — Secure Enterprise AI Agent

**Problem:** Employees waste hours searching for information across siloed wikis, drives, and documents. No guarantee users only access data they're authorized to see.

**Solution:** Built an enterprise AI assistant with a secure, ACL-aware RAG pipeline. Checks user permissions before retrieving information from vector database, ensuring data security at the core of every response.

**Stack:** Python, LangChain, RAG, Flask, OpenAI GPT-4o, ChromaDB, Docker

**Impact:** Instant access to authorized information with enforced access controls, significantly reducing internal data leak risk.

---

### 🤖 Autonomous AI Sales Agent for Lead Outreach

**Problem:** Sales teams losing time on manual lead qualification and follow-ups, causing high-value leads to slip through.

**Solution:** Built a 24/7 autonomous agent that perceives customer data, reasons to qualify leads, and acts by sending hyper-personalized emails and booking meetings. Uses vector database for long-term memory and context-aware interactions.

**Stack:** Agentic AI, n8n, OpenAI, Supabase (Vector Database)

**Impact:** Eliminated outreach bottleneck, allowing sales team to focus 100% on closing deals.

---

### 🎙️ ConvoBot — Intelligent AI Meeting Assistant

**Problem:** Critical decisions and action items lost in manual note-taking during meetings.

**Solution:** Developed a voice-activated AI agent that joins meetings (Google Meet, Zoom), provides real-time transcription, and delivers intelligent summaries. Uses RAG to create a searchable knowledge base of all past conversations.

**Stack:** Voice AI, RAG, LangChain, Whisper, FastAPI

**Impact:** Automated 100% of note-taking, reduced post-meeting admin work by 90%.

---

### ⚙️ ZESU — Intelligent Automation for IT Support

**Problem:** Enterprise IT team overwhelmed with repetitive Level 2 support requests, causing delays and pulling senior staff from critical incidents.

**Solution:** Implemented an internal AI chatbot using RAG pipeline to securely access internal knowledge bases, providing real-time guidance for 143+ distinct IT procedures.

**Stack:** AI Agents, RAG, LangChain, TARS

**Impact:** Reduced L2 query response times by 40%, increased IT team productivity.

---

### 🎓 AI Tutor Evaluation for EdTech Safety & Efficacy

**Problem:** EdTech client needed to integrate LLMs as AI tutors but faced risks from hallucinations that could harm learner trust.

**Solution:** Developed comprehensive evaluation framework and multi-faceted rubric to benchmark LLM performance and safety for educational use.

**Stack:** LLM Evaluation, Responsible AI, Prompt Engineering

**Impact:** Recommendations led to 25% reduction in model hallucinations on key subjects.

---

## 💡 What I Bring

I thrive in global environments where **innovation meets execution**, building AI systems designed to scale, perform, and deliver sustained ROI. My approach emphasizes:

- **Production-first mindset:** Solutions built for reliability, not just impressive demos
- **Observability & governance:** Tracing, monitoring, and compliance for enterprise environments
- **Business alignment:** Bridging technical teams and stakeholders for measurable outcomes
- **End-to-end ownership:** From architecture to deployment to maintenance

---

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/servicesfromjulio/)

📫 **Let's connect** — I'm always interested in challenging GenAI problems at enterprise scale.
