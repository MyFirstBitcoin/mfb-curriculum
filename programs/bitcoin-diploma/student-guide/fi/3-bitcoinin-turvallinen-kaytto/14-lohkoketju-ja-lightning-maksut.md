# 3.14 Lohkoketju- ja Lightning-maksut

![](https://cdn.sanity.io/images/vje9ehw2/staging/db0a9af04f26c001f101dab84bb68faf11c8f1eb-1536x1024.svg)


<!-- micrographic: on-chain-and-lightning-01 -->



> **Definition – Lohkoketju- ja Lightning-maksut**
>
> [Lohkoketjumaksut](https://curriculum.myfirstbitcoin.org/lexicon/en/#on-chain-payment) tallennetaan Bitcoinin [lohkoketjuun](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) ja ne saavat [vahvistuksia](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation). Lightning on Bitcoinin päälle rakennettu maksuverkko, joka voi mahdollistaa nopeat, usein toistuvat maksut. Lightning-maksu voi onnistua nopeasti tai epäonnistua, ja siinä käytettävä lompakko voi silti olla joko säilytyspalveluun perustuva tai itsehallinnoitu.



> **Dark – Maksureitti ei määritä varojen hallintatapaa**
>
> Lohkoketju- ja Lightning-maksuihin liittyy erilaisia [kompromisseja](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off). Lightning-lompakko voi olla säilytyspalveluun perustuva tai itsehallinnoitu, eikä nopeasti onnistunut maksu todista, että palvelu soveltuu suurempien saldojen säilyttämiseen tai jokaiseen tilanteeseen.



<!-- micrographic: onchain-lightning-table-01 -->


Mitä maksureittiä vastaanottaja odottaa käytettävän? Varmistakaa ennen maksamista, onko vastaanottaja antanut lohkoketjuosoitteen vai [Lightning-laskun](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) tai maksupyynnön. Lohkoketjulompakolla ei voi maksaa suoraan jokaista [Lightning-laskua](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice), eikä Lightning-lompakko välttämättä tue kaikkia lohkoketjutoimintoja. Jotkin sovellukset tukevat molempia maksureittejä, mutta niiden käyttö voi aiheuttaa lisämaksuja tai riippuvuutta palveluista. Lightningin yksityiskohtainen käyttöönotto, kanavat, reititys ja [likviditeetti](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) kuuluvat [syventäviin opintoihin](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/); paikan päällä tehtävä käytännön harjoittelu kuuluu **moduuliin 4** silloin, kun se on turvallista ja tarkoituksenmukaista.

Kuvitelkaa, että valmiiksi laaditussa esimerkkitilanteessa on tarjolla molemmat maksureitit. Kumpaa maksupyyntöä käytettäväksi tarkoitettu lompakko pystyy hyödyntämään, ja mitä tarkistaisitte ennen maksun hyväksymistä? Vastaus riippuu vastaanottajan maksupyynnöstä, lompakosta ja tilanteesta — ei yleispätevästä ”parhaasta” maksureitistä.

![Opettaja osoittaa taululla kahta erilaista geometrista maksureittiä, joita aloittelija ja teknisesti suuntautuneet oppijat pohtivat.](https://cdn.sanity.io/images/vje9ehw2/staging/88a814c8d03b3b08fbffc1adcec1767df8735759-1055x1491.png)
