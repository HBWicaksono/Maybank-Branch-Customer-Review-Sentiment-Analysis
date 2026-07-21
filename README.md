# Maybank Branch Sentiment Analysis Dashboard

Dashboard ini digunakan untuk menganalisis sentimen dan topik komentar pelanggan Maybank di seluruh cabang. Proyek ini adalah hasil kolaborasi.

## Fitur Utama

- **Overview:** Ringkasan distribusi sentimen (Positif, Netral, Negatif).
- **Analisis Sentimen Detail:** Word Cloud, N-gram (Bigram, Trigram, Fourgram), dan distribusi kata/karakter untuk setiap jenis sentimen.
- **Analisis Topik:** Pemodelan topik untuk memahami isu utama yang dibicarakan pelanggan di setiap kategori sentimen.

## Cara Menjalankan Secara Lokal

1.  Pastikan Anda sudah menginstal Python.
2.  Clone repositori ini:
    ```bash
    git clone [https://github.com/username-kamu/dashboard-maybank-kolaborasi.git](https://github.com/username-kamu/dashboard-maybank-kolaborasi.git)
    ```
3.  Masuk ke folder proyek:
    ```bash
    cd dashboard-maybank-kolaborasi
    ```
4.  Instal library yang dibutuhkan:
    ```bash
    pip install -r requirements.txt
    ```
5.  Jalankan aplikasi Streamlit:
    ```bash
    streamlit run app.py
    ```

## Struktur Data

Aplikasi ini membutuhkan file data CSV berikut di dalam folder `data/`:
- `komen negatif.csv`, `komen netral.csv`, `komen positif.csv`
- `topik negatif label.csv`, `topik netral label.csv`, `topik positif label.csv`

## Kontributor

- [Nama Kamu](https://github.com/username-kamu) - (Peran Kamu, misal: Deployer & Dokumentasi)
- [Nama Teman Kamu](https://github.com/username-temanmu) - (Peran Teman, misal: Lead Developer & Data Scientist)
