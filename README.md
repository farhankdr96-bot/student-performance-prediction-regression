# 📈 Student Performance Prediction Using Machine Learning

## 📌 Overview

Student performance is influenced by multiple academic and personal factors. This project leverages Machine Learning Regression techniques to predict a student's Performance Index based on study habits, previous academic achievements, sleep patterns, extracurricular activities, and practice efforts.

The project demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, model training, prediction, and evaluation.

---

## 🎯 Problem Statement

Educational institutions can benefit from understanding the factors that influence student performance. The objective of this project is to build a regression model capable of predicting a student's Performance Index using various academic and lifestyle attributes.

---

## 📊 Dataset Information

The dataset includes the following features:

| Feature | Description |
|----------|------------|
| Hours Studied | Number of hours spent studying |
| Previous Scores | Previous academic scores |
| Extracurricular Activities | Participation in extracurricular activities |
| Sleep Hours | Average daily sleep hours |
| Sample Question Papers Practiced | Number of practice papers solved |

### 🎯 Target Variable

**Performance Index**

A numerical score representing overall student performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Collection
- Loaded dataset using Pandas.
- Inspected data structure and feature types.

### 2. Data Preprocessing
- Checked for missing values.
- Encoded categorical variables.
- Prepared features for model training.

### 3. Exploratory Data Analysis (EDA)
- Dataset summary statistics.
- Distribution analysis.
- Relationship analysis using visualizations.

### 4. Data Splitting
- Training Set: 70%
- Testing Set: 30%

### 5. Model Development
Implemented:

- Linear Regression

### 6. Prediction
- Predicted student performance on unseen data.

### 7. Model Evaluation
Performance evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Results

The Linear Regression model achieved strong predictive performance and demonstrated the relationship between study habits and student outcomes.

### Evaluation Metrics

- MAE
- MSE
- RMSE
- R² Score

---

## 📂 Project Structure

Student-Performance-Prediction-Regression/

├── Regression_Project.ipynb

├── Student_Performance.csv

├── README.md

├── requirements.txt

└── images/

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/student-performance-prediction-regression.git
```

Move to the project directory:

```bash
cd student-performance-prediction-regression
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 💡 Key Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Regression Modeling
- Model Evaluation
- Performance Prediction
- Data Visualization

---

## 🚀 Future Enhancements

- Compare Multiple Regression Algorithms
- Hyperparameter Tuning
- Feature Importance Analysis
- Streamlit Web Application Deployment
- Real-Time Prediction Dashboard

---

## 📚 Skills Demonstrated

- Machine Learning
- Regression Analysis
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Predictive Analytics
- Python Programming
- Scikit-learn

---

## 👨‍💻 Author

Mohd Farhan
