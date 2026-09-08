<div align="center">

# Hi, I'm Ahmed Walid Bouanzoul 👋

### AI Engineer in the making — LLMs · RAG · Agentic Systems

**M2 Systèmes Intelligents @ Sorbonne Université · Paris**

<br>

<a href="YOUR_LINKEDIN_URL">
  <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="YOUR_EMAIL">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br><br>

> **Building, evaluating and deploying reliable AI systems — beyond the prompt.**

<br>

🟢 **OPEN TO WORK — 6-MONTH PFE INTERNSHIP · JAN/FEB 2027**

</div>

---

## About Me

I'm a **Master's student in Intelligent Systems at Sorbonne Université**, focused on building reliable systems around **Large Language Models**.

My interests sit at the intersection of:

**LLMs → RAG → Agents → Evaluation → Deployment**

I don't just experiment with prompts.

I like understanding what happens underneath — how information is retrieved, how agents decide which tools to use, how systems behave when they fail, and how to evaluate and monitor them once they leave the notebook.

My background in **electronics and automation (Licence EEA)** also shaped the way I approach AI:

> **Measure it. Validate it. Understand its failure modes. Then ship it.**

Currently looking for a **6-month end-of-studies internship (PFE)** starting **January/February 2027**, in **LLM Engineering, RAG, Agentic AI, Generative AI or AI Engineering**.

---

## What I Build

<table>
<tr>
<td width="50%">

### 🔎 RAG Systems

Dense, lexical and hybrid retrieval systems.

I care about **retrieval quality, grounding, temporal knowledge and evaluation**, not just connecting a vector database to an LLM.

</td>

<td width="50%">

### 🤖 Agentic Systems

Multi-agent and tool-using architectures.

Exploring **LangGraph, ReAct, tool orchestration and explicit evaluation** rather than black-box agent behavior.

</td>
</tr>

<tr>
<td width="50%">

### 🧠 LLM Applications

Fine-tuning and domain-specific applications.

From **QLoRA / Transformers** to API-based deployment and real-world use cases.

</td>

<td width="50%">

### 📊 Evaluation & Observability

Making AI systems measurable.

**RAG evaluation, agent benchmarks, drift detection, monitoring and failure analysis.**

</td>
</tr>
</table>

---

# Featured Projects

## 🤖 AgentForge

### Production-oriented Multi-Agent LLM System

An end-to-end system combining **Advanced RAG, multi-agent orchestration, evaluation and fine-tuning**.

**Architecture**

`User → RAG → LangGraph Agents → Tools → LLM → Evaluation`

**Highlights**

- Advanced RAG pipeline using **Qdrant**
- Multi-agent orchestration with **LangGraph**
- RAG evaluation with **RAGAS**
- **QLoRA fine-tuning** on Mistral 7B
- FastAPI + Docker deployment
- Tested across **legal, finance and technical** use cases
- Fine-tuned model published on Hugging Face

**Evaluation**

`RAGAS: 1.0` · `Eval Loss: 1.4584`

<br>

🔗 **[Explore AgentForge →](YOUR_AGENTFORGE_URL)**

---

## 🚗 GarageMind

### Agentic Vehicle Diagnostic Copilot

An AI diagnostic system combining **LLM agents, hybrid RAG, CAN-bus analysis and anomaly detection**.

The core is a **LangGraph ReAct agent** capable of orchestrating diagnostic tools for:

- Repair-case retrieval
- DTC / VIN decoding
- CAN log analysis
- Agentic troubleshooting

**Retrieval**

`Dense Retrieval + BM25 → RRF Fusion → Context`

**Evaluation**

- 15 adversarial scenarios
- 93% tool-selection accuracy
- 100% citation grounding
- 100% correct rejection of trap questions

The project also compares a **LSTM Autoencoder** against an **Isolation Forest** baseline for CAN-bus anomaly detection — including cases where the simpler baseline performs better.

> I believe good AI engineering also means documenting when the "fancier" model loses.

<br>

🔗 **[Explore GarageMind →](YOUR_GARAGEMIND_URL)**

---

## 📈 FinSentinel

### Financial Sentiment Analysis · MLOps · Model Monitoring

A French financial sentiment classifier built with **CamemBERT**, deployed with a complete production monitoring stack.

**Pipeline**

`Data → CamemBERT → FastAPI → Docker → MLflow → Prometheus → Grafana`

**Highlights**

- CamemBERT fine-tuning
- F1 score: **0.776**
- FastAPI inference service
- Dockerized deployment
- MLflow experiment tracking
- Prometheus monitoring
- 12-panel Grafana dashboard
- PSI-based drift detection
- Controlled drift experiment

The project also investigates model limitations such as:

- Majority-class bias
- Prediction drift vs input drift
- Behavior under controlled distribution changes

<br>

🔗 **[Explore FinSentinel →](YOUR_FINSENTINEL_URL)**

---

## 🕒 TempoRAG

### Temporal Retrieval-Augmented Generation

A RAG system designed around a problem often ignored in standard RAG pipelines:

> **What happens when the knowledge itself changes over time?**

**Pipeline**

`RSS → Temporal Parsing → Retrieval → Agent → Contradiction Detection`

Includes:

- RSS ingestion
- Temporal information extraction
- LangGraph retrieval agent
- Knowledge drift handling
- Contradiction detection
- Cross-source temporal reasoning

The goal is to explore how RAG systems can remain reliable when sources evolve and information becomes contradictory.

<br>

🔗 **[Explore TempoRAG →](YOUR_TEMPORAG_URL)**

---

## 🖼️ Panoptic Segmentation

### Academic Project · Master's Coursework

Computer vision project combining:

- **Mask R-CNN** for instance segmentation
- **DeepLabV3+** for semantic segmentation
- Panoptic segmentation pipeline

A project from my Master's coursework exploring deep learning for image understanding.

<br>

🔗 **[Explore Project →](YOUR_PANOPTIC_URL)**

---

# Tech Stack

<div align="center">

### LLM / Generative AI

`LangChain` `LangGraph` `Qdrant` `RAGAS` `QLoRA` `Hugging Face` `Transformers`

### Machine Learning

`PyTorch` `Scikit-learn` `CamemBERT` `Deep Learning`

### Backend & Deployment

`Python` `FastAPI` `Docker`

### MLOps & Observability

`MLflow` `Prometheus` `Grafana` `Git`

### Programming

`Python` `SQL` `C/C++` `MATLAB`

</div>

---

# Engineering Interests

```text
                    ┌──────────────────────┐
                    │       LLMs           │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │        RAG           │
                    │ Retrieval & Grounding│
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       AGENTS         │
                    │ Tools & Orchestration│
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     EVALUATION       │
                    │ Benchmarks & Metrics │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      PRODUCTION      │
                    │ Deploy & Monitor     │
                    └──────────────────────┘
