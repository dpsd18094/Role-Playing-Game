# Δημιουργία παιχνιδιού RPG
## Σύνοψη

Το συγκεκριμένο έγγραφο  αποτελεί δεύτερο παραδοτέο της εξαμηνιαίας εργασίας του μαθήματος Ψηφιακά Παιχνίδια και Παιγνιώδης Μάθηση.

Σκοπός της εργασίας είναι η δημιουργία ενός rpg παιχνιδιού ακολουθώντας το tutorial της unity "Ruby's Adventure: 2D Beginner" χρησιμοποιώντας 
assets από το διαδίκτυο.

Το παιχνίδι ξεκινάει με μια μάγισσα που ζει στο δάσος, όταν ξαφνικά στοιχεία του δάσους άρχισαν να επιτίθενται. Η πρωταγωνίστρια μας προσπαθεί να βρει τον λόγο που προκύπτει αυτό ώστε να επαναφερθεί το δάσος στην αρχική του κατάσταση.

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
Ακολουθώντας το παρακάτω βίντεο (αναφορές) πρόσθεσα τα tilemaps, τα οποία βρήκα έτοιμα από το διαδίκτυο και δημιούργησα την πρώτη πίστα του παιχνιδιού. Τέλος, πήρα έτοιμα assets και διακόσμησα την πίστα ακολουθώντας το tutorial "Decorating the World" μετατρέποντας τα sprites σε prefabs. Όλα τα tilemaps και τα assets βρίσκονται στις αναφορές.

#### Η ολοκληρωμένη πίστα:

