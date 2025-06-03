# 🎓 Student Performance Predictor

This project builds a machine learning model to predict students' final grades using behavioral, academic, and social data. It applies both **Linear Regression** and **Random Forest Regression** with hyperparameter tuning.

---

## 🚀 Quick Start

### 🔗 Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/student-performance-predictor/blob/main/student_performance_predictor.ipynb)

---

## 📂 Project Structure

```text
student-performance-predictor/
├── student_performance_predictor.ipynb   # Main Colab notebook
├── student_data.csv                      # Dataset
├── requirements.txt                      # Python dependencies
├── README.md                             # Project documentation
```

---

## 📊 Features

- Linear Regression baseline
- Random Forest Regressor with GridSearchCV tuning
- Feature importance analysis
- Visualizations of predictions and key drivers
- Google Drive integration for persistence

---

## 🧠 ML Stack

- **Languages**: Python
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn, numpy
- **Algorithms**: Linear Regression, Random Forest

---

## 🗃️ Dataset

Uses a cleaned subset of the [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance).

Key features used:

- Study time
- Failures
- Absences
- Parental education
- Internet access
- Romantic relationship status
- Grades from previous terms

---

## 📦 Installation (for local use)

```bash
pip install -r requirements.txt
```
