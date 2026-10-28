# 4.5 Pembayaran Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Penerima membuat permintaan pembayaran Lightning yang mencantumkan jumlahnya di ponselnya, pengirim memindainya lalu membayar, dan pembayaran diterima di ponsel penerima sesaat kemudian.](/micrographics/lightning-phone-payment-01/id.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[Pembayaran Lightning dalam enam langkah: penerima membuat permintaan, pengirim memindainya, memeriksa penerima, jumlah, satuan, waktu kedaluwarsa, dan biaya, lalu menyetujuinya, pembayaran dirutekan, dan kedua dompet menunjukkan hasilnya. Setiap dompet dapat bersifat kustodial atau kustodi mandiri, dan pembayaran yang gagal atau kedaluwarsa dimulai kembali dengan permintaan baru.](/micrographics/lightning-payment-sequence-01/id.md)


Lightning dapat membuat pembayaran Bitcoin bernilai kecil dapat dilakukan dengan cepat dan praktis. Lightning mungkin cocok digunakan di loket pembayaran pedagang, untuk pembayaran lokal yang berulang, layanan daring, atau transfer yang biaya on-chain-nya terlalu besar dibandingkan dengan nilai pembayaran.

Demonstrasi Lightning setempat perlu menjelaskan:

* apakah dompet bersifat kustodial atau kustodi mandiri
* bagaimana dompet diisi dana
* apakah pendanaan memerlukan proses on-chain berupa [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) atau suatu layanan
* mekanisme pencadangan atau pemulihan apa yang melindungi saldo
* jenis permintaan pembayaran apa yang digunakan
* biaya atau batasan apa yang berlaku
* apa yang terjadi ketika pembayaran gagal
* bagaimana penerima mengonfirmasi pembayaran

Sebuah [**faktur Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) adalah permintaan pembayaran yang dibuat untuk pembayaran tertentu. Faktur ini dapat mencakup jumlah, informasi tujuan, dan waktu kedaluwarsa. Bacalah layar [konfirmasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) pada dompet Anda sebelum membayar.

Sebuah [**alamat Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) adalah pengenal yang mudah dibaca manusia dan didukung oleh sejumlah layanan. Bentuknya mungkin menyerupai alamat surel, tetapi fungsinya adalah mempermudah perutean pembayaran, bukan sebagai akun surel. Alamat ini bergantung pada penyedia atau domain yang mendukungnya.

Untuk pembayaran dengan panduan:

1. Penerima membuat permintaan yang benar.
1. Pengirim memindai atau menyalinnya.
1. Pengirim memeriksa penerima, jumlah, satuan, dan biaya.
1. Pengirim hanya menyetujui setelah semua perinciannya benar.
1. Kedua pihak mengonfirmasi hasilnya di dompet masing-masing.
1. Kelompok menjelaskan risiko terkait [kustodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) dan kegagalan.

Jangan menganggap bahwa keberhasilan pembayaran Lightning membuktikan dompet tersebut aman untuk menyimpan saldo yang lebih besar. Kemudahan pembayaran dan [kustodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) yang aman merupakan dua persoalan yang berbeda.
