# 💳 Rilevamento di Frodi nelle Transazioni Finanziarie - ML Project

Questo progetto affronta il problema della rilevazione automatica di frodi con carta di credito utilizzando un dataset reale e fortemente sbilanciato. L'obiettivo è confrontare l'efficacia di diversi modelli di machine learning nel classificare correttamente le transazioni come "lecite" o "fraudolente".

## 📂 Dataset

- Dataset: [Credit Card Fraud Detection - Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Transazioni totali: 284.807
- Frodi: 492 (0.17%)
- Feature: 30 variabili numeriche derivate da PCA, più `Time`, `Amount`, `Class`

## Fasi progetto:
- **Analisi esplorativa dei dati (EDA)**: studio della distribuzione delle feature, visualizzazione dello sbilanciamento e identificazione di eventuali pattern rilevanti
- **Preprocessing**: normalizzazione dei dati, separazione del dataset in training e test set, gestione delle variabili `Time` e `Amount`
- **Modellazione**: implementazione e confronto tra vari modelli supervisionati (es. Random Forest, XGBoost, SVM) e non supervisionati (Autoencoder, LSTM Autoencoder)
- **Valutazione**: uso di metriche tradizionali e avanzate (es. ROC-AUC, PR-AUC) per l'analisi delle performance, con particolare attenzione alla classe minoritari
