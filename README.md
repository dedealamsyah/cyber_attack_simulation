# 🛡️ Cyber Security Simulation Web

**Cyber Security Simulation** adalah sebuah web edukatif interaktif yang dirancang untuk mensimulasikan berbagai jenis serangan siber secara aman langsung dari browser. Proyek ini bertujuan sebagai alat bantu belajar untuk siswa, mahasiswa, atau siapa pun yang ingin memahami kerentanan keamanan siber tanpa risiko merusak sistem nyata.

---

## 🎯 Tujuan Proyek

- Meningkatkan pemahaman konsep serangan umum dalam keamanan jaringan
- Menyediakan simulasi interaktif (client-side only) untuk pembelajaran mandiri atau demonstrasi kelas
- Menampilkan praktik terbaik pencegahan terhadap serangan seperti phishing, brute force, SQL injection, dan XSS

---

## 🧩 Fitur Utama

### 🔐 1. **Phishing Simulation**
- Menampilkan email phishing palsu
- Login palsu yang menampilkan "data curian"
- Edukasi mendeteksi email phishing

### 🔓 2. **Brute Force Attack**
- Login form dengan kombinasi mudah ditebak
- Tombol simulasi brute-force otomatis
- Log percobaan login dan hasil akhir

### 🧨 3. **SQL Injection**
- Form login rentan SQL injection
- Menampilkan query SQL yang terbentuk
- Contoh payload bypass autentikasi
- Penjelasan cara pencegahan dan contoh kode aman

### 🧪 4. **XSS (Cross-Site Scripting)**
- Komentar rentan terhadap script injection
- Komentar aman dengan escaping karakter HTML
- Edukasi sanitasi input dan CSP

### 📚 5. **Materi Pembelajaran**
- Video YouTube edukatif
- Infografis diagram serangan
- Tautan ke artikel & sumber resmi (OWASP, CISA, Hacksplaining)

---

## 🛠️ Teknologi yang Digunakan

- HTML5, CSS3 (Vanilla, responsive dengan Flex/Grid)
- JavaScript murni (tanpa framework)
- Seluruh simulasi berjalan **fully client-side** (tidak ada backend)
- Layout responsif untuk mobile dan desktop

---

## ▶️ Cara Menjalankan

1. **Download atau Clone Repositori**
   ```bash
   git clone https://github.com/nama-user/cyber-security-simulation.git
   cd cyber-security-simulation
   ```

2. **Jalankan di Browser**
   - Buka file `index.html` dengan browser modern (Chrome, Firefox, Edge)
   - Tidak perlu server, cukup double-click saja atau seret ke browser

---

## ⚠️ Disclaimer & Etika

- 🔸 **Tujuan proyek ini adalah edukasi.**
- 🔸 **Semua simulasi bersifat lokal dan tidak mengirimkan data ke server mana pun.**
- 🔸 **Melakukan serangan nyata terhadap sistem tanpa izin adalah tindakan ilegal.**
- Gunakan pengetahuan ini secara etis dan hanya di lingkungan uji yang aman atau dengan izin.

---

## 📂 Struktur Direktori

```
.
├── index.html         # File utama (berisi semua kode HTML, CSS, JS)
├── README.md          # Dokumentasi proyek ini
└── (opsional assets)  # Bisa ditambahkan untuk gambar, css, js eksternal
```

---

## 📌 Pengembangan Selanjutnya

Beberapa ide pengembangan lebih lanjut:
- Simulasi DoS/DDoS (hanya ilustratif)
- Login honeypot / honeynet visual
- Mode Admin untuk menilai peserta didik
- Modul Quiz dengan hasil skor
- Versi backend menggunakan Node.js atau Python Flask

---

## 👨‍💻 Pengembang

Dikembangkan oleh: [Dede Alamsyah](https://www.youtube.com/c/ALDEVTM)

Lisensi: MIT License  
Tahun: 2025

---