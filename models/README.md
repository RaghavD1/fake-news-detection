## Models

### 1. TF-IDF Baseline
- Vectorizer: TF-IDF (10,000 features, bigrams)
- Classifier: Logistic Regression
- Accuracy: ~92-94%

### 2. BERT Fine-tuned (Main Model)
- Model: `bert-base-uncased`
- Max Length: 128 tokens
- Batch Size: 32
- Epochs: 2
- Learning Rate: 2e-5
- Val Accuracy: **98.40%**

### Note
Trained model is saved on Google Drive due to large file size (440MB+).
To use the model, run the notebook which loads it automatically.
