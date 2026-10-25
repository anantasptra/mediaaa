# 🌟 Media Pembelajaran Interaktif Siswa SD
### Petualangan Sains Ceria: Perubahan Wujud Benda & Keajaiban Siklus Air
Aplikasi web media pembelajaran interaktif untuk siswa Sekolah Dasar (SD) dengan pengalaman belajar ala **Articulate Storyline modern**, laboratorium virtual, 3 mini games edukatif, evaluasi otomatis, serta sistem akun siswa & operator terpisah.

---

## 🚀 Cara Menjalankan Aplikasi

### Cara 1: Menggunakan File Batch (Paling Mudah)
Cukup klik ganda (double click) file:
```
D:\GEOCODE\Materi Pembelajaran\run.bat
```
Server akan aktif dan browser otomatis membuka halaman pembelajaran.

### Cara 2: Melalui Terminal / Command Prompt
Buka PowerShell atau CMD di folder `D:\GEOCODE\Materi Pembelajaran`, lalu jalankan:
```bash
python app.py
```

---

## 🌐 Alamat Akses (URL)

### 💻 Dari Laptop Ini (Google Chrome / Browser):
- **Portal Siswa:** [http://localhost:8000](http://localhost:8000)
- **Portal Operator / Guru:** [http://localhost:8000/operator](http://localhost:8000/operator)

### 📱 Dari HP / Tablet / Orang Lain di Jaringan Wi-Fi yang Sama:
- **Portal Siswa:** `http://10.153.208.166:8000`
- **Portal Operator:** `http://10.153.208.166:8000/operator`

*(Catatan: Pastikan perangkat terhubung ke Wi-Fi yang sama).*

---

## 🔑 Kredensial Akun Masuk

### 1. Akun Operator (Guru / Administrator):
* **Halaman Login:** [http://localhost:8000/operator](http://localhost:8000/operator)
* **Username:** `Ananta` *(atau `ananta`)*
* **Kata Sandi (Password):** `12345`

### 2. Akun Siswa (Telah Didaftarkan Operator):
Siswa dapat langsung login melalui halaman utama [http://localhost:8000](http://localhost:8000) atau klik tombol **"Mode Demo"**:
* **Siswa 1:** NIM `SD2026001` | Nama: `Ahmad Faiz Pratama` | PIN: `1234` | Kelas 4A
* **Siswa 2:** NIM `SD2026002` | Nama: `Siti Nur Azizah` | PIN: `1234` | Kelas 4A
* **Siswa 3:** NIM `SD2026003` | Nama: `Budi Wicaksono` | PIN: `1234` | Kelas 4B
* **Siswa 4:** NIM `SD2026004` | Nama: `Dewi Ayu Lestari` | PIN: `1234` | Kelas 4B

---

## 🗺️ 8 Menu Pembelajaran Utama

1. **💡 Petunjuk:** Panduan visual langkah belajar dari materi hingga evaluasi.
2. **🎯 Pengujian (Pre-test):** Soal pengujian diagnostik awal sebelum belajar.
3. **👦 Profil Siswa:** Biodata, 8 pilihan avatar kartun ceria, rapor nilai, dan lemari lencana prestasi.
4. **📖 Materi (Storyline Slide):** Slide interaktif dengan navigasi bab, teks ramah anak, diagram warna-warni, narasi suara berbahasa Indonesia, aktivitas hotspot sentuh benda, drag-and-drop, dan checkpoint quiz.
5. **🔬 Eksperimen Virtual:** Laboratorium sains simulasi pemanasan zat cair (es batu, pemanas Bunsen, termometer digital, dan kondensasi tutup kaca pendingin) lengkap dengan jurnal catatan pengamatan siswa.
6. **🧩 Kesimpulan:** Peta konsep segitiga perubahan wujud benda dan rangkuman visual.
7. **📝 Soal (Post-test Evaluasi Akhir):** Evaluasi akhir dengan perhitungan nilai otomatis di server (anti-manipulasi), perbandingan nilai kenaikan pre-test vs post-test, serta pembahasan jawaban lengkap.
8. **🎮 Permainan Edukasi (3 Mini Game):**
   - *Game 1:* Tebak Cepat Wujud Benda (Refleks 60 detik)
   - *Game 2:* Susun Rantai Siklus Air (Teka-teki urutan tahapan)
   - *Game 3:* Tangkap Benda Sains (Arcade seru dengan tombol layar / keyboard)

---

## 🛠️ Fitur Panel Operator
- **Manajemen Akun Siswa:** Tambah siswa, edit, nonaktifkan, reset PIN, buat akun massal, impor & ekspor CSV.
- **Manajemen Materi & Slide:** Susun slide Storyline, ubah tipe slide, tambahkan checkpoint quiz.
- **Bank Soal Evaluasi:** Kelola soal pilihan ganda, kunci jawaban, dan pembahasan.
- **Laporan & Analitik:** Pantau nilai Pre-test, Post-test, kenaikan gain skor, progres materi, skor game, dan unduh ke format CSV.
- **Pengaturan Media:** Ganti judul media pembelajaran, nama sekolah, dan tema.

---

## 🎵 Sistem Suara & Musik
- **Web Audio API Procedural Synthesizer:** Musik latar instrumental lembut yang selalu berfungsi tanpa perlu dependensi audio eksternal.
- **Efek Suara Lengkap:** Klik tombol, jawaban benar, jawaban salah, naik level, dan suara terompet kemenangan (fanfare).
- **Pengaturan Terpisah:** Volume musik (BGM) dan efek suara (SFX) dapat diatur secara mandiri.
- **Narasi Suara:** Terintegrasi dengan Web Speech Synthesis Bahasa Indonesia yang ramah anak.
