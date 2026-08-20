# 👋 Hi, I'm Miguel Yu (余均浩)

🎓 Dual Bachelor in **PPLE + Data & Business Analytics** @ IE University  
📍 Barcelona / Madrid, Spain  
🧠 Building at the intersection of **LLM alignment, brain-inspired computing, and scalable AI systems**

---

## 🚀 About Me

I'm a multidisciplinary researcher and builder focused on **large language model fine-tuning and alignment**, **neuroscience-inspired AI architectures**, and **production-grade ML systems**.

I approach AI from two directions simultaneously: engineering systems that work reliably at scale, and grounding that work in questions about how biological intelligence actually operates.

**Core areas:**
- 🤖 LLM Fine-tuning & Alignment (SFT, DPO, RLHF)
- 🧠 Computational Neuroscience & Brain-Inspired Learning
- 📡 RAG Systems & Knowledge Graphs
- ⚙️ Concurrent Systems & Data Engineering
- ⚖️ AI Governance & Technology Policy

---

## 🔬 Current Projects

### 🏥 Medical QA Fine-tuning: LoRA SFT + DPO Alignment *(Active)*
`PyTorch` `HuggingFace TRL` `PEFT` `QLoRA` `Kaggle T4 x2`

- Fine-tuned **Qwen2.5-1.5B-Instruct** on 5,000 medical QA examples using **QLoRA** (4-bit NF4 + LoRA r=16), raising MCQ accuracy from ~35–45% → ~55–65%
- Implemented **instruction masking from scratch** — custom `InstructionMaskingCollator` setting prompt tokens to -100
- Applied **DPO (β=0.1)** on 3,000 preference pairs from medmcqa; further +5–8% MCQ accuracy
- Conducted **LoRA rank ablation** (r=8/16/32) and **DPO β sensitivity study** (β=0.05/0.1/0.3)

### 🧬 Predictive Coding Light — Replication & Ablation Study *(Active)*
`PyTorch` `NumPy` `Matplotlib`

- Replicated a **two-layer hierarchical spiking neural network** (Nature Communications, 2025) from scratch in PyTorch
- Implemented biologically plausible **excitatory + inhibitory STDP** learning rules — no backpropagation
- Diagnosed and fixed a critical bug in the convolutional STDP update (global averaging → patch-based `F.unfold` correlation)
- Designed **9 ablation conditions** beyond the original paper (no top-down inhibition, no iSTDP, varying T and β)

---

## 📂 Past Projects

### 🔎 Xuanzhi — Academic Knowledge Graph & Paper Retrieval
`Playwright` `HuggingFace` `sentence-transformers` `spaCy` `NetworkX` `Streamlit` `GraphRAG`

- Multi-source ArXiv ingestion pipeline: scraping → classification/summarisation → k-means clustering → figure extraction (PyMuPDF + CLIP)
- Built a navigable **NetworkX knowledge graph** with NER (50+ ML/NLP entity types) and cross-literature querying via Streamlit

### 🧟 World War Jose (WWJ) — Multithreaded Outbreak Simulation
`Python` `threading` `SQLite (WAL)` `Observer Pattern` `OS & Parallel Computing`

- **311 concurrent Python threads** (305 agents + 5 daemons) on a 250×250 validated U.S. geography grid (~6,100 LOC)
- Deadlock-free coordination: 7 `threading.Lock` (acyclic graph), 4 `threading.Event`, Observer-pattern EventBus, Producer-Consumer SQLite writer
- 6 design patterns applied; **52/52 unit tests** passing (race conditions, parallel DB writes, seed-determinism)
- 89 empirical simulations across 4 response strategies

### 🏥 Healthcare RAG System
`FastAPI` `ChromaDB` `sentence-transformers` `CLIP` `React` `Docker` `LangChain`

- Production-ready RAG: FastAPI backend + ChromaDB vector store + cross-encoder reranking + multimodal query (image + text via CLIP)
- Per-query telemetry, configurable model routing (small/heavy modes), Docker + docker-compose deployment
- LangChain compatibility fallback layer; reproducible environment verification scripts

### 📊 COVID-19 Big Data Pipeline
`PySpark` `PostgreSQL` `BigQuery` `dbt` `Plotly`

- End-to-end pipeline: OWID + COVID Tracking → PostgreSQL → BigQuery → layered dbt project (staging → intermediate → analytics marts)
- Animated COVID wave maps with Plotly for geographic visualisation

### 🤖 Measuring Progress Toward AGI — Cognitive Framework
`Python` `Kaggle`

- Implemented a **uMath extrapolation benchmark** to evaluate mathematical reasoning generalisation in LLMs
- Developed a cognitive framework for operationalising AGI progress metrics grounded in reasoning benchmarks

---

## 🛠️ Tech Stack

**LLM & ML**  
`PyTorch` `HuggingFace (TRL/PEFT/QLoRA)` `PaddlePaddle/PaddleNLP` `TensorFlow` `scikit-learn`

**RAG & NLP**  
`LangChain` `RAGAS` `ChromaDB` `BM25` `sentence-transformers` `spaCy` `CLIP`

**Languages**  
`Python` `Julia` `SQL (MySQL/NoSQL)` `R`

**Data & Distributed**  
`Spark (PySpark)` `Hadoop/MapReduce` `PostgreSQL` `BigQuery` `dbt` `MongoDB`

**Systems & Infra**  
`FastAPI` `React` `Docker` `Linux/UNIX` `threading` `SQLite (WAL)` `Streamlit`

**Knowledge & Graphs**  
`NetworkX` `GraphRAG` `Playwright`

**Tools**  
`Git/GitHub` `Jupyter` `W&B` `Plotly` `Folium`

---

## 🌱 Currently Exploring
- Spiking neural networks & biologically plausible learning rules
- LLM post-training: RLHF pipelines, reward modelling
- Scientific AI applications (neuro-inspired architectures)

---

## 📫 Contact
- 💼 [LinkedIn](https://linkedin.com/in/business-myu)
- 🐙 [GitHub](https://github.com/devMYurge)
- 📧 myu.ieu2023@student.ie.edu

---

*Languages: 普通话 (Native) · Español (Native) · English (C1) · Català (C1)*
