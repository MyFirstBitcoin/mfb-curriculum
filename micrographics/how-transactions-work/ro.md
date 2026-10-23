# How Transations Work

## Alt text

O diagramă verticală cu șapte etape care prezintă o plată în bitcoin de la Alice către Bob: crearea și semnarea unei tranzacții, difuzarea ei, verificarea de către noduri, mempool-ul, includerea într-un bloc prin minare și adăugarea blocului în blockchain pe măsură ce se acumulează confirmările.

## Texts

### s1-label

Alice creează o tranzacție

### s1-desc

Ea specifică cine primește monedele, ce sumă și ce comision oferă minerilor.

### r-to

Către

### r-to-v

Adresa lui Bob

### r-amount

Sumă

### r-fee

Comision de rețea

### s2-label

Ea o semnează cu cheia sa privată

### s2-desc

Semnătura digitală dovedește că ea are dreptul să cheltuiască monedele.

### s3-label

Difuzarea în rețea

### s3-desc

Tranzacția semnată este trimisă nodurilor, care verifică dacă respectă regulile.

### chip-sig

Semnătură validă

### chip-bal

Suficienți bitcoin

### chip-rules

Respectă regulile

### s4-label

Tranzacția așteaptă în mempool

### s4-desc

Tranzacțiile valide așteaptă într-un spațiu comun pentru plăți în așteptare.

### s5-label

Minerii o includ într-un bloc

### s5-desc

Minerii selectează tranzacții și concurează pentru a mina un bloc.

### s6-label

Blocul este adăugat în blockchain

### s6-desc

Celelalte noduri verifică blocul, apoi îl adaugă definitiv în lanț.

### s7-label

Bob primește monedele bitcoin

### s7-desc

Tranzacția este acum confirmată. Alice nu mai poate cheltui acele monede, iar Bob poate cheltui ceea ce a primit.

### foot

<strong>Fiecare bloc nou consolidează tranzacția.</strong> Cu fiecare bloc adăugat deasupra, anularea ei devine exponențial mai dificilă &#8212; ceea ce face ca tranzacțiile în bitcoin să fie definitive.
