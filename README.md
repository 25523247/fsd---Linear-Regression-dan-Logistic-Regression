# fsd---Linear-Regression-dan-Logistic-Regression

# Tugas Fundamen Sains Data
## Linear Regression dan Logistic Regression

### Identitas Anggota
1. [Sabrina Hani F] - [25523112]
2. [Anindya Salwa V] - [25523247]
3. [Anggun Dwi S] - [25523257]

## Bagian A: Linear Regression

**Dataset:** California Housing  
**Sumber:** Scikit-learn (`fetch_california_housing`)  
**Jumlah data:** 20.640 baris  
**Jumlah fitur:** 8  
**Target:** `MedHouseVal`

Model digunakan untuk memprediksi nilai median rumah berdasarkan delapan fitur.

Hasil evaluasi:
- MAE data uji: 0.5332
- MSE data uji: 0.5559
- RMSE data uji: 0.7456
- R-squared data uji: 0.5758

## Bagian B: Logistic Regression

**Dataset:** Breast Cancer Wisconsin  
**Sumber:** Scikit-learn (`load_breast_cancer`)  
**Jumlah data:** 569 baris  
**Jumlah fitur:** 30  
**Target:** `target` (0 = malignant, 1 = benign)

Model digunakan untuk mengklasifikasikan tumor menjadi ganas dan jinak.

Hasil evaluasi:
- Accuracy: 98.25%
- Precision: 98.61%
- Recall: 98.61%
- F1-score: 98.61%
- AUC: 0.9954

## Pembagian Kontribusi
- [Sabrina Hani F]: [Bagian B]
- [Anindya Salwa V]: [Bagian A (Logistic Regression)]
- [Anggun Dwi S]: [Membuat README, Memasukkan ke GitHub]

## Struktur Repository
- `A_linear_regression.ipynb`: Notebook Linear Regression
- `B_logistic_regression.ipynb`: Notebook Logistic Regression
- `README.md`: Dokumentasi tugas
