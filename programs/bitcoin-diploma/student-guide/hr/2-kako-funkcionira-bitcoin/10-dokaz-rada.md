# 2.10 Dokaz rada

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Dokaz rada**
>
> [Dokaz rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) je postupak kojim se [rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) služe kako bi se natjecali za pravo predlaganja sljedećeg bloka.


Jedna [funkcija sažimanja](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) pretvara podatke u rezultat fiksne duljine. Mala promjena ulaznih podataka daje nepredvidiv novi rezultat. Jedan [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) mijenja mali dio podataka u predloženom bloku i opetovano ga sažima. Rezultat je valjan samo kada je njegov broj ispod mrežne [ciljne vrijednosti](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), praga utvrđenog pravilima; niža [ciljna vrijednost](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) znači manje [valjanih rezultata](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) i više pokušaja. Nema prečaca, pa [rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) možda moraju pokušati mnogo puta.

Kada [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pronađe [valjan rezultat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), on [šalje](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok cijeloj mreži. [Čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) mogu brzo provjeriti dokaz, iako je njegovo pronalaženje zahtijevalo znatne računalne resurse i energiju. Ako blok uključuje [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), ta [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dobiva svoju [prvu potvrdu](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): njezin je zapis uključen u jedan valjan blok. Svaki valjan blok dodan nakon njega dodaje još jednu [potvrdu](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), čime [transakciji](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mjesto u [lancu blokova](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) postaje skuplje mijenjati. Ta je razlika važna: rad je skupo obaviti, a lako provjeriti.


<!-- micrographic: proof-of-work-process-01 -->
[Rudar iznova izračunava sažetak predloženog bloka sve dok jedan rezultat ne bude manji od ciljne vrijednosti mreže, a zatim objavljuje blok mreži. Čvorovi brzo provjeravaju dokaz i poštovanje svakog pravila prije nego što se blok pridruži lancu blokova: rad je skupo obaviti, a lako provjeriti.](/micrographics/proof-of-work-process-01/hr.md)


[Dokaz rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) služi u nekoliko svrha:

* neovisnim [rudarima](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) omogućuje natjecanje bez središnjeg koordinatora
* čini redoslijed [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) skupim za naknadno mijenjanje
* povezuje sigurnost mreže s fizičkom opremom i energijom
* podržava javnu metodu odabira između konkurentskih valjanih povijesti: lanac s najviše [akumuliranog rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Rudarenje](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ne rješava korisne jednadžbe za neku vanjsku svrhu. Njegova je svrha osigurati redoslijed Bitcoin [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Mreža povremeno prilagođava ciljnu vrijednost: kada blokovi pristižu prebrzo, snižava je, a kada pristižu presporo, povisuje je, nastojeći održati prosjek od otprilike jednog bloka svakih deset minuta unatoč promjenama računalne snage.

[Dokaz rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) podrazumijeva stvarni energetski trošak. Zagovornici tvrde da upravo taj trošak čini temelj sigurnosti Bitcoina i može stvoriti potražnju za energijom čija se potrošnja može fleksibilno prilagođavati ili koja bi inače ostala neiskorištena. Kritičari preispituju količinu i izvor utrošene energije. Odgovorna procjena razmatra koja se energija koristi, odakle dolazi, kakvu sigurnost pruža i koje se alternative uspoređuju.

![Nastavnik, polaznik početnik i tehnički potkovan polaznik razgovaraju o stolnom uređaju za rudarenje s ventilatorom i zasebnim napajanjem.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
