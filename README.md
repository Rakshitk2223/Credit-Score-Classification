# Credit Scoring Classification

## Project Overview
This project focuses on building and evaluating machine learning models for credit scoring classification. The goal is to predict whether a loan applicant is likely to default or not, based on various financial and demographic features. The analysis is performed in a Jupyter Notebook using Python.

## Key Steps and Methodology
- **Data Loading and Exploration:**
  - Loaded a credit scoring dataset and performed exploratory data analysis (EDA) to understand the distribution and relationships of features.
  - Visualized data using plots to identify trends and outliers.
- **Data Preprocessing:**
  - Handled missing values and outliers.
  - Encoded categorical variables and scaled numerical features for optimal model performance.
- **Model Building:**
  - Implemented and compared 5 different classification algorithms: Random Forest, XGBoost, Decision Tree, K-Nearest Neighbors, and Gaussian Naive Bayes.
  - Used train-test split and cross-validation to ensure robust evaluation.
- **Model Evaluation:**
  - Assessed model performance using accuracy, precision, and recall metrics across multiple algorithms:
    - **Random Forest**: Accuracy: 81.50%, Precision: 80.50%, Recall: 80.95% (Best performer)
    - **XGBoost**: Accuracy: 77.38%, Precision: 75.88%, Recall: 76.33%
    - **Decision Tree**: Accuracy: 72.39%, Precision: 70.56%, Recall: 70.56%
    - **K-Nearest Neighbors**: Accuracy: 69.79%, Precision: 67.05%, Recall: 67.99%
    - **Gaussian Naive Bayes**: Accuracy: 64.19%, Precision: 63.31%, Recall: 68.73%
  - Visualized confusion matrices and performance comparisons for deeper insights.
- **Feature Importance:**
  - Analyzed feature importances to interpret which variables most influence credit risk predictions.
- **Conclusion:**
  - Random Forest emerged as the best-performing model with 81.50% accuracy and balanced precision-recall metrics.
  - Successfully identified key factors influencing credit risk with quantifiable model performance.

## Technologies Used
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn, plotly, XGBoost)
- Jupyter Notebook
- Machine Learning Algorithms: Random Forest, XGBoost, Decision Tree, K-NN, Gaussian Naive Bayes

---

*This README provides an overview and summary suitable for sharing in a portfolio or resume context.*
