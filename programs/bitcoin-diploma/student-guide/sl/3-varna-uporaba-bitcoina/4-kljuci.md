# 3.4 Ključi

Lastništvo v omrežju Bitcoin se zagotavlja s kriptografskimi ključi.


<!-- card: definition -->
> **Definition – Zasebni ključ**
>
> Vsak [zasebni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) je tajni podatek, ki denarnici omogoča ustvarjanje veljavnih [digitalnih podpisov](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). Podpis odobri porabo bitcoinov, ki jih nadzoruje ustrezni ključ. Kdor pridobi [zasebni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key), lahko običajno porabi ta sredstva.


Vsak [**javni ključ**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) je matematično izpeljan iz [zasebnega ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Pomaga preveriti podpis, ne da bi razkril [zasebni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Naslovi se ustvarijo iz [javnoključnih](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) podatkov.

Bistveno pravilo je preprosto:

**Javne podatke za prejemanje lahko delite. Zasebni podatki za porabo morajo ostati tajni.**

Vsak [digitalni podpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) dokazuje, da je zahtevani [zasebni ključ](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) odobril [transakcijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Pri tem ne vključi [zasebnega ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) v [transakcijo](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Vozlišča](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) preverijo podpis, preden sprejmejo porabo.

Večina denarnic za začetnike uporablja [enojni podpis](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): en zasebni ključ odobri transakcijo. Sodobne denarnice samodejno upravljajo številne ključe. Začetniki naj ne kopirajo ali obdelujejo posameznih [zasebnih ključev](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) v obliki nizov. Zaščitite varnostno kopijo, ki jo predvideva denarnica, in upoštevajte njen postopek obnovitve.

Noben zaupanja vreden izobraževalec, ponudnik denarnice, zaposleni na menjalnici, delavec tehnične podpore ali razvijalec omrežja Bitcoin ne potrebuje vašega [zasebnega ključa](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) ali [obnovitvene fraze](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Vsakogar, ki vas prosi za te podatke, obravnavajte kot grožnjo.


<!-- card: light -->
> **Preizkusite:** Pripravljene primere razvrstite v tri skupine: podatki za prejemanje, ki jih je varno deliti, tajni podatki za porabo in podatki, ki so lahko javni, vendar jih je treba ohraniti zasebne, kadar so povezani z osebo.



<!-- micrographic: private-key-public-info-01 -->
[Iz skrivnega zasebnega ključa, ki ga nikoli ne smete deliti z drugimi, nastanejo javni podatki, ki jih lahko delite: javni ključ, izpeljan iz njega, in naslov za prejemanje, ustvarjen iz javnega ključa. Isti zasebni ključ ustvarja podpise, ki jih vozlišča preverjajo, ne da bi kadar koli izvedela zasebni ključ.](/micrographics/private-key-public-info-01/sl.md)
