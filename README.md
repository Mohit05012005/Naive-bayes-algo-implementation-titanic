# Titanic Survival Prediction using Naive Bayes

This project uses the Titanic dataset to predict passenger survival using the **Naive Bayes** classification algorithm.  
It is implemented in Python with **pandas**, **NumPy**, **scikit-learn**, and **matplotlib/seaborn** for data handling and visualization.

---

## 📂 Dataset
The dataset used is `titanic.csv`, containing passenger details such as:
- Passenger ID
- Name
- Sex
- Age
- Passenger class (`Pclass`)
- Number of siblings/spouses (`SibSp`)
- Number of parents/children (`Parch`)
- Ticket number
- Fare
- Cabin
- Embarked (Port of Embarkation)
- Survival status (`Survived`)

---

## ⚙️ Steps in the Notebook
1. **Import Libraries**  
   Load required Python libraries for data analysis, visualization, and machine learning.

2. **Load Dataset**  
   Read `titanic.csv` into a pandas DataFrame.

3. **Data Cleaning & Preprocessing**  
   - Drop irrelevant columns.
   - Handle missing values.
   - Encode categorical variables if necessary.

4. **Model Training**  
   Train a Naive Bayes classifier on the cleaned dataset.

5. **Model Evaluation**  
   - Evaluate accuracy on the test set.
   - Display classification metrics.

6. **Visualization**  
   Optional plots to understand the dataset distribution and survival patterns.

---

## 🛠 Requirements
Install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook "titanic_naive_baye's.ipynb"

