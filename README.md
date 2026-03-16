# 🎬 Netflix User Watching Behavior — Supervised Learning Classification

## 📌 Project Overview

This project applies **supervised machine learning classification** techniques to analyze and predict Netflix user watching behavior. The goal is to build and evaluate classification models that can identify patterns in user engagement and predict behavioral categories based on viewing data.

---

## 📂 Dataset

- **Source:** [Kaggle — Netflix User Watching Behavior Dataset](https://www.kaggle.com/datasets/rhythmghai/netflix-user-watching-behavior-dataset)
- **Format:** CSV
- **Description:** Contains features related to Netflix users' watching habits, including viewing duration, genres, frequency, and engagement metrics.

---

## 🎯 Objectives

- Explore and preprocess the dataset (EDA)
- Apply supervised classification algorithms
- Evaluate and compare model performance
- Identify the best model for predicting user behavior

---

## 🧠 Models Used

| Model | Description |
|-------|-------------|
| Logistic Regression | Linear baseline classifier |
| Decision Tree | Interpretable tree-based model |
| Random Forest | Ensemble of decision trees |
| K-Nearest Neighbors (KNN) | Distance-based classifier |
| Support Vector Machine (SVM) | Margin-based classifier |
| XGBoost | Gradient boosting classifier |

---

## 🛠️ Technologies & Libraries

```
Python 3.x
├── pandas          # Data manipulation
├── numpy           # Numerical computing
├── matplotlib      # Data visualization
├── seaborn         # Statistical plots
├── scikit-learn    # ML models & evaluation
└── xgboost         # Gradient boosting
```

---

## 📊 Workflow

```
1. Data Loading
      ↓
2. Exploratory Data Analysis (EDA)
      ↓
3. Data Preprocessing
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
      ↓
4. Model Training & Cross-Validation
      ↓
5. Model Evaluation
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC Curve
      ↓
6. Best Model Selection
```

---

## 📈 Evaluation Metrics

- **Accuracy** — Overall correctness of the model
- **Precision** — Ratio of correct positive predictions
- **Recall** — Ability to find all positive cases
- **F1-Score** — Harmonic mean of precision and recall
- **Confusion Matrix** — Detailed classification breakdown
- **ROC-AUC** — Area under the receiver operating characteristic curve

---

## 🗂️ Project Structure

```
Mini-Project_Supervised_Learning/
│
├── data/
│   └── netflix_user_watching_behavior.csv
│
├── notebooks/
│   └── classification_model.ipynb
│
├── models/
│   └── best_model.pkl
│
├── .gitignore
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Mohamed-Thamer-BenBaccar/netflix_user_ML.git
cd netflix_user_ML
```

### 2. Create a virtual environment
```bash
python -m venv ml-env
ml-env\Scripts\activate      # Windows
source ml-env/bin/activate   # Mac/Linux
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

---

## 📋 Requirements

Create a `requirements.txt` with:
```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
jupyter
kagglehub
```

---

## 👤 Author

**Mohamed Thamer Ben Baccar**
- GitHub: [@Mohamed-Thamer-BenBaccar](https://github.com/Mohamed-Thamer-BenBaccar)

---

## 🏫 Academic Context

> Mini-Project — Supervised Learning
> Module: Machine Learning avec Python — Analyse et Programmation
