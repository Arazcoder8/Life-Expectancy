# Machine Learning Project for Heart data

---

## 📌 Overview
Goal of this Dataset is to find which country has more Life Expectancy.

---

## 📊 about Dataset 
* Number of Columns : 22
* Number of Rows : 2938
* Number of Duplicates : 0
* Number of Nan Values : 2563
* * Columns : [ 'Country', 'Year', 'Status', 'Life_expectancy', 'Adult_Mortality',
       'infant_deaths', 'Alcohol', 'percentage_expenditure', 'Hepatitis_B',
       'Measles', 'BMI', 'under-five_deaths', 'Polio', 'Total_expenditure',
       'Diphtheria', 'HIV/AIDS', 'GDP', 'Population', 'thinness__1-19_years',
       'thinness_5-9_years', 'Income_composition_of_resources', 'Schooling' ]
* Target : Life_expectancy
* Regression Problem


---

## 🧠 Models
Models Used :

* Linear Regression
* Random Forest Regression
* Gradient Boosting Regression
* XGBoost Regression

---

## ⚙️ Preprocessing

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Scaling
* Missing Value Imputation
* Hyperparameter Tuning
* Model Evaluation
* Evaluation Metrics

---

## 🛠️ Technologies

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Joblib

---

## 📊 Model Evaluation
The model Evaluated by MAE (mean absolute error) , MSE (mean squared error) , RMSE (root mean squared error) , R2 (r2 score)

---

## 📈 Results

Best Model is Random Forest

| Model | MAE | MSE | RMSE | R2 | 
|------|----------|-----------|--------|-------|
| Random Forest | 1.03668 | 2.660873 | 1.631218 | 0.96991 |

---

## 📂 Project Structure

```text
.
├── data/
├── images/
├── models/
├── Heart.ipynb
├── README.md
└── requirements.txt
```

---

▶️ How to Run

Install requirements :
```text

pip install requirements.txt

```
then run ipynb file