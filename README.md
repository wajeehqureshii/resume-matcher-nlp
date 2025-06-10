# resume-matcher-nlp
An NLP-powered project that parses resumes and ranks job descriptions based on relevance using TF-IDF vectorization and cosine similarity. This tool helps job seekers identify their best-fitting roles based on actual content match.
# Resume Matcher NLP – Job Ranking Tool

This project uses Natural Language Processing (NLP) to match a resume against multiple job descriptions and rank them based on textual relevance.

## 🔍 What It Does

- Parses a given resume (text format)
- Compares it with a list of job descriptions
- Uses **TF-IDF vectorization** and **cosine similarity** to score each match
- Outputs a ranked list showing which job is the best fit

## 📌 Example Use Case

You're applying to 10 jobs and want to know:
> "Which ones actually match my resume based on skills, tools, and responsibilities?"

This tool gives you a **data-driven answer**.

## 🧠 Tech Stack

- Python  
- scikit-learn  
- Pandas  
- NLTK  
- Cosine Similarity  
- TF-IDF Vectorizer  

## 🧹 Features

- Basic text preprocessing: stopword removal, lemmatization, lowercasing
- Smart ranking using cosine distance
- Fully modular – can be expanded to accept `.pdf` or `.docx` uploads (via `pdfminer`, `docx2txt`)
- Can be extended to a Streamlit web app

## 🧪 Sample Output

| Job Description                                   | Match Score |
|--------------------------------------------------|-------------|
| Data Analyst – Python, SQL, Tableau              | 0.82        |
| Business Analyst – Excel, Stakeholder Reporting | 0.68        |
| ML Engineer – Deep Learning, TensorFlow          | 0.44        |

## 🚀 Future Improvements

- Add a file uploader to handle PDF or DOCX resumes
- Streamlit UI for live scoring
- Optional reverse matching: input job → find top resumes

## 🧑‍💻 Created by

**Wajeeh Qureshi**  
Rutgers Business School – Management Information Systems  
[LinkedIn](https://www.linkedin.com/in/wajeeh-qureshi-9708b6293) | [GitHub](https://github.com/wajeehqureshii)

