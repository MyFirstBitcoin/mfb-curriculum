# 2.3 Primele încercări de creare a banilor digitali și problema dublei cheltuieli

Bitcoin nu a fost prima încercare de a crea bani digitali. A fost construit pe baza a patru decenii de experimente, preluând idei din numeroase proiecte anterioare care au contribuit la succesul concepției sale.

* [**DigiCash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#digicash) folosea [Criptografie](https://curriculum.myfirstbitcoin.org/lexicon/en/#cryptography) pentru a permite plăți digitale confidențiale. Depindea de o companie centrală și de relații cu băncile. Când compania a dat faliment, sistemul nu a putut continua să funcționeze ca o rețea monetară independentă.
* [**Hashcash**](https://curriculum.myfirstbitcoin.org/lexicon/en/#hashcash) folosea [Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) pentru a face costisitoare trimiterea de e-mailuri nedorite. Calculatorul expeditorului trebuia să efectueze un efort de calcul înainte de a trimite un mesaj. Ideea a arătat cum costul de calcul putea descuraja abuzurile.
* [**Bit Gold**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bit-gold) descria un sistem propus în care efortul de calcul putea crea înregistrări digitale rare. Nu a fost lansat ca un sistem monetar descentralizat complet, dar a dezvoltat idei importante despre caracterul digital al [rarității](https://curriculum.myfirstbitcoin.org/lexicon/en/#scarcity) și despre dovezi.
* [**B-money**](https://curriculum.myfirstbitcoin.org/lexicon/en/#b-money) și [**Dovada Muncii reutilizabilă (RPoW)**](https://curriculum.myfirstbitcoin.org/lexicon/en/#reusable-proof-of-work) au explorat modalități prin care participanții să creeze sau să transfere, în formă digitală și în cantitate limitată, [valoare](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) fără a se baza doar pe o singură bază de date centrală. Erau incomplete, dar au contribuit la clarificarea cerințelor unui sistem funcțional.
* Deși [**BitTorrent**](https://curriculum.myfirstbitcoin.org/lexicon/en/#bittorrent) nu era o formă de bani, a arătat că o [rețea Peer-to-Peer (P2P)](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network) putea permite multor calculatoare independente să partajeze informații fără ca un server central să controleze întregul sistem.

Împreună, aceste experimente au oferit piese utile ale puzzle-ului. De asemenea, au clarificat problema rămasă.


<!-- card: definition -->
> **Definition – Dubla cheltuire**
>
> [Dubla cheltuire](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) este o încercare de a trimite aceeași unitate digitală către doi destinatari. Datele digitale pot fi copiate perfect, așa că un sistem monetar digital are nevoie de o modalitate de a stabili care [Tranzacție](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) este validă.


[Sistemele centralizate](https://curriculum.myfirstbitcoin.org/lexicon/en/#centralized-system) împiedică acest lucru lăsând o singură bază de date de încredere să decidă care plată a avut loc prima. Pe 31 octombrie 2008, [Satoshi Nakamoto](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi-nakamoto), în Whitepaper-ul său, [_Bitcoin: Un sistem de numerar electronic Peer-to-Peer (P2P)_](https://bitcoin.org/bitcoin.pdf), a explicat o abordare diferită: un sistem public care putea stabili un istoric comun al plăților fără o bancă, o companie sau o altă autoritate centrală.

Whitepaper-ul a reunit caracteristicile necesare pentru această abordare:

1. **O [rețea Peer-to-Peer (P2P)](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network):** [tranzacțiile](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) sunt anunțate direct unei rețele de participanți.
1. **[Semnături digitale](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature):** o [Cheie Privată](https://curriculum.myfirstbitcoin.org/lexicon/en/#private-key) este o informație secretă care creează o semnătură pentru a autoriza o cheltuială; doar deținătorul ei poate face acest lucru.
1. **Blocuri și [minerit](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** [minerii](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) adună [tranzacții](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) în blocuri și folosesc [Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) pentru a concura să adauge următorul bloc.
1. **Verificare [independentă](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification):** [nodurile](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) verifică [tranzacțiile](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) și blocurile în raport cu regulile Bitcoin.
1. **Un istoric comun cu un volum acumulat de [Dovada Muncii](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work):** participanții recunosc [lanțul valid](https://curriculum.myfirstbitcoin.org/lexicon/en/#valid-chain) de [tranzacții](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) cu cel mai mare volum de [muncă acumulată](https://curriculum.myfirstbitcoin.org/lexicon/en/#accumulated-work) drept evidența comună.


<!-- micrographic: five-part-response-01 -->
[Cinci componente se îmbină pentru a rezolva problema dublei cheltuiri: o rețea peer-to-peer, semnături digitale, blocuri și minerit, verificare independentă și un istoric comun cu cea mai mare cantitate de muncă acumulată demonstrată prin dovada muncii. Împreună, acestea permit rețelei să respingă o a doua cheltuire fără o autoritate centrală.](/micrographics/five-part-response-01/ro.md)


Acest modul explică aceste concepte mai detaliat. Împreună, ele au oferit un răspuns practic la [problema de Cheltuială Dublă](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending): rețeaua poate respinge o a doua încercare de a cheltui același bitcoin fără a se baza pe o autoritate centrală. Bitcoin a oferit combinația lipsă pe care decenii de experimente cu bani digitali încercaseră să o găsească.

![](https://cdn.sanity.io/images/vje9ehw2/production/a3edf811f6b40ec4111cb8b7ccd1280c057ac572-1536x1024.svg)
