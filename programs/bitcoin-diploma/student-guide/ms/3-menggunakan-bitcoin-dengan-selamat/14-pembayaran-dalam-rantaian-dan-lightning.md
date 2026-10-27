# 3.14 Pembayaran dalam Rantaian dan Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->
[Pembayaran dalam rantaian direkodkan secara langsung dalam rantaian blok Bitcoin, manakala Lightning ialah rangkaian pembayaran yang dibina di atas Bitcoin untuk pembayaran pantas dan kerap yang juga boleh gagal. Kedua-dua kaedah ini boleh menggunakan jagaan pihak ketiga atau jagaan kendiri.](/micrographics/on-chain-and-lightning-01/ms.md)



<!-- card: definition -->
> **Definition – Pembayaran dalam rantaian dan Lightning**
>
> [Pembayaran dalam rantaian](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) direkodkan dalam [rantaian blok Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) dan memperoleh [pengesahan](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning ialah rangkaian pembayaran yang dibina di atas Bitcoin yang boleh menyokong pembayaran pantas dan kerap. Pembayaran Lightning mungkin selesai dengan cepat atau gagal, dan dompetnya masih boleh berupa dompet jagaan pihak ketiga atau jagaan kendiri.



<!-- card: dark -->
> **Laluan pembayaran tidak menentukan penjagaan**
>
> Pembayaran dalam rantaian dan Lightning melibatkan pelbagai [kompromi](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Dompet Lightning boleh berupa dompet jagaan pihak ketiga atau jagaan kendiri, dan pembayaran yang berjaya dengan pantas tidak membuktikan bahawa sesuatu perkhidmatan sesuai untuk baki yang lebih besar atau setiap situasi.



<!-- micrographic: onchain-lightning-table-01 -->
[Jadual yang membandingkan Bitcoin dalam rantaian dengan Lightning: maklumat penerimaan, hasil pembayaran, kegunaan lazim dan semakan untuk pemula. Kedua-dua kaedah boleh menggunakan penjagaan aset oleh pihak ketiga atau penjagaan aset sendiri.](/micrographics/onchain-lightning-table-01/ms.md)


Laluan manakah yang dijangkakan oleh penerima? Sahkan sama ada mereka telah memberikan alamat dalam rantaian atau [invois Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) atau permintaan sebelum membuat pembayaran. Dompet dalam rantaian tidak boleh membayar setiap [invois Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) secara langsung, dan dompet Lightning mungkin tidak menyokong setiap tindakan dalam rantaian. Sesetengah aplikasi menyokong kedua-dua laluan tetapi mungkin mengenakan fi tambahan atau menambah kebergantungan pada perkhidmatan. Persediaan Lightning secara terperinci, saluran, penghalaan dan [kecairan](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) tergolong dalam [Pembelajaran Lanjutan](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); latihan amali secara langsung di lokasi setempat merupakan sebahagian daripada **Modul 4** apabila selamat dan sesuai.

Bayangkan bahawa suatu senario yang disediakan menawarkan kedua-dua laluan pembayaran. Permintaan manakah yang boleh digunakan oleh dompet yang dimaksudkan, dan apakah yang akan anda semak sebelum meluluskannya? Jawapannya bergantung pada permintaan penerima, dompet dan situasi — bukan pada satu laluan “terbaik” untuk semua keadaan.

![Pendidik menunjuk ke arah dua laluan pembayaran berbentuk geometri yang berbeza pada papan sementara pelajar pemula dan pelajar teknikal menelitinya.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
