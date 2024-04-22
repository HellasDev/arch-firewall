# Εργαλεία Διαχείρισης Συστήματος για Arch Linux

Αυτό το repository περιέχει ένα σετ από εργαλεία αυτοματισμού για τη διαχείριση του συστήματος Arch Linux. Τα εργαλεία περιλαμβάνουν scripts για την ενημέρωση του συστήματος, τον καθαρισμό του διαχειριστή πακέτων, τη διαχείριση του χώρου στον δίσκο και την ασφάλεια.

## Περιεχόμενα
- [Εκτέλεση του ενιαίου script](#εκτέλεση-του-ενιαίου-script)
  
- [Ενημέρωση του συστήματος](#ενημέρωση-του-συστήματος)
- [Καθαρισμός του διαχειριστή πακέτων](#καθαρισμός-του-διαχειριστή-πακέτων)
- [Καθαρισμός του δίσκου](#καθαρισμός-του-δίσκου)
- [Διαχείριση χώρου στον δίσκο](#διαχείριση-χώρου-στον-δίσκο)
- [Ενεργοποίηση της ασφάλειας](#ενεργοποίηση-της-ασφάλειας)

# Εκτέλεση του ενιαίου script

Το ενιαίο script `system_management.sh` εκτελεί όλες τις παρακάτω λειτουργίες αυτόματα.
```
./system_management.sh
```

# Ενημέρωση του συστήματος

Το script `update_system.sh` εκτελεί την ενημέρωση του συστήματος με την τελευταία έκδοση των πακέτων.

```
./update_system.sh
```

# Καθαρισμός του διαχειριστή πακέτων
Το script clean_packages.sh καθαρίζει τον διαχειριστή πακέτων από τα παλιά πακέτα που δεν χρειάζονται πλέον.
```
./clean_packages.sh
```

# Καθαρισμός του δίσκου
Το script clean_disk.sh καθαρίζει τον δίσκο από τα προσωρινά αρχεία και τα cache.
```
./clean_disk.sh
```

# Διαχείριση χώρου στον δίσκο
Το script disk_usage.sh ελέγχει τη χρήση του δίσκου.
```
./disk_usage.sh
```

# Ενεργοποίηση της ασφάλειας
Το script enable_ufw.sh ενεργοποιεί και ξεκινάει το Uncomplicated Firewall (ufw).
```
./enable_ufw.sh
```

# Εκτέλεση
1. Κλωνοποιήστε το repository: git clone `https://github.com/HellasDev/system-management.git`
2. Μεταβείτε στον κατάλογο του repository:  `cd system-management`
3. Δώστε δικαιώματα εκτέλεσης στο script:  `chmod +x system_management.sh`
4. Εκτελέστε το script:  `./system_management.sh`

## Καλή χρήση!!
