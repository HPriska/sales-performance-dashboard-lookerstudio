# Sales Performance Dashboard (Looker Studio)

## Deskripsi
Project ini berfokus pada pembuatan dashboard interaktif menggunakan Looker Studio untuk memantau dan mengevaluasi kinerja penjualan serta performa campaign selama tahun 2022.

Dashboard dirancang untuk mendukung kebutuhan analisis Tim Marketing dalam pengambilan keputusan berbasis data.

## Ruang Lingkup Dashboard
Dashboard terdiri dari dua halaman utama:

### Halaman 1 – Analisis Campaign
- Analisis hubungan antara Value Sales (before discount), Net Profit, dan Average Order Value (AOV)
- Tren performa campaign selama tahun 2022
- Insight dan rekomendasi (call to action) untuk pengambilan keputusan
- Slicer:
  - Order Date
  - Category
  - Value Transaction (is_valid)
  - Payment Method

### Halaman 2 – Detail Penjualan
- Tabel detail penjualan berisi:
  Product Name, Category, Before Discount, After Discount, Net Profit, Quantity, dan Customer (unique)
- Scorecard:
  Before Discount, After Discount, Net Profit, Quantity, Customer (unique), dan AOV
- Slicer:
  Order Date, Category, Value Transaction, dan Payment Method

## Analisis Tambahan
- Analisis kategori *Mobiles & Tablets* dengan pembayaran menggunakan JazzWallet selama tahun 2022, meliputi:
  - Total quantity
  - Total customer (unique)
- Visualisasi chart berdasarkan data pada Halaman 2

## Tools
- Looker Studio
- Data Preparation (SQL / Python)

## Output
- Dashboard interaktif Looker Studio
- Visualisasi dan insight analisis penjualan
