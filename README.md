# Multi-AI Document Intelligence System

## Project Overview

The **Multi-AI Document Intelligence System** is an intelligent and privacy-focused platform designed to automate the process of reading, understanding, analyzing, and generating information from digital documents.

Users can upload documents such as **PDF, DOCX, and TXT files** and interact with them using natural-language queries. The system uses **Retrieval-Augmented Generation (RAG), Natural Language Processing (NLP), Large Language Models (LLMs), and a multi-agent architecture** to provide relevant and task-specific responses.

---

## Key Features

* Upload and process PDF, DOCX, and TXT documents
* Ask questions using natural language
* Generate concise document summaries
* Extract important information
* Analyze patterns and insights
* Generate structured reports and professional content
* Maintain query history
* Display AI agent execution status
* Export user sessions
* Local AI processing for improved privacy

---

## Multi-Agent Architecture

The system uses a central **Orchestrator Agent** to understand the user's request and route it to the appropriate specialized agent.

### Reader Agent

Extracts relevant information from uploaded documents.

### Summarizer Agent

Generates concise and meaningful summaries.

### Analyzer Agent

Identifies patterns, important insights, and relevant information.

### Q&A Agent

Answers specific questions based on the uploaded documents.

### Writer Agent

Generates structured reports and professional content.

---

## System Workflow

1. User uploads a document.
2. The document content is extracted.
3. The content is divided into smaller meaningful chunks.
4. The chunks are stored in a vector-based retrieval system.
5. The user submits a natural-language query.
6. Relevant document chunks are retrieved.
7. The Orchestrator Agent identifies the requested task.
8. The query is routed to the appropriate AI agent.
9. The system generates and displays the final response.

---

## Technologies Used

* **Python**
* **Streamlit**
* **Ollama**
* **Locally Hosted LLMs**
* **Retrieval-Augmented Generation (RAG)**
* **Natural Language Processing (NLP)**
* **Multi-Agent AI Architecture**
* **Vector-Based Retrieval System**

---

## Project Structure

```text
Multi-AI-Document-Intelligence-System/
│
├── src/                # Source code
├── docs/               # Project documentation
├── data/               # Sample documents or data references
├── results/            # Output and evaluation results
├── reports/            # Project reports
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd Multi-AI-Document-Intelligence-System
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Ensure that **Ollama** and the required local LLM are installed and running.

Start the application:

```bash
streamlit run app.py
```

---

## Applications

The system can be useful in:

* Research and education
* Legal document analysis
* Business reporting
* Financial document processing
* Knowledge management

---

## Future Improvements

* Support for additional document formats
* Improved retrieval accuracy
* Advanced document comparison
* Multi-document analysis
* Better evaluation of answer faithfulness
* Performance optimization for response latency
* Enhanced user interface and visualization

---

## Team Members

| Name           | University ID |
| -------------- | ------------- |
| Madhu Praveena | 2420030321    |
| M. Pranusree   | 2420030658    |
| Ranan Magdala  | 2420030744    |
| Hema Thulasi   | 2420030699    |

---

## Academic Information

**Course:** Engineering Capstone Project – 1
**Academic Year:** 2026–2027
**Department:** Computer Science and Engineering

## License

This project is developed for academic and educational purposes.
