## Results

### Model Comparison

| Model | Accuracy |
|-------|----------|
| TF-IDF + Logistic Regression | 96.6% |
| BERT Fine-tuned | **98.4%** |

---

### BERT Confusion Matrix
![BERT Confusion Matrix](bert_confusion_matrix.png)

---

### TF-IDF Confusion Matrix
![TF-IDF Confusion Matrix](tfidf_confusion_matrix.png)

---

### Training Curves
![Training Curves](training_curves.png)

---

### Key Findings
- BERT made only **16 errors** out of 1000 test samples
- TF-IDF made **34 errors** out of 1000 test samples
- BERT made **2x fewer mistakes** than TF-IDF
- Loss dropped from 0.22 → 0.05 over 2 epochs
- No overfitting observed
