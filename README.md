# Klasifikasi Jeruk Lemon & Jeruk Purut (GLCM & K-NN)

Repositori ini berisi notebook Jupyter untuk klasifikasi citra jeruk lemon dan jeruk purut menggunakan metode ekstraksi fitur tekstur **Gray-Level Co-occurrence Matrix (GLCM)** dan algoritma **K-Nearest Neighbors (K-NN)**.

## Isi Repositori
- `Klasifikasi_Jeruk_GLCM_KNN.ipynb` : Notebook utama implementasi preprocessing citra (OpenCV), ekstraksi fitur GLCM (skimage), standarisasi Z-score, dan klasifikasi K-NN.

## Metode
1. **Preprocessing**: Resize citra ke ukuran 150x150 dan konversi ke Grayscale.
2. **Ekstraksi Fitur GLCM**: Menghitung 5 fitur tekstur (*Contrast*, *Dissimilarity*, *Homogeneity*, *Energy*, dan *Correlation*) dari 4 sudut ($0^\circ, 45^\circ, 90^\circ, 135^\circ$).
3. **Klasifikasi**: K-Nearest Neighbors (K-NN) dengan metrik jarak Euclidean.
