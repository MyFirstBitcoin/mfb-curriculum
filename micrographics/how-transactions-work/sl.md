# How Transations Work

## Alt text

Navpični prikaz v sedmih korakih, ki ponazarja plačilo z bitcoini, pri katerem Alice pošilja, Bob pa prejema: ustvarjanje in podpisovanje transakcije, posredovanje v omrežje, preverjanje v vozliščih, čakalnica mempool, vključitev v blok z rudarjenjem ter dodajanje bloka v verigo blokov, medtem ko se potrditve kopičijo.

## Texts

### s1-label

Alice ustvari transakcijo

### s1-desc

Določi, kdo prejme kovance, koliko jih prejme in kolikšna je provizija za rudarje.

### r-to

Za

### r-to-v

Naslov prejemnika (Bob)

### r-amount

Znesek

### r-fee

Omrežna provizija

### s2-label

Podpiše jo s svojim zasebnim ključem

### s2-desc

Digitalni podpis dokazuje, da so kovanci njeni in jih lahko porabi.

### s3-label

Posredovanje v omrežje

### s3-desc

Podpisana transakcija se pošlje vozliščem, ki preverijo, ali je skladna s pravili.

### chip-sig

Veljaven podpis

### chip-bal

Dovolj bitcoinov

### chip-rules

Skladnost s pravili

### s4-label

Čaka v čakalnici mempool

### s4-desc

Veljavne transakcije čakajo v zbirki čakajočih plačil.

### s5-label

Rudarji jo vključijo v blok

### s5-desc

Rudarji izbirajo transakcije in tekmujejo, kdo bo izrudaril blok.

### s6-label

Blok se pridruži verigi blokov

### s6-desc

Druga vozlišča preverijo blok in ga nato trajno dodajo v verigo.

### s7-label

Bob prejme bitcoine

### s7-desc

Transakcija je zdaj potrjena. Alice teh kovancev ne more več porabiti, Bob pa lahko porabi prejete kovance.

### foot

<strong>Vsak nov blok utrdi transakcijo.</strong> Z vsakim blokom, dodanim za njo, postane njena razveljavitev eksponentno težja &#8212; prav to zagotavlja dokončnost plačil z bitcoinom.
