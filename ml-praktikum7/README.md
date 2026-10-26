# Praktikum 7 Machine Learning – Ensemble Random Forest

**Shodiqun Amin – 0110223202 – Teknik Informatika STT Terpadu Nurul Fikri (2026)**

Mata kuliah Machine Learning · Dosen: Dr. Sirojul Munir, S.Si., M.Kom.

Implementasi klasifikasi dengan algoritma Random Forest di Google Colab pada dataset siswa `dataset_college.csv` (8.000 data) untuk memprediksi apakah siswa berencana melanjutkan kuliah (`plan`) atau tidak (`not plan`).

## Isi folder

| File | Isi |
|---|---|
| `praktikum07.ipynb` | Notebook Colab lengkap beserta output: loading data, EDA, cleaning dan One-Hot Encoding, pembagian data, pelatihan Random Forest, evaluasi, penyimpanan dan pemuatan model dengan joblib, serta fungsi prediksi data baru |

Notebook di Google Colab: https://colab.research.google.com/drive/1NWf03DbMAjJPVZ-P8nXN5uoRNjtlf7m9

## Isi notebook

- **Persiapan dan EDA:** menghubungkan Google Drive, membaca dataset, `info()`, `describe()`, nilai unik kolom kategorik, boxplot, distribusi target, dan pemeriksaan data duplikat serta nilai kosong.
- **Preprocessing:** One-Hot Encoding kolom `Gender` dan `Encourage`, penentuan fitur (X) dan target (y), dan pembagian data 80:20 dengan `stratify`.
- **Pemodelan dan evaluasi:** `RandomForestClassifier` (200 pohon, `class_weight='balanced'`), accuracy, classification report, dan confusion matrix.
- **Penyimpanan dan prediksi:** model dan daftar fitur disimpan dengan `joblib`, dimuat kembali, lalu dipakai pada fungsi `prediksi_plan()` untuk data siswa baru.
