# tumor-classification-mri
# Analisis Komparasi Algoritma Klasifikasi Tumor Otak Berbasis Radiomics 🧠

## Tentang Project
Project ini adalah bagian dari penelitian Skripsi S1 Informatika. Penelitian ini bertujuan untuk membandingkan performa algoritma Machine Learning dalam mendeteksi jenis tumor otak (Glioma, Meningioma, Pituitary, Healthy) menggunakan fitur numerik (Radiomics).

## Algoritma yang Digunakan
1. **Random Forest** (Baseline)
2. **Support Vector Machine (SVM)**
3. **XGBoost** (Best Performance)
4. **Voting Classifier** (Ensemble)

## Hasil Analisis
- Akurasi Tertinggi: **95.09%** (Menggunakan XGBoost dengan Tuning)
- Dataset: Brain MRI Rich Numerical Dataset (7.000+ sampel)
- Fitur: 26 Fitur Radiomics (GLCM, LBP, Intensity Stats)

## Tech Stack
- Python 3.10
- Scikit-Learn
- XGBoost
- Pandas & NumPy
- Matplotlib & Seaborn

---
*Dibuat oleh: M. Paksi Pratama*
