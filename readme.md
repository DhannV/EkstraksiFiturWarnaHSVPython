# Ekstraksi Fitur Warna HSV pada Citra

Repositori ini menyediakan skrip Python untuk mengekstraksi fitur warna berbasis model HSV (Hue, Saturation, Value) dan analisis tekstur dari gambar digital.

## 📌 Deskripsi
Tujuan utama proyek ini adalah mentransformasi informasi visual dari gambar menjadi data numerik. Data ini sangat berguna untuk kebutuhan analisis data, seperti klasifikasi daging babi dan daging sapi atau pengenalan objek lainnya.

Ekstraksi fitur dilakukan menggunakan:
- Model warna HSV
- Statistik (mean dan standar deviasi)
- Fitur tekstur (GLCM - Gray Level Co-occurrence Matrix)

## 🛠️ Teknologi yang Digunakan
- Python
- OpenCV (`cv2`)
- NumPy
- Pandas
- Scikit-image

## 📂 Struktur Proses
1. Mengambil dataset citra dari folder
2. Melakukan preprocessing (resize gambar)
3. Konversi warna dari RGB ke HSV
4. Menghitung:
   - Mean HSV
   - Standar deviasi HSV
   - Kontras tekstur (GLCM)
5. Menyimpan hasil ekstraksi ke file Excel

## 📊 Fitur yang Diekstraksi
- Hue Mean
- Saturation Mean
- Value Mean
- Hue Standard Deviation
- Saturation Standard Deviation
- Value Standard Deviation
- Texture Contrast (GLCM)

## ▶️ Cara Menjalankan
1. Upload dataset ke Google Drive
2. Sesuaikan path folder pada kode:
   ```python
   folder_path = 'path_ke_dataset'
