# Rimjhim AI Kingdom®

> *"Where Knowledge Flows Like Raindrops"*

**One of the world's first navigable agentic AI ecosystems, built solo.**
Founded by **Rimjhim (Rémy) Singh** · Rikanverse® Ltd., London

![Status](https://img.shields.io/badge/status-systems%20online-brightgreen)
![Language](https://img.shields.io/badge/built%20with-Python-blue)
![Focus](https://img.shields.io/badge/focus-Agentic%20AI-purple)

---

## About

Rimjhim AI Kingdom is an AI innovation lab where agentic AI systems are designed, built and deployed from scratch. Every system starts with an architecture (reasoning engine, safety layer, multi-tool orchestration), not just a prompt and an API call.

The ecosystem is presented as a **navigable virtual city**. Each building is a real agentic system. Click a building to see the industry problem it addresses and the solution built for it.

All systems are developed in **Python**, without any no-code or low-code platforms.

---

## The AI City

| District | Building | What it represents |
|---|---|---|
| **Financial District** | Banking Tower | Intelligent banking agent with a six-gate safety system |
| **Property Towers** | Property Towers | Rikanverse® voice-first, multilingual PropTech agent |
| **Hospitality Quarter** | Restaurant Quarter | Hotel and restaurant review automation |
| **Enterprise Zone** | Corporate Office | CRM email assistant for e-commerce customer service |
| **Enterprise Zone** | News HQ | News agent (GPT-4 + Notion) |
| **Knowledge District** | Knowledge Academy and libraries | Published technical writing on reliable AI design |
| **City centre** | Safety HQ | The shared six-gate safety core reused across systems |

### Agent line-up

| Agent | Stack highlights |
|---|---|
| Banking Agent | ReAct · RAG · FCA compliance |
| Property Agent | Voice · FastAPI |
| Doc Assistant | RAG · ChromaDB |
| Review Agent | NLP · GPT-4 |
| Email Agent | n8n · Gmail API |
| News Agent | GPT-4 · Notion |

---

## Flagship Systems

### Banking Agent (Fintech)
- **Need:** Reasoning beyond scripted flows, plus compliance with UK FCA rules and GDPR.
- **Architecture:** Multi-agent **ReAct orchestration engine**. Product and policy questions are answered from retrieved policy documents (RAG). Routine requests such as balance checks and statements are automated.
- **Safety:** Every action passes a **six-gate compliance layer**. For risky actions such as transfers, the agent asks the customer to confirm or clarify depending on its confidence, a human is involved before the action is carried out, and actions can be rolled back.

### Rikanverse® UK PropTech App
- **Need:** UK property search is mostly filter-based, while people ask natural, spoken questions in many languages about Council Tax, tenancy agreements and mortgages.
- **Architecture:** Voice-first, multilingual agent on a **ReAct reasoning loop**. Voice and text run through separate pipelines with their own latency budgets. Session state persists across the conversation.
- **Two-sided marketplace:**
  - **Tenants and buyers** describe their ideal home by voice or text and get matched to Rikanverse listings first, then routed to existing UK property apps with the right filters.
  - **Landlords and agents** register listings by speaking, with no forms, and can ask market questions such as "What rent should I charge?"
- **Beta deployed:** 10 June 2026 (free during closed beta).

### Hotel Review Agent (Hospitality)
A four-layer production pipeline with a strict human-in-the-loop workflow:
1. **NLP layer:** sentiment analysis (92% sentiment accuracy)
2. **Crisis detection:** flags reviews with compliance or reputational risk
3. **Generation layer:** drafts replies in the brand's own voice
4. **Approval dashboard** (FastAPI + React): staff approve every reply before it is published

End-to-end processing takes 2–3 seconds.

### CRM Email Assistant (E-commerce)
- Classifies incoming email by urgency and topic
- Pulls thread history and the customer's CRM record
- Drafts sentiment-matched replies with few-shot learning
- Sends drafts to a review queue for staff approval, escalates critical issues to humans, and logs every action in a GDPR-aligned audit trail

---

## Six Customisation Dimensions

From the research paper *Architecting & Engineering Production-Grade Agentic AI for Industry-Specific Needs*: every system shares one **agentic core** (LLM + tools + orchestration), adapted along six dimensions.

| Dimension | Banking | Property | Hotel Review | CRM Email |
|---|---|---|---|---|
| **Interaction mode** | Text conversation | Voice-first + text; multilingual | Review feed + dashboard | Email inbox + review queue |
| **Knowledge source** | Policy documents (retrieval) | Rikanverse listings; renting guidance | Review text; brand-voice examples | Thread history; CRM record; few-shot examples |
| **Reasoning style** | Multi-agent ReAct loop | ReAct loop with clarifying questions | Four-layer pipeline | Classify-and-draft pipeline |
| **Compliance layer** | Six-gate FCA + GDPR verification | Response checks | Crisis and compliance detection | GDPR data handling; audit trail |
| **Integrations** | Tool orchestration (LangChain) | Listings DB (PostgreSQL); speech interface | Approval dashboard (FastAPI, React) | Email + CRM systems |
| **Automation boundary** | Routine requests automated; risky actions need confirmation and a human | Guidance and listing suggestions automated | Drafts automated; staff approve | Triage and drafts automated; staff approve |

### Design lessons
1. **Start from the industry, not the model.** Regulation, language and brand voice drove the key decisions.
2. **Keep a shared core and customise around it.** Reasoning, tools and orchestration are reused; the rest adapts.
3. **Reuse proven designs across industries.** The review agent and email assistant share one *classify → draft → review* pattern, and banking's gated safety method informs the shared safety core.
4. **Build compliance in from the start.** In regulated industries, compliance belongs in the core, not bolted on at the end.

> Implementation details are withheld because the systems are under commercial development.

---

## Publications

### Agentic AI
- **Singh, R. (2026).** *Architecting & Engineering Production-Grade Agentic AI for Industry-Specific Needs.* International Journal for Multidisciplinary Research.
- **Singh, R. (2026).** *Engineering Reliable Agentic AI: Decision-Making in Real-World Deployments.* International Journal for Multidisciplinary Research, 8(6). [DOI: 10.36948/ijfmr.2026.v08i06.91388](https://doi.org/10.36948/ijfmr.2026.v08i06.91388)

### Forthcoming
- **Fullard, J., Singh, R., & Ventura-Coello, S.** *When the gold standard meets the classroom: Risk of bias and the limits of RCTs in education.* Nature Human Behaviour (in press).

### Machine learning and economics
- **Singh, R. (2024).** *Decoding the Obesity Puzzle in Peru, Colombia, and Mexico.* IJHSSM, 4(6), 409–417. [DOI: 10.5281/zenodo.23871159](https://doi.org/10.5281/zenodo.23871159)
- **Singh, R. (2024).** *The Puzzle of Economic Development.* IJHSSM, 4(6), 252–259. [DOI: 10.5281/zenodo.23866917](https://doi.org/10.5281/zenodo.23866917)
- **Singh, R. (2022).** *Multimarket Contacts with Trade Costs and Distance Cost.* JBMIS, 9(1), 1–4. [DOI: 10.48001/jbmis.2022.0901001](https://doi.org/10.48001/jbmis.2022.0901001)
- **Singh, R. (2022).** *Capital Account Liberalization Debates.* Veethika, 8(4), 16–19. [DOI: 10.48001/veethika.2022.08.04.003](https://doi.org/10.48001/veethika.2022.08.04.003)
- **Singh, R. (2022).** *An Analysis of the Status and Potential of the Delhi Tourism Industry.* JBMIS, 9(2), 1–10. [DOI: 10.48001/jbmis.2022.0902001](https://doi.org/10.48001/jbmis.2022.0902001)
- **Singh, R. (2022).** *Curbing Child Labour is the Da Vinci Code of Economic Development.* Veethika, 8(2), 25–28. [DOI: 10.48001/veethika.2022.08.02.006](https://doi.org/10.48001/veethika.2022.08.02.006)
- **Singh, R. (2021).** *Analyzing the Impact of the Economic Crisis in Greece on the U.S.* JBMIS, 8(2), 18–26. [DOI: 10.48001/jbmis.2021.0802003](https://doi.org/10.48001/jbmis.2021.0802003)

### Books and chapters
- **Singh, R. (2022).** *Puzzles of Labour Economics.* Eliva Press. ISBN 978-9994984879
- **Singh, R., & Singh, R. (2016).** *Sport and Anti-Sport: Big Game Hunting in Jim Corbett's India.* In *Sport, Identity and Community*, Brill. Presented at the University of Oxford. [DOI: 10.1163/9781848884526_005](https://doi.org/10.1163/9781848884526_005)

### Tech articles on Medium
- Designing Reliable AI Systems: My Engineering Approach Across RAG, Agents, and Real-World Workflows
- Why Your AI Project Failed and How to Fix It
- How to Validate AI-Generated Python Code
- I Built One of the World's First Navigable & Interactive Agentic AI Virtual City Experience Web App!
- Tired of Writing Docstrings? GitHub Copilot Has You Covered!

---

## Founder

**Rimjhim (Rémy) Singh**: AI Engineer · Technical AI Product Architect · Economist · Founder of Rikanverse® Ltd., London

- Sole architect and developer of Rimjhim AI Kingdom; has engineered 10+ AI agents
- Specialises in agentic AI, LLM automation, NLP, RAG pipelines and scalable ML systems
- MSc in Behavioural & Data Science, University of Warwick; Master's in Quantitative Economics
- Google Certified AI Professional
- Former Senior AI Engineer at a London-based company, architecting enterprise GenAI workflows for startups in 60+ countries
- Former Assistant Professor; 15+ published research articles
- Economics Honours, Ramjas College, University of Delhi (Overall Rank 1)

> *"AI isn't just about algorithms. It's about impact. Every solution should solve a real problem, deliver measurable value, and unlock new possibilities."*

---
---

<p align="center">
  <b>RIMJHIM AI KINGDOM</b> © 2025 · Built with precision · Powered by curiosity<br>
  © 2026 Rikanverse® Ltd., London
</p>





