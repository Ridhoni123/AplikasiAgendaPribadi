
## **Aplikasi Agenda Pribadi**

---
Aplikasi Agenda Pribadi adalah aplikasi berbasis GUI yang dibuat menggunakan Java Swing untuk mengelola catatan kegiatan sehari-hari. Aplikasi ini memungkinkan pengguna untuk menambahkan, mengubah, menghapus, menyimpan, mengimpor, dan mengekspor data agenda.

---

## **Fitur Utama**

1. Tambah: Menambahkan kegiatan baru ke daftar agenda.
2. Hapus: Menghapus kegiatan yang dipilih dari daftar agenda.
3. Edit: Mengubah detail kegiatan yang dipilih.
4. Bersihkan: Menghapus semua data yang dimasukkan di form input.
5. Simpan: Menyimpan data agenda ke dalam file.
6. Import: Mengimpor data agenda dari file.
7. Keluar: Menutup aplikasi.

---

## **Komponen GUI**
1. **Label** (JLabel)
  - Deskripsi: Digunakan untuk memberikan informasi atau petunjuk kepada pengguna tentang data yang harus diisi.
  - Komponen:
      - Kegiatan : Menunjukkan kolom untuk memasukkan nama kegiatan.
      - Pukul: Menunjukkan kolom untuk memasukkan waktu kegiatan.
      - Tanggal: Menunjukkan kolom untuk memasukkan tanggal kegiatan.
2. **Kolom Input** (JTextField)
  - Deskripsi: Digunakan untuk menerima input dari pengguna.
  - Komponen:
      - Kolom input untuk Kegiatan.
      - Kolom input untuk Pukul (format waktu: Jam:Menit WIB).
      - Kolom input untuk Tanggal (format tanggal: DD/MM/YYYY).
3. **Tabel Data** (JTable)
  - Deskripsi: Menampilkan daftar kegiatan yang telah dimasukkan oleh pengguna dalam bentuk tabel.
  - Kolom Tabel:
      - Kegiatan: Menampilkan nama kegiatan.
      - Pukul: Menampilkan waktu kegiatan.
      - Tanggal: Menampilkan tanggal kegiatan.
  - Scroll Pane: Mendukung scrollbar untuk melihat data yang panjang.
4. **Tombol Navigasi** (JButton)
  - Deskripsi: Digunakan untuk melakukan aksi tertentu seperti menambah, menghapus, atau menyimpan data.
  - Komponen:
      - Tambah: Menambahkan data dari kolom input ke tabel.
      - Hapus: Menghapus baris yang dipilih dari tabel.
      - Bersihkan: Mengosongkan kolom input.
      - Edit: Mengubah data yang dipilih di tabel.
      - Simpan: Menyimpan daftar kegiatan ke file.
      - Import: Memuat data kegiatan dari file.
      - Keluar: Menutup aplikasi.
5. **Scroll Pane** (JScrollPane)
  - Deskripsi: Menyediakan scrollbar untuk melihat seluruh data di tabel jika jumlahnya melebihi kapasitas layar.
6. **Frame Utama** (JFrame)
  - Deskripsi: Menjadi wadah utama dari seluruh komponen GUI.
  - Detail:
      - Ukuran: 600x500 piksel.
      - Warna latar: Pink cerah untuk memberikan tampilan yang menarik.

---

## **Cara Menggunakan**

1. Masukkan data Kegiatan, Pukul, dan Tanggal pada kolom input.
2. Klik tombol Tambah untuk menyimpan kegiatan ke daftar.
3. Untuk mengedit data, pilih salah satu baris pada tabel, ubah isinya di kolom input, dan klik Edit.
4. Gunakan tombol Hapus untuk menghapus data yang dipilih.
5. Klik Simpan untuk menyimpan agenda ke file.
6. Gunakan Import untuk memuat data agenda dari file.
7. Klik Keluar untuk menutup aplikasi.
---

## **Pembuat Apllikasi**
   Muhammad Ridhoni Ilham - 2210010515

## **Demo** 
![Demo GIF](https://github.com/Ridhoni123/MuhammadRidhoniIlham-2210010515-UTS/blob/main/img/Recording%202024-11-24%20185636.gif)
