# ⚽ Exploratory Data Analysis: Premier League 2023/2024

## 📌 Deskripsi Proyek

Proyek ini merupakan **Exploratory Data Analysis (EDA)** terhadap pertandingan-pertandingan di **English Premier League (EPL) musim 2023/2024**. Analisis dilakukan menggunakan Python dalam Jupyter Notebook dengan bantuan pustaka populer seperti `pandas`, `matplotlib`, dan `seaborn`.

Tujuan dari proyek ini adalah untuk memahami pola-pola statistik pertandingan seperti tren kemenangan, statistik tembakan, pengaruh bermain di kandang/tandang, dan banyak lagi.

---

## 📁 Dataset

- **File:** `matches.csv`
- **Jumlah Baris:** 760
- **Jumlah Kolom:** 28
- **Cakupan Data:**
  - 20 tim EPL (semua tim musim 2023/2024)
  - Setiap tim memainkan 38 pertandingan
  - Informasi meliputi:
    - `Date`, `Comp`, `Team`, `Opponent`, `Venue`
    - `Result`, `GF`, `GA`, `xG`, `xGA`
    - Statistik: `Poss`, `Sh`, `SoT`, `Dist`, `PK`, `Attendance`, dll

---

## 📊 Analisis dalam Notebook (`EDA.ipynb`)

Notebook terdiri dari 12 sel kode yang berisi:

- Import library dan data
- Pembersihan dan penyesuaian data
- Analisis distribusi hasil pertandingan
- Visualisasi performa tim
- Statistik metrik kunci seperti:
  - Tembakan (Shots), Tembakan Tepat Sasaran (SoT)
  - Expected Goals (`xG`, `xGA`)
  - Pengaruh kandang vs tandang
  - Analisis per pekan pertandingan

> ⚠️ Catatan: Notebook belum memiliki penjelasan dalam bentuk markdown, sehingga analisis sepenuhnya dalam bentuk kode.

---

## 🎯 Tujuan Pembelajaran

Proyek ini bertujuan untuk:

- Melatih kemampuan analisis data dengan Python
- Menjelajahi data olahraga menggunakan teknik EDA
- Memahami hubungan antar metrik performa tim sepak bola
- Membiasakan diri menggunakan tools data science seperti Jupyter, pandas, dan seaborn

---

## 🚀 Cara Menjalankan Proyek

1. Clone repositori ini:

```bash
git clone https://github.com/username/nama-repo.git
