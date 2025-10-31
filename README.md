Produk App - Java + Firebase Firestore + Base64 Image

Aplikasi Android sederhana untuk mengelola data produk (Create, Read, Update, Delete) menggunakan Firebase Firestore. Tidak menggunakan Firebase Storage, gambar produk disimpan dalam format Base64 string langsung ke Firestore (cocok untuk akun Firebase gratis / Spark plan).

FITUR UTAMA

Tambah Produk

• Input nama produk, harga, nomor urut, dan pilih gambar dari galeri.

• Gambar otomatis dikonversi ke Base64 sebelum disimpan ke Firestore.

Tampil Daftar Produk

• Data produk dimuat dari koleksi Firestore Produk.

• Semua field (namaProduk, harga, noProduk, fotoBase64) ditampilkan di RecyclerView.

Edit Produk

• Ubah data produk dan gambar (Base64 akan diperbarui).

• Data lama otomatis ter-replace di Firestore.

Hapus Produk

• Menghapus dokumen dari Firestore berdasarkan ID produk.

• Tidak perlu hapus file di Storage karena gambar disimpan sebagai Base64.

Otomatis Refresh

• Setelah menambah, mengedit, atau menghapus produk, MainActivity otomatis memuat ulang data tanpa harus menutup aplikasi.

Teknologi Yang Digunakan :

Bahasa Pemrograman : HTML

Database : Firebase

Penyimpanan Gambar : Base64 Encoding
