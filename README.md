# Resume Analyzer

## Overview

The **Resume Analyzer** is a Python-based application designed to automatically extract and analyze key information from resumes. It processes resume files (PDF format) and identifies structured data such as skills, education, experience, and other relevant attributes to assist in resume screening and evaluation.

This project is intended for academic use, learning purposes, and as a foundational system for recruitment automation.

---

## Features

- Upload and analyze resume PDFs
- Extract key sections such as:
  - Skills
  - Education
  - Experience
- Modular Python codebase for easy extension
- Environment-variable-based configuration
- Simple and clean project structure

---

## Prerequisites

Ensure the following are installed on your system:

- Python **3.9 or higher**
- `pip` (Python package manager)
- Git (for cloning)

---

## Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/Nayak72/Resume_Analyzer.git
```
```
cd Resume_Analyzer
```
---

### 2. Create a Virtual Environment (Recommended)
```bash
python3 -m venv venv
```
```bash
source venv/bin/activate   # Linux / macOS
```
```bash
venv\Scripts\activate      # Windows
```
---
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
---
4. Configure Environment Variables

Create a .env file in the project root:
```env
FLASK_ENV=development
FLASK_APP=app.py
GEMINI_API_KEY=your_gemini_api_key_here
```

Replace your_gemini_api_key_here with your actual Gemini API key.

---
Running the Application
```bash
python app.py
```
Once started, the application will be available at:
```bash
http://127.0.0.1:5000/
```
Upload a resume PDF through the interface to analyze it.

---

Usage Notes

Only PDF resumes are supported.

The accuracy of extraction depends on resume formatting.

This project is modular and can be extended with NLP or ML models.

---

Security Notes

The .env file is intentionally excluded from version control.

Do not upload sensitive data or real resumes to public repositories.

---

Future Enhancements

1.Integration with NLP / ML models

2.Resume scoring and ranking

3.Support for DOCX resumes

4.Database-backed candidate storage

5.Admin dashboard

---

Academic Disclaimer

This project is developed for educational and academic purposes.
It is not intended for production deployment without further validation, optimization, and security hardening.

---
Author

Koushik Nayaka U

Saharsha 

Harshavardhan N

---
License

This project is open for academic and learning use.
