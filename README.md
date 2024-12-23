# Perbandingan Algoritma Insertion Sort untuk Pengelolaan Stok Obat

Repositori ini berisi sebuah notebook Jupyter untuk membandingkan performa algoritma **Insertion Sort (Iteratif)** dan **Insertion Sort (Rekursif)** dalam konteks pengurutan data stok obat berdasarkan kuantitas. Proyek ini bertujuan untuk menganalisis dan memvisualisasikan performa kedua metode pengurutan ketika diterapkan pada dataset dengan berbagai ukuran, khususnya untuk pengelolaan stok obat.

## Gambaran Umum Proyek

Tujuan utama dari proyek ini adalah untuk mengevaluasi kompleksitas waktu dan performa kedua algoritma pengurutan (iteratif dan rekursif) ketika mengurutkan daftar obat dengan kuantitas stoknya. Hal ini dilakukan dengan menghasilkan dataset stok obat dan menerapkan kedua metode pengurutan, kemudian menganalisis waktu eksekusi mereka untuk dataset yang kecil dan besar.

### Fitur Utama

- **Pembuatan Data**: Daftar nama obat dan kuantitasnya dihasilkan secara acak untuk mensimulasikan stok obat dalam sebuah inventaris.
- **Algoritma Pengurutan**: Baik **Insertion Sort Iteratif** maupun **Insertion Sort Rekursif** diimplementasikan dan diterapkan pada dataset.
- **Analisis Performa**: Waktu eksekusi kedua algoritma dibandingkan untuk berbagai ukuran dataset (dari yang kecil hingga besar).
- **Visualisasi**: Waktu eksekusi digambarkan dalam grafik untuk membandingkan performa kedua algoritma.

## Hasil

- **Dataset Kecil**: Untuk dataset yang lebih kecil, kedua metode (iteratif dan rekursif) menunjukkan performa yang serupa.
- **Dataset Besar**: Saat ukuran dataset meningkat, **Insertion Sort Iteratif** menunjukkan peningkatan waktu eksekusi yang lebih signifikan dibandingkan dengan **Insertion Sort Rekursif**, yang menunjukkan performa lebih baik untuk dataset yang lebih besar meskipun kedua algoritma memiliki kompleksitas waktu yang sama, yaitu **O(n²)**.

## Kesimpulan

- Untuk dataset kecil, baik **Insertion Sort Iteratif** maupun **Insertion Sort Rekursif** dapat digunakan dengan performa yang hampir setara.
- Untuk dataset yang lebih besar, **Insertion Sort Rekursif** lebih efisien dibandingkan **Insertion Sort Iteratif** karena memberikan waktu eksekusi yang lebih cepat.

## Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.
