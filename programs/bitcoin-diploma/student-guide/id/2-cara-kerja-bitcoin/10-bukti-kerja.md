# 2.10 Bukti Kerja

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Bukti kerja**
>
> [Bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) adalah proses yang [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gunakan untuk bersaing mendapatkan hak mengusulkan blok berikutnya.


Sebuah [fungsi hash](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) mengubah data menjadi hasil dengan panjang tetap. Perubahan kecil pada masukan menghasilkan hasil baru yang tidak dapat diprediksi. Seorang [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mengubah sebagian kecil data dalam blok yang diusulkan dan melakukan hashing berulang kali. Suatu hasil hanya valid jika angkanya berada di bawah [target](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) jaringan, yaitu ambang batas yang ditetapkan oleh aturan; [target](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) yang lebih rendah berarti lebih sedikit [hasil yang valid](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) dan lebih banyak percobaan. Tidak ada jalan pintas, sehingga [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mungkin perlu melakukan banyak percobaan.

Ketika seorang [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) menemukan [hasil yang valid](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), ia [menyiarkan](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok tersebut. [Simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) dapat memeriksa bukti tersebut dengan cepat, meskipun untuk menemukannya diperlukan komputasi dan energi yang besar. Jika blok tersebut memuat sebuah [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tersebut menerima [konfirmasi pertamanya](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): catatannya telah dimasukkan ke dalam satu blok yang valid. Setiap blok valid yang ditambahkan setelahnya menambahkan satu [konfirmasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) lagi, sehingga posisi [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tersebut dalam [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) menjadi lebih mahal untuk diubah. Perbedaan ini penting: kerja membutuhkan biaya besar untuk dihasilkan, tetapi mudah diverifikasi.


<!-- micrographic: proof-of-work-process-01 -->
[Penambang menghitung hash dari blok yang diusulkan berulang kali hingga salah satu hasilnya berada di bawah target jaringan, lalu menyiarkan blok tersebut. Simpul memeriksa bukti dan kepatuhan terhadap setiap aturan dengan cepat sebelum blok masuk ke blockchain: menghasilkan bukti kerja membutuhkan biaya besar, tetapi memverifikasinya mudah.](/micrographics/proof-of-work-process-01/id.md)


[Bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) memiliki beberapa tujuan:

* memberikan cara bagi [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) independen untuk bersaing tanpa pengatur jadwal terpusat
* membuat urutan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) membutuhkan biaya besar untuk diubah
* mengaitkan keamanan jaringan dengan peralatan dan energi di dunia nyata
* mendukung metode publik untuk memilih di antara riwayat valid yang saling bersaing: rantai dengan [akumulasi kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) terbanyak

[Penambangan](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) tidak memecahkan persamaan yang berguna untuk tujuan di luar Bitcoin. Tujuannya adalah mengamankan pengurutan [transaksi Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Jaringan secara berkala menyesuaikan target: ketika blok muncul terlalu cepat, jaringan menurunkan target, dan ketika blok muncul terlalu lambat, jaringan menaikkannya. Penyesuaian ini bertujuan untuk mempertahankan rata-rata sekitar satu blok setiap sepuluh menit seiring perubahan daya komputasi.

[Bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) melibatkan biaya energi yang nyata. Para pendukung berpendapat bahwa biaya inilah yang menjadi landasan keamanan Bitcoin dan dapat menciptakan permintaan akan energi yang penggunaannya dapat disesuaikan atau yang jika tidak digunakan untuk penambangan akan terbuang. Para pengkritik mempertanyakan jumlah dan sumber energi yang digunakan. Evaluasi yang bertanggung jawab menanyakan energi apa yang digunakan, dari mana asalnya, keamanan seperti apa yang dihasilkannya, dan alternatif apa saja yang dibandingkan.

![Pendidik, peserta didik pemula, dan peserta didik teknis mendiskusikan sebuah unit penambangan di atas meja yang dilengkapi kipas dan catu daya terpisah.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
