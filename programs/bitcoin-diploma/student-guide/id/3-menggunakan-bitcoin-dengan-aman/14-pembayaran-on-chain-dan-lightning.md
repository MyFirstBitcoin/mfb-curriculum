# 3.14 Pembayaran On-chain dan Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->
[Pembayaran di blockchain dicatat langsung di blockchain Bitcoin, sedangkan Lightning adalah jaringan pembayaran yang dibangun di atas Bitcoin untuk pembayaran cepat dan berfrekuensi tinggi yang juga dapat gagal. Kedua jalur ini dapat menggunakan kustodi pihak ketiga atau kustodi mandiri.](/micrographics/on-chain-and-lightning-01/id.md)



<!-- card: definition -->
> **Definition – Pembayaran on-chain dan Lightning**
>
> [Pembayaran on-chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) dicatat di Bitcoin dalam [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) dan memperoleh [konfirmasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning adalah jaringan pembayaran yang dibangun di atas Bitcoin dan dapat mendukung pembayaran yang cepat dan sering dilakukan. Pembayaran Lightning dapat selesai dengan cepat atau gagal, dan dompetnya tetap dapat bersifat kustodial atau nonkustodial.



<!-- card: dark -->
> **Jalur pembayaran tidak menentukan kustodi**
>
> Pembayaran on-chain dan Lightning memiliki [kelebihan dan keterbatasan yang berbeda](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Dompet Lightning dapat bersifat kustodial atau nonkustodial, dan pembayaran yang berhasil dengan cepat tidak membuktikan bahwa suatu layanan cocok untuk saldo yang lebih besar atau untuk setiap situasi.



<!-- micrographic: onchain-lightning-table-01 -->
[Tabel yang membandingkan Bitcoin on-chain dan Lightning: informasi untuk menerima pembayaran, hasil pembayaran, penggunaan umum, dan pemeriksaan bagi pemula. Kedua jalur dapat menggunakan kustodi pihak ketiga atau kustodi mandiri.](/micrographics/onchain-lightning-table-01/id.md)


Jalur mana yang diharapkan oleh penerima? Sebelum membayar, pastikan apakah penerima telah memberikan alamat on-chain atau [tagihan Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) atau permintaan pembayaran. Dompet on-chain tidak dapat langsung membayar setiap [tagihan Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), dan dompet Lightning mungkin tidak mendukung setiap tindakan on-chain. Beberapa aplikasi mendukung kedua jalur tersebut, tetapi mungkin menambahkan biaya atau ketergantungan pada layanan. Pengaturan Lightning secara terperinci, kanal, perutean, dan [likuiditas](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) merupakan materi [Pembelajaran Lanjutan](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); praktik langsung di lokasi merupakan bagian dari **Modul 4** jika aman dan sesuai.

Bayangkan sebuah skenario yang telah disiapkan menawarkan kedua jalur pembayaran. Permintaan pembayaran mana yang dapat digunakan oleh dompet yang dimaksud, dan apa yang akan Anda periksa sebelum menyetujuinya? Jawabannya bergantung pada permintaan pembayaran dari penerima, dompet, dan situasinya — bukan pada satu jalur “terbaik” yang berlaku secara universal.

![Pendidik menunjuk dua jalur pembayaran berbentuk geometris yang berbeda pada papan, sementara peserta didik pemula dan peserta didik berlatar belakang teknis mempertimbangkan keduanya.](https://cdn.sanity.io/images/vje9ehw2/production/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
