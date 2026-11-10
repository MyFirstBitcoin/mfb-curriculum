# 2.3 Percubaan awal wang digital dan masalah perbelanjaan berganda

Bitcoin bukanlah percubaan pertama untuk mewujudkan wang digital. Ia dibangunkan berasaskan empat dekad percubaan, dengan memanfaatkan idea daripada banyak projek terdahulu yang membantu membentuk reka bentuknya yang berjaya.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) menggunakan [kriptografi](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) untuk menyokong pembayaran digital yang menjaga privasi. Ia bergantung pada sebuah syarikat pusat dan hubungan dengan institusi perbankan. Apabila syarikat itu gagal, sistem tersebut tidak dapat diteruskan sebagai rangkaian wang yang bebas.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) menggunakan [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) untuk menjadikan penghantaran e-mel yang tidak diingini memerlukan kos yang tinggi. Komputer pengirim perlu melaksanakan kerja sebelum menghantar mesej. Idea ini menunjukkan bagaimana kos pengkomputeran dapat membendung penyalahgunaan.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) menghuraikan satu cadangan sistem yang membolehkan kerja pengkomputeran menghasilkan rekod digital yang terhad bekalannya. Ia tidak dilancarkan sebagai sistem wang terdesentralisasi yang lengkap, tetapi ia mengembangkan idea penting tentang sifat digital yang [terhad](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) dan bukti.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) dan [**bukti kerja boleh guna semula (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) meneroka cara untuk peserta mencipta atau memindahkan sesuatu yang terhad dalam bentuk digital, iaitu [nilai](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) tanpa bergantung hanya pada satu pangkalan data pusat. Kedua-duanya tidak lengkap, tetapi membantu memperjelas perkara yang diperlukan oleh sistem yang dapat berfungsi.
* Walaupun [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) bukan wang, ia menunjukkan bahawa [rangkaian rakan ke rakan](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) boleh membolehkan banyak komputer bebas berkongsi maklumat tanpa satu pelayan pusat mengawal keseluruhan sistem.

Secara bersama, percubaan ini menunjukkan unsur-unsur berguna yang diperlukan untuk melengkapkan sistem tersebut. Percubaan ini juga memperjelas masalah yang masih belum diselesaikan.


> **Definition – Perbelanjaan berganda**
>
> [Perbelanjaan berganda](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) ialah percubaan untuk menghantar unit digital yang sama kepada dua penerima. Data digital boleh disalin dengan sempurna, maka sistem wang digital memerlukan cara untuk menentukan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) yang sah.


[Sistem berpusat](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) mencegah perkara ini dengan membenarkan satu pangkalan data yang dipercayai menentukan pembayaran yang dibuat terlebih dahulu. Pada 31 Oktober 2008, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) dalam kertas putihnya, [_Bitcoin: Sistem Wang Tunai Elektronik Rakan ke Rakan_](https://bitcoin.org/bitcoin.pdf), menerangkan pendekatan yang berbeza: sistem awam yang boleh mewujudkan sejarah pembayaran bersama tanpa bank, syarikat atau pihak berkuasa pusat yang lain.

Kertas putih itu menghimpunkan ciri-ciri yang diperlukan untuk pendekatan tersebut:

1. **Sebuah [rangkaian rakan ke rakan](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) diumumkan secara langsung kepada rangkaian peserta.
1. **[Tandatangan digital](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** satu [kunci peribadi](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ialah maklumat rahsia yang menghasilkan tandatangan untuk membenarkan perbelanjaan; hanya pemegangnya boleh berbuat demikian.
1. **Blok dan [perlombongan](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [pelombong](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mengumpulkan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ke dalam blok dan menggunakan [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) untuk bersaing menambah blok seterusnya.
1. **Kebebasan [pengesahan](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) menyemak [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dan blok berdasarkan peraturan Bitcoin.
1. **Sejarah bersama dengan pengumpulan [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** peserta mengiktiraf [rantaian sah](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) bagi [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dengan jumlah tertinggi [kerja terkumpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) sebagai rekod bersama.


<!-- micrographic: five-part-response-01 -->


Modul ini menerangkan konsep-konsep ini dengan lebih terperinci. Secara bersama, konsep-konsep ini memberikan penyelesaian praktikal kepada [masalah perbelanjaan berganda](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): rangkaian boleh menolak percubaan kedua untuk membelanjakan bitcoin yang sama tanpa bergantung pada pihak berkuasa pusat. Bitcoin menawarkan gabungan yang selama ini belum ditemui dan telah dicari melalui eksperimen wang digital selama beberapa dekad.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
