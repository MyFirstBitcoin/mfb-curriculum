# BD-V-059-01 Lightning payment sequence

## Alt text

Lightning-maksu kuudessa vaiheessa: vastaanottaja luo maksupyynnön, lähettäjä skannaa sen, tarkistaa vastaanottajan, summan, yksikön, voimassaoloajan ja siirtomaksun sekä hyväksyy maksun, maksu reititetään ja molemmat lompakot näyttävät tuloksen. Kumpikin lompakko voi olla säilytyspalvelun hallinnoima tai itsehallinnoitu, ja epäonnistuneen tai vanhentuneen maksun jälkeen aloitetaan alusta uudella maksupyynnöllä.

## Texts

### boundary

Selvittäkää, onko kukin lompakko säilytyspalvelun hallinnoima vai itsehallinnoitu.

### s1-title

Luokaa maksupyyntö

### s1-text

Vastaanottaja luo maksupyynnön.

### s2-title

Skannatkaa maksupyyntö

### s2-text

Lähettäjä skannaa tai kopioi sen.

### s3-title

Tarkistakaa tiedot

### s3-text

Tarkistakaa vastaanottaja, summa, yksikkö, voimassaoloaika ja siirtomaksu.

### s4-title

Hyväksykää maksu

### s4-text

Lähettäjä hyväksyy maksun.

### s5-title

Reitittäkää maksu

### s5-text

Maksu kulkee Lightning-verkon kautta.

### s6-title

Tarkistakaa tulos

### s6-text

Molemmat lompakot näyttävät, onnistuiko vai epäonnistuiko maksu.

### loop

Epäonnistuiko tai vanheniko maksu? Varmistakaa tila molemmista lompakoista ja luokaa sitten uusi maksupyyntö.
