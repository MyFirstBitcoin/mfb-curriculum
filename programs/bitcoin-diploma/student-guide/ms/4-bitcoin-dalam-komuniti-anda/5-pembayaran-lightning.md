# 4.5 Pembayaran Lightning

![](https://cdn.sanity.io/images/vje9ehw2/production/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Penerima membuat permintaan pembayaran Lightning yang menyertakan jumlah bayaran pada telefonnya, pengirim mengimbas permintaan tersebut dan membayar, dan bayaran diterima pada telefon penerima sejurus kemudian.](/micrographics/lightning-phone-payment-01/ms.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[Pembayaran Lightning dalam enam langkah: penerima mencipta permintaan, pengirim mengimbasnya, menyemak penerima, amaun, unit, masa luput dan fi, meluluskannya, pembayaran dihalakan, dan kedua-dua dompet menunjukkan hasilnya. Setiap dompet mungkin bersifat kustodian atau jagaan sendiri, dan pembayaran yang gagal atau tamat tempoh dimulakan semula dengan permintaan baharu.](/micrographics/lightning-payment-sequence-01/ms.md)


Lightning boleh menjadikan pembayaran Bitcoin yang pantas dan kecil praktikal. Ia mungkin sesuai untuk kaunter peniaga, pembayaran tempatan yang berulang, perkhidmatan dalam talian, atau pemindahan yang fi dalam rantaiannya terlalu tinggi berbanding dengan jumlah pembayaran.

Demonstrasi Lightning setempat perlu mengenal pasti:

* sama ada dompet itu di bawah jagaan pihak ketiga atau jagaan sendiri
* cara dana dimasukkan ke dalam dompet
* sama ada pendanaan memerlukan pelaksanaan dalam rantaian bagi [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) atau suatu perkhidmatan
* sandaran atau kaedah pemulihan yang melindungi baki
* jenis permintaan pembayaran yang digunakan
* fi atau had yang dikenakan
* perkara yang berlaku apabila pembayaran gagal
* cara penerima mengesahkan pembayaran

Suatu [**invois Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) ialah permintaan pembayaran yang dicipta untuk pembayaran tertentu. Ia boleh merangkumi jumlah, maklumat destinasi, dan masa luput. Baca [pengesahan](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) pada skrin dompet sebelum membuat pembayaran.

Suatu [**alamat Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) ialah pengecam yang boleh dibaca oleh manusia dan disokong oleh sesetengah perkhidmatan. Ia mungkin kelihatan seperti alamat e-mel, tetapi ia merupakan kemudahan untuk menghalakan pembayaran, bukan akaun e-mel. Ia bergantung pada penyedia atau domain yang menyokongnya.

Untuk pembayaran berpandu:

1. Penerima mencipta permintaan yang betul.
1. Pengirim mengimbas atau menyalinnya.
1. Pengirim menyemak penerima, jumlah, unit, dan fi.
1. Pengirim hanya meluluskan pembayaran setelah butirannya betul.
1. Kedua-dua pihak mengesahkan hasilnya dalam dompet masing-masing.
1. Kumpulan menerangkan risiko [penjagaan aset](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) dan kegagalan.

Jangan menganggap bahawa pembayaran Lightning yang berjaya membuktikan dompet itu selamat untuk menyimpan baki yang lebih besar. Kemudahan pembayaran dan [penjagaan aset](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) yang selamat ialah dua perkara yang berbeza.
