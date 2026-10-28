# 2.5 La blockchain: il registro pubblico di Bitcoin

<!-- card: definition -->
> **Definition – Blockchain**
>
> La [blockchain](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) di Bitcoin è un registro pubblico delle [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), replicato su molti computer indipendenti. Un blocco raggruppa un insieme di [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) valide nella successiva porzione proposta di tale registro. Ogni blocco valido si collega al precedente, fornendo alla rete una cronologia condivisa e ordinata da verificare.



<!-- card: light -->
> **Come i nodi raggiungono il consenso**
>
> [I nodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verificano in modo indipendente le stesse regole e convergono sulla cronologia valida con la maggiore [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) accumulata. Modificare una registrazione precedente modifica il relativo blocco e spezza i collegamenti con i blocchi successivi, quindi una cronologia concorrente deve rifare quel lavoro e recuperare il ritardo prima che i [nodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) la accettino. Questo costoso processo di ordinamento aiuta la rete a raggiungere il [consenso](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) senza un custode centrale del registro. Le copie non cambiano simultaneamente; i [nodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ricevono e convalidano i dati in modo indipendente. Bitcoin punta a produrre un nuovo blocco circa ogni dieci minuti, in media. La cronologia è difficile e costosa da riscrivere, ma non letteralmente impossibile da modificare: possono verificarsi cronologie concorrenti temporanee e riorganizzazioni.
