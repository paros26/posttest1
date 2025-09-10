# PBO_Posttest1 – Sistem Manajemen Penyewaan Kendaraan

##  Deskripsi Program

Program ini merupakan aplikasi **Java console** sederhana untuk melakukan operasi **CRUD (Create, Read, Update, Delete)** terhadap data kendaraan yang disewakan. Aplikasi dijalankan langsung dari console dan hanya terdiri dari satu file, `Main.java`. Data kendaraan disimpan di memori menggunakan `ArrayList`, dan interaksinya sepenuhnya melalui input dari pengguna.

Setiap kendaraan memiliki properti berikut:
- **Nama kendaraan**
- **Jenis kendaraan** (Mobil atau Motor)
- **Harga sewa** (dalam Rupiah)

---

##  Fitur Utama

1. **Tambah Kendaraan** – Menambah data kendaraan baru.
2. **Lihat Semua Kendaraan** – Menampilkan semua kendaraan dalam daftar.
3. **Update Kendaraan** – Mengubah data kendaraan berdasar nomor urut.
4. **Hapus Kendaraan** – Menghapus kendaraan dari daftar.
5. **Keluar** – Mengakhiri program.

---

##  Alur Program

1. Program dijalankan dan masuk ke method `main`.
2. `Scanner` digunakan untuk membaca input dari keyboard.
3. Tiga buah `ArrayList` (`namaKendaraan`, `jenisKendaraan`, `hargaSewa`) menyimpan masing-masing informasi kendaraan.
4. Pada awalnya, daftar kosong atau bisa diinisialisasi dengan data contoh (opsional).
5. Looping utama (`do … while`) menampilkan menu dan menunggu input pilihan dari pengguna.
6. `switch-case` digunakan untuk memproses pilihan:
   - **CREATE**: meminta input nama, jenis, dan harga lalu menyimpannya.
   - **READ**: menampilkan semua data dengan `for`—looping untuk iterasi daftar.
   - **UPDATE**: meminta nomor kendaraan, lalu input data baru.
   - **DELETE**: meminta nomor kendaraan, lalu menghapus data dari semua `ArrayList`.
   - **EXIT**: keluar dari program.
7. Program hanya berhenti bila pengguna memilih opsi “Keluar”.

---

