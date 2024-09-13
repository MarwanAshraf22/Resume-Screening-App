# Resume Screening App

This project is a machine learning-based Resume Screening App that aims to automate the process of scanning and filtering resumes for recruitment purposes. The app extracts key skills from resumes and matches them against job descriptions, ranking resumes based on their relevance to the job requirements.

## Features
- Upload multiple resumes in PDF or Word format.
- Extracts text from resumes using OCR (for images) and text extraction methods (for PDF/Word).
- Uses Natural Language Processing (NLP) techniques to identify relevant skills, experience, and qualifications.
- Compares extracted data with the job description.
- Ranks resumes based on their relevance to the job requirements.
- Generates a report on the ranking and matching results.

## Prerequisites
- Python 3.x
- Jupyter Notebook (optional for running the `.ipynb` file)
- The following Python packages:
  - `pandas`
  - `numpy`
  - `nltk`
  - `scikit-learn`
  - `PyPDF2`
  - `docx`
  - `pdfplumber`
  - `re`

Install the required packages using the following command:

```bash
pip install -r requirements.txt
