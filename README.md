🎓 Student Performance Predictor

A Machine Learning model to predict whether a student will pass or fail based on academic scores and other demographic data.

## Features
- Predicts **Pass/Fail** outcome
- Uses Logistic Regression with 100% accuracy on test data
- Analyzes feature importance
- Data preprocessing with one-hot encoding
- Easily deployable with Streamlit

##  Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

##  Dataset
This project uses a student performance dataset containing:
- Math, Reading, Writing scores
- Gender, Race/Ethnicity
- Parental education level
- Lunch type
- Test preparation course

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/jananisathyamoorthy/student-performance-predictor.git
   ```
2. Open `predict_student.ipynb` in Google Colab or Jupyter Notebook
3. Run all cells

##  Model Performance
- **Accuracy:** 100% on test data
- **Top 3 features:**
  1. Writing Score
  2. Math Score
  3. Reading Score

##  Future Enhancements
- Add Streamlit Web App
- Try other ML algorithms (Random Forest, XGBoost)
- Deploy on HuggingFace Spaces

---

 Author: Janani Sathyamoorthy
