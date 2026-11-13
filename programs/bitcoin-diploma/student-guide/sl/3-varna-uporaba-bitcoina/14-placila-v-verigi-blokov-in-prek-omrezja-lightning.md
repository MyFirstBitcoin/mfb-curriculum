# 3.14 Plačila v verigi blokov in prek omrežja Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->
[Plačila na verigi se beležijo neposredno v Bitcoinovi verigi blokov, medtem ko je Lightning plačilno omrežje, zgrajeno na Bitcoinu, za hitra in pogosta plačila, ki pa lahko tudi spodletijo. Pri obeh načinih lahko sredstva hrani skrbnik ali pa jih hranite sami.](/micrographics/on-chain-and-lightning-01/sl.md)



<!-- card: definition -->
> **Definition – Plačila v verigi blokov in prek omrežja Lightning**
>
> [Plačila v verigi blokov](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) se beležijo v Bitcoinovi [verigi blokov](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) in prejemajo [potrditve](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning je plačilno omrežje, zgrajeno na Bitcoinu, ki omogoča hitra in pogosta plačila. Plačilo prek omrežja Lightning se lahko hitro izvede ali pa ne uspe, denarnica zanj pa je lahko skrbniška ali samoskrbniška.



<!-- card: dark -->
> **Plačilna pot ne določa skrbništva**
>
> Plačila v verigi blokov in prek omrežja Lightning vključujejo različne [kompromise](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Denarnica Lightning je lahko skrbniška ali samoskrbniška, hitro in uspešno plačilo pa ne dokazuje, da je storitev primerna za večja stanja ali za vse okoliščine.



<!-- micrographic: onchain-lightning-table-01 -->
[Tabela, ki primerja Bitcoin v verigi in Lightning: podatke za prejem, rezultat plačila, običajno uporabo in preverjanja za začetnike. Obe možnosti omogočata skrbništvo tretje osebe ali lastno skrbništvo.](/micrographics/onchain-lightning-table-01/sl.md)


Katero pot pričakuje prejemnik? Pred plačilom preverite, ali je posredoval naslov za plačilo v verigi blokov ali [plačilni nalog Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) oziroma zahtevek. Denarnica za plačila v verigi blokov ne more neposredno poravnati vsakega [plačilnega naloga Lightning](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), denarnica Lightning pa morda ne podpira vseh dejanj v verigi blokov. Nekatere aplikacije podpirajo obe poti, vendar lahko zaračunajo dodatne provizije ali zahtevajo uporabo dodatnih storitev. Podrobnosti o nastavitvi omrežja Lightning, kanalih, usmerjanju in [likvidnosti](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) so del [naprednega učenja](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); praktično delo v živo v lokalnem okolju sodi v **modul 4**, kadar je varno in primerno.

Predstavljajte si, da pripravljeni scenarij ponuja obe plačilni poti. Kateri zahtevek lahko uporabite s predvideno denarnico in kaj bi preverili pred njegovo odobritvijo? Odgovor je odvisen od zahtevka za prejem plačila, denarnice in okoliščin — ne od ene same »najboljše« poti za vse primere.

![Izobraževalec na tabli kaže dve različni geometrijsko prikazani plačilni poti, medtem ko o njiju razmišljajo začetnik in tehnično podkovani udeleženci.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
