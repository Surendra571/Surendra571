# Kuruva Surendra Kumar

<p align="center">
  <b>AI Engineer | Finance Agents & Automation | LLM Evaluation | Backend Engineering</b><br/>
  <i>I build reliable AI systems where financial correctness, measurable outcomes, and clean backend engineering matter.</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/surendra571">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://surendra571.itsfolio.tech/">
    <img src="https://img.shields.io/badge/Portfolio-Website-6366F1?style=flat-square&logo=googlechrome&logoColor=white" />
  </a>
  <a href="mailto:ksurendraa1.4@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Open%20to-AI%2FML%20%26%20Backend%20Roles-22C55E?style=flat-square" />
</p>

## 👨‍💻 About

I'm an AI Engineer with an MBA in Finance and a B.Sc. in Computer Science (AI/ML).

I build AI-powered financial applications, LLM agents, reconciliation systems, and backend platforms with a focus on financial accuracy, reliability, and production-ready engineering.

My primary focus areas:

- **Finance AI & Automation:** Bank reconciliation, invoice processing, payment systems, financial workflows, and accounting automation.
- **AI Agents & LLMs:** LangGraph, LangChain, structured outputs, RAG, and human-in-the-loop workflows.
- **Backend Engineering:** Python, FastAPI, Django REST Framework, PostgreSQL, Redis, and Celery.
- **Reliability & Evaluation:** Deterministic validation, idempotency, automated testing, audit trails, and LLM evaluation.

I believe AI should assist decision-making, while deterministic business rules enforce correctness, especially in financial systems.

**Open to:** AI Engineering, AI/ML, LLM/NLP, Backend Engineering, FinTech AI, and Forward Deployed Engineering roles across India.

## 📈 Results at a Glance

| Project | What it does | Results / Engineering Highlights |
|---|---|---|
| **FinBridge** | AI-powered financial reconciliation | 100+ automated tests, deterministic financial verification, multi-tenant architecture |
| **TokenWise** | LLM context optimization | Compares 5 context strategies, including a trained PyTorch reranker |
| **LLM Evaluation & Safety Platform** | Evaluates LLM and RAG quality | Async evaluation with PostgreSQL history |
| **Support Intent Pipeline** | Support classification and escalation | 84.5% accuracy, 0.8455 Macro F1 on 104,730 conversations |
| **Digital Advertising Analytics** | Conversion prediction and ROAS forecasting | R² 0.939, MAE 4.05 on 100K+ events |
| **InvoiceFlow AI** | Automated invoice approval | Explainable financial decisions with 30+ tests |
| **Digital Wallet** | Payments and ledger backend | Double-entry accounting, idempotency, 30+ tests |

## 🚀 Featured Projects

### 💳 [FinBridge — AI Financial Reconciliation Platform](ADD_GITHUB_REPOSITORY_URL)

**AI-powered bank-to-ledger reconciliation with deterministic financial verification.**

Built and deployed a financial reconciliation platform that matches bank statements against ERP ledger exports, using AI for intelligent suggestions and Python for final financial verification.

**Tech Stack:** `Python` `FastAPI` `React` `TypeScript` `PostgreSQL` `LangGraph` `OpenAI` `Docker`

Key engineering features:

- Bank statement ingestion from CSV/PDF and ERP ledger exports in NetSuite, SAP, and QuickBooks formats.
- Multi-currency reconciliation across USD, EUR, and INR.
- LangGraph + OpenAI agent suggests matches for messy bank transaction descriptions with confidence scores.
- **LLM proposes, Python verifies:** AI confidence alone never approves a financial match.
- Exact Decimal-based financial validation with cent-level checks.
- Currency isolation, debit/credit direction validation, amount tolerance, and duplicate-match prevention.
- Accounting-period locks to protect closed financial periods.
- Maker-Checker approval workflow for exceptions and fee variances.
- Tamper-evident SHA-256 hash-chained audit trail for every decision.
- Retry mechanisms and circuit breakers for unreliable external systems.
- Multi-tenant data isolation and role-based access control.
- 100+ automated tests, including property-based and tenant-isolation tests.

**Deployment:** Vercel + Render

**Core engineering principle:** AI assists reconciliation; deterministic code protects financial correctness.

---

### 🔬 [TokenWise](https://github.com/Surendra571/tokenwise)

**LLM token optimization and quality evaluation.**

Compares different context strategies and determines how to reduce token consumption without sacrificing answer quality.

`Python` `PyTorch` `Sentence Transformers` `FAISS` `FastAPI` `MLflow` `Streamlit`

- Compares full context, truncation, BM25, dense retrieval, and cross-encoder reranking.
- Token counting with tiktoken and Hugging Face tokenizers.
- Quality scoring with Exact Match, Token F1, ROUGE, and LLM-as-Judge.
- Adaptive token budgeting and experiment tracking.

---

### 🛡️ [LLM Evaluation & Safety Platform](https://github.com/Surendra571/llm-eval-safety-platform)

**Containerized benchmarking and safety monitoring for LLMs and RAG.**

`Python` `FastAPI` `PostgreSQL` `DeepEval` `RAGAS` `Plotly` `Docker`

- Evaluates toxicity, bias, hallucination, faithfulness, and relevance.
- Concurrent evaluation with asyncio.
- Dashboard to compare model quality over time.
- Stores evaluation history in PostgreSQL.

---

### 🎫 [Support Intent Classification & Escalation Pipeline](https://github.com/Surendra571/hiver-ai-support-agent)

