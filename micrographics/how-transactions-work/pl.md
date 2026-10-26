# How Transations Work

## Alt text

Pionowy schemat z siedmioma etapami przedstawiający płatność w bitcoinie od Alice do Bob: utworzenie i podpisanie transakcji, rozgłoszenie jej w sieci, weryfikację przez węzły, mempool, wydobycie bloku zawierającego transakcję oraz dodanie bloku do łańcucha bloków wraz ze wzrostem liczby potwierdzeń.

## Texts

### s1-label

Alice tworzy transakcję

### s1-desc

Określa, kto otrzyma monety, w jakiej ilości oraz jaką opłatę otrzymają górnicy.

### r-to

Do

### r-to-v

Adres odbiorcy: Bob

### r-amount

Kwota

### r-fee

Opłata sieciowa

### s2-label

Podpisuje ją swoim kluczem prywatnym

### s2-desc

Podpis cyfrowy potwierdza, że ma prawo wydać te monety.

### s3-label

Rozgłoszenie w sieci

### s3-desc

Podpisana transakcja trafia do węzłów, które sprawdzają jej zgodność z regułami.

### chip-sig

Prawidłowy podpis

### chip-bal

Wystarczająca ilość bitcoinów

### chip-rules

Zgodność z regułami

### s4-label

Czeka w mempoolu

### s4-desc

Prawidłowe transakcje czekają w puli oczekujących płatności.

### s5-label

Górnicy umieszczają ją w bloku

### s5-desc

Górnicy wybierają transakcje i rywalizują o wydobycie bloku.

### s6-label

Blok dołącza do łańcucha bloków

### s6-desc

Pozostałe węzły weryfikują blok, a następnie na stałe dołączają go do łańcucha.

### s7-label

Bob otrzymuje bitcoiny

### s7-desc

Transakcja jest już potwierdzona. Alice nie może ponownie wydać tych monet, a Bob może wydać otrzymane środki.

### foot

<strong>Każdy nowy blok zwiększa głębokość transakcji w łańcuchu.</strong> Z każdym kolejnym blokiem dodanym nad nią jej cofnięcie staje się wykładniczo trudniejsze &#8212; to właśnie zapewnia nieodwracalność płatności w bitcoinie.
