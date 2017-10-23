# Thesis
Emmanouil Papadimitriou's Thesis
Athens, Greece
T.E.I. Athens

Περιγραφή Νοσκομειακής Εφαρμογής :

Η εφαρμογή εξυπηρετεί την γρήγορη και άμεση ενημέρωση του γιατρού (αλλά και του νοσοκομειακού προσωπικού) για όλες τις πληροφορίες του ασθενούς.
Το κύριο μέρος της εφαρμογής, παρέχει τις απαραίτητες πληροφορίες του ασθενούς. Όπως, προσωπικά στοιχεία, ημερομηνία εισαγωγής στο νοσοκομείο, ιστορικό, φάρμακα, εξετάσεις που έγιναν και τα αποτελέσματα τους
chat μεταξύ γιατρών και νοσοκομειακού προσωπικού για τον ασθενή, δημιουργία σημειώσεων από τον/τους γιατρό/γιατρούς.
Αρχικά, για να γίνει η χρήση της εφαρμογής θα πρέπει ο χρήστης (γιατρός, νοσοκομειακό προσωπικό) να έχει ήδη ή να φτιάξει λογαριασμό.
Η διαφορά του γιατρού με το  νοσοκομείακό προσωπικό, είναι ότι μόνο ο γιατρός μπορει να τροποποιησει και να προβαλει τα δεδομένα,
ενώ το νοσοκομειακό προσωπικό μόνο να προβάλει και να αφήσει σημειώσεις και να συμμετέχει στο chat.
Όταν θα κάνει εγγραφή και θα εισάγει τα απαραίτητα στοιχεία του, δεν θα μπορεί να εισαχθεί στο σύστημα αμέσως αλλά θα πρέπει να τον αποδεχθεί ο υπεύθυνος.
Όταν μπει στην εφαρμογή, καλείται να κάνει αναζήτηση το όνομα του ασθενή και να τον επιλέξει ώστε να μπορεί να χρησιμοποιήσει το κύριο μέρος της εφαρμογής.
Όταν γίνει για πρώτη φορά η επιλογή του ασθενούς, θα πρέπει ο χρήστης να περιμένει ώστε να επιβεβαιωθεί από τον υπεύθυνο η επιλογή του.
Μέχρι τότε δεν θα μπορεί ούτε να δει, ούτε να τροποποιήσει καμία πληροφορία λόγω αυστηρών μέτρων ασφάλειας για την προστασία των προσωπικών δεδομένων.
Όταν επιβεβαιωθεί η επιλογή του ασθενούς, θα του εμφανιστεί μήνυμα στην εφαρμογή ότι μπορεί να χρησιμοποιήσει το κύριο μέρος της εφαρμογής.
Η εφαρμογή σέβεται τα προσωπικά στοιχεία των ασθενών και για αυτό χρησιμοποιείται αποκλειστικά από το περιβάλλον του νοσοκωμείου και μόνο (γιατροί, νοσκομοοι κ.α.).

Ανάλυση Κύριου Μέρους:
(Θα χρησιμοποιηθούν fragments για κάθε λειτουργία ή κουμπιά, δεν έχει αποφασισθεί ακόμα αυτό αλλά δεν είναι κάτι το ιδιαίτερο)
-Η αρχική οθόνη θα περιέχει τις βασικές πληροφορίες του ασθενούς:
    Όπως: Ονοματεπώνυμο, Ημερομηνία Γέννησης, Διεύθυνση, Τηλέφωνο/α, Ημερομηνία Εισαγωγής, Αιτία Εισαγωγής

-Σε επόμενη οθόνη θα περιέχονται τα τρέχοντα φάρμακα του ασθενούς με τις απαραίτητες πληροφορίες
    Όπως: Όνομα φάρμακος, δοσολογία, λόγος που δόθηκε αυτό το φάρμακο, όνομα γιατρού που το έδωσε.

-Έπειτα, έχουμε την οθόνη των εξετάσεων. Εδώ πέρα ο γιατρός μπορεί να εισάγει τις εξετάσεις που έγιναν και τα αποτελέσματα τους.
    Και εδώ θα καταγράφεται το όνομα του γιατρού που τις εισήγαγε.

-Έπόμενη οθόνη είναι του ιστορικού. Εδώ παρουσιάζονται όλες οι αλλαγές κατά χρονική σειρά. Αλλαγές στα φάρμακα, εισαγωγή νέων εξετάσεων, δημιουργία σημειώσεων
    και οτιδήποτε έχει να κάνει με εισαγωγή,διαγραφή και τροποποίηση στοιχείων.

-Στην συνέχεια, προβάλλεται σε μια οθόνη το ιστορικό εισαγωγής του ασθενούς στο νοσκομείο. Δηλαδή αν και πότε είχε ξαναεισαχθεί στο παρελθον ο ασθενής

-Σε άλλη οθόνη, θα προβάλλονται οι σημειώσεις των γιατρών και του νοσκομειακού προσωπικού. Μπορούν εδώ και οι δυο να αφήσουν σημειώσεις είτε για να εξυπηρετήσουν τον εαυτό τους είτε τους άλλους

-Επίσης , υπάρχει και chat room για την άμεση επικοινωνία μεταξύ εκείνων που είναι υπεύθυνοι για τον ασθενή.


Διευκρινίσεις:
-Κατά την εγγραφή,θα πρέπει να επιλέξει ο χρήστης αν είναι γιατρός ή νοσοκόμος/νοσοκόμα
-Αλλαγές σε οτιδήποτε μέσα στην κύρια εφαρμογή μπορεί να κάνει μόνο ο γιατρός. Το νοσοκομειακό προσωπικό
μπορεί μόνο να προβάλει τις πληροφορίες αυτές χωρίς να έχει δικαίωμα τροποποίησης, αλλά μπορεί να αφήσει σημειώσεις και να χρησιμοποιήσει το chat room

Η Υλοποίηση των βάσεων δεδομένων θα γίνει με Firebase.
