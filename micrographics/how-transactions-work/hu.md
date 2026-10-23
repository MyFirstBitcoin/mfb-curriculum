# How Transations Work

## Alt text

Függőleges, hétlépéses folyamatábra egy Alice-től Bobnak küldött bitcoinfizetésről: a tranzakció létrehozása és aláírása, továbbítása a hálózatnak, a csomópontok általi ellenőrzés, a mempool, a blokkba bányászás, majd a blokk hozzáadása a blokklánchoz, miközben gyűlnek a megerősítések.

## Texts

### s1-label

Alice létrehoz egy tranzakciót

### s1-desc

Megadja, ki kapja meg az érméket, mekkora összeget kap, és mennyi díjat fizet a bányászoknak.

### r-to

Címzett

### r-to-v

Bob címe

### r-amount

Összeg

### r-fee

Hálózati díj

### s2-label

Aláírja a privát kulcsával

### s2-desc

A digitális aláírás igazolja, hogy jogosult elkölteni az érméket.

### s3-label

Továbbítás a hálózatnak

### s3-desc

Az aláírt tranzakció eljut a csomópontokhoz, amelyek ellenőrzik, hogy megfelel-e a szabályoknak.

### chip-sig

Érvényes aláírás

### chip-bal

Elegendő bitcoin

### chip-rules

Megfelel a szabályoknak

### s4-label

A mempoolban várakozik

### s4-desc

Az érvényes tranzakciók a függőben lévő fizetések gyűjtőhelyén várakoznak.

### s5-label

A bányászok beillesztik egy blokkba

### s5-desc

A bányászok tranzakciókat választanak ki, és versenyeznek egy blokk kibányászásáért.

### s6-label

A blokk a blokklánchoz kapcsolódik

### s6-desc

A többi csomópont ellenőrzi a blokkot, majd véglegesen a lánchoz kapcsolja.

### s7-label

Bob megkapja a bitcoint

### s7-desc

A tranzakció immár megerősítést kapott. Alice nem költheti el újra ezeket az érméket, Bob pedig elköltheti a kapott összeget.

### foot

<strong>Minden új blokk mélyebbre helyezi a tranzakciót a blokkláncban.</strong> Minden fölé kerülő blokkal exponenciálisan nehezebbé válik a visszafordítása &#8212; ez teszi véglegessé a bitcoint.
