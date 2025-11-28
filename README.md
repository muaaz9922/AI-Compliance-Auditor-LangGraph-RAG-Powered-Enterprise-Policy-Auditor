# AI-Compliance-Auditor-LangGraph-RAG-Powered-Enterprise-Policy-Auditor
An AI-driven compliance auditing system using LangGraph, LangChain, Groq LLM, and RAG to automatically analyze company policies, HR manuals, contracts, and GDPR/ISO documents. Generates structured audit reports, risk scores, and missing clause detections — with export to PDF/DOCX.


# 🛡️ AI Compliance Auditor  
### **LangGraph + LangChain + RAG + Groq-Powered Enterprise Auditor**

![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Framework](https://img.shields.io/badge/Framework-LangGraph-purple)
![Groq](https://img.shields.io/badge/LLM-Groq%20Mixtral-orange)

---

## 🚀 Overview

The **AI Compliance Auditor** is a powerful enterprise-scale audit system that uses:

- **LangGraph** (workflow/state machine)
- **LangChain** (RAG pipeline)
- **Groq LLM** (ultra-fast inference)
- **Vector Search**
- **Automated Report Generation (PDF/DOCX)**

It ingests **policies, HR manuals, legal contracts, GDPR/ISO docs**, and more — then performs:

### ✅ Compliance Violation Detection  
### ✅ Missing Clause Identification  
### ✅ GDPR / ISO / HR Policy Alignment  
### ✅ Risk Scoring & Heatmaps  
### ✅ Automated Report Creation  

This tool is built for **real organizations**, **consultants**, and **audit teams** who want a modern AI-powered compliance assistant.

---

## 🧠 Core Features

### 🔍 **1. RAG Document Intelligence**
- Upload PDF/Text/Docs
- Extract & embed using updated LangChain embedding models
- Store embeddings in **ChromaDB** 
- Retrieve relevant chunks for precise AI reasoning

---

### 🔁 **2. LangGraph Workflow Engine**

The system runs through a **state-machine pipeline**:

1. **Planner Node** – identifies audit goals  
2. **Retriever Node** – fetches relevant policy chunks  
3. **Analysis Agent** – evaluates violations & issues  
4. **Compliance Auditor** – applies GDPR/ISO/HR logic  
5. **Report Writer** – generates structured summary  
6. **Reporter Node** – outputs final results  

**Graph Visual Included:**


---

### 📊 **3. Enterprise-Level Visualizations**
- Policy Coverage Pie Chart  
- Risk Heatmap  
- Violation Frequency Bars  
- Category-wise Breakdown  

These appear inside Google Colab with clean matplotlib visuals.

---

### 📝 **4. Professional Report Export**
Export final audit report as:

- **📄 PDF** (ReportLab engine)
- **📝 DOCX** (python-docx)

Each report includes:

- Executive Summary  
- Detected Violations  
- Missing Clauses  
- GDPR/ISO Alignment  
- Risk Score & Recommendations  

---

## 🏗️ Project Architecture

/AI-Compliance-Auditor

│
├── data/ # Uploaded documents

├── embeddings/ # Vector store (ChromaDB)

├── notebook.ipynb # Full Colab notebook with UI + graph

├── audit_reports/ # PDF & DOCX export
│

└── modules/

├── graph.py # LangGraph workflow

├── rag_pipeline.py # Embedding + Retrieval

├── analysis_agent.py # Violations & risk logic

├── report_exporter.py # PDF/DOCX generator


---

## ⚙️ Installation (Google Colab)

Just open the notebook and run:

```bash
pip install langchain langgraph chromadb groq pdfplumber python-docx reportlab matplotlib

🤝 Contributing

Contributions, issues, and new compliance logic modules are welcome!

📄 License

This project is released under the MIT License.

⭐ Support

If you like this project, give it a ⭐ on GitHub — it helps a lot!


---

If you'd like, I can also generate:

✅ Repo Banner Image  
✅ Folder Structure Template  
✅ Demo GIF (ASCII version)  
✅ Badges for "Made with LangGraph"  

Just tell me **“Generate banner”** or **“Generate repo visuals”**.
