Crée une application web simple en HTML, CSS et JavaScript pour enfants de 6 à 11 ans intitulée « Invente ton histoire ».

Objectif :
Permettre à l’enfant de créer une scène en déplaçant des éléments et en ajoutant du texte sous forme de blocs déplaçables.

Fonctionnalités principales :

1. Une grande zone centrale (canvas) FIXE :

* représente une feuille ou une scène
* ne doit pas être déplaçable
* les éléments peuvent être déplacés à l’intérieur uniquement

2. Une barre latérale avec des éléments à glisser-déposer :

* personnages (images)
* objets (images)
* éléments de décor (images)
* les éléments doivent être draggable vers la scène
* ils doivent pouvoir être repositionnés librement

3. Système de texte transformé en bloc :

* un champ de saisie texte
* un bouton « Ajouter »
* quand l’utilisateur clique :
  → un bloc de texte apparaît sur la scène
  → ce bloc est draggable
  → plusieurs blocs peuvent être créés
  → les blocs peuvent être repositionnés librement

4. Aide à l’écriture (phrases pré-faites) :

* afficher des boutons avec :

  * Il était une fois...
  * Un jour...
  * Soudain...
  * Ensuite...
  * Grâce à...
  * Finalement...
  * Depuis ce jour...
* quand on clique sur une phrase :
  → elle remplit le champ texte
  OU
  → elle crée directement un bloc texte

Contraintes techniques :

* utiliser du JavaScript simple (pas de framework)
* utiliser le drag & drop natif OU implémentation custom simple
* code clair, structuré et commenté
* interface fluide et réactive

Design :

* interface colorée, enfantine, joyeuse
* gros boutons
* éléments faciles à manipuler
* police lisible
* disposition claire (sidebar + scène)

Bonus (si possible) :

* possibilité de supprimer un élément
* possibilité de redimensionner les éléments
* petites animations au drag

Important :
Le canvas doit rester fixe. Seuls les éléments (images et textes) doivent être déplaçables.

Le résultat doit ressembler à un mini Canva simplifié pour enfants, centré sur la création d’histoires visuelles.
