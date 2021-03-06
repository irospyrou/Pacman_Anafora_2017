<p align="center">
   <img src="https://user-images.githubusercontent.com/15046396/26847816-0a44b994-4b07-11e7-839c-3be1c05c1757.png">
</p>

# Δημιουργία Pacman

*	**Ονοματεπώνυμο:** Ηρώ Σπύρου
*	**Αριθμός Μητρώου:** Π2014120
*	**[Προσωπικό αποθετήριο κώδικα](https://github.com/irospyrou/pacman "Iro's Repository")**
*	**[Εκτελέσιμο](https://irospyrou.github.io/pacman/ "Iro's Pacman")**

## Σύνοψη
Η παρούσα τελική αναφορά δημιουργήθηκε από την Ηρώ Σπύρου με αριθμό μητρώου Π2014120 για το μάθημα Τεχνολογία Λογισμικού του ΣΤ' εξαμήνου στο ακαδημαϊκό έτος 2016-2017.

Στόχος της εργασίας είναι η δημιουργία μίας παραλλαγής του παιχνιδιού Pacman σε HTML5, με χρήση της βιβλιοθήκης Phaser. 

Αρχικά, έγινε αλλαγή του βασικού χαρακτήρα του Pacman, σχεδιάστηκε μία νέα πίστα και αντικαταστάθηκαν τα dots. 

Στη συνέχεια, έγινε προσθήκη ήχων, score, ζωών και bonus.

Έπειτα, προστέθηκαν εχθροί, η δυνατότητα αντιμετώπισής τους και χρόνος.

Τέλος, πρόσθεσα μία εικόνα background και μερικούς ακόμα ήχους.

## Aρχικός σχεδιασμός εφαρμογής
### Προτεινόμενες αλλαγές:
  *	Αντί για τον Pacman χρησιμοποίησε έναν άλλο χαρακτήρα για πρωταγωνιστή του παιχνιδιού.
  *	Αντί ο πρωταγωνιστής να μαζεύει μόνο dots θα μπορούσε να μαζεύει διάφορα αντικείμενα (κέρματα, λουλούδια, φρούτα κτλ).
  *	Δημιούργησε μια νέα πίστα για το παιχνίδι χρησιμοποιώντας το Tiled.

### Υλοποίηση:
  * Aρχικά, επέλεξα να αντικαταστήσω τον χαρακτήρα του Pacman με τον χαρακτήρα του Mario.
  <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26546513/02e08bd2-4473-11e7-91cb-042165d5378f.png">
  </p>
  
  * Πλέον, ο πρωταγωνιστής του παιχνιδιού δεν μαζεύει dots, αλλά μαζεύει κέρματα (coins), όπως κάνει και στο αυθεντικό παιχνίδι του Mario.
  <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560502/c2e5d33c-44bf-11e7-8e16-c0043c238d32.png">
  </p>
  
  * Τέλος, δημιούργησα μια νέα πίστα παιχνιδιού, με χρήση του Tiled, βασισμένη στην πίστα που υπήρχε στον φάκελο assets.
  <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560518/f59beaaa-44bf-11e7-83cf-3e18dc0f3e4a.png">
  </p>
  
### Αποτέλεσματα:
<p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560529/132fde32-44c0-11e7-89b1-0f2a0aad65e8.png">
</p> 

## Τελικό προσχέδιο έργου για σχολιασμό και βελτιώσεις 
### Προτεινόμενες αλλαγές:
  * Προσθήκη αντικειμένου που εμφανίζεται και μετά από κάποιο χρονικό διάστημα εξαφανίζεται.
  * Προσθήκη score, bonus και ζωών.
  * Προσθήκη ήχων.
  
### Υλοποίηση:
  * Αρχικά, πρόσθεσα στην κάτω αριστερή γωνία ένα μανιτάρι, το οποίο εξαφανίζεται μετα από ορισμένο χρονικό διάστημα.
  * Στην συνέχεια πρόσθεσα score, το οποίο αυξάνεται κατά ένα κάθε φορά που ο Mario συλλέγει ένα κέρμα. 
  * Τέλος, πρόσθεσα τα bonus, τα οποία συμβολίζονται από μανιτάρια στην πίστα του παιχνιδιού, με τα οποία σε επόμενο παραδοτέο θα μπορεί να τρώει τους εχθρούς που θα προστεθούν. Όρισα η τιμή του Bonus να αυξάνεται κατά 10 ανά μανιτάρι.
  <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560553/3b2674a0-44c0-11e7-91be-b0ee16d21c16.png">
  </p>
  
  * Επιπλέον έχουν προστεθεί 3 ζωές, που συμβολίζονται με αστέρια, οι οποίες θα χάνονται αν κάποιος εχθρός φάει τον Mario.
  <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560574/69f4f3ba-44c0-11e7-83a5-142133723cc7.png">
  </p>
  
  * Τέλος, έχω προσθέσει το theme song του Mario, έναν ήχο να αναπαράγεται όταν ο παίκτης συλλέγει νομίσματα και έναν ξεχωριστό ήχο για όταν συλλέγει μανιτάρια.

### Αποτελέσματα:
 <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26560587/851797ec-44c0-11e7-8147-d3cacdff8ffe.png">
 </p>

## Τελική αναφορά και έργο
### Προτεινόμενες αλλαγές:
  * Προσθήκη εχθρών.
  * Αντιμετώπιση εχθρών με την συλλογή του κατάλληλου αντικειμένου.
  * Δυνατότητα teleport για τον πρωταγωνιστή σε συγκεκριμένα σημεία της πίστας.

### Υλοποίηση:
  * Αρχικά, πρόσθεσα τρείς εχθρούς. Συγκεκριμένα τα Goomba που είναι και οι εχθροί του Mario στο αυθεντικό παιχνίδι. Αν ο χαρακτήρας έρθει σε επαφή με κάποιον από τους εχθρούς, του αφαιρείται μία ζωή.
  <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26826443/d8a3340a-4ac1-11e7-98bd-1ac6b6604584.png">
  </p>
  
  * Πλέον, με την συλλογή των μανιταριών ο Mario αποκτά την δυνατότητα να γίνεται ανίκητος και να μπορεί να αντιμετωπίσει τους εχθρούς του για το χρονικό διάστημα των 10 δευτερολέπτων.
  * Πρόσθεσα σημεία στα οποία ο χαρακτήρας του παιχνιδιού θα κάνει teleport προς την θέση εκκίνησης του χαρακτήρα, τα σημεία αυτά συμβολίζονται με μία πόρτα, όπως στο αυθεντικό παιχνίδι του Mario. 
  <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26826670/8f7223ee-4ac2-11e7-99d6-d4b7cc2091de.png">
  </p>
  
  * Επιπροσθέτως, έγινε προσθήκη χρόνου στο παιχνίδι.
  * Επιπλέον, προστέθηκε και μία εικόνα background.
  * Τέλος, αν ο παίκτης χάσει εμφανίζεται στην οθόνη κατάλληλο μήνυμα "Game Over". 
  <p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26826785/f824a16e-4ac2-11e7-93b1-f1694d473282.png">
  </p>

### Αποτελέσματα:
<p align="center">
    <img src="https://cloud.githubusercontent.com/assets/15046396/26827004/e04428d4-4ac3-11e7-9c28-84e4e2f743a6.png">
</p>
