# 📄 AI Resume Filter

AI Resume Filter is an intelligent tool designed to help recruiters, HR teams, and students/job seekers quickly and accurately evaluate resumes. It analyzes resumes to check how well they match a job description by looking at relevant skills, keywords, and resume formatting quality — all through an easy-to-use web interface built with Streamlit.

---

## 🧠 Project Overview

The AI Resume Filter uses machine learning and natural language processing to analyze resumes, extract keywords, compare them against job descriptions, and detect irrelevant or weak resume patterns. It helps automate the shortlisting process with high accuracy and transparency.

---

## 🚀 Key Features

- ✅ **PDF Resume Parsing** using PyMuPDF
- 🧠 **Text Embeddings** using `sentence-transformers` (`all-MiniLM-L6-v2`)
- 🗃️ **Semantic Search** with ChromaDB (or FAISS)
- 🔍 **Keyword Extraction** and **Match Scoring**
- 🛑 **Irrelevant Skill Detection**
- 💬 **Fallback Chat Analysis** using Hugging Face Transformers (optional)
- 🌐 **Streamlit-based Web UI** for easy interaction

---

## 🛠 Technologies Used

| Component         | Tool/Library                     |
|------------------|----------------------------------|
| Backend           | Python                           |
| Web UI            | Streamlit                        |
| NLP Embeddings    | Sentence Transformers (MiniLM)   |
| Resume Parsing    | PyMuPDF                          |
| Vector DB         | ChromaDB or FAISS                |
| Fallback NLP API  | Hugging Face Inference API       |

---

## 🎯 How It Works

1. **User uploads a PDF resume**
2. **Text is extracted and cleaned**
3. **Embeddings are generated**
4. **Semantic similarity is calculated against job description**
5. **Keywords are extracted and scored**
6. **Optional fallback to Hugging Face API if OpenAI API is unavailable**
7. **Results displayed via Streamlit with recommendations**

## 📁 Project Structure

```
resume-filter/
├── app1.py                  # Main Streamlit app
├── .gitignore                     # API keys (ignored in .gitignore)
├── requirements.txt         # Dependencies
└── README.md                # Project documentation
```


## ✅ Todo / Upcoming
Add OpenAI API fallback (optional)

Export shortlisted candidates to Excel

User authentication for secure access

Deploy on Streamlit Community Cloud

---

## 🙏 Acknowledgments
Sentence Transformers

ChromaDB

Streamlit

Hugging Face

---

---

## 📢 Contact

**Harsh Kaushik**  
🔗 [LinkedIn](https://www.linkedin.com/in/harshkaushik1)  
📧 harshkaushik494@gmail.com


## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/Harshkaushik-coder/resume-filter.git
cd resume-filter

re updation

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app1.py
