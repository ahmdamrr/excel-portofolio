# 🛒 Olist E-commerce Analysis - Ahmad Amir Hamzah

## 📌 Tentang Proyek
Analisis data e-commerce Brasil (Olist) menggunakan Excel dengan Power Query. Dataset terdiri dari **9 tabel terpisah** yang diintegrasikan menjadi satu model analisis dengan total **100.000 pesanan**.

**Sumber Dataset:** [Olist E-commerce (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

**Proses Data Integration:**
- Melakukan **merge 6 tabel utama** menggunakan Power Query (customers, orders, products, sellers, payments, reviews)
- Menggabungkan berdasarkan key column (`order_id`, `customer_id`, `product_id`)
- Pembersihan data dan transformasi kolom untuk analisis

---

## 🎯 Sudut Pandang yang Dianalisis

### 📊 Dashboard 1: Logistic Performance
**Fokus:** Analisis ketepatan waktu pengiriman dan performa seller

| Key Metrics | Nilai |
|-------------|-------|
| Total Pesanan | 100.000 |
| Rata-rata Waktu Kirim | 12 hari |
| Rata-rata Review | 4,2 |

**🔍 Insight Utama:**
- **15% pesanan TERLAMBAT** dari estimasi (15.000 order)
- **Seller SP** paling bermasalah: **20% late rate** (5.000 order)
- Keterlambatan **TURUNKAN review 1,3 poin** (dari 4,5 → 3,2)

### 📈 Dashboard 2: Sales Performance
**Fokus:** Analisis revenue, kategori produk, dan pola waktu belanja

| Key Metrics | Nilai |
|-------------|-------|
| Total Order | 100.000 |
| Total Revenue | **$5 Juta** |
| Rata-rata Harga | $50 |

**🔍 Insight Utama:**
- **Top 5 kategori** menyumbang **48% revenue** (bed_bath, health, sports, dll)
- **Puncak belanja: November** (+26% growth, Black Friday)
- **Siang hari (12-5)** = prime time (40% transaksi)

---

## 🛠️ Tools & Fitur Excel yang Digunakan

| Fitur | Kegunaan |
|-------|----------|
| **Power Query** | **Merge 6 file!** (customers, orders, products, sellers, payments, reviews) berdasarkan key column |
| **PivotTables & PivotCharts** | Analisis keterlambatan per seller, revenue per kategori |
| **Slicers & Timeline** | Filter interaktif untuk eksplorasi data |
| **VLOOKUP & IF** | Grouping variabel dan transformasi data |
| **Kolom bantuan** | `delivery_time`, `delivery_status`, `product_segment`, `Month`, `Day`, `TimeGroup` |
| **TEXT, MONTH, YEAR, HOUR** | Ekstraksi timestamp dari kolom tanggal |

---

## 📁 File dalam Folder Ini

| Nama File | Deskripsi |
|-----------|-----------|
| `0_olist_ecommerce.pdf` | Portofolio lengkap dengan 2 dashboard, insight, dan temuan bisnis |
| `1_dahsboard1.png` | Preview dashboard 1 |
| `2_dahsboard2.png` | Preview dashboard 2 |
| `3_olist_ecommerce.xlsx` | Portofolio lengkap dengan kedua dashboard dan insight dalam bentuk excel |

---

## 🔍 Key Findings (Ringkasan Eksekutif)

| Temuan | Implikasi Bisnis |
|--------|------------------|
| **15% pesanan terlambat** | Perlu evaluasi proses logistik, terutama seller dengan performa rendah |
| **Seller SP: 20% late rate** | Prioritaskan pembinaan atau pertimbangkan ulang kerja sama dengan seller ini |
| **Keterlambatan turunkan review 1,3 poin** | Dampak langsung ke reputasi toko - on-time delivery harus jadi prioritas |
| **Top 5 kategori = 48% revenue** | Fokus stok dan promosi di kategori ini |
| **November +26% growth** | Siapkan stok dan promosi khusus menyambut Black Friday |
| **Siang hari = 40% transaksi** | Optimasi iklan dan promo di jam 12-5 siang |

---

## 📊 Excel Mastery yang Didemonstrasikan

- ✅ **Power Query** - Merge 6 tabel berbeda berdasarkan key column
- ✅ Data Integration - Menggabungkan customers, orders, products, sellers, payments, reviews
- ✅ Data Cleaning - Transformasi dan pembersihan data mentah
- ✅ PivotTables & PivotCharts - Analisis multi-dimensi
- ✅ Slicers & Timeline - Dashboard interaktif
- ✅ Kolom bantuan - `delivery_time`, `delivery_status`, `product_segment`
- ✅ Fungsi Text/Time - `TEXT`, `MONTH`, `YEAR`, `HOUR` untuk ekstraksi timestamp
- ✅ VLOOKUP & IF - Grouping variabel dan transformasi data

---

## 📱 Kontak & Kolaborasi

**Ahmad Amir Hamzah**  
Bachelor of Economics | Research & Data Enthusiast

📧 **Email:** ahmadamirhmz@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/ahmdamir](https://linkedin.com/in/ahmdamir)  

---

## 🗓️ Proyek Lainnya

- [📁 HR Analytics - IBM Dataset](../Dataset%201%20-%20HR%20Analytics)
- [📁 Lending Club - Analisis Keuangan](../Dataset%202%20-%20Lending%20Club)

---

*⭐ Jika proyek ini bermanfaat, jangan lupa star repositori utama!*
