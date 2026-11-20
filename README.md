# Bhavya Mummaneni

**AI Engineer** · San Antonio, TX, USA · Open to relocation anywhere in the US

AI/ML Engineer with 7+ years of experience building production machine learning and Generative AI systems — LLM applications, retrieval-augmented generation (RAG), and AI agents — in regulated, security-sensitive enterprise environments. My employer work is proprietary, so this page focuses on my personal projects and general background. The specifics of my professional work — outcomes, scale, and project detail — belong in my resume and in interviews, not on a public page.

## What I work on

- **Generative AI & agents** — LLM applications, RAG architectures with embeddings and vector databases, agent tool/function calling, prompt engineering, structured outputs
- **Machine learning** — model development, validation, deployment, monitoring, and optimization across the full lifecycle
- **MLOps & platforms** — Docker, Kubernetes, MLflow, CI/CD, cloud AI on AWS and Azure
- **Data engineering** — feature pipelines with PySpark, SQL, and Airflow; ETL and data quality

## Projects

**[RAG Document Q&A](https://github.com/bhavya-mummaneni/rag-doc-qa)** — working code
- **Problem:** answer questions grounded in a document set, with traceable sources.
- **Approach:** LangChain ingestion and chunking, FAISS vector search, answers composed from retrieved passages with source citations, FastAPI backend, Streamlit UI.
- **Results (sample data):** a 15-question evaluation — 100% retrieval hit rate and 100% answer accuracy.
- **Limitations:** generation is extractive because the project runs without an LLM API key; the design lets an LLM swap in without changing the API or UI.

**[LangGraph Agent](https://github.com/bhavya-mummaneni/langgraph-agent)** — working code
- **Problem:** an agent that plans multi-step tasks, calls tools in sequence, and refuses out-of-scope requests.
- **Approach:** a LangGraph state graph (guardrail → plan → execute → respond) with three tools — document lookup with citations, a calculator, and data queries over a sample dataset — each wrapped with retries and per-call latency logging; structured outputs throughout.
- **Results (sample data):** a 15-task evaluation — 15/15 passed, including chained multi-step tasks, an expected refusal, and an error-handling case.
- **Limitations:** the planner is deterministic because the project runs without an LLM API key; an LLM planner can swap in behind the same interface.

## Experience

- **AI Engineer — Goldman Sachs** (Aug 2025 – Present)
  - Build LLM, RAG, and AI-agent applications for enterprise users in a regulated environment
  - Model evaluation, monitoring, and governance for production ML systems
  - Data pipelines for feature engineering and analytics
- **Machine Learning Engineer — IBM** (Sep 2019 – Apr 2023)
  - Developed production ML systems and MLOps pipelines in multi-cloud environments
  - NLP pipelines for document intelligence; predictive modeling for client analytics
- **Machine Learning Engineer — CGI** (Jun 2016 – Aug 2019)
  - Built ML and forecasting models for investment analytics
  - ETL and data-quality pipelines; model monitoring and reporting

## Tech I use

- **Languages:** Python, SQL, R, Scala, Bash
- **ML/DL:** PyTorch, TensorFlow, scikit-learn, XGBoost, Hugging Face, spaCy, Prophet
- **GenAI:** LangChain, LangGraph, RAG, FAISS, Pinecone, AWS Bedrock, Azure ML, MCP, AutoGen
- **MLOps/Cloud:** Docker, Kubernetes (EKS/AKS), Terraform, MLflow, Airflow, GitHub Actions, Azure DevOps, AWS (SageMaker, Bedrock, Lambda, Glue, EMR, Kinesis)
- **Data:** Spark/PySpark, Databricks, Kafka, DynamoDB, MongoDB

## Education

- Master's in Information Technology Management — Webster University (2023–2025)

## Contact

- LinkedIn: https://www.linkedin.com/in/mummaneni-aiml
- Email: bhavya.m.connect@gmail.com
