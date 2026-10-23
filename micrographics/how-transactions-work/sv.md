# How Transations Work

## Alt text

Ett vertikalt flöde i sju steg som visar en bitcoinbetalning från Alice till Bob: en transaktion skapas och signeras, sänds ut, verifieras av noder, väntar i mempoolen och tas med i ett block genom utvinning, varefter blocket läggs till i blockkedjan och bekräftelserna blir allt fler.

## Texts

### s1-label

Alice skapar en transaktion

### s1-desc

Hon anger vem som ska få mynten, hur mycket och en avgift till utvinnarna.

### r-to

Till

### r-to-v

Bobs adress

### r-amount

Belopp

### r-fee

Nätverksavgift

### s2-label

Hon signerar den med sin privata nyckel

### s2-desc

Den digitala signaturen bevisar att hon har rätt att spendera mynten.

### s3-label

Transaktionen sänds ut till nätverket

### s3-desc

Den signerade transaktionen skickas till noder som kontrollerar att den följer reglerna.

### chip-sig

Giltig signatur

### chip-bal

Tillräckligt med bitcoin

### chip-rules

Följer reglerna

### s4-label

Den väntar i mempoolen

### s4-desc

Giltiga transaktioner väntar i en samling av väntande betalningar.

### s5-label

Utvinnare tar med den i ett block

### s5-desc

Utvinnare väljer transaktioner och tävlar om att utvinna ett block.

### s6-label

Blocket läggs till i blockkedjan

### s6-desc

Andra noder verifierar blocket och fogar sedan in det permanent i kedjan.

### s7-label

Bob får bitcoinen

### s7-desc

Transaktionen är nu bekräftad. Alice kan inte spendera samma mynt igen, och Bob kan spendera det han har fått.

### foot

<strong>Varje nytt block förankrar transaktionen djupare.</strong> För varje block som läggs ovanpå blir det exponentiellt svårare att återkalla den &#8212; det är det som gör bitcoinbetalningar slutgiltiga.
