# 3.4 Nycklar

Ägande av Bitcoin säkerställs genom kryptografiska nycklar.


<!-- card: definition -->
> **Definition – Privat nyckel**
>
> En [privat nyckel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) är hemlig information som gör det möjligt för en plånbok att skapa giltiga [digitala signaturer](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature). En signatur godkänner användningen av bitcoin som kontrolleras av motsvarande nyckel. Den som får tag på den [privata nyckeln](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) kan vanligtvis använda dessa medel.


En [**publik nyckel**](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) härleds matematiskt från den [privata nyckeln](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Den hjälper till att verifiera en signatur utan att avslöja den [privata nyckeln](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key). Adresser skapas utifrån [publika nycklars](https://curriculum.myfirstbitcoin.org/lexicon/en/#public-key) information.

Grundregeln är enkel:

**Publik information för att ta emot betalningar kan delas. Privat information för att använda medel måste förbli hemlig.**

En [digital signatur](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature) bevisar att den nödvändiga [privata nyckeln](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) godkände en [transaktion](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). Den placerar inte den [privata nyckeln](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) i [transaktionen](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction). [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifierar signaturen innan de godkänner användningen av medlen.

De flesta nybörjarplånböcker använder [enkelsignering](https://curriculum.myfirstbitcoin.org/lexicon/en/#single-signature): en privat nyckel godkänner en transaktion. Moderna plånböcker hanterar många nycklar automatiskt. Nybörjare bör inte kopiera eller hantera enskilda [privata nycklars](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) teckensträngar. Skydda plånbokens godkända säkerhetskopia och följ dess återställningsprocedur.

Ingen seriös utbildare, plånboksleverantör, börsanställd, teknisk supportmedarbetare eller Bitcoin-utvecklare behöver er [privata nyckel](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) eller [återställningsfras](https://curriculum.myfirstbitcoin.org/lexicon/en/#recovery-phrase). Den som ber om den bör betraktas som ett hot.


<!-- card: light -->
> **Prova själva:** Sortera förberedda exempel i tre grupper: information som är säker att dela för att ta emot betalningar, hemlig information för att använda medel och information som kan vara offentlig men ändå bör hållas privat när den är kopplad till en person.



<!-- micrographic: private-key-public-info-01 -->
[En hemlig privat nyckel, som aldrig får delas med någon, ligger till grund för publik information som kan delas: en publik nyckel som härleds från den och en mottagaradress som skapas utifrån den publika nyckeln. Samma privata nyckel skapar signaturer som noder verifierar utan att någonsin få kännedom om den privata nyckeln.](/micrographics/private-key-public-info-01/sv.md)
