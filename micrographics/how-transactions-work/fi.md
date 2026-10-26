# How Transations Work

## Alt text

Pystysuuntainen seitsemänvaiheinen kaavio, joka näyttää bitcoin-maksun kulun Alicelta Bobille: siirron luominen ja allekirjoittaminen, sen lähettäminen verkkoon, solmujen tekemä tarkistus, mempool, siirron louhiminen osaksi lohkoa ja lohkon lisääminen lohkoketjuun vahvistusten kertyessä.

## Texts

### s1-label

Alice luo siirron

### s1-desc

Hän määrittää, kuka saa kolikot, kuinka paljon ja mikä on louhijoille maksettava siirtomaksu.

### r-to

Vastaanottaja

### r-to-v

Bobin osoite

### r-amount

Määrä

### r-fee

Verkkomaksu

### s2-label

Hän allekirjoittaa sen yksityisellä avaimellaan

### s2-desc

Digitaalinen allekirjoitus todistaa, että hänellä on oikeus käyttää kolikot.

### s3-label

Siirto lähetetään verkkoon

### s3-desc

Allekirjoitettu siirto lähetetään solmuille, jotka tarkistavat sen noudattavan sääntöjä.

### chip-sig

Kelvollinen allekirjoitus

### chip-bal

Riittävästi bitcoinia

### chip-rules

Noudattaa sääntöjä

### s4-label

Siirto odottaa mempoolissa

### s4-desc

Kelvolliset siirrot odottavat vahvistamattomien maksujen varannossa.

### s5-label

Louhijat sisällyttävät sen lohkoon

### s5-desc

Louhijat valitsevat siirtoja ja kilpailevat lohkon louhimisesta.

### s6-label

Lohko liitetään lohkoketjuun

### s6-desc

Muut solmut tarkistavat lohkon ja liittävät sen sitten pysyvästi ketjuun.

### s7-label

Bob saa bitcoinit

### s7-desc

Siirto on nyt vahvistettu. Alice ei voi käyttää samoja kolikoita uudelleen, ja Bob voi käyttää saamansa kolikot.

### foot

<strong>Jokainen uusi lohko vahvistaa siirtoa.</strong> Jokainen sen päälle lisätty lohko tekee siirron kumoamisesta eksponentiaalisesti vaikeampaa &#8212; juuri tämä tekee bitcoin-maksuista lopullisia.
