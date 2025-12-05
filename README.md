# AIPrototypeITKB
# Synthetic IT Support GenAI Assistant  
_A safe, portfolio-focused demonstration of retrieval-augmented AI for IT support contexts._

This repository contains a **fully synthetic** proof-of-concept GenAI assistant designed to explore how Large Language Models (LLMs) can support IT self-service, user guidance, and knowledge retrieval workflows.

No internal, confidential, or proprietary organizational data is used.  
All content (KB samples, instructions, workflows, ticket scenarios) is fictional.

---

## 🔧 Purpose
This project demonstrates:

- Retrieval-Augmented Generation (RAG) using **synthetic knowledge base articles**
- Summarization and conversational reformulation
- Safe prompt design and user-centered interaction patterns
- Basic architecture for a self-service IT support AI assistant
- Documentation suitable for innovation teams evaluating AI pilots or prototypes

The prototype is intentionally lightweight to show **velocity, experimentation, and governance awareness**, consistent with ITIL HVIT and innovation best practices.

---

## 🧠 Features

- **Synthetic KB Data:**  
  A collection of fictional IT support articles (20–30 entries) covering topics such as password resets, hardware troubleshooting, VPN setup, and software requests.

- **RAG Retrieval Pipeline:**  
  Embeds and retrieves relevant synthetic KB entries to ground model responses.

- **Simple Web Interface (Streamlit):**  
  - Ask a support question  
  - Model retrieves and summarizes relevant KB entries  
  - Sources are cited for transparency  

- **Governance & Safety Controls:**  
  - No real organizational data  
  - Prompts reinforce safe handling & disclaimers  
  - Logging of user interactions (optional and anonymized)

---

## 📁 Repository Structure

