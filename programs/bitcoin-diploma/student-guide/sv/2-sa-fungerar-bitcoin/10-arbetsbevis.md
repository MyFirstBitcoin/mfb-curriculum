# 2.10 Arbetsbevis

![](https://cdn.sanity.io/images/vje9ehw2/staging/45335cc0b3fa7d780ac9afb46b371566868dd2df-1536x1024.svg)


> **Definition – Arbetsbevis**
>
> [Arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) är den process som [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) använder för att tävla om rätten att föreslå nästa block.


En [hashfunktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#hash-function) omvandlar data till ett resultat med fast längd. En liten ändring av indata ger ett oförutsägbart nytt resultat. En [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ändrar en liten del av datan i ett föreslaget block och hashar det upprepade gånger. Ett resultat är giltigt endast när dess talvärde ligger under nätverkets [målvärde](https://curriculum.myfirstbitcoin.org/lexicon/en/#target), ett tröskelvärde som fastställs av reglerna; ett lägre [målvärde](https://curriculum.myfirstbitcoin.org/lexicon/en/#target) innebär färre [giltiga resultat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result) och fler försök. Det finns ingen genväg, så [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) kan behöva göra många försök.

När en [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) hittar ett [giltigt resultat](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-result), [sänder den ut](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) blocket. [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kan kontrollera beviset snabbt, även om det krävdes betydande beräkningar och energi för att hitta det. Om blocket innehåller en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), får denna [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sin [första bekräftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#first-confirmation): den har registrerats i ett giltigt block. Varje giltigt block som läggs till efter det ger ytterligare en [bekräftelse](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation), vilket gör [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)ens plats i [blockkedjan](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) mer kostsam att skriva om. Denna skillnad är viktig: arbete är kostsamt att utföra och enkelt att verifiera.


<!-- micrographic: proof-of-work-process-01 -->


[Arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) fyller flera syften:

* det ger oberoende [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) ett sätt att tävla utan en central schemaläggare
* det gör ordningsföljden för [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) kostsam att skriva om
* det kopplar nätverkets säkerhet till fysisk utrustning och energi
* det stöder en offentlig metod för att välja mellan konkurrerande giltiga historiker: kedjan med mest [ackumulerat arbete](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work)

[Utvinning](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) löser inte nyttiga ekvationer för något externt ändamål. Syftet är att säkerställa ordningsföljden för Bitcoins [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Nätverket justerar målvärdet regelbundet: när block kommer för snabbt sänker det målvärdet, och när de kommer för långsamt höjer det målvärdet, med sikte på i genomsnitt ungefär ett block var tionde minut när beräkningskraften förändras.

[Arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) innebär en faktisk energikostnad. Förespråkare menar att denna kostnad utgör grunden för Bitcoins säkerhet och kan skapa efterfrågan på energi som är flexibelt tillgänglig eller annars skulle förbli oanvänd. Kritiker ifrågasätter mängden energi som används och varifrån den kommer. En ansvarsfull utvärdering undersöker vilken energi som används, varifrån den kommer, vilken säkerhet den ger och vilka alternativ som jämförs.

![Läraren, nybörjaren och den tekniskt kunniga eleven diskuterar en utvinningsenhet för bordsplacering med en fläkt och separat strömförsörjning.](https://cdn.sanity.io/images/vje9ehw2/staging/697bc6224bf2a1b1e59538d3ed7fbd6bc34fb2ac-1054x1493.png)
