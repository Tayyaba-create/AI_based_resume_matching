# 🧠 Resume Matcher with FastAPI
This is a web-based Resume and Job Description (JD) matching application built using FastAPI. It extracts skills from uploaded resumes and job descriptions using spaCy NLP, compares them, and returns a matching score based on overlapping skills.

## 🚀 Features
- ✅ Upload resumes in .pdf, .docx, .txt, or image formats (.jpg, .png)

- ✅ Extracts text using OCR and text parsers

- ✅ Extracts skills using spaCy's NLP engine

- ✅ Matches resume skills with job description

- ✅ Calculates and displays a skill match score

- ✅ Web interface built with Jinja2 templates


## 🛠 Requirements
- Python 3.8+

- FastAPI

- Uvicorn

- spaCy (en_core_web_sm)

- PyMuPDF (fitz)

- python-docx

- pytesseract

- Pillow


## ⚙️ Installation & Run
#### 1. Clone the repo
- git clone https://github.com/yourusername/resume-matcher-fastapi.git
- cd resume-matcher-fastapi
  
#### 2. Create virtual environment (optional but recommended)
- python -m venv venv (For Windows)
- source venv/bin/activate (For Linux)

#### 3. Install dependencies
pip install -r requirements.txt

#### 4. Install spaCy model
python -m spacy download en_core_web_sm

#### 5. Run the app
uvicorn app:app --reload

## 🧪 How It Works
1.  Upload a Resume and paste a Job Description
2. Text is extracted and processed using NLP

3. Relevant skill keywords are extracted

4. Matched skills are compared and a score (%) is calculated

## 📌 Notes
- models/model.pkl, vectorizer.pkl, and encoder.pkl are placeholders (optional if you plan to expand with classification or ML scoring).

- Ensure Tesseract OCR is installed on your machine for image-based resumes:
➤ Install Tesseract OCR






