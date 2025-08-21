# Sentiment Analysis Demo (TF-IDF + Logistic Regression)

![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Framework](https://img.shields.io/badge/framework-Gradio-orange)
![Model](https://img.shields.io/badge/model-Logistic%20Regression-yellow)

## 📌 Overview
This project demonstrates a **sentiment analysis model** built using **TF-IDF vectorization** and **Logistic Regression**.  
It classifies movie reviews as **positive (POS)** or **negative (NEG)** based on their text content.  

The project also includes a **Gradio web interface** for interactive testing.

---

## 📂 Files
- `sentiment_model.pkl` → Trained Logistic Regression model  
- `tfidf_vectorizer.pkl` → TF-IDF vectorizer  
- `sentiment_notebook.ipynb` → Full notebook (data, training, evaluation, UI)  
- `requirements.txt` → Required dependencies  
- `app.py` → Gradio application  

---

## 📊 Notes
- **Dataset**: NLTK `movie_reviews` (English)  
- **Accuracy (Test Set)**: ~85%  
  - Parameters: `bigram`, `sublinear_tf`, `min_df=5`, `max_df=0.9`, `C=2.0`  
- **POS threshold**: 0.55 (to reduce false positives in borderline cases)  

---

## 🚀 Run the App
### 1. Clone the repository
```bash
git clone https://github.com/rbacyln/ai-sentiment.git
cd ai-sentiment

pip install -r requirements.txt

python app.py


git add README.md
git commit -m "Update README.md: add badges and English version"
git push origin main

cat > README.md << 'EOF'
# Sentiment Analysis Demo (TF-IDF + Logistic Regression)

![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Framework](https://img.shields.io/badge/framework-Gradio-orange)
![Model](https://img.shields.io/badge/model-Logistic%20Regression-yellow)

## 📌 Overview
This project demonstrates a **sentiment analysis model** built using **TF-IDF vectorization** and **Logistic Regression**.  
It classifies movie reviews as **positive (POS)** or **negative (NEG)** based on their text content.  

The project also includes a **Gradio web interface** for interactive testing.

---

## 📂 Files
- `sentiment_model.pkl` → Trained Logistic Regression model  
- `tfidf_vectorizer.pkl` → TF-IDF vectorizer  
- `sentiment_notebook.ipynb` → Full notebook (data, training, evaluation, UI)  
- `requirements.txt` → Required dependencies  
- `app.py` → Gradio application  

---

## 📊 Notes
- **Dataset**: NLTK `movie_reviews` (English)  
- **Accuracy (Test Set)**: ~85%  
  - Parameters: `bigram`, `sublinear_tf`, `min_df=5`, `max_df=0.9`, `C=2.0`  
- **POS threshold**: 0.55 (to reduce false positives in borderline cases)  

---

## 🚀 Run the App
### 1. Clone the repository
```bash
git clone https://github.com/rbacyln/ai-sentiment.git
cd ai-sentiment


cat > README.md << 'EOF'

