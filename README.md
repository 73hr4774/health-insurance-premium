# 🏥 Health Insurance Premium Prediction

This project focuses on predicting health insurance premiums using demographic and lifestyle data. It aims to assist insurance companies in determining accurate premium amounts for individuals based on various factors such as age, BMI, smoking habits, and more.

---

## 🔍 Problem Statement

Insurance companies need a reliable model to estimate the premium amount for a new customer based on their health and demographic profile. This predictive modeling helps optimize pricing strategies and manage risk.

---

## 📊 Dataset Information

- Source: [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Total Records: 1,338
- Features:
  - `age`: Age of the policyholder
  - `sex`: Gender
  - `bmi`: Body Mass Index
  - `children`: Number of dependents
  - `smoker`: Smoking status
  - `region`: Residential region
  - `charges`: Annual insurance premium (target)

---

## ⚙️ Tech Stack

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Modeling**: Linear Regression, Random Forest Regressor
- **Deployment**: Streamlit

---

## 🚀 How to Run Locally

1. Clone the repository  
```bash
git clone https://github.com/73hr4774/health-insurance-premium.git
cd health-insurance-premium

2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py

## 📌 Key Features

- Interactive **Streamlit app**
- End-to-end ML pipeline: preprocessing → training → prediction
- Trained on regression algorithms (Linear Regression, Random Forest, etc.)
- Feature importance and model evaluation

---

## 🌐 Deployed App

🔗 https://health-insurance-premium-zone.streamlit.app/

## 📥 Feedback & Contributions

Pull requests and suggestions are welcome. If you find any issues, feel free to open an issue or drop feedback. Thanks!

