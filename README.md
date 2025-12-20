# ProductHealthSentimentAnalyst_HybridRAG

**A decision-centric Agentic AI system for Product Management decision support.**

## 📖 Overview

This repository contains a reference implementation of a **Hybrid RAG (Retrieval-Augmented Generation)** system designed specifically for Product Managers. It combines semantic search, structural graph retrieval, and real-time data access to generate a recommendation for one decision primitive.

The system is built with a focus on **evaluations and observability**, ensuring that the decision support provided is accurate, traceable, and reliable.

### Key Features
* **Hybrid Retrieval:** Combines vector-based semantic search with graph-based structural retrieval.
* **Agentic AI:** Autonomous reasoning capabilities to assist in complex PM decision-making.
* **Real-time Analysis:** Integrates real-time retrieval capabilities.
* **Observability:** Integrated with LangSmith for tracing and debugging.

---

## 🛠️ Tech Stack

* **LLMs:** NVIDIA Nemotron, Anthropic Claude
* **Graph Database:** Neo4j / MemGraph
* **Observability:** LangSmith
* **Environment:** Google Colab

---

## ⚙️ Prerequisites

Before running the notebook, ensure you have the following:

### 1. API Keys
You will need active API keys for the following services:
* **NVIDIA Nemotron** (for inference)
* **LangSmith** (for observability and evaluations)
* **Anthropic Claude** (for advanced reasoning)
* **Neo4j** and **MemGraph** (for Knowledge Graph storage)

### 2. Data Files
* `BMT_Internal_Documentation.docx`: This file is required for the Semantic RAG component.

---

## 🚀 Setup & Usage

This project is designed to be run in **Google Colab**. Follow these steps to get started:

### Step 1: Configure Environment Secrets
To keep your credentials secure, do **not** hardcode them in the notebook. Instead, use Google Colab's "Secrets" feature (the key icon on the left sidebar).


### Step 2: Upload Data
1. Open the file explorer in the left sidebar of your Colab instance.
2. Upload the `BMT_Internal_Documentation.docx` file.
   * *Note: This file must be present in the runtime environment before executing the code.*

### Step 3: Execution
Run the cells in order. The system will ingest the internal documentation, build the knowledge graph, and initialize the agentic workflow.

---

## 📝 License
None

<img width="1024" height="565" alt="image" src="https://github.com/user-attachments/assets/88360eb7-25d6-44c0-866b-71f90b1eef2e" />
