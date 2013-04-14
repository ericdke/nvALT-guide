---
title: Astuces
---

## Astuces Markdown

### Rappel/fondamentaux

- Deux fois `Entrée` = nouveau paragraphe

- `>` ou `tab` puis votre texte = citation

- `#`= titre

- `##` = sous-titre

- `###` = section

- `[texte](lien)` = lien vers URL

- `*texte*` ou `_texte_` = texte en *italique*

- `**texte**` ou `__texte__` = texte en **gras**


### Insérer une image

Pour faire un lien vers une image il suffit d'ajouter un `!` devant la formule habituelle servant à créer un lien&nbsp;:

```
![texte](lien)
```

On peut également faire un **drag-n-drop** (glisser-déplacer) du Finder (ou de PathFinder) vers le corps de la note, un lien sera automatiquement créé.

Lien&nbsp;: [explications](http://brettterpstra.com/2012/09/27/quick-tip-images-in-nvalt/) (en anglais) pour bénéficier des liens relatifs dans les notes.

## Markdown service tools

Brett Terpstra a créé les [markdown service tools](http://brettterpstra.com/projects/markdown-service-tools/), un ensemble de services pour OSX accessibles par toutes les applications.

Vous sélectionnez une partie de votre texte, et un service se charge d'y appliquer une action.

Par exemple : avec "Auto search link", vous sélectionnez un ou plusieurs mots, actionnez ce service, et nvALT transforme le mot en lien avec le résultat de la recherche de Google.

## Mode todo list

Même si je gère mes tâches et toutes mes TODO list dans [Wunderlist](http://www.6wunderkinder.com/wunderlist), j'aime bien de temps en temps me laisser des reminder dans mes notes.

Dans ce cas j'ai un système tout simple&nbsp;: je tagge avec `todo` toutes les notes qui contiennent une tâche à effectuer mais qui ne sont pas urgentes (la plupart du temps ce sont des références à chercher).

Chaque week-end je mets de l'ordre dans mes documents, et j'en profite pour afficher toutes les notes contenant `todo` et je change le tag en `done` ou `archive` pour celles qui sont accomplies.

Une action Hazel se charge de déplacer les notes concernées dans un dossier d'archive.
