# 🚀 AI-Powered Resume Analyzer & CSV Generator (LangChain + Streamlit)

This project automates the extraction of candidate information from **multiple resumes stored inside a ZIP file**. It processes PDF/DOCX resumes, parses key details using **LangChain + LLMs**, and exports everything into a clean, structured **CSV file** — ready for HR screening.

---

## 📌 Features

- 📁 Upload a ZIP file of resumes (PDF/DOCX)
- 🤖 LLM-powered structured resume extraction
- 📄 Reads each file & converts to text automatically
- 🧱 Enforced schema using LangChain Output Parser
- 📊 Outputs all candidates into a CSV dataset
- 🌐 Streamlit UI for interactive usage & CSV download

---

## 🧠 Tech Stack

Python
Streamlit
LangChain
Google Gemini LLM
PyPDF2, python-docx


---

## ⚙️ How It Works

Upload ZIP file
Extract resume text
Convert unstructured text → structured schema
Aggregate results
Download CSV

---

## ▶️ How to Run

pip install -r requirements.txt
streamlit run main.py

---


## 📌 Real-World Use Cases

HR resume screening automation
Bulk candidate processing for campuses
Startup hiring automation

