## Results

### Model Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|----------|-----------|--------|----------|
| TF-IDF + Logistic Regression | ~92-94% | ~92% | ~92% | ~92% |
| BERT Fine-tuned | **98.40%** | ~98% | ~98% | ~98% |

### Key Findings
- BERT outperforms TF-IDF baseline by ~5-6%
- BERT Loss reduced from 0.71 → 0.05 over 2 epochs
- Val Accuracy improved from 98.30% → 98.40%

### Output Files
- `training_curves.png` — Loss and accuracy per epoch
- `bert_confusion_matrix.png` — BERT prediction matrix
- `model_comparison.png` — TF-IDF vs BERT bar chart
