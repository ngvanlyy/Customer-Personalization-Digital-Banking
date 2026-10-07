# 🏦 Customer Personalization in Digital Banking

**Python · Behavioural Embeddings · XGBoost · SHAP · Contextual Bandits**

A Master's research project developing an adaptive personalization framework for digital banking using customer transaction behaviour.

## 🔗 Google Colab

**[Open the Research Project in Google Colab](https://colab.research.google.com/drive/1dDksVX6wX-9zdWdycVwTA7rc1Lmhl5dM?usp=sharing)**

The notebook contains the complete implementation of the data preprocessing, behavioural embeddings, XGBoost modelling, SHAP explainability and contextual bandit simulation.

## 📌 Project Overview

The project investigates how customer behavioural patterns can be represented and used to support personalised financial product recommendations.

The research combines:

- 🧠 **Behavioural Embeddings** using an autoencoder
- 📈 **XGBoost** for predictive modelling
- 🔍 **SHAP** for model explainability
- 🎯 **Contextual Bandits** for adaptive recommendations

The project follows the **ASUM-DM** methodology and uses the **Czech Financial Dataset**.

## 🔧 Methodology

The workflow includes:

- Data integration and preprocessing
- Transaction-level feature engineering
- Behavioural feature aggregation
- Autoencoder-based behavioural embeddings
- XGBoost modelling
- SMOTE for class imbalance
- Hyperparameter tuning
- SHAP-based explainability
- Contextual bandit simulation using ε-greedy and LinUCB

## 📊 Key Results

The tuned XGBoost model achieved:

- **78% recall** for the positive class
- **F1-score: 0.38**
- **ROC-AUC: 0.7466**

The contextual bandit simulation achieved a **78.43% acceptance rate for loan recommendations** after 100 simulated interactions.

## 🔍 Key Insights

- Behavioural embeddings provided compact representations of customer financial activity.
- SMOTE improved minority-class detection.
- Hyperparameter tuning improved model recall and ROC-AUC.
- SHAP was used to identify behavioural features influencing model predictions.
- Contextual bandit simulation demonstrated adaptive recommendation based on user feedback.

## 📊 Dataset

The project uses the **Czech Financial Dataset**, a relational banking dataset containing customer, account, transaction, loan and card information.

The dataset was sourced from the **PKDD'99 Discovery Challenge** and used to construct customer behavioural features for digital banking personalization.

The raw dataset is **not included in this repository due to file size limitations**.

## 🛠️ Tools

`Python` · `Google Colab` · `XGBoost` · `SHAP` · `scikit-learn` · `TensorFlow/Keras` · `SMOTE` · `pandas` · `NumPy`

## 📁 Repository Structure

```text
Customer-Personalization-Digital-Banking/
│
├── README.md
├── Research-Project.pdf
└── research-project-artefact.py
```

## 📄 Research Report

The full research report documents the methodology, data preparation, behavioural embedding approach, predictive modelling, explainability analysis, contextual bandit simulation and evaluation.

## 🎓 Research Project

This project was completed as part of an **MSc Data Analytics research project** and demonstrates the application of machine learning, representation learning, explainable AI and adaptive recommendation methods to digital banking personalization.
