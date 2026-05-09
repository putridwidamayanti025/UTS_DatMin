# 🍷 UTS Data Mining - Prediksi Kualitas Anggur

| **Nama** | Putri Dwi Damayanti |
|----------|---------------------|
| **NIM** | 090 |
| **Mata Kuliah** | Data Mining |
| **Dosen Pengampu** | Nur Achmey Selgi Harwanti, S.Stat., M.Stat. |
| **Fakultas** | Matematika dan Ilmu Pengetahuan Alam |
| **Universitas** | Universitas Negeri Semarang (UNNES) |
| **Semester/Tahun** | Genap / 2025-2026 |

---

## 📋 Petunjuk Ujian

1. Membuat model klasifikasi untuk memprediksi kualitas anggur
2. Dataset: Wine Quality (fitur kimiawi anggur merah & putih)
3. Target: `quality` (skala 0-10)
4. Memprediksi nilai quality untuk `data_testing.csv`
5. Dokumentasi di notebook → upload ke GitHub
6. Hasil prediksi dalam format CSV (Id & quality)

---

## 📁 Struktur Repository

| File | Deskripsi |
|------|-----------|
| `UTS_DatMin_090.ipynb` | Notebook lengkap (kode, analisis, visualisasi, interpretasi) |
| `hasilprediksi_090.csv` | Hasil prediksi kualitas untuk data testing |
| `README.md` | Dokumentasi proyek ini |

---

## 🔧 Tahapan Analisis

### 1. Persiapan Data
- Load dataset training (`train.csv`) dan testing (`test.csv`)
- Eksplorasi struktur data

### 2. Pembersihan Data (Data Preprocessing)
- Pengecekan missing values
- Handling outlier (jika ada)
- Feature scaling (normalisasi/standarisasi)

### 3. Eksplorasi Data (EDA)
- Distribusi variabel target (`quality`)
- Korelasi antar fitur
- Visualisasi dengan matplotlib/seaborn

### 4. Pembuatan Model Klasifikasi
Model yang digunakan: **[isi model Anda, misal: Random Forest Classifier]**

| Model | Akurasi |
|-------|---------|
| [Model 1] | [xx%] |
| [Model 2] | [xx%] |
| **Model Terpilih** | **[xx%]** |

Evaluasi: Confusion Matrix, Classification Report (Precision, Recall, F1-Score)

### 5. Prediksi Data Uji
- Menerapkan model terbaik ke `data_testing.csv`
- Menyimpan hasil prediksi ke `hasilprediksi_090.csv`

### 6. Kesimpulan
- [Tulis kesimpulan singkat dari proyek ini]

---

## 📊 Hasil Prediksi (Preview 10 baris pertama)

| Id | Quality |
|----|---------|
| 222 | 5 |
| 1514 | 6 |
| 417 | 5 |
| 754 | 5 |
| 516 | 5 |
| 1120 | 6 |
| 180 | 5 |
| 82 | 5 |
| 632 | 6 |
| 592 | 5 |

> File lengkap: `hasilprediksi_090.csv` (300 baris)

---

## 🚀 Cara Menjalankan Notebook

### Opsi 1: Google Colab (Rekomendasi)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/putridwidamayanti025/Uts_DatMin/blob/main/UTS_DatMin_090.ipynb)

1. Klik badge di atas
2. Upload dataset training dan testing
3. Run all cells (Runtime → Run all)

### Opsi 2: Jupyter Notebook Lokal
```bash
jupyter notebook UTS_DatMin_090.ipynb
