# 📰 BERT Fake News Detector

This project fine-tunes a **mini BERT model** (`prajjwal1/bert-mini`) to classify news articles as **Real or Fake** using natural language processing and deep learning.

---

## 🚀 Project Overview

- **Model**: `prajjwal1/bert-mini` (lightweight version of BERT)
- **Dataset**: [Fake and Real News Dataset (Kaggle)](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- **Frameworks**: Hugging Face Transformers, PyTorch, Scikit-learn
- **Environment**: Google Colab

---

## 📊 Results

- **Accuracy**: ✅ 99.5% on test dataset
- **F1-Score**: Near perfect for both real and fake categories

---

## 📂 Files Included

| File/Folder                | Description                               |
|---------------------------|--------------------------------------------|
| `bert-fake-news-model/`   | Fine-tuned model files (config, tokenizer) |
| `BERT_Fake_News_Detector.ipynb`| Full Colab notebook with training,    |
|                                   evaluation and prediction code       |
| `README.md`               | This documentation                         |

---

## 🧪 Predict Example

```python
predict_news("NASA discovers water on Mars!")
# Output: 🟢 Real News
