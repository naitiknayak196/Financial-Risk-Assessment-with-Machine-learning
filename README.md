Financial Risk Assessment

📌 Project Overview

This project focuses on financial risk assessment using credit card transaction data. The goal is to clean, preprocess, and analyze financial data to develop insights that can help in evaluating creditworthiness and risk profiling. The dataset is processed using Python, and all cleaning steps are documented in a Jupyter Notebook.

📂 Dataset Information

The dataset used for this project is Credit Card dataset.csv. It contains various financial attributes of customers, including:

Customer ID

Credit Score

Income Level

Loan Amount

Debt-to-Income Ratio

Payment History

Default Indicators

🔍 Data Cleaning & Processing

The dataset underwent extensive cleaning and preprocessing, including:

Handling Missing Values: Imputation and removal of records with excessive missing data.

Outlier Detection: Identifying and treating extreme values.

Feature Engineering: Creating new variables, including a Credit Risk Score, which is based on multiple financial indicators.

Standardization & Normalization: Scaling numerical features for better model performance.

📜 Methodology & Code Explanation

The cleaning and preprocessing steps are implemented in the Jupyter Notebook Credit Card Scoring.ipynb. This notebook includes:

Exploratory Data Analysis (EDA): Understanding data distribution and relationships.

Data Cleaning: Applying transformations and handling inconsistencies.

Feature Engineering: Creating new predictive variables, including a Credit Risk Score based on key financial metrics.

Machine Learning Models for Credit Risk Assessment:

XGBoost: A high-performance gradient boosting model used for classification.

Random Forest: A robust ensemble decision tree model that provides feature importance insights.

K-Nearest Neighbors (KNN): A distance-based algorithm to classify credit risk groups.

Model Evaluation: The performance of each model was assessed using accuracy, precision, recall, and AUC-ROC curves:

Random Forest Accuracy: 77%

XGBoost Accuracy: 76%

KNN Accuracy: 72%

Random Forest showed the best trade-off between accuracy and interpretability.

🚀 Installation & Usage

To run this project locally, follow these steps:

Prerequisites

Ensure you have the following installed:

Python 3.x

Jupyter Notebook

Required Libraries: pandas, numpy, matplotlib, seaborn, sklearn, xgboost

Steps to Run

Clone the repository:

git clone https://github.com/yourusername/financial-risk-assessment.git
cd financial-risk-assessment

Install dependencies:

pip install -r requirements.txt

Open Jupyter Notebook and run Credit Card Scoring.ipynb:

jupyter notebook

📊 Insights & Findings

Customers with high debt-to-income ratios tend to have lower credit scores.

Payment history is the most critical factor in determining creditworthiness.

Certain income brackets exhibit higher default probabilities.

The Credit Risk Score, developed through feature engineering, improves prediction accuracy.

Random Forest achieved the highest accuracy (77%), making it the best-performing model.

XGBoost performed slightly lower at 76% but offers high scalability for larger datasets.

KNN struggled with imbalanced data, leading to a lower accuracy of 72%.

📁 Repository Structure

financial-risk-assessment/
│── Credit Card dataset.csv        # Cleaned dataset
│── Credit Card Scoring.ipynb      # Jupyter Notebook with code
│── README.md                      # Project documentation

🤝 Contribution

Contributions are welcome! If you’d like to improve the project:

Fork the repository.

Create a feature branch (git checkout -b feature-name).

Commit your changes (git commit -m 'Add new feature').

Push to the branch (git push origin feature-name).

Open a pull request.

📞 Contact

For questions, feel free to reach out via email or open an issue in the repository.

🚀 Happy Coding!

