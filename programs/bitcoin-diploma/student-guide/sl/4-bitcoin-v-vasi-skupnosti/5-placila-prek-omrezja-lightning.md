# 4.5 Plačila prek omrežja Lightning

![](https://cdn.sanity.io/images/vje9ehw2/staging/6885723fcdb1a7ee8121a9139daa7714cf5bbd05-1536x1024.svg)


<!-- micrographic: lightning-phone-payment-01 -->
[Prejemnik na svojem telefonu ustvari zahtevek za plačilo prek omrežja Lightning z navedenim zneskom, pošiljatelj ga skenira in plača, plačilo pa trenutek pozneje prispe na prejemnikov telefon.](/micrographics/lightning-phone-payment-01/sl.md)



<!-- micrographic: lightning-payment-sequence-01 -->
[Plačilo prek omrežja Lightning v šestih korakih: prejemnik ustvari zahtevek, pošiljatelj ga skenira, preveri prejemnika, znesek, enoto, rok veljavnosti in provizijo ter odobri plačilo, nato se plačilo usmeri po omrežju in obe denarnici prikažeta rezultat. Vsaka denarnica je lahko skrbniška ali samoskrbniška. Če plačilo ne uspe ali zahtevek poteče, se postopek začne znova z novim zahtevkom.](/micrographics/lightning-payment-sequence-01/sl.md)


Lightning omogoča praktično izvajanje hitrih, majhnih plačil v omrežju Bitcoin. Primeren je lahko za plačevanje pri trgovcu, ponavljajoča se lokalna plačila, spletne storitve ali prenose, pri katerih bi bila provizija za transakcijo v verigi prevelika glede na znesek plačila.

Pri lokalnem prikazu uporabe omrežja Lightning je treba pojasniti:

* ali je denarnica skrbniška ali samoskrbniška
* kako se denarnica napolni s sredstvi
* ali polnjenje zahteva verižno [transakcijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ali storitev
* kakšno varnostno kopiranje ali obnavljanje ščiti stanje sredstev
* katera vrsta plačilnega zahtevka se uporablja
* katere provizije ali omejitve veljajo
* kaj se zgodi, če plačilo ne uspe
* kako prejemnik potrdi plačilo

Posamezen [**račun Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-invoice) je plačilni zahtevek, ustvarjen za določeno plačilo. Vključuje lahko znesek, podatke o cilju plačila in čas poteka veljavnosti. Pred plačilom v denarnici preberite [potrditveni](https://curriculum.myfirstbitcoin.org/lexicon/en/#confirmation) zaslon.

Posamezen [**naslov Lightning**](https://curriculum.myfirstbitcoin.org/lexicon/en/#lightning-address) je človeku berljiv identifikator, ki ga podpirajo nekatere storitve. Lahko je videti kot e-poštni naslov, vendar je pripomoček za usmerjanje plačil, ne e-poštni račun. Odvisen je od ponudnika ali domene, ki ga podpira.

Pri vodenem plačilu:

1. Prejemnik ustvari ustrezen zahtevek.
1. Pošiljatelj ga optično prebere ali kopira.
1. Pošiljatelj preveri prejemnika, znesek, enoto in provizijo.
1. Pošiljatelj odobri plačilo šele, ko so podatki pravilni.
1. Obe strani potrdita rezultat vsaka v svoji denarnici.
1. Skupina pojasni tveganja, povezana s [skrbništvom](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) in neuspešnimi plačili.

Ne predpostavljajte, da uspešno plačilo prek omrežja Lightning dokazuje, da je denarnica varna za hranjenje večjih zneskov. Priročnost plačevanja in [skrbniška](https://curriculum.myfirstbitcoin.org/lexicon/en/#custody) varnost sta ločeni vprašanji.
