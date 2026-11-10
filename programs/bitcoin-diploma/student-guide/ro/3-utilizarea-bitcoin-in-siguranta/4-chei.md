# 3.4 Chei

Proprietatea asupra Bitcoin este asigurată prin chei criptografice.


<!-- card: definition -->
> **Definition – Cheie Privată**
>
> O [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) este o informație secretă care permite unui Portofel să creeze [semnături digitale](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) valide. O semnătură autorizează cheltuirea de bitcoin controlați de cheia corespunzătoare. Oricine obține o [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) poate, de obicei, să cheltuiască fondurile respective.


O [**Cheie Publică**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) este derivată matematic dintr-o [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Aceasta ajută la verificarea unei semnături fără a dezvălui o [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adresele sunt create dintr-o [Cheie Publică](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) pe baza informațiilor acesteia.

Regula esențială este simplă:

**Informațiile publice pentru primirea fondurilor pot fi partajate. Informațiile private pentru cheltuirea fondurilor trebuie să rămână secrete.**

O [semnătură digitală](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) dovedește că o [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) necesară a autorizat o [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Aceasta nu introduce o [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) în acea [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifică semnătura înainte de a accepta cheltuirea fondurilor.

Majoritatea portofelelor pentru începători folosesc [semnătura unică](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): o singură Cheie Privată autorizează o Tranzacție. Portofelele moderne gestionează automat numeroase chei. Începătorii nu ar trebui să copieze sau să manipuleze o [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) sub forma unui șir individual de caractere. Protejați copia de siguranță aprobată pentru Portofel și urmați procedura de recuperare a acestuia.

Niciun educator de încredere, nicio companie care oferă portofele, niciun angajat al unei platforme de schimb, niciun lucrător de asistență tehnică și niciun dezvoltator Bitcoin nu are nevoie să îi comunicați o [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) sau [fraza de recuperare](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Oricine vă solicită aceste informații trebuie considerat o amenințare.


<!-- card: light -->
> **Încercați:** Sortați exemplele pregătite în trei grupuri: informații care pot fi partajate în siguranță pentru primirea fondurilor, informații secrete pentru cheltuirea fondurilor și informații care pot fi publice, dar care ar trebui totuși păstrate confidențiale atunci când sunt asociate cu o persoană.



<!-- micrographic: private-key-public-info-01 -->
[Dintr-o cheie privată secretă, care nu trebuie divulgată niciodată, se obțin informații publice care pot fi partajate: o cheie publică derivată din aceasta și o adresă de primire creată pe baza cheii publice. Aceeași cheie privată creează semnături pe care nodurile le verifică fără a afla vreodată cheia privată.](/micrographics/private-key-public-info-01/ro.md)
