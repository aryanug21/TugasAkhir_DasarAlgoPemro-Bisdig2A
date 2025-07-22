👕 USER MANUAL – APLIKASI INVENTORI TOKO THRIFTING
🛍️ 1. Deskripsi Program
Aplikasi ini adalah sistem manajemen inventori sederhana untuk toko thrifting (pakaian bekas). Program berbasis Python ini memungkinkan pengguna untuk:

Menambah data pakaian thrift (dengan kode unik)

Melihat seluruh data pakaian

Mengedit stok

Menghapus data barang

Menampilkan laporan stok dari tertinggi ke terendah

Menyimpan data secara otomatis ke file inventori_thrift.json

💻 2. Persyaratan Sistem
Python 3.6 atau lebih tinggi

Bisa dijalankan di:

VS Code / Terminal (Windows, macOS, Linux)

Google Colab

📂 3. Struktur File
Nama File	Keterangan
inventori_thrift.py	File utama berisi kode program
inventori_thrift.json	File penyimpanan data pakaian dalam format JSON
user_manual.md	File dokumentasi/manual penggunaan

▶️ 4. Cara Menjalankan Program
💻 Via Terminal / VS Code
Pastikan Python sudah terinstal

Jalankan perintah berikut:

bash
Salin
Edit
python inventori_thrift.py
☁️ Via Google Colab
Upload file inventori_thrift.py

Jalankan sel program

File inventori_thrift.json akan otomatis dibuat

📋 5. Panduan Menu Program
text
Salin
Edit
=== Menu Inventori Toko Thrifting ===
1. Tambah Barang Thrift
2. Lihat Semua Barang
3. Edit Stok
4. Hapus Barang
5. Laporan Stok
6. Simpan & Keluar
No	Menu	Deskripsi
1	Tambah Barang Thrift	Menambahkan data barang baru (kode, nama, ukuran, kategori, stok)
2	Lihat Semua Barang	Menampilkan seluruh barang dan detailnya
3	Edit Stok	Mengubah jumlah stok berdasarkan kode
4	Hapus Barang	Menghapus barang berdasarkan kode
5	Laporan Stok	Menampilkan daftar barang dari stok terbanyak ke terkecil
6	Simpan & Keluar	Menyimpan data ke file JSON dan keluar dari program

🧾 6. Format Input
Field	Format	Contoh
Kode	String tanpa spasi	THR001
Nama	String bebas	Vintage Jacket
Ukuran	String pendek	L, XL, M
Kategori	String bebas	Outerwear
Stok	Angka bulat positif (int)	3

⚙️ 7. Fitur Optimasi & Error Handling
✅ Penanganan file dengan with open() dan try-except
✅ Komentar lengkap pada kode
✅ Validasi kode unik untuk mencegah data ganda
✅ Waktu eksekusi fungsi dicatat dengan time.time()
✅ Struktur data fleksibel dengan list of dictionaries
✅ Mudah dikembangkan menjadi sistem database yang lebih besar

📌 8. Catatan Tambahan
File inventori_thrift.json akan otomatis diperbarui setelah memilih menu Simpan & Keluar

Jika file JSON belum ada, program akan membuat file kosong

Jangan edit file .json secara manual untuk menjaga konsistensi data

💡 Saran Pengembangan (Opsional)
Tambahkan fitur pencarian berdasarkan kategori atau ukuran

Buat opsi filter berdasarkan stok minim

Ekspor laporan ke .csv untuk keperluan laporan stok mingguan

Gunakan dict indexing untuk pencarian lebih cepat (O(1))
