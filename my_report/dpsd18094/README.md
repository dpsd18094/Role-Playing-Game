# Δημιουργία παιχνιδιού RPG
## Σύνοψη

Το συγκεκριμένο έγγραφο  αποτελεί πρώτο παραδοτέο της εξαμηνιαίας εργασίας του μαθήματος Ψηφιακά Παιχνίδια και Παιγνιώδης Μάθηση.

Σκοπός της εργασίας είναι η δημιουργία ενός rpg παιχνιδιού ακολουθώντας το tutorial της unity "Ruby's Adventure: 2D Beginner" χρησιμοποιώντας 
assets από το διαδίκτυο.

### Στοιχεία

*  Ονοματεπώνυμο: **Μαρίνα Πόγκα**
*  Αριθμός Μητρώου: **dpsd18094**
*  Θέμα εργασίας **"Δημιουργία rpg παιχνιδιού"**
*  Προσωπικό repository: [Link repository](https://github.com/dpsd18094/Role-Playing-Game)
*  Link για το εκτελέσιμο: [Link Εκτελέσιμου](https://dpsd18094.github.io/Role-Playing-Game/)


### Πρώτο Παραδοτέο (20%) - 11/11/2022

#### Χαρακτήρας
Το πρώτο παραδοτέο αφορά το `World Building`. Ξεκίνησα ακολουθώντας το "Get started with Ruby's Adventure" εισάγωντας την πρωταγωνίστρια μας (sprite), την οποία σχεδίασα στο procreate σε μέγεθος 3000*3000px για να μην χαλάσει η ποιότητα στο Unity και μετά έβαλα την αρχική κίνηση του χαρακτήρα (keyboard input) χωρίς animation.

![Witchy_Girl (1)](https://user-images.githubusercontent.com/115794300/201360166-4d040d25-6355-41dc-9f75-fc9f910e5db2.png)
#### Δημιουργία Κόσμου
Μετά έβαλα την αρχική κίνηση του χαρακτήρα (keyboard input) χωρίς animation. Έπειτα, ακολουθώντας το παρακάτω βίντεο (αναφορές) πρόσθεσα τα tilemaps, τα οποία βρήκα έτοιμα από το διαδίκτυο και δημιούργησα την πρώτη πίστα του παιχνιδιού. Τέλος, πήρα έτοιμα assets και διακόσμησα την πίστα ακολουθώντας το tutorial "Decorating the World" μετατρέποντας τα sprites σε prefabs. Όλα τα tilemaps και τα assets βρίσκονται στις αναφορές.

#### Η ολοκληρωμένη πίστα:

![Map](https://user-images.githubusercontent.com/115794300/201358658-228db56a-1d82-4218-a8c1-7b5a910562ac.png)

### Δεύτερο Παραδοτέο (20%) - 16/12/2022

#### Κίνηση αποκλεισμού/ Colliders
Ακολουθώντας ξανά το tutorial της Ruby, με την προσθήκη ενός rigidbody, απενεργοποίησα την βαρύτητα. Μετά πρόσθεσα τα colliders (box collider 2d) στην πρωταγωνίστρια και στα υπόλοιπα assets και tilemaps του παιχνιδιού, όπου αυτό χρειαζόταν. Διορθώνοντας τα μεγέθη και προσθέτοντας τον αντίστοιχο κώδικο το βήμα αυτό ολοκληρώθηκε. 

![Screenshot 2022-12-16 130014](https://user-images.githubusercontent.com/115794300/208084967-488ca416-edf8-4d82-a9d5-75cc8f5a1ba8.png)![Screenshot 2022-12-16 130047 (1)](https://user-images.githubusercontent.com/115794300/208086126-bf8478dc-98a5-4916-bc89-97d1c76cf165.png)![Screenshot 2022-12-16 130201](https://user-images.githubusercontent.com/115794300/208085876-49318df5-e00a-4279-8b2f-3428bb744b23.png)

#### Συλλεκτικά Αντικείμενα 
Μέσω του tutorial η πρωταγωνίστρια έχει πλέον max health 5. Το αντικείμενο που θα κάνει healing έιναι ένα `health potion` για να ταιριάζει με την θεματική του κόσμου, που θα μπορεί να συλλέγει ο παίκτης από τον χάρτη. Σε επόμενο στάδιο θα προστεθούν και άλλα collectibles (πιθανότατα κάποιο έξτρα boost στην δεύτερη πίστα).

![Health Potion 1 (1)](https://user-images.githubusercontent.com/115794300/208090557-4f22a543-7403-4c75-9d8a-dc2690a76c1e.png)

#### Εχθροί και Damage Zones
Οι εχθροί που χρησιμοποιήθηκαν είναι κορμοί δέντρων και τα damage zones είναι earthworms. Τα assets βρέθηκαν στο διαδίκτυο (βλέπε αναφορές).

![enemy_tree](https://user-images.githubusercontent.com/115794300/208092808-bd925118-698e-406b-b3c4-f8cca2e3ec62.png)![Sandworm trap - Level 1 (1)](https://user-images.githubusercontent.com/115794300/208092820-af443fbe-c27e-4194-af8f-54d9cb6fe58c.png)

Ο λόγος που επιλέγχθηκαν είναι κυρίως για την αισθητική και εφόσον υπάρχει μαγεία σε αυτόν τον κόσμο πιθανότατα κάποιος τα ελέγχει ώστε να επιτίθονται στην πρωταγωνίστρια.
Επιπλέον σε αυτό το βήμα, ρυθμίστηκε η πρωταγωνίστρια ώστε να χάνει 1 health όταν ακουμπάει τους εχρούς και τις ζώνες κινδύνου.








## Αναφορές

https://www.youtube.com/watch?v=DTp5zi8_u1U (video tutorial for tilesets)
https://byaqua.itch.io/shabby-cottage (nature and decorating assets)
https://opengameart.org/content/whispers-of-avalon-grassland-tileset (cliffs, water and ground)
https://ansimuz.itch.io/tiny-rpg-town (house)
