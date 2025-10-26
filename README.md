# 🚢 Titanic Data Mining Project

### 🎯 Objective
This project explores the famous **Titanic dataset** from [Kaggle](https://www.kaggle.com/c/titanic) to understand passenger survival patterns and build a **machine learning model** (Decision Tree) to predict survival.

---

## 📂 Project Structure

| Folder / File                                           | Description                                      |
| ------------------------------------------------------- | ------------------------------------------------ |
| `data/train.csv`                                        | Original Titanic dataset                         |
| `data/clean_train.csv`                                  | Cleaned and preprocessed dataset                 |
| `notebooks/01_titanic_data_exploration.ipynb`           | Data loading and exploration                     |
| `notebooks/02_titanic_data_visualization.ipynb`         | Basic visualizations                             |
| `notebooks/03_titanic_quantitative_relationships.ipynb` | Relationships between quantitative variables     |
| `notebooks/04_titanic_qualitative_relationships.ipynb`  | Relationships between qualitative variables      |
| `notebooks/05_titanic_mixed_relationships.ipynb`        | Mixed relationships (quantitative ↔ qualitative) |
| `notebooks/06_titanic_data_preprocessing.ipynb`         | Data cleaning, missing values, encoding          |
| `notebooks/07_titanic_decision_tree_model.ipynb`        | Decision Tree model and prediction               |


---

## 🔍 Project Overview

The **Titanic** dataset contains information about passengers such as:
- Age, Sex, and Class (`Pclass`)
- Number of family members aboard (`SibSp`, `Parch`)
- Ticket fare (`Fare`)
- Port of embarkation (`Embarked`)
- Survival status (`Survived`)

This project focuses on:
1. 🧹 **Data Cleaning & Preprocessing**  
   - Handling missing values  
   - Encoding categorical features  
   - Creating a cleaned dataset  

2. 📊 **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics  
   - Visualizations of categorical and numerical variables  
   - Correlations and relationships between variables  

3. 🌲 **Modeling**  
   - Building a **Decision Tree classifier**  
   - Evaluating model accuracy  
   - Interpreting feature importance  

---

## 🧰 Tools & Libraries

| Category | Libraries |
|-----------|------------|
| Data Manipulation | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Statistics | `scipy` |
| Machine Learning | `scikit-learn` |
| Environment | `Jupyter Notebook` |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Maryem-Laabidi/titanic-data-mining.git
cd titanic-data-mining
``` 

###2️⃣ Install dependencies

pip install -r requirements.txt

###3️⃣ Launch Jupyter Notebook

jupyter notebook

###📈 Key Insights

- Survival Rate: ~38% of passengers survived.

- Gender Impact: Women had a much higher survival rate than men.

- Class Difference: First-class passengers were more likely to survive than third-class.

- Age Effect: Younger passengers had a slightly higher survival chance.

###🤖 Model Summary

- Algorithm: Decision Tree Classifier

- Accuracy: (add your trained model results)

- Important Features: Sex, Pclass, Age, Fare



