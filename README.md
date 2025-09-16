# **Analisis Penjualan Suplemen untuk Mengurangi Tingkat Pengembalian Produk**

Proyek ini bertujuan untuk menganalisis data penjualan suplemen kesehatan guna mengidentifikasi faktor-faktor utama yang memengaruhi tingkat pengembalian produk (*return rate*). Dengan menggunakan visualisasi data interaktif, proyek ini memberikan wawasan untuk membantu manajemen mengambil keputusan strategis dan merumuskan rekomendasi guna mengurangi kerugian finansial dan meningkatkan kepuasan pelanggan.

---

### **Latar Belakang Masalah**

Tingginya tingkat pengembalian produk merupakan masalah krusial yang dapat merugikan perusahaan secara finansial dan merusak reputasi merek. Analisis ini berfokus pada identifikasi pola dan anomali dalam data pengembalian produk, khususnya di berbagai platform penjualan dan lokasi geografis, untuk menemukan akar penyebab masalah dan merumuskan solusi yang efektif.

---

### **Output Proyek**

Proyek ini menghasilkan dua luaran utama:

1. **Analisis Statistik**: Investigasi mendalam terhadap tingkat pengembalian produk dengan fokus pada **kategori produk**, **platform penjualan (Amazon, Walmart, iHerb)**, serta **lokasi geografis pembeli**.
2. **Dashboard Interaktif**: Dashboard yang dibuat menggunakan Tableau untuk menampilkan visualisasi kunci terkait *return rate*, tren penjualan, dan perbandingan metrik penting (seperti Year-over-Year Growth).

---

### **Sumber Data**

- **Judul Dataset**: Supplement Sales Data
- **Link Dataset**: https://www.kaggle.com/datasets/zahidmughal2343/supplement-sales-data

Berikut adalah detail kolom-kolom utama dalam dataset:

- `Date`: Tanggal penjualan (Mingguan).
- `Product Name`: Nama suplemen (contoh: Vitamin C, Whey Protein).
- `Category`: Kategori suplemen (contoh: Vitamin, Omega).
- `Units Sold`: Jumlah unit terjual.
- `Price`: Harga jual produk.
- `Revenue`: Total pendapatan (`Units Sold` * `Price`).
- `Discount`: Diskon produk.
- `Units Returned`: Jumlah unit yang dikembalikan.
- `Location`: Lokasi penjualan (USA, UK, Canada).
- `Platform`: Platform *e-commerce* (Amazon, Walmart, iHerb).

---

### **Metode Analisis**

Proyek ini menggunakan metode **analisis statistik deskriptif dan inferensial** untuk mengidentifikasi pola dan hubungan antar variabel. Pendekatan ini memungkinkan pemahaman yang komprehensif tentang faktor-faktor yang mendorong tingkat pengembalian produk.

---

### **Dashboard**
<img width="1238" height="795" alt="image" src="https://github.com/user-attachments/assets/767ff5de-0413-4edb-9c61-d75819baebeb" />

---

### **Stacks Teknis**

- **Bahasa Pemrograman**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, SciPy
- **Tools**: Jupyter Notebook
- **Platform**: GitHub (untuk *repository* proyek), Tableau (untuk visualisasi dan dashboard interaktif)
