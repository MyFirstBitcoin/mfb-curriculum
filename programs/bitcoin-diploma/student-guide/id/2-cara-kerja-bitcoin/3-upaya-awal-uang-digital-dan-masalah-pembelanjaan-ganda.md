# 2.3 Upaya Awal Uang Digital dan Masalah Pembelanjaan Ganda

Bitcoin bukanlah upaya pertama untuk menciptakan uang digital. Bitcoin dibangun berdasarkan empat dekade eksperimen, dengan memanfaatkan gagasan dari berbagai proyek sebelumnya yang turut membentuk desainnya yang berhasil.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) menggunakan [kriptografi](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) untuk mendukung pembayaran digital yang menjaga privasi. Sistem ini bergantung pada sebuah perusahaan pusat dan hubungan dengan perbankan. Ketika perusahaan tersebut gagal, sistem ini tidak dapat terus beroperasi sebagai jaringan uang yang mandiri.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) menggunakan [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) agar pengiriman surel yang tidak diinginkan memerlukan biaya. Komputer pengirim harus melakukan pekerjaan komputasi sebelum mengirim pesan. Gagasan ini menunjukkan bagaimana biaya komputasi dapat menghambat penyalahgunaan.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) menjabarkan usulan sistem yang memungkinkan pekerjaan komputasi menghasilkan catatan digital yang langka. Sistem ini tidak diluncurkan sebagai sistem uang terdesentralisasi yang lengkap, tetapi mengembangkan gagasan penting tentang [kelangkaan digital](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) dan pembuktian.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) dan [**bukti kerja yang dapat digunakan kembali (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) mengeksplorasi berbagai cara bagi peserta untuk menciptakan atau mentransfer [nilai digital yang langka](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) tanpa hanya bergantung pada satu basis data pusat. Keduanya belum lengkap, tetapi membantu memperjelas apa saja yang dibutuhkan agar suatu sistem dapat berfungsi.
* Meskipun [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) bukan uang, sistem ini menunjukkan bahwa [jaringan antarrekan](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) dapat memungkinkan banyak komputer independen berbagi informasi tanpa satu server pusat yang mengendalikan seluruh sistem.

Secara keseluruhan, eksperimen-eksperimen ini menunjukkan bagian-bagian berguna dari teka-teki tersebut. Eksperimen ini juga memperjelas masalah yang masih tersisa.


<!-- card: definition -->
> **Definition – Pembelanjaan ganda**
>
> [Pembelanjaan ganda](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) adalah upaya mengirim unit digital yang sama kepada dua penerima. Data digital dapat disalin secara sempurna, sehingga sistem uang digital memerlukan cara untuk menentukan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mana yang sah.


[Sistem terpusat](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) mencegah hal ini dengan membiarkan satu basis data tepercaya menentukan pembayaran mana yang lebih dahulu dilakukan. Pada 31 Oktober 2008, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto) dalam makalah putihnya, [_Bitcoin: Sistem Uang Tunai Elektronik Antarrekan_](https://bitcoin.org/bitcoin.pdf), menjelaskan pendekatan yang berbeda: sistem publik yang dapat menetapkan riwayat pembayaran bersama tanpa bank, perusahaan, atau otoritas pusat lainnya.

Makalah putih tersebut menyatukan fitur-fitur yang diperlukan untuk pendekatan itu:

1. **Sebuah [jaringan antarrekan](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) diumumkan secara langsung kepada jaringan peserta.
1. **[Tanda tangan digital](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** sebuah [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) adalah informasi rahasia yang menghasilkan tanda tangan untuk mengesahkan pembelanjaan; hanya pemegangnya yang dapat melakukan hal ini.
1. **Blok dan [penambangan](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [penambang](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mengumpulkan [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ke dalam blok dan menggunakan [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) untuk bersaing menambahkan blok berikutnya.
1. **Independensi [verifikasi](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) memeriksa [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dan blok berdasarkan aturan Bitcoin.
1. **Riwayat bersama dengan akumulasi [bukti kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** peserta mengakui [rantai yang valid](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) dari [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dengan paling banyak [akumulasi kerja](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) sebagai catatan bersama.


<!-- micrographic: five-part-response-01 -->
[Lima bagian berpadu untuk mengatasi masalah pembelanjaan ganda: jaringan antarrekan, tanda tangan digital, blok dan penambangan, verifikasi independen, serta riwayat bersama dengan akumulasi bukti kerja terbanyak. Bersama-sama, kelimanya memungkinkan jaringan menolak pembelanjaan kedua atas dana yang sama tanpa otoritas pusat.](/micrographics/five-part-response-01/id.md)


Modul ini menjelaskan konsep-konsep tersebut secara lebih terperinci. Secara bersama-sama, konsep-konsep ini memberikan jawaban praktis untuk [masalah pembelanjaan ganda](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): jaringan dapat menolak upaya kedua untuk membelanjakan bitcoin yang sama tanpa bergantung pada otoritas pusat. Bitcoin menawarkan kombinasi yang selama ini belum ditemukan dan telah dicari melalui eksperimen uang digital selama puluhan tahun.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
