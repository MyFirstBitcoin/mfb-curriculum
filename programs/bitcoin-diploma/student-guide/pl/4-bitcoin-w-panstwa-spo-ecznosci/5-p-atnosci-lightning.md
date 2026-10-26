# 4.5 Płatności Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->



<!-- micrographic: lightning-payment-sequence-01 -->


Lightning umożliwia praktyczne wykorzystanie szybkich, drobnych płatności w sieci Bitcoin. Może sprawdzić się przy kasie w sklepie, przy regularnych płatnościach lokalnych, w usługach internetowych lub przy przelewach, w których opłata za transakcję on-chain byłaby zbyt wysoka w stosunku do kwoty płatności.

Lokalny pokaz działania Lightning powinien wyjaśniać:

* czy portfel jest powierniczy, czy niepowierniczy
* jak zasila się portfel
* czy zasilenie wymaga przeprowadzenia [transakcji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) on-chain lub skorzystania z usługi
* jaka kopia zapasowa lub metoda odzyskiwania chroni zgromadzone środki
* jaki rodzaj żądania płatności jest używany
* jakie opłaty lub limity obowiązują
* co się dzieje, gdy płatność się nie powiedzie
* jak odbiorca potwierdza otrzymanie płatności

Taka [**faktura Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) to żądanie płatności utworzone dla konkretnej płatności. Może zawierać kwotę, informacje o odbiorcy i termin ważności. Proszę zapoznać się z ekranem [potwierdzenia](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) w portfelu przed dokonaniem płatności.

Taki [**adres Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) to czytelny dla człowieka identyfikator obsługiwany przez niektóre usługi. Może wyglądać jak adres e-mail, ale jest ułatwieniem służącym do kierowania płatności, a nie kontem poczty elektronicznej. Jego działanie zależy od dostawcy lub domeny, która go obsługuje.

Przy płatności wykonywanej pod kierunkiem prowadzącego:

1. Odbiorca tworzy właściwe żądanie płatności.
1. Nadawca skanuje je lub kopiuje.
1. Nadawca sprawdza odbiorcę, kwotę, jednostkę i opłatę.
1. Nadawca zatwierdza płatność dopiero po upewnieniu się, że szczegóły są poprawne.
1. Obie strony potwierdzają wynik we własnych portfelach.
1. Grupa wyjaśnia ryzyko związane z [przechowywaniem środków](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) i niepowodzeniem płatności.

Proszę nie zakładać, że udana płatność Lightning dowodzi, iż portfel jest bezpieczny do przechowywania większych kwot. Wygoda płatności i bezpieczeństwo [przechowywania środków](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) to odrębne kwestie.
