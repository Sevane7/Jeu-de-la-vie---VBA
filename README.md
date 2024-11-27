# Jeu de la Vie en VBA

Ce projet implémente le **Jeu de la Vie** de Conway en VBA, visant à explorer les possibilités de programmation avec Excel et VBA.

## Règles du Jeu de la Vie
- Une cellule vivante reste vivante si elle a 2 ou 3 voisins vivants, sinon elle meurt.
- Une cellule morte devient vivante si elle a exactement 3 voisins vivants.
- La simulation se déroule sur plusieurs périodes, où l'état des cellules évolue selon ces règles.

## Objectif
L'objectif principal était de se familiariser avec VBA et la manipulation d'Excel pour simuler un système dynamique en utilisant des macros.

## Fonctionnalités
- **Création d'une carte** : Génère une grille de cellules vivantes et mortes.
- **Simulation** : Évolution des cellules sur plusieurs périodes.
- **Affichage visuel** : Utilisation des couleurs dans Excel pour représenter les états des cellules.

## Instructions
1. **Préparer le fichier Excel** : Définissez les paramètres (dimensions de la grille, nombre de périodes, etc.) dans la feuille "Main" et cliquez sur "Créer la carte" pour générer la grille.
2. **Lancer la simulation** : Cliquez sur le bouton 'Démarrer (Auto)' dans la feuille "World" pour lancer le jeu de façon automatique.
3. **Remplissage manuel** : Remplissez la grille manuellement et cliquez sur le bouton "Démarrer (Manuel)".
