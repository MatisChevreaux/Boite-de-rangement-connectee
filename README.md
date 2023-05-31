# Boîte de rangement connectée:
Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l’Université 
Côte D'Azur.

L'idée initiale de mon projet était de créer un cadenas connecté mais, j'ai changé ma façon de voir en cours de route afin de créer une boîte de rangement connectée, fonctionnant de la même manière que le cadenas mais en plus appropriée vue la taille des pièces, plus résistante et moins coûteuse. Pour finir, la démonstration de mon projet est plus compréhensible car chaque pièce est visible.


# Description du projet:

Mon projet est une boîte de rangement sécurisée. Le loquet s'ouvre grâce à un lecteur de carte magnétique, simplifie donc l'ouverture manuelle et évite l'utilisation de clefs, ce qui offre la possibilité d'utiliser plusieurs cartes ayant les mêmes identifiants ce qui réduit les frais pour les utilisateurs. Ainsi cette boîte pourrait être utilisée par des colectivités où plusieurs personnes utilisent des cartes magnétiques de même identifiant.


# Fabrication :
# Composant côté électronique:
- 1 Carte Arduino Uno
- 1 Carte RFID RC522
- 1 broche pour carte RFID RC522
- 1 Servo-motor
- 1 Loquet
- 1 Mini breadboard arduino
- 10 cables mâle/mâle

# Matériaux côté boîte:
- 1 Planche de contreplaqué 1200x600mm de 5mm d'épaisseur
- 1 Tasseau 15x15mm de 2m de longeur
- 2 Charnieres 30x30mm
- 1 sachet de 40 vis de 12x2.5mm
- 2 sachets de 25 vis de 16x3.5mm


# Création côté électronique:

1ere étape: Souder la broche et la carte RFID RC522 entre elles.

2eme étape: Plugger la carte RFID au mini breadboard arduino.

3eme étape: Brancher la carte Arduino Uno à la carte RFID (Regarder l'image associée "Branchement Arduino et RFID RC522.png").

4eme étape: Brancher le servo-motor à la carte Arduino. (Le marron sur GND; Rouge sur 5V et Orange sur A2).

5eme étape: Rentrer le code dans la carte Arduino (Regarder le code associé "Final.ino").

6eme étape: Choisir et créer un loquet en plastique grâce à une imprimante 3D et le clipper sur le moteur (Regarder un dossier associé "Loquet.stl").

# Création côté boîtes:

1ere étape: Il faut couper des plaques en bois de différentes tailles dans le contreplaqué (dans mon cas j'ai utiliser une découpeuse laser pour une découpe de méilleure qualiter, vous pouvez regarder les photos associés "ggggggggggggggggggggg") :
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
- Visser les contreplaqué sur les tasseaux, dans un premier temps les côté, sans fixer le plafon ni la porte

4eme étape: Construire la deuxième partie de la boîte :
- Visser les charnières sur la porte puis sous le socle
- Visser le plafon sur la boîte

# Assemblage de l'électronique à la boîte:

Afin de proposer une présentation claire de mon projet j'ai décidé d'installer les composants sur le dessus de la boîte.
Mais j'aurais pu installer les composants dans un double fond afin de les disimuler.

Pour fixer chaque composant sur la boîte, j'ai:

- Pour la carte Arduino Uno, vissé 4 vis dans le toît.

- Pour le servo-motor, vissé un tasseau de 9cm dans le toit dans lequel le moteur est incrusté avec l'aide de deux petites cales de 3x1cm, en prenant en compte l'espace pour que la porte s'ouvre et se ferme.

- Pour le mini breadboard arduino, vissé de chaque côté des petites plaques en contreplaqué de différentes tailles pour le coincer, puis créé un loquet avec un autre petit morceau de contreplaqué afin de fixer completement l'ensemble à la boîte.

# Conclusion:

Mon projet, une fois terminé correspond entièrement à ce que j'avais imaginé et vous pouvez visionner la vidéo de présentation ce nommant "Présentation du projet.mp4".









