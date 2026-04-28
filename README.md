# dataset-E-Commerce-Public-Dataset Olist Brazil
Repositori ini berisi E-Commerce Public Dataset Olist dari Brazil yang dirancang untuk kebutuhan analisis data, market research, dan pembangunan model machine learning.
Dataset ini mencakup informasi komprehensif mengenai transaksi belanja online, termasuk detail pelanggan, item produk, metode pembayaran, hingga ulasan pelanggan.
Tujuan utama dari dataset ini adalah untuk memberikan gambaran nyata tentang dinamika operasional dalam platform e-commerce dan perilaku belanja pengguna.

Dataset ini terdiri dari beberapa tabel yang saling berhubungan (relasional). Berikut adalah rincian file yang tersedia:

- customers_dataset.csv: Berisi data pelanggan seperti ID unik dan lokasi geografis (kode pos, kota, negara bagian). Digunakan untuk menganalisis demografi pembeli.

- products_dataset.csv: Berisi detail fisik produk seperti kategori, berat, dimensi (panjang, tinggi, lebar), dan jumlah foto yang ditampilkan.

- product_category_name_translation.csv: Tabel pembantu yang menerjemahkan nama kategori produk dari bahasa Portugis ke bahasa Inggris (misal: beleza_saude menjadi health_beauty).

- orders_dataset.csv: Inti dari dataset ini. Berisi status pesanan (dikirim, dibatalkan, dll.) dan timestamp penting seperti waktu pembelian, waktu persetujuan pembayaran, hingga estimasi dan tanggal aktual barang sampai di pelanggan.

- order_items_dataset.csv: Menghubungkan pesanan dengan produk. Satu pesanan bisa berisi banyak item. File ini mencatat harga barang dan biaya ongkos kirim untuk setiap item dalam satu transaksi.

- order_payments_dataset.csv: Berisi rincian bagaimana pelanggan membayar, termasuk metode pembayaran (kartu kredit, boleto, voucher), jumlah cicilan, dan total nilai yang dibayarkan.

- order_reviews_dataset.csv: Berisi data kepuasan pelanggan, mencakup skor rating (1-5), judul ulasan, dan isi pesan ulasan dari pembeli.
