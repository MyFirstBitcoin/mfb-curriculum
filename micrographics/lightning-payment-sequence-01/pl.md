# BD-V-059-01 Lightning payment sequence

## Alt text

Płatność w sieci Lightning w sześciu krokach: odbiorca tworzy żądanie, nadawca je skanuje, sprawdza odbiorcę, kwotę, jednostkę, termin ważności i opłatę, zatwierdza płatność, płatność jest przesyłana przez sieć, a oba portfele pokazują wynik. Każdy portfel może być powierniczy lub niepowierniczy, a jeśli płatność się nie powiedzie lub żądanie wygaśnie, proces rozpoczyna się od nowa, od utworzenia nowego żądania.

## Texts

### boundary

Proszę ustalić, czy każdy z portfeli jest powierniczy czy niepowierniczy.

### s1-title

Proszę utworzyć żądanie

### s1-text

Odbiorca tworzy żądanie płatności.

### s2-title

Proszę zeskanować żądanie

### s2-text

Nadawca skanuje je lub kopiuje.

### s3-title

Proszę zweryfikować szczegóły

### s3-text

Proszę sprawdzić odbiorcę, kwotę, jednostkę, termin ważności i opłatę.

### s4-title

Proszę zatwierdzić płatność

### s4-text

Nadawca zatwierdza płatność.

### s5-title

Proszę przesłać płatność

### s5-text

Płatność jest przesyłana przez sieć Lightning.

### s6-title

Proszę sprawdzić wynik

### s6-text

Oba portfele pokazują powodzenie lub niepowodzenie płatności.

### loop

Płatność nie powiodła się lub żądanie wygasło? Proszę potwierdzić status w obu portfelach, a następnie utworzyć nowe żądanie.
