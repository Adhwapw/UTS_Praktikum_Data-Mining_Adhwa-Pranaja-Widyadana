# 🚗 Prediksi Harga Mobil Bekas Menggunakan Linear Regression

Proyek ini dibuat sebagai bagian dari **Ujian Tengah Semester (UTS) Praktikum Data Mining** pada Program Studi **Informatika, Universitas Singaperbangsa Karawang**.  
Tujuan proyek ini adalah untuk **memprediksi harga mobil bekas berdasarkan fitur-fitur numerik dan kategorik** seperti tahun produksi, kapasitas mesin, dan tenaga mesin.

---

## 📂 Struktur Proyek
```
├── train-data.csv          # Dataset training
├── test-data.csv           # Dataset testing
├── UTS_DataMining.ipynb    # Notebook utama Google Colab
├── UTS_Data_Mining_Adhwa_Desain_Cerah.pptx   # Slide presentasi hasil proyek
├── README.md               # Dokumentasi proyek
```

---

## 🧩 Deskripsi Singkat
Proyek ini menggunakan algoritma **Linear Regression** untuk memprediksi harga mobil bekas.  
Tahapan utama yang dilakukan mencakup:
1. **Data Loading** – membaca dataset menggunakan pandas.  
2. **Data Cleaning** – menghapus kolom tidak relevan, mengonversi teks ke numerik, dan mengisi nilai kosong.  
3. **Feature Selection** – memilih fitur paling berpengaruh dengan *VarianceThreshold* dan *SelectKBest (f_regression)*.  
4. **Feature Scaling** – menormalkan data dengan *StandardScaler* agar skala fitur seimbang.  
5. **Modelling** – membangun model Linear Regression dan melakukan evaluasi menggunakan R², MAE, MSE, RMSE.  
6. **Prediction** – menghasilkan prediksi harga mobil bekas pada data test.

---

## ⚙️ Tools dan Library
- **Python 3.10+**
- **Google Colab / Jupyter Notebook**
- **pandas**
- **numpy**
- **scikit-learn**
- **matplotlib**
- **seaborn**

---

## 📈 Hasil Evaluasi Model

| Metrik | Nilai |
|--------|--------|
| R² (Train) | 0.45 |
| R² (Test)  | 0.37 |
| MAE        | 1.65 |
| RMSE       | 2.39 |

Model Linear Regression mampu menjelaskan sekitar **37% variasi harga mobil bekas**.  
Hasil ini tergolong baik untuk dataset dunia nyata yang bersifat kompleks dan variatif.

---

## 💡 Alasan Pemilihan One Hot Encoding
- Kolom kategorik seperti `Fuel_Type` dan `Transmission` tidak memiliki urutan logis.  
- One Hot Encoding menghindari kesalahan interpretasi nilai urutan yang sering terjadi pada Label Encoding.  
- Cocok untuk model **Linear Regression**, karena setiap kategori direpresentasikan secara independen (0/1).  

---

## 🧭 Alur Proyek
1. Import Dataset  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Selection  
5. Scaling  
6. Model Training  
7. Evaluation & Prediction  
8. Visualization & Reporting  

---

## 🎓 Tentang Pembuat
👤 **Nama:** Adhwa Pranaja Widyadana  
📘 **Kelas:** Informatika 5A  
🏫 **Mata Kuliah:** Praktikum Data Mining  
🎯 **Universitas:** Universitas Singaperbangsa Karawang  

---

## 📎 Lisensi
Proyek ini dibuat untuk kepentingan akademik dan pembelajaran.  
Dataset diambil dari sumber publik Kaggle: *Used Car Price Prediction Dataset*.

---

## 🔗 Portofolio & Dokumentasi Tambahan
- 🎥 Video Presentasi YouTube: [Akan ditambahkan setelah upload]  
- 🧠 Notebook Colab: [Akan ditambahkan setelah publikasi]  
- 📊 PPT Presentasi: *UTS_Data_Mining_Adhwa_Desain_Cerah.pptx*
