# 🚢 Task 1 – Titanic Survival Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter" />
  <img src="https://img.shields.io/badge/scikit--learn-ML-green?style=flat-square&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/CODTECH-AI%20Internship-red?style=flat-square" />
</p>

---

## 👤 Intern Information

| Field | Details |
|-------|---------|
| **Intern Name** | Khushi Kumari |
| **Intern ID** | CITS2079 |
| **Company** | CODTECH IT Solutions Pvt. Ltd. |
| **Domain** | Artificial Intelligence |
| **Mentor** | Neela Santhosh Kumar |
| **Duration** | 4 Weeks |

---

## 📌 Task Overview

Build a machine learning classification model to **predict passenger survival** on the Titanic using features like gender, age, ticket class, and fare.

---

## 📂 Project Structure

```
Task-1-Titanic-Survival-Prediction/
│
├── titanic.csv                          # Dataset (418 passengers)
├── Titanic_Survival_Prediction.ipynb    # Main Jupyter Notebook
└── README.md                            # This file
```

---

## 📊 Dataset Description

The dataset contains **418 passenger records** with the following features:

| Column | Description |
|--------|------------|
| `PassengerId` | Unique passenger identifier |
| `Survived` | **Target**: 0 = Not survived, 1 = Survived |
| `Pclass` | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| `Name` | Passenger name |
| `Sex` | Gender (male / female) |
| `Age` | Age in years |
| `SibSp` | No. of siblings/spouses aboard |
| `Parch` | No. of parents/children aboard |
| `Ticket` | Ticket number |
| `Fare` | Passenger fare |
| `Cabin` | Cabin number |
| `Embarked` | Port of Embarkation (C/Q/S) |

---

## 🔧 Technologies Used

- **Python 3.14.5**
- **Pandas** – Data loading and manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models

---

## 🤖 Models Used

| Model | Description |
|-------|-------------|
| **Logistic Regression** | Linear classification baseline model |
| **Random Forest Classifier** | Ensemble model (100 trees, best performer) |

---

## 📈 Key Findings

- 🚺 **Female passengers** had ~3× higher survival rate than males
- 🎟️ **1st class** passengers survived at nearly double the rate of 3rd class
- 👶 **Children under 15** had a higher chance of survival
- 💰 **Higher fare** correlated with better survival outcomes
- 🏆 **Most important feature**: `Sex` (gender)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/khushis1n/<repo-name>.git
   cd Task-1-Titanic-Survival-Prediction
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Titanic_Survival_Prediction.ipynb
   ```

---

---

*| CODTECH IT Solutions Pvt. Ltd. | AI Internship*
