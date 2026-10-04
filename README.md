<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1400&color=00D9FF&center=true&vCenter=true&width=760&height=50&lines=Lead+AI+Architect+%26+Fractional+CTO;Multi-agent+systems+%C2%B7+RAG+%C2%B7+MCP+%C2%B7+AI+security;From+architecture+to+production" alt="Lead AI Architect and Fractional CTO. Multi-agent systems, RAG, MCP, AI security." />

**I design and build production AI systems end to end: the architecture, the code, the security and the tests that prove they work.**

This page is the technical evidence behind my [website](https://nicchin.com) and CV. Every project below links to the code, the benchmark or the write-up.

**Hiring a Lead AI Architect, or need a fractional CTO?** [LinkedIn](https://www.linkedin.com/in/nic-chin) · [Email](mailto:nic.chin@nicchin.com)

</div>

---

## 📈 Track record

<div align="center">

| 🏗️ 13+ production AI systems | 🤖 20-agent ensemble | 👥 Led a 15-person team |
|:---:|:---:|:---:|
| Delivered and running | 38,319 predictions scored against real outcomes | Architecture to production |

| 💰 $350K seed raised | 🌐 15K+ users | 🎓 Microsoft, Google & IBM |
|:---:|:---:|:---:|
| SculptAI | TAU Mine | AI certified |

</div>

🎤 **Speaker**: TechStars Startup Week · DeFi Summit London · LevelUP KL

---

## 🔥 What I've built, and how

<table>
<tr>
<td width="50%" valign="top">

### 🔌 Tools for AI agents (MCP)
**SystemAudit MCP server.** Ask Claude or Cursor "is this codebase safe?" and get a straight answer in seconds, from a tool I built that is listed in Claude's connector directory.

<sub>**Under the hood:** remote MCP server, three read-only tools. No model call: every figure comes from a deterministic scan, with files read stated.</sub>

[![Connect](https://img.shields.io/badge/MCP-Connect-191919?style=flat-square&logo=modelcontextprotocol&logoColor=white)](https://systemaudit.dev/mcp)
[![Claude directory](https://img.shields.io/badge/Claude-Connector_directory-D97757?style=flat-square&logo=claude&logoColor=white)](https://claude.ai/directory/systemaudit)

</td>
<td width="50%" valign="top">

### 📄 Answers from documents, with sources
**DocsFlow, now SureCiteAI.** A private AI assistant for a company's own documents that shows the source behind every answer. Tested on 297 questions without inventing a single source.

<sub>**Under the hood:** hybrid retrieval with rank fusion, four tenant-isolation layers, four-model failover, abstention when evidence is weak. **0 hallucinated citations** in 297 benchmark cases.</sub>

[![Repo](https://img.shields.io/badge/Repo-docsflow-181717?style=flat-square&logo=github)](https://github.com/nicuk/docsflow)
[![Benchmark](https://img.shields.io/badge/Benchmark-297_cases-2EA043?style=flat-square)](https://github.com/nicuk/docsflow/blob/main/BENCHMARKS.md)
[![Live](https://img.shields.io/badge/Live-sureciteai.com-00D9FF?style=flat-square)](https://sureciteai.com)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 Many agents, one decision
**AI NeuroSignal.** Twenty AI agents with different strategies read the markets, and the system learns which ones to trust by checking every call against what really happened. Over 38,000 predictions tracked live.

<sub>**Under the hood:** parallel LLM calls with schema validation; deterministic voting that abstains on disagreement; 38,319 predictions scored against outcomes.</sub>

[![Live record](https://img.shields.io/badge/Live_record-public_API-5433FF?style=flat-square)](https://aineurosignal.com/api/public/edge)
[![Methodology](https://img.shields.io/badge/Methodology-aineurosignal.com-5433FF?style=flat-square)](https://aineurosignal.com/methodology)

</td>
<td width="50%" valign="top">

### 🛡️ Security of AI-built software
**I studied 53 apps built with AI tools** like Lovable, Cursor and Claude Code. One in five had their passwords and keys committed to the code, and nearly three in four had no automatic security checks at all. AI makes apps fast to build, not safe to launch; this shows exactly where they break, with a checklist to fix it.

<sub>**Under the hood:** deterministic scan with no AI model in the loop, every credential finding checked by hand, anonymised dataset published. Citable via DOI.</sub>

[![Research](https://img.shields.io/badge/Research-53_repos-8957E5?style=flat-square)](https://github.com/nicuk/ai-built-app-production-readiness-checklist)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.23094508-1682D4?style=flat-square)](https://doi.org/10.5281/zenodo.23094508)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🪨 Checking what AI says it did
**Cairn, three Claude Code plugins.** AI coding assistants often say "fixed" when they haven't. These plugins check the AI's work, so a team can trust what it reports. Free and open source.

<sub>**Under the hood:** a script locates, the model judges. Every check has a self-test that plants a defect, run in CI. Results published, including a null.</sub>

[![Repo](https://img.shields.io/badge/Repo-cairn--principles-181717?style=flat-square&logo=github)](https://github.com/nicuk/cairn-principles)
[![Evidence](https://img.shields.io/badge/Evidence-EVIDENCE.md-2EA043?style=flat-square)](https://github.com/nicuk/cairn-principles/blob/main/EVIDENCE.md)

</td>
<td width="50%" valign="top">

### 🔍 Understanding any codebase
**SystemAudit.** Paste a GitHub link and get a plain-English health report on any codebase in under three minutes: the kind of review that usually takes a consultant weeks.

<sub>**Under the hood:** open-source scanner engine (dependencies, import graph, health scoring) feeding a multi-pass AI layer. Findings carry file-and-line evidence.</sub>

[![Repo](https://img.shields.io/badge/Repo-systemaudit-181717?style=flat-square&logo=github)](https://github.com/nicuk/systemaudit)
[![Live](https://img.shields.io/badge/Live-systemaudit.dev-7C3AED?style=flat-square)](https://systemaudit.dev)

</td>
</tr>
</table>

---

## 💼 Client work

| Project | What it did for the client |
|:--|:--|
| **AI Marketing Intelligence Platform** | Five AI tools under one supervisor agent run a creative business's marketing: writing in the owner's voice, finding leads and drafting replies. Saves 15–20 hours a week and is in daily use. |
| **AI legal document analyser** | Lawyers review 150–200-page fund agreements in minutes instead of 4–6 hours, without leaving Microsoft Word. |
| **Enterprise pharma AI security** | Took an AI platform for pharmaceutical manufacturers from prototype to enterprise pilot approval in 7 weeks, passing all 24 acceptance criteria. |
| **IoT utility platform, Germany** | Multi-tenant billing and device management connected to five metering companies' platforms, led as fractional CTO. |

All 13 production systems, with architecture and screenshots: [nicchin.com/portfolio](https://nicchin.com/portfolio)

---

## 🧭 How I build

<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/how-i-build-stacked-dark.svg">
    <source media="(max-width: 600px)" srcset="assets/how-i-build-stacked-light.svg">
    <source media="(prefers-color-scheme: dark)" srcset="assets/how-i-build-dark.svg">
    <img src="assets/how-i-build-light.svg" width="100%" alt="Rules and checks feed evidence to an AI layer, which abstains if unsure; only what passes verification reaches production, and every production failure becomes a new rule.">
  </picture>
</p>

<details>
<summary><b>For technical reviewers: decisions worth asking me about</b></summary>

<br/>

| Decision | Where | Why |
|:--|:--|:--|
| Pinecone namespaces over pgvector | DocsFlow | Namespace-per-tenant maps directly onto isolation; no shared index to filter wrongly. |
| Abstain below a confidence threshold | DocsFlow | A refusal costs less than a confident wrong citation. Calibration is reported as ECE, Brier and AUROC. |
| Publish the hard benchmark | DocsFlow | CUAD legal scores 49% and FinanceBench passes at 63% (with 96% retrieval hit). A public hard corpus says more than 100% on an internal one. |
| No model in the MCP path | SystemAudit MCP | An agent acting on a figure needs the same figure every time. |
| Script locates, model judges | Cairn | The script makes checks repeatable at scale; the model supplies judgement a pattern can't. |
| Gate claims against the best naive baseline | AI NeuroSignal | 53% beats a coin flip but not "always short" by enough, so the system publishes no skill claim. |
| Measure a mechanism before tuning it | AI NeuroSignal | Replaying stored votes showed Elo-style weighting reversed the majority once in 5,125 signals, so ratings should choose who votes rather than reweight votes. |
| Keep best-effort writes out of the source-of-truth transaction | AI NeuroSignal | One failing side write silently rolled back a month of agent scoring; the fix separated it and made it fail loudly. |
| Supabase job queue over Redis | DocsFlow | Row-level security applies to jobs too, and there is one data layer to secure. |

More: [eleven case studies and five architecture decision records](https://github.com/nicuk/ai-architecture-portfolio), and the [Cairn plugin repos](https://github.com/nicuk/cairn-principles#the-plugins) for [memory](https://github.com/nicuk/claude-md-memory-architecture), [AI signals](https://github.com/nicuk/llm-silent-failure-audit) and [agent claims](https://github.com/nicuk/did-ai-really-fix-it).

</details>

---

## 🛠️ Stack

<div align="center">

**AI & agents**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-5433FF?style=for-the-badge&logo=qwen&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-191919?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge&logo=crewai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)

**Languages & backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)

**Frontend & cloud**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

</div>

---

## 📬 Contact

Looking for **AI architecture, multi-agent systems, or fractional CTO leadership**?

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nic--chin-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/nic-chin)
&nbsp;
[![Website](https://img.shields.io/badge/Website-nicchin.com-00D9FF?style=for-the-badge)](https://nicchin.com)
&nbsp;
[![Email](https://img.shields.io/badge/Email-nic.chin@nicchin.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nic.chin@nicchin.com)

</div>
