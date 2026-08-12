# Analisis Data Logistik & Pengiriman

Project ini berisi analisis data pengiriman logistik menggunakan SQL (SQLite) di Google Colab. Dataset berisi 1.500 data pengiriman yang mencakup informasi supplier, gudang, tujuan, biaya, dan status pengantaran.

# Tentang Dataset
Dataset publik dari Kaggle berisi 1.500 baris data pengiriman logistik dengan 24 kolom, mencakup informasi supplier, rute, moda transportasi, komponen biaya (bahan bakar, tenaga kerja, maintenance, tol), pendapatan, profit, serta performa pengantaran (waktu tempuh dan status keterlambatan).

# Tools
- SQLite (via Python `sqlite3`)
- Google Colab
- Pandas (untuk menampilkan hasil query)

# Isi Analisis
File: `logistik_analysis.ipynb`

| No | Query | Fokus Analisis |
|----|-------|-----------------|
| 1 | SELECT + LIMIT | Menampilkan data awal |
| 2 | WHERE | Filter pengiriman yang mengalami keterlambatan |
| 3 | ORDER BY + LIMIT | 10 pengiriman dengan profit tertinggi |
| 4 | GROUP BY + AVG + SUM | Rata-rata dan total biaya per moda transportasi |
| 5 | CASE WHEN + GROUP BY | Persentase keterlambatan per supplier |
