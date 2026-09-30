# Simeon Akinrinola
Full-Stack Software Engineer | React, Next.js, TypeScript, Node.js | AI/LLM Systems (RAG, Agentic Workflows)

Lagos, Nigeria | 09065979423 | simeonakinrinola7@gmail.com | linkedin.com/in/simeonakinrinola | github.com/AkinDiamonds

## Professional Summary
Full-stack software engineer who ships across the whole product: React and Next.js interfaces (dashboards, forms, AI chat), Node.js and Python (Express, FastAPI) services, relational data layers, and LLM features (LangChain, LangGraph, LlamaIndex, RAG, agentic workflows) running in live products for real users. Known for diagnosing problems at the root cause: resolved an N+1 query pattern that halved a core reporting feature's response time, introduced Redis caching that lifted response times across an internal operational platform by over 20%, and fixed a calculation defect in a clock-in/attendance feature that cut related incident reports by more than 80%. Applies the same engineering rigor to frontend architecture, backend APIs, and AI pipelines: automated testing, code review, containerization, and cloud deployment (AWS, DigitalOcean, Oracle Cloud). Builds with modern AI-assisted tooling (Cursor, Claude Code, GitHub Copilot), presents live projects weekly, open-sourced a forkable portfolio agent, and regularly explains AI concepts to developers and founders on LinkedIn and a technical blog.

## Core Competencies
- [frontend] Front-End Development & Architecture (React, Next.js, TypeScript, JavaScript, HTML, CSS, component architecture, dashboards, forms, AI chat interfaces)
- [backend] Backend API Design & Development (Node.js, Express.js, FastAPI, TypeScript, Python, RESTful architecture, microservices)
- [ai] AI/LLM Engineering & Agentic Systems (LangChain, LangGraph, LlamaIndex, RAG pipelines, tool-calling agents, prompt design, evaluation)
- [ai] AI-Assisted Development (Cursor, Claude Code, GitHub Copilot, VS Code)
- [backend] Database Design & Query Optimization (MySQL, PostgreSQL, Redis, indexing, TypeORM, full-text search)
- [backend] Performance Diagnosis & Root-Cause Debugging
- [backend][frontend] Automated Testing & Code Quality (Mocha, Chai, Vitest, code review)
- [devops] Cloud Deployment & Containerization (AWS, DigitalOcean, Oracle Cloud, Docker, Linux, deployment pipelines)
- [comms][leadership] Technical Communication, Writing & Leadership (weekly live-project presentations, LinkedIn AI explainers, technical blog, cross-functional collaboration, documentation)

## Technical Skills
- **Languages:** JavaScript (ES6+), TypeScript, Python, SQL
- **Front-End:** React, Next.js, Vite, TypeScript, JavaScript (ES6+), HTML, CSS, frontend architecture, consuming RESTful APIs, streaming chat interfaces
- **Back-End:** Node.js, Express.js, FastAPI, RESTful API design, TypeORM, Drizzle ORM, microservices-oriented design, Object-Oriented Design
- **AI / LLM Engineering:** LangChain, LangGraph, LlamaIndex, Retrieval-Augmented Generation (RAG), FAISS, agentic workflows and tool calling, prompt design, LLM evaluation, OpenAI, Gemini SDK, Anthropic and Hugging Face APIs, N-ATLAS (Awarri), self-hosted and local models
- **Databases & Caching:** MySQL, PostgreSQL, Supabase, Redis, query optimization, indexing, full-text search
- **Testing & Quality:** Mocha, Chai, Vitest, automated testing, debugging, performance tuning, code review
- **Cloud & Infrastructure:** AWS, DigitalOcean, Oracle Cloud, Docker, Docker Compose, containerization, Linux, deployment pipelines
- **Developer Tools:** VS Code, Cursor, Claude Code, GitHub Copilot, Git/GitHub

## Professional Experience

