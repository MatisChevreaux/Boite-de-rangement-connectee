# Boîte de rangement connecter:
Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l’Université 
Côte D'Azur.

L'idée initiale de mon projet était de créer un cadenas connecter mais, j'ai changé ma façon de voir en cours de route afin de créer une boîte de rangement connecter, fonctionnent de la même manière que le cadenas mais étant plus appropriées, vue la taille des pièces, plus résistante et moins coûteuse. Pour finir la démonstration de mon projet est plus compréhensible, car chaque pièce est visible.


# Description du projet:

Mon projet est une boîte qui sert de rangement sécuriser, le loquet s'ouvre grâce à un lecteur de carte magnétique. Simplifiant donc l'ouverture manuelle et évite l'utilisation de clefs, ce qui offre la possibilité d'utiliser plusieurs cartes ayant les mêmes identifiants ce qui réduit les frais pour les utilisateurs. Ainsi cette boîte pourrait être utilisée par des colectiviter dont plusieurs personnes utilisent des cartes magnétique de même identifiant.


# Fabrication :
# Composant cotée électronnique:
- 1 Carte Arduino Uno
- 1 Carte RFID RC522
- 1 broche pour carte RFID RC522
- 1 Servo-motor
- 1 Loquet
- 1 Mini breadboard arduino
- 10 cables mâle/mâle

# Matériaux cotée boite:
- 1 Planche de contreplaquer 1200x600mm de 5mm d'épesseur
- 1 Tasseau 15x15mm de 2m de longeur
- 2 Charniere 30x30mm
- 1 sachet de 40 vis de 12x2.5mm
- 2 sachet de 25 vis de 16x3.5mm


# Création cotée électronique:

1ere étape: Souder la broche et la carte RFID RC522 entre elles.

2eme étape: Plugger la carte RFID au mini breadboard arduino.

3eme étape: Brancher la carte Arduino Uno à la carte RFID (Regarder l'image associer "Branchement Arduino et RFID RC522.png").

4eme étape: Brancher le servo-motor à la carte Arduino. (Le marron sur GND; Rouge sur 5V et Orange sur A2).

5eme étape: Rentrer le code dans la carte Arduino (Regarder le code associer "Final.ino").

6eme étape: Choisir et créer un loquet en plastique grâce a une imprimante 3D et le cliper sur le moteur (Regarder un dossier associer "Loquet.stl").

# Création cotée boîtes:

1ere étape: Il faut couper des plaques en bois de différentes tailles dans le contreplaquer :
- 3 plaques de 20x14.5cm
- 2 plaques de 9x14.5cm
- 1 plaque de 19x9cm
- 1 plaque de 20x10cm

2eme étape: Il faut couper des tasseaux en bois de différentes tailles :
- 4 tasseaux de 9cm
- 4 tasseaux de 11.5cm
- 3 tasseaux de 15.5cm

3eme étape: Construire la premiere partie de la boîte:
- Visser 2 plaques de 20x14.5cm ensembles (ce sera le socle)
- Visser sur le socle un cadre fait à partir des tasseaux
- Visser les contreplaquer sur les tasseaux, dans un premier temps les coter, sans fixer le plafon ni la porte

4eme étape: Construire la deuxième partie de la boîte :
-Visser charnière sur la porte puis sous le socle
-Visser le plafon sur la boîte









