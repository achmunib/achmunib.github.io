# CAT Simulator - Seleksi KDKMP & KNMP 2026

Simulator Computer Assisted Test (CAT) untuk persiapan seleksi Koperasi Desa/Kelurahan Merah Putih (KDKMP) dan Koperasi Nagari Merah Putih (KNMP) tahun 2026.

## 📋 Deskripsi

Aplikasi web berbasis HTML/CSS/JavaScript murni yang menyediakan simulasi tes seleksi KDKMP & KNMP. Aplikasi ini dirancang untuk membantu peserta memahami pola soal dan berlatih dengan waktu terbatas seperti tes CAT sebenarnya.

## ✨ Fitur Utama

### 1. **Mode Belajar**
- Akses semua soal dengan pembahasan lengkap
- Tersedia untuk Tes Potensi Kognitif (TPK) dan Tes Manajemen Koperasi (MKO)
- Setiap soal dilengkapi dengan:
  - Konsep inti yang sering keluar
  - Pola jebakan (trap) soal
  - Pembahasan detail dan reasoning

### 2. **Simulasi Tes**
- **Tes TPK** (42 menit) - 228 soal, 6 subtes
- **Tes MKO** (20 menit) - 20 soal fokus Manajemen Koperasi
- **Simulasi Penuh** (62 menit) - Gabungan TPK + MKO
- **Mini Test** (15 menit) - 15 soal terpilih

### 3. **Navigasi Soal**
- Grid navigasi untuk melihat semua soal
- Tandai soal (flag) untuk ditinjau kembali
- Navigasi antar soal (Prev/Next)

### 4. **Hasil & Analisis**
- Skor total dan per section
- Statistik: benar, salah, tidak dijawab, akurasi
- Status lulus/tidak (ambang batas TPK: 110)
- Pembahasan lengkap semua soal setelah tes selesai

## 📊 Struktur Tes

### Tes Potensi Kognitif (TPK)
**Total: 228 Soal | Waktu: 42 Menit (6 × 7 menit)**

| Subtes | Materi | Jumlah Soal | Waktu |
|--------|--------|--------------|-------|
| 1 | Bahasa | 50 | 7 menit |
| 2 | Hitungan | 31 | 7 menit |
| 3 | Pengetahuan Umum | 40 | 7 menit |
| 4 | Pola Gambar | 55 | 7 menit |
| 5 | Abstraksi Ruang | 27 | 7 menit |
| 6 | Menentukan Bentuk | 25 | 7 menit |

**Nilai Ambang Batas: 110** (22 soal benar × 5 poin)

### Tes Manajemen Koperasi (MKO)
**Total: 20 Soal | Waktu: 20 Menit**

Fokus materi:
- Tugas Manajer Koperasi
- Sistem Simpan Pinjam
- Pengelolaan Simpanan Anggota
- Pengelolaan Pinjaman Anggota
- SHU dari Sektor Simpan Pinjam

**Bobot: Benar = 5 poin, Salah/Kosong = 0 poin**

## 🎯 Sistem Penilaian

### TPK & MKO:
```
Nilai = (Jumlah Jawaban Benar × 5)
```

- Nilai maksimal TPK: 250 (50 soal × 5)
- Nilai maksimal MKO: 100 (20 soal × 5)
- **Tidak ada pengurangan nilai** untuk jawaban salah (right-only scoring)
- Nilai ambang batas TPK: **110**

## 🚀 Cara Penggunaan

1. **Buka file `cat_simulator.html`** di browser (Chrome, Firefox, Edge, dll)
2. Pilih mode tes:
   - **Mode Belajar** - Untuk mempelajari materi dan pembahasan
   - **Tes TPK** - Latihan TPK mandiri (42 menit)
   - **Tes MKO** - Latihan MKO mandiri (20 menit)
   - **Simulasi Penuh** - Gabungan TPK + MKO (62 menit)
   - **Mini Test** - Tes singkat 15 soal (15 menit)
3. Kerjakan soal dalam waktu yang disediakan
4. Gunakan tombol navigasi atau sidebar untuk berpindah soal
5. Tandai soal yang ragu dengan tombol "Tandai"
6. Klik "Selesai" untuk melihat hasil

## ⌨️ Keyboard Shortcuts (Opsional)

- **Arrow Keys** - Navigasi soal (jika diimplementasikan)
- **F5** - Refresh halaman (reset tes)

## 📁 Struktur File

```
.
├── cat_simulator.html          # File utama aplikasi
├── tes_potensi_kognitif.md    # Dokumentasi aturan & perhitungan TPK
├── tes_manajemen_koperasi.md  # Dokumentasi aturan & perhitungan MKO
├── prompt.md                  # Instruksi pembuatan soal
└── README.md                  # File ini
```

## 🔧 Teknologi

- **HTML5** - Struktur halaman
- **CSS3** - Styling (Dark theme)
- **JavaScript (Vanilla)** - Logika aplikasi dan timer
- **Google Fonts** - Font Segoe UI / System UI

Tidak memerlukan:
- ❌ Node.js
- ❌ NPM/Yarn
- ❌ Web server
- ❌ Database

Cukup buka file HTML di browser!

## 📚 Referensi & Materi

- UU No. 25 Tahun 1992 tentang Perkoperasian
- Instruksi Presiden No. 9 Tahun 2025 tentang KDKMP
- Prinsip Koperasi ICA (International Cooperative Alliance)
- Peraturan BKN tentang Seleksi ASN
- Kisi-kisi Tes Potensi Kognitif Terbaru (6 Subtes)
- Kisi-kisi Tes Manajemen Koperasi Terbaru (Fokus Simpan Pinjam)

## 🎨 Tampilan

- **Dark Theme** - Nyaman di mata untuk belajar lama
- **Responsif** - Dapat dibuka di desktop, tablet, maupun mobile
- **Modern UI** - Antarmuka bersih dan intuitif

## ⚠️ Catatan Penting

1. **Hapus Cache Browser** jika ada error setelah update:
   - Windows/Linux: `Ctrl + Shift + R` atau `Ctrl + F5`
   - Mac: `Cmd + Shift + R`

2. **Waktu Pengerjaan**:
   - TPK: 42 menit (6 subtes × 7 menit)
   - MKO: 20 menit
   - Waktu berjalan otomatis, soal otomatis submit jika waktu habis

3. **Nilai Ambang Batas**:
   - TPK: 110 (dari skala penilaian yang ditetapkan)
   - MKO: Tidak ada ambang batas spesifik, murni latihan

## 🐛 Bug Report

Jika menemukan bug atau ada saran perbaikan, silakan buat issue atau hubungi pengembang.

## 📄 Lisensi

Project ini dibuat untuk tujuan edukasi dan latihan seleksi KDKMP & KNMP 2026.

---

**Selamat belajar dan sukses dalam seleksi KDKMP & KNMP 2026! 🎉**

---

## 📞 Kontak

Untuk pertanyaan terkait materi dan soal:
- Dokumentasi lengkap: `tes_potensi_kognitif.md` dan `tes_manajemen_koperasi.md`

---

*Dibuat dengan ❤️ untuk peserta seleksi KDKMP & KNMP 2026*
