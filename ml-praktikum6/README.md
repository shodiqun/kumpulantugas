# Praktikum 6 Machine Learning – Support Vector Machine (SVM)

**Shodiqun Amin – 0110223202 – Teknik Informatika STT Terpadu Nurul Fikri (2026)**

Mata kuliah Machine Learning · Dosen: Dr. Sirojul Munir, S.Si., M.Kom.

Implementasi klasifikasi dengan algoritma Support Vector Machine di Google Colab: praktikum pada dataset Iris (kernel linear) dan tugas praktikum mandiri pada dataset Breast Cancer Wisconsin (diagnosis tumor jinak atau ganas).

## Isi folder

| File | Isi |
|---|---|
| `praktikum06.ipynb` | Notebook Colab lengkap beserta output: Bagian A (dataset Iris) dan Bagian B (tugas mandiri, dataset Breast Cancer Wisconsin) |

Notebook di Google Colab: https://colab.research.google.com/drive/1z_P4hys3iQoNfXzyLXu1VaNriGe0nHJo

## Isi notebook

- **Bagian A – Praktikum (Iris):** loading data, pembagian data 80:20, pelatihan SVM kernel linear, evaluasi (accuracy, classification report, confusion matrix), diagram sebar 2D dan 3D, dan penyimpanan model.
- **Bagian B – Tugas mandiri (Breast Cancer Wisconsin):** loading data, standarisasi fitur dengan `StandardScaler`, perbandingan kernel linear, polynomial, dan RBF, evaluasi model RBF, penyetelan parameter dengan `GridSearchCV`, dan penyimpanan model beserta scaler.
