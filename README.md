# Banking Fraud Detection System 🏦

A machine learning-based fraud detection system designed to identify suspicious banking transactions using transaction data, predictive models, and fraud risk scoring.

## 📌 Problem Statement

Traditional rule-based fraud detection systems can struggle to identify evolving fraud patterns. Common challenges include:

- Static rules that fail to adapt to new fraud techniques.
- High false-positive rates that affect legitimate customers.
- Difficulty identifying suspicious patterns across transactions, accounts, locations, and time.
- Increased operational costs associated with manual fraud investigation.

## 🚀 Proposed Solution

This project explores a machine learning-based approach to banking fraud detection that aims to:

- Apply machine learning models for transaction fraud classification.
- Extract transaction and account-behavior features to identify suspicious activity.
- Generate fraud probability scores instead of relying only on binary decisions.
- Support model evaluation and fraud-risk analysis.
- Provide a web interface for submitting transactions and viewing predictions.

## 🛠️ Tech Stack

- **Language:** Python 3
- **Data Processing:** NumPy, Pandas
- **Machine Learning:** Scikit-learn, XGBoost, TensorFlow/Keras
- **Visualization:** Matplotlib, Seaborn
- **Explainability:** SHAP
- **Backend:** Flask

## 📊 Model Evaluation

The original project documentation reports the following results:

| Metric | Reported Result |
|---|---:|
| Accuracy | 95.3% |
| AUC Score | 0.951 |
| False-positive reduction | 23% compared with rule-based detection |
| Response time | Approximately 120–150 ms per transaction |

These figures are reported in the source project's documentation and should be independently verified against the model and evaluation data before being treated as validated results.

## ⚙️ System Architecture

The system can be understood through three main components:

- **Data Processing:** Prepares transaction data for model inference.
- **Machine Learning:** Uses a trained model to estimate transaction fraud risk.
- **Prediction Interface:** Accepts transaction inputs and displays the resulting prediction.

## 🔮 Future Enhancements

- Explore transformer architectures for sequential transaction analysis.
- Investigate graph neural networks to identify relationships between accounts and transactions.
- Add real-time fraud alerts.
- Explore privacy-preserving machine learning techniques.

## 💻 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/123cs0178/fraud-detection-1.git
cd fraud-detection-1
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Start the application

```bash
python app.py
```

Open the local URL displayed in the terminal, if one is provided by the application.

## 📁 Project Structure

```text
fraud-detection-1/
├── app.py
├── fraud_model.pkl
├── model/
│   └── model.py
├── requirements.txt
├── packages.txt
├── Procfile
├── railway.json
└── README.md
```

## ⚠️ Disclaimer

This project is intended for educational and research purposes. Predictions may be incorrect and should not be used as the sole basis for real-world financial decisions.

## 👤 Maintainer

**Rahul Kumar**

- **Email:** [rahulbror612@gmail.com](mailto:rahulbror612@gmail.com)
- **Phone:** +91 9034341712
- **GitHub:** [123cs0178](https://github.com/123cs0178)

## 🙏 Acknowledgment

This repository is adapted from the original [fraud-detection project](https://github.com/Sweekar18/fraud-detection). The original project and its contributors are acknowledged. The implementation and reported results should be verified against the code in this repository.

## 📄 License

Check the repository's license file before reusing or redistributing this project. If no license is present, reuse permissions have not been established.
