# 🚀 FinInsight

## AI-Powered Financial Analysis Platform

**University of Michigan--Dearborn**\
**CIS-5570 -- Introduction to Big Data**\
**Instructor:** Dr. Mohamed Abouelenien

------------------------------------------------------------------------

# 📌 Project Overview

**FinInsight** is a scalable, modular financial intelligence platform
that integrates **Big Data pipelines** with **Artificial Intelligence
models** to perform real-time financial analysis.

The system processes large-scale datasets including:

-   📄 SEC Filings\
-   📰 Financial News Articles\
-   💬 Reddit Finance Discussions

It transforms raw financial text into **context-grounded, explainable
AI-generated insights in seconds.**

------------------------------------------------------------------------

# 🎯 Objective

> Enable users to query massive financial datasets using natural
> language and receive accurate, explainable, context-aware answers in
> real time.

------------------------------------------------------------------------

# 🏗 System Architecture

FinInsight follows a **Retrieval-Augmented Generation (RAG)**
architecture:

### 1️⃣ Data Processing Layer

-   Clean and preprocess financial text using **PySpark**
-   Extract entities & sentiment using **Spark NLP**

### 2️⃣ Embedding Layer

-   Generate dense vector embeddings using **Sentence Transformers
    (MiniLM-L6-v2)**

### 3️⃣ Retrieval Layer

-   Perform semantic similarity search with **FAISS**

### 4️⃣ Generation Layer

-   Construct prompts via **LangChain**
-   Generate answers using **FLAN-T5 (Base)**

------------------------------------------------------------------------

# 🛠 Tech Stack

  Category                  Technology
  ------------------------- --------------------------------------
  Distributed Processing    Apache Spark (PySpark)
  NLP                       Spark NLP
  Embeddings                Sentence Transformers (MiniLM-L6-v2)
  Vector Search             FAISS
  Orchestration             LangChain
  Language Model            FLAN-T5 Base
  Development Environment   Google Colab

------------------------------------------------------------------------

# 📂 Project Structure

``` bash
FinInsight/
│
├── notebooks/
│   └── AI_Powered_Financial_Analysis_FILE_(2).ipynb
│
├── data/
│   ├── CNBC_financial_articles_2.json
│   ├── CNBC_financial_news_1.json
│   └── reddit_posts.json
│
├── diagrams/
│   ├── system_architecture.png
│   ├── pyspark_ingestion_flow.png
│   ├── rag_pipeline_diagram.png
│
├── screenshots/
│   └── (retrieval examples, query responses)
│
├── README.md
└── requirements.txt
```

------------------------------------------------------------------------

# ⚙️ How to Run

### 1️⃣ Clone the Repository

``` bash
git clone https://github.com/OweshC12/FinInsight-AI-Powered-Financial-Analysis.git
cd FinInsight-AI-Powered-Financial-Analysis
```

### 2️⃣ Install Dependencies

``` bash
pip install -r requirements.txt
```

### 3️⃣ Launch the Jupyter Notebook

``` bash
jupyter notebook
```

Open:

    notebooks/AI_Powered_Financial_Analysis_FILE_(2).ipynb

### 4️⃣ Execute the Notebook

Follow the code cells sequentially to: - Load and preprocess data\
- Generate embeddings\
- Build FAISS index\
- Query the system\
- Generate AI-powered responses

------------------------------------------------------------------------

# 📊 Evaluation Results

  Metric               Result
  -------------------- ------------------
  Top-3 Relevance      \~87%
  Semantic Retrieval   Strong
  Context Grounding    \~0.5 (Moderate)
  Response Quality     High

------------------------------------------------------------------------

# 🚀 Future Enhancements

-   Real-time ingestion via **Kafka / Spark Streaming**\
-   Fine-tuning FLAN-T5 on financial corpora\
-   Front-end web application for public financial Q&A\
-   Expansion to earnings calls, SEC exhibits, and investor reports

------------------------------------------------------------------------

# 📚 References

-   Spark NLP Documentation\
-   FAISS by Facebook Research\
-   Sentence Transformers (SBERT)\
-   LangChain Framework\
-   FLAN-T5 on HuggingFace\
-   FNSPID Dataset (arXiv: 2402.06698)

------------------------------------------------------------------------

# 🏆 Key Contributions

-   Designed scalable Spark-based ingestion pipeline\
-   Implemented full RAG pipeline\
-   Built semantic search using FAISS\
-   Integrated financial NER & sentiment analysis\
-   Delivered explainable AI-generated financial insights

------------------------------------------------------------------------

# 📈 Why This Project Matters

FinInsight demonstrates integration of:

-   Big Data Engineering\
-   NLP\
-   Vector Databases\
-   Generative AI\
-   Financial Analytics

It showcases production-level architecture combining **distributed
systems + AI orchestration**, making it highly relevant for Data
Science, AI Engineering, and Financial Analytics roles.
