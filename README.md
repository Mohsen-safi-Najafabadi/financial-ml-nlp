# 📈 Financial Machine Learning & NLP

Two academic data-science projects applying machine learning and NLP to financial data —supervised modeling with neural networks, and word-embedding analysis of earnings calls.

Coursework, University of Passau (2022–2023).

## 📊 Project 1 — Financial Factor Prediction: Regression vs. Neural Network
Predicting a financial target variable from **book-to-market ratio, market capitalization, and beta**, comparing a classical model with a deep-learning approach.
- Linear Regression **benchmark**, evaluated with Mean Absolute Error (MAE)
- **Neural network** trained for the same task and compared
- **Hyperparameter tuning with Optuna** to improve the network
- **Feature-importance** comparison across models
- Results interpreted in the context of the **Fama-French factors** (market premium, SMB, HML)

*Python · scikit-learn · Optuna · pandas · NumPy · neural networks*

## 🗣️ Project 2 — Earnings-Call NLP with Word Embeddings (ESG)
Analyzing company earnings-call transcripts with vector embeddings to surface semantically related content and ESG themes.
- Extract questions & answers from earnings-call transcripts
- Convert documents to vectors using **Word2Vec / Doc2Vec**
- Retrieve the most similar documents via **cosine similarity** (top-k)
- Map documents to **ESG vocabulary** (environmental, social, governance terms)

*Python · Word2Vec · Doc2Vec · cosine similarity · pandas*

## 📁 Files
- `financial-factor-prediction.ipynb` → Project 1 (regression vs. neural network)
- `earnings-call-nlp-esg.ipynb` → Project 2 (earnings-call embeddings)

---
📫 **Mohsen Safi Najafabadi** — [LinkedIn](https://linkedin.com/in/mohsen-safi-najafabadi) · Mohsen.Safi.Najafabadi@gmail.com
