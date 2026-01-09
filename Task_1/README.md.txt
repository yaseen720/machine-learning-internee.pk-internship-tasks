# Intern Performance Prediction Model

Task 1: from Internee.pk Machine Learning Virtual Internship.

## Objective
Build a regression model to predict an intern's final performance score based on features like:
- Attendance Percentage
- Quiz Scores
- Hours Spent on Tasks
- Previous Experience
- Tasks Submitted on Time

## Results
- Best Model: Linear Regression with Polynomial Features (degree=2)
- R² Score: 0.774
- MAE: 3.83

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## How to Run
1. Clone repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook
4. Load the saved model: `joblib.load('intern_performance_prediction_model.pkl')`

## Screenshots
![Correlation Heatmap](screenshots/correlation_heatmap.png)
![Actual vs Predicted](screenshots/actual_vs_predicted.png)

Made with ❤️ during Internee.pk Internship 2026
