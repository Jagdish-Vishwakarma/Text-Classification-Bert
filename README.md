# Text-Classification-Bert

# Text Classification using BERT (Hugging Face)

## 📌 Project Overview
This project fine-tunes the `bert-base-uncased` transformer model on a multi-label dataset of customer support queries to predict intent categories. It leverages Hugging Face’s Transformers library, token embeddings, and attention mechanisms to classify long-form text accurately.

- **Model:** BERT (`bert-base-uncased`)
- **Task:** Multi-label text classification
- **F1 Score:** Achieved 92% on validation data
- **Tools:** Python, Hugging Face Transformers, PyTorch, Scikit-learn

---

## 🧠 Problem Statement
Automatically classify support tickets or queries into multiple categories (e.g., Billing, Technical Issue, Feature Request) to improve triaging efficiency in a customer service system.

---

## ⚙️ Model Architecture
- Pretrained BERT encoder (`bert-base-uncased`)
- Custom classification head (fully connected layer)
- Sigmoid activation for multi-label output
- Binary Cross-Entropy loss

---

## 📁 File Structure
```bash
├── train.py               # Model training script
├── predict.py             # Inference and prediction
├── dataset_loader.py      # Preprocessing and tokenization
├── requirements.txt       # Python dependencies
└── README.md              # Project description
