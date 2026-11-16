# Sélecteurs avancés

**Durée** : 20 minutes — **En binôme**

## Consigne

À partir de la page `index.html` fournie, ajoutez du CSS dans `style.css` pour réaliser les consignes ci-dessous.

Chaque consigne indique **quel type de sélecteur** utiliser. L'objectif est de manipuler les sélecteurs d'attribut, les pseudo-classes et les pseudo-éléments vus en cours.

Vérifiez le résultat dans le navigateur après chaque modification.

## Consignes

| # | Consigne                                                                            | Sélecteur à utiliser     |
|---|-------------------------------------------------------------------------------------|--------------------------|
| 1 | Ajouter un 🔗 **avant** le texte de chaque lien externe (URL commençant par `http`) | `[href^="http"]::before` |
| 2 | Mettre en **gras** le premier élément de la liste des ingrédients                   | `:first-child`           |
| 3 | Ajouter une **bordure inférieure** décorative après chaque titre `<h2>`             | `::after`                |
| 4 | Colorer en rouge les champs de formulaire **obligatoires** (attribut `required`)    | `[required]`             |
| 5 | Changer la couleur de fond des **lignes paires** du tableau des étapes              | `:nth-child(even)`       |
| 6 | Retirer le soulignement des liens **au repos**, puis le **rétablir au survol**      | `:hover`                 |
| 7 | Colorer en gris les paragraphes **sauf** celui ayant la classe `intro`              | `:not()`                 |

## Indice

> [!tip]
>
> - Pour les pseudo-éléments `::before` et `::after`, n'oubliez pas la propriété `content`.
> - Pour les liens externes, le sélecteur `[href^="http"]` cible les attributs dont la valeur **commence par** `http`.
> - `:nth-child(even)` sélectionne les éléments à une position paire (2, 4, 6…).

## Fichiers de départ

- `index.html` — page HTML d'une recette de cuisine
- `style.css` — feuille de style vide à compléter
