# Hi, I'm Srikanth 👋
 
**Principal Product Manager | Multi-Agent AI Systems | Enterprise Platforms | 15+ Years Building 0→1 at Scale**
 
I'm a product leader who believes the best PMs are technical enough to build, strategic enough to influence executives, and hands-on enough to ship. I design and build multi-agent AI systems, enterprise data platforms, and real-time infrastructure products that deliver measurable business impact.
 
Currently driving AI product strategy at **Microsoft** (Teams Platform). Previously built enterprise data ecosystems at **Starbucks** serving 200+ data scientists globally.
 
---
 
## 🎯 What I Do
 
- **🤖 Build Multi-Agent AI Systems**: Designing Accomplice & Gauntlet — a dual-agent system with structurally enforced ideation/adversarial boundary, federated PM Memory, and pluggable offline LLM backend
- **⚡ Ship Production AI**: Two production AI agents at Microsoft — incident classifier (Claude API, 5–7 days → 2 minutes) and real-time ops monitoring agent (Gemini, live event quality at 20K+ concurrent participants)
- **📈 Drive Enterprise Scale**: $14M+ revenue impact, 800K+ enterprise seats protected, 9+ organizations aligned simultaneously
- **🏗️ Platform Thinking**: 0→1 data platforms serving 200+ data scientists at 75% daily active adoption; MLOps pipelines at 92% production accuracy
---
 
## 🚀 Featured Projects
 
### ⭐ [Accomplice & Gauntlet](https://github.com/sjaligam-MS/accomplice-gauntlet) *(in active development)*
 
**Dual-agent system for product managers — structurally enforced ideation + adversarial review**
 
- **Architecture**: Accomplice (divergent ideation) and Gauntlet (adversarial review) with a hard structural boundary — neither agent can perform the other's role, enforced architecturally not by convention
- **Gauntlet**: Fans out across 12+ adversarial review lenses — governance, compliance, data/telemetry, responsible AI, reliability, engineering feasibility, GTM, competitive — each returning structured findings with severity and go/hold/no-go verdict
- **PM Memory Layer**: Federates from 6 upstream source types — meeting intelligence, signal clustering, org knowledge, incident history, telemetry, service catalog — with provenance tagging (verified vs. inferred) and quality grading before reaching any agent
- **Offline-capable**: Pluggable model backend; single-shot and conversational ideation modes; Hardener stage synthesizes cross-lens conflicts into backlog-ready specs
- **Tech Stack**: Python, Claude API, multi-agent orchestration, federated memory architecture
```
# What it does in one line:
PM idea → Accomplice ideates → Gauntlet stress-tests across 12+ lenses → Backlog-ready spec
```
 
**Why this matters**: This isn't a wrapper around an LLM. It's an opinionated multi-agent architecture with structural boundaries, federated memory, and adversarial review — built by a PM who understands the difference between a demo and a system.
 
---
 
### 🔥 [ICM Incident Classifier + Townhall Support Agent](https://github.com/sjaligam-MS/Townhall_Incident_Analyzer)
 
**Two production AI agents covering the full incident lifecycle at Microsoft**
 
- **ICM Classifier**: Defined inference architecture and prompt engineering framework using Claude API; owned 8-metric evaluation framework (classification confidence, false-positive rate, false-negative rate, escalation trigger accuracy, latency P50/P95, human review rate) before any production traffic
- **Impact**: Reduced incident triage from 5–7 days to 2 minutes across 100–150 monthly incidents — org-wide production deployment, not a pilot
- **Model Selection**: Claude over GPT-4 for classification reliability and audit trail traceability
- **Townhall Support Agent**: Gemini Flash — agentic orchestration pattern: continuous telemetry ingestion → quality signal detection → threshold evaluation → automated incident report generation during live events at 20K+ concurrent participants
- **Combined system**: Classifier handles async triage, monitoring agent handles live event ops — full incident lifecycle covered
- **Tech Stack**: Python, Claude API, Gemini API, REST API integration, pandas, openpyxl, python-pptx
```
# What it does:
Live event telemetry → Quality signal detection → Auto-drafted incident report before customer escalation
100–150 monthly incidents → AI classification → 2-minute triage (was 5–7 days)
```
 
