# Fraud Detection System for Nepali Banking 🏦

This project implements an **Advanced Machine Learning–based Fraud Detection System** designed specifically for **Global IME Bank** and Nepali banking systems.  
It was developed as part of the **Global IME Bank Hackathon (April 2025)** to address the growing sophistication of financial fraud beyond traditional rule-based systems.

---

## 📌 Problem Statement
Nepali banks, including Global IME Bank, face increasing challenges from fraudsters who exploit weaknesses in traditional **rule-based detection systems**.  
Some key issues:
- Static rules that cannot adapt to evolving fraud tactics
- High false positive rates → poor customer experience
- Inability to detect complex fraud patterns across multiple accounts, locations, or times
- Significant operational costs and reputational risks

---

## 🚀 Proposed Solution
We developed a **multi-stage, real-time machine learning system** that:
- Uses an **ensemble of Random Forest, XGBoost, and Neural Networks**
- Engineers **120+ banking-specific features** (transaction timing, location distance, account behavior, remittance-aware patterns, festival patterns, etc.)
- Provides **fraud probability scores** instead of binary decisions
- Includes an **explainability framework** with SHAP values and bilingual (Nepali/English) explanations
- Works in **real-time** with sub-150ms latency

---

## 🛠️ Tech Stack
- **Python 3**
- **NumPy, Pandas** – data preprocessing
- **Scikit-learn, XGBoost, TensorFlow/Keras** – ML modeling
- **Matplotlib, Seaborn, SHAP** – analysis & explainability
- **Flask** – real-time API for fraud detection

---

## 📊 Key Results
- **Accuracy:** 95.3%  
- **AUC Score:** 0.951  
- **False Positives:** Reduced by 23% compared to rule-based systems  
- **Response Time:** ~120–150ms per transaction  

Business impact for Global IME Bank:
- Estimated **67% reduction in fraud-related losses**
- **Improved customer trust** through fewer incorrect blocks
- **Compliance** with Nepal Rastra Bank’s regulatory requirements

---

## ⚙️ System Architecture
- **Data Processing Layer:** Cleans raw transactions, performs feature engineering  
- **ML Layer:** Runs ensemble models for fraud probability  
- **Decision Layer:** Provides explanations, flags suspicious activity, assigns risk levels  

---

## 📌 Future Enhancements
- Use **transformers** and **graph neural networks** for sequence & network-based fraud detection  
- Integrate **cross-bank collaboration** with federated learning  
- Add **mobile app integration** for customer alerts  
- Implement **privacy-preserving ML** (differential privacy, homomorphic encryption)  

---

## 🏆 Hackathon Submission
This project was officially submitted to the **Global IME Bank Hackathon (2025)** by **Sweekar Subedi**.

---

## 📜 License
This repository is for **academic and research purposes**. Please contact before using in production banking systems.

---

## 👤 Author
**Sweekar Subedi**  
📧 Email: sweekarsubedi18@gmail.com  
📱 +977 9860614096
