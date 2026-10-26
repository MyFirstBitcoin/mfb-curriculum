# How Transations Work

## Alt text

Diagram alur vertikal tujuh langkah yang menunjukkan pembayaran bitcoin dari Alice kepada Bob: pembuatan dan penandatanganan transaksi, penyiaran transaksi, verifikasi oleh simpul, mempool, penambangan transaksi ke dalam blok, dan penambahan blok ke blockchain seiring bertambahnya konfirmasi.

## Texts

### s1-label

Alice membuat transaksi

### s1-desc

Ia menentukan siapa yang menerima koin, berapa jumlahnya, dan biaya untuk penambang.

### r-to

Kepada

### r-to-v

Alamat Bob

### r-amount

Jumlah

### r-fee

Biaya jaringan

### s2-label

Ia menandatanganinya dengan kunci privatnya

### s2-desc

Tanda tangan digital membuktikan bahwa ia berhak membelanjakan koin tersebut.

### s3-label

Disiarkan ke jaringan

### s3-desc

Transaksi yang telah ditandatangani dikirim ke simpul, yang memeriksa apakah transaksi tersebut mengikuti aturan.

### chip-sig

Tanda tangan valid

### chip-bal

Bitcoin mencukupi

### chip-rules

Mengikuti aturan

### s4-label

Transaksi menunggu di mempool

### s4-desc

Transaksi yang valid menunggu dalam kumpulan pembayaran yang belum diproses.

### s5-label

Penambang memasukkannya ke dalam blok

### s5-desc

Penambang memilih transaksi dan bersaing untuk menambang sebuah blok.

### s6-label

Blok ditambahkan ke blockchain

### s6-desc

Simpul lain memverifikasi blok tersebut, lalu menambahkannya ke rantai secara permanen.

### s7-label

Bob menerima bitcoin

### s7-desc

Transaksi kini telah dikonfirmasi. Alice tidak dapat membelanjakan koin tersebut lagi, dan Bob dapat membelanjakan apa yang telah diterimanya.

### foot

<strong>Setiap blok baru memperkuat konfirmasi transaksi.</strong> Dengan setiap blok yang ditambahkan di atasnya, pembatalan transaksi menjadi semakin sulit secara eksponensial &#8212; inilah yang membuat transaksi bitcoin bersifat final.
