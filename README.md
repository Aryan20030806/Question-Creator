# 🧠 PDF Question & Answer Generator using LangChain and OpenAI

This project builds an **AI-driven system** that automatically **generates and answers interview-style questions** from the content of any uploaded PDF file.  
It uses **LangChain**, **OpenAI GPT-3.5**, and **FAISS** to read, chunk, and analyze documents — producing meaningful, thought-provoking Q&A pairs suitable for interviews, education, or research.

---

## 🚀 Overview

`experiment.ipynb` demonstrates how to:
1. Load and read a PDF file using **LangChain's PyPDFLoader**  
2. Split text into chunks using **token-based text splitting**  
3. Generate 5 **contextual, critical-thinking questions** for each chunk  
4. Create **vector embeddings** with **OpenAI Embeddings**  
5. Use **FAISS vector search** to find relevant answers  
6. Generate concise, accurate answers using **GPT-3.5-Turbo**  
7. Save all generated Q&A pairs in a text file (`generated_questions_and_answers.txt`)

---

## ⚙️ Tech Stack

- 🐍 **Python 3.10+**
- 🧩 **LangChain** (`langchain-community`, `langchain-core`, `langchain-openai`)
- 🤖 **OpenAI GPT-3.5 Turbo**
- 📘 **PyPDFLoader**
- 💾 **FAISS Vector Store**
- 🔑 **python-dotenv**

---

## 📦 Installation & Setup

Clone this repository:
```bash
git clone https://github.com/yourusername/pdf-question-generator.git
cd pdf-question-generator
