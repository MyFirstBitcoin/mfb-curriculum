# How Transations Work

## Alt text

Aliran menegak tujuh langkah yang menunjukkan pembayaran bitcoin daripada Alice kepada Bob: mencipta dan menandatangani transaksi, menyiarkannya, pengesahan oleh nod, mempool, perlombongan untuk memasukkannya ke dalam blok, dan penambahan blok ke rantaian blok apabila pengesahan terkumpul.

## Texts

### s1-label

Alice mencipta transaksi

### s1-desc

Dia menentukan siapa yang menerima syiling, jumlahnya, dan fi untuk pelombong.

### r-to

Kepada

### r-to-v

Alamat Bob

### r-amount

Jumlah

### r-fee

Fi rangkaian

### s2-label

Dia menandatanganinya dengan kunci peribadinya

### s2-desc

Tandatangan digital membuktikan bahawa syiling itu miliknya untuk dibelanjakan.

### s3-label

Disiarkan ke rangkaian

### s3-desc

Transaksi yang telah ditandatangani dihantar ke nod, yang menyemak bahawa transaksi itu mematuhi peraturan.

### chip-sig

Tandatangan sah

### chip-bal

bitcoin mencukupi

### chip-rules

Mematuhi peraturan

### s4-label

Transaksi menunggu dalam mempool

### s4-desc

Transaksi yang sah menunggu dalam kumpulan pembayaran yang belum diproses.

### s5-label

Pelombong memasukkannya ke dalam blok

### s5-desc

Pelombong memilih transaksi dan bersaing untuk melombong blok.

### s6-label

Blok disambungkan ke rantaian blok

### s6-desc

Nod lain mengesahkan blok itu, kemudian menyambungkannya ke rantaian secara kekal.

### s7-label

Bob menerima bitcoin

### s7-desc

Transaksi kini telah disahkan. Alice tidak boleh membelanjakan syiling itu lagi, dan Bob boleh membelanjakan apa yang diterimanya.

### foot

<strong>Setiap blok baharu mengukuhkan kedudukan transaksi dalam rantaian.</strong> Dengan setiap blok yang ditambahkan di atasnya, pembalikan transaksi menjadi semakin sukar secara eksponen &#8212; itulah yang menjadikan transaksi bitcoin muktamad.
