# Churn Sage: Leveraging Machine Learning and Explainable AI for Enhanced Customer Retention[cite: 1, 16]

[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E.svg)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-1b813e.svg)](https://xgboost.readthedocs.io/)

> A robust, machine learning-driven framework developed to forecast customer attrition using advanced predictive analytics, feature engineering, and Explainable AI (XAI)[cite: 1].

---

## 📋 Table of Contents
- [About the Project](#-about-the-project)
- [Authors & Affiliation](#-authors--affiliation)
- [Key Objectives](#-key-objectives)
- [Dataset & Preprocessing](#-dataset--preprocessing)
- [Methodology & Models](#-methodology--models)
- [Experimental Results](#-experimental-results)
- [Tech Stack](#-tech-stack)
- [Future Enhancements](#-future-enhancements)
- [References](#-references)

---

## 🚀 About the Project

In today's competitive market, customer retention is crucial for long-term business success, with acquiring a new customer costing up to five times more than retaining an existing one[cite: 1, 2]. **Churn Sage** is designed to proactively forecast customer churn by leveraging historical transaction data and user behavior patterns[cite: 1, 2]. 

By integrating classification algorithms, ensemble techniques, and **Explainable AI (XAI)**, Churn Sage helps organizations identify at-risk customers, understand the key drivers of attrition, and design targeted retention strategies[cite: 1, 2].

---

## 👥 Authors & Affiliation

- **Er. Disha Sharma** *(Assistant Professor)*[cite: 1]
- **Satyam Kumar**[cite: 1]
- **Chiranjeev Kumar Singh**[cite: 1]
- **Shivam Kumar**[cite: 1]
- **Anshul Gautam**[cite: 1]

*Department of Computer Science and Engineering (CSE), Chandigarh University, Mohali, Punjab, India[cite: 1, 16].*

---

## 🎯 Key Objectives

- **Predictive Model Development**: Build Python-based predictive systems to forecast customer churn[cite: 2].
- **Algorithm Utilization**: Implement models like Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting[cite: 2, 6].
- **Performance Optimization**: Apply feature engineering and hyperparameter tuning using GridSearchCV to maximize accuracy[cite: 2, 7].
- **Explainable AI Integration**: Provide transparency into decision-making processes to identify core churn drivers[cite: 2].
- **Scalability**: Demonstrate cross-industry applicability in domains like e-commerce and telecommunications[cite: 1, 2].

---

## 📊 Dataset & Preprocessing

- **Source**: Customer behavior and transaction details sourced from an e-commerce platform[cite: 6].
- **Key Variables Analyzed**:
  - **Transaction Frequency**: How often a customer makes purchases[cite: 12].
  - **Platform Usage Time**: Overall engagement levels on the platform[cite: 12].
  - **Purchase Recency**: The date and timing of the last transaction[cite: 12].
- **Preprocessing Pipeline**:
  - Removal of irrelevant features (e.g., Customer ID) and handling missing values[cite: 6].
  - Numerical normalization using `StandardScaler`[cite: 6].
  - Categorical transformation using Label Encoding[cite: 6].
  - Data split into an 80-20 train-test ratio[cite: 7].

---

## ⚙️ Methodology & Models

Churn Sage evaluates a wide range of supervised machine learning classifiers:
1. **Baseline & Traditional Models**: Logistic Regression, Decision Trees, and K-Nearest Neighbors (KNN)[cite: 6, 12, 13].
2. **Advanced Boosting Algorithms**: XGBoost, LightGBM, CatBoost, and Gradient Boosting[cite: 6, 9].
3. **Ensemble Methods**: Voting Classifier and Stacking Classifier utilizing soft/majority voting to reduce variance and bias[cite: 6, 11].
4. **Hyperparameter Tuning**: Optimized using 5-fold cross-validation via `GridSearchCV`[cite: 7].

---

## 📈 Experimental Results

Model performance was evaluated using accuracy, precision, recall, F1-score, and ROC-AUC curves[cite: 7]. Ensemble and boosting techniques significantly outperformed traditional baseline models[cite: 11, 13].

| Model | Accuracy (%) |
| :--- | :--- |
| **Tuned Stacking Classifier** | **97.51**[cite: 14] |
| **Stacking Classifier** | **97.33**[cite: 14] |
| **Voting Classifier** | **96.81**[cite: 14] |
| **Bagging Classifier** | **94.84**[cite: 14] |

*Note: The XGBoost model achieved an impressive ROC-AUC score of **0.96**, demonstrating exceptional class differentiation capabilities[cite: 9, 10].*

---

## 🛠️ Tech Stack

- **Language**: Python 3.7[cite: 10]
- **Data Manipulation**: Pandas, NumPy[cite: 10]
- **Visualization**: Matplotlib, Seaborn[cite: 10]
- **Machine Learning**: Scikit-Learn, XGBoost, LightGBM, CatBoost[cite: 10]

---

## 🔮 Future Enhancements

- **Real-Time Pipelines**: Implement real-time data pipelines for instantaneous churn evaluation[cite: 14].
- **Deep Learning**: Explore complex neural network architectures (e.g., RNNs, LSTMs) to handle larger datasets[cite: 14].
- **Unsupervised Clustering**: Integrate customer segmentation and behavior clustering to uncover hidden patterns[cite: 14].

---

## 📚 References

1. Shahabikargar, M., et al. "Generative AI-enabled Knowledge Base Fine-tuning: Enhancing Feature Engineering for Customer Churn." (2024)[cite: 15].
2. Phumchusri, N., & Amornvetchayakul, P. "Machine learning models for predicting customer churn: a case study in a software-as-a-service inventory management company." IJBIDI (2024)[cite: 15].
3. Ahmad, A. K., Jafar, A., & Aljoumaa, K. "Customer churn prediction in telecom using machine learning in big data platform." Journal of Big Data (2019)[cite: 16].