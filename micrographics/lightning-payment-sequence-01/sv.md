# BD-V-059-01 Lightning payment sequence

## Alt text

En Lightning-betalning i sex steg: mottagaren skapar en betalningsbegäran, avsändaren skannar den, kontrollerar mottagare, belopp, enhet, giltighetstid och avgift och godkänner den, betalningen vidarebefordras och båda plånböckerna visar resultatet. Varje plånbok kan förvaltas av en tredje part eller av innehavaren själv, och om betalningen misslyckas eller giltighetstiden löper ut börjar processen om med en ny betalningsbegäran.

## Texts

### boundary

Ta reda på om varje plånbok förvaltas av en tredje part eller av innehavaren själv.

### s1-title

Skapa betalningsbegäran

### s1-text

Mottagaren skapar en betalningsbegäran.

### s2-title

Skanna betalningsbegäran

### s2-text

Avsändaren skannar eller kopierar den.

### s3-title

Kontrollera uppgifterna

### s3-text

Kontrollera mottagare, belopp, enhet, giltighetstid och avgift.

### s4-title

Godkänn betalningen

### s4-text

Avsändaren godkänner den.

### s5-title

Vidarebefordra betalningen

### s5-text

Den skickas genom Lightning-nätverket.

### s6-title

Kontrollera resultatet

### s6-text

Båda plånböckerna visar om betalningen lyckades eller misslyckades.

### loop

Misslyckades betalningen eller löpte giltighetstiden ut? Kontrollera statusen i båda plånböckerna och skapa sedan en ny betalningsbegäran.
