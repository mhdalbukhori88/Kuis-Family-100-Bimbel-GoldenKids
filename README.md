# Kuis Family 100 - Bimbel Golden Kids 🌟

Game web kuis interaktif berbasis survei bertema Family 100 yang dirancang khusus untuk pembelajaran seru di **Bimbel Golden Kids**.

---

## 🚀 Fitur Unggulan

1. **Tampilan Siap Proyektor / Infokus Kelas**:
   - Teks pertanyaan ekstra besar dan berkontras tinggi agar siswa di bagian paling belakang kelas dapat membaca dengan sangat jelas.
   - Papan skor Tim 1 dan Tim 2 diperbesar dan dipertegas dengan aksen emas serta indikator giliran aktif.
   - Panel jawaban proporsional dengan kartu jawaban 3D flip yang responsif.

2. **Kelola Bank Soal Praktis & Ramah Guru (2 Tampilan)**:
   - **Tampilan Daftar Soal (List View)**: Guru dapat melihat seluruh soal dalam bentuk kartu rapi, dilengkapi tombol `[✏️ Edit]` dan `[🗑️ Hapus]` untuk tiap soal.
   - **➕ Tambah Soal Baru**: Membuka form bersih untuk menambahkan soal materi pelajaran.
   - **🗑️ Kosongkan / Buat Kuis Baru**: Mengosongkan bank soal dalam 1 klik agar guru bisa menyusun kuis dari nomor 1 tanpa tercampur soal bawaan.
   - **🔄 Muat 30 Soal Bawaan**: Mengembalikan ke 30 soal kuis pengetahuan umum SD bawaan Golden Kids kapan pun dibutuhkan.
   - **Form Input Bersih**: Form terpisah yang rapi dan mudah diisi (pertanyaan + 5 jawaban berpoin).
   - **Variasi Jawaban Guru**: Mendukung tanda garis miring `/` untuk sinonim kata (contoh: `Paus/ikan paus` atau `Sepak Bola/bola/futsal`).
   - **📦 Cadangan, Ekspor & Impor**: Soal dapat disalin (ekspor) atau diimpor sekaligus dalam format teks sederhana.
   - **Penyimpanan Otomatis**: Tersimpan otomatis di peramban (`localStorage`).

3. **Interaktivitas Game Family 100**:
   - Papan skor untuk 2 tim (nama tim dapat diklik dan diedit langsung).
   - Deteksi jawaban cerdas (fuzzy matching toleran saltik / typo ringan).
   - Efek suara sintetis (Web Audio API) untuk jawaban benar, salah, dan kemenangan.
   - Efek visual confetti kembang api saat permainan selesai.
   - Tombol oper giliran tim, buka semua jawaban, dan reset silang (✕).

---

## 💻 Cara Menjalankan

Buka file `index.html` langsung di browser modern (Google Chrome, Firefox, Microsoft Edge, Safari) atau jalankan melalui web server lokal:

```bash
python3 -m http.server 8080
```

Akses melalui `http://localhost:8080`.
