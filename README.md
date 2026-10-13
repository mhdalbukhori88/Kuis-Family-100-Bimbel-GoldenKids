# Kuis Family 100 - Bimbel Golden Kids 🌟

Game web kuis interaktif berbasis survei bertema Family 100 yang dirancang khusus untuk pembelajaran seru di **Bimbel Golden Kids**.

---

## 🚀 Fitur Unggulan

1. **Tampilan Siap Proyektor / Infokus Kelas**:
   - Teks pertanyaan ekstra besar dan berkontras tinggi agar siswa di bagian paling belakang kelas dapat membaca dengan sangat jelas.
   - Papan skor Tim 1 dan Tim 2 diperbesar dan dipertegas dengan aksen emas serta indikator giliran aktif.
   - Panel jawaban proporsional dengan kartu jawaban 3D flip yang responsif.

2. **Kelola & Edit Soal Bebas Tanpa Batas (Untuk Guru)**:
   - **Bebas Edit**: Guru dapat mengubah pertanyaan dan kelima jawaban survei beserta variasinya (menggunakan tanda garis miring `/`, contoh: `Sepak Bola/bola/futsal`).
   - **➕ Tambah Soal Baru**: Guru dapat menambahkan soal baru tanpa batas sesuai materi pembelajaran.
   - **🗑️ Hapus Soal**: Guru dapat menghapus soal yang tidak relevan dengan aman.
   - **📦 Cadangan, Ekspor & Impor**: Soal dapat disalin (ekspor) atau diimpor sekaligus dalam format teks sederhana.
   - **🔄 Reset Default**: Dapat dikembalikan ke 30 soal bawaan Golden Kids kapan saja.
   - **Penyimpanan Otomatis**: Tersimpan di `localStorage` peramban.

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
