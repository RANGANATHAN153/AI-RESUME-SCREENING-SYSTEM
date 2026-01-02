# AI-RESUME-SCREENING-SYSTEM
This project is prepared with ai, python, sql and powerbi  using that csv dataset from kaggle to choose whether the person is eligible to hire or reject according to ats score of his/her resume.
🤖 AI Resume Screening System – Data Analysis Project
📌 Project Overview

The AI Resume Screening System is a data-driven application designed to automate the initial resume shortlisting process using Python, Machine Learning, and Data Analysis techniques.
The system analyzes resumes, extracts key features, assigns an AI-based score, and classifies candidates as Suitable or Not Suitable for a given job role. This helps recruiters save time, reduce manual effort, and make unbiased decisions.

🎯 Problem Statement

Recruiters often receive hundreds of resumes for a single job opening.
Manual screening is:

Time-consuming

Prone to human bias

Inefficient for large datasets

This project solves the problem by automating resume analysis and screening using AI and data analytics.

🧠 Solution Approach

We built an end-to-end AI Resume Screening System that:

Takes resume data as input

Cleans and preprocesses the data

Extracts important features

Applies machine learning algorithms

Generates predictions and insights using data analysis

🗂️ Dataset Description

The dataset contains structured resume-related information such as:

Candidate name

Skills

Education level

Years of experience

Certifications

Job role

AI score (generated)

Final screening decision

The dataset is used both for training the model and for data analysis & visualization.

🔍 Data Analysis Steps Performed
1️⃣ Data Collection & Loading

Imported resume dataset using Pandas

Verified data types and structure

2️⃣ Data Cleaning

Removed null and duplicate records

Standardized text fields (skills, roles)

Converted categorical values into numerical format

3️⃣ Exploratory Data Analysis (EDA)

We analyzed:

Distribution of experience levels

Skill frequency across candidates

Education vs suitability trends

AI score distribution

Suitable vs Not Suitable ratio

Used:

Pandas for aggregation

Matplotlib & Seaborn for visual analysis

⚙️ Feature Engineering

Key features created:

Skill match score

Experience weight

Education level score

Certification bonus

These features significantly improved prediction accuracy.

🤖 Machine Learning Model

Algorithm used: Logistic Regression / Random Forest

Data split: Training & Testing

Target variable: Suitable / Not Suitable

Model accuracy achieved: 80% – 90%

📊 Model Evaluation

Evaluation metrics used:

Accuracy Score

Confusion Matrix

Precision & Recall

The model performed well in identifying suitable candidates while minimizing false positives.

🧪 AI Resume Scoring Logic

Each resume is assigned an AI Score based on:

Skill relevance

Years of experience

Education qualification

Certifications

Final decision logic:

AI Score ≥ threshold → Suitable

AI Score < threshold → Not Suitable

🖥️ Output & Results

Automated resume classification

Ranked candidate list based on AI score

Clear decision labels for recruiters

Analytical insights for hiring trends

🛠️ Tools & Technologies Used

Python

Pandas, NumPy – Data processing

Matplotlib, Seaborn – Visualization

Scikit-learn – Machine learning

Jupyter Notebook / VS Code

🚀 Key Achievements

Reduced manual resume screening effort

Improved screening accuracy

Implemented real-world AI hiring use case

Built scalable and reusable ML pipeline

🔮 Future Enhancements

Resume parsing using NLP (PDF & DOCX)

Skill extraction using TF-IDF or embeddings

Web-based interface using Flask/Streamlit

Integration with job portals

📌 Conclusion

This project demonstrates how AI and Data Analysis can be effectively used to automate resume screening.
It highlights practical applications of Python, Machine Learning, and analytics in solving real-world recruitment challenges.
