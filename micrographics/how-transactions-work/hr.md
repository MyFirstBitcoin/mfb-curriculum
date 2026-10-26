# How Transations Work

## Alt text

Okomiti prikaz plaćanja bitcoinom u sedam koraka u kojem Alice šalje bitcoin, a Bob ga prima: stvaranje i potpisivanje transakcije, njezino slanje mreži, provjera na čvorovima, mempool, uključivanje u blok rudarenjem i dodavanje bloka u lanac blokova uz prikupljanje potvrda.

## Texts

### s1-label

Alice stvara transakciju

### s1-desc

Određuje tko prima novčiće, koji iznos i kolika je naknada za rudare.

### r-to

Primatelj

### r-to-v

Adresa koju koristi Bob

### r-amount

Iznos

### r-fee

Mrežna naknada

### s2-label

Potpisuje je svojim privatnim ključem

### s2-desc

Digitalni potpis dokazuje da ima pravo potrošiti te novčiće.

### s3-label

Slanje mreži

### s3-desc

Potpisana transakcija šalje se čvorovima, koji provjeravaju je li u skladu s pravilima.

### chip-sig

Valjan potpis

### chip-bal

Dovoljno bitcoina

### chip-rules

U skladu s pravilima

### s4-label

Čeka u mempoolu

### s4-desc

Valjane transakcije čekaju u skupu plaćanja na čekanju.

### s5-label

Rudari je uključuju u blok

### s5-desc

Rudari odabiru transakcije i natječu se u rudarenju bloka.

### s6-label

Blok se pridružuje lancu blokova

### s6-desc

Ostali čvorovi provjeravaju blok, a zatim ga trajno dodaju u lanac.

### s7-label

Bob prima bitcoin

### s7-desc

Transakcija je sada potvrđena. Alice ne može ponovno potrošiti te novčiće, a Bob može potrošiti ono što je primio.

### foot

<strong>Svaki novi blok dodatno učvršćuje transakciju.</strong> Sa svakim blokom dodanim nakon nje, njezino poništavanje postaje eksponencijalno teže &#8212; upravo to osigurava konačnost bitcoina.
