# 8.10 Pengguna, node, penambang, pengembang, dan layanan

Gunakan batasan berikut secara tepat untuk pemula:


| Peran | Fungsi utama untuk pemula | Tidak berarti |
| --- | --- | --- |
| Pengguna | Memilih untuk menerima, menyimpan, mengirim, memverifikasi, dan menerima pembayaran dalam bitcoin, secara langsung atau melalui layanan | Secara otomatis menjalankan setiap bagian jaringan |
| Simpul | Secara mandiri memeriksa transaksi dan blok berdasarkan aturannya serta meneruskan data yang valid | Membuat blok baru atau mendiktekan aturan kepada semua pihak |
| Penambang | Menyusun blok kandidat dan melakukan bukti kerja untuk mengusulkan urutan blok-blok tersebut | Dapat membuat penerbitan atau transaksi yang tidak valid menjadi valid bagi simpul yang jujur |
| Pengembang | Meninjau, menulis, dan mengusulkan perangkat lunak | Dapat memaksa peserta untuk mengadopsi perubahan aturan |
| Layanan Bitcoin | Menyediakan dompet, bursa, penjelajah blok, antarmuka pembayaran, atau antarmuka lainnya | Merupakan protokol Bitcoin itu sendiri |



<!-- micrographic: bitcoin-participant-roles-01 -->
[Empat peran dalam Bitcoin: pengguna menerima, menyimpan, dan mengirim bitcoin, simpul memverifikasi aturan secara mandiri, penambang menyusun calon blok dengan bukti kerja, dan pengembang mengusulkan perangkat lunak. Tidak ada satu peran pun yang mengendalikan jaringan.](/micrographics/bitcoin-participant-roles-01/id.md)


#### Aktivitas: blok tidak valid

Berikan kepada seorang peserta didik yang berperan sebagai [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) sebuah [blok kandidat](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) yang menghasilkan subsidi lebih besar daripada yang diizinkan oleh [simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) dalam kartu aturannya. Peserta didik yang berperan sebagai [simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) memeriksa dan menolaknya.

Pembahasan:

* Sang [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) benar-benar melakukan kerja, tetapi tetap tidak memperoleh izin untuk melanggar aturan.
* [Simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) menerapkan aturan secara mandiri, tetapi jaringan yang sebenarnya terdiri atas perangkat lunak dan komunikasi, bukan pemungutan suara di kelas.
* Seorang pengembang dapat menulis aturan lain, tetapi adopsinya bersifat sukarela dan aturan yang tidak kompatibel dapat menciptakan jaringan terpisah.

Tanyakan:

> Mengapa sebuah [simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) memverifikasi transaksi? Sebutkan setidaknya satu aturan yang diperiksanya.
