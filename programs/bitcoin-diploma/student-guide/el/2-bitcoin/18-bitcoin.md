# 2.18 Ανασκόπηση: Πώς αντιμετωπίζει το Bitcoin τις αδυναμίες του νομισματικού συστήματος;

Σταματήστε για λίγο και σκεφτείτε πώς οι δημόσιοι κανόνες, η πεπερασμένη έκδοση, η μεταφορά μεταξύ ομοτίμων και η ανεξάρτητη [επαλήθευση](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification) αντιμετωπίζουν τις αδυναμίες που εντοπίστηκαν στην **Ενότητα 1**: τη μεταβαλλόμενη προσφορά, τον θεσμικό έλεγχο, την περιορισμένη πρόσβαση και την εξάρτηση από την εμπιστοσύνη. Γιατί οι [κόμβοι](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) και οι [εξορύκτες](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) έχουν διαφορετικούς ρόλους και γιατί πρέπει η [διπλή δαπάνη](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending) να αποτρέπεται; Το Bitcoin αντικαθιστά μέρος της εμπιστοσύνης στους θεσμούς με [επαλήθευση](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification) και προσωπική ευθύνη· δεν εξαλείφει τον κίνδυνο ή τους [συμβιβασμούς](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off).


<!-- micrographic: bitcoin-responses-tradeoffs-01 -->
[Ένας πίνακας που αντιστοιχίζει πέντε πιθανές αδυναμίες των σύγχρονων νομισματικών συστημάτων με την απάντηση του Bitcoin και τη νέα ευθύνη ή τον συμβιβασμό που συνεπάγεται κάθε απάντηση. Το Bitcoin αντικαθιστά μέρος της εμπιστοσύνης στους θεσμούς με επαλήθευση και προσωπική ευθύνη, αλλά δεν εξαλείφει τον κίνδυνο.](/micrographics/bitcoin-responses-tradeoffs-01/el.md)


**Βασικός προβληματισμός:** Με βάση όσα έχετε μάθει για το Bitcoin σε αυτή την ενότητα, έχει [αξία](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) για εσάς; Αντιπροσωπεύει η τρέχουσα [τιμή](https://curriculum.myfirstbitcoin.org/lexicon/en/#price) του bitcoin την [αξία](https://curriculum.myfirstbitcoin.org/lexicon/en/#value) του;

#### Βασικά συμπεράσματα

* Το Bitcoin δημιουργήθηκε για να καταστήσει δυνατή την ψηφιακή μεταφορά χωρίς ένα κεντρικό [καθολικό](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) υπό τη διαχείριση ενός υπευθύνου, αποτρέποντας παράλληλα τη [διπλή δαπάνη](https://curriculum.myfirstbitcoin.org/lexicon/en/#double-spending).
* Το δημόσιο [καθολικό](https://curriculum.myfirstbitcoin.org/lexicon/en/#ledger) του, οι [ψηφιακές υπογραφές](https://curriculum.myfirstbitcoin.org/lexicon/en/#digital-signature), το [δίκτυο ομοτίμων](https://curriculum.myfirstbitcoin.org/lexicon/en/#peer-to-peer-network), η [απόδειξη εργασίας](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work) και η ανεξάρτητη [επαλήθευση](https://curriculum.myfirstbitcoin.org/lexicon/en/#verification) λειτουργούν συνδυαστικά για να διατηρούν ένα κοινό [συναλλακτικό](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) ιστορικό.
* Το Bitcoin είναι αποκεντρωμένο με την έννοια ότι κανένας μεμονωμένος συμμετέχων δεν μπορεί να αλλάξει μονομερώς τα υπόλοιπα ή τους κανόνες για όλους.
* Οι χρήστες επιλέγουν αν θα διακρατούν ή θα αποδέχονται bitcoin· οι [κόμβοι](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) επαληθεύουν τους κανόνες· οι [εξορύκτες](https://curriculum.myfirstbitcoin.org/lexicon/en/#miner) προτείνουν μπλοκ· και οι προγραμματιστές μπορούν να προτείνουν, αλλά όχι να επιβάλλουν, αλλαγές στο λογισμικό.
* Το Bitcoin έχει ένα δημόσια γνωστό χρονοδιάγραμμα προσφοράς με ανώτατο όριο τα 21 εκατομμύρια BTC, και [οι κόμβοι](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) απορρίπτουν μπλοκ που παραβιάζουν αυτόν τον κανόνα.
* Ένα bitcoin (1 BTC) υποδιαιρείται σε 100.000.000 [sats](https://curriculum.myfirstbitcoin.org/lexicon/en/#satoshi), ώστε οι άνθρωποι να μπορούν να χρησιμοποιούν μικρότερες μονάδες χωρίς να χρειάζονται ένα ολόκληρο bitcoin.
* Το Bitcoin μπορεί να αξιολογηθεί ως [υγιές χρήμα](https://curriculum.myfirstbitcoin.org/lexicon/en/#sound-money) με βάση τις νομισματικές του ιδιότητες, αναγνωρίζοντας παράλληλα τους [συμβιβασμούς που συνεπάγεται](https://curriculum.myfirstbitcoin.org/lexicon/en/#trade-off): [μεταβλητότητα της τιμής](https://curriculum.myfirstbitcoin.org/lexicon/en/#volatility), περιορισμένη αποδοχή, πληρωμές που συνήθως είναι δύσκολο ή αδύνατο να αναστραφούν και ανάγκη για αυξημένη προσωπική ευθύνη.

#### Μια στιγμή για αναστοχασμό

Ποιο μέρος του σχεδιασμού του Bitcoin θα εξηγούσατε διαφορετικά τώρα και γιατί;
