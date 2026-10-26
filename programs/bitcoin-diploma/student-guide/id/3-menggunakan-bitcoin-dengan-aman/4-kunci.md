# 3.4 Kunci

Kepemilikan Bitcoin ditegakkan melalui kunci kriptografis.


> **Definition – Kunci privat**
>
> Sebuah [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) adalah informasi rahasia yang memungkinkan dompet membuat [tanda tangan digital](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) yang sah. Tanda tangan mengesahkan pembelanjaan bitcoin yang dikendalikan oleh kunci terkait. Siapa pun yang memperoleh [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) biasanya dapat membelanjakan dana tersebut.


Sebuah [**kunci publik**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) diturunkan secara matematis dari [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Kunci ini membantu memverifikasi tanda tangan tanpa mengungkapkan [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Alamat dibuat dengan menggunakan [kunci publik](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) sebagai sumber informasi.

Aturan utamanya sederhana:

**Informasi publik untuk menerima dana boleh dibagikan. Informasi privat untuk membelanjakan dana harus tetap dirahasiakan.**

Sebuah [tanda tangan digital](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) membuktikan bahwa [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) yang diperlukan telah mengesahkan sebuah [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Tanda tangan tersebut tidak menempatkan [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) di dalam [transaksi](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Simpul](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) memverifikasi tanda tangan sebelum menerima pembelanjaan tersebut.

Sebagian besar dompet untuk pemula menggunakan [tanda tangan tunggal](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): satu kunci privat mengesahkan sebuah transaksi. Dompet modern mengelola banyak kunci secara otomatis. Pemula tidak boleh menyalin atau menangani masing-masing [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) dalam bentuk untaian karakter. Lindungi cadangan yang direkomendasikan oleh dompet dan ikuti prosedur pemulihannya.

Tidak ada pendidik, perusahaan dompet, pegawai bursa, petugas dukungan teknis, atau pengembang Bitcoin yang sah yang memerlukan [kunci privat](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) atau [frasa pemulihan](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase) Anda. Siapa pun yang memintanya harus dianggap sebagai ancaman.


> **Light**
>
> **Cobalah:** Pilah contoh-contoh yang telah disiapkan ke dalam tiga kelompok: informasi yang aman dibagikan untuk menerima dana, informasi rahasia untuk membelanjakan dana, dan informasi yang mungkin bersifat publik tetapi tetap harus dijaga kerahasiaannya ketika dikaitkan dengan seseorang.



<!-- micrographic: private-key-public-info-01 -->
