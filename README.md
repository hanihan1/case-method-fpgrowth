# Case Method Data Mining — FP-Growth

Repository ini berisi proyek Case Method mata kuliah Data Mining untuk menganalisis pola keranjang belanja pada dataset Online Retail menggunakan algoritma FP-Growth dan aturan asosiasi.

## Informasi proyek
- Mata kuliah: Data Mining
- Metode: Case Method
- Algoritma: FP-Growth
- Dataset: Online Retail (UCI Machine Learning Repository)
- Fokus analisis: transaksi pelanggan United Kingdom

## Alur Case Method
1. Memahami karakteristik dataset dan kualitas data.
2. Melakukan preprocessing transaksi.
3. Menganalisis pola awal dan membentuk matriks transaksi biner.
4. Menemukan frequent itemset dengan FP-Growth.
5. Mengevaluasi aturan menggunakan support, confidence, dan lift.
6. Mengidentifikasi produk yang paling sering muncul pada aturan teratas.
7. Menyusun rekomendasi dan kesimpulan.

## Struktur repository
```text
case-method-fpgrowth/
├── README.md
├── requirements.txt
├── 01-memahami-dataset/
├── 02-data-preprocessing/
├── 03-implementasi-fpgrowth/
│   └── FP_Growth_Online_Retail_Colab_revisi.ipynb
├── 04-hasil-dan-visualisasi/
└── 05-laporan/
```

## Menjalankan notebook
Buka notebook implementasi di Google Colab, unggah `Online_Retail.xlsx` saat diminta, lalu jalankan sel secara berurutan. Instal dependensi dengan `pip install -r requirements.txt` jika menjalankannya di lingkungan lokal. Dataset tidak disertakan; unduh dari UCI Machine Learning Repository.

## Catatan metodologi
Aturan asosiasi menunjukkan keterkaitan, bukan hubungan sebab-akibat. Hasil notebook bergantung pada data dan parameter yang digunakan.
