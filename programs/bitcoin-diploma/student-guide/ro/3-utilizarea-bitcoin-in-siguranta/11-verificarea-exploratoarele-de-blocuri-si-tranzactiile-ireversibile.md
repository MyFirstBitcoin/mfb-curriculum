# 3.11 Verificarea, exploratoarele de blocuri și tranzacțiile ireversibile

> **Definition – ID Tranzacție și Explorator de Blocuri**
>
> Un [ID Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identifică o [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) înregistrată pe blockchain. Un [Explorator de Blocuri](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) afișează date publice Bitcoin, cum ar fi starea unei [Tranzacții](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) și numărul de [Confirmări](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Este un instrument util de vizualizare, nu o autoritate asupra Bitcoin și nici o dovadă a identității sau a onestității destinatarului.


Ce pot arăta aceste informații publice și ce nu pot arăta? Pot arăta starea unei [Tranzacții](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), destinația, suma, comisionul și numărul de [Confirmări](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation); nu pot dovedi de ce a avut loc o plată sau dacă o persoană este de încredere. O [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) pe blockchain este neconfirmată după ce este [difuzată](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) și primește [prima Confirmare](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) când este inclusă într-un bloc valid. Blocurile ulterioare sporesc încrederea în locul său în registru, dar nu remediază o destinație greșită sau o înșelătorie. Nu există un număr universal de [Confirmări](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) pentru toate plățile; verificarea adecvată depinde de sumă și de risc.

Pentru a examina o [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) pregătită în prealabil, obțineți [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)-ul acesteia, deschideți un explorator de încredere pentru [rețeaua Bitcoin](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network) vizată și verificați starea, destinația, suma, comisionul și [Confirmările](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Un explorator este doar o interfață. Căutarea unei adrese sau a unui [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) poate dezvălui operatorului său că dispozitivul dumneavoastră este interesat de acele informații. Pentru exerciții, folosiți o [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) pregătită de un cadru didactic sau o captură de ecran tipărită. Nu căutați adresa personală sau o [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) personală a unui cursant pe un serviciu public. Dacă ulterior cercetați o plată personală, informați-vă despre [confidențialitate](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) și securitate [și despre compromisurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) pe care le implică conexiunea dumneavoastră înainte de a folosi un serviciu public.


> **Callout – Datele publice nu sunt o dovadă a identității sau a onestității**
>
> Un [Explorator de Blocuri](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) poate afișa date publice despre o [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), dar nu poate dovedi cine controlează o adresă, de ce a avut loc o plată sau dacă un destinatar este de încredere. Folosiți exemple pregătite în prealabil pentru exerciții și protejați-vă [confidențialitatea](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) atunci când efectuați căutări pe servicii publice.



<!-- micrographic: confirmation-timeline-01 -->


![Cadrul didactic și cursantul mai în vârstă discută un exemplu pregătit în prealabil, afișat pe un monitor orientat spre grup, în timp ce cursantul cu competențe tehnice manevrează mouse-ul; privitorul vede carcasa din spate a monitorului.](https://cdn.sanity.io/images/vje9ehw2/staging/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
