# 💬 LSTM Financial Sentiment Classification

This project uses a Long Short-Term Memory (LSTM) neural network to perform sentiment analysis on financial news headlines. The goal is to classify sentences as **positive**, **negative**, or **neutral** based on their semantic content.

---

## 📊 Dataset

- **Source:** [Financial PhraseBank](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news)
- **Format:** Sentences labeled with sentiment (positive, neutral, negative)
- **Usage:** Loaded from `data/FinancialPhraseBank/` directory

---

## 🧠 Model

- **Architecture:** LSTM (with optional attention)
- **Embedding:** GloVe pretrained word embeddings
- **Framework:** PyTorch
- **Loss Function:** CrossEntropyLoss
- **Optimizer:** Adam
