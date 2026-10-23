# 2.3 Tidiga försök med digitala pengar och problemet med dubbelspendering

Bitcoin var inte det första försöket att skapa digitala pengar. Det byggde på fyra årtionden av experiment och hämtade idéer från många tidigare projekt som bidrog till dess framgångsrika utformning.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) använde [kryptografi](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) för att möjliggöra integritetsskyddade digitala betalningar. Det var beroende av ett centralt företag och bankförbindelser. När företaget gick omkull kunde systemet inte fortsätta som ett oberoende nätverk för pengar.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) använde [arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) för att göra oönskad e-post kostsam. Avsändarens dator behövde utföra arbete innan ett meddelande kunde skickas. Idén visade hur beräkningskostnader kunde motverka missbruk.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) beskrev ett föreslaget system där beräkningsarbete kunde skapa digitala poster med begränsad tillgång. Det lanserades inte som ett fullständigt decentraliserat penningsystem, men utvecklade viktiga idéer om digital [knapphet](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) och bevis.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) och [**återanvändbara arbetsbevis (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) undersökte sätt för deltagare att skapa eller överföra digitalt [värde](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) med begränsad tillgång utan att enbart förlita sig på en central databas. De var ofullständiga, men bidrog till att klargöra vad ett fungerande system skulle behöva.
* Även om [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) inte var pengar visade det att ett [icke-hierarkiskt nätverk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) kunde låta många oberoende datorer dela information utan att en central server kontrollerade hela systemet.

Tillsammans visade dessa experiment användbara pusselbitar. De klargjorde också det återstående problemet.


> **Definition – Dubbelspendering**
>
> [Dubbelspendering](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) är ett försök att skicka samma digitala enhet till två mottagare. Digitala data kan kopieras exakt, så ett digitalt penningsystem behöver ett sätt att fastställa vilken [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) som är giltig.


[Centraliserade system](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) förhindrar detta genom att låta en betrodd databas avgöra vilken betalning som kom först. Den 31 oktober 2008 gav [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto)s vitbok, [_Bitcoin: Ett icke-hierarkiskt elektroniskt kontantsystem_](https://bitcoin.org/bitcoin.pdf), en förklaring av ett annat tillvägagångssätt: ett offentligt system som kunde fastställa en gemensam betalningshistorik utan en bank, ett företag eller någon annan central instans.

Vitboken sammanförde de funktioner som behövdes för detta tillvägagångssätt:

1. **Ett [icke-hierarkiskt nätverk](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) tillkännages direkt i ett nätverk av deltagare.
1. **[Digitala signaturer](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** en [privat nyckel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) är hemlig information som skapar en signatur för att godkänna en betalning; endast innehavaren kan göra detta.
1. **Block och [utvinning](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [utvinnare](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) samlar [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) i block och använder [arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) för att tävla om att lägga till nästa block.
1. **Oberoende [verifiering](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerar [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) och block mot Bitcoins regler.
1. **En gemensam historik med ackumulerade [arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** deltagarna erkänner den [giltiga kedjan](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) av [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) med mest [ackumulerat arbete](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) som den gemensamma historiken.


<!-- micrographic: five-part-response-01 -->


Den här modulen förklarar dessa begrepp mer ingående. Tillsammans gav de en praktisk lösning på [dubbelspenderingsproblemet](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): nätverket kan avvisa ett andra försök att spendera samma bitcoin utan att förlita sig på en central instans. Bitcoin erbjöd den kombination som saknades och som årtionden av experiment med digitala pengar hade sökt efter.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
