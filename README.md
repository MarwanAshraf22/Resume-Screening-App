# Resume-Screening-App

This project is a machine learning-based Resume Screening App that aims to automate the process of scanning and filtering resumes for recruitment purposes. The app extracts key skills from resumes and matches them against job descriptions, ranking resumes based on their relevance to the job requirements.

Features
Upload multiple resumes in PDF or Word format.
Extracts text from resumes using OCR (for images) and text extraction methods (for PDF/Word).
Uses Natural Language Processing (NLP) techniques to identify relevant skills, experience, and qualifications.
Compares extracted data with the job description.
Ranks resumes based on their relevance to the job requirements.
Generates a report on the ranking and matching results.
Prerequisites
Python 3.x
Jupyter Notebook (optional for running the .ipynb file)
The following Python packages:
pandas
numpy
nltk
scikit-learn
PyPDF2
docx
pdfplumber
re
Install the required packages using the following command:

bash
Copy code
pip install -r requirements.txt
How to Use
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/MarwanAshraf22/Resume-Screening-App.git
Navigate to the project directory:

bash
Copy code
cd Resume-Screening-App
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook
Open the Resume Screening App.ipynb file in Jupyter.

Run the cells sequentially to:

Load resumes.
Extract and preprocess data.
Compare resumes with job descriptions.
Rank resumes based on relevance.
Check the output for a ranking of resumes.

Project Structure
Resume Screening App.ipynb: The main notebook that contains the code for resume screening.
requirements.txt: The file to install required Python packages.
data/: Directory to store resumes and job descriptions.
output/: Directory where the ranked resumes are saved.
Future Enhancements
Integrate the app into a web interface for easier usage.
Improve the NLP model to handle more complex job descriptions.
Add support for more resume formats (e.g., HTML, TXT).
Optimize the ranking algorithm for better accuracy.
Contributing
Feel free to fork this project, open issues, or submit pull requests with improvements. Contributions are always welcome!
