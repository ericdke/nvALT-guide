---
title: Avantages
---

## Principaux avantages de nvALT

fork[^fn-1] du déjà très bon [Notational Velocity](http://notational.net/fr/), **nvALT** possède de nombreux avantages&nbsp;:

[^fn-1]: [Définition de fork](http://fr.wikipedia.org/wiki/Fork)

- vitesse : application ultra réactive, même sur une machine modeste
- implémentation markdown avancée
- une interface graphique mais une philosophie hacker
- bonne qualité de prévisualisation et export
- interface spéciale amoureux du clavier
- openmeta tags pour tri et recherche (mdfind, spotlight, meta indexeurs)
- prise de note immédiate, jamais aucun délai
- on peut ouvrir une note dans un autre éditeur à tout instant
- inutile de penser à enregistrer, c'est automatique et instantané

## Pourquoi pas une base de données ?

La plupart des logiciels de prise de notes enregistrent celles-ci dans un format qui leur est propre, souvent de manière compressée et encodée dans une base de données ([BDD](http://fr.wikipedia.org/wiki/Base_de_donn%C3%A9es)).

Ce principe souffre de nombreux défauts. Parmi les principaux&nbsp;:

- fragile : une BDD encodée est susceptible d'être corrompue par un bug ou une mauvaise manipulation
- binaire : la BDD est illisible en dehors d'une application qui en comprend le format
- pas portable : si personne n'a créé d'outil pour exporter le contenu de votre BDD vers un autre format, vous êtes enfermés
- pas pérenne : que deviennent vos notes si le logiciel qui crée et lit la BDD n'existe plus&nbsp;?
- exige une maintenance : les logiciels évoluent, le format de la BDD aussi, d'où mises à jour fastidieuses et pouvant occasionner de nouveaux bugs

Une BDD pour ses notes peut être utile dans certains cas[^fn-2]&nbsp;: si vous avez d'énormes quantités de données à traiter, données ayant les mêmes champs et tags, alors manipuler plusieurs milliers de fichiers n'est *peut-être* pas le bon choix. A vous de voir. 

Personnellement je n'en suis absolument pas certain : avec des outils Unix et des scripts Bash ou Ruby, on fait des merveilles sur des fichiers, même en surnombre.

[^fn-2]: nvALT propose en option de fonctionner avec une base de données au lieu de fichiers texte.  Même si l'application reste agréable à utiliser dans ce cas, ça reste une gestion "à l'ancienne" avec un format que l'on ne peut pas utiliser en dehors de l'application qui le produit.

## Pourquoi écrire en Markdown ?

C'est comme écrire en langage naturel, avec simplement quelques variations très faciles à retenir.

Et c'est un format texte, compatible avec tout, facilement exportable en pdf, doc, html, etc.

Une fois le texte écrit, on peut varier l'habillage visuel indépendamment du contenu.

Les avantages sont nombreux !

On peut se référer à [Markdown Guide](http://bywordapp.com/markdown/guide.html) (en anglais) ou [Markdown Wikipédia](http://fr.wikipedia.org/wiki/Markdown) (en français).

Le mode fichiers texte permet d'être accessible par un grand nombre d'apps, y compris sur appareils mobiles.

Surtout : les fichiers texte en Markdown, c'est *universel* et paré pour le futur (contrairement à mes vieux fichiers des années 80, sniff).

![](https://www.evernote.com/shard/s89/sh/6b594b93-cf66-4b66-b8ae-2f8e44dbf287/527fdc44b4e82a1a094589a5149715ea/deep/0/nvalt-prise-de-notes.jpg)

## Pourquoi pas un traitement de texte ?

Utiles au bureau, quoi que de moins en moins, [LibreOffice](https://www.libreoffice.org/) ou [MSWord](https://office.microsoft.com/) sont totalement inadaptés à la prise de note : dédiés au traitement de longs textes et lourds en fonctions telle collaboration ou révisions, pour la prise de notes rapide c'est enfoncer un clou avec un engin de chantier&nbsp;!

De plus, le format doc est fermé... et payant ! A moins de pirater le produit, il faut débourser… franchement, de nos jours il est devenu inutile de se livrer à ce jeu.

Word n'est même pas utile pour l'écriture de textes courts ou moyens, il y a des outils mille fois meilleurs ([Scrivener](http://www.literatureandlatte.com/scrivener.php) par exemple).
