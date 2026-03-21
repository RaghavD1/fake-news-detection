# 🔍 AI-Based Fake News Detection System

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-red)
![BERT](https://img.shields.io/badge/BERT-bert--base--uncased-yellow)
![Accuracy](https://img.shields.io/badge/Accuracy-98.40%25-brightgreen)

A machine learning system to detect fake news using 
TF-IDF as baseline and BERT as the main model, 
with real-world verification via external APIs.

---

## 🧠 Pipeline
```
Input News Article
       ↓
  Preprocessing
       ↓
  ┌────────────┬──────────────┐
  │  TF-IDF    │    BERT      │
  │ (Baseline) │ (Main Model) │
  └────┬───────┴──────┬───────┘
       └──────┬───────┘
              ↓
    API Verification Layer
    (Google Fact Check + NewsAPI)
              ↓
     Final Verdict + Confidence
     [REAL / FAKE / UNCERTAIN]
```

---

## 📊 Results

| Model | Accuracy | F1 Score |
|-------|----------|----------|
| TF-IDF + Logistic Regression | ~92-94% | ~92% |
| BERT Fine-tuned | **98.40%** | ~98% |

---

## 📁 Project Structure
```
fake-news-detection/
├── notebooks/     # Colab training notebook
├── data/          # Dataset info
├── models/        # Model details
├── results/       # Evaluation charts
├── report/        # Project report
└── requirements.txt
```

---

## 🛠️ Tech Stack

- **Language:** Python
- **Deep Learning:** PyTorch, HuggingFace Transformers
- **ML:** Scikit-learn
- **Model:** bert-base-uncased (fine-tuned)
- **APIs:** Google Fact Check Tools API, NewsAPI
- **Platform:** Google Colab (T4 GPU)

---

## 🚀 How to Run

1. Open `notebooks/fake_news_detection.ipynb` in Google Colab
2. Set Runtime to **T4 GPU**
3. Run all cells in order
4. Add API keys in Cell 11 for verification layer

---

## 👨‍💻 Author

**Raghav** — BTech Third Year
