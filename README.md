# 💼 Skill-Based Job Recommendation System using NLP

## 🧠 Overview
This project is a machine learning and NLP-based system that recommends jobs to users based on their listed skills. It uses cosine similarity to match user-provided skills with job descriptions.

---

## 📂 Dataset
- `job_title_des.csv`: Contains job titles and corresponding job descriptions.
- Sample records: ~1,000+
- Features: `Job Title`, `Description`
- Dataset created or sourced from public job listings.

---

## 🤖 Model Used
- **Text Preprocessing**: Lowercasing, punctuation removal, tokenization
- **Vectorization**: TF-IDF (Term Frequency–Inverse Document Frequency)
- **Similarity Metric**: Cosine Similarity

---

## 📈 How it Works
1. User provides a set of skills (e.g., "Python, Machine Learning, SQL")
2. System vectorizes input and job descriptions using TF-IDF
3. Cosine similarity is calculated between user input and all jobs
4. Top 5 most relevant jobs are recommended

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/22asim26/job-recommendation-system.git
   cd job-recommendation-system
