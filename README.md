# News-Topic-Classifier-Using-BERT
This project fine-tunes a transformer model (DistilBERT) on the AG News dataset to classify news headlines into four categories: 🌍 World, 🏀 Sports, 💰 Business, and 🛰️ Science/Technology.
# 📰 News Topic Classifier (DistilBERT)

## 📌 Overview  
This project fine-tunes a **transformer model (DistilBERT)** on the **AG News dataset** to classify news headlines into **four categories**:  

- 🌍 World  
- 🏀 Sports  
- 💰 Business  
- 🛰️ Science/Technology  

It demonstrates **NLP with Transformers, transfer learning, evaluation metrics, and deployment** with Gradio.  

---

## 🚀 Features  
- ✅ Preprocessing & tokenization with Hugging Face  
- ✅ Fine-tuned **DistilBERT** for text classification  
- ✅ Model evaluation with **Accuracy** and **F1-Score**  
- ✅ **Gradio app** for interactive headline classification  

---

## 🛠️ Tech Stack  
- Python 🐍  
- [PyTorch](https://pytorch.org/)  
- [Hugging Face Transformers](https://huggingface.co/transformers/)  
- [Datasets](https://huggingface.co/docs/datasets/)  
- [Scikit-learn](https://scikit-learn.org/)  
- [Gradio](https://gradio.app/)  

---

## 📂 Project Structure  
```bash
.
├── model/                # Saved trained model
├── train.py              # Training script
├── app.py                # Gradio app for demo
├── requirements.txt      # Dependencies
└── README.md             # Project description
