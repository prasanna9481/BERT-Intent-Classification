# 🔍 BERT Intent Classification

A lightweight and effective implementation of BERT for text-based **intent classification**. This model is designed to detect seven different user intents using a fine-tuned version of BERT, implemented with **Keras** and **TensorFlow 2.0**.

---

## 🚀 Overview

This project demonstrates how to fine-tune a pre-trained BERT model to classify user queries or speech transcripts into one of several predefined intents.

Originally intended as a part of a smart assistant or safety system, this classifier could be integrated with speech-to-text models (like OpenAI Whisper) to enable natural language understanding in real-world applications.

---

## 🎯 Features

- ✅ Pre-trained BERT fine-tuned for intent detection  
- ✅ Handles 7 different user intents  
- ✅ High accuracy (97% on test set)  
- ✅ Built using TensorFlow 2.0 and Keras  
- ✅ Easily extendable to custom datasets

---

## 📊 Dataset

The model was trained on a labeled dataset consisting of user utterances categorized into the following 7 intents:

1. Greeting  
2. Goodbye  
3. Order Status  
4. Product Inquiry  
5. Complaint  
6. General Query  
7. Emergency

> You can modify `intents.json` or the training notebook to suit your own intent categories.

---

## 🧪 Model Performance

- **Test Accuracy**: 97%  
- **Framework**: Keras & TensorFlow 2.0  
- **Embedding**: BERT base uncased

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/bert-intent-classification.git
cd bert-intent-classification
pip install -r requirements.txt
