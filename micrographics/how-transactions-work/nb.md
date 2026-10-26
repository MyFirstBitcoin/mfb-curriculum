# How Transations Work

## Alt text

En vertikal flyt i sju trinn som viser en bitcoin-betaling fra Alice til Bob: oppretting og signering av en transaksjon, kringkasting av den, verifisering hos nodene, mempoolen, innlemming i en blokk gjennom utvinning og til slutt at blokken legges til i blokkjeden mens bekreftelsene blir flere.

## Texts

### s1-label

Alice oppretter en transaksjon

### s1-desc

Hun angir hvem som skal motta myntene, hvor mye og et gebyr til utvinnerne.

### r-to

Til

### r-to-v

Bobs adresse

### r-amount

Beløp

### r-fee

Nettverksgebyr

### s2-label

Hun signerer den med sin private nøkkel

### s2-desc

Den digitale signaturen beviser at hun har rett til å bruke myntene.

### s3-label

Den kringkastes til nettverket

### s3-desc

Den signerte transaksjonen sendes til noder, som kontrollerer at den følger reglene.

### chip-sig

Gyldig signatur

### chip-bal

Nok bitcoin

### chip-rules

Følger reglene

### s4-label

Den venter i mempoolen

### s4-desc

Gyldige transaksjoner venter i en samling av ubehandlede betalinger.

### s5-label

Utvinnere tar den med i en blokk

### s5-desc

Utvinnere velger transaksjoner og konkurrerer om å utvinne en blokk.

### s6-label

Blokken legges til i blokkjeden

### s6-desc

Andre noder verifiserer blokken og knytter den deretter permanent til kjeden.

### s7-label

Bob mottar bitcoinene

### s7-desc

Transaksjonen er nå bekreftet. Alice kan ikke bruke disse myntene igjen, og Bob kan bruke det han har mottatt.

### foot

<strong>Hver ny blokk forankrer transaksjonen dypere.</strong> For hver blokk som legges til oppå, blir det eksponentielt vanskeligere å reversere den &#8212; det er dette som gjør bitcoin-betalinger endelige.
