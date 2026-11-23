# Case Method Data Mining — FP-Growth

Repository ini berisi proyek Case Method mata kuliah Data Mining untuk menganalisis pola keranjang belanja pada dataset Online Retail menggunakan algoritma FP-Growth.

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
├── dataset/
│   ├── README.md
│   └── Online_Retail.zip
└── hasil-case-method/
    ├── README.md
    └── FP_Growth_Online_Retail.ipynb
```

## Menjalankan program
Buka notebook implementasi pada folder `program/` di Google Colab, unggah dataset Online Retail jika diperlukan, lalu jalankan sel secara berurutan.