**Leak-free NLP pipeline for customer support.**

`Python` `Sentence Transformers` `FAISS` `RAG` `Pytest`

- SHA-256-audited manifests prove train and test data never overlap.
- Seven-class intent classification model.
- Ten-signal escalation policy.
- Retrieval-grounded responses with automated tests.

---

### 📊 [Digital Advertising Analytics](https://github.com/Surendra571/digital-advertising-analytics)

**Conversion prediction and budget allocation.**

`Python` `SQL` `Scikit-learn` `Streamlit` `Pytest` `Docker`

- Two-proportion z-test A/B testing.
- Gradient Boosting model selection.
- ROAS forecasting and budget recommendations.
- 14-test Pytest suite.

---

### 🎤 [MeetMind AI](https://github.com/Surendra571/MeetMind-AI)

**AI-powered meeting intelligence platform.**

`Python` `FastAPI` `React` `PostgreSQL` `LLMs`

- Streaming speech-to-text and speaker diarization.
- Grounded RAG search across meetings.
- Action-item tracking.

---

### 📄 [PolicyLens AI](https://github.com/Surendra571/policylens-ai)

**Insurance PDF assistant.**

`Python` `LLMs` `RAG`

- Clause extraction from health, motor, life, and travel policies.
- Grounded question answering with citations.
- Plain-language policy explanations.

---

### 🧑‍💻 [AI Communication & Mock Interview Coach](https://github.com/Surendra571/AI-Communication-Mock-Interview-Coach)

**AI-powered interview practice and communication feedback.**

`TypeScript` `FastAPI` `React` `LLMs`

- Voice interaction and response evaluation.
- Structured communication feedback.
- AI-powered mock interview experience.

---

### 🧾 [InvoiceFlow AI — Accounts Payable Agent](ADD_INVOICEFLOW_GITHUB_URL)

**PDF-to-decision financial automation.**

`Python` `LLMs` `pdfplumber` `Streamlit` `SQL`

- Extracts supplier invoice information from PDF documents.
- Produces explainable APPROVED / REVIEW / REJECTED decisions.
- Deterministic validation for duplicate invoices, blocked vendors, PO mismatches, currency mismatches, and line-item arithmetic.
- ±2% PO amount tolerance and 85% minimum extraction confidence.
- Human review for low-confidence cases.
- Separate automated decision and human override audit logs.
- 30+ automated tests.

---

### 💰 [Digital Wallet — Payments & Ledger Backend](ADD_WALLET_GITHUB_URL)

**Concurrency-safe payment processing and double-entry accounting.**

`Python` `Django REST Framework` `PostgreSQL` `Redis` `Celery` `React` `Docker`

- Registration, JWT authentication, bank-account linking, and merchant wallets.
- Wallet-to-wallet transfers.
- Double-entry ledger with equal debit and credit entries.
- Atomic database transactions and Decimal-based financial calculations.
- Idempotency keys to prevent duplicate transfers.
- Configurable daily, monthly, and per-transfer limits.
- CI, Docker, Kubernetes, Prometheus, and Grafana monitoring.
- 30+ automated tests.

## 🛠️ Tech Stack

**Languages:**  
Python • SQL • JavaScript • TypeScript

**Backend:**  
FastAPI • Django • Django REST Framework • REST APIs • WebSockets • SQLAlchemy • Pydantic

**AI & Agents:**  
OpenAI API • Gemini API • LangGraph • LangChain • CrewAI • Hugging Face • PyTorch • Scikit-learn • TensorFlow

**LLM & Retrieval:**  
RAG • Embeddings • FAISS • Qdrant • Sentence Transformers • Structured Outputs

**Finance Automation:**  
Bank Reconciliation • Double-Entry Ledgers • Invoice Processing • Payment Systems • Maker-Checker Controls • Audit Trails

**Evaluation:**  
DeepEval • RAGAS • LLM-as-Judge • MLflow

**Databases & Queues:**  
PostgreSQL • SQLite • Redis • Celery • DuckDB

**Engineering & Testing:**  
Docker • Git • GitHub Actions • Pytest • Property-Based Testing • CI/CD

**Frontend:**  
React • TypeScript • Streamlit

**Cloud:**  
AWS • Azure • Oracle Cloud • Vercel • Render

## 🎓 Education & Certifications

**Master of Business Administration (MBA), Finance**  
St. John's College of Engineering and Technology | 2024–2026

**B.Sc. Computer Science (AI/ML Specialization)**  
Vyshnavi Degree College | 2019–2023

**Certifications:**

- Oracle Cloud Infrastructure — Generative AI Professional
- AWS — Cloud Practitioner
- DeepLearning.AI — Generative AI with LLMs
- HackerRank — SQL and Python (Intermediate)

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Surendra571&show_icons=true&theme=vue-dark&hide_border=true&include_all_commits=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Surendra571&layout=compact&theme=vue-dark&hide_border=true" width="48%" />
</p>

---

## 📫 Connect

<p align="center">
  <a href="https://www.linkedin.com/in/surendra571">LinkedIn</a> •
  <a href="https://surendra571.itsfolio.tech/">Portfolio</a> •
  <a href="https://github.com/Surendra571">GitHub</a> •
  <a href="mailto:ksurendraa1.4@gmail.com">Email</a>
</p>

<p align="center">
  <i>Build. Verify. Ship. Measure. Improve.</i>
</p>
