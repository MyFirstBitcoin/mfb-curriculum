# BD-V-059-01 Lightning payment sequence

## Alt text

Lightning-fizetés hat lépésben: a fogadó fél kérelmet hoz létre, a küldő fél beolvassa azt, ellenőrzi a címzettet, az összeget, az egységet, a lejáratot és a díjat, majd jóváhagyja a fizetést; a fizetés továbbítódik, és mindkét tárca megjeleníti az eredményt. Mindkét tárca lehet letétkezelői vagy saját kezelésű, sikertelen vagy lejárt fizetés esetén pedig a folyamat új kérelemmel kezdődik elölről.

## Texts

### boundary

Legyen tisztában azzal, hogy az egyes tárcák letétkezelői vagy saját kezelésűek.

### s1-title

Hozza létre a kérelmet

### s1-text

A fogadó fél fizetési kérelmet hoz létre.

### s2-title

Olvassa be a kérelmet

### s2-text

A küldő fél beolvassa vagy kimásolja azt.

### s3-title

Ellenőrizze az adatokat

### s3-text

Ellenőrizze a címzettet, az összeget, az egységet, a lejáratot és a díjat.

### s4-title

Hagyja jóvá a fizetést

### s4-text

A küldő fél jóváhagyja azt.

### s5-title

Irányítsa tovább a fizetést

### s5-text

A fizetés áthalad a Lightning Network hálózatán.

### s6-title

Ellenőrizze az eredményt

### s6-text

Mindkét tárca jelzi a sikert vagy a sikertelenséget.

### loop

Sikertelen vagy lejárt? Ellenőrizze mindkét tárcában, majd hozzon létre új kérelmet.