---
 
### 📊 [Movie Recommendation Engine](https://github.com/sjaligam-MS/Movie_Recommendation_Bot)
 
**Semantic search using Gemini 2.0 Flash + RAG + FAISS vector indexing**
 
- **Goal**: Understand how modern AI recommendation products actually work from the inside
- **Tech Stack**: Google Gemini 2.0 Flash, FAISS, RAG architecture, few-shot prompting, collaborative filtering, content-based filtering
- **Key Insight**: Built to explore vector search, embeddings, and LLM reasoning at the application layer
- **Product Thinking**: Integrated OTT/affiliate monetization model into the architecture
```
# Natural language query example:
"Suspenseful thrillers with strong female leads" → Vector search → Ranked recommendations
```
 
---
 
## 💼 Professional Background
 
**Current**: Senior Product Manager @ **Microsoft** — Teams AI & Media Platform
 
- Authored FY2027 Media Convergence strategy aligning 9+ organizations into single architectural direction
- Shipped 1080p streaming for 20K+ concurrent participants (sub-2s P90 latency, protected $14M revenue)
- Built COGS and pricing framework: unlocked $14M opportunity, prevented $7.9M revenue loss
- Shipped two production AI agents: incident classifier (Claude API) + real-time monitoring agent (Gemini)
**Previous**: Product Manager @ **Starbucks** — Enterprise Data Platforms
 
- Built 360 Data Suite from zero: governed data layer for Marketing, Operations, Finance globally
- Owned MLOps pipeline on Azure ML: 92% forecast accuracy in production
- Architected Identity Stitching framework using MDM principles across 7 source systems
- Drove 200+ data scientists to 75% daily active adoption through embedded delivery strategy
**Earlier**: Technical Product Manager @ **Lamb Weston** — ERP & Supply Chain
 
- Owned order management workflows for global accounts (McDonald's, IHOP)
- Directed ERP system transitions for acquired companies globally
---
 
## 🧰 Tech Stack
 
**Languages**:
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
 
**AI / Agent Systems**:
![Claude](https://img.shields.io/badge/-Claude%20API-000000?style=flat)
![Gemini](https://img.shields.io/badge/-Google%20Gemini-4285F4?style=flat&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Azure ML](https://img.shields.io/badge/-Azure%20ML-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
 
**Data & MLOps**:
![Databricks](https://img.shields.io/badge/-Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![FAISS](https://img.shields.io/badge/-FAISS-blue?style=flat)
![pandas](https://img.shields.io/badge/-pandas-150458?style=flat&logo=pandas&logoColor=white)
 
**Builder Tools**:
![Cursor](https://img.shields.io/badge/-Cursor-000000?style=flat)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
 
---
 
## 🧠 Currently Building & Learning
 
- **Accomplice & Gauntlet**: Multi-agent orchestration with structural boundaries, federated memory, and adversarial review pipelines
- **Eval frameworks at scale**: Designing multi-metric evaluation systems for production AI — confidence thresholds, false-positive tolerance, human escalation triggers
- **Agentic memory architectures**: Federated PM Memory with provenance tracking (verified vs. inferred signals)
- **Offline-capable LLM pipelines**: Pluggable model backends for enterprise deployment constraints
---
 
## 💡 Product Philosophy
 
> *"The best PMs are technical enough to design the architecture, strategic enough to influence the C-suite, and hands-on enough to ship. Knowing which mode to be in — and when to switch — is the actual skill."*
 
**What I believe**:
- ✅ Production > Pilot
- ✅ Evaluation frameworks > Vibes-based launches
- ✅ Structural boundaries > Convention-based constraints
- ✅ Provenance-tracked memory > Hallucinated context
- ✅ Ship and iterate > Wait for perfect
---
 
## 📫 Let's Connect
 
- 💼 **LinkedIn**: [linkedin.com/in/srikanthjaligam](https://www.linkedin.com/in/srikanthjaligam/)
- 📧 **Email**: srikanth.jaligam@gmail.com
- 🌐 **Location**: Seattle, WA (Open to remote)
- 💻 **GitHub**: You're already here
---
 
*Building multi-agent AI systems. Shipping things that run in production. Learning in public.*
 
