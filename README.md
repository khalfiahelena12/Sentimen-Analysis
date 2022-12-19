# Analisis Sentimen Pada Review Pakaian Wanita Di E-commerce


## Background
Sentimen Analisis dibutuhkan oleh perusahaan seperti e-commerce maupun perusahaan yang proses bisnisnya menggunakan bantuan teknologi di dalamnya.  Sentimen analisis digunakan untuk membantu perusahaan mengetahui seberapa baik dan berapa banyak peminat produk mereka. Kadangkala juga digunakan sebagai masukan untuk memperbaiki produk, bahkan banyak juga digunakan dalam penelitian sederhana, contohnya untuk mengetahui respon masyarakat. 

## Problem Statement
Sebanyak 18.2% pelanggan memilih tidak merekomendasikan produk pakaian wanita di e-commerce X. Jika pelanggan memberikan rating dan review buruk, maka dikhawatirkan akan mendorong calon pembeli lain untuk tidak membeli produk pakaian wanita di e-commerce X. 


## Goals
Perusahaan perlu mengetahui hal apa yang membuat pelanggan bersedia memberikan rekomendasi di e-commerce berdasarkan review yang mereka tulis. Projek ini bertujuan untuk menganalisis sentimen dari ulasan pelanggan terhadap pakaian wanita di suatu situs e-commerce. Adapun hal yang akan dibahas dalam projek ini adalah:

1. Mengklasifikasikan review yang ditulis konsumen berdasarkan kategori positif, negatif, dan netral.
2. Mengetahui kata apa yang paling sering ditulis oleh konsumen pada reviewnya.
3. Memberikan rekomendasi kepada stakeholder hal apa yang perlu ditindaklanjuti dari review konsumen.

## Data Collection
Data ini berisi tentang kumpulan ulasan yang ditulis oleh pelanggan terkait dengan E-Commerce Pakaian Wanita. Dalam data ini terdapat sembilan fitur yang mencakup 23486 baris. Data dapat diakses di https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews

## Langkah-Langkah'
1. Import library
2. Load data
3. Data preprocessing
4. Explorasi data
5. Pelabelan sentimen
6. Visualisasi wordcloud
7. Modelling

## Kesimpulan
1. Kata yang sering ditulis customer pada review positif adalah love, perfect, fit, top, color
2. Kata yang sering ditulis customer pada review negatif adalah bad, disappoint, wrong, sad
3. SVM (Linear Kernel) menjadi metode yang paling akurat dalam mengklasifikasikan review customer dengan recall score 96% dan akurasi 89%.

## Rekomendasi
1. Untuk perusahaan diharapkan bisa memperbaiki kualitas produk mereka mengingat banyak customer yang memberikan review negatif yang berdampak pada ketidakmauan customer memberikan rekomendasi.
2. Perusahaan bisa menggunakan SVM linear kernel untuk mengklasikasikan review customer
3. Analisis sentimen ini berguna untuk diterapkan pada Brand/Product Reputation Analysis, Competitor Analysis, Customer Service Analysis, dan Trend/Event Analysis
