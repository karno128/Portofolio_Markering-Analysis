**Business Problem**

Proyek ini bertujuan untuk mengoptimalkan hasil dari campaign pemasaran yang dilakukan oleh perusahaan. Fokus utama adalah:
1. Memaksimalkan profit dalam campaign bulan berikutnya.
2. Memahami karakteristik pelanggan yang menerima penawaran produk baru.
3. Menganalisis faktor-faktor yang mempengaruhi keberhasilan campaign.
   
**Dataset**
Dataset ini berisi informasi mengenai pelanggan yang mencakup variabel seperti:
- Year_Birth: Tahun lahir pelanggan.
- Education: Tingkat pendidikan.
- Marital_Status: Status pernikahan.
- Income: Pendapatan tahunan pelanggan.
- Kidhome: Jumlah anak kecil dalam rumah tangga.
- Teenhome: Jumlah remaja dalam rumah tangga.
- Recency: Hari sejak transaksi terakhir.
- MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds: Pengeluaran untuk berbagai kategori produk.
- NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases: Jumlah pembelian berdasarkan channel.
- Response: Apakah pelanggan merespons penawaran kampanye.
- Complain: Adakah keluhan yang diajukan oleh pelanggan.
- Country: Negara asal pelanggan.
  
**Objective**

- Membersihkan data untuk analisis yang lebih akurat.
- Mengidentifikasi pola pembelian dan karakteristik demografis pelanggan.
- Memprediksi pelanggan yang kemungkinan besar merespons penawaran di masa depan.
  
**Steps to Solution**
1. Data Cleaning
Menghapus simbol seperti $ dan , pada kolom pendapatan (Income) dan mengonversinya ke tipe data numerik.
Mengonversi kolom tanggal seperti Dt_Customer menjadi tipe data datetime untuk analisis berbasis waktu.
2. Exploratory Data Analysis (EDA)
Memeriksa distribusi data demografis dan pengeluaran produk.
Mengidentifikasi data duplikat, missing values, atau outliers yang dapat mempengaruhi hasil analisis.
3. Feature Engineering
Mengubah beberapa kolom menjadi lebih bersih dan siap digunakan untuk model prediktif.
Membuat visualisasi yang relevan untuk menunjukkan hubungan antara variabel.

**Tools and Libraries Used**

- Python: Untuk pengolahan data dan pembuatan model.
- Pandas: Digunakan untuk manipulasi data.
- NumPy: Digunakan untuk operasi matematis.
- Matplotlib & Seaborn: Untuk visualisasi data.
- Scikit-learn: Digunakan untuk analisis prediktif.

**Conclusion:**
Proyek ini memberikan insight terkait perilaku pelanggan dalam merespons campaign pemasaran. Dengan membersihkan data dan melakukan analisis mendalam, hasil akhir membantu mengidentifikasi karakteristik pelanggan yang berpotensi memberikan respon positif terhadap penawaran produk di masa depan.
