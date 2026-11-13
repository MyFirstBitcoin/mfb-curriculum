# 2.10 Prova di lavoro

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


<!-- card: definition -->
> **Definition – Proof of Work (PoW)**
>
> [La Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) è il processo che i [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) utilizzano per competere per il diritto di proporre il blocco successivo.


Una [Hash Function](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) trasforma dei dati in un risultato di lunghezza fissa. Una piccola modifica all'input produce un nuovo risultato imprevedibile. Un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) modifica una piccola porzione di dati in un blocco proposto e ne calcola ripetutamente l'hash. Un risultato è valido solo quando il suo numero è inferiore al [target](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) della rete, una soglia stabilita dalle regole; un [target](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) più basso significa meno [risultati validi](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) e più tentativi. Non esistono scorciatoie, quindi i [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) possono dover effettuare molti tentativi.

Quando un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) trova un [risultato valido](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), [diffonde](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) il blocco. I [nodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) possono verificare la prova rapidamente, anche se trovarla ha richiesto una notevole quantità di calcolo e di energia. Se il blocco include una [transazione](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), quella [transazione](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) riceve la sua [prima conferma](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): la sua registrazione è stata inclusa in un blocco valido. Ogni blocco valido aggiunto successivamente aggiunge un'ulteriore [conferma](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), rendendo più costoso riscrivere la posizione della [transazione](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) nella [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain). Questa differenza è importante: il lavoro è costoso da produrre e facile da verificare.


<!-- micrographic: proof-of-work-process-01 -->
[Un miner calcola ripetutamente l'hash di un blocco proposto finché un risultato non è inferiore al target della rete, poi trasmette il blocco. I nodi verificano rapidamente la prova e ogni regola prima che il blocco entri a far parte della blockchain: il lavoro è costoso da produrre e facile da verificare.](/micrographics/proof-of-work-process-01/it.md)


[La Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) svolge diverse funzioni:

* offre ai [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) indipendenti un modo per competere senza un coordinatore centrale
* rende l'ordine delle [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) costoso da riscrivere
* collega la sicurezza della rete ad apparecchiature ed energia del mondo reale
* supporta un metodo pubblico per scegliere tra storie valide concorrenti: la catena con il maggior [lavoro accumulato](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Il Mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) non risolve equazioni utili per uno scopo esterno. Il suo scopo è garantire l'ordinamento delle [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) di Bitcoin. La rete regola periodicamente il target: quando i blocchi arrivano troppo rapidamente lo abbassa, e quando arrivano troppo lentamente lo alza, puntando in media a circa un blocco ogni dieci minuti al variare della potenza di calcolo.

[La Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) comporta un costo energetico reale. I sostenitori affermano che proprio questo costo ancora la sicurezza di Bitcoin e può creare domanda di energia flessibile o altrimenti inutilizzata. I critici mettono in discussione la quantità e la provenienza dell'energia impiegata. Una valutazione responsabile si chiede quale energia venga utilizzata, da dove provenga, quale sicurezza offra e con quali alternative venga confrontata.

![L'educatore, lo studente principiante e lo studente tecnico discutono di un'unità di mining da tavolo con una ventola e un alimentatore separato.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
