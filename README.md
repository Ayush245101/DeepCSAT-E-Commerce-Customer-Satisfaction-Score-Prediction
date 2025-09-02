<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2331/2331970.png" width="100" />
  <h1 align="center">E-commerce Customer Support CSAT Analysis & Prediction</h1>
  <p align="center"><em>🤖 Predicting & Classifying Customer Satisfaction using Artificial Neural Networks</em></p>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Python-3.10-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/Contributions-Welcome-ff69b4?style=flat-square" />
</p>

---

## 📌 Overview

This project focuses on **analyzing and predicting Customer Satisfaction (CSAT) scores** for an e-commerce platform’s customer support system.  
We built **Artificial Neural Network (ANN) models** for both regression (predicting continuous CSAT scores) and classification (High vs. Low CSAT), providing **actionable insights** for businesses to improve customer experience.

---

### 🔍 Problem Statement

Customer satisfaction is a **key performance metric** for e-commerce businesses.  
This project addresses:
- Can we **predict CSAT scores** from support-related data?  
- Which factors **influence satisfaction levels** the most?  
- Can we automatically **classify customers** as satisfied or dissatisfied?  

---

## 📊 Dataset

- 📂 File: `eCommerce_Customer_support_data.csv`  
- 🧾 Format: CSV  
- 📈 Size: ~10,000+ records  
- 🎯 Features: `Issue Category`, `Product Category`, `Item Price`, `Handling Time`, `Remarks`, `CSAT Score`

---

## 🔧 Tools & Technologies

<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-FB9820?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-orange?style=flat&logo=tensorflow&logoColor=white" />
</p>

---

## 🚀 Project Workflow

| Step                   | Details                                                                 |
|------------------------|-------------------------------------------------------------------------|
| 🧹 Data Cleaning       | Missing values handled, duplicates removed                             |
| ⚙️ Feature Engineering | Handling time (min), remarks length                                    |
| 📊 EDA                 | Histograms, correlation heatmaps, feature distributions                |
| 🔤 Preprocessing       | Encoding categorical variables, scaling numerical features             |
| 🧠 Modeling            | ANN Regression (CSAT prediction) & ANN Classification (High vs. Low CSAT) |
| 📉 Evaluation          | Regression → MSE, MAE, R²; Classification → Accuracy, Confusion Matrix |
| 📈 Feature Importance  | Identified most influential features (Remarks length, Product Category, Item Price) |

---

## 🧠 Models and Evaluation

| Model                  | Task         | Metrics / Results                       |
|------------------------|-------------|-----------------------------------------|
| ANN Regression         | Predict CSAT | R² ≈ 0.047 (moderate predictive power)  |
| ANN Classification     | High/Low CSAT | Accuracy: **82.9%**, Confusion Matrix   |

📌 *Classification outperformed regression in terms of actionable insights.*

---

## 📊 Visualizations

- ✅ Confusion Matrix → Classification accuracy visualization  
- ✅ Feature Importance Bar Chart → Key factors driving satisfaction  
- ✅ Training History Curves → Model accuracy & loss over epochs  

---

👀 **Explore the full project on GitHub**:  
[![View Project](https://img.shields.io/badge/View_Project-GitHub-black)](https://github.com/Ayush245101/DeepCSAT-E-Commerce-Customer-Satisfaction-Score-Prediction/tree/main)

---

## ✅ Conclusion

- 📌 ANN Regression → Predicts CSAT scores but with limited accuracy  
- 📌 ANN Classification → **82.9% accuracy** in distinguishing satisfied vs. dissatisfied customers  
- 📌 Business Insight → Product category, item price, and remarks length strongly influence satisfaction  

---

## 👨‍💻 Author

**Ayush245101**

---

## 📜 License

This project is under the **MIT License** – free to use and modify.
