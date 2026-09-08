# Hi, I'm Ahmed Walid Bouanzoul 👋

**AI Engineer in the making — LLMs, RAG & Agentic Systems**

M2 Systèmes Intelligents student at Sorbonne Université (Paris) · Currently looking for a **6-month end-of-studies internship (PFE)**, starting Jan/Feb 2027, in LLM Engineering, RAG, Agentic AI or AI Engineering.

---

## About Me

I build systems around large language models — not just prompts, but the retrieval, evaluation, and monitoring layers that make them reliable enough to ship. My background is in electronics and automation (Licence EEA) before specializing in AI, which pushes me toward treating LLM systems the way I was trained to treat any engineered system: measure it, validate it, document what breaks.

Most of what's below started as a way to learn RAG and agent architectures properly, and turned into four projects I maintain, benchmark, and keep improving.

## What I Build

- **RAG systems** — dense, lexical, and hybrid retrieval, benchmarked against each other rather than assumed
- **Multi-agent systems** — tool-using agents (LangGraph, ReAct) with explicit evaluation harnesses
- **LLM applications** — fine-tuning (QLoRA), deployment (FastAPI/Docker), and sector-specific use cases
- **Evaluation & observability** — drift detection, production monitoring (Prometheus/Grafana), scenario-based agent evaluation
- **ML systems** — from classic baselines to deep learning, compared honestly rather than defaulting to the trendiest model

## Featured Projects

### 🤖 [AgentForge](https://github.com/AhmedWalidbou/AgentForge)
End-to-end multi-agent LLM system: a RAG engine (Qdrant, RAGAS score 1.0), a LangGraph orchestration layer, and a fine-tuned model (QLoRA on Mistral 7B, eval loss 1.4584, published on Hugging Face). Deployed via FastAPI/Docker across 3 distinct sector use cases (legal, finance, technical) to test how far one core stack adapts.

### 🚗 [GarageMind](https://github.com/AhmedWalidbou/GarageMind)
An agentic vehicle diagnostic copilot. A LangGraph ReAct agent orchestrates 4 tools (repair-case retrieval, DTC/VIN decoding, CAN log analysis) — evaluated on 15 adversarial scenarios: 93% tool-selection accuracy, 100% citation grounding (zero hallucinations), 100% of trap questions correctly declined. Underneath: a hybrid dense+BM25 retriever (RRF fusion) over a bilingual repair-case knowledge base, and a CAN-bus anomaly detector (LSTM autoencoder) benchmarked against an Isolation Forest baseline — the baseline wins on some attack types, which is documented rather than hidden.

### 📈 [FinSentinel](https://github.com/AhmedWalidbou/FinSentinel)
French financial sentiment classifier (CamemBERT, F1 0.776, [on Hugging Face](https://huggingface.co/Walid692/finsentinel-camembert)) shipped with a full production monitoring stack: FastAPI, Docker, MLflow, Prometheus, and a 12-panel Grafana dashboard. Includes PSI-based drift detection, validated with a controlled drift experiment — plus two documented findings on the model's own limitations (majority-class bias, prediction-drift vs. input-drift).

### 🕒 [TempoRAG](https://github.com/AhmedWalidbou/TempoRAG)
A temporal RAG pipeline: RSS ingestion, temporal parsing, a LangGraph retrieval agent, and a dedicated contradiction-detection agent for catching conflicting information across sources over time.

### 🖼️ Panoptic Segmentation *(academic project)*
Panoptic segmentation combining instance and semantic prediction (Mask R-CNN, DeepLabV3+), completed as part of my Master's coursework.

## Tech Stack

**LLM / GenAI** — LangChain · LangGraph · Qdrant · RAGAS · QLoRA · Hugging Face Hub
**AI / ML** — PyTorch · Scikit-learn · CamemBERT / Transformers
**Backend** — FastAPI · Docker
**MLOps / Observability** — MLflow · Prometheus · Grafana · Git
**Programming** — Python · SQL · C/C++ · MATLAB

## Currently Looking For

🎯 **6-month end-of-studies internship (PFE)**, starting January/February 2027, ideally converting into a full-time role.

Interested in: LLM Engineering · RAG · Agentic AI · Generative AI · AI Engineering · ML Engineering

## Contact

- 💼 [LinkedIn](https://www.linkedin.com/in/ahmed-walid-bouanzoul-25648328b/)
- 📧 [Ahmed.Walid.Bouanzoul@gmail.com](mailto:Ahmed.Walid.Bouanzoul@gmail.com)
