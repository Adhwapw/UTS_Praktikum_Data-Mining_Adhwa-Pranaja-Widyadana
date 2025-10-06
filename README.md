# 🚗 Prediksi Harga Mobil Bekas Menggunakan Linear Regression

Proyek ini dibuat sebagai bagian dari **Ujian Tengah Semester (UTS) Praktikum Data Mining** pada Program Studi **Informatika, Universitas Singaperbangsa Karawang**.  
Tujuan proyek ini adalah untuk **memprediksi harga mobil bekas berdasarkan fitur-fitur numerik dan kategorik** seperti tahun produksi, kapasitas mesin, dan tenaga mesin.

---

## 📂 Struktur Proyek
```
├── train-data.csv         
├── test-data.csv          
├── UTS_Data_Mining_Adhwa_Pranaja.ipynb   
├── PPT UTS Praktikum Data Mining_Adhwa Pranaja Widyadana.pptx   
├── README.md              
```

---

## 🧩 Deskripsi Singkat
Proyek ini menggunakan algoritma **Linear Regression** untuk memprediksi harga mobil bekas.  
Tahapan utama yang dilakukan mencakup:
1. **Data Loading** – membaca dataset menggunakan pandas.  
2. **Data Cleaning** – menghapus kolom tidak relevan, mengonversi teks ke numerik, dan mengisi nilai kosong.  
3. **Feature Selection** – memilih fitur paling berpengaruh dengan *VarianceThreshold*.  
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

Model Linear Regression mampu menjelaskan sekitar **72,5% variasi harga mobil bekas**.  
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

---

## 🎓 Tentang Pembuat
👤 **Nama:** Adhwa Pranaja Widyadana  
📘 **Kelas:** 5A Informatika   
🏫 **Mata Kuliah:** Praktikum Data Mining  
🎯 **Universitas:** Universitas Singaperbangsa Karawang  

---

## 📎 Lisensi
Proyek ini dibuat untuk kepentingan akademik dan pembelajaran.  
Dataset diambil dari sumber publik Kaggle: *Used Car Price Prediction Dataset*.

---

## 🔗 Portofolio & Dokumentasi Tambahan
- 🎥 Video Presentasi YouTube: https://youtu.be/y6cD6kgCpy8
- 🧠 Notebook Colab: https://colab.research.google.com/drive/1wx4nhMJWY-wPnmGAT5RMYLz_HITGT7X7?usp=sharing  
