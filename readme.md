# German Credit Risk Prediction

A machine learning web application that predicts whether a loan applicant is likely to be a **Good** or **Bad** credit risk based on demographic and financial information.

## Live Demo

 **Streamlit App:** https://german-credit-risk-modeling.streamlit.app/


---

## Project Overview

Financial institutions assess an applicant's creditworthiness before approving loans. This project leverages machine learning to automate credit risk assessment using applicant demographic and financial data.

The final model was deployed as an interactive Streamlit application that allows users to enter applicant details and obtain an instant prediction of credit risk.

---

## Dataset

This project uses the **German Credit Data with Risk** dataset from Kaggle.

Dataset Source:

https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk

The dataset contains information about loan applicants, including:

* Age
* Sex
* Job
* Housing
* Saving Accounts
* Checking Account
* Credit Amount
* Duration of Loan

### Target Variable

* **Good** — Low credit risk
* **Bad** — High credit risk

---

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) was conducted to understand feature distributions, relationships between variables, and patterns associated with credit risk.

Techniques used include:

* Descriptive statistics
* Correlation analysis
* Distribution plots
* Class balance analysis

---

## Model Development

Several classification algorithms were trained and evaluated:

* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier
* Extra Trees Classifier

Hyperparameter tuning was performed using **GridSearchCV** to identify the optimal model configuration.

### Best Performing Model

**Extra Trees Classifier**

Evaluation metric:

* Accuracy Score

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Joblib
* Streamlit

---

## Application Screenshots

### Prediction result

![Prediction Result](/images/prediction%201.png)

### Prediction Result

![Prediction Result](/images/prediction%202.png)

---

## Project Structure

```text
German-Credit-Risk-Modeling/

├── app.py
├── requirements.txt
├── extra_trees_credit_model.pkl
├── Sex_encoder.pkl
├── Housing_encoder.pkl
├── Saving accounts_encoder.pkl
├── Checking account_encoder.pkl
├── images/
│   ├── prediction 1.png
│   └── prediction 2.png
├── notebooks/
└── README.md
```

---

## Running the Project Locally

Clone the repository

```bash
git clone https://github.com/marykamithi/German-Credit-Risk-Modeling.git
```

Navigate to the project folder

```bash
cd German-Credit-Risk-Modeling
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## Future Improvements

* Add probability scores for predictions
* Include model explainability using SHAP
* Deploy multiple models for comparison
* Improve the user interface with custom styling

---

## Author

**Mary Kamithi**

GitHub: https://github.com/marykamithi

LinkedIn: https://linkedin.com/in/marykamithi
