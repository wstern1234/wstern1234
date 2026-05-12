# Hi, I'm William Stern

**Software Engineer @ AWS | Distributed Systems & ML Infrastructure**  

---

## Tech Stack
- **Languages:** Python, Java, C/C++, TypeScript, SQL, Git
- **ML & AI:** PyTorch, TensorRT, CUDA, Hugging Face, Transformers, NLP, Computer Vision
- **Cloud & Infrastructure:** AWS (S3, EC2, Athena, CDK, CloudFormation), Google Cloud, Docker, Linux, CI/CD, Infrastructure as Code (IaC)
- **Systems:** Distributed Systems, ML Infrastructure, System Design, REST APIs
- **Data Engineering:** ETL Pipelines, Retrieval-Augmented Generation (RAG), Vector DBs (FAISS), Testing & Validation

---

## Experience
**Amazon Web Services** | Seattle, WA | *May 2024 – Present*  
*Software Development Engineer (Jul 2025 – Present)*  
*Software Development Engineer Intern (May 2024 – Aug 2024)*  
- Built an end-to-end ML data pipeline integrating model inference with downstream AWS service APIs, automating reporting workflows and cutting analyst cycle time from days to minutes; designed for fault tolerance and observability across distributed infrastructure.
- Independently identified an active data exposure vulnerability through open-source reconnaissance, scoped the attack surface, and led cross-functional remediation with the cybersecurity team: hardening bucket policies, enforcing IAM access controls, and fixing security gaps at scale.
- Extended a multi-region deployment pipeline with automated health checks, continuous integration, and CloudWatch observability, improving reliability for S3's infrastructure serving global-scale traffic.
**Mendel.ai** | San Jose, CA | *Jun 2023 – Aug 2023*  
*AI Research Engineer Intern*  
- Prototyped knowledge extraction + cloud-parallelized processing pipelines for clinical research.
- Improved automation and reliability of AI-powered medical data tools.
**UC Berkeley, ASUC** | *Sep 2023 – May 2024*  
*Chief Technology Officer (Student Government)*  
- Led digital infrastructure and technical projects for UC Berkeley's 40k+ student body.
**Lawrence Berkeley National Lab** | *Jun 2021 – Aug 2021*  
*ML Research Assistant*  
- Researched AI/ML for biological datasets using protein data APIs and custom algorithms.  

---

## Featured Work

### 🛡️ [Brigade](https://github.com/wstern1234/brigade)

A lightweight benchmarking framework that emulates multi-GPU training behavior on a single consumer GPU, enabling fast experimentation with parallelism strategies without expensive hardware.

* Simulates data-parallel and pipeline-parallel workflows on a single GPU
* Supports configurable batch partitioning, communication-delay modeling, and step-time profiling
* Provides a unified CLI for running experiments and comparing parallelization strategies
* Automatically logs performance traces and produces summarized reports
* Designed for learning *systems-level ML engineering* without needing access to multi-node clusters

---

### 🤖📏 [Yardstick](https://github.com/wstern1234/yardstick)

A **modular AI performance benchmarking system** built to evaluate TensorRT models like ResNet and BERT with dynamic precision, automated logging, and performance summarization.

* **GPU-accelerated** inference using TensorRT (FP16 and FP32 support)
* Unified **CLI interface** for running and comparing benchmarks across models
* Automatic **log parsing and summarization** for reproducible performance tracking
* Demonstrates **deep learning systems optimization** and **software design for automation**  

---

### 💧 [Meltwater](https://github.com/wstern1234/meltwater)  
A lightweight, self-hosted Python project that exposes a **pretrained LLM via FastAPI REST API** with JWT authentication and a Gradio interface.  
* Endpoints for `/login`, `/generate`, and `/generate_stream` (streaming ChatGPT-style outputs)  
* Fully **Dockerized** for one-container deployment (API + UI)  
* Supports **JWT-secured access** and optional hot-reload for development  

---

### 🧪 [research](https://github.com/wstern1234/research)
**Asthma Diagnosis (ml_research/)**:
* Explores early-onset asthma prediction using social and socioeconomic indicators. Implements Logistic Regression, Decision Tree (CART), Random Forest, and XGBoost models with extensive data preprocessing (VIF, PCA, feature scaling, K-fold validation). Achieved high interpretability and addressed challenges of severe class imbalance in medical datasets.

**BERT for NLP Classification (nlp_research/)**:
* Fine-tuned a pretrained BERT model on a custom annotated dataset for text classification. Covers full preprocessing, tokenization, and evaluation pipelines, showcasing applied NLP model development and dataset curation.

---

## Connect With Me
- **Personal site:** [w-stern.com](http://w-stern.com)  
- **LinkedIn:** [linkedin.com/in/wills-stern](http://linkedin.com/in/wills-stern)  
- **Email:** [wills.stern@gmail.com](mailto:wills.stern@gmail.com)  

---

Feel free to explore my other repos. I’m always open to collaboration, feedback, and new opportunities to build impactful software.
