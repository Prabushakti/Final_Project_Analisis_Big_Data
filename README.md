# **<center>Project Akhir Analisis Big Data</center>**

![spotify-icon-1024x1024-b709ug61](https://github.com/user-attachments/assets/7d8f77ba-7cb4-4b47-88f7-51db642ece44)



# <center>Jelajahi dan Dapatkan Berbagai Macam Pengetahuan Mendalam Tentang Musik di Spotify </center>

## **Table of Contents**
1. [**Overview**](#Overview)
2. [**Objective**](#Objective)
3. [**Dataset**](#Dataset)
4. [**Methodology**](#Methodology)
5. [**Insights**](#Insights)
6. [**Dependencies**](#Dependencies)
7. [**Usage**](#Usage)
8. [**Team Members**](#Team-Members)
9. [**Repository Structure**](#Repository-Structure)
10. [**References**](#References)


## **Overview**
Proyek ini akan memberikan wawasan tentang bagaimana data besar dari Spotify dapat digunakan untuk memahami pola musik dan preferensi pengguna. Dengan menggunakan alat analisis big data, mahasiswa akan memperoleh pengalaman langsung dalam memproses, menganalisis, dan memvisualisasikan data kompleks dari dunia nyata.

---

## **Objective**

Proyek ini bertujuan untuk mengeksplorasi pola dan tren dalam dataset lagu yang ada pada platform Spotify. Fokus utamanya adalah untuk:

1. Menganalisis korelasi antara fitur audio (seperti danceability, energy, acousticness) dengan genre musik.

2. Mengidentifikasi genre dan karakteristik yang dominan dalam playlist tertentu serta menganalisis faktor-faktor yang mempengaruhi popularitas lagu di platform Spotify.

---

## **Dataset**

Dataset berasal dari proyek [TidyTuesday](https://github.com/rfordatascience/tidytuesday) dan dikumpulkan menggunakan paket [`spotifyr`](https://github.com/charlie86/spotifyr). Data dirilis pada **21 Januari 2020** dan dapat diakses melalui tautan berikut:  
[spotify_songs.csv](https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2020/2020-01-21/spotify_songs.csv).

Paket `spotifyr` digunakan untuk mendapatkan metadata lagu dari API Spotify, mencakup informasi seperti popularitas lagu, nama artis, album, genre, serta atribut audio (danceability, energy, valence, dll.).

### Variabel dalam Dataset:
Dataset ini terdiri dari 19 variabel, termasuk:
- `track_id`, `track_name`, `track_artist`: Identifikasi dan informasi dasar mengenai lagu.
- `track_popularity`: Popularitas lagu berdasarkan nilai antara 0-100.
- `playlist_name`, `playlist_genre`: Nama playlist dan genre playlist terkait.
- `danceability`, `energy`, `acousticness`, dan lainnya: Atribut audio yang menggambarkan karakteristik musik lagu seperti keterpaduan untuk berdansa, energi, keaslian suara, dan lainnya.

---

## **Methodology**

1. Data import and cleaning.
2. Exploratory Data Analysis (EDA).
3. Optional: Advanced analysis KNN untuk song recommendation system

---

## **Insights**


---

### **Dependencies**
Proyek ini menggunakan beberapa dependensi untuk menjalankan analisis. Berikut adalah daftar dependensi yang diperlukan:

pandas, versi 1.4.3
numpy, versi 1.23.0
matplotlib, versi 3.5.2

Catatan: Belum diuji sepenuhnya, namun bisa digunakan di lingkungan Python.

---

## **Usage**
1. Clone Repository
Clone repository ini :
    
    ```
    git clone https://github.com/Hazarddrips/Proyek_Akhir_Analisis_Big_Data.git
    ```
    ```
    cd Proyek_Akhir_Analisis_Big_Data
    ```
2. Install Dependencies
Install paket yang dibutuhkan:
    ```
    pip install -r requirements.txt
    ```
3. Jalankan Jupyter Notebook
Buka file analisisbigdata.ipynb dengan Jupyter:
    ```
    jupyter notebook analisisbigdata.ipynb
    ```
4. Dataset
Pastikan file `spotify_songs.csv` ada di direktori yang sama dengan notebook.

5. Jelajahi Analisis
Ikuti langkah-langkah di notebook untuk pembersihan dan analisis data.

---

## **Team Members**

   * [Taufik Suryo Abintoro](https://github.com/) 
   * [Febriansyah Ilham Nur Wakit](https://github.com/) 
   * [Haidar Zakki Jumali](https://github.com/) 

---

## **Repository Structure**
- `spotify_songs.csv`: Dataset berisi data lagu-lagu Spotify, termasuk informasi seperti nama lagu, artis, genre, durasi, dan metrik lainnya yang digunakan untuk analisis.
- `.ipynb`: Jupyter Notebook yang berisi langkah-langkah analisis data, mulai dari pembersihan data hingga eksplorasi dan visualisasi untuk menemukan wawasan yang relevan dari dataset.
- `README.md`: Pengantar dan gambaran umum proyek, termasuk instruksi penggunaan, tujuan analisis, serta bagaimana cara menjalankan dan mereplikasi analisis ini.
---

## **References**
- Dataset: [TidyTuesday](https://github.com/rfordatascience/tidytuesday)
- Additional Resources: 
    * https://github.com/SPARC-FAIR-Codeathon/QuiltedTutorials
    * https://github.com/SPARC-FAIR-Codeathon/KnowMore


---
