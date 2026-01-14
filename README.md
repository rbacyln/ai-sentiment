# 🤖 AI Sentiment Analysis with RoBERTa

![Python](https://img.shields.io/badge/Python-3.x-blue)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![Gradio](https://img.shields.io/badge/Gradio-Demo-orange)

## 📌 Project Overview
This project implements a **Deep Learning-based Sentiment Analysis** model. This project utilizes a **Transformer architecture (RoBERTa)** to understand the context and nuance of the text, including slang and emojis.

The model is deployed with an interactive web interface using **Gradio**.

## 🧠 Model Details
- **Architecture:** RoBERTa (Robustly optimized BERT approach)
- **Base Model:** `cardiffnlp/twitter-roberta-base-sentiment-latest`
- **Training Data:** Trained on ~124M tweets, optimized for social media text and sentiment detection.
- **Labels:** Positive, Neutral, Negative

## 🚀 Installation & Usage

### 1. Clone the Repository
```bash
git clone [https://github.com/rbacyln/ai-sentiment.git](https://github.com/rbacyln/ai-sentiment.git)
cd ai-sentiment

2. Install Dependencies

Bash

pip install -r requirements.txt
3. Run the Application

Open the Jupyter Notebook ai_sentiment_deep_learning.ipynb and run all cells. The Gradio interface will launch at the end.

📊 Example Results
Input Text	Predicted Sentiment	Confidence
"I absolutely loved this movie!"	POSITIVE 😃	98.7%
"The plot was meh 😒"	NEGATIVE 😐	94.2%


🛠 Tech Stack
Python

Hugging Face Transformers

PyTorch

Gradio

Developed by Rabia Ceylan as a Deep Learning implementation project.
