<p align="center">
<b>Δημιουργία Pacman</b>
</p>

*	**Ονοματεπώνυμο:** Ηρώ Σπύρου
*	**Αριθμός Μητρώου:** Π2014120
*	**[Προσωπικό αποθετήριο κώδικα](https://github.com/irospyrou/pacman "Iro's Repository")**
*	**[Εκτελέσιμο](https://irospyrou.github.io/pacman/ "Iro's Pacman")**

## Σύνοψη
Η παρούσα τελική αναφορά δημιουργήθηκε από την Ηρώ Σπύρου με αριθμό μητρώου Π2014120 για το μάθημα Τεχνολογία Λογισμικού του ΣΤ' εξαμήνου στο ακαδημαϊκό έτος 2016-2017.

Στόχος της εργασίας είναι η δημιουργία μίας παραλλαγής του παιχνιδιού Pacman σε HTML5, με χρήση της βιβλιοθήκης Phaser. 

Αρχικά, έγινε αλλαγή του βασικού χαρακτήρα του Pacman, σχεδιάστηκε μία νέα πίστα και αντικαταστάθηκαν τα dots. 

Στη συνέχεια, έγινε προσθήκη ήχων, score, ζωών και bonus.

Τέλος, πρόσθεσα και μία εικόνα background.

## Aρχικός σχεδιασμός εφαρμογής
### Προτεινόμενες αλλαγές:
  *	Αντί για τον Pacman χρησιμοποίησε έναν άλλο χαρακτήρα για πρωταγωνιστή του παιχνιδιού.
  *	Αντί ο πρωταγωνιστής να μαζεύει μόνο dots θα μπορούσε να μαζεύει διάφορα αντικείμενα (κέρματα, λουλούδια, φρούτα κτλ).
  *	Δημιούργησε μια νέα πίστα για το παιχνίδι χρησιμοποιώντας το Tiled.

### Υλοποίηση:
  * Aρχικά, αντικατέστησα τον χαρακτήρα του Pacman με τον χαρακτήρα του Mario.
  <p align="left">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26546513/02e08bd2-4473-11e7-91cb-042165d5378f.png">
  </p>
  * Πλέον, ο πρωταγωνιστής του παιχνιδιού δεν μαζεύει dots, αλλά μαζεύει κέρματα (coins), όπως κάνει και στο αυθεντικό παιχνίδι του Mario.
  <p align="left">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560502/c2e5d33c-44bf-11e7-8e16-c0043c238d32.png">
  </p>
  * Τέλος, δημιούργησα μια νέα πίστα παιχνιδιού, με χρήση του Tiled, βασισμένη στην πίστα που υπήρχε στον φάκελο assets.
  <p align="left">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560518/f59beaaa-44bf-11e7-83cf-3e18dc0f3e4a.png">
  </p>
  
### Αποτέλεσματα:
<p align="left">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560529/132fde32-44c0-11e7-89b1-0f2a0aad65e8.png">
</p> 

## Τελικό προσχέδιο έργου για σχολιασμό και βελτιώσεις 
### Προτεινόμενες αλλαγές:
  * Προσθήκη αντικειμένου που εμφανίζεται και μετά από κάποιο χρονικό διάστημα εξαφανίζεται.
  * Προσθήκη score, bonus και ζωών.
  * Προσθήκη ήχων.
  
### Υλοποίηση:
  * Πρόσθεσα στην κάτω αριστερή γωνία ένα μανιτάρι, το οποίο εξαφανίζεται μετα από ορισμένο χρονικό διάστημα.
  * Πρόσθεσα score, το οποίο αυξάνεται κατά ένα κάθε φορά που ο Mario τρώει ένα κέρμα. 
  * Πρόσθεσα επίσης bonus, τα οποία συμβολίζονται από μανιτάρια στην πίστα του παιχνιδιού, με τα οποία σε επόμενο παραδοτέο θα μπορεί να τρώει τους εχθρούς που θα προστεθούν.
  <p align="left">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560553/3b2674a0-44c0-11e7-91be-b0ee16d21c16.png">
  </p>
  * Επιπλέον έχουν προστεθεί 3 ζωές, τις οποίες συμβολίζω με αστέρια, οι οποίες θα χάνονται αν κάποιος εχθρός που θα προστεθεί φάει τον Mario.
  <p align="left">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560574/69f4f3ba-44c0-11e7-83a5-142133723cc7.png">
  </p>
  * Τέλος, έχω προσθέσει το theme song του Mario, έναν ήχο όταν τρώει νομίσματα και έναν ξεχωριστό ήχο για όταν τρώει μανιτάρια.

### Αποτελέσματα:
 <p align="left">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560587/851797ec-44c0-11e7-8147-d3cacdff8ffe.png">
 </p>
