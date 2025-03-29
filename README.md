This Project built as Part of AICTE- Internship on AI: Transformative Learning with TechSaksham – A joint CSR initiative of Microsoft & SAP, focusing on AI Technologies. 
project title : AI-powered Resume Screening and Ranking System 

# AI Resume Screening & Candidate Ranking System

This project is a simple web application built with Streamlit that extracts text from PDF resumes and ranks them based on a provided job description. It uses TF-IDF vectorization and cosine similarity from scikit-learn to determine how well each resume matches the job description.

## Features

- **Extract Text from PDF:** Uses PyPDF2 to read and extract text from PDF files.
- **Resume Ranking:** Ranks uploaded resumes based on their similarity to a provided job description using TF-IDF vectorization and cosine similarity.
- **Interactive UI:** Built with Streamlit for an easy-to-use web interface.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/kranthii-k/resume-screening.git
   cd your-repository

python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

pip install -r requirements.txt

streamlit run app.py

your-repository/
├── app.py         # Main application script (contains the code)
├── README.md              # This file
└── requirements.txt       # Python dependencies
