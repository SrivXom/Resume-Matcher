# 🧾 AI Resume Matcher using TF-IDF + Cosine Similarity

A Streamlit web app that helps recruiters screen multiple resumes by matching them against a job description using NLP techniques like TF-IDF and cosine similarity.
---
##  Features

-  Upload multiple PDF resumes
-  NLP-based text preprocessing (lowercasing, stopword removal)
-  Match each resume with job description using **TF-IDF + Cosine Similarity**
-  Ranks candidates by match score
-  View example matched content from resumes
-  Built with: `streamlit`, `scikit-learn`, `nltk`, `PyPDF2`, `pandas`
---

## How It Works

Extracts raw text from PDF resumes using PyPDF2
Preprocesses the text (lowercasing, punctuation removal, stopword filtering)
Converts resumes and job description to TF-IDF vectors
Computes cosine similarity to evaluate how closely each resume matches the job
Displays ranked results and example content

## Acknowledgements

NLTK & Scikit-learn for NLP
Streamlit for interactive UI
PyPDF2 for PDF handling

