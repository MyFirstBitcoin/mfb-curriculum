# 2.10 Bukti kerja

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Bukti kerja**
>
> [Bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ialah proses yang [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) gunakan untuk bersaing bagi mendapatkan hak mencadangkan blok seterusnya.


Satu [fungsi cincang](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) menukarkan data kepada hasil dengan panjang tetap. Perubahan kecil pada input menghasilkan hasil baharu yang tidak dapat diramalkan. Seorang [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mengubah sebahagian kecil data dalam blok yang dicadangkan dan mencincangnya berulang kali. Sesuatu hasil hanya sah apabila nombornya berada di bawah nilai yang ditetapkan oleh rangkaian sebagai [sasaran](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), iaitu ambang yang ditetapkan oleh peraturan; nilai yang lebih rendah bagi [sasaran](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) bermakna lebih sedikit [hasil yang sah](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) dan lebih banyak percubaan. Tiada jalan pintas, jadi [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mungkin perlu membuat banyak percubaan.

Apabila seorang [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) menemui [hasil yang sah](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), pelombong itu [menyiarkan](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok tersebut. [Nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) boleh menyemak bukti itu dengan cepat, walaupun usaha menemuinya memerlukan pengiraan dan tenaga yang banyak. Jika blok itu mengandungi suatu [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), maka [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) itu menerima [pengesahan pertamanya](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): rekodnya telah dimasukkan ke dalam satu blok yang sah. Setiap blok sah yang ditambahkan selepasnya menambah satu lagi [pengesahan](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), menjadikan kedudukan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) itu dalam [rantaian blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) lebih mahal untuk ditulis semula. Perbezaan ini penting: kerja memerlukan kos yang tinggi untuk dihasilkan tetapi mudah disahkan.


<!-- micrographic: proof-of-work-process-01 -->
[Pelombong mengira hash bagi blok yang dicadangkan berulang kali sehingga satu hasil berada di bawah sasaran rangkaian, kemudian menyiarkan blok itu. Nod menyemak bukti dan pematuhan terhadap setiap peraturan dengan pantas sebelum blok itu dimasukkan ke dalam rantaian blok: kerja tersebut memerlukan kos yang tinggi untuk dihasilkan tetapi mudah disahkan.](/micrographics/proof-of-work-process-01/ms.md)


[Bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) mempunyai beberapa tujuan:

* ia memberi para [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bebas cara untuk bersaing tanpa penjadual pusat
* ia menjadikan susunan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mahal untuk ditulis semula
* ia mengaitkan keselamatan rangkaian dengan peralatan dan tenaga di dunia nyata
* ia menyokong kaedah terbuka untuk memilih antara sejarah sah yang bersaing: rantaian dengan jumlah terbesar [kerja terkumpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Perlombongan](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) tidak menyelesaikan persamaan yang berguna untuk tujuan luaran. Tujuannya adalah untuk memastikan Bitcoin mempunyai urutan yang terjamin untuk [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Rangkaian melaraskan sasaran secara berkala: apabila blok tiba terlalu cepat, rangkaian menurunkan sasaran, dan apabila blok tiba terlalu lambat, rangkaian menaikkannya, dengan tujuan mengekalkan purata kira-kira satu blok setiap sepuluh minit apabila kuasa pengkomputeran berubah.

[Bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) melibatkan kos tenaga yang nyata. Penyokong berpendapat bahawa kos inilah yang menjadi asas keselamatan Bitcoin dan boleh mewujudkan permintaan untuk tenaga yang penggunaannya boleh dilaraskan atau yang jika tidak digunakan akan terbiar. Pengkritik mempersoalkan jumlah dan sumber tenaga yang digunakan. Penilaian yang bertanggungjawab meneliti tenaga yang digunakan, sumbernya, keselamatan yang disediakannya, serta alternatif yang dibandingkan.

![Pendidik, pelajar pemula dan pelajar teknikal membincangkan sebuah unit perlombongan atas meja yang dilengkapi kipas dan bekalan kuasa berasingan.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
