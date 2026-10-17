# FinGuard – Financial Fraud Detection & Transaction Intelligence

## 📌 Project Overview

FinGuard is a web-based financial analytics application that helps analyze credit card transactions and identify potentially fraudulent activities. It transforms transaction data into interactive dashboards and analytical reports to support fraud investigation and risk assessment.

The project demonstrates practical data analytics concepts, including data visualization, data quality validation, classification metrics, threshold analysis, and transaction-level investigation.

## 🎯 Objectives

* Analyze credit card transaction patterns.
* Identify transactions labeled as potentially fraudulent.
* Display important financial and fraud-related KPIs.
* Evaluate a baseline fraud-detection model.
* Explore precision, recall, F1-score, and confusion matrix results.
* Support transaction filtering, investigation tracking, and report exports.

## ✨ Key Features

* Interactive financial dashboard with KPI cards.
* CSV dataset upload and analysis.
* Transaction search and filtering.
* Interactive charts and visual summaries.
* Browser-based logistic regression baseline.
* Model evaluation using precision, recall, F1-score, and a confusion matrix.
* Adjustable classification threshold.
* Ranked transaction investigation queue.
* Investigation review-status tracking.
* Hypothetical financial-impact simulator.
* Data-quality checks and validation.
* CSV exports and printable summary reports.
* Responsive interface with dark and light themes.

## 📊 Dataset

The project is designed to work with the **Credit Card Fraud Detection** dataset available on Kaggle.

Dataset link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The original dataset contains 284,807 transactions and 492 fraud cases. Its main columns are:

* `Time` – Time elapsed between the first transaction and the transaction being recorded.
* `V1` to `V28` – Anonymized numerical features produced using Principal Component Analysis (PCA).
* `Amount` – Transaction amount.
* `Class` – Target label: `0` for a legitimate transaction and `1` for a fraudulent transaction.

The included demo CSV contains synthetic demonstration data and is not a real bank transaction dataset. Model results from the demo should not be treated as real-world fraud-detection performance.

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Chart.js
* PapaParse
* Logistic regression baseline
* CSV data processing

## 🚀 How to Run the Project

1. Download or clone the project files.
2. Extract the ZIP file if you downloaded the project package.
3. Open `index.html` in Google Chrome or another modern browser.
4. Select the **Load Demo Data** option to explore the dashboard.
5. Open the Model Lab and train or retrain the baseline model.
6. Download the Kaggle dataset and upload its CSV file to analyze the real dataset.
7. Explore the charts, filters, model metrics, investigation queue, and export options.

An internet connection is required for external libraries loaded through CDNs.

## 📈 Analytical Metrics

FinGuard presents several metrics for understanding fraud-detection performance:

* **Precision:** The proportion of transactions flagged as fraudulent that are actually labeled as fraud.
* **Recall:** The proportion of actual fraud cases detected by the model.
* **F1-score:** A combined measure of precision and recall.
* **Confusion Matrix:** A summary of correct and incorrect fraud classifications.
* **Classification Threshold:** The decision cutoff used to classify a transaction as potentially fraudulent.

Because fraudulent transactions are rare in this dataset, accuracy alone is not sufficient to evaluate a model.

## 💼 Business Value

A fraud analytics dashboard can help analysts explore suspicious transaction patterns, prioritize cases for review, and understand the trade-off between detecting fraud and incorrectly flagging legitimate transactions.

The financial-impact simulator is hypothetical and should not be interpreted as verified savings or actual bank losses.

## ⚠️ Limitations

* This project is an educational prototype, not a production banking system.
* The browser-based model is a baseline and should not be considered production-ready.
* The included demo dataset is synthetic.
* The original dataset's `V1`–`V28` features are anonymized; they do not directly reveal merchant names, customer identities, or transaction locations.
* Advanced techniques such as SHAP explanations, Isolation Forest, rigorous cross-validation, and SQL-based processing are not implemented in this version.
* Model results require further validation before any real-world use.

## 🔮 Future Enhancements

* Develop a Python backend using Flask or FastAPI.
* Add advanced fraud-detection models.
* Implement SHAP-based model explanations.
* Integrate SQL for structured transaction analysis.
* Add cross-validation and class-imbalance handling.
* Build automated model comparison and monitoring.
* Add secure user authentication and audit logging.

## 👩‍💻 Project Purpose

This project was developed as a data analytics portfolio project to demonstrate dashboard development, data analysis, visualization, classification evaluation, and financial risk analytics.

**Disclaimer:** FinGuard is intended for educational and portfolio purposes only. It does not provide financial advice or make production banking decisions.
