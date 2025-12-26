# 📄 AI Resume Analyzer

This is a smart AI-powered Resume Analyzer built using Flask and NLP models.  
It compares a candidate's resume with a job description and provides:

✔ Match Score  
✔ Skills Found in Resume  
✔ Missing Skills  
✔ Suggestions to Improve Resume  

The system uses advanced **semantic similarity** and **skill extraction AI models**.

---

## 🚀 Features

- Upload resume (PDF format)
- Paste any job description
- AI-based semantic matching
- Skill extraction using NER models
- Visual feedback with skill insights
- Professional and clean UI (Tailwind CSS)

---

## 🧠 Technologies Used

| Component | Technology |
|----------|-----------|
| Backend | Flask (Python) |
| AI Model | SentenceTransformer: `all-MiniLM-L6-v2` |
| Skill Extraction | HuggingFace NER |
| PDF Parsing | PyMuPDF |
| Frontend UI | HTML + TailwindCSS |

---

## 📦 Installation

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/kavyapulipati1/ResumeAnalyzer.git
cd ResumeAnalyzer
