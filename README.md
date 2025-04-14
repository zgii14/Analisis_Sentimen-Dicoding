# eFootball Playstore Review Sentiment Classification

Proyek ini merupakan implementasi pipeline lengkap untuk klasifikasi sentimen ulasan eFootball (berbahasa Indonesia). Data dikumpulkan melalui web scraping, diproses, dan digunakan untuk membangun model machine learning dengan berbagai teknik feature extraction dan algoritma klasifikasi.

## Struktur Proyek

├── Scrapping_Data.ipynb           
├── preprocessed_efootball_reviews.csv 
├── df_efootball.csv                 
├── Modelling.ipynb                
├── Inference.ipynb                  
├── requirements.txt                 


## Fitur Proyek

- **Scraping Data:** Mengambil 32.000 ulasan berbahasa Inggris dari Playstore.
- **Preprocessing:** Melakukan pembersihan teks, stopword removal, mengatasi slangword, lemmatization, dan tokenisasi.
- **Ekstraksi Fitur:** Menggunakan TF-IDF dan embedding untuk representasi vektor teks.
- **Modeling:**
  - CNN + Embedding
  - SVM + TF-IDF
  - Random Forest + TF-IDF
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
  
**amdzz**
Proyek ini dibuat sebagai bagian dari eksplorasi pribadi di bidang NLP dan Machine Learning.
