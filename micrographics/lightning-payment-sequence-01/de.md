# BD-V-059-01 Lightning payment sequence

## Alt text

Eine Lightning-Zahlung in sechs Schritten: Der Empfänger erstellt eine Anfrage, der Absender scannt sie, prüft Empfänger, Betrag, Einheit, Ablaufzeit und Gebühr und bestätigt sie, die Zahlung wird weitergeleitet, und beide Wallets zeigen das Ergebnis an. Jede Wallet kann verwahrt oder selbstverwahrt sein, und eine fehlgeschlagene oder abgelaufene Zahlung beginnt mit einer neuen Anfrage von vorn.

## Texts

### boundary

Sie sollten wissen, ob jede Wallet verwahrt (custodial) oder selbstverwahrt (self-custodial) ist.

### s1-title

Anfrage erstellen

### s1-text

Der Empfänger erstellt eine Zahlungsanforderung.

### s2-title

Anfrage scannen

### s2-text

Der Absender scannt oder kopiert sie.

### s3-title

Details prüfen

### s3-text

Prüfen Sie Empfänger, Betrag, Einheit, Ablaufzeit und Gebühr.

### s4-title

Zahlung bestätigen

### s4-text

Der Absender bestätigt sie.

### s5-title

Zahlung weiterleiten

### s5-text

Sie wird über das Lightning-Netzwerk geleitet.

### s6-title

Ergebnis prüfen

### s6-text

Beide Wallets zeigen Erfolg oder Fehlschlag an.

### loop

Fehlgeschlagen oder abgelaufen? Prüfen Sie beide Wallets und erstellen Sie dann eine neue Anfrage.
