# Globetrotter

##Info :

* **Pour changer les cartes** Changer dans l'actualisation de l'affichage la ligne (GlobeTrotter : )
 * <code>carteJoueur += JoueursTab[numJoueur][i].getHtml();</code>
* Par :
 * <code>carteJoueur += JoueursTab[numJoueur][i].getHtmlTurned();</code>

## To Do :

* Créer des affichages avec des bandeaux pour donner des informations : joueur dont c'est le tour, action a effectuer, etc...
 * Créer 2 fonctions : DisplayRed(String) et DisplayGreen(String) et DisplayBleu(String)
* Modifier le fond derriere les cartes : Remplacer le fond blanc par une image en rapport avec le jeu (transparence ??)
* Créer les fonctions permettant le choix d'une carte et de l'emplacement
* Créer une fonction de Parse pour permettre l'affichage au dela de 10 cartes sur le board
* Améliorer DisplayGood()
* Améliorer DisplayFalse()
* Modifier comportement de trouverIDCarteDroiteFleche(id) au cas ou on clique que la fleche a plus à droite
* Mettre en gras et souligner le nom du pays sur la carte

## Idées améliorations :
* Glisser les cartes (et donc enlever les fleches)
* Mettre en gras l'info de la carte qui compte pour la partie
* Afficher les unités
* Ajouter des espaces entre les milliers

## Done :
* Gerer l'affichage Des fleches entre les cartes du board
* Afficher le nom du joueur 
* Faire une fonction d'affichage de la carte "Retournée"
* Gerer l'affichage des cartes sur une même ligne
* Faire perdurer l'affichage d'une carte selectionnée (genre la carte actuellement selectioné reste marqué)
* Faire perdurer l'affichage d'une fleche selectionnée (genre la fleche actuellement selectioné reste marqué
