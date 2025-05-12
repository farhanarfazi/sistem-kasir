# sistem-kasir

Ringkasan Fitur Aplikasi Kasir (EFS Cashier)
Kategori Produk:
Makanan
Minuman
Snack

🧾Proses Pemesanan:
Kasir memilih produk sesuai keinginan pelanggan.
Produk yang dipilih masuk ke keranjang beserta total harga yang otomatis dihitung.
Kasir dapat menambahkan catatan/deskripsi (contoh: "semua pedas").
Jumlah produk bisa diedit, dan total harga akan otomatis ter-update.
Produk dalam keranjang bisa dihapus.
Setelah selesai, kasir klik tombol Bayar → data tersimpan ke JSON Server (bukan hanya sementara).

Teknologi yang Digunakan:
React JS (dengan struktur folder pages, components, utils)
React Router DOM
Axios (untuk komunikasi dengan backend/json-server)
JSON Server (untuk simulasi database)
Font Awesome (ikon)
Bootstrap (styling)
SweetAlert (untuk konfirmasi/tampilan alert)

💻 Kelebihan Pendekatan Ini
Real-time interaction: Update langsung ketika ada perubahan (jumlah produk, deskripsi, dll).
Cocok untuk pemula: JSON Server mudah digunakan sebagai simulasi backend.
User-friendly UI: Dengan Bootstrap dan SweetAlert, tampilannya lebih menarik dan responsif.
Struktur kode rapi: Terbagi menjadi folder components dan utils.
