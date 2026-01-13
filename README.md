# Heart Disease Prediction using Machine Learning

## Project Overview

This project focuses on building and evaluating supervised machine learning models to predict the presence of heart disease based on clinical and demographic data. The objective is to compare multiple classification algorithms and identify the most suitable model using robust evaluation metrics.

The project follows an end-to-end data science workflow and emphasizes reproducibility, model comparison, and data-driven decision making.

---

## Problem Statement

Cardiovascular diseases are among the leading causes of mortality worldwide. Early detection and risk assessment can support medical professionals in clinical decision making.

This project addresses a **binary classification problem**, predicting whether a patient is likely to have heart disease based on a set of clinical features.

---

## Dataset

* Structured tabular dataset containing patient information such as age, sex, chest pain type, cholesterol levels, blood pressure, and other medical indicators.
* Target variable: **presence or absence of heart disease**.
* Dataset includes both numerical and categorical features.

### Data Preparation

* Handling of categorical variables
* Feature scaling where required
* Train-test split for model evaluation

---

## Methodology

The project follows a standard machine learning pipeline:

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature preparation
3. Model training and hyperparameter tuning
4. Model evaluation and comparison
5. Selection of the best-performing model

This structured approach ensures consistency and reproducibility of results.

---

## Models and Evaluation

The following supervised machine learning models were implemented and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

### Evaluation Strategy

* Cross-validation for robust performance estimation
* Performance metrics:

  * Accuracy
  * Precision
  * Recall
  * F1-score
  * ROC-AUC

---

## Results

* Ensemble-based models (Random Forest and XGBoost) achieved the highest overall performance.
* Logistic Regression provided a strong and interpretable baseline model.
* Final model selection was based on a balance between predictive performance, robustness, and interpretability.

Detailed metric values and visualizations can be found in the project notebooks.

---

## Technologies Used

* **Python**
* **Pandas, NumPy**
* **Scikit-learn**
* **XGBoost**
* **Matplotlib, Seaborn**
* **Jupyter Notebook**

---

## How to Run

1. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib streamlit
```

2. Open the Jupyter notebook provided in the repository and execute the cells to train and evaluate the models.

3. After selecting the best-performing model, save it using `joblib`.

4. Navigate to the `src` folder in your terminal or command prompt.

5. Run the following command to start the Streamlit application:

```bash
streamlit run app.py
```

The Streamlit app will launch locally and allow interactive use of the trained model.

The trained model is stored in the `model/` directory and loaded by the Streamlit application for inference.

---

## Project Structure

```
heart_disease_prediction_project/
|
├── data/                 # Dataset files
├── model/                # Trained model artifacts
├── notebooks/            # Jupyter notebooks
├── src/                  # Application source code
└── README.md             # Project documentation
```

---

## Future Improvements

* Apply additional feature engineering techniques
* Perform more extensive hyperparameter optimization
* Explore model explainability methods (e.g., SHAP, feature importance)
* Evaluate model performance on external or larger datasets

---

## Academic Context

This project was developed as part of a **Machine Learning course** during an exchange program at **Hochschule Karlsruhe – University of Applied Sciences**.

**Academic Supervisor:** Prof. Sarah Haq

Sarah Haq's GitHub Profile: https://github.com/shaq31415926  
Course Repository: https://github.com/shaq31415926/ip302

---

## Author

**Matheus Caetano**
GitHub: [https://github.com/MatheusCaetano99](https://github.com/MatheusCaetano99)
