# project_04 Personalized Learning using Machine Learning

**Project Goal:**  
A Machine Learning web app that predicts a student's test score based on their study behavior and recommends personalized learning strategies.

---

## 📂 Project Structure
📂 PersonalizedLearningML
│
├── student_dataset_25.xls # Raw dataset
├── new_student_dataset_25.xls # Cleaned dataset
├── _data_cleaning.ipynb # Jupyter notebook for data cleaning
├── _eda.ipynb # Jupyter notebook for EDA (analysis)
├── _model_selection.ipynb # Model training and evaluation
├── personalized_model.pkl # Trained ML model
├── app.py # Streamlit web app
├── requirements.txt # Python package requirements
└── README.md # Project documentation

## 🔍 Input Features

- Hours Studied
- Previous Scores
- Assignments Completed
- Preferred Learning Style
- Favourite Subject

- ## 🎯 Output

- **Predicted Test Score** (out of 100)
- **Personalized Learning Suggestion** (e.g. visual, practical, theoretical)

- ## 📈 Process Overview

1. **Data Cleaning**
   - Removed null/missing values
   - Encoded categorical features
   - Exported cleaned dataset: `new_student_dataset_25.xls`

2. **EDA (Exploratory Data Analysis)**
   - Checked distribution of scores
   - Visualized correlation between features
   - Used boxplots, histograms, heatmaps

3. **Model Training**
   - Trained Linear Regression model
   - Evaluated using RMSE and R²
   - Saved model as `.pkl` file
  
4. 🎓 Inputs:
- Hours Studied: 7
- Previous Score: 80
- Assignments: 9
- Style: Visual
- Subject: Math

🔮 Prediction: 85.82 out of 100
📌 Suggestion: Visual study materials + more practice

✍️ Author
payal Tanaji Chougale
