# 🚆 Analisis Sentimen Ulasan KAI Access dengan 4 Skema Deep Learning

Proyek ini membandingkan performa 4 model deep learning dalam mengklasifikasikan sentimen pengguna aplikasi **Access by KAI** (Google Play Store) menjadi 3 kelas: **Positif**, **Netral**, dan **Negatif**.

## 🎯 Tujuan

- Mengukur akurasi berbagai arsitektur deep learning pada data ulasan aplikasi Access by KAI.
- Menentukan model terbaik untuk digunakan dalam sistem monitoring kepuasan pelanggan.

## 🧠 Model yang Dibandingkan

| No | Model               |  Akurasi Train  |   Akurasi Test  | 
|----|---------------------|-----------------|-----------------|
| 1  | RNN (SimpleRNN)     |      96.52%     |      83.97%     |    
| 2  | BiLSTM + FastText   |      95.59%     |      87.15%     | 
| 3  | GRU + FastText      |      95.90%     |      85.45%     |  
| 4  | IndoBERT            |      97.48%     |      89.33%     |  



