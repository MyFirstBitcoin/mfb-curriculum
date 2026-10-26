# How Transations Work

## Alt text

Ein vertikaler Ablauf in sieben Schritten, der eine bitcoin-Zahlung von Alice an Bob zeigt: Erstellen und Signieren einer Transaktion, ihre Übertragung, die Überprüfung durch Nodes, der Mempool, das Minen in einen Block und das Hinzufügen des Blocks zur Blockchain, während sich die Bestätigungen ansammeln.

## Texts

### s1-label

Alice erstellt eine Transaktion

### s1-desc

Sie legt fest, wer die Coins erhält, wie viel und welche Gebühr an die Miner geht.

### r-to

An

### r-to-v

Bobs Adresse

### r-amount

Betrag

### r-fee

Netzwerkgebühr

### s2-label

Sie signiert sie mit ihrem privaten Schlüssel

### s2-desc

Die digitale Signatur beweist, dass sie über die Coins verfügen darf.

### s3-label

Übertragung an das Netzwerk

### s3-desc

Die signierte Transaktion wird an Nodes gesendet, die prüfen, ob sie den Regeln entspricht.

### chip-sig

Gültige Signatur

### chip-bal

Genug bitcoin

### chip-rules

Entspricht den Regeln

### s4-label

Sie wartet im Mempool

### s4-desc

Gültige Transaktionen warten in einem Pool ausstehender Zahlungen.

### s5-label

Miner nehmen sie in einen Block auf

### s5-desc

Miner wählen Transaktionen aus und konkurrieren darum, einen Block zu minen.

### s6-label

Der Block wird Teil der Blockchain

### s6-desc

Andere Nodes überprüfen den Block und hängen ihn dann dauerhaft an die Kette an.

### s7-label

Bob erhält die bitcoin

### s7-desc

Die Transaktion ist nun bestätigt. Alice kann diese Coins nicht noch einmal ausgeben, und Bob kann ausgeben, was er erhalten hat.

### foot

<strong>Jeder neue Block verankert die Transaktion tiefer.</strong> Mit jedem weiteren Block, der darauf folgt, wird es exponentiell schwieriger, sie rückgängig zu machen &#8211; genau das macht Zahlungen in bitcoin endgültig.
