# 📐 Sketch Tools: Pattern, Mirror & Construction Line dalam Gambar Teknik

Dokumen ini menjelaskan penggunaan tools **Sketch Pattern**, **Mirror**, dan pentingnya **Construction Line** dalam pembuatan gambar teknik pada software CAD seperti SolidWorks, Fusion 360, dan software parametrik lainnya.

---

# 🎯 Tujuan

- Memahami fungsi dan cara kerja Sketch Pattern
- Memahami penggunaan Mirror dalam sketsa
- Mengetahui peran penting Construction Line
- Meningkatkan efisiensi dan presisi dalam desain teknik

---

# 1️⃣ Sketch Pattern

## 📌 Pengertian
Sketch Pattern adalah fitur untuk menggandakan geometri sketsa secara teratur berdasarkan jumlah dan jarak tertentu.

## 📌 Jenis Pattern

### 🔹 Linear Pattern
Menggandakan objek dalam satu atau dua arah dengan jarak tetap.

Contoh penggunaan:
- Lubang baut berderet
- Sirip pendingin
- Slot berulang

Parameter utama:
- Direction (arah)
- Spacing (jarak antar objek)
- Number of instances (jumlah pengulangan)

---

### 🔹 Circular Pattern
Menggandakan objek mengelilingi titik pusat dengan sudut tertentu.

Contoh penggunaan:
- Lubang flange
- Gear sederhana
- Pola baut melingkar

Parameter utama:
- Center point
- Total angle
- Jumlah pengulangan

---

## 📌 Keuntungan Menggunakan Pattern
- Menghemat waktu
- Mengurangi kesalahan pengukuran manual
- Menjaga konsistensi dimensi
- Memudahkan modifikasi (parametrik)

---

# 2️⃣ Mirror Tool

## 📌 Pengertian
Mirror adalah fitur untuk mencerminkan geometri terhadap suatu garis sumbu (axis).

## 📌 Cara Kerja
1. Tentukan garis sumbu (mirror line)
2. Pilih objek yang akan dicerminkan
3. Sistem membuat salinan simetris

---

## 📌 Kapan Digunakan?
- Desain simetris
- Komponen mekanik yang memiliki keseimbangan kiri-kanan
- Mengurangi penggambaran ulang sisi berlawanan

---

## 📌 Keunggulan Mirror
- Presisi simetri sempurna
- Menghemat waktu
- Mengurangi risiko perbedaan dimensi
- Mudah diedit (parametrik)

---

# 3️⃣ Construction Line (Garis Bantu)

## 📌 Pengertian
Construction Line adalah garis referensi yang tidak menjadi bagian dari bentuk akhir, tetapi digunakan sebagai panduan dalam menggambar.

Biasanya ditampilkan sebagai garis putus-putus.

---

## 📌 Fungsi Utama

### 🔹 Sebagai Sumbu Simetri
Digunakan untuk Mirror dan Circular Pattern.

### 🔹 Sebagai Referensi Dimensi
Memudahkan pemberian ukuran dari titik tengah atau pusat.

### 🔹 Membantu Constraint
Digunakan untuk menjaga hubungan geometris seperti:
- Horizontal
- Vertical
- Coincident
- Symmetric

---

## 📌 Mengapa Construction Line Sangat Penting?

Tanpa construction line:
- Sketsa sulit dikontrol
- Simetri sulit dijaga
- Dimensi tidak stabil
- Sketch menjadi overdefined atau underdefined

Dalam desain parametrik, construction line membantu membuat desain lebih:
- Stabil
- Mudah diedit
- Lebih profesional

---

# 4️⃣ Hubungan Ketiga Tools dalam Workflow

Dalam praktik terbaik:

1. Buat Construction Line terlebih dahulu (sumbu atau referensi).
2. Gambar setengah bagian desain.
3. Gunakan Mirror untuk membuat sisi simetris.
4. Gunakan Pattern untuk fitur berulang.

Metode ini membuat:
- Sketch lebih rapi
- Mudah dimodifikasi
- Lebih efisien

---

# 📌 Contoh Studi Kasus

## 🔹 Membuat Flange dengan 6 Lubang Baut
1. Buat lingkaran utama.
2. Buat satu lubang.
3. Buat construction line dari pusat.
4. Gunakan Circular Pattern sebanyak 6.
5. Gunakan dimensi parametrik.

Hasil:
- Lubang selalu merata.
- Jika diameter berubah, pola tetap konsisten.

---

# ⚠ Kesalahan Umum

- Tidak menggunakan construction line untuk sumbu.
- Menggambar semua fitur satu per satu tanpa pattern.
- Tidak menggunakan mirror untuk desain simetris.
- Over-dimensioning sketch.

---

# 🚀 Best Practice dalam Sketching

✔ Gunakan construction line untuk referensi utama  
✔ Manfaatkan mirror untuk geometri simetris  
✔ Gunakan pattern untuk fitur berulang  
✔ Pastikan sketch fully defined  
✔ Gunakan dimensi parametrik  

---

# 🎯 Kesimpulan

Sketch Pattern, Mirror, dan Construction Line adalah tools fundamental dalam CAD parametrik.

Ketiganya membantu:
- Meningkatkan efisiensi
- Menjaga presisi
- Membuat desain mudah dimodifikasi
- Menghasilkan gambar teknik yang profesional

Menguasai ketiga tools ini adalah langkah awal untuk menjadi desainer CAD yang rapi dan sistematis.

---

✍️ Dokumentasi ini dibuat untuk mendukung pembelajaran CAD dan gambar teknik.
