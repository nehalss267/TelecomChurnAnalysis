# Telecom Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-green)

## 📖 Overview
This project focuses on **Customer Churn Prediction** in the telecommunications industry. By analyzing customer demographics, service usage, and billing patterns, the system identifies customers who are at high risk of leaving (churning). 

The project implements and compares three different machine learning approaches—**Logistic Regression**, **Support Vector Machines (SVM)**, and **Artificial Neural Networks (ANN)**—to determine the most effective model for this classification task.

## ❓ Problem Statement
In the telecom sector, retaining existing customers is significantly more cost-effective than acquiring new ones. Churn often occurs "silently" due to dissatisfaction or better competitor offers. 

**The Goal:** Build a predictive model that allows the telecom provider to proactively identify at-risk customers and intervene with retention strategies, thereby reducing revenue loss.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression, SVM, Neural Network)

## ⚙️ Project Workflow
1.  **Data Cleaning:**
    * Handled missing values.
    * Removed irrelevant columns.
    * Converted categorical target variables to numeric values.
2.  **Exploratory Data Analysis (EDA):**
    * Visualized churn rates against Tenure, Monthly Charges, and Contract types using Seaborn.
3.  **Feature Engineering:**
    * **One-Hot Encoding** for categorical variables (e.g., Internet Service, Payment Method).
    * **MinMax Scaling** for numerical columns (`tenure`, `MonthlyCharges`, `TotalCharges`) to normalize data between 0 and 1.
4.  **Model Training:**
    * **Logistic Regression:** Baseline probabilistic model.
    * **SVM:** For finding optimal hyperplanes in high-dimensional space.
    * **Neural Network:** Multi-layer perceptron with ReLU activation and Sigmoid output.
5.  **Evaluation:**
    * Generated Classification Reports (Precision, Recall, F1-Score).
    * Created Heatmaps to visually compare model performance.

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/telecom-churn-analysis.git](https://github.com/yourusername/telecom-churn-analysis.git)
    cd telecom-churn-analysis
    ```

2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3.  **Place the dataset:**
    Ensure `Telecom-Customer-Churn.csv` is in the project root directory.

4.  **Run the script:**
    ```bash
    python telcomchurnanalysis.py
    ```
---
