# 2.10 Dokaz o radu

![](https://cdn.sanity.io/images/vje9ehw2/production/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Dokaz rada**
>
> [Dokaz rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) je proces koji [rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) koriste da se nadmeću za pravo da predlože sledeći blok.


Jedna [heš funkcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) pretvara podatke u rezultat fiksne dužine. Mala promena ulaznih podataka daje nepredvidiv novi rezultat. Jedan [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) menja mali deo podataka u predloženom bloku i iznova izračunava njegov heš. Rezultat je važeći samo kada je njegova brojčana vrednost ispod mrežnog [cilja](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), praga utvrđenog pravilima; niži [cilj](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) znači manje [važećih rezultata](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) i više pokušaja. Ne postoji prečica, pa [rudari](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) možda moraju da naprave mnogo pokušaja.

Kada [rudar](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) pronađe [važeći rezultat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), on [emituje](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blok. [Čvorovi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) mogu brzo da provere dokaz, iako je njegovo pronalaženje zahtevalo znatne računarske resurse i energiju. Ako blok sadrži [transakciju](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), ta [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) dobija svoju [prvu potvrdu](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): zapis o njoj uključen je u jedan važeći blok. Svaki važeći blok dodat posle njega donosi još jednu [potvrdu](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), zbog čega je [transakcijino](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) mesto u [blokčejnu](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) skuplje naknadno izmeniti. Ova razlika je važna: rad je skupo obaviti, a lako proveriti.


<!-- micrographic: proof-of-work-process-01 -->
[Rudar iznova izračunava heš predloženog bloka sve dok jedan rezultat ne bude manji od ciljne vrednosti mreže, a zatim šalje blok mreži. Čvorovi brzo proveravaju dokaz i poštovanje svakog pravila pre nego što blok postane deo lanca blokova: obavljanje rada je skupo, a njegova provera jednostavna.](/micrographics/proof-of-work-process-01/sr-Latn.md)


[Dokaz rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ima više svrha:

* daje nezavisnim [rudarima](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) način da se nadmeću bez centralnog koordinatora
* čini redosled [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) skupim za naknadno menjanje
* povezuje bezbednost mreže sa stvarnom opremom i energijom
* podržava javni metod za izbor između konkurentskih važećih istorija: lanac sa najviše [akumuliranog rada](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Rudarenje](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) ne rešava korisne jednačine za neku spoljašnju svrhu. Njegova svrha je da obezbedi redosled Bitcoin [transakcija](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Mreža periodično prilagođava ciljnu vrednost: kada blokovi pristižu prebrzo, snižava je, a kada pristižu presporo, povećava je, nastojeći da održi prosek od približno jednog bloka na svakih deset minuta uprkos promenama računarske snage.

[Dokaz o radu](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) podrazumeva stvarni energetski trošak. Pristalice tvrde da upravo taj trošak predstavlja temelj bezbednosti Bitcoin mreže i može stvoriti potražnju za fleksibilno dostupnom energijom ili energijom koja bi inače ostala neiskorišćena. Kritičari dovode u pitanje količinu i poreklo utrošene energije. Odgovorna procena razmatra koja se energija koristi, odakle dolazi, kakvu bezbednost obezbeđuje i koje se alternative porede.

![Predavač, polaznik početnik i polaznik sa tehničkim predznanjem razgovaraju o stonom uređaju za rudarenje sa ventilatorom i zasebnim napajanjem.](https://cdn.sanity.io/images/vje9ehw2/production/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
