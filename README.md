# 📊 Analisis Waktu Respon Server (Python)

Project ini merupakan analisis waktu respon server menggunakan metode
statistik deskriptif dan visualisasi data dengan Python.

------------------------------------------------------------------------

## 🎯 Tujuan

Analisis ini bertujuan untuk: - Mengukur performa server berdasarkan
waktu respon - Mengetahui distribusi data - Mengevaluasi stabilitas
sistem - Memberikan insight dari hasil analisis

------------------------------------------------------------------------

## 🧠 Metode Analisis

### 🔹 Ukuran Pemusatan

-   Mean (Rata-rata)
-   Median
-   Modus

### 🔹 Ukuran Penyebaran

-   Minimum & Maximum
-   Range
-   Varians
-   Standar Deviasi

### 🔹 Visualisasi

-   Histogram
-   Boxplot

------------------------------------------------------------------------

## 🛠️ Tools & Library

-   Python
-   Pandas
-   NumPy
-   Matplotlib

------------------------------------------------------------------------

## 📊 Dataset

Dataset berisi **120 data waktu respon server (dalam milidetik)** yang
digunakan untuk simulasi analisis performa.

File: dataset_waktu_respon_120.xlsx

------------------------------------------------------------------------

## 📈 Hasil Analisis

-   Mean (Rata-rata): **290.05 ms**
-   Median: **288.46 ms**
-   Modus: Tidak ada (data unik)
-   Range: **388.16 ms**
-   Varians: **12901.03**
-   Standar Deviasi: **113.58 ms**

------------------------------------------------------------------------

## 💡 Insight

-   Rata-rata waktu respon server tergolong **cukup baik**
-   Distribusi data relatif **simetris**
-   Tidak terdapat nilai yang dominan (modus)
-   Variasi data cukup besar → menunjukkan **performa server belum
    stabil**

------------------------------------------------------------------------

## 🚀 Cara Menjalankan Project

1.  Clone repository: git clone
    https://github.com/iqbal96/analisis-waktu-respon-server-python.git

2.  Masuk ke folder project: cd analisis-waktu-respon-server-python

3.  Aktifkan virtual environment: venv`\Scripts`{=tex}`\activate`{=tex}

4.  Install dependencies: pip install pandas numpy matplotlib openpyxl
    jupyter

5.  Jalankan Jupyter Notebook: jupyter notebook

6.  Buka file: analisis_waktu_respon_server.ipynb

------------------------------------------------------------------------

## 📁 Struktur Project

TUGAS PYTHON/ │ ├── .ipynb_checkpoints/ ├── venv/ ├──
analisis_waktu_respon_server.ipynb ├── dataset_waktu_respon_120.xlsx ├──
Laporan.docx └── README.md

------------------------------------------------------------------------

## 📌 Catatan

-   Folder `venv/` tidak perlu di-upload ke GitHub (sebaiknya masuk
    `.gitignore`)
-   Pastikan semua library sudah terinstall sebelum menjalankan notebook

------------------------------------------------------------------------

## 👨‍💻 Author

**Iqbal Kurniawan**

------------------------------------------------------------------------

## ⭐ Penutup

Project ini dibuat sebagai bagian dari pembelajaran statistik deskriptif
menggunakan Python dalam menganalisis performa sistem berbasis web.
