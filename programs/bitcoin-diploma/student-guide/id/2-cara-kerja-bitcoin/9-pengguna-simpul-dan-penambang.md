# 2.9 Pengguna, Simpul, dan Penambang

Bitcoin berfungsi karena para pesertanya menjalankan peran yang berbeda-beda.

* **Pengguna** menerima, menyimpan, dan mengirim bitcoin. Pengguna dapat mengendalikan kunci mereka sendiri yang disimpan dalam dompet atau menggunakan [kustodian](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Pengguna memberi jaringan makna ekonomi dengan memilih apakah akan menerima bitcoin serta aturan atau layanan mana yang mereka percayai.
* [**Node**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) menjalankan perangkat lunak Bitcoin dan memverifikasi aturan secara mandiri. Sebuah [node penuh](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) memeriksa bahwa [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) memiliki tanda tangan yang valid, bahwa bitcoin belum dibelanjakan, bahwa blok memenuhi persyaratan [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), dan bahwa bitcoin baru mengikuti [jadwal penerbitan](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) berbagi data yang valid dengan node lain dan menolak data yang tidak valid.
* [**Penambang**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mengumpulkan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) yang menunggu diproses, menyusun [kandidat blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block), dan bersaing melalui [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Seorang [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [yang berhasil menyiarkan](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) sebuah blok dan dapat menerima [subsidi blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) yang diizinkan serta [biaya transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) membantu mengurutkan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dan membuat [buku besar](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) membutuhkan biaya besar untuk ditulis ulang.
* **Pengembang** meninjau, menulis, dan mengusulkan perubahan perangkat lunak. Mereka tidak memiliki aturan Bitcoin. Perubahan perangkat lunak hanya berdampak jika para peserta memilih untuk menjalankan perangkat lunak yang mengikuti aturan tersebut.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Empat peran dalam Bitcoin: pengguna menerima, menyimpan, dan mengirim bitcoin, simpul memverifikasi aturan secara mandiri, penambang menyusun calon blok dengan bukti kerja, dan pengembang mengusulkan perangkat lunak. Tidak ada satu peran pun yang mengendalikan jaringan.](/micrographics/bitcoin-participant-roles-01/id.md)


Peran-peran ini saling membatasi:

* pengguna tidak dapat membelanjakan bitcoin tanpa tanda tangan valid yang diperlukan
* seorang [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) dapat mengusulkan sebuah blok, tetapi [node](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) memutuskan apakah blok tersebut mengikuti aturan
* sebuah [simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) memverifikasi berdasarkan aturannya sendiri, tetapi [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) memerlukan aturan yang selaras di seluruh jaringan
* pengembang dapat mengusulkan perangkat lunak, tetapi para peserta memilih apakah akan menjalankannya

Sebagian orang menjalankan beberapa peran. Seorang [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) dapat menjalankan sebuah [simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) dan juga menjadi pengguna. Seorang pemula tidak perlu menjalankan setiap peran untuk menjelaskan bagaimana peran-peran tersebut saling mengimbangi.

**Pertanyaan singkat:** Mengapa sebuah [simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) memverifikasi [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Sebutkan setidaknya satu aturan yang diperiksa oleh sebuah [simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node).

![Pendidik membimbing peserta didik yang mempelajari aspek teknis di depan komputer simpul, dengan monitor menghadap keduanya dan bagian belakang monitor terlihat oleh pemirsa.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
