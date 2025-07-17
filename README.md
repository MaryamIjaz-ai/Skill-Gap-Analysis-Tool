# Skill-Gap-Analysis-Tool
📊 Skill Gap Analysis Tool using NLP + Clustering
🔍 Objective
This project identifies skill gaps between interns and industry job requirements using Natural Language Processing (TF-IDF) and KMeans Clustering. It also suggests relevant training resources to help interns bridge those gaps.

🧠 Technologies & Libraries
Python

Pandas

Scikit-learn (TF-IDF, KMeans, Cosine Similarity)

Seaborn & Matplotlib (for visualization)

WordCloud (optional)

Jupyter/Google Colab

📂 Dataset Sources
Intern Skills: Internships Skill Dataset

Industry Job Descriptions: Job Description Dataset

✅ Features
Extracts and preprocesses intern skill data

Processes industry job descriptions

Creates clusters of job skill profiles using KMeans

Matches interns to closest industry cluster via cosine similarity

Identifies missing skills (skill gaps)

Suggests relevant online courses for upskilling

Generates visual insights (bar charts, word clouds)

Saves result as CSV for easy analysis/reporting

📊 Visualizations
Top 10 most commonly missing skills
Word cloud of all missing skills

📚 Training Recommendations
Maps missing skills to online learning platforms (Coursera, Udemy, edX) using a predefined dictionary of resources.

🚀 How to Run (Google Colab Recommended)
Upload internships.csv and job_descriptions.csv

Run the notebook cells step-by-step

View output CSV and visualizations



