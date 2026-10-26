# BD-V-059-01 Lightning payment sequence

## Alt text

Lightning plaćanje u šest koraka: primalac kreira zahtev, pošiljalac ga skenira, proverava primaoca, iznos, jedinicu, rok važenja i naknadu, odobrava plaćanje, plaćanje se usmerava kroz mrežu, a oba novčanika prikazuju rezultat. Svaki novčanik može biti kastodijalni ili samokastodijalni, a ako plaćanje ne uspe ili zahtev istekne, postupak počinje ponovo s novim zahtevom.

## Texts

### boundary

Proverite da li je svaki novčanik kastodijalni ili samokastodijalni.

### s1-title

Kreirajte zahtev

### s1-text

Primalac kreira zahtev za plaćanje.

### s2-title

Skenirajte zahtev

### s2-text

Pošiljalac ga skenira ili kopira.

### s3-title

Proverite detalje

### s3-text

Proverite primaoca, iznos, jedinicu, rok važenja i naknadu.

### s4-title

Odobrite plaćanje

### s4-text

Pošiljalac odobrava plaćanje.

### s5-title

Usmerite plaćanje

### s5-text

Plaćanje prolazi kroz Lightning mrežu.

### s6-title

Proverite rezultat

### s6-text

Oba novčanika prikazuju uspeh ili neuspeh.

### loop

Plaćanje nije uspelo ili je zahtev istekao? Proverite status u oba novčanika, pa kreirajte novi zahtev.
