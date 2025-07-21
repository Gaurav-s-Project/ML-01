# Student Reading Score Predictor 📊

This project is a simple machine learning web application that predicts a student's **reading score** based on their **math score**, **writing score**, and demographic features such as gender, race, parental education, lunch type, and test preparation status.

## 🔍 Overview

- **Dataset Source:** [Kaggle – Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **ML Algorithm Used:** Linear Regression
- **Frontend:** HTML, CSS, JavaScript (JavaScript part built using ChatGPT)
- **Backend:** Python with Flask (Flask backend built using ChatGPT)
- **Deployment:** [Live Demo on Netlify](https://grv-machine01.netlify.app/)

## 📦 Features

- User inputs scores and demographic details through a form.
- Data is sent to a Flask backend which loads the trained model (`model.pkl`) and returns the predicted reading score.
- Clean and interactive UI with dynamic input fields.
- Suitable for learning regression-based ML deployment.

## 🧠 ML Pipeline

- **Target Variable:** `reading_score`
- **Training Features:**
  - `math_score`
  - `writing_score`
  - Encoded Demographics:
    - `gender`
    - `race/ethnicity`
    - `parental level of education`
    - `lunch`
    - `test preparation course`
- **Steps Involved:**
  - Data Cleaning
  - Label Encoding & One-Hot Encoding
  - Feature Engineering
  - Data Visualization
  - Model Training using `LinearRegression` from Scikit-learn
  - Model Saved as `model.pkl`

## 📝 How to Run Locally

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/student-score-predictor.git
   cd student-score-predictor
