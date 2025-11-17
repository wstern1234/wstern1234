# Hi, I'm William Stern

**Software Engineer @ AWS | UC Berkeley CS + Data Science**  

---

## Tech Stack
- **Languages & AI:** Python, Java, C/C++, PyTorch, TensorRT, CUDA, Hugging Face, Transformers, NLP, Computer Vision  
- **Cloud & Systems:** AWS (S3, EC2, Athena), Google Cloud, Docker, REST APIs, CI/CD, Linux  
- **Data Engineering:** ETL pipelines, Retrieval-Augmented Generation (RAG), Vector DBs (FAISS), Testing & Validation  

---

## Experience
- **Amazon Web Services (AWS)** — Software Development Engineer  
  - Built AI-powered visualization pipelines reducing reporting time from *days to minutes*
  - Designed test coverage across S3 APIs to ensure reliability and backward compatibility
  - Strengthened S3 bucket security with the cybersecurity team, mitigating misconfiguration risks and improving security compliance.

- **Mendel.ai** — AI Research Engineer Intern  
  - Prototyped knowledge extraction + cloud-parallelized processing pipelines for clinical research  
  - Improved automation and reliability of AI-powered medical data tools  

- **UC Berkeley CTO (Student Government)** — Led digital infrastructure for 40k+ students  
- **Lawrence Berkeley National Lab** — Researched AI/ML for biological datasets  

---

## Featured Work

### 🤖📏 [Yardstick](https://github.com/wstern1234/yardstick)

A **modular AI performance benchmarking system** built to evaluate TensorRT models like ResNet and BERT with dynamic precision, automated logging, and performance summarization.

* **GPU-accelerated** inference using TensorRT (FP16 and FP32 support)
* Unified **CLI interface** for running and comparing benchmarks across models
* Automatic **log parsing and summarization** for reproducible performance tracking
* Demonstrates **deep learning systems optimization** and **software design for automation**  

---

### 💧 [Meltwater](https://github.com/wstern1234/meltwater)  
A lightweight, self-hosted Python project that exposes a **pretrained LLM via FastAPI REST API** with JWT authentication and a Gradio interface.  
- Endpoints for `/login`, `/generate`, and `/generate_stream` (streaming ChatGPT-style outputs)  
- Fully **Dockerized** for one-container deployment (API + UI)  
- Supports **JWT-secured access** and optional hot-reload for development  

---

### 🧠 [wee_model](https://github.com/wstern1234/wee_model)  
A **locally fine-tuned GPT-2 tiny model**, trained fully on consumer hardware (Windows, CPU).  
- 18,000 training steps on a custom dataset with Hugging Face + PyTorch  
- Checkpoint saving/restoration for reproducibility  
- Interactive text generation loop for rapid testing  

---

### 💠 [Holocron](https://github.com/wstern1234/holocron)  
A **local-first RAG chatbot** that combines **FAISS semantic search** with **Google Gemini** for context-aware answers.  
- Load and embed PDFs into a FAISS vector database  
- Retrieve context and generate responses with Gemini via LangChain  
- Lightweight CLI chatbot for querying your personal knowledge base

---

### 🧪 [research](https://github.com/wstern1234/research)
**Asthma Diagnosis (ml_research/)**:
- Explores early-onset asthma prediction using social and socioeconomic indicators. Implements Logistic Regression, Decision Tree (CART), Random Forest, and XGBoost models with extensive data preprocessing (VIF, PCA, feature scaling, K-fold validation). Achieved high interpretability and addressed challenges of severe class imbalance in medical datasets.

**BERT for NLP Classification (nlp_research/)**:
- Fine-tuned a pretrained BERT model on a custom annotated dataset for text classification. Covers full preprocessing, tokenization, and evaluation pipelines, showcasing applied NLP model development and dataset curation.

---

## Connect With Me
- **Personal site:** [w-stern.com](http://w-stern.com)  
- **LinkedIn:** [linkedin.com/in/wills-stern](http://linkedin.com/in/wills-stern)  
- **Email:** [willsstern@gmail.com](mailto:willsstern@gmail.com)  

---

Feel free to explore my other repos. I’m always open to collaboration, feedback, and new opportunities to build impactful software.
