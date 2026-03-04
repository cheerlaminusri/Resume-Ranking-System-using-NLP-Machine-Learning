# Resume Ranking System using NLP & Machine Learning

## 📌 Overview
This project builds a Job Description and Resume Matching System using Python and Machine Learning techniques.  
The system streamlines the recruitment process by automatically ranking resumes based on their similarity to a given job description.

It helps recruiters quickly identify the most relevant candidates using text similarity scoring.

---

## 🚀 Features

- **Job Description Input**  
  Recruiters can enter a job description for analysis.

- **Resume Upload**  
  Multiple resumes (PDF, DOCX, TXT) can be uploaded.

- **Text Extraction Pipeline**  
  Automatically extracts text from uploaded resumes.

- **Matching Algorithm**  
  Uses TF-IDF vectorization and Cosine Similarity to compute similarity scores between resumes and the job description.

- **Resume Ranking**  
  Displays top matching resumes sorted by similarity score.

---

## 🧠 Machine Learning Approach

1. Convert job description and resumes into numerical vectors using **TF-IDF (Term Frequency-Inverse Document Frequency)**.
2. Compute similarity using **Cosine Similarity**.
3. Rank resumes based on similarity scores.

This is a traditional NLP-based Machine Learning approach (not Deep Learning).

---

## 🛠️ Technologies Used

- **Python** – Backend development
- **Flask** – Web framework for handling requests
- **Scikit-learn** – TF-IDF & similarity computation
- **PyPDF2 & docx2txt** – Resume text extraction
- **Bootstrap** – Responsive UI design
- **HTML/CSS** – Frontend structure and styling

---

## ▶️ How to Run Locally

1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Run the application: python main.py
4. Open in browser: http://127.0.0.1:5000/


