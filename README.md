# Awesome-Legal

## Legal AI Agents Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Agents for Legal Workflows*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **legal AI agents** — autonomous or semi-autonomous systems that handle research, drafting, contract analysis, due diligence, case workflows, and multi-step legal tasks.

**Examples** include Harvey and Legora (the category leaders). Tools listed here emphasize **agentic capabilities** (reasoning loops, tool use, workflow orchestration, RAG grounding, custom agents) rather than simple chatbots.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Platforms (Full Legal AI Agents / Operating Systems)

- **[Harvey](https://www.harvey.ai/)**  
  Leading generative AI platform built for law firms and in-house teams. Offers legal research with citations, memo drafting, contract analysis, and a **custom AI Agent Builder** for repeatable workflows (due diligence, litigation prep, etc.). Trained on legal data with RAG. Used by AmLaw 100 firms.

- **[Legora](https://legora.com/)** (formerly Leya)  
  Collaborative AI workspace for lawyers. Agentic tools for document review (tabular analysis), research (with web search), drafting (Word add-in), and team collaboration. Focuses on precision, citations, and enterprise workflows. Recently raised $550M (valuation ~$5.55B) and expanding aggressively in the US.

- **[Spellbook](https://www.spellbook.legal/)**  
  Microsoft Word-native AI copilot for transactional lawyers. Features clause drafting/redlining, risk flagging, market benchmarking, and **Spellbook Associate** — a true multi-step AI agent that executes complex projects (e.g., full due-diligence packages from a term sheet). Over 4,000 legal teams use it.

### Enterprise & Research-Focused Agents

- **[CoCounsel](https://www.casetext.com/cocounsel)** (Thomson Reuters)  
  AI legal assistant with deep Westlaw integration. Handles research, document review, contract analysis, and playbooks. Strong for litigation and research-heavy workflows.

- **[Luminance](https://luminance.com/)**  
  AI agent specialized in contract review and M&A due diligence. Analyzes agreements against historical data, flags risks/outliers, and generates red-flag reports.

- **[Lexis+ AI](https://www.lexisnexis.com/en-us/products/lexis-plus.page)** (LexisNexis)  
  Generative AI layered on the Lexis research platform. Agentic research, drafting, and analysis with authoritative citations.

### Specialized & Workflow Agents

- **[Clio AI](https://www.clio.com/)**  
  Embedded AI agent inside Clio Manage (practice management). Summarizes cases, tracks deadlines, extracts court dates, logs time, and automates admin tasks.

- **[EvenUp](https://www.evenup.io/)**  
  AI agent purpose-built for personal injury law. Automates demand letter drafting and case valuation with high ROI for high-volume practices.

- **[GC AI](https://www.gcai.com/)** (or similar in-house platforms)  
  Workspace combining legal research, contract review, and collaboration tools tailored for corporate legal departments.

- **[Activepieces](https://www.activepieces.com/)**  
  No-code/low-code platform to **build custom legal AI agents**. Connects LLMs, internal systems, and tools for intake automation, deadline tracking, document routing, etc. Self-hostable option available.

- **[Kira Systems](https://www.kirasystems.com/)** (by Litera)  
  Contract intelligence platform with AI clause extraction and due-diligence agents. Popular for large-scale M&A and compliance reviews.

**Other notable mentions**: Ironclad (contract lifecycle), Juro (AI contract management), Lawmatics (client-intake agents), Gavel (document automation agents), Vincent AI (Clio ecosystem).

## Open-Source GitHub Projects

### Dedicated Legal AI Agent Projects

- **[OpenContracts](https://github.com/Open-Source-Legal/OpenContracts)**  
  Self-hosted platform where **humans and configurable AI agents** build legal knowledge bases together. Features document annotation, version control, semantic search, and MCP-compatible agents that can reason over contracts, regulations, and policies.  
  **Tech**: Django + TypeScript, Docker, vector embeddings, PydanticAI (Claude/Cursor integration).  
  **License**: AGPL-3.0 | Stars: ~1.2k | [Demo](https://contracts.opensource.legal)

- **[LawGlance](https://github.com/lawglance/lawglance)**  
  Free, RAG-based AI legal assistant focused on making law accessible. Answers questions with citations from major statutes (currently strong on Indian law; expandable).  
  **Tech**: LangChain + ChromaDB + OpenAI + Streamlit/Django.  
  **License**: Apache-2.0 | Perfect for self-hosting or customization.

- **[AiLegalAgent](https://github.com/BTheCoderr/AiLegalAgent)**  
  OpenAI-powered agent for automating custody, criminal, and family-law case workflows. Designed to help self-represented litigants and pro bono attorneys (initial focus: MA/RI/CT jurisdictions).

- **[ai-legal-agent](https://github.com/aepel/ai-legal-agent)**  
  Flexible LangChain-based legal agent for research, document analysis, and client advisory. Supports multiple LLMs (Gemini, OpenAI, Langbase).

- **[LawAgent](https://github.com/AI-Hub-Admin/LawAgent)**  
  Curated awesome list of legal AI agents, tools, and resources (great starting point for discovery).

### Frameworks Commonly Used for Legal Agents
General agent frameworks (LangGraph, Auto-GPT forks, CrewAI, etc.) are frequently adapted for legal use via custom RAG on case law/contracts. See the [500-AI-Agents-Projects](https://github.com/ashishpatel26/500-AI-Agents-Projects) repo for legal-specific examples and templates.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Always verify data privacy, security certifications (SOC 2, HIPAA, etc.), and jurisdictional compliance.
- AI agents are powerful tools but **not substitutes** for licensed legal advice.

---

**Made for lawyers, legal tech builders, and AI enthusiasts.**  
Let's make legal work faster, smarter, and more accessible.