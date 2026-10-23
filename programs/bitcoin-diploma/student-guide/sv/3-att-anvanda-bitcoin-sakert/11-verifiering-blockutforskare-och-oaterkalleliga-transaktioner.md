# 3.11 Verifiering, blockutforskare och oåterkalleliga transaktioner

> **Definition – Transaktions-ID och blockutforskare**
>
> Ett [transaktions-ID](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) ([_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id)) identifierar en blockkedjebaserad [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). En [blockutforskare](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) visar offentliga Bitcoin-data, till exempel en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)s status och antal [bekräftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Den ger en användbar överblick, men är ingen auktoritet över Bitcoin och inget bevis på mottagarens identitet eller ärlighet.


Vad kan denna offentliga information visa, och vad kan den inte visa? Den kan visa en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)s status, destination, belopp, avgift och antal [bekräftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation); den kan inte bevisa varför en betalning gjordes eller om en person är pålitlig. En blockkedjebaserad [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) är obekräftad efter att den har [sänts ut](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) och får sin [första bekräftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation) när den tas med i ett giltigt block. Senare block stärker tilliten till dess plats i historiken, men de rättar inte till en felaktig destination eller ett bedrägeri. Det finns inget universellt antal [bekräftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) som gäller för varje betalning; vilken kontroll som är lämplig beror på beloppet och risken.

För att granska en förberedd [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), ta fram dess [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id), öppna en betrodd blockutforskare för det avsedda [Bitcoin-nätverket](https://curriculum.myfirstbitcoin.org/lexicon/en/#bitcoin-network), och kontrollera status, destination, belopp, avgift och [bekräftelser](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). En blockutforskare är bara ett gränssnitt. En sökning efter en adress eller ett [_txid_](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-id) kan avslöja för operatören att er enhet är intresserad av den informationen. Använd en av läraren förberedd [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) eller en utskriven skärmbild vid övning. Sök inte efter en elevs personliga adress eller [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) på en offentlig tjänst. Om ni senare undersöker en personlig betalning, sätt er in i de [integritetsmässiga](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) och säkerhetsmässiga [avvägningarna](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off) med er anslutning innan ni använder en offentlig tjänst.


> **Callout – Offentliga data är inte bevis på identitet eller ärlighet**
>
> En [blockutforskare](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-explorer) kan visa offentliga [transaktioners](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) data, men den kan inte bevisa vem som kontrollerar en adress, varför en betalning gjordes eller om en mottagare är pålitlig. Använd förberedda exempel för övning och skydda [den personliga integriteten](https://curriculum.myfirstbitcoin.org/lexicon/en/#privacy) vid sökningar i offentliga tjänster.



<!-- micrographic: confirmation-timeline-01 -->


![Läraren och den äldre kursdeltagaren diskuterar ett förberett exempel på en bildskärm som är vänd mot gruppen medan den teknikkunniga kursdeltagaren använder musen; betraktaren ser skärmens baksida.](https://cdn.sanity.io/images/vje9ehw2/production/ea8be6a16be3446fba57b195026c0ce1041b3081-1054x1492.png)
