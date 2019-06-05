# Συνεργατικές εφαρμογές

*  Ονοματεπώνυμο: **Ιάσων - Ιωάννης Παπαναγιώτου**
*  Αριθμός Μητρώου: **ΠΚΜ201801**

***
_Σχετικά με τα παραδοτέα 1Α, 1Γ, 2ΑΒ_:

Το branch gh-pages περιέχει τον αρχικό κώδικα της σελίδας του βιβλίου και τις επιπλέον αλλαγές για την υλοποίηση των παραδοτέων. Λόγω του [jekyll bug](https://github.com/mibook/gr/issues/55) δημιουργήθηκε ένα branch στο οποίο έχουν γίνει επιπλέον αλλαγές στον κώδικα της σελίδας του βιβλίου έτσι ώστε να μπορεί να γίνεται build το site (επιλέχθηκε το συγκεκριμένο branch στα settings-github pages).
***

## Παραδοτέο Α (Συπλήρωση Βιογραφικού)

Για την υλοποίηση του συγκεκριμένου παραδοτέου, αρχικά πραγματοποιήθηκε fork του https://github.com/sharu725/online-cv από τα προτεινόμενα παραδείγματα. Στη συνέχεια πραγματοποιήθηκε η δημιουργία των branches develop, gh-pages.  Χρησιμοποιήθηκε το branch develop για τις απαραίτητες αλλαγές στο `data.yml` και `_config.yml`. Με την ολοκλήρωση των αλλαγών πραγματοποιήθηκε  Merge pull request από το branch develop στο branch gh-pages.
*  [Η σελίδα του βιογραφικού](https://c18papa.github.io/c18papa-cv/)
*  [Αποθετήριο του κώδικα του βιογραφικού](https://github.com/c18papa/c18papa-cv/tree/gh-pages)

## Παραδοτέο 1Α

Για την υλοποίηση του συγκεκριμένου παραδοτέου, αρχικά πραγματοποιήθηκε fork του https://github.com/mibook/gr. Στη συνέχεια έγινε η δημιουργία των νέων αρχείων .md στο φάκελο `_gallery` και η προσθήκη των αντίστοιχων νέων εικόνων στο φάκελο `images`. Επίσης έγιναν μικρές αλλαγές στο αρχείο _config.yml ώστε να μπορέσουμε να δούμε πως εμφανίζονται οι εικόνες στη σελίδα.

*  [Η σελίδα του βιβλίου με τις επιπλέον εικόνες](https://c18papa.github.io/gr/)
*  [Αποθετήριο του κώδικα του παραδοτέου](https://github.com/c18papa/gr)
*  [Εικόνα 1](https://github.com/c18papa/gr/blob/gh-pages/_gallery/tux.md)
*  [Εικόνα 2](https://github.com/c18papa/gr/blob/gh-pages/_gallery/beastie.md)
*  [Εικόνα 3](https://github.com/c18papa/gr/blob/gh-pages/_gallery/defcon.md)
*  [Εικόνα 4](https://github.com/c18papa/gr/blob/gh-pages/_gallery/amiga.md)
*  [Εικόνα 5](https://github.com/c18papa/gr/blob/gh-pages/_gallery/esp8266.md)

## Παραδοτέο 1Α*2

*  [Εικόνα 1](https://github.com/c18papa/gr/blob/gh-pages/_gallery/vi.md)
*  [Εικόνα 2](https://github.com/c18papa/gr/blob/gh-pages/_gallery/slack.md)
*  [Εικόνα 3](https://github.com/c18papa/gr/blob/gh-pages/_gallery/wireframes.md)
*  [Εικόνα 4](https://github.com/c18papa/gr/blob/gh-pages/_gallery/appinventor.md)
*  [Εικόνα 5](https://github.com/c18papa/gr/blob/gh-pages/_gallery/google_duplex.md)

## Παραδοτέο 1Γ (μια νέα βιογραφία)

Για την υλοποίηση του συγκεκριμένου παραδοτέου, πραγματοποιήθηκε δημιουργία νέων αρχείων .md στο φάκελο `_biography` και η προσθήκη των αντίστοιχων εικόνων (συμπεριλαμβανομένων thumbnails) στο φάκελο `images`.

*  [Αποθετήριο του κώδικα του παραδοτέου](https://github.com/c18papa/gr)
*  [alan-turing.md](https://github.com/c18papa/gr/blob/gh-pages/_biography/alan-turing.md)
*  [bio-turing.md](https://github.com/c18papa/gr/blob/gh-pages/_biography/bio-turing.md)

## Παραδοτέα 2ΑΒ

Για την υλοποίηση των συγκεκριμένων παραδοτέων, αρχικά πραγματοποιήθηκε δημιουργία νέου αρχείου `twitter.html` στο φάκελο `_includes` που περιέχει τμήμα κώδικα για την εμφάνιση twitter stream στη σελίδα του βιβλίου και παραμετροποιήθηκε το αρχείο `index.md` ώστε να γίνεται include. Επιπλέον, προστέθηκε το αρχείο [social-share.html](https://github.com/mmistakes/minimal-mistakes/blob/master/_includes/social-share.html) στο φάκελο `_includes` και έγινε επεξεργασία του αρχείου `_config.yml` όπου προστέθηκε ο λογαριασμός του twitter και η οδηγία `share: true`. Με τον τρόπο αυτό υπάρχει δυνατότητα [sharing σε Twitter, Facebook, LinkedIn](https://raw.githubusercontent.com/c18papa/blob/master/share_buttons.png).

*  [Αποθετήριο του κώδικα του παραδοτέου](https://github.com/c18papa/gr)
*  [Η σελίδα του βιβλίου με twitter stream](https://c18papa.github.io/gr/)
*  [Ενδεικτική σελίδα του βιβλίου με social sharing](https://c18papa.github.io/gr/gallery/architecture-model/)
*  [Λογαριασμός Twitter](https://twitter.com/c18papa)
*  [Στατιστικά λογαριασμού Twitter (*ενημέρωση 19/5/2019*)](https://github.com/c18papa/blob/blob/master/tweet_activity_metrics_c18papa.csv)

## Οδηγός σπουδών τμήματος

Για την υλοποίηση του συγκεκριμένου παραδοτέου, πραγματοποιήθηκε fork του αποθετηρίου `ioniodi/study-guide` και στη συνέχεια δημιουργία του branch `201801-develop`. Δημιουργήθηκαν και επιλύθηκαν τα ακόλουθα Issues μέσω αιτημάτων ενσωμάτωσης:

* https://github.com/ioniodi/study-guide/issues/14
