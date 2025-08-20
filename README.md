# Sentiment Demo (TF-IDF + Logistic Regression)

## Nasıl Çalıştırılır
1) Terminal:
   python3 -m pip install -r requirements.txt
2) Notebook'u aç ve en sondaki Gradio hücresini çalıştır (demo.launch()).

## Dosyalar
- sentiment_model.pkl         -> Eğitimli Logistic Regression
- tfidf_vectorizer.pkl        -> TF-IDF vektörleyici
- Untitled-1.ipynb            -> Tüm adımlar (veri, eğitim, değerlendirme, arayüz)
- requirements.txt            -> Gerekli paketler

## Notlar
- Veri: NLTK movie_reviews (EN)
- Doğruluk (test): ~%85 (bigram, sublinear_tf, min_df=5, max_df=0.9, C=2.0)
- POS eşiği: 0.55 (kararsız pozitifleri azaltmak için)
