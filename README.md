# Sliide

1. Installez le barda avec `npm ci` ;
2. Démarrez le machin avec `npm start` ;
3. Testez l’accessibilité avec `npm t`.

## Contenus

Vous trouverez un exemple de _slide_ :

* introductif,
* textuel,
* avec exemple de code HTML avec affichage en vis-à-vis,
* avec exemple de code CSS en édition directe, avec rendu en vis-à-vis,
* conclusion.

### Vue présentateur

Vous pouvez activer une vue présentateur avec le raccourci <kbd>alt</kbd>+<kbd>s</kbd>. Le support se rouvre dans un nouvel onglet, avec la vue présentateur activée. Elle contient :

- Les notes (texte brut), déclarées dans un attribut `data-notes` sur chaque slide.
- Un aperçu du slide suivant (Firefox seulement).
- Un minuteur, qui se contente d'afficher le temps qui passe.

Ceci est un projet expérimental : **la vue présentateur n'est pas accessible**. Tout ou presque est géré en CSS : si vous êtes intéressés par cet outil et avez besoin de le rendre accessible, indiquez-le moi dans une issue. Je pourrais saupoudrer du JavaScript et arrêter mes bêtises en CSS !

## Scripts

On utilise PrismJS pour la coloration syntaxique (avec un _build_ personnalisé pour HTML et CSS pour le moment) et Twemoji pour assurer l’affichage homogène des emojis.