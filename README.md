# Praktikum 6: Sub Rutin / Fungsi (Python)

Repository ini berisi tugas praktikum pertemuan ke-6 tentang penggunaan Fungsi dan Lambda dalam Python.

## Latihan 1: Lambda Function
Mengkonversi fungsi standar menjadi *lambda expression*:
- Fungsi `a`: Menguadratkan angka.
- Fungsi `b`: Menghitung hipotenusa (Pythagoras) menggunakan `math.sqrt`.
- Fungsi `c`: Menghitung rata-rata dari argumen arbitrer (*args).
- Fungsi `d`: Mengambil karakter unik dari string menggunakan `set` dan menggabungkannya kembali.

## Tugas Praktikum: Program Data Mahasiswa
Program sederhana untuk CRUD (Create, Read, Update, Delete) data nilai mahasiswa menggunakan list dan dictionary.

### Alur Program (Flowchart Logic):
1. **Start**: Inisialisasi list kosong `data_mahasiswa`.
2. **Menu Loop**: Program menampilkan pilihan menu (Tambah, Lihat, Ubah, Hapus, Keluar).
3. **Pencabangan (Decision)**:
   - Jika **(T)ambah**: Input Nama & Nilai -> Simpan ke list -> Kembali ke Menu.
   - Jika **(L)ihat**: Cetak Header -> Loop List -> Print setiap data -> Kembali ke Menu.
   - Jika **(U)bah**: Input Nama -> Cari di List -> Jika ada, update nilai baru -> Kembali ke Menu.
   - Jika **(H)apus**: Input Nama -> Cari di List -> Jika ada, hapus dari list -> Kembali ke Menu.
   - Jika **(K)eluar**: Terminate program (Stop).
