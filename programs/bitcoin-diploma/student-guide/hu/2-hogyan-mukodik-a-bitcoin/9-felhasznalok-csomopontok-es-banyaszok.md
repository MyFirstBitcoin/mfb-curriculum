# 2.9 Felhasználók, csomópontok és bányászok

A Bitcoin azért működik, mert a különböző résztvevők különböző szerepeket töltenek be.

* **A felhasználók** bitcoint fogadnak, tartanak és küldenek. A felhasználó maga kezelheti a tárcában tárolt saját kulcsait, vagy használhat egy [letétkezelőt](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian). A felhasználók gazdasági jelentőséget adnak a hálózatnak azzal, hogy eldöntik, elfogadnak-e bitcoint, és mely szabályokban vagy szolgáltatásokban bíznak.
* [**A csomópontok**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) Bitcoin-szoftvert futtatnak, és önállóan ellenőrzik a szabályok betartását. Egy [teljes csomópont](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node) ellenőrzi, hogy a [tranzakciók](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) érvényes aláírásokkal rendelkeznek-e, hogy a bitcoinokat nem költötték-e már el, hogy a blokkok teljesítik-e a [munkabizonyítás követelményeit](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work), és hogy az új bitcoinok követik-e a [kibocsátási ütemtervet](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule). [A csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) megosztják az érvényes adatokat a társaikkal, és elutasítják az érvénytelen adatokat.
* [**A bányászok**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) összegyűjtik a függőben lévő [tranzakciókat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction), összeállítanak [blokkjelölteket](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block), és versenyeznek a [munkabizonyítás](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) révén. Egy sikeres [bányász](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [szétküld](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) egy blokkot, és megkaphatja az engedélyezett [blokktámogatást](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) és [tranzakciós díjakat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee). [A bányászok](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) segítenek sorrendbe rendezni a [tranzakciókat](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) és a [főkönyv](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) átírását költségessé teszik.
* **A fejlesztők** felülvizsgálják és megírják a szoftvermódosításokat, valamint javaslatokat tesznek rájuk. Nem ők birtokolják a Bitcoin szabályait. Egy szoftvermódosítás csak akkor számít, ha a résztvevők úgy döntenek, hogy az adott szabályokat követő szoftvert futtatnak.


<!-- micrographic: bitcoin-participant-roles-01 -->


Ezek a szerepek kölcsönösen korlátozzák egymást:

* a felhasználó nem költhet bitcoint a szükséges érvényes aláírás nélkül
* egy [bányász](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) javasolhat egy blokkot, de a [csomópontok](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) döntik el, hogy az megfelel-e a szabályoknak
* egy [csomópont](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) a saját szabályai alapján végez ellenőrzést, de a [konszenzus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) megköveteli, hogy a hálózat egészében összeegyeztethetők legyenek a szabályok
* a fejlesztők javasolhatnak szoftvereket, de a résztvevők döntik el, hogy futtatják-e azokat

Vannak, akik több szerepet is betöltenek. Egy [bányász](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) futtathat egy [csomópontot](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) és egyben felhasználó is lehet. Egy kezdőnek nem kell minden szerepet betöltenie ahhoz, hogy el tudja magyarázni, hogyan tartják egyensúlyban egymást ezek a szerepek.

**Ellenőrző kérdés:** Miért végez egy [csomópont](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ellenőrzést a [tranzakciókon](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction)? Nevezzen meg legalább egy olyan szabályt, amelyet egy [csomópont](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) ellenőriz.

![Az oktató egy csomópontként működő számítógépnél segíti a technikai ismereteket tanuló diákot; a monitor feléjük néz, a néző pedig a monitor hátlapját látja.](https://cdn.sanity.io/images/vje9ehw2/staging/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
