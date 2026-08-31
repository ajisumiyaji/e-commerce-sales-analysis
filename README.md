# e-commerce-sales-analysis
# Ringkasan Proyek
Proyek ini menganalisis data transaksi penjualan toko online untuk memahami tren pendapatan bulanan, kategori produk paling berkontribusi, serta produk unggulan. Hasil analisis ini bertujuan untuk membantu tim manajemen dalam mengambil keputusan berbasis data (data-driven decision).
# Masalah Bisnis
Tren Penjualan: Bagaimana performa pendapatan toko dari bulan ke bulan?
Kontribusi Kategori: Kategori produk mana yang memberikan kontribusi penjualan terbesar?
Produk Unggulan: Produk apa saja yang masuk ke dalam daftar Top 5 terlaris untuk diutamakan stoknya?
# Pembersihan Data (Data Cleaning)
Sebelum analisis dilakukan, data mentah dibersihkan menggunakan SQL:
Memfilter baris data anomali yang memiliki Jumlah_Beli = 0.
Menghapus baris transaksi dengan nilai Harga_Satuan negatif (< 0).

# Temuan Utama (Key Insights)
Puncak Penjualan 📈: Penjualan tertinggi terjadi pada bulan Desember, mengalami kenaikan sebesar 25% dibanding bulan sebelumnya.
Dominasi Kategori 🥧: Kategori Elektronik menyumbang 60% dari total seluruh pendapatan toko.
Produk Terlaris 🏆: Laptop Pro 15 menjadi produk #1 yang paling banyak menghasilkan pendapatan.

# Rekomendasi Bisnis
Manajemen Stok: Memastikan ketersediaan stok Top 5 produk terlaris ditingkatkan menjelang akhir tahun untuk mencegah kehabisan barang (out of stock).
Strategi Pemasaran: Memberikan promosi bundel (bundling) untuk kategori dengan kontribusi lebih rendah agar penjualan lebih merata.
