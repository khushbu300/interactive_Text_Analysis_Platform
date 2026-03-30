# Interactive NLP Text Analysis System
🤖 Domain: NLP | ⚡ Real-time Analysis | 🧠 Transformer Models

## 📊 Project Summary

Developed an interactive NLP-based text analysis system using Python and Streamlit, enabling users to analyze text data ither by directly entering text or by uploading a CSV file through sentiment analysis, emotion detection, tone classification, and summarization. Implemented advanced transformer models to process and extract meaningful insights from raw text in real time.
---

## 📌 Project Overview

This application provides a complete NLP pipeline where users can:

- Input any length of raw text  
- Upload a CSV file and select a text column  
- Automatically preprocess and analyze the text  
- Visualize important patterns  
- Extract emotional, sentimental, and tonal insights  
- Generate automatic summaries  

The project demonstrates practical implementation of modern NLP techniques along with real-time user interaction.

---

## 🎯 Business Value

- Enables businesses to analyze customer feedback and reviews automatically  
- Helps identify customer sentiment and emotional trends for better decision-making  
- Supports content moderation and brand monitoring  
- Automates text summarization for faster information processing  

---

## 🔄 NLP Pipeline Implemented

1. **Text Input**
   - Direct user input
   - CSV upload with column selection

2. **Text Preprocessing**
   - Text cleaning using Regular Expressions (re)
   - Lemmatization using SpaCy
   - Token creation

3. **Text Visualization**
   - Word Cloud generation
   - N-gram analysis using NLTK with frequency graphs

4. **Emotion Detection**
   - Model: `nateraw/bert-base-uncased-emotion`
   - Library: Transformers + Torch
   - Output: Top 5 emotions with confidence scores

5. **Sentiment Analysis**
   - Model: `cardiffnlp/twitter-roberta-base-sentiment`
   - Output: Positive / Negative / Neutral classification

6. **Tone of Speech Classification**
   - Model: `facebook/bart-large-mnli`
   - Technique: Zero-shot classification

7. **Text Summarization**
   - Model: `facebook/bart-large-cnn`
   - Output: Automatic abstractive summary

8. **Web Interface**
   - Built using Streamlit

---

## 🚀 Features

- Text & CSV-based analysis  
- Advanced text cleaning and lemmatization  
- Token generation  
- Word cloud visualization  
- N-gram frequency analysis  
- Emotion detection (Top 5 emotions)  
- Sentiment classification  
- Tone of speech analysis  
- Automatic text summarization  
- Interactive Streamlit dashboard  

---

## 🛠 Tech Stack & Libraries

- Python  
- Streamlit  
- SpaCy  
- NLTK  
- Transformers  
- Torch  
- Pandas  
- NumPy  
- Matplotlib  
- Regex (re)

---

## 📂 Project Structure

- `app.py` → Streamlit user interface  
- `main.py` → Core pipeline execution  
- `nlp_functions.py` → NLP and model logic  
- `text_cleaner.py` → Text preprocessing utilities  

---

## ▶️ How to Run the Project Locally

```bash
git clone https://github.com/khushbu300/interactive_text_classifier.git
cd interactive_text_classifier
pip install -r requirements.txt
streamlit run app.py
