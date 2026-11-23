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
├── dataset/
│   └── README.md
├── program/
│   └── README.md
└── hasil-case-method/
    └── README.md
```

## Menjalankan program
Buka notebook implementasi pada folder `program/` di Google Colab, unggah dataset Online Retail jika diperlukan, lalu jalankan sel secara berurutan.

Instal dependensi dengan:

```bash
pip install -r requirements.txt
```

## Catatan metodologi
Aturan asosiasi menunjukkan keterkaitan, bukan hubungan sebab-akibat. Hasil notebook bergantung pada data dan parameter yang digunakan.
