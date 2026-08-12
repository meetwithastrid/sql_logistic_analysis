# Tentang Dataset
Dataset berisi 1.500 baris data pengiriman logistik dengan 24 kolom, mencakup informasi supplier, rute, moda transportasi, komponen biaya (bahan bakar, tenaga kerja, maintenance, tol), pendapatan, profit, serta performa pengantaran (waktu tempuh dan status keterlambatan).

# Tools
- SQLite (via Python `sqlite3`)
- Google Colab
- Pandas (untuk menampilkan hasil query)

# Isi Analisis

| No | Query | Fokus Analisis |
|----|-------|-----------------|
| 1 | SELECT + LIMIT | Menampilkan data awal |
| 2 | WHERE | Filter pengiriman yang mengalami keterlambatan |
| 3 | ORDER BY + LIMIT | 10 pengiriman dengan profit tertinggi |
| 4 | GROUP BY + AVG + SUM | Rata-rata dan total biaya per moda transportasi |
| 5 | CASE WHEN + GROUP BY | Persentase keterlambatan per supplier |
