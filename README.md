# Hi, I'm Srikanth 👋
 
**Principal Product Manager | Multi-Agent AI Systems | Enterprise Platforms | 15+ Years Building 0→1 at Scale**
 
I'm a product leader who believes the best PMs are technical enough to build, strategic enough to influence executives, and hands-on enough to ship. I design and build multi-agent AI systems, enterprise data platforms, and real-time infrastructure products that deliver measurable business impact.
 
Currently driving AI product strategy at **Microsoft** (Teams Platform). Previously built enterprise data ecosystems at **Starbucks** serving 200+ data scientists globally.
 
---
 
## 📊 Impact at a Glance
 
| $14M+ | 800K+ | 9+ | 3 | 20K+ | 200+ |
|---|---|---|---|---|---|
| Revenue Generated | Enterprise Seats Protected | Orgs Aligned | Production AI Agents | Concurrent Users | Data Scientists Served |
 
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
 
### 🏗️ [GC Cost Estimator](https://github.com/sjaligam-MS/GC_Cost_Estimator)
 
**Parametric cost estimator for residential general contractors — deterministic, auditable, human-in-the-loop**
 
- **Problem**: Low-to-mid volume residential GCs need rough-order-of-magnitude pricing before drawings exist — existing AI takeoff tools (Togal, Kreo, Handoff AI) require drawings that don't exist at this stage
- **Approach**: Parametric/conceptual estimating — matches new projects against comparable historical SOVs using weighted similarity scoring across project inputs (sqft, bed/bath, garage, levels, foundation type)
- **Cost buildup**: Per CSI division (Concrete, Framing, Roofing, Windows & Doors, Finishes, Casework, Plumbing, HVAC, Electrical, Site/Earthwork) normalized as % of total cost — survives small historical samples better than flat $/sqft
- **Output**: Range, not point estimate — total cost range, derived $/sqft, division-by-division breakdown, each tagged with confidence level (high/medium/low) based on input correlation
- **Design principle**: Deterministic, not generative — core matching and cost math is rules-based arithmetic, fully auditable; contractor's proprietary cost data stays in their environment
- **Tech Stack**: Python, HTML interactive prototype, parametric matching algorithms
```
# What it does:
Project inputs (sqft, beds, garage, levels) → Comparable project matching → 
CSI division cost breakdown with confidence flags → ROM range estimate
```
 
**Why this matters**: Built for a real contractor solving a real pre-drawings pricing problem. Shows product thinking: range over false precision, confidence shown per division, human-in-the-loop by design — not a black-box number generator.
 
---
 
### 🎬 [Movie Recommendation Engine](https://github.com/sjaligam-MS/Movie_Recommendation_Bot)
 
**Semantic search using Gemini 2.0 Flash + RAG + FAISS vector indexing**
 
- **Goal**: Understand how modern AI recommendation products work from the inside
- **Tech Stack**: Google Gemini 2.0 Flash, FAISS, RAG architecture, few-shot prompting, collaborative filtering, content-based filtering
- **Product Thinking**: Integrated OTT/affiliate monetization model into the architecture
```
"Suspenseful thrillers with strong female leads" → Vector search → Ranked recommendations
```
 
---
 
### 📋 [PM Frameworks](https://github.com/sjaligam-MS/pm-frameworks) *(in progress)*
 
**Battle-tested templates from shipping products at Microsoft & Starbucks**
 
- PRD templates (technical, consumer, 0→1)
- Prioritization frameworks (Impact Score Model, Tech Debt vs Features)
- OKR definition and tracking frameworks
- Evaluation frameworks for AI product quality (accuracy, latency, confidence thresholds)
- Stakeholder templates (Business cases, RFCs, Launch checklists)
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
 
## 📫 Let's Connect
 
- 💼 **LinkedIn**: [linkedin.com/in/srikanthjaligam](https://www.linkedin.com/in/srikanthjaligam/)
- 📧 **Email**: srikanth.jaligam@gmail.com
- 🌐 **Location**: Seattle, WA (Open to remote)
---
 
*Building multi-agent AI systems. Shipping things that run in production. Learning in public.*
 
