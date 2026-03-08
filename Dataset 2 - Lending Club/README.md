# 💰 Lending Club Loan Analysis - Ahmad Amir Hamzah

## 📌 Tentang Proyek
Analisis data pinjaman dari Lending Club menggunakan Excel. Dataset berisi **56.160 baris** dan **14 kolom** dengan informasi peminjam, detail pinjaman, serta status pembayaran (default/lunas).

**Sumber Dataset:** [Kaggle (Original)](https://www.kaggle.com/datasets/wordsforthewise/lending-club?select=rejected_2007_to_2018Q4.csv.gz) / [Zenodo (Ariza-Garzón)](https://zenodo.org/records/11295916)

---

## 🎯 Sudut Pandang yang Dianalisis

### 📊 Dashboard 1: Credit Risk Analysis
**Fokus:** Identifikasi karakteristik peminjam berisiko tinggi

| Key Metrics | Nilai |
|-------------|-------|
| Total Debtor | 56.160 |
| Total Default | 8.846 |
| Average DTI | 18,66% |

**🔍 Insight Utama:**
- **Small Business** = 32% default (tertinggi dari semua tujuan pinjaman)
- **FICO Good (650-699)** = 19% default dengan **5.018 orang** (jumlah default terbanyak)
- **Penyewa (Rent)** = 21% default vs pemilik rumah (Mortgage) = 12%
- Peminjam dengan **emp_length "NI" (No Information)** = 24% default (setinggi <1 tahun)

### 📈 Dashboard 2: Portfolio Health Dashboard
**Fokus:** Analisis kerugian (loss) berdasarkan segmentasi

| Key Metrics | Nilai |
|-------------|-------|
| Total Loss | **$150,5 Juta** |
| Total Default | 8.846 |

**🔍 Insight Utama:**
- **Debt Consolidation** = 54% dari total loss (**$81,9 Juta**)
- **FICO Good (650-699)** = 53% dari total loss
- **Penyewa (Rent)** = 45% dari total loss
- **Q1 (Jan-Apr)** menyumbang **65% total kerugian** tahunan

---

## 📊 Excel Mastery yang Didemonstrasikan

- ✅ PivotTables & PivotCharts untuk analisis multi-dimensi
- ✅ Slicers & Timeline untuk dashboard interaktif
- ✅ Calculated Field untuk menghitung Default Rate
- ✅ VLOOKUP untuk grouping FICO, DTI, emp_length
- ✅ IF untuk membuat kolom Loss berdasarkan loan_status

---

## 📁 File dalam Folder Ini

| Nama File | Deskripsi |
|-----------|-----------|
| `0_lending_club.pdf` | Portofolio lengkap dengan 2 dashboard, insight, dan temuan bisnis |
| `1_dahsboard1.png` | Preview dashboard 1 |
| `2_dahsboard2.png` | Preview dashboard 2 |
| `3_lending_club.xlsx` | Portofolio lengkap dengan kedua dashboard dan insight dalam bentuk excel |
---

## 🔍 Key Findings (Ringkasan Eksekutif)

| Temuan | Implikasi Bisnis |
|--------|------------------|
| **Small Business** = 32% default (tertinggi) | Perlu underwriting lebih ketat untuk pinjaman bisnis kecil |
| **FICO Good (650-699)** nyumbang default terbanyak (5.018 orang) & 53% loss | Segmen ini perlu mitigasi risiko, bukan cuma fokus ke FICO rendah |
| **Debt Consolidation** = 54% loss ($81,9M) | Evaluasi ulang kriteria pinjaman konsolidasi utang |
| **Penyewa (Rent)** = 45% loss | Pertimbangkan status kepemilikan rumah dalam scoring |
| **Q1** menyumbang 65% loss | Indikasi musiman? Perlu analisis lebih lanjut |

---

## 📱 Kontak & Kolaborasi

**Ahmad Amir Hamzah**  
Bachelor of Economics | Research & Data Enthusiast

📧 **Email:** ahmadamirhmz@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/ahmdamir](https://linkedin.com/in/ahmdamir)

---

## 🗓️ Proyek Lainnya

- [📁 HR Analytics - IBM Dataset](../Dataset%201%20-%20HR%20Analytics)
- [📁 Olist E-commerce Analysis](../Dataset%203%20-%20Olist%20E-commerce)

---

*⭐ Jika proyek ini bermanfaat, jangan lupa star repositori utama!*
