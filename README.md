# 🚢 Titanic Survival Prediction Model

Titanic Survival Prediction Model is a machine learning project that aims to predict whether a passenger would have survived the Titanic disaster based on features like age, gender, class, and more. It utilizes classification algorithms to process and analyze data from the iconic Titanic dataset.

## 📌 Table of Contents

- [About](#-about)
- [Tech Stack](#-tech-stack)
- [Working](#-working)
- [Dataset Description](#-dataset-description)
- [Project Structure](#-project-structure)
---

## 🔎 About

This project applies fundamental machine learning techniques to one of the most popular datasets in the data science community—**Titanic: Machine Learning from Disaster**. The model is trained to classify whether a passenger survived or not based on attributes like:

- Age  
- Gender  
- Passenger class (Pclass)  
- Number of siblings/spouses aboard  
- Number of parents/children aboard  
- Fare  
- Embarked location  

The goal is to understand and implement the full pipeline of a data science project—from cleaning data to training models and evaluating their performance.

---

## 🛠 Tech Stack

- **Language**: Python  
- **Libraries**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `xgboost`

- **IDE**: Jupyter Notebook / VS Code

---

## ⚙️ Working

1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Feature engineering and scaling

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing survival trends across age, gender, and class
   - Correlation heatmaps and bar plots

3. **Model Training**:
   - Trained multiple models: Logistic Regression, Decision Tree, Random Forest, XGBoost
   - Evaluated using accuracy, precision, recall, and confusion matrix

4. **Prediction**:
   - Final model predicts whether a person would survive based on their input features.

---

## 📊 Dataset Description

The dataset used in this project is the famous [Titanic dataset](https://www.kaggle.com/competitions/titanic/data) from Kaggle’s Machine Learning competition.

**Key Features:**
| Feature        | Description                            |
|----------------|----------------------------------------|
| `Survived`     | Target variable (0 = No, 1 = Yes)      |
| `Pclass`       | Passenger class (1, 2, 3)              |
| `Sex`          | Gender                                 |
| `Age`          | Age in years                           |
| `SibSp`        | # of siblings/spouses aboard           |
| `Parch`        | # of parents/children aboard           |
| `Fare`         | Ticket fare                            |
| `Embarked`     | Port of Embarkation (C, Q, S)          |

---

## 📁 Project Structure

```bash
titanic_survival_prediction_model/
│
├── Titanic_model.ipynb                  # Main notebook with full workflow
├── train.csv                            # Training dataset
├── predict.csv                          # Deployment Testing 
└── README.md                            # Project documentation


