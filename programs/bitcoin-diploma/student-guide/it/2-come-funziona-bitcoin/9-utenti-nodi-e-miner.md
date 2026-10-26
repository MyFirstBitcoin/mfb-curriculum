# 2.9 Utenti, nodi e miner

Bitcoin funziona perché partecipanti diversi svolgono ruoli diversi.

* **Gli utenti** ricevono, custodiscono e inviano bitcoin. Un utente può controllare le proprie chiavi conservate in un wallet oppure affidarsi a un [custode](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Gli utenti danno alla rete un significato economico scegliendo se accettare bitcoin e di quali regole o servizi fidarsi.
* [**I nodi**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) eseguono il software Bitcoin e verificano le regole in modo indipendente. Un [nodo completo](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) controlla che le [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) abbiano firme valide, che i bitcoin non siano già stati spesi, che i blocchi soddisfino la [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) e che i nuovi bitcoin rispettino il [calendario di emissione](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [I nodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) condividono i dati validi con i peer e rifiutano quelli non validi.
* [**I miner**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) raccolgono le [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) in sospeso, costruiscono [blocchi candidati](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) e competono attraverso la [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Se ha successo, un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [trasmette](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) un blocco e può ricevere il [sussidio di blocco](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) consentito e le [commissioni di transazione](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [I miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) contribuiscono a ordinare le [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) e rendono il [ledger](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) costoso da riscrivere.
* **Gli sviluppatori** esaminano, scrivono e propongono modifiche al software. Non sono i proprietari delle regole di Bitcoin. Una modifica al software conta solo se i partecipanti scelgono di eseguire un software che segue quelle regole.


<!-- micrographic: bitcoin-participant-roles-01 -->


Questi ruoli si limitano a vicenda:

* un utente non può spendere bitcoin senza la firma valida richiesta
* un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) può proporre un blocco, ma sono i [nodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) a decidere se rispetta le regole
* un [nodo](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifica secondo le proprie regole, ma il [consenso](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) richiede regole compatibili in tutta la rete
* gli sviluppatori possono proporre software, ma sono i partecipanti a scegliere se eseguirlo

Alcune persone svolgono più ruoli. Un [miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) può gestire un [nodo](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ed essere anche un utente. Un principiante non ha bisogno di svolgere ogni ruolo per spiegare come i ruoli si bilanciano a vicenda.

**Domanda flash:** Perché un [nodo](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifica le [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Indichi almeno una regola che un [nodo](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) controlla.

![L'educatore guida lo studente con competenze tecniche davanti a un computer che funge da nodo, con il monitor rivolto verso di loro e il retro dell'involucro visibile all'osservatore.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
