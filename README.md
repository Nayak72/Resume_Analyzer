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

## Project Structure

resume_analyzer/
│
├── app.py # Main application entry point
├── requirements.txt # Python dependencies
├── .env # Environment variables (not committed)
├── resume_analyzer/
│ ├── utils/
│ │ ├── pdf_extract.py
│ │ ├── skill_extract.py
│ │ ├── education_extract.py
│ │ ├── exper_test.py
│ │ └── db_operations.py
│ ├── templates/ # HTML templates (if applicable)
│ └── static/ # Static assets (CSS/JS)
│
└── README.md


---

## Prerequisites

Ensure the following are installed on your system:

- Python **3.9 or higher**
- `pip` (Python package manager)
- Git (optional, for cloning)

---

## Installation Steps

### 1. Clone the Repository

git clone https://github.com/<your-username>/resume_analyzer.git
cd resume_analyzer

###2. Create a Virtual Environment (Recommended)

python3 -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows

###3. Install Dependencies
pip install -r requirements.txt

###4. Configure Environment Variables

Create a .env file in the project root:

FLASK_ENV=development
FLASK_APP=app.py

Modify or extend variables if required by your setup.

##Running the Application
python app.py

Once started, the application will be available at:

http://127.0.0.1:5000/

Upload a resume PDF through the interface to analyze it.

###Usage Notes

Only PDF resumes are supported.

The accuracy of extraction depends on resume formatting.

This project is modular and can be extended with NLP or ML models.

###Security Notes

The .env file is intentionally excluded from version control.

Do not upload sensitive data or real resumes to public repositories.

###Future Enhancements

1.Integration with NLP / ML models

2.Resume scoring and ranking

3.Support for DOCX resumes

4.Database-backed candidate storage

5.Admin dashboard

6.Academic Disclaimer

This project is developed for educational and academic purposes. It is not intended for production deployment without further validation, optimization, and security hardening.

###Author

Koushik Nayaka U
Saharsha
Harshavardhan N
3rd Semester Engineering Student

###License

This project is open for academic and learning use.
