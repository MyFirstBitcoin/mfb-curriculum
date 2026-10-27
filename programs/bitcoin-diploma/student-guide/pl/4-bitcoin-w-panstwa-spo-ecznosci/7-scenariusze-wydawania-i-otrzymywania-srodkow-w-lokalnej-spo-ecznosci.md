# 4.7 Scenariusze wydawania i otrzymywania środków w lokalnej społeczności

![](https://cdn.sanity.io/images/vje9ehw2/staging/fa265ee4b78004e155781ac30066875cd39cc983-1536x1024.svg)


<!-- micrographic: coffee-shop-payment-01 -->
[Płatność w kawiarni w czterech krokach: klient składa zamówienie, kelner wysyła rachunek, klient płaci w bitcoinach za pomocą telefonu, a kelner podaje kawę.](/micrographics/coffee-shop-payment-01/pl.md)


Proszę wykorzystywać lokalnie znane towary i usługi. Konkretny produkt nie ma znaczenia; liczy się sposób rozumowania dotyczący płatności.

###### Scenariusz 1: Drobny zakup

Klient chce kupić przedmiot codziennego użytku. Sprzedawca przyjmuje płatności przez Lightning oraz w sieci Bitcoin bezpośrednio w łańcuchu bloków.

* Która metoda będzie prawdopodobnie odpowiednia dla drobnej, natychmiastowej płatności?
* Kto tworzy żądanie płatności?
* Jak klient sprawdza kwotę i jednostkę?
* Skąd sprzedawca wie, że płatność się powiodła?
* Co się dzieje, jeśli portfel klienta pokazuje „wysłano”, ale sprzedawca nie widzi statusu „otrzymano”?

###### Scenariusz 2: Zapłata za pracę

Pracownik zgadza się otrzymać część wynagrodzenia w bitcoinach.

* Czy [cena](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) jest ustalona w lokalnej [walucie](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency), bitcoinach czy [satoshi](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi)?
* W którym momencie [kurs wymiany](https://curriculum.myfirstbitcoin.org/lexicon/en/#exchange-rate) jest ustalany?
* Kto pokrywa ewentualne opłaty?
* Czy odbiorca korzysta z [samodzielnego przechowywania środków](https://curriculum.myfirstbitcoin.org/lexicon/en/#self-custody)?
* Jaka dokumentacja dochodowa lub podatkowa jest wymagana?
* Czy pracownik potrafi bezpiecznie zarządzać tą kwotą?

###### Scenariusz 3: Przelew między członkami rodziny

Jedna osoba chce przesłać [środki](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) członkowi rodziny w innym miejscu.

* Jakie koszty i opóźnienia wiążą się z obecnie stosowaną metodą?
* W jaki sposób każda z osób pozyska lub wykorzysta bitcoiny?
* Czy odbiorca chce otrzymać bitcoiny czy lokalną [walutę](https://curriculum.myfirstbitcoin.org/lexicon/en/#currency)?
* Jakie zagrożenia związane z wymianą i [przechowywaniem środków](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) występują na każdym etapie?
* Czy cały proces pozwala zaoszczędzić czas lub pieniądze po uwzględnieniu wszystkich opłat?

###### Scenariusz 4: Zwrot środków

Sprzedawca musi zwrócić [środki](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) po [płatności w łańcuchu bloków](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment).

* Dlaczego sprzedawca powinien poprosić o nowy adres do zwrotu środków?
* Jak sprzedawca może sprawdzić, czy żądanie rzeczywiście pochodzi od klienta?
* Kto pokrywa [opłatę za transakcję zwrotu](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee)?
* Jakie potwierdzenie powinny zachować obie strony?

###### Scenariusz 5: Darowizna na rzecz lokalnej społeczności

Lokalna organizacja chce otrzymywać wsparcie w bitcoinach.

* Jak darczyńcy zweryfikują autentyczność żądania płatności?
* Kto kontroluje portfel odbierający środki i jego kopię zapasową?
* Czy darowizny będą przyjmowane on-chain, przez sieć Lightning, czy na oba sposoby?
* Jakie informacje powinny być publiczne dla zapewnienia przejrzystości, a jakie powinny pozostać poufne dla bezpieczeństwa darczyńców?
* Jaka dokumentacja jest potrzebna, aby spełnić lokalne wymogi księgowe, podatkowe lub sprawozdawcze?

W ramach ćwiczenia praktycznego proszę użyć przedmiotu o niewielkiej wartości lub przeprowadzić symulację. Osoba ucząca się powinna umieć wyjaśnić cały przebieg transakcji przed zatwierdzeniem płatności.