### Software Engineer, PublicaAI | March 2026 – Present | Lagos, Nigeria
- [frontend][backend] Own features end to end across the stack: build React and TypeScript interfaces (dashboards, data-entry forms, and AI chat experiences) alongside the Node.js and Express services, RESTful APIs, and database schemas behind them.
- [ai][frontend][backend] Integrate LangChain-based AI/LLM features directly into production products, working across frontend, backend, and AI orchestration through to deployment.
- [backend] Identified and resolved an N+1 query pattern in a production reporting feature used daily by internal teams, cutting query response time by 50% and removing a recurring source of dashboard slowdowns.
- [backend] Diagnosed a metrics-calculation defect in a clock-in/attendance feature traced to the calculation referencing a live timestamp instead of a fixed reference point; shipped the fix and reduced incident reports on the feature by over 80%.
- [backend] Introduced Redis caching to an internal operational platform, improving response times by more than 20% and reducing repeated load on the primary database.
- [backend] Own the design and maintenance of MySQL schemas, indexing strategy, and TypeORM migrations supporting core product workflows, including full-text search functionality.
- [backend][frontend] Write and maintain automated test suites (Mocha/Chai), building out substantial coverage across core modules, and participate in regular peer code review to uphold code quality standards.
- [devops] Deploy and support production services on DigitalOcean and AWS, handling release management and operational monitoring.

### AI Architect, True Believer Strategy Inc | 2026
- [ai] Architect AI-powered solutions, defining system design, retrieval and agent workflows, and technical direction for LLM-based features.
- [ai][comms] Translate business needs into practical AI system designs, balancing quality, cost, and reliability for real users.

### GenAI Fellow (AI Developer), Publica Academy | August 2025 – Present
- [comms][leadership] Present live projects in weekly demos to mentors and cohort peers, walking through architecture, trade-offs, and results for both technical and non-technical audiences.
- [ai] Build LLM-backed products end to end: RAG pipelines (chunking, embeddings, retrieval) and multi-step agentic flows using LangChain, LangGraph, and LlamaIndex, through to the user-facing interface.
- [frontend] Study and apply frontend architecture principles when building the user-facing layer of AI products.
- [ai] Practice AI engineering with a focus on evaluation: test retrieval and generation quality against representative query sets, then tighten prompts and retrieval parameters to reduce hallucinated or unsupported answers.
- [comms][leadership] Collaborate with a cohort of AI developers on shared tooling, code review, and best practices across multiple projects.

### Data Science Intern, Hamoye.org | May 2022 – March 2023 | United Kingdom (Remote)
- [data] Performed data cleaning, exploratory data analysis, and feature engineering on real-world datasets as part of a distributed, remote cohort, collaborating asynchronously across time zones.
- [data] Resolved missing values, inconsistent formatting, and outliers across multiple raw datasets, and engineered new features to improve model input quality.
- [data] Conducted exploratory data analysis in Python (Pandas, NumPy, Matplotlib/Seaborn) to surface trends, correlations, and data quality issues ahead of modeling.
- [data][comms] Documented workflows for reproducible handoff and presented findings to cohort peers and mentors, translating analysis into clear, actionable takeaways.

### Student Intern, Aspire Institute | February 2022 – March 2023
### Intern, Covenant University | May 2021 – October 2021

## Selected Projects

### Portfolio Agent: Open-Source AI Agent for Developer Portfolios (Python, FastAPI, Docker)
- [ai][backend][comms] Designed and open-sourced a self-hostable, model-agnostic chat agent backend that lets any developer add an AI assistant to a portfolio site by forking the repo and editing only a .env file and a system prompt, with detailed setup guidelines; works with any OpenAI-compatible provider (OpenAI, OpenRouter, Groq, Ollama, vLLM).
- [ai][backend] Built a tool-calling agent loop that grounds answers in live public GitHub data (one tool, nine actions), with a non-streaming decide step, streamed final answers, a tool-iteration loop guard, server-side token budgeting, per-IP rate limiting, and strict CORS; stateless and shipped as a single Docker container (MIT licensed).
- [devops] Powers the assistant on my own portfolio site, deployed on an Oracle Cloud VM.
- Repo: github.com/AkinDiamonds/portfolio_agent

