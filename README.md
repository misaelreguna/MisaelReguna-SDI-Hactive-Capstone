# Analisis Kecanduan Media Sosial pada Pelajar dan Dampaknya terhadap Prestasi Akademik

![Colab Badge](https://img.shields.io/badge/Google%20Colab-orange?logo=googlecolab) ![Python Badge](https://img.shields.io/badge/Python-3.9-blue?logo=python)

&#x20;

---

## 🚀 Project Overview
Repositori ini berisi analisis komprehensif atas dataset **"Students Social Media Addiction"**, dengan tujuan:

1. Meninjau **hubungan durasi penggunaan media sosial** terhadap **jam tidur pelajar**.
2. Mengukur **dampak media sosial** pada **kesehatan mental pelajar**.
3. Mengidentifikasi **platform** dengan **skor kecanduan tertinggi**.

Analisis menggunakan Python (Pandas, Seaborn, Matplotlib) dalam format Jupyter Notebook untuk memproses, memvisualisasikan, dan menginterpretasi data.

---

## 📂 Link Dataset

Dataset asli dapat diunduh di:

[🔗 Students Social Media Addiction.csv (Raw)](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships/data)


---

## 💡 Findings & Insight

1. **Penggunaan vs Jam Tidur**

   * **Korelasi Pearson:** `-0.79` (negatif kuat)
   * Pelajar yang menggunakan media sosial lebih lama cenderung memiliki jam tidur yang lebih sedikit.

2. **Penggunaan vs Kesehatan Mental**

   * **Korelasi Pearson:** `-0.80` (negatif kuat)
   * Durasi penggunaan tinggi terkait dengan skor kesehatan mental yang lebih rendah.

3. **Skor Kecanduan per Platform**

   | Platform  | Rata‑Rata Skor Kecanduan |
   | --------- | ------------------------ |
   | WhatsApp  | **7.46**                 |
   | Snapchat  | **7.46**                 |
   | TikTok    | **7.43**                 |
   | Instagram | 6.55                     |
   | YouTube   | 6.10                     |

   > Platform dengan fitur chat real-time atau video pendek menunjukkan tingkat kecanduan tertinggi.

---

## 🤖 Dukungan AI

Analisis dan dokumentasi ini dibantu oleh **LLM IBM Granite**, yang menyediakan:

* Membuat visualisasi otomatis (scatter plot, bar chart).
* Interpretasi statistik korelasi dan tren data.
* Menghitung rata rata dan nilai tertinggi dari suatu kolom.

> *AI berperan sebagai asisten pintar untuk mempercepat proses analisis dan penulisan tanpa menggantikan keahlian domain.*

---

## 📖 Cara Penggunaan

1. **Clone repositori ini**:

   ```bash
   git clone https://github.com/username-repo.git
   cd username-repo
   ```
2. **Buka Google Colab Notebook**:

   ```bash
   jupyter notebook Students_Social_Media_Addiction_Analysis.ipynb
   ```
3. **Jalankan Seluruh Sel** untuk mereproduksi analisis dan visualisasi.

---

> *Dibuat dengan 😊 oleh Misael Reguna Gagarin Manik*
