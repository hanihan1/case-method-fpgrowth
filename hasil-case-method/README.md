# Hasil Case Method: FP-Growth Online Retail

Notebook analisis: [`FP_Growth_Online_Retail.ipynb`](FP_Growth_Online_Retail.ipynb).

Analisis menggunakan data transaksi toko online, dengan satu invoice diperlakukan sebagai satu keranjang belanja. Notebook melakukan pemeriksaan kualitas data, memfokuskan analisis pada transaksi United Kingdom, membuang data transaksi yang tidak sesuai untuk analisis pembelian, lalu membentuk frequent itemsets dan aturan asosiasi menggunakan FP-Growth.

## Ringkasan hasil

Pada keluaran notebook yang tersimpan, data hasil preprocessing mencakup **16.523 transaksi**, menghasilkan **475 frequent itemsets** dan **95 aturan asosiasi dengan lift lebih dari 1**. Pola teratas dan metrik aturannya ditampilkan di notebook; gunakan hasil tersebut untuk melihat pasangan produk secara rinci.

## Kesimpulan 

Hasil menunjukkan adanya sejumlah produk yang cenderung muncul bersama dalam transaksi. Temuan ini dapat menjadi masukan untuk eksplorasi penataan produk atau rekomendasi bundel, tetapi aturan asosiasi hanya menunjukkan keterkaitan dan tidak membuktikan hubungan sebab-akibat. Hasil juga bergantung pada preprocessing dan parameter yang digunakan.

Analisis lanjutan dapat membandingkan FP-Growth dengan Apriori, melihat perubahan pola menurut periode waktu, atau mengelompokkan produk berdasarkan kategori.
