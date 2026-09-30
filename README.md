# 🩸 Preprocessing Dataset Penyakit Demam Berdarah Dengue (DBD)

Repositori ini berisi laporan dan skrip *data cleaning* & *preprocessing* dataset penyakit Demam Berdarah Dengue (DBD) menggunakan Python di Google Colab untuk tugas mata kuliah Data Mining.

---

## 👨‍🎓 Identitas
* **Nama**: Insan Nia 
* **NIM**: 240103192
* **Kelas**: 24TIA6
---

## 📌 Ringkasan Pengolahan Data
Dataset awal dari Kaggle terdiri dari **42 baris** dan **12 kolom**. Tahapan pengolahan data yang dilakukan meliputi:
1. **Pemeriksaan Data**: Cek *missing value* (0) dan data duplikat (0).
2. **Pembersihan Teks**: Menghilangkan spasi berlebih (`strip()`), merapikan ejaan nama kolom, dan menyeragamkan nilai kategori (seperti `Jenis Kelamin`).
3. **Transformasi Data**: Ekstraksi durasi gejala bertipe teks menjadi atribut numerik baru `Durasi Gejala (Hari)`.
4. **Visualisasi Data**: Membuat grafik distribusi jenis kelamin, durasi gejala, dan riwayat kesehatan.
5. **Output**: Dataset akhir memiliki **42 baris** dan **13 kolom** dalam format `.csv` dan `.xlsx`.

---

## 📊 Hasil Analisis Singkat
* **Jenis Kelamin**: Perempuan (26) & Laki-laki (16).
* **Durasi Gejala Dominan**: 5 hari (13 pasien).
* **Riwayat Kesehatan**: Tidak Ada (28) & Diabetes (14).

---

## 📁 File dalam Repositori
* `dataset_dbd_tugas_1.ipynb` : Notebook Python / Google Colab
* `DATA_DBD_Hasil_Pengolahan.csv` : Dataset hasil pengolahan (CSV)
* `DATA_DBD_Hasil_Pengolahan.xlsx` : Dataset hasil pengolahan (Excel)
* `Laporan Preprocessing Dataset Penyakit DBD.pdf` : Laporan resmi
