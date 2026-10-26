# BD-V-059-01 Lightning payment sequence

## Alt text

En Lightning-betaling i seks trinn: Mottakeren oppretter en forespørsel, avsenderen skanner den, kontrollerer mottaker, beløp, enhet, utløpstidspunkt og gebyr og godkjenner betalingen. Betalingen rutes, og begge lommebøkene viser resultatet. Hver lommebok kan være tredjepartsforvaltet eller selvforvaltet, og ved en mislykket eller utløpt betaling starter prosessen på nytt med en ny forespørsel.

## Texts

### boundary

Vit om hver lommebok er tredjepartsforvaltet eller selvforvaltet.

### s1-title

Opprett forespørselen

### s1-text

Mottakeren oppretter en betalingsforespørsel.

### s2-title

Skann forespørselen

### s2-text

Avsenderen skanner eller kopierer den.

### s3-title

Kontroller opplysningene

### s3-text

Kontroller mottaker, beløp, enhet, utløpstidspunkt og gebyr.

### s4-title

Godkjenn betalingen

### s4-text

Avsenderen godkjenner den.

### s5-title

Rut betalingen

### s5-text

Den sendes gjennom Lightning-nettverket.

### s6-title

Kontroller resultatet

### s6-text

Begge lommebøkene viser om betalingen var vellykket eller mislykket.

### loop

Mislykket eller utløpt? Bekreft statusen i begge lommebøkene, og opprett deretter en ny forespørsel.
