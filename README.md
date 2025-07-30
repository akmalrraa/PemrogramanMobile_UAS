# ⚽ KickOff Booking – Aplikasi Booking Lapangan Sepak Bola Android 📱  

**Dibuat oleh:** Akmal Rabbih Aizar  
**NIM:** 232101180  
**Kelas:** TIF RP23I – Universitas Teknologi Bandung  

---

## 📱 Tentang Aplikasi

**KickOff Booking** adalah aplikasi Android yang dirancang untuk memudahkan pengguna dalam melakukan booking lapangan sepak bola. Dengan fitur-fitur yang lengkap dan antarmuka yang intuitif, aplikasi ini memberikan pengalaman digital yang praktis dan efisien bagi para pencinta olahraga.

---

## 🌟 Fitur-Fitur Utama

### 🧭 Menu Navigasi Horizontal  
- Terdiri dari 4 menu utama:
  - **Jadwal**
  - **Lapangan**
  - **Booking**
  - **Pesan**
- Navigasi didesain interaktif dengan animasi saat berpindah halaman

---

### ⚽ 1. Booking Lapangan  
- Form input: **Nama**, **Nama Klub**, **Tanggal**, dan **Jam Booking**
- Mendukung pemilihan **lebih dari satu jam**
- Jam yang sudah dibooking tidak dapat dipilih ulang
- **Total harga dihitung otomatis** sesuai lapangan yang dipilih
- Tersedia tombol untuk melanjutkan ke halaman pembayaran

---

### 🎴 2. Galeri Kenangan  
- Pengguna dapat mengunggah **foto dari link gambar**
- Setiap foto memiliki **judul (teks tebal)** dan **deskripsi**
- Galeri ditampilkan tepat di bawah tombol “Tambah Kenangan Kamu!”
- Tampilan galeri dapat **discroll ke bawah**

---

### 📕 3. Lihat Jadwal Booking  
- Melihat semua jadwal lapangan yang telah dibooking oleh pengguna lain
- Slot jam yang sudah dibooking akan muncul sebagai **"terisi"**
- Menampilkan **nama klub** yang melakukan booking pada jam tersebut

---

### ✉ 4. Pesan  
- Fitur kirim dan lihat pesan antar pengguna atau ke admin
- Saat booking:
  - **Disetujui:** Pengguna menerima **QR Code** untuk validasi
  - **Ditolak:** Pengguna menerima pesan **"Maaf Bookingan Anda gagal dan tidak valid"**
- Semua pesan disimpan di Firebase secara online

---

### 📋 5. Daftar Lapangan  
- Menampilkan daftar lapangan yang tersedia untuk dibooking
- Informasi setiap lapangan:
  - **Nama Lapangan**
  - **Jenis Lapangan** (Rumput Sintetis / Vinly / Mini Soccer)
  - **Diameter Lapangan**
- Tampilan bersih dan mudah dipahami

---

## 🛡️ Fitur Khusus Admin

### ✅ Kelola Booking  
- Melihat semua permintaan booking
- Dapat menyetujui (**approve**) atau menolak booking

### 🖼️ Kelola Galeri  
- Menghapus konten galeri yang tidak sesuai

### 📅 Kelola Jadwal  
- Mengatur dan menampilkan jadwal lapangan
- Layout menyatu dengan halaman utama admin

### 📷 Scan QR Code  
- Fitur scan QR untuk validasi lapangan
- Hasil scan akan menampilkan detail booking terkait

---

## 🔧 Teknologi yang Digunakan

| Komponen               | Detail                          |
|------------------------|----------------------------------|
| **Bahasa Pemrograman** | Java                            |
| **Database**           | Firebase Realtime Database       |
| **Autentikasi**        | Firebase Authentication          |
| **Upload Gambar**      | imgBB                            |
| **IDE**                | Android Studio                   |
| **Desain UI**          | XML                              |
| **Manajemen Proyek**   | Gradle                           |

---

## 🚀 Cara Menjalankan Aplikasi

1. Clone repository ini:
   ```bash
   git clone https://github.com/akmalrraa/KickOff.Booking.git
