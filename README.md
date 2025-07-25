# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Bagus Febrian Dali Hidayat       
**NRP**: 5025201208         
**Judul TA**: PENGEMBANGAN MODEL PREDIKSI HARGA SAHAM BERBASIS LSTM-GRU DI BURSA EFEK INDONESIA           
**Dosen Pembimbing**: Arya Yudhi Wijaya  


---

## 📺 Demo Aplikasi  
  

[![Demo Aplikasi](https://i.ytimg.com/vi/LtcitLjjOmQ/maxresdefault.jpg)](https://youtu.be/LtcitLjjOmQ)  
*Klik gambar di atas untuk menonton demo*

---

*Konten selanjutnya hanya merupakan contoh awalan yang baik. Anda dapat berimprovisasi bila diperlukan.*

## 🛠 Panduan Instalasi & Menjalankan Software (via Google Colab) 

### Prasyarat  
Tidak Perlu Instalasi Lokal
Semua proses dilakukan di Google Colab. 

### Langkah-langkah  
1. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/ta-BagusFebrianRB.git
   ```
2. **Buka File Utama Notebook**        
   Setelah repository ter-clone, buka file berikut:
   ```bash
   LSTM_128-GRU_32_TA.ipynb
   ```
   
3. **Jalankan Notebook**    
Klik "Runtime" → "Run all" untuk menjalankan semua sel dari atas ke bawah. Pastikan runtime terkoneksi.
4. **Proses yang Dilakukan dalam Notebook**
   - Mengambil data historis saham LQ45 dari Yahoo Finance
   - Membersihkan data (forward fill)
   - Normalisasi dengan Min-Max Scaler
   - Membentuk window time series (30 hari)
   - Pelatihan model LSTM-GRU (128 unit LSTM + 32 unit GRU)
   - Evaluasi model dengan MAE (%) dan RMSE

---

## 📚 Dokumentasi Tambahan

- [![File notebook utama]](https://colab.research.google.com/drive/1X8wLq3atFIqeWSOaweZNBgCfwSvwOqZw?usp=sharing )

---

## ✅ Validasi

Pastikan proyek memenuhi kriteria berikut sebelum submit:
- Source code dapat di-build/run tanpa error
- Video demo jelas menampilkan fitur utama
- README lengkap dan terupdate
- Tidak ada data sensitif (password, API key) yang ter-expose

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: bagusfebrian67@gmail.com      
- Pembimbing Utama: arya@if.its.ac.id
