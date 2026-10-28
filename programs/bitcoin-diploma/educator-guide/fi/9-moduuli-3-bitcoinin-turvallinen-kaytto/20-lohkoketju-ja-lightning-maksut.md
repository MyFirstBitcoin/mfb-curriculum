# 9.20 Lohkoketju- ja Lightning-maksut

Käyttäkää vertailua, jossa erotetaan maksun kulkureitti [varojen säilytyksestä](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody).


| Kysymys | Lohkoketjussa | Lightning |
| --- | --- | --- |
| Mihin lopullinen selvitys kirjataan? | Suoraan Bitcoinin lohkoketjuun | Maksujen päivitykset tapahtuvat Bitcoinin päälle rakennetussa verkossa; kanavat ovat viime kädessä riippuvaisia Bitcoinista |
| Aloittelijan tavallisesti käyttämät maksun vastaanottotiedot | Lohkoketjuosoite | Lasku, tuettu Lightning-osoite tai muu hyväksytty maksupyyntötyyppi |
| Tyypillinen käyttö | Peruskerroksessa tapahtuva lopullinen selvitys, usein suuremmat tai harvemmin tehtävät siirrot | Usein pienet tai toistuvat maksut, kun paikalliset työkalut ja likviditeetti tukevat niitä |
| Ajoitus | Ensimmäinen vahvistus riippuu siirron sisällyttämisestä lohkoon | Usein nopea, mutta maksut voivat epäonnistua |
| Maksut ja kapasiteetti | Riippuvat siirron datasta ja lohkotilan kysynnästä | Riippuvat lompakosta, reitistä, likviditeetistä, palvelusta ja maksun olosuhteista |
| Varojen säilytys | Varat voivat olla palveluntarjoajan säilytyksessä tai omassa hallinnassa | Varat voivat olla palveluntarjoajan säilytyksessä tai omassa hallinnassa |
| Aloittelijan tärkeimmät tarkistukset | Oikea osoite, verkko, summa, siirtomaksu ja vahvistus | Oikea lasku tai kohde, summa, voimassaoloaika, maksu ja maksun lopputulos |


Lightning ei ole erillinen kolikko. Onnistunut Lightning-maksu ei osoita, että lompakossa on turvallista säilyttää suurempaa saldoa. Kanavien toiminta, reititysinfrastruktuuri ja [likviditeetin](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-liquidity) hallinta kuuluvat [syventäviin opintoihin](https://curriculum.myfirstbitcoin.org/programs/advanced-modules/) Bitcoin Diploma -koulutuksen ulkopuolella.


<!-- micrographic: on-chain-and-lightning-01 -->
[Lohkoketjumaksut kirjataan suoraan Bitcoinin lohkoketjuun, kun taas Lightning on Bitcoinin päälle rakennettu maksuverkko nopeisiin, toistuviin maksuihin, jotka voivat myös epäonnistua. Kumpikin vaihtoehto voi perustua ulkopuoliseen säilytyspalveluun tai omatoimiseen säilytykseen.](/micrographics/on-chain-and-lightning-01/fi.md)
