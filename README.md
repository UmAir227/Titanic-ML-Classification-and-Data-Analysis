# Titanic Data Analysis & Machine Learning

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/1200px-RMS_Titanic_3.jpg)

## 📊 Project Overview
Comprehensive analysis of the Titanic dataset to predict passenger survival using machine learning. Includes exploratory data analysis, data cleaning, visualization, and predictive modeling.

## 🎯 Objectives
- Analyze factors affecting survival rates
- Build predictive models for survival classification
- Compare different machine learning algorithms

## 📁 Dataset Features
- **PassengerId**: Unique ID
- **Survived**: Survival (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: # of siblings/spouses aboard
- **Parch**: # of parents/children aboard
- **Fare**: Passenger fare
- **Embarked**: Port of embarkation

## 🔍 Key Insights
- Women had 74.2% survival rate vs 18.9% for men
- 1st class passengers had 63% survival vs 24% for 3rd class
- Children had higher survival rate (54%) than adults (36%)
- Higher fare = Better survival chances

## 🛠️ Technologies Used
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📈 Machine Learning Models & Accuracy
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|-----------|
| Logistic Regression | 81.0% | 0.83 | 0.87 | 0.85 |
| Random Forest | 83.2% | 0.85 | 0.89 | 0.87 |
| Decision Tree | 79.3% | 0.81 | 0.84 | 0.82 |
| SVM | 80.4% | 0.82 | 0.86 | 0.84 |
| K-Nearest Neighbors | 78.2% | 0.80 | 0.83 | 0.81 |

### 🔍 Best Performing Model: **Random Forest (83.2% Accuracy)**
- Highest accuracy among all classifiers
- Robust to overfitting
- Handles non-linear relationships well

### 📊 Key Metrics Explanation:
- **Accuracy**: Overall correctness of the model
- **Precision**: How many predicted survivors actually survived
- **Recall**: How many actual survivors were correctly identified
- **F1-Score**: Balanced measure of precision and recall
- 

## 👨‍💻 Author
Muhammad Umair Azeem
