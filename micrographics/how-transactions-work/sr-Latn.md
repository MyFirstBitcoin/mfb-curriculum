# How Transations Work

## Alt text

Vertikalni prikaz plaćanja bitcoinom od Alice do Bob u sedam koraka: kreiranje i potpisivanje transakcije, njeno slanje mreži, provera koju obavljaju čvorovi, mempul, rudarenje kojim se transakcija uključuje u blok i dodavanje bloka u lanac blokova dok se potvrde prikupljaju.

## Texts

### s1-label

Alice kreira transakciju

### s1-desc

Ona navodi ko prima novčiće, koliko i kolika je naknada za rudare.

### r-to

Za

### r-to-v

Adresa koju koristi Bob

### r-amount

Iznos

### r-fee

Mrežna naknada

### s2-label

Potpisuje je svojim privatnim ključem

### s2-desc

Digitalni potpis dokazuje da ona ima pravo da potroši te novčiće.

### s3-label

Slanje mreži

### s3-desc

Potpisana transakcija šalje se čvorovima, koji proveravaju da li je u skladu s pravilima.

### chip-sig

Važeći potpis

### chip-bal

Dovoljno bitcoina

### chip-rules

U skladu s pravilima

### s4-label

Čeka u mempulu

### s4-desc

Važeće transakcije čekaju u skupu plaćanja na čekanju.

### s5-label

Rudari je uključuju u blok

### s5-desc

Rudari biraju transakcije i takmiče se ko će izrudariti blok.

### s6-label

Blok se pridružuje lancu blokova

### s6-desc

Ostali čvorovi proveravaju blok, a zatim ga trajno dodaju u lanac.

### s7-label

Bob prima bitcoin

### s7-desc

Transakcija je sada potvrđena. Alice ne može ponovo da potroši te novčiće, a Bob može da potroši ono što je primio.

### foot

<strong>Svaki novi blok dodatno učvršćuje transakciju.</strong> Sa svakim blokom dodatim iznad nje, njeno poništavanje postaje eksponencijalno teže &#8212; upravo to bitcoinu daje konačnost.
