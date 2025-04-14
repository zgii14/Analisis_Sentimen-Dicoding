# Mobile Legends Playstore Review Sentiment Classification

Proyek ini merupakan implementasi pipeline lengkap untuk klasifikasi sentimen ulasan Mobile Legends (berbahasa Indonesia). Data dikumpulkan melalui web scraping, diproses, dan digunakan untuk membangun model machine learning dengan berbagai teknik feature extraction dan algoritma klasifikasi.

## Struktur Proyek

├── Scrapping_Data.ipynb           
├── preprocessed_mobile_legends_reviews.csv 
├── df_ml.csv                 
├── Modelling.ipynb                
├── Inference.ipynb                  
├── requirements.txt                 


## Fitur Proyek

- **Scraping Data:** Mengambil 70.000 ulasan berbahasa Indonesia dari Playstore.
- **Preprocessing:** Melakukan pembersihan teks, stopword removal, mengatasi slangword, lemmatization, dan tokenisasi.
- **Ekstraksi Fitur:** Menggunakan TF-IDF dan embedding untuk representasi vektor teks.
- **Modeling:**
  - CNN + Embedding
  - SVM + TF-IDF
  - Logistic Regression + TF-IDF
- **Evaluasi Model:** Skema pembagian data 80/20

## Cara Menjalankan

1. Clone repositori ini:

   ```bash
   git clone https://github.com/username/nama-repo.git
   cd nama-repo

2. Install Dependensi:

   pip install -r requirements.txt

3. Jalankan notebook sesuai urutan:
    - Scrapping_Data.ipynb
    - Modelling.ipynb
    - Inference.ipynb
  
**zgii14**
Proyek ini dibuat sebagai bagian dari eksplorasi pribadi di bidang NLP dan Machine Learning.
