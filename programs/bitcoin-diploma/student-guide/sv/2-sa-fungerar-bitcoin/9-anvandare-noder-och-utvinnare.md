# 2.9 Användare, noder och utvinnare

Bitcoin fungerar eftersom olika deltagare har olika roller.

* **Användare** tar emot, innehar och skickar bitcoin. En användare kan själv kontrollera sina nycklar som förvaras i en plånbok eller använda en [förvaringstjänst](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). Användare ger nätverket ekonomisk betydelse genom att välja om de vill acceptera bitcoin och vilka regler eller tjänster de litar på.
* [**Noder**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kör Bitcoin-programvara och verifierar reglerna oberoende av varandra. En [fullnod](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) kontrollerar att [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) har giltiga signaturer, att bitcoin inte redan har spenderats, att block uppfyller kraven för [arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) och att nya bitcoin följer [utgivningsschemat](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) delar giltiga data med andra noder och avvisar ogiltiga data.
* [**Utvinnare**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) samlar ihop väntande [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), bygger [kandidatblock](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) och tävlar genom [arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). En framgångsrik [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [sänder ut](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) ett block och kan få den tillåtna [blocksubventionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) och [transaktionsavgifterna](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [Utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) hjälper till att ordna [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) och gör [huvudboken](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) kostsam att skriva om.
* **Utvecklare** granskar, skriver och föreslår ändringar i programvaran. De äger inte Bitcoins regler. En ändring i programvaran har betydelse endast om deltagarna väljer att köra programvara som följer dessa regler.


<!-- micrographic: bitcoin-participant-roles-01 -->


Dessa roller begränsar varandra:

* en användare kan inte spendera bitcoin utan den giltiga signatur som krävs
* en [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan föreslå ett block, men [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) avgör om det följer reglerna
* en [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifierar enligt sina egna regler, men [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) kräver kompatibla regler i hela nätverket
* utvecklare kan föreslå programvara, men deltagarna väljer om de vill köra den

Vissa personer har flera roller. En [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan driva en [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) och även vara användare. En nybörjare behöver inte ha alla roller för att kunna förklara hur rollerna balanserar varandra.

**Kontrollfråga:** Varför utför en [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifiering av [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Nämn minst en regel som en [nod](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerar.

![Läraren vägleder den tekniskt intresserade eleven vid en dator som kör en nod, med bildskärmen vänd mot dem och skärmens baksida synlig för betraktaren.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
