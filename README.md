# Machine Learning Internship - Internee.pk

This repository contains the projects and tasks completed during my Machine Learning internship at **Internee.pk**. The internship focused on applying various ML techniques to solve real-world problems in the context of an internship platform, ranging from predictive modeling to NLP and recommendation systems.

## Projects Overview

| Task | Project Name | Key Technologies | Description |
| :--- | :----------- | :--------------- | :---------- |
| 01 | [Intern Performance Prediction](./Task_1_Per_Prediction)** | Python, XGBoost, Scikit-learn | Predicts intern success based on engagement and assessment metrics. |
| 02 | [Sentiment Analysis](./Task_2_sentiment_analysis)** | BERT, NLP, Logistic Regression | Analyzes intern feedback to monitor satisfaction and improve the program. |
| 03 | [Learning Path Recommendation](./Task_3_Learn_Path)** | Collaborative Filtering, Embeddings | Recommends personalized learning paths based on intern interests and skills. |
| 04 | [AI Interview Question Generator](./Task_4_AI_Question_generator)** | Pandas, Rule-based AI | Generates tailored interview questions for different internship roles. |
| 05 | [Skill Gap Analysis Tool](./Task_5_Research_Gap)** | PCA, Clustering, Data Analysis | Identifies missing skills in intern profiles compared to industry requirements. |
| 06 | [AI Chatbot Support](./Task-6_chatbot_intenrship_support)** | Cosine Similarity, Embeddings | FAQ-based chatbot to provide instant support to interns. |

## Detailed Task Summaries

### 1. Intern Performance Prediction
- **Goal**: Predict whether an intern will successfully complete the internship.
- **Methodology**: Used historical data of intern engagement, quiz scores, and project submissions. 
- **Model**: XGBoost Regressor/Classifier.
- **Results**: Achieved high accuracy in identifying at-risk interns based on early engagement patterns.
- **Artifacts**: [Report](./Reports/Intern_Performance_Prediction_Report.pdf), [Notebook](./Task_1_Per_Prediction/ML_Task1.ipynb)

### 2. Sentiment Analysis on Intern Feedback
- **Goal**: Understand intern satisfaction through textual feedback.
- **Methodology**: Performed EDA and applied BERT-based sentiment classification.
- **Results**: Identified key areas of improvement (e.g., more technical workshops) and positive aspects (e.g., mentorship quality).
- **Artifacts**: [Report](./Reports/sentiment_analysis.pdf), [Notebook](./Task_2_sentiment_analysis/sentiment-analysis.ipynb)

### 3. Personalized Learning Path Recommendation System
- **Goal**: Suggest courses and projects to interns based on their profile.
- **Methodology**: Implemented a hybrid recommendation engine using user-item interaction matrices.
- **Results**: Successfully mapped intern skill sets to relevant learning paths.
- **Artifacts**: [Report](./Reports/learning_path_recommendation_system.pdf), [Notebook](./Task_3_Learn_Path/Learning-Path-system.ipynb)

### 4. AI-Powered Interview Question Generator
- **Goal**: Automate the creation of technical interview questions.
- **Methodology**: Keyword extraction and role-based question mapping.
- **Results**: Streamlined the interview process for recruiters by providing relevant questions for roles like Data Analyst, ML Engineer, and Web Dev.
- **Artifacts**: [Report](./Reports/AI_powered_interview_questions_generator.pdf), [Notebook](./Task_4_AI_Question_generator/AI-Powered-Interview-Question-Generator.ipynb)

### 5. Skill Gap Analysis Tool
- **Goal**: Help interns identify which technical skills they need to acquire.
- **Methodology**: Comparative analysis of intern profiles against target job descriptions using clustering.
- **Results**: Generated personalized "Gap Reports" with recommended skills for each intern.
- **Artifacts**: [Report](./Reports/Skill_gap_analysis_tool.pdf), [Notebook](./Task_5_Research_Gap/Skill-Gap-Analysis-Tool.ipynb)

### 6. AI Chatbot for Internship Support
- **Goal**: Provide 24/7 automated assistance for common intern queries.
- **Methodology**: Semantic search using Sentence Embeddings and Cosine Similarity.
- **Results**: Reduced the load on the support team by handling 80% of common FAQ queries instantly.
- **Artifacts**: [Report](./Reports/AI_chatbot_for_internship_support.pdf), [Notebook](./Task-6_chatbot_intenrship_support/chatbot.ipynb)

## Installation & Usage

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost transformers torch
   ```
3. Explore the Jupyter notebooks in each task folder to see the implementation.

## Repository Structure
```text
Machine learning internship/
├── Task_1_Per_Prediction/
├── Task_2_sentiment_analysis/
├── Task_3_Learn_Path/
├── Task_4_AI_Question_generator/
├── Task_5_Research_Gap/
├── Task-6_chatbot_intenrship_support/
├── Reports/ (PDF Files)
└── README.md
```
