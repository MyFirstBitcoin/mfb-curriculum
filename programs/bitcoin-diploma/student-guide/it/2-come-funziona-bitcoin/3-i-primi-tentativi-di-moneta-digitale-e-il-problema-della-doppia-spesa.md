# 2.3 I primi tentativi di moneta digitale e il problema della doppia spesa

Bitcoin non è stato il primo tentativo di moneta digitale. È nato da quattro decenni di sperimentazione, attingendo alle idee di molti progetti precedenti che hanno contribuito a definirne il progetto vincente.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) utilizzava la [crittografia](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) per consentire pagamenti digitali privati. Dipendeva da un'azienda centrale e da rapporti con le banche. Quando l'azienda è fallita, il sistema non ha potuto proseguire come rete monetaria indipendente.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) utilizzava la [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) per rendere costoso l'invio di email indesiderate. Il computer del mittente doveva svolgere un lavoro prima di inviare un messaggio. L'idea ha mostrato come un costo computazionale potesse scoraggiare gli abusi.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) descriveva un sistema proposto in cui il lavoro computazionale poteva creare registrazioni digitali scarse. Non è stato lanciato come sistema monetario decentralizzato completo, ma ha sviluppato idee importanti sulla [scarsità](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) digitale e sulla prova.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) e la [**Proof of Work riutilizzabile (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) hanno esplorato modi per consentire ai partecipanti di creare o trasferire [valore](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) digitale scarso senza affidarsi soltanto a un unico database centrale. Erano incompleti, ma hanno contribuito a chiarire di che cosa avrebbe avuto bisogno un sistema funzionante.
* Sebbene [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) non fosse una moneta, ha dimostrato che una [rete Peer-to-Peer (P2P)](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) poteva consentire a molti computer indipendenti di condividere informazioni senza che un unico server centrale controllasse l'intero sistema.

Nel loro insieme, questi esperimenti hanno fornito tasselli utili del puzzle. Hanno anche chiarito il problema rimasto aperto.


<!-- card: definition -->
> **Definition – Doppia spesa**
>
> [La doppia spesa](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) è il tentativo di inviare la stessa unità digitale a due destinatari. I dati digitali possono essere copiati perfettamente, quindi un sistema di moneta digitale ha bisogno di un modo per stabilire quale [transazione](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sia valida.


[I sistemi centralizzati](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) lo impediscono lasciando che un unico database fidato decida quale pagamento è avvenuto per primo. Il 31 ottobre 2008, il whitepaper di [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto), [_Bitcoin: A Peer-to-Peer Electronic Cash System_](https://bitcoin.org/bitcoin.pdf), ha illustrato un approccio diverso: un sistema pubblico in grado di stabilire una cronologia condivisa dei pagamenti senza una banca, un'azienda o un'altra autorità centrale.

Il whitepaper ha riunito le caratteristiche necessarie per tale approccio:

1. **Una [rete Peer-to-Peer (P2P)](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [le transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) vengono annunciate direttamente a una rete di partecipanti.
1. **[Firme digitali](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** una [chiave privata](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) è un'informazione segreta che crea una firma per autorizzare una spesa; solo chi la detiene può farlo.
1. **Blocchi e [Mining](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [i miner](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) raccolgono le [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) in blocchi e usano la [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) per competere nell'aggiunta del blocco successivo.
1. **Verifica [indipendente](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [i nodi](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) controllano che [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) e blocchi rispettino le regole di Bitcoin.
1. **Una storia condivisa con l'accumulo di [Proof of Work (PoW)](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** i partecipanti riconoscono la [catena valida](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) di [transazioni](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) con il maggior [lavoro accumulato](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) come registro condiviso.


<!-- micrographic: five-part-response-01 -->
[Cinque elementi si combinano per risolvere il problema della doppia spesa: una rete peer-to-peer, le firme digitali, i blocchi e il mining, la verifica indipendente e una storia condivisa con la maggiore proof of work accumulata. Insieme permettono alla rete di respingere una seconda spesa senza un'autorità centrale.](/micrographics/five-part-response-01/it.md)


Questo modulo spiega questi concetti in modo più dettagliato. Insieme, hanno fornito una risposta pratica al [problema del Double Spend](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): la rete può respingere un secondo tentativo di spendere gli stessi bitcoin senza affidarsi a un'autorità centrale. Bitcoin ha offerto la combinazione mancante che decenni di esperimenti sul denaro digitale avevano cercato.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
