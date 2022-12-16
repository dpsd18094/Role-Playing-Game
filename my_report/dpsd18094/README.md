# Δημιουργία παιχνιδιού RPG
## Σύνοψη

Το συγκεκριμένο έγγραφο  αποτελεί δεύτερο παραδοτέο της εξαμηνιαίας εργασίας του μαθήματος Ψηφιακά Παιχνίδια και Παιγνιώδης Μάθηση.

Σκοπός της εργασίας είναι η δημιουργία ενός rpg παιχνιδιού ακολουθώντας το tutorial της unity "Ruby's Adventure: 2D Beginner" χρησιμοποιώντας 
assets από το διαδίκτυο.

Το παιχνίδι ξεκινάει με μια μάγισσα που ζει στο δάσος, όταν ξαφνικά άρχισαν στοιχεία του δάσους να γίνονται επιθετικά. Η πρωταγωνίστρια μας προσπαθεί να βρει τον λόγο που προκύπτει αυτό ώστε να επαναφερθεί το δάσος στην αρχική του κατάσταση.

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

#### Sprite Animations

Μέσω του animation, του animator και των αντίστοιχων scripts δημιουργήθηκαν οι εξίσου κινήσεις μέσα στο παιχνίδι:

`Πρωταγωνίστρια`

Idle animation

![IMG_0330](https://user-images.githubusercontent.com/115794300/208099193-e8c3a734-3a11-4612-b04a-9a53cfeb0692.GIF)
Walking animation

![IMG_0233](https://user-images.githubusercontent.com/115794300/208099213-0d85914f-8124-4fb4-b394-f74b9e87b54f.GIF)

`Εχθροί και Damage Zones`

Walking

![tronchungol](https://user-images.githubusercontent.com/115794300/208099515-712642bf-1b54-49a1-8604-6c1fc0f013a4.png)

Damage

![damageenemy](https://user-images.githubusercontent.com/115794300/208099697-8f9c6637-5486-4347-a36e-b8532c2314a9.png)

Earthworm

![Sandworm trap - Level 1](https://user-images.githubusercontent.com/115794300/208099813-78495121-63ac-42b9-99ab-2a4934fc2cb3.png)

`Projectile`

![right](https://user-images.githubusercontent.com/115794300/208100388-7e58d09a-6845-480f-958d-979efb632af0.png)

`Fire Torch`

![burning_loop_1](https://user-images.githubusercontent.com/115794300/208100580-46c0929d-02f1-4541-9041-47a3f20b44c8.png)

`Health Potion`

![Health Potion 1 (1)](https://user-images.githubusercontent.com/115794300/208101077-898f59e1-63a9-47ed-84c0-192c028290c9.png)![Health Potion 2 (1)](https://user-images.githubusercontent.com/115794300/208101150-093b23f9-a13c-43a7-b4f2-55f2e3ce508f.png)![Health Potion 3](https://user-images.githubusercontent.com/115794300/208101202-6893a538-a333-49e1-a333-2805dfa243e5.png)![Health Potion 4](https://user-images.githubusercontent.com/115794300/208101236-9c4bf0b0-1dcb-42e8-8ad8-9cc19bb2cf0c.png)![Health Potion 5](https://user-images.githubusercontent.com/115794300/208101331-ccd7191e-d46e-46d5-866a-9f5145808b74.png)![Health Potion 6](https://user-images.githubusercontent.com/115794300/208101342-1355aa79-f85a-450c-9403-33f2faa8f195.png)

#### Projectiles

Ακολουθώντας τα βήματα του unity tutorial η πρωταγωνίστρια μας πετάει projectile σε μορφή φωτιάς ώστε να επιτίθεται τους εχθρούς, όπως είδαμε πιο πάνω.

#### Camera Fix

Σε αυτό το βήμα εισήγαγα το CineMachine και διόρθωσα την κίνηση της κάμερας ώστε να ακολουθεί τον χαρακτήρα μας.

![Screenshot 2022-12-16 150235](https://user-images.githubusercontent.com/115794300/208106225-5eed35fd-5222-4587-ac1c-83dbc6311223.png)

#### Η ολοκληρωμένη πίστα:

![Screenshot 2022-12-16 150341](https://user-images.githubusercontent.com/115794300/208106329-b8055206-5c9f-4dbd-86bc-4080e7b7dc95.png)


## Αναφορές

https://www.youtube.com/watch?v=DTp5zi8_u1U (video tutorial for tilesets)
https://byaqua.itch.io/shabby-cottage (nature and decorating assets)
https://opengameart.org/content/whispers-of-avalon-grassland-tileset (cliffs, water and ground)
https://ansimuz.itch.io/tiny-rpg-town (house)

