# 2.9 Kullanıcılar, düğümler ve madenciler

Bitcoin, farklı katılımcıların farklı roller üstlenmesi sayesinde çalışır.

* **Kullanıcılar** bitcoin alır, saklar ve gönderir. Bir kullanıcı, bir cüzdanda tutulan kendi anahtarlarını kontrol edebilir ya da bir [saklayıcı](https://curriculum.myfirstbitcoin.org/lexicon/en/#custodian) kullanabilir. Kullanıcılar, bitcoin'i kabul edip etmemeyi ve hangi kurallara ya da hizmetlere güvendiklerini seçerek ağa ekonomik anlam kazandırır.
* [**Düğümler**](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) Bitcoin yazılımını çalıştırır ve kuralları bağımsız olarak doğrular. Bir [tam düğüm](https://curriculum.myfirstbitcoin.org/lexicon/en/#full-node), [işlemlerin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) geçerli imzalara sahip olduğunu, bitcoin'lerin daha önce harcanmamış olduğunu, blokların [iş ispatı](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) koşulunu karşıladığını ve yeni bitcoin'lerin [ihraç takvimine](https://curriculum.myfirstbitcoin.org/lexicon/en/#issuance-schedule) uyduğunu kontrol eder. [Düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) geçerli verileri eşleriyle paylaşır ve geçersiz verileri reddeder.
* [**Madenciler**](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bekleyen [işlemleri](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) toplar, [aday bloklar](https://curriculum.myfirstbitcoin.org/lexicon/en/#candidate-block) oluşturur ve [iş ispatı](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) yoluyla rekabet eder. Başarılı bir [madenci](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) [bir blok yayınlar](https://curriculum.myfirstbitcoin.org/lexicon/en/#broadcast) ve izin verilen [blok sübvansiyonunu](https://curriculum.myfirstbitcoin.org/lexicon/en/#block-subsidy) ve [işlem ücretlerini](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction-fee) alabilir. [Madenciler](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) hem [işlemlerin](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sıralanmasına hem de [defterin](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) yeniden yazılmasının maliyetli hale gelmesine yardımcı olur.
* **Geliştiriciler** yazılım değişikliklerini inceler, yazar ve önerir. Bitcoin'in kurallarının sahibi değildirler. Bir yazılım değişikliği, ancak katılımcılar bu kurallara uyan yazılımı çalıştırmayı seçerse önem taşır.


<!-- micrographic: bitcoin-participant-roles-01 -->
[Bitcoin'deki dört rol: kullanıcılar bitcoin alır, saklar ve gönderir; düğümler kuralları bağımsız olarak doğrular; madenciler iş ispatıyla aday bloklar oluşturur; geliştiriciler ise yazılım önerir. Hiçbir rol tek başına ağı kontrol etmez.](/micrographics/bitcoin-participant-roles-01/tr.md)


Bu roller birbirini sınırlar:

* bir kullanıcı, gerekli geçerli imza olmadan bitcoin harcayamaz
* bir [madenci](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bir blok önerebilir, ancak bloğun kurallara uyup uymadığına [düğümler](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) karar verir
* bir [düğüm](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kendi kurallarını kullanarak doğrulama yapar, ancak [mutabakat](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) ağ genelinde uyumlu kurallar gerektirir
* geliştiriciler yazılım önerebilir, ancak onu çalıştırıp çalıştırmamaya katılımcılar karar verir

Bazı kişiler birden fazla rol üstlenir. Bir [madenci](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) bir [düğüm](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) çalıştırabilir ve aynı zamanda kullanıcı da olabilir. Yeni başlayan birinin, rollerin birbirini nasıl dengelediğini açıklayabilmesi için her rolü kendisinin üstlenmesi gerekmez.

**Anlık soru:** Bir [düğüm](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) neden [işlemleri](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) doğrular? Bir [düğümün](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrol ettiği en az bir kuralı belirtin.

![Eğitmen, bir düğüm bilgisayarının başındaki teknik öğrenciye rehberlik ediyor; monitör onlara dönük, arka kasası ise izleyiciye görünür durumda.](https://cdn.sanity.io/images/vje9ehw2/production/78294f6c55abe9c667acb9b6c7e3aea1b0fd6f5b-1054x1492.png)
