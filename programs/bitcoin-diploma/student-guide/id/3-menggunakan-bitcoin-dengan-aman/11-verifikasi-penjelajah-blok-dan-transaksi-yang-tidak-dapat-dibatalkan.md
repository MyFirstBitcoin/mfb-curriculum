# 3.11 Verifikasi, Penjelajah Blok, dan Transaksi yang Tidak Dapat Dibatalkan

<!-- card: definition -->
> **Definition – ID transaksi dan penjelajah blok**
>
> Sebuah [ID transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) mengidentifikasi sebuah [transaksi on-chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Sebuah [penjelajah blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) menampilkan data publik Bitcoin, seperti data [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) berupa status dan jumlah [konfirmasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) yang diterima. Penjelajah blok merupakan sarana yang berguna untuk melihat data, bukan otoritas atas Bitcoin dan bukan bukti identitas atau kejujuran penerima.


Apa yang dapat ditunjukkan oleh informasi publik ini, dan apa yang tidak dapat ditunjukkannya? Informasi ini dapat menunjukkan data [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) berupa status, tujuan, jumlah, biaya, dan jumlah [konfirmasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) yang diterima; informasi ini tidak dapat membuktikan alasan suatu pembayaran dilakukan atau apakah seseorang dapat dipercaya. Sebuah [transaksi on-chain](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) belum terkonfirmasi setelah [disiarkan](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) dan memperoleh [konfirmasi pertama](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) saat dimasukkan ke dalam blok yang valid. Blok-blok berikutnya meningkatkan keyakinan akan posisinya dalam catatan, tetapi tidak memperbaiki tujuan yang salah atau penipuan. Tidak ada jumlah [konfirmasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) yang berlaku universal untuk setiap pembayaran; pemeriksaan yang sesuai bergantung pada jumlah dan risikonya.

Untuk memeriksa [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) yang telah disiapkan, dapatkan [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) transaksi tersebut, buka penjelajah tepercaya untuk [jaringan Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) yang dimaksud, lalu periksa status, tujuan, jumlah, biaya, dan [konfirmasinya](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Penjelajah hanyalah sebuah antarmuka. Pencarian alamat atau [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) dapat mengungkapkan kepada operatornya bahwa perangkat Anda tertarik pada informasi tersebut. Untuk latihan, gunakan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) yang disiapkan oleh pendidik atau tangkapan layar yang dicetak. Jangan mencari alamat pribadi atau [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) milik peserta didik di layanan publik. Jika kelak Anda menelusuri pembayaran pribadi, pelajari [privasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) dan keamanan serta [kompromi yang menyertainya](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) pada koneksi Anda sebelum menggunakan layanan publik.


<!-- card: callout -->
> **Data publik bukan bukti identitas atau kejujuran**
>
> Sebuah [penjelajah blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) dapat menampilkan data publik tentang [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), tetapi tidak dapat membuktikan siapa yang mengendalikan suatu alamat, mengapa suatu pembayaran dilakukan, atau apakah penerima dapat dipercaya. Gunakan contoh yang telah disiapkan untuk berlatih dan lindungi [privasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) saat melakukan pencarian di layanan publik.



<!-- micrographic: confirmation-timeline-01 -->
[Sebuah transaksi menunggu tanpa konfirmasi di kumpulan transaksi tertunda, lalu dimasukkan ke dalam Blok N sebagai konfirmasi pertamanya, dan setiap blok berikutnya menambahkan satu konfirmasi lagi.](/micrographics/confirmation-timeline-01/id.md)


![Pendidik dan peserta didik yang lebih tua mendiskusikan contoh yang telah disiapkan pada monitor yang menghadap ke kelompok, sementara peserta didik yang memahami teknologi mengoperasikan tetikus; penonton melihat penutup belakang monitor.](https://cdn.sanity.io/images/vje9ehw2/staging/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
