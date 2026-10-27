# 10.9 Daftar Periksa Modul Lightning

Sebelum lokakarya Lightning, verifikasi dan jelaskan:

* apakah dompet bersifat kustodial atau kustodi mandiri
* bagaimana dompet tersebut didanai
* apakah pendanaan atau penarikan menggunakan transaksi on-chain atau layanan
* pemulihan dan keberlanjutan jika penyedia layanan atau perangkat mengalami kegagalan
* apakah permintaan berupa faktur, [alamat Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) yang didukung, atau jenis lain
* jumlah, satuan, penerima, masa berlaku, biaya, batas, dan [likuiditas](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) yang perlu dipertimbangkan
* seperti apa status berhasil, tertunda, kedaluwarsa, atau gagal ditampilkan
* bagaimana kedua pihak mengonfirmasi hasil secara mandiri; dan
* simulasi luring.


<!-- card: dark -->
> **Satu pembayaran Lightning yang berhasil hanya membuktikan bahwa rute ini berhasil digunakan satu kali**
>
> Hal ini tidak membuktikan bahwa dompet tersebut aman untuk menyimpan saldo yang lebih besar atau bahwa jalur yang sama akan berfungsi di setiap tempat.



<!-- micrographic: lightning-payment-sequence-01 -->
[Pembayaran Lightning dalam enam langkah: penerima membuat permintaan, pengirim memindainya, memeriksa penerima, jumlah, satuan, waktu kedaluwarsa, dan biaya, lalu menyetujuinya, pembayaran dirutekan, dan kedua dompet menunjukkan hasilnya. Setiap dompet dapat bersifat kustodial atau kustodi mandiri, dan pembayaran yang gagal atau kedaluwarsa dimulai kembali dengan permintaan baru.](/micrographics/lightning-payment-sequence-01/id.md)
