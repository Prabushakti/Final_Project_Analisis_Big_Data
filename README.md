
# **<center>Proyek Akhir: Analisis Big Data</center>**

![Spotify Logo](https://github.com/user-attachments/assets/7d8f77ba-7cb4-4b47-88f7-51db642ece44)

## **Daftar Isi**
1. [**Gambaran Umum**](#Gambaran-Umum)
2. [**Tujuan**](#Tujuan)
3. [**Deskripsi Dataset**](#Deskripsi-Dataset)
4. [**Metodologi**](#Metodologi)
5. [**Hasil Analisis**](#Hasil-Analisis)
6. [**Ketergantungan**](#Ketergantungan)
7. [**Panduan Penggunaan**](#Panduan-Penggunaan)
8. [**Anggota Tim**](#Anggota-Tim)
9. [**Struktur Repositori**](#Struktur-Repositori)
10. [**Referensi**](#Referensi)

---

## **Gambaran Umum**
Proyek ini dirancang untuk memberikan pemahaman mendalam tentang bagaimana data Spotify dapat dimanfaatkan untuk menganalisis pola musik dan preferensi pengguna. Dengan menggunakan alat analitik big data, peserta proyek dapat mempelajari cara memproses, menganalisis, dan memvisualisasikan dataset besar yang berasal dari kasus nyata.

---

## **Tujuan**
Proyek ini bertujuan untuk:
1. Mengidentifikasi hubungan antara atribut audio (seperti danceability, energy, dan acousticness) dengan genre musik tertentu.
2. Menemukan genre dan karakteristik audio yang dominan dalam berbagai playlist.
3. Menganalisis faktor-faktor yang memengaruhi popularitas lagu di platform Spotify.

---

## **Deskripsi Dataset**
Dataset digunakan berasal dari proyek [TidyTuesday](https://github.com/rfordatascience/tidytuesday), yang datanya diperoleh menggunakan pustaka [`spotifyr`](https://github.com/charlie86/spotifyr). Dataset ini dirilis pada **21 Januari 2020** dan dapat diakses melalui tautan berikut:  
[spotify_songs.csv](https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2020/2020-01-21/spotify_songs.csv).

### Detail Variabel Dataset:
Dataset ini mencakup 19 variabel, di antaranya:
- `track_id`, `track_name`, `track_artist`: Informasi identifikasi lagu.
- `track_popularity`: Skor popularitas lagu dengan rentang 0-100.
- `playlist_name`, `playlist_genre`: Nama dan genre playlist terkait.
- Atribut audio seperti `danceability`, `energy`, `acousticness`, yang mendeskripsikan karakteristik musik, seperti tingkat energi dan keselarasan untuk menari.

---

## **Metodologi**
1. Mengimpor dan membersihkan data.
2. Melakukan Analisis Data Eksploratif (EDA).
3. (Opsional) Implementasi sistem rekomendasi lagu menggunakan KNN berdasarkan atribut audio.

---

## **Hasil Analisis**
Hasil analisis akan mencakup wawasan tentang pola musik, preferensi genre, dan hubungan antara atribut audio dengan popularitas lagu.

---

## **Ketergantungan**
Proyek ini memerlukan beberapa pustaka Python untuk dijalankan, yaitu:
- `pandas` versi 1.4.3
- `numpy` versi 1.23.0
- `matplotlib` versi 3.5.2

Catatan: Pustaka ini telah diuji untuk mendukung analisis, meskipun masih perlu disesuaikan dengan lingkungan Python masing-masing.

---

## **Panduan Penggunaan**
1. **Klon Repositori**  
   Salin repositori ke direktori lokal:
   ```
   git clone https://github.com/Hazarddrips/Proyek_Akhir_Analisis_Big_Data.git
   cd Proyek_Akhir_Analisis_Big_Data
   ```
2. **Instalasi Pustaka**  
   Instal semua dependensi yang diperlukan:
   ```
   pip install -r requirements.txt
   ```
3. **Jalankan Jupyter Notebook**  
   Buka file notebook untuk memulai analisis:
   ```
   jupyter notebook analisisbigdata.ipynb
   ```
4. **Dataset**  
   Pastikan file `spotify_songs.csv` berada di direktori yang sama dengan notebook.
5. **Eksplorasi**  
   Ikuti langkah-langkah dalam notebook untuk menganalisis data.

---

## **Anggota Tim**
- [Prabu Shakti](https://github.com/)
- [Muhammad Fauzan Adzyma Hele](https://github.com/)

---

## **Struktur Repositori**
- **`spotify_songs.csv`**: Dataset utama dengan informasi detail mengenai lagu Spotify.
- **Notebook `.ipynb`**: Berisi langkah-langkah analisis data, pembersihan, dan visualisasi.
- **`README.md`**: Pengantar proyek dengan penjelasan tujuan, penggunaan, dan langkah analisis.

---

## **Referensi**
- Dataset: [TidyTuesday](https://github.com/rfordatascience/tidytuesday)
- Sumber tambahan:
  - [SPARC Tutorials](https://github.com/SPARC-FAIR-Codeathon/QuiltedTutorials)
  - [KnowMore Guide](https://github.com/SPARC-FAIR-Codeathon/KnowMore)

---
