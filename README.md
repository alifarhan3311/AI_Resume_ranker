# AI_Resume_ranker
This project is about ranking the resume according to recruiter needs and automate the process of shortlisting of candidates
# 📝 AI Resume Ranker

An **AI-powered recruitment tool** that automates resume screening and candidate shortlisting using **Machine Learning (ML)** and **Natural Language Processing (NLP)**.  

This project helps recruiters efficiently analyze resumes, extract key skills and experiences, and rank candidates against job descriptions — reducing bias, improving fairness, and accelerating the hiring process.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [System Workflow](#-system-workflow)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Future Scope](#-future-scope)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🔎 Overview
Recruiters often face the challenge of reviewing **hundreds of resumes** for a single job posting. Traditional manual screening is:
- Time-consuming ⏳
- Error-prone ❌
- Biased ⚖️  

The **AI Resume Ranker** addresses these issues by:
- Parsing resumes in **DOCX** and **PDF** formats  
- Extracting structured information (skills, experience, education)  
- Matching candidates against job descriptions using NLP  
- Ranking candidates based on relevance scores  

---

## ✨ Features
- **Resume Parsing** → Extracts skills, education, work history, and personal info  
- **Job Description Analysis** → Identifies required qualifications and skills  
- **Candidate Ranking** → Uses similarity scores & ML models for ranking  
- **Search & Filters** → Narrow down candidates by score, skills, or experience  
- **Export Options** → Ranked results exportable to **PDF** or **Excel**  
- **Feedback Loop** → System improves accuracy based on recruiter decisions  

---

## ⚙️ System Workflow
1. Upload resumes (DOCX/PDF)  
2. Input job description  
3. NLP preprocessing (tokenization, stopwords removal, lemmatization)  
4. Named Entity Recognition (NER) for skill & role extraction  
5. Matching engine compares resumes with job description  
6. Candidates ranked & displayed with relevance scores  
7. Results exportable for recruiter use  

---

## 🛠 Tech Stack
- **Programming Language:** Python (Jupyter Notebook, Colab, Anaconda)  
- **Libraries & Frameworks:**  
  - `scikit-learn`, `NumPy`, `Pandas`, `Matplotlib`  
  - `NLTK`, `regex`, `PyPDF2`, `python-docx`  
  - `NER models` for entity recognition  
- **Frontend (optional):** Streamlit / Flask / Django  
- **Data:** Resume dataset (228 resumes in DOCX/PDF format)  

---

## 🚀 Installation
```bash
# Clone the repository
git clone https://github.com/your-username/ai-resume-ranker.git
cd ai-resume-ranker

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

# Install dependencies
pip install -r requirements.txt
