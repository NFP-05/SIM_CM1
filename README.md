# Analisis Bisnis Berbasis Data: Eksplorasi Database Sakila (MySQL)

Repositori ini berisi laporan analisis bisnis mendalam terhadap sistem manajemen penyewaan film (*DVD rental store*) menggunakan database **Sakila**. Laporan ini disusun dan dieksekusi menggunakan bahasa pemrograman **R** di lingkungan **R-Markdown**.

# 🔗 Link Laporan Interaktif (GitHub Pages)

👉 [Klik di sini untuk melihat laporan interaktifnya](https://nfp-05.github.io/SIM_CM1/)

---

# 🚀 Fitur Utama & Cakupan Analisis

Laporan ini mencakup tiga analisis strategis untuk mengoptimalkan profitabilitas dan efisiensi operasional toko pada Database Sakila:

1. **Actor ROI Analysis (Manajemen Konten):**
   Mengidentifikasi jajaran aktor terpopuler yang menghasilkan akumulasi pendapatan (*gross revenue*) tertinggi, sekaligus memetakan efisiensi biaya pengadaan berdasarkan rata-rata pendapatan per judul film (*Sweet Spot* produksi).

2. **Inventory Efficiency Analysis (Manajemen Aset):**
   Mengukur *utilization rate* (tingkat perputaran sewa) dari setiap keping ketersediaan DVD di tiap cabang. Berfungsi mendeteksi judul-judul film pasif yang berstatus *Dead Stock* (stok mati) yang membebani biaya penyimpanan (*holding cost*) tanpa menyumbang profit.

3. **Rental Timing Pattern (Optimasi Temporal):**
   Menganalisis fluktuasi demand pelanggan berdasarkan dimensi waktu untuk mengidentifikasi masa sibuk (*Peak Hour* & *Peak Day*) serta masa senggang (*Off-Peak*). Digunakan sebagai fondasi *dynamic pricing*, penjadwalan kru (*staffing*), dan manajemen pemeliharaan sistem.
   
---

# 🛠️ Teknologi & Pustaka (Libraries) yang Digunakan

- **Bahasa Utama:** R & SQL (MySQL Syntax)
- **Konektivitas Database:** `odbc`, `DBI`
- **Manipulasi Data & Visualisasi:** `tidyverse` (`dplyr`, `ggplot2`), `scales`, `treemapify`
- **Format Tabel & Output:** `knitr`, `kableExtra`

---

# 📁 Struktur Folder Proyek

```text
├── images/            
│   └── Sakila_ERD_Diag.png   # Diagram Hubungan Entitas (ERD) Database Sakila
├── index.html                # Output HTML hasil kompilasi (Knit) dari R-Markdown
├── SIM_CM1_F_M0724077.rmd    # File sumber utama koding analisis R-Markdown
├── styles.css                # Style sheet CSS kustom untuk hiasan UI komponen laporan
├── .gitignore                # Berkas konfigurasi pengabaian repositori Git
└── README.md                 # Dokumentasi utama proyek analisis
```