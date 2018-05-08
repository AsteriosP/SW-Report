<img src="https://user-images.githubusercontent.com/18286552/39784957-0596ed20-5323-11e8-94c7-63ad78830152.jpg" height="100" width="100">

# Μάθημα: Τεχνολογία Λογισμικού         


#### Ονοματεπώνυμο: Αστέριος Παπαμιχαήλ

#### Αριθμός Μητρώου: Π2015059

## Περιεχόμενα

[Links](#Links)

[Εισαγωγή](#Εισαγωγή)

[Μέθοδος-Τεχνικές](#Μέθοδος-Τεχνικές)

[Αποτελέσματα](#Αποτελέσματα)

[Κεντρικό Αποθετήριο](#Κεντρικό-Αποθετήριο)




## Links
[Εκτελέσιμο Παράδειγμα στο gh-pages](https://asteriosp.github.io/D3js-uk-political-donations/)

[Αποθετήριο του κώδικα](https://github.com/AsteriosP/D3js-uk-political-donations)

[Ήχος των κουμπιών των ομαδοποιήσεων των δεδομένων](https://freesound.org/people/altemark/sounds/35415/)

[Βιβλιοθήκη αναπαραγωγής ομιλίας από κείμενο](https://responsivevoice.org/)

[Javascript - HTML DOM](https://www.w3schools.com/js/js_htmldom.asp)

[Buttons Sound με Javascript](https://stackoverflow.com/questions/9419263/playing-audio-with-javascript)

[Zoom on Hover](https://www.w3schools.com/howto/howto_css_zoom_hover.asp)

[Καινούριο γράφημα](http://blockbuilder.org/renecnielsen/9904735)

### Links από τις εικόνες του πρώτου παραδοτέου 

[Scottish Parliament](https://www.facebook.com/scottishparliament/)

[House of Commons](http://www.ipex.eu/IPEXL-WEB/parliaments/institution/ukcom.do)

[House of Lords](https://commons.wikimedia.org/wiki/File:House_of_Lords.svg)

[Australian Labor Party](https://en.wikipedia.org/wiki/Australian_Labor_Party)

Sir Arthur Rowbotham





## Εισαγωγή 
Ο σκοπός τη εργασίας του μαθήματος είναι η επέκταση ιστοσελίδας που οπτικοποιεί στατιστικά στοιχεία δωρεών που έχουν γίνει σε πολιτικά κόμματα της Μεγάλης Βρετανίας με χρήση της βιβλιοθήκης της Javascript: D3 και εξοικείωση με αυτήν. Εκτός από την προαναφερόμενη βιβλιοθήκη χρειάστηκαν γνώσεις από την CSS οπού είναι γλώσσα εμφάνισης και κρίνεται απαραίτητη για μία εμφανίσιμη ιστοσελίδα. Επίσης είναι σημαντικό να σημειωθεί ότι η ιστοσελίδα που καλούμαστε να χρησιμοποιήσουμε έχει γίνει αντίγραφο από το κεντρικό αποθετήριο του κώδικα.


## Μέθοδος-Τεχνικές
Η μέθοδος που ακολουθήθηκε έχει να κάνει αρχικά με τις αλλαγές που πρέπει να γίνουν στο κεντρικό αποθετήριο του κωδικά. Αρχικά έγινε αντιγραφή του αποθετηρίου στο προφίλ μου. Στην συνέχεια  ενεργοποίησα  το Github-pages (gh-pages) και υλοποιήθηκαν τα εξής στο προσωπικό αποθετήριο:
- Έγινε αλλαγή του συνδέσμου για το εκτελέσιμο δηλαδή αφαίρεση του ονόματος του αρχείου.
- Πραγματοποιήθηκε αλλαγή χρωμάτων στις μπάλες του γραφήματος των δεδομένων
- Αναπαραγωγή ήχου σε περίπτωση click στα κουμπιά των ομαδοποιήσεων των δεδομένων.
- Σε περίπτωση κλίκ σε μία μπάλα δωρητή να πραγματοποιείται αναζήτηση στην μηχανή αναζήτησης Google για αυτόν
- Μεγέθυνση του κειμένου σε περίπτωση μετακίνησης του κέρσορα πάνω από αυτό
- Αναπαραγωγή του ονόματος και το ποσό της δωρεάς του δωρητή όταν το ποντίκι βρίσκεται πάνω από μία μπάλα.
- Δημιουργήθηκε ομαδοποίηση των δεδομένων ως προς το ποσό της δωρεάς
- Καταγραφή των εικόνων των δωρητών από όπου πέρασε ο χρήστης
- Ένα διαφορετικό γράφημα όπου οπτικοποιεί τα αρχικά δεδομένα
- Ένα γράφημα όπου οπτικοποιεί διαφορετικά δεδομένα

Το καινούριο γράφημα διαφορετικών δεδομένων οπτικοποιεί τον αριθμό τον οχημάτων ανά κατηγορία οχήματος (βλέπε περιοχές) έπειτα ανά γεωγραφική περιοχή (βλέπε χρώμα) και στην συνέχεια ανά νομό(βλέπε μπάλα).



Και στο κοινό αποθετήριο έγιναν τα εξής:
- [Το αρχείο .csv με τα στοιχεία μου](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo1-Meros2o/participants/2015059.csv)
- Προσθήκη 5 εικόνες δωρητών: 
  1. [Scottish Parliament (71)](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo1-Meros2o/photos/Scottish%20Parliament.ico)
  2. [House of Commons (72)](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo1-Meros2o/photos/House%20of%20Commons.ico) 
  3. [House of Lords (78)](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo1-Meros2o/photos/House%20of%20Lords.ico)
  4. [Australian Labor Party (89)](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo1-Meros2o/photos/Australian%20Labor%20Party.ico)
  5. [Sir Arthur Rowbotham (95)](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo1-Meros2o/photos/Sir%20Arthur%20Rowbotham.ico)
- Τροποποίηση του αρχείου [index.html](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo2-Meros2o/participants/index.html) στο φάκελο participants προκειμένου να εμφανίζονται τα στοιχεία μου με animation.
- [Οπτικοποίηση των χρηστών που συνεισφέρουν στο κεντρικό αποθετήριο του κώδικα](https://github.com/AsteriosP/D3js-uk-political-donations/blob/Paradoteo2-Meros2o/participants/2015059.html)


## Αποτελέσματα

{% include youtubePlayer.html id="_lA_0Bnu1jQ" %}

Επιλέχθηκε βίντεο για τον λόγο ότι παρουσιάζει τις αλλαγές όπου έγιναν και τις κινήσεις από τις μπάλες επίσης τους ήχους της διαδικτυακής εφαρμογής όπου δεν είναι δυνατό να αναπαρασταθεί με τις κινούμενες εικόνες .gif. Είναι σημειωτέο ότι το βίντεο καλύπτει όλα(Εκτός την αναζήτηση από την αρχική οπτικοποίηση για αυτό και προστίθεται gif που το παρουσιάζει) τα ζητούμενα των παραδοτέων που πραγματεύονται το προσωπικό αποθετήριο.

Το κλικ σε κάποια μπάλα ανοίγει ένα νέο παράθυρο με τα αποτελέσματα της αναζήτησης στο google για τον αντίστοιχο δωρητή.

![search](https://user-images.githubusercontent.com/18286552/37308298-419bdc40-2646-11e8-8377-e3ce15c8ff2a.gif)

### Κεντρικό Αποθετήριο
Το animation για το όνομα χρήστη και την εικόνα του Github

![animation](https://user-images.githubusercontent.com/18286552/39784763-417be080-5322-11e8-8f16-381306827a52.gif)

Η σελίδα από τις συνεισφορές του κεντρικού αποθετηρίου του κώδικα

![contributions](https://user-images.githubusercontent.com/18286552/39784865-b64e4a88-5322-11e8-8a25-7dea2e87d04f.png)

# Δικτυογραφία









