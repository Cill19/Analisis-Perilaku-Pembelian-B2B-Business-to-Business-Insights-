# 🚀 Amazon B2B Deep Dive: Mengoptimalkan Strategi Penjualan & Inventaris

## 🎯 Ringkasan Proyek

Proyek ini adalah Analisis Data E-commerce yang berfokus pada segmentasi dan pemahaman mendalam tentang **Perilaku Pembelian Bisnis-ke-Bisnis (B2B)** dibandingkan dengan segmen konsumen (B2C).

Dengan menganalisis data penjualan Amazon, kami mengidentifikasi perbedaan kunci dalam Nilai Pesanan, Volume, Preferensi Produk, dan Pola Waktu, yang bertujuan untuk memberikan rekomendasi yang dapat **meningkatkan pendapatan B2B** dan **mengoptimalkan manajemen stok**.

---

## 💡 Masalah Bisnis & Tujuan

### Masalah (The Problem)

Manajemen penjualan kesulitan mengalokasikan sumber daya marketing dan inventaris karena minimnya wawasan spesifik tentang segmen B2B. Asumsi bahwa B2B membeli secara massal perlu diuji dan dikuantifikasi.

### Tujuan (The Goal)

1.  **Mengkuantifikasi Nilai B2B:** Menghitung seberapa besar rata-rata nilai pesanan (AOV) dan volume (Qty) B2B dibandingkan B2C.
2.  **Memetakan Preferensi:** Mengidentifikasi Kategori, Gaya, dan Ukuran produk yang paling diminati oleh pelanggan B2B.
3.  **Wawasan Operasional:** Menemukan pola waktu pembelian B2B (Hari/Bulan) untuk sinkronisasi operasional dan *fulfillment*.

---

## 🛠️ Metrik & Tools

### Metrik Kunci

| Metrik | Definisi | Wawasan Kunci |
| :--- | :--- | :--- |
| **AOV (Average Order Value)** | Rata-rata Nilai Penjualan per Transaksi. | Ukuran nilai finansial per pelanggan B2B. |
| **Avg Qty** | Rata-rata Kuantitas Produk per Transaksi. | Bukti kebutuhan pembelian massal (*bulk*). |
| **Pola Waktu** | Tren Qty yang terjual per Hari dalam Seminggu. | Waktu optimal untuk marketing dan logistik. |
| **Top Kategori** | Kategori produk dengan Qty penjualan B2B tertinggi. | Fokus inventaris dan pengembangan produk. |

### Teknologi

* **Bahasa:** Python
* **Pustaka:** `pandas` (Pembersihan Data & Analisis), `matplotlib`, `seaborn` (Visualisasi Data).
* **Lingkungan:** Google Colab / Jupyter Notebook

---

## 🔎 Temuan Kunci (Key Insights)

*Ringkasan temuan paling signifikan yang akan Anda temukan (Anda bisa mengganti dengan hasil aktual Anda):*

1.  **💰 B2B adalah Segmen Premium:** **AOV B2B** ditemukan **[Contoh: 3x lebih tinggi]** dibandingkan B2C, memvalidasi bahwa pelanggan bisnis bernilai tinggi meskipun jumlah transaksinya lebih sedikit.
2.  **📦 Utilitas Mendominasi:** Pembelian B2B terfokus pada Kategori **[Contoh: Set Pakaian]** dan cenderung memilih **Ukuran [Contoh: L dan XL]** secara proporsional lebih tinggi daripada B2C, menunjukkan pembelian untuk seragam atau inventaris standar.
3.  **🗓️ Pembelian Terstruktur:** Pembelian B2B secara signifikan **mendominasi hari kerja (Senin-Jumat)**, dengan penurunan drastis di akhir pekan, membuktikan bahwa aktivitas pembelian terikat pada jam kantor.

---

## 📝 Rekomendasi Bisnis

Berdasarkan analisis, kami merekomendasikan:

1.  **Strategi Pengeluaran Iklan:** Alihkan **80% *budget* iklan B2B** agar aktif hanya pada hari kerja.
2.  **Manajemen Inventaris:** Terapkan **stok minimum (*safety stock*) yang lebih tinggi** untuk SKU teratas B2B, terutama kategori **[Contoh: Set Pakaian]**, karena nilai pesanan yang besar memerlukan ketersediaan stok instan.
3.  **Layanan Prioritas:** Pertimbangkan untuk menugaskan tim dukungan/sales B2B khusus yang beroperasi selama hari kerja untuk menjaga retensi AOV tinggi.

---


