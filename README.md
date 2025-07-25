# ML-Based-Fraud-Detection-Model

This project focuses on building a machine learning model to detect fraudulent transactions using a real-world financial dataset containing over 6 million records. The goal is to proactively identify suspicious activity and derive actionable insights that can help prevent financial fraud.

## Dataset

- The dataset consists of 6,362,620 rows and 10 columns.
- It includes features such as transaction type, amount, old and new balances, and fraud labels.
- Source: Provided by internship task guidelines (not publicly hosted here due to size).

## Objectives

- Perform data cleaning, including handling outliers and checking for multicollinearity.
- Explore and analyze key transaction patterns.
- Train classification models to predict fraudulent transactions.
- Evaluate model performance using appropriate metrics.
- Derive business-level insights and suggest fraud prevention strategies.

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Key Steps

1. **Data Preprocessing**: 
   - Handled missing values and outliers in the `amount` column.
   - Checked multicollinearity using Variance Inflation Factor (VIF).

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed class imbalance and feature distributions.
   - Visualized transaction types and fraud patterns.

3. **Modeling**:
   - Trained and evaluated Logistic Regression and Random Forest models.
   - Metrics used: Accuracy, Precision, Recall, F1-score, and ROC-AUC.

4. **Insights**:
   - Identified high-risk transaction types (e.g., TRANSFER, CASH_OUT).
   - Proposed strategies for real-time fraud detection and prevention.

## Results

- Random Forest outperformed Logistic Regression in recall and ROC-AUC.
- Key indicators of fraud included transaction amount, type, and account balances.
- Business recommendations were made based on the model's findings.

## How to Run

1. Clone this repository.
2. Open the `project.ipynb` file using Jupyter Notebook or VSCode.
3. Ensure required libraries (`pandas`, `sklearn`, etc.) are installed.
4. Replace the data path with your local dataset if required.

## License

This project was created as part of an internship task and is for educational and demonstration purposes only.

**NOTE**
The dataset used in this project is not included in the repository due to its large size and external hosting. Please refer to the original source or contact me if access is required
