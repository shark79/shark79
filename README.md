<h1 align="center">Shashank Jamkhandi</h1>

<p align="center">
  <b>AI Engineer building production agent systems in healthcare.</b><br/>
  <i>Evaluation, reliability, and guardrails that hold.</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sjam"><img src="https://img.shields.io/badge/LinkedIn-sjam-blue?logo=linkedin&logoColor=white" /></a>
  <a href="mailto:shashankjamkhandi@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-red?logo=gmail&logoColor=white" /></a>
  <a href="https://www.npmjs.com/package/@sharkbuilds/job-finder"><img src="https://img.shields.io/npm/v/@sharkbuilds/job-finder?label=npm%20%40sharkbuilds%2Fjob-finder&logo=npm" /></a>
</p>

---

## About

AI Developer at **DocAide.ai**, shipping clinical AI features to physicians: Claude (AWS Bedrock) alongside OpenAI, a RAG pipeline over PGVector, and LLM extraction from clinical notes into structured tables. M.S. Information Technology, Arizona State University (GPA 4.0). Based in Arizona.

What I care about in an AI system is the part that runs after the model answers:

- **Evaluation before shipping.** Answers get scored by an independent judge and gated to Ship or Hold, not trusted because they read well.
- **Claims tied to evidence.** Agents cite sources, and code checks the citations, not the prompt.
- **Failure handling by construction.** Races, retries, and mid-workflow crashes are reproduced in tests and survived.

---

## Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [Harness Eval for RAG Chatbot](https://github.com/shark79/harness-eval-for-rag-chatbot) | Documentation-grounded support bot whose drafts are scored by a separate eval service and gated Ship / Hold, with one bounded correction attempt | Python · Dify · OpenAI |
| [Adversarial Research Panel](https://github.com/shark79/agentic-workflow-claude) | Four research agents that cite every claim and debate each other; citation verification and weight dilution enforced in code with tests | Python · FastAPI · Claude |
| [Agentic Commerce (UCP + Stripe)](https://github.com/shark79/agentic-commerce-ucp) | Shopping agent that checks out through Google's Universal Commerce Protocol and pays with a Stripe Shared Payment Token, so the merchant never sees the card | TypeScript · Express · Next.js |
| [Multi-Model Agent Dev Team](https://github.com/shark79/MultiAgent-Organization) | Five agents on five open-weight models with separate permissions; the QA and adversary agents can't fix code, devs can't close their own defects | OpenCode · OpenRouter |
| [Job Finder](https://github.com/shark79/job-finder) | Published MCP server: cross-references DOL H1B filings with live postings and tailors a resume per role | JavaScript · MCP · npm |
| [Reservation System with Failure Handling](https://github.com/shark79/Reservation-System-Failure-Handling) | Seat booking on durable actors that survives seat races, double-charge retries, and crash-mid-workflow, each proven by a test; MCP seat-map widget | Python · Reboot · React |

---

## Experience

**AI Developer · DocAide.ai** *(June 2025 – Present)*
- Integrated Claude via AWS Bedrock alongside OpenAI across 2 clinical AI features, with hybrid retrieval over embeddings and structured records
- Owned the core RAG pipeline and root-caused 3 Critical clinical-accuracy defects, including fabricated symptoms and incomplete medication lists
- Cut clinical note generation latency by **60%** (40s → 15s) by parallelizing post-transcription steps

**Sustainable AI Innovation Assistant · Arizona State University** *(Dec 2024 – May 2025)*
- Built and deployed a [Streamlit simulator](https://github.com/shark79/Simulator) modeling energy, cost, and CO₂ tradeoffs for AI data centers

---

## Stack

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-000000?logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?logo=anthropic&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

**Cloud & Tools**

![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
