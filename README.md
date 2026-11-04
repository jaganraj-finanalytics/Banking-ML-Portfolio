# Banking & Financial Machine Learning Portfolio

This repository contains two applied machine-learning projects using
public financial datasets.

## Projects

### 1. Financial Fraud Detection Using Machine Learning

**Notebook:** `Financial_Fraud_Detection_ML.ipynb`

-   Exploratory data analysis and data-quality checks
-   Handling severe class imbalance
-   Logistic Regression, Random Forest and XGBoost
-   Precision, Recall, F1-score, ROC-AUC and PR-AUC evaluation
-   Threshold selection and fraud-case review
-   Export-ready outputs for Power BI

**Dataset:** [Credit Card Fraud Detection --
Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Expected Kaggle input filename: `creditcard.csv`\
Target column: `Class`

### 2. Credit Risk & Loan Default Prediction

**Notebook:** `Credit_Risk_Loan_Default_Prediction.ipynb`

-   Exploratory analysis of borrower and loan characteristics
-   Data cleaning, feature engineering and leakage checks
-   Logistic Regression, Random Forest and XGBoost
-   Probability-of-default scoring and risk bands
-   Illustrative expected-credit-loss calculation using PD, LGD and EAD
-   Optional SQL exploration and Power BI export tables

**Dataset:** [Lending Club Loan Data --
Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club)

Expected input filename: `accepted_2007_to_2018Q4.csv`\
Target column: `loan_status`

## How to run on Kaggle

1.  Open the notebook on Kaggle or upload the `.ipynb` file to Kaggle
    Notebooks.
2.  In the notebook, use **Add Input** to attach the corresponding
    public Kaggle dataset.
3.  Confirm that the dataset filename and column names match the
    notebook's configuration. Update the file path if Kaggle mounts the
    data under a different folder.
4.  Run the notebook cells from top to bottom.
5.  For the Lending Club project, start with a manageable sample if the
    full dataset exceeds available memory.

## Important notes

-   These are portfolio starter notebooks. Run them against the attached
    datasets and review the outputs before presenting results.
-   Model metrics and findings should be reported only after executing
    the notebooks; this repository does not claim pre-computed
    performance.
-   The expected-credit-loss section is an educational illustration, not
    a regulatory or accounting estimate.
-   Do not upload private, confidential, client, employer, or personally
    identifiable data.
-   Public dataset availability and licensing are governed by the
    dataset publishers' terms.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost,
imbalanced-learn (where required), and optional DuckDB/Power BI.

## Author

Add your name and professional links here: - LinkedIn: \[Your LinkedIn
URL\] - Kaggle: \[Your Kaggle profile URL\]
