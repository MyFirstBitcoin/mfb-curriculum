# 2.9 Pengguna, nod dan pelombong

Bitcoin berfungsi kerana peserta yang berbeza menjalankan peranan yang berbeza.

* **Pengguna** menerima, menyimpan dan menghantar bitcoin. Pengguna boleh mengawal kunci mereka sendiri yang disimpan dalam dompet atau menggunakan khidmat [kustodian](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Pengguna memberikan makna ekonomi kepada rangkaian dengan memilih sama ada untuk menerima bitcoin serta peraturan atau perkhidmatan yang mereka percayai.
* [**Nod**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) menjalankan perisian Bitcoin dan mengesahkan peraturan secara bebas. Sesebuah [nod penuh](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) menyemak bahawa [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mempunyai tandatangan yang sah, bahawa bitcoin belum dibelanjakan, bahawa blok memenuhi syarat [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), dan bahawa bitcoin baharu mengikut [jadual penerbitan](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) berkongsi data yang sah dengan nod rakan setara dan menolak data yang tidak sah.
* [**Pelombong**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mengumpulkan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) yang belum diproses, membina [blok calon](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block), dan bersaing melalui [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Apabila berjaya, seorang [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [menyiarkan](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) satu blok dan boleh menerima [subsidi blok](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) serta [fi transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee) yang dibenarkan. [Pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) membantu menyusun urutan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dan menjadikan [lejar](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) mahal untuk ditulis semula.
* **Pembangun** menyemak, menulis dan mencadangkan perubahan perisian. Mereka tidak memiliki peraturan Bitcoin. Sesuatu perubahan perisian hanya memberikan kesan jika peserta memilih untuk menjalankan perisian yang mengikut peraturan tersebut.


<!-- micrographic: bitcoin-participant-roles-01 -->


Peranan ini saling mengehadkan:

* pengguna tidak boleh membelanjakan bitcoin tanpa tandatangan sah yang diperlukan
* seorang [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) boleh mencadangkan satu blok, tetapi [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) menentukan sama ada blok itu mengikut peraturan
* sebuah [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) mengesahkan mengikut peraturannya sendiri, tetapi [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) memerlukan peraturan yang serasi di seluruh rangkaian
* pembangun boleh mencadangkan perisian, tetapi peserta memilih sama ada untuk menjalankannya

Sesetengah orang menjalankan beberapa peranan. Seorang [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) boleh menjalankan sebuah [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) dan juga menjadi pengguna. Seorang pemula tidak perlu menjalankan setiap peranan untuk menerangkan bagaimana peranan-peranan tersebut saling mengimbangi.

**Soalan spontan:** Mengapakah sebuah [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) mengesahkan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Nyatakan sekurang-kurangnya satu peraturan yang diperiksa oleh sebuah [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node).

![Pendidik membimbing pelajar teknikal di sebuah komputer nod, dengan monitor menghadap mereka dan bahagian belakang monitor kelihatan kepada pemerhati.](https://cdn.sanity.io/images/vje9ehw2/production/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
