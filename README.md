# 📊 Analisis Time Series & Peramalan GARCH dan SARIMA

## 👥 Anggota Kelompok 8
| NIM       | Nama                                 |
|-----------|-------------------------------------|
| 121450018 | Balqis Dwian Fitri Zamzami          |
| 121450026 | Ericson Chandra Sihombing            |
| 121450075 | Veni Zahara Kartika                 |
| 121450112 | Christian Arvianus Nathanael Biran  |

---

## 📌 Deskripsi Proyek

Proyek ini bertujuan melakukan analisis deret waktu dan peramalan menggunakan model **ARMA**, **GARCH**, dan **SARIMA** pada data harga saham IBM serta data inflasi Indonesia.  
Metode yang digunakan meliputi uji kestasioneran, transformasi Box-Cox, identifikasi model terbaik melalui AIC, uji diagnostik residu, serta peramalan masa depan.

---

## 🔍 Fitur Utama

- Visualisasi data deret waktu harga saham IBM dan inflasi Indonesia
- Uji kestasioneran menggunakan Augmented Dickey-Fuller (ADF) dan Box-Cox Transformation
- Model ARMA dan GARCH untuk analisis volatilitas harga saham
- Model SARIMA untuk menangani pola musiman pada data inflasi
- Uji diagnostik residual untuk validasi model
- Peramalan 3 periode ke depan dengan model terbaik

---

## 📈 Contoh Visualisasi

![Plot Harga Saham IBM](path_to_your_image/IBM_Close_Plot.png)  
*Plot deret waktu harga saham IBM menunjukkan pola volatilitas dan tren*

![Plot ACF Data Inflasi](path_to_your_image/Inflasi_ACF_Plot.png)  
*Plot ACF data inflasi memperlihatkan pola musiman yang jelas*

---

## 🛠️ Cara Menjalankan Analisis

1. Pastikan R dan package terkait telah terinstal (`forecast`, `tseries`, `rugarch`, dll).  
2. Buka file R Markdown `.Rmd` dan jalankan setiap chunk kode untuk mereproduksi analisis.  
3. File dataset dapat ditemukan di folder `data/` (atau sesuaikan path pada script).  
4. Lihat output berupa grafik, tabel model, dan ringkasan peramalan.

---

## 📊 Hasil Utama

- Model ARMA(4,2)-GARCH(5,6) terbaik untuk memodelkan volatilitas harga saham IBM.  
- Model SARIMA(0,0,1)(0,1,1)[12] dan ARIMA(0,0,2)(0,1,1)[12] memberikan peramalan inflasi yang cukup akurat.  
- Residual dari model memenuhi asumsi normalitas, non-autokorelasi, dan homoskedastisitas.  

---

---
## 📚 Referensi

- Engle, R. (1982). Autoregressive Conditional Heteroskedasticity. Econometrica.  
- Hyndman, R. J., & Athanasopoulos, G. (2018). Forecasting: Principles and Practice.  
- Badan Pusat Statistik Indonesia - [bps.go.id](https://www.bps.go.id)
-   
---

---

## 📞 Kontak

Ericson Chandra Sihombing  
Email: sihombingericson@gmail.com

---

> \*Proyek ini merupakan bagian dari tugas Mata Kuliah Analisis Deret Waktu Institut Teknologi Sumatera
