# 🧠 Multiclass Text Classification using BERT

[![Hugging Face](https://img.shields.io/badge/HuggingFace-Datasets-yellow)](https://huggingface.co/datasets/DatasetName)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue)](Kaggle_Link_Here)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)

This project fine-tunes **BERT (Bidirectional Encoder Representations from Transformers)** for **multiclass text classification** using a dataset from 🤗 **Hugging Face**.  
The model is trained and evaluated in a **Kaggle Notebook** with GPU acceleration.

---

## 📊 Dataset  
- **Dataset Name:** [AG_news](https://huggingface.co/datasets/SetFit/ag_news).  
- **Source:** Hugging Face  
- **Classes:** 🏷️ 'World', 'Sports', 'Business', 'Sci/Tech'  
- **Size:** 📏 120k  

---

## 🚀 How to Run the Notebook
1️⃣ **Open the Kaggle Notebook:** [Kaggle_Link_Here](https://www.kaggle.com/code/pradeep18102003/notebook29ef978133)  
2️⃣ **Run All Cells** (Pre-configured to load data & train model)  
3️⃣ **Results are auto-saved in Kaggle’s output directory**  

---

## 🏗️ Model Architecture  
- **Base Model:** `roberta-base` (from Hugging Face Transformers)  
- **Fine-tuned for** text classification (multiclass)  
- **Optimizer:** AdamW  
- **Loss Function:** CrossEntropyLoss  
- **Evaluation Metric:** Accuracy & F1-Score  

---

## 🔧 Training Pipeline  
✅ Load dataset from Hugging Face  
✅ Preprocess text & tokenize using BERT tokenizer  
✅ Fine-tune BERT on Kaggle with **GPU** (Tesla P100)  

---
## 📧 Contact
- If you have any questions or feedback, feel free to reach out via email: pradeep18kumar10@gmail.com linkedin: https://www.linkedin.com/in/pradeep-kumar-bba090320/.
---