![Map](https://user-images.githubusercontent.com/115794300/201358658-228db56a-1d82-4218-a8c1-7b5a910562ac.png)

### Δεύτερο Παραδοτέο (20%) - 16/12/2022

#### Κίνηση αποκλεισμού/ Colliders
Ακολουθώντας ξανά το tutorial της Ruby, με την προσθήκη ενός rigidbody, απενεργοποίησα την βαρύτητα. Μετά πρόσθεσα τα colliders (box collider 2d) στην πρωταγωνίστρια και στα υπόλοιπα assets και tilemaps του παιχνιδιού, όπου αυτό χρειαζόταν. Διορθώνοντας τα μεγέθη και προσθέτοντας τον αντίστοιχο κώδικα το βήμα αυτό ολοκληρώθηκε. 

![Screenshot 2022-12-16 130014](https://user-images.githubusercontent.com/115794300/208084967-488ca416-edf8-4d82-a9d5-75cc8f5a1ba8.png)![Screenshot 2022-12-16 130047 (1)](https://user-images.githubusercontent.com/115794300/208086126-bf8478dc-98a5-4916-bc89-97d1c76cf165.png)![Screenshot 2022-12-16 130201](https://user-images.githubusercontent.com/115794300/208085876-49318df5-e00a-4279-8b2f-3428bb744b23.png)

#### Συλλεκτικά Αντικείμενα 
Μέσω του tutorial η πρωταγωνίστρια έχει πλέον max health 5. Το αντικείμενο που θα κάνει healing έιναι ένα `health potion` για να ταιριάζει με την θεματική του κόσμου, που θα μπορεί να συλλέγει ο παίκτης από τον χάρτη. 

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

### Τρίτο Παραδοτέο (20%) - 13/01/2023

#### Αλλαγές 

Πριν ξεκινήσω το τελικό παραδοτέο, άλλαξα το projectile και τα damage zones, ώστε να ταιριάζουν περισσότερο στο πλαίσιο του παιχνιδιού. Επίσης έγινε μια μικρή αλλαγή στο animation της δεξιάς και αριστερής κίνησης της πρωταγωνίστριας, ώστε να φαίνεται πιο smooth.

![Explosion 2 SpriteSheet](https://user-images.githubusercontent.com/115794300/211881499-ee4e5a59-c9e6-45fe-80a9-037f55834e05.png)
![Plant](https://user-images.githubusercontent.com/115794300/211881545-f9f238d9-6ea6-41d7-a02a-7f0c3b0cf646.png)

#### Σκορ

Ακολουθώντας βίντεο (αναφορές) πρόσθεσα ένα scoring system και αντίστοιχα collectibles ώστε ο παίκτης να μπορεί να τα συλλέγει από την πίστα. Θα συλλέγει βότανα, καθώς το βρήκα ταιριαστό για την αισθητική και τον χαρακτήρα του παιχνιδιού. Το σύνολο αυτών των συλλεκτικών αντικειμένων είναι 12 (7 στην αρχική και 5 στην τελική πίστα).

#### Particles

Ακολουθώντας τα αντίστοιχα βήματα από το tutorial πρόσθεσα particle effects τοποθετόντας sprites στα δέντρα (για να δηλωθεί η μαγεία που υπάρχει στο δάσος) και στα συλλεκτικά αντικείμενα για το σκορ, ώστε να είναι πιο φανερά στον χάρτη.

![tree_50](https://user-images.githubusercontent.com/115794300/211860050-d8d68f23-6741-4e96-9ed9-2bff775e0912.png)
![Collectivle_50](https://user-images.githubusercontent.com/115794300/211860228-ea271359-2969-485e-a2be-4d694bdc6b08.png)

#### Head Up Display

Ξεκίνησα αυτό το βήμα σχεδιάζοντας το UI του παιχνιδιού για τον δείκτη ζωής και το σκορ του παίκτη στο procrate και έπειτα τα τοποθέτησα στο σύστημα UI του Unity ώστε να φαίνονται στο πάνω μέρος αριστερά της οθόνης του παίκτη.

![Health_1_60](https://user-images.githubusercontent.com/115794300/211862173-e23a9777-6dd8-4994-943e-86034bc49b8a.png)

Επιπλέον, εάν ο χρήστης χάσει όλο το health η πρωταγωνίστρια κάνει respawn στην αρχή του παιχνιδιού.

#### Dialog Raycast 

Στο βήμα αυτό πρόσθεσα έναν npc, την γάτα της πρωταγωνίστριας, που εμφανίζει ένα συγκεκριμένο κείμενο πατώντας το x. Επιπλέον ακολουθώντας τα ίδια βήματα έβαλα μία πινακίδα στον χάρτη της πρώτης πίστας, ώστε να μπορεί να καθοδηγηθεί πιο εύκολα ο παίκτης.

![cat_1_78](https://user-images.githubusercontent.com/115794300/211863580-3b03cf25-834e-46a5-9a7f-53e8666922b1.png)
![sign_78](https://user-images.githubusercontent.com/115794300/211863591-e5c38447-ca11-4cc1-8ebf-808ed5af0c77.png)

#### Teleport

Ακολουθώντας βίντεο, δημιούργησα 2 teleport points στην κάθε πίστα ώστε να γίνει πιο εύκολη η καθοδήγηση στον χάρτη πατώντας T, με αντίστοιχα scripts.

![Στιγμιότυπο οθόνης 2023-01-11 193253](https://user-images.githubusercontent.com/115794300/211877207-a9b139dd-b4ea-4571-9dc1-c4a21773d614.png)

#### Ήχος 

Σε αυτό το βήμα έβαλα ήχο στο παιχνίδι ώστε να είναι πιο immersive. Πρόσθεσα επιπέον ακολουθώντας βίντεο, ένα walking audio που ενεργοποιείται όταν η πρωταγωνίστρια περπατάει.

![audio](https://user-images.githubusercontent.com/115794300/211881066-d95961c8-ca77-40b6-85c4-2c2845267571.png)

#### Δεύτερη Πίστα

Για την δεύτερη πίστα εστίασα στο να κάνω την αισθητική λίγο πιο μουντή, καθώς η πρωταγωνίστρια μπαίνει στην σπηλιά για να αντιμετωπήσει τον εχθρό της, δηλαδή τον κακό μάγο. Ακολουθώντας τα ίδια βήματα για την δημιουργία της πρώτης πίστας έκανα τον χάρτη μεγαλύτερο σε μέγεθος και πολυπλοκότητα χρησιμοποιώντας διαφορετικά tilesets και assets απο το διαδίκτυο, κρατώντας ίδιους τους εχθρούς και τα collectibles. Σε αυτή την πίστα πρόσθεσα και τον μάγο, ο οποίος λειτουργεί ως final boss και μέσω κώδικα κάνει trace την θέση του παίκτη, σε αντίθεση με τους πιο απλούς εχθρούς οι οποίοι κάνουν οριζόντια ή κάθετη κίνηση σε μια συγκεκριμένη απόσταση. Ο μάγος έχει επιπέον και περισσότερο health(5), καθώς και μπάρα ζωής η οποία ενεργοποιείται όταν του επιτεθεί ο παίκτης. Η πίστα ολοκληρώνεται όταν ο παίκτης κάνει collide με την πινακίδα που βρίσκεται δίπλα από την έξοδο(σπηλιά) και το παιχνίδι ολοκληρώνεται.

![βγ](https://user-images.githubusercontent.com/115794300/211877782-46a8c290-e9b4-4364-a356-a136190080bd.png)

`Mage`

![mage_80](https://user-images.githubusercontent.com/115794300/211877996-b418f5cd-4294-4531-ab63-5a0956450413.png)
![5BcDD7](https://user-images.githubusercontent.com/115794300/211878188-1d2704af-3c76-4c09-8a0e-1f93d58362a3.png)
![2023-01-11_193949_38](https://user-images.githubusercontent.com/115794300/211878735-d63d6d5c-361b-4dcf-8837-29c092fc19db.png)

`Damage Zones`

![Spike_Trap_81](https://user-images.githubusercontent.com/115794300/211879271-deaa1946-66ca-49e4-ba81-aa1970728d1e.png)

`Exit Sign`

![Στιγμιότυπο οθόνης 2023-01-11 194354](https://user-images.githubusercontent.com/115794300/211879502-8db48b8f-057e-424a-b6ea-fef993858608.png)

#### Μενού

Για την δημιουργία μενού ακολούθησα βίντεο, δημιουργώντας ένα αρχικό μενού με την δυνατότητα επιλογής πίστας (η δεύτερη είναι κλειδωμένη), την δυνατότητα ρύθμισης ήχου την ένδειξη των κουμπιών (animated) που θα χρειαστούν για το παιχνίδι και την επιλογή εξόδου από το παιχνίδι.

![m_20](https://user-images.githubusercontent.com/115794300/211872692-21798df2-30bc-41c9-b29a-c4e8fd380936.png)
![l_20](https://user-images.githubusercontent.com/115794300/211872761-4f6f3258-e4bd-4d0d-a806-da3e3ea5d1cf.png)
![o_20](https://user-images.githubusercontent.com/115794300/211872955-8ea85873-d7d5-4ac7-be3e-af299d4393c4.png)

Επιπλέον, δημιούργησα και ένα escape μενού το οποίο πατώντας το αντίστοιχο πλήκτρο σου δίνεται η δυνατότητα ρύθμισης του ήχου και επιστροφής στο αρχικό μενού, καθώς τρέχει το παιχνίδι.

![e_20](https://user-images.githubusercontent.com/115794300/211872883-ed49e37f-eacb-4a61-853a-b6c4bf9ca503.png)

Τέλος, έβαλα ένα pop-up μύνημα όταν ολοκληρωθούν οι δύο πίστες και ένα κουμπί για επιστροφή στο αρχικό μενού.

![k_20](https://user-images.githubusercontent.com/115794300/211873209-e2b1ce50-50ea-4c6b-816d-c9c707af40a3.png)

#### Mini Map 

Για να γίνει πιο εύκολη η καθοδήγηση και η αναγνώριση αντικειμένων που χρειάζονται προσοχή απο τον χρήστη προστέθηκε ένα mini map με ενδείξεις του παίκτη, των εχθρών, των damage zones και των interactable objects.

![Στιγμιότυπο οθόνης 2023-01-11 200636](https://user-images.githubusercontent.com/115794300/211884194-b1669d0d-16f7-45ef-8d95-f5a0be17d880.png)

### Σύνοψη

Έχοντας ολοκληρώσει την εργασία, θεωρώ ότι ήταν μια πάρα πολύ καλή εισαγωγή για εκμάθηση στο Unity και στην ανάπτυξη βιντεοπαιχνιδιών γενικότερα. Αν είχα την δυνατότητα να συνεχίσω το παιχνίδι θα ήθελα να αναπτύξω περισσότερο την ιστορία και το world building εστιάζοντας περισσότερο στο να φτιάξω δικά μου assets και tilesets, καθώς να έκανα και επιπλέον έρευνα ηια το combat system ώστε να δημιουργηθεί κάτι πιο ολοκληρωμένο και συνεκτικό, έχοντας έναν δικό του χαρακτήρα. 



## Αναφορές

#### Video Tutorials

https://www.youtube.com/watch?v=DTp5zi8_u1U (video tutorial for tilesets)

https://youtu.be/BUPiblhl-bw (respawn player)

https://youtu.be/EQHymuRQrh4 (UI score and code)

https://youtu.be/ILUbcxfvEMk (teleportation between scenes)

https://youtu.be/yWCHaTwVblk (volume slider)

https://youtu.be/kWhOMJMihC0 (minimap)

https://youtu.be/zc8ac_qUXQY (start menu)

https://youtu.be/JivuXdrIHK0 (pause menu)

https://youtu.be/1xHecUzFEqI (level lock)

https://youtu.be/7DPElwMtc9Y, https://youtu.be/v1UGTTeQzbo (hit points and health bar)

https://youtu.be/rhoQd6IAtDo (follow AI for mage)

https://youtu.be/OLbWB1R095s (game over menu)

https://youtu.be/dO5BzWYqEdY (finish game code)

https://youtu.be/0JXVT28KCIg (theleportation in map)

#### Assets

https://byaqua.itch.io/shabby-cottage (nature and decorating assets)

https://opengameart.org/content/whispers-of-avalon-grassland-tileset (cliffs, water and ground)

https://ansimuz.itch.io/tiny-rpg-town (house)

https://whatneyesore.itch.io/red-potion-animated-sprites (health potion)

https://jose-moyano.itch.io/evil-tree-pixel-art (enemy)

https://foozlecc.itch.io/trap-pack (earthworm trap)

https://stealthix.itch.io/animated-fires (fire projectile)

https://brullov.itch.io/fire-animation (fire)

https://soulofkiran.itch.io/pixel-art-wooden-gui-v1 ( UI πινακίδας και npc)

https://opengameart.org/content/portals (portal)

https://king-of-swords.itch.io/geralds-keys (UI για keyboard tutorial)

https://szadiart.itch.io/rpg-worlds-ca?download (tilesets δεύτερης πίστας)

https://stealthix.itch.io/animated-traps?download (spikes)

https://szadiart.itch.io/rogue-fantasy-catacombs (animated torches)

https://lionheart963.itch.io/wizard (mage)


#### Audio

Ήχος όταν ο παίκτης συλλέγει health potion: https://pixabay.com/sound-effects/health-pickup-6860/ 

Ήχος npc: https://pixabay.com/sound-effects/cat-3-43850/

Ήχος projectile: http://freesoundeffect.net/sound/fireball-burst-28-sound-effect

Ήχος για walking animation: https://pixabay.com/sound-effects/going-on-a-forest-road-gravel-and-grass-6404/

Ήχος μετάβασης μεταξύ επιπέδων: https://pixabay.com/sound-effects/success-1-6297/

Ήχος εχθρών: https://pixabay.com/sound-effects/rustling-leaves-6875/

Ήχος μάγου: https://pixabay.com/sound-effects/shimmering-object-79354/

Ήχος backround πρώτης πίστας: https://soundcloud.com/songsontape/rpg-forest

Ήχος backround δεύτερης πίστας: https://pixabay.com/sound-effects/droplets-in-a-cave-6785/
                                https://pixabay.com/sound-effects/frosty-wind-nature-sounds-8051/