### TouristAI, Top 10, Awarri AI Developer Competition (React, Vite, FastAPI, LangChain, FAISS, Supabase)
- [ai] Led the RAG architecture for a travel assistant for Lagos that pairs a curated attractions directory with an AI guide powered by N-ATLAS, Nigeria's first multilingual LLM (Awarri); placed among the top 10 entries in a national developer competition.
- [ai][backend][frontend] Engineered retrieval pipelines (LangChain, FAISS) over curated local data to give hyper-local, language-aware answers, served through a FastAPI backend with a React/Vite frontend and Supabase (PostgreSQL) for dynamic content; self-hosted the LLM behind the API.
- Repo: github.com/AkinDiamonds/touristai (public, not live)

### EduGuide: AI-Powered Exam Prep Platform (FastAPI, React, PostgreSQL, Redis)
- [backend][frontend][ai] Contributed to system design as part of an 8-person team building a platform that guides Nigerian secondary school students through WAEC, JAMB, and POST-UTME preparation, with practice questions, an AI study advisor, personal study plans, and a university cutoff tracker covering 50+ institutions.
- [devops][frontend] Owned containerization (Docker) and full production deployment, including domain configuration and SSL setup; contributed UI and performance refinements.

### BuildersCabal: African Startup Directory (Backend, ongoing)
- [backend][devops] Backend engineer on an ongoing African startup directory platform, building the server-side APIs and the DevOps pipeline that supports deployment.

### Personal Portfolio (Next.js)
- [frontend][ai] Designed and built my portfolio in Next.js with project case studies, a technical blog, and an embedded AI agent; deployed on an Oracle Cloud VM.

## Writing & Community
- [comms][leadership] Regularly explain AI concepts to developers and founders on LinkedIn, translating LLM and agent engineering topics into practical guidance.
- [comms][ai] Author a technical blog on AI engineering and AI-assisted development (for example, structured outputs vs. JSON, and agentic coding tools).

## Education
**Bachelor of Science (BSc), Physics**, Federal University of Agriculture, Abeokuta (FUNAAB), 2018 – 2023

## Certifications
- API Design in Node.js, v5 (Master.dev)
- AI Engineering Fundamentals (Master.dev)
- Complete Intro to Containers, v2 (Master.dev)
- Introducing DevOps for Developers (Master.dev)
- Deep JavaScript Foundations, v3 (Master.dev)
- JavaScript: The Hard Parts, v3 (Master.dev)
- Python for Professional Developers (Master.dev)
- Agentic Frontend Development with Codex (Master.dev)
- The Hard Parts of Servers & Node.js (Master.dev)
- The Last Algorithms Course You'll Need (Master.dev)
- Complete Intro to Computer Science (Master.dev)
- Intermediate Python (Master.dev)
- C# and .NET Basics (Master.dev)
- Digging Into Node.js (Master.dev)
- Frontend Architecture: Monoliths to Microfrontends (Master.dev)
- TypeScript in the Age of AI (Master.dev)
- Permission Systems that Scale (Master.dev)
- Deploying Web Applications on AWS, v3 (Master.dev)
- Harness Engineering & Agent Orchestration (Master.dev)
- Award-Winning Marketing Websites (Master.dev)
- Functional JavaScript First Steps, v2 (Master.dev)
- Complete Intro to React, v9 (Master.dev)
- Vanilla JS: You Might Not Need a Framework (Master.dev)
- Testing Fundamentals (Master.dev)
- TypeScript 5+ Fundamentals, v4 (Master.dev)
- Professional CSS: Build a Website from Scratch (Master.dev)
- Web Performance Fundamentals, v2 (Master.dev)
- The Last Algorithms Course You'll Want (Part 2) (Master.dev)
- Practical Problem Solving with Algorithms (Master.dev)
- Own Your AI Stack with Local Models (Master.dev)