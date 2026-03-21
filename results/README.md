## Results

### Model Comparison

| Model | Accuracy |
|-------|----------|
| TF-IDF + Logistic Regression | 96.6% |
| BERT Fine-tuned | **98.4%** |

---

### BERT Confusion Matrix
![BERT Confusion Matrix](<img width="562" height="390" alt="download (2)" src="https://github.com/user-attachments/assets/e524e3ac-9fb5-41fe-9c8e-a8b628e22ff1" />
)

---

### TF-IDF Confusion Matrix
![TF-IDF Confusion Matrix](<img width="562" height="390" alt="download" src="https://github.com/user-attachments/assets/ddc67755-744a-4184-86fe-b30f0e2da961" />
)

---

### Training Curves
![Training Curves](<img width="1189" height="390" alt="download (1)" src="https://github.com/user-attachments/assets/a8a8bdc6-a9c3-4a95-a8dd-06e3d599b02b" />
)

---

### Key Findings
- BERT made only **16 errors** out of 1000 test samples
- TF-IDF made **34 errors** out of 1000 test samples
- BERT made **2x fewer mistakes** than TF-IDF
- Loss dropped from 0.22 → 0.05 over 2 epochs
- No overfitting observed
