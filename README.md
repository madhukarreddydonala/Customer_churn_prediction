# Customer Churn Prediction

This repository contains an end-to-end machine learning project for predicting customer churn using historical telecom data. The goal is to identify customers who are likely to cancel their subscription, enabling proactive retention strategies.

## 📊 Project Overview

- **Data Source:** [WA_Fn-UseC_-Telco-Customer-Churn.csv](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Tech Stack:** Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn, imbalanced-learn (SMOTE)
- **Notebook:** `CUSTOMER_CHRUN.ipynb`

## 🚀 Features

- Data loading and exploration
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Handling missing values and outliers
- Encoding categorical variables
- Addressing class imbalance with SMOTE
- Model training (Decision Tree, Random Forest, XGBoost)
- Model evaluation and comparison
- Model saving and loading for prediction

## 🛠️ How to Run

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/customer-churn-prediction.git
    cd customer-churn-prediction
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook CUSTOMER_CHRUN.ipynb
    ```

4. **(Optional) Predict with the saved model:**
    - Load `customer_model.pkl` and use it to predict churn on new data.

## 📁 Files

- `CUSTOMER_CHRUN.ipynb` — Main notebook with code and explanations
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — Dataset (not included, download from Kaggle)
- `customer_model.pkl` — Trained Random Forest model (generated after running the notebook)
- `encoders.pkl` — Label encoders for categorical features

## 📈 Results

- Random Forest achieved the highest accuracy among tested models.
- The notebook includes detailed evaluation metrics and visualizations.

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

**Author:** DONALA MADHUKAR REDDY
