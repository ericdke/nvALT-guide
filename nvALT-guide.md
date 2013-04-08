> Voici un guide sur nvALT et la prise de notes en Markdown que j'ai publié sur mon site. Je le place ici dans sa version source en Markdown à des fins d'achivage et de référence.

---

# nvALT

*ou*

## La prise de notes pour les perfectionnistes

[nvALT](http://brettterpstra.com/projects/nvalt/) pour OSX est une application *gratuite*, légère et rapide qui permet de **prendre des notes instantanément**.

[nvALT](https://www.evernote.com/shard/s89/sh/31fef5eb-ef56-4139-9802-14040164c539/57d120150a72defff1f8ec889eccb650/deep/0/nvALT.jpg)

nvALT c'est également : 

- une gestion des notes par étiquettes et mots-clés
- le plaisir d'écrire en [Markdown](http://fr.wikipedia.org/wiki/Markdown)
- vos notes synchronisées sur tous vos appareils avec [Dropbox](https://www.dropbox.com/)
- vos notes accessibles par toute application sur n'importe quelle plateforme, puisque constituées de simples fichiers texte

Après avoir essayé [Springpad](http://www.springpad.com), [Simplenote](http://simplenote.com/), [Evernote](https://evernote.com/) et de nombreuses autres solutions pour prendre des notes de manière efficace, j'ai fini par réaliser que rien ne pouvait remplacer la rapidité, la versatilité, la pérénnité et le plaisir d'utiliser de simples fichiers texte.

Le désir d'efficacité m'a poussé vers la meilleure solution à ce jour sur Mac&nbsp;: nvALT de [Brett Terpstra](http://brettterpstra.com/).

Si vous aimez prendre des notes et que vous êtes sur Mac, c'est incontournable, comme vous allez vous en rendre compte.

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

### Pourquoi pas une base de données ?

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

### Pourquoi écrire en Markdown ?

C'est comme écrire en langage naturel, avec simplement quelques variations très faciles à retenir.

Et c'est un format texte, compatible avec tout, facilement exportable en pdf, doc, html, etc.

Une fois le texte écrit, on peut varier l'habillage visuel indépendamment du contenu.

Les avantages sont nombreux !

On peut se référer à [Markdown Guide](http://bywordapp.com/markdown/guide.html) (en anglais) ou [Markdown Wikipédia](http://fr.wikipedia.org/wiki/Markdown) (en français).

Le mode fichiers texte permet d'être accessible par un grand nombre d'apps, y compris sur appareils mobiles.

Surtout : les fichiers texte en Markdown, c'est *universel* et paré pour le futur (contrairement à mes vieux fichiers des années 80, sniff).

![](https://www.evernote.com/shard/s89/sh/6b594b93-cf66-4b66-b8ae-2f8e44dbf287/527fdc44b4e82a1a094589a5149715ea/deep/0/nvalt-prise-de-notes.jpg)

### Pourquoi pas un traitement de texte ?

Utiles au bureau, quoi que de moins en moins, [LibreOffice](https://www.libreoffice.org/) ou [MSWord](https://office.microsoft.com/) sont totalement inadaptés à la prise de note : dédiés au traitement de longs textes et lourds en fonctions telle collaboration ou révisions, pour la prise de notes rapide c'est enfoncer un clou avec un engin de chantier&nbsp;!

De plus, le format doc est fermé... et payant ! A moins de pirater le produit, il faut débourser… franchement, de nos jours il est devenu inutile de se livrer à ce jeu.

Word n'est même pas utile pour l'écriture de textes courts ou moyens, il y a des outils mille fois meilleurs ([Scrivener](http://www.literatureandlatte.com/scrivener.php) par exemple).

## Installation et configuration

### L'essentiel

nvALT est une application facile à installer : téléchargez-la [en bas de la page](http://brettterpstra.com/projects/nvalt/) puis déplacez-la dans le dossier Application. 

Vous pouvez commencer à l'utiliser.

Mais si vous voulez aller encore plus loin dans la productivité, plus tard, après vous être familiarisé avec cet outil, je vous conseille de considérer les liens suivants dès maintenant : ça permet de prendre les devants.

### Recommandé

- Si vous prévoyez d'utiliser un système d'automatisation des tâches tel [Hazel](http://www.noodlesoft.com/hazel.php) (ce que je vous recommande vivement), téléchargez [Open Meta](https://code.google.com/p/openmeta/downloads/list), installez la fonction "cachée" OpenMeta pour Hazel, puis installez le binaire et activez la fonction&nbsp;:

```
    cd ~/Downloads
    unzip openmeta_commandline_1.3.0.zip
    sudo chown u=rw /usr/local/bin
    mv openmeta /usr/local/bin
    defaults write com.noodlesoft.Hazel OMToolPath /usr/local/bin/openmeta
```


- [L'extension](http://elasticthreads.tumblr.com/post/8212672178/nvit-chrome-and-safari-extensions-for-nvalt) pour le navigateur Chrome (et Safari) est également pratique, avec entre autres fonctions la sélection d'un texte, d'une URL ou même du contenu d'une page transcrit en Markdown, envoyé directement à nvALT en tant que nouvelle note. Il y a aussi un [bookmarklet](http://jots.mypopescu.com/post/8529405944/nvalt-bookmarklet) pour Firefox.

### Configuration

- Dans les préférences, choisissez la gestion par fichiers texte et indiquez où se trouve votre dossier de notes dans Dropbox 

![Fichiers, Dropbox, extensions](https://www.evernote.com/shard/s89/sh/1d1dce8a-1db6-4abe-8cf2-ed289dd742d3/1f192c6cc9f7d5e9fa185960e9a7567e/deep/0/Notes.jpg)

- [Ajoutez](http://faceofgeoff.com/post/9665888623/nvalt-quick-tip-making-markdown-readable-and-your) les bons types d'extensions de fichier (nvALT ne met pas d'extension à ses fichiers textes, mais effectuer cette opération lui permet de lire tous les fichiers markdown que l'on copie dans son dossier notes à partir de l'extérieur)

- Réglez quelques options

![Options d'édition](https://www.evernote.com/shard/s89/sh/82ccea41-1213-49cc-b27a-560e5597123a/e2f9e19ce8a78478b039bc865e25fe7c/deep/0/Editer.jpg)

- Choisissez une présentation horizontale ou verticale
- Choisissez vos thèmes et couleurs

![Polices et couleurs](https://www.evernote.com/shard/s89/sh/47065da6-a7b9-455d-bbe9-e374ce58dcdc/224e495255f8b9ba9a33f3cb6010a48f/deep/0/Polices/Couleurs.jpg)

### Importer ses notes

Si vous preniez vos notes dans un autre format ou logiciel et que vous faites le grand saut vers le mode hacker, vous pourrez trouver quelques utilitaires et scripts intéressants pour récupérer vos notes et les exporter en Markdown.

- pour [Simplenote](http://simple-backup.appspot.com/)
- pour [Evernote](https://fr.support.evernote.com/link/portal/16051/16135/Article/3149/Exporter-des-notes-et-des-carnets-de-notes-dans-Evernote-pour-Mac)
- pour [Springpad](http://springpad.com/#!/_mak_/explore/sharedapplications/blocks/note/springpaddataextractor)

On trouve également quelques scripts sh/python/ruby sur [github](https://github.com/) pour exporter et transformer quelques formats de notes particuliers.

## Pour commencer

### Principe de base

**Il n'y a pas de bouton "+" ou "Nouvelle note", pas plus que de bouton "Rechercher".**

*Une fois l'application active[^fn-3] on commence tout de suite à écrire dans la zone de titre.*

[^fn-3]: click sur son icone dans le dock ou dans la menubar, activé par ALT/TAB, par son raccourci clavier, etc

![Nouvelle note](https://www.evernote.com/shard/s89/sh/b5a220a7-83e1-4ab9-b300-03c8f96f1151/7dada37c05fb4ae8219667b622cda7bc/deep/0/nvALT.jpg)

Au fur et à mesure que l'on tape les premières lettres du titre, la liste des notes qui contiennent ces caractères s'actualise en temps réel : si une note existe déjà avec ce titre on peut l'éditer en appuyant sur Entrée ou après avoir navigué avec les flèches du clavier.

![Liste des notes](https://www.evernote.com/shard/s89/sh/b2e3c819-b1f5-4e4b-bc8e-1d86eb989218/30bafb2433584b98c13e7c194a3280aa/deep/0/nvALT.jpg)

Si l'on continue de taper et que le titre devient unique, la note le devient aussi et est automatiquement créée.

Le titre écrit, en appuyant sur Entrée le curseur est déplacé dans la zone principale et on peut commencer à écrire le corps du texte.

### Raccourcis clavier

nvALT est pensée pour les amoureux du clavier et ceux qui veulent toucher la souris le moins possible. 

En effet, que ce soit pour des raisons de santé (traumatismes répétés au poignet) ou simplement de productivité, il vaut mieux éviter de trop souvent manipuler la souris&nbsp;: les raccourcis permettent de travailler rapidement sans avoir à bouger les mains hors du clavier.

*Liste des principaux raccourcis clavier de nvALT&nbsp;:*

- **Chercher** ou **créer** une note = `CMD+L` (revient à se placer dans la barre principale)
 
- **Supprimer** une note = `CMD+DEL` (mais je déconseille de supprimer, il vaut mieux archiver)
 
- **Tagger** une note (ajouter des mots-clés) = `SHIFT+CMD+T` (attention, la liste de tags, séparés par une virgule, est sélectionnée par défaut : ne pas l'effacer par erreur, d'abord faire `flèche droite` avant d'ajouter des tags)
 
- **Renommer** une note = `CMD+R`
 
- **Insérer** un lien = `SHIFT+CMD+L`
 
- **Afficher** la fenêtre de prévisualisation = `CTRL+CMD+P`
 
- **Editer** la note dans un logiciel externe = `SHIFT+CMD+E`

## Organiser ses notes

La manière d'organiser ses notes est un vaste sujet et mériterait d'y consacrer une oeuvre à part entière.

De grands esprits se sont penchés sur la question et on mis au point des techniques efficaces, toutes différentes et dignes d'intérêt : [Getting things done](http://fr.wikipedia.org/wiki/Getting_Things_Done), [Inbox zero](http://inboxzero.com/), etc.

Personnellement, je me "contente" d'utiliser un système de classement à la fois sémantique et complètement libre et anarchique.

En effet, la recherche et les tags dans nvALT sont une fonction si puissante et rapide qu'il suffit de bien tagger et titrer ses notes pour les retrouver en un instant.

### Conventions dans les titres

Une des meilleures manières de s'organiser est de mettre la date en début ou fin de titre, ce qui autorise une recherche aisée pour plus tard.

Mais taper manuellement la date à chaque fois est très désagréable et source d'erreurs. Je recommande fortement l'utilisation de cette merveille qu'est [TextExpander](http://www.smilesoftware.com/TextExpander/index.html) qui vous permettra d'insérer la date et/ou l'heure en tapant deux ou trois lettres seulements.

Je préfère pour mon usage personnel utiliser uniquement un nombre restreint de mots-clés dans mes titres.

Ils correspondent à des catégories plus générales que les tags, ou à des déclencheurs pour Hazel.

Exemples : `@post`, `@email`, `@logins`, `@list`, `@critique`, `@edito`, `@tuto`, `@phone`, `@links`, etc.

Je les fais précéder d'un `@` pour les retrouver plus facilement.

Si une note doit rester au top de la liste pour que je me souvienne de la traiter, je peux mettre un `#` au début du titre&nbsp;: `#urgent`, `#anniv`, `#work`, etc.

L'usage de l'anglais est recommandé, les mots sont plus courts et synthétiques. 

Bien sûr ça marche aussi en français, il est simplement moins facile de rester cohérent à cause des accents et de l'orthographe plus complexe.

**Attention** à ne pas surcharger vos titres avec des mots-clés, les… mots-clés sont là pour ça&nbsp;!

### Meta tags

**Un réflexe à prendre rapidement dans nvALT est de tagger votre note avant d'oublier de le faire**.

J'aime tagger mes notes en deux temps : immédiatement après avoir entré le titre et le début du contenu, puis à la fin avant de passer à autre chose.

Avec le raccourci `SHIFT+CMD+T` vous ajoutez des tags en les séparant par une virgule.

Vous pouvez tagger de manière plus large que dans les titres, il n'y a pas de limites. 

Je recommande néanmoins de respecter une certaine voie du milieu&nbsp;: une grosse dizaine de tags maximum par note semble raisonnable.

Les tags peuvent représenter des catégories, des index, des genres, des mots-clés sémantiques, bref, tout ce que vous souhaitez.

Le genre de tag que j'utilise souvent&nbsp;: 

    food, films, blog, work, app, list, link, email
    podcast, article, webpage, image, mp3, text
    idea, dev, citation, book, ebay, snippet
    css, php, ruby, jade, tuto, flow
    space, philo, physics, ref, galaxy
    sandwich, cronenberg, tech, racc, song
    perso, reminder, where-keys, when-meeting
    todo, done, archive, null, wtf, cool

### Liens inter notes

**Une fonction simple à utiliser qui permet de classer ses notes&nbsp;: les liens inter-notes**.

Il suffit de taper deux fois un crochet carré gauche (`[`, sous le `5`), ce qui est immédiatement transformé en double crochet `[[]]` grâce à l'auto-complétion, et de continuer à taper le titre d'une note : les titres correspondants s'affichent sous le curseur et permettent de choisir la note à laquelle on veut référer.

Exemple : `[[@food riz au lait 07/04/2013]]` est un lien vers la note ayant le titre "@food riz au lait 07/04/2013.txt". Je n'ai eu qu'à taper deux fois le crochet puis '@food' pour voir apparaitre une liste de fichiers à référencer (puisque je place ce tag au début de toutes mes recettes complètes).

Cela permet de créer aisément un système de chapitrage à partir de notes indépendantes.

Vous pouvez par exemple créer une note qui contiendra uniquement des appels à d'autres notes, comme une table des matières : l'index des recettes taggées 'dessert', les chapitres de votre futur roman, les grandes lignes de vos examens d'histoire, rassembler des notes par thème pour un article à publier, etc. 

Vous pouvez également vous laisser porter au gré de vos inspirations et écrire des références au fur et à mesure que vous accumulez les notes : il sera toujours facile ensuite de créer une nouvelle note contenant tous les liens grâce à une recherche sur vos tags.

On peut placer un lien inter-notes à n'importe quel endroit du texte.

## Recherche de notes

### Dans nvALT

**Rien de spécial à faire, si les notes sont bien titrées et taggées, il suffit de commencer à écrire dans la barre de titre et les notes concernées apparaissent en temps réel.**

C'est un des gros atouts de nvALT : une réactivité exemplaire et une recherche intuitive.

### En dehors de nvALT 

Une simple recherche dans Spotlight fait apparaitre les notes. De même dans le Finder, bien sûr.

Dans le Terminal, avec `mdfind` (commande pour Spotlight):

```
mdfind @food
mdfind Janvier
```

Brett Terpstra a de bonnes idées de fonctions à placer dans `~/.bashrc` ou `~/.zshrc`. Je les ai simplifiées&nbsp;:

```
fbox () { mdfind -onlyin ~/Dropbox "$1";}
fposts () { mdfind -onlyin ~/Dropbox/articles "$1";}
fnotes () { mdfind -onlyin ~/Dropbox/Notes "$1";}
```

mais vous pouvez trouver les originales quelques part au fond de son blog...

## Prévisualisation Markdown

nvALT inclut une fenêtre flottante pour prévisualiser le rendu de votre document. 

![Prévisualisation nvALT](https://www.evernote.com/shard/s89/sh/5a820308-00f6-4cea-ba3a-b0f7d43e6882/f117db887cc9a42b9bb88df85ccae21e/deep/0/Capture%20d%E2%80%99e%CC%81cran%202013-04-06%20a%CC%80%2002.33.58.jpg)

On la fait apparaître avec le raccourci clavier `CTRL+CMD+P`.

Il est possible de personnaliser l'apparence du document dans cette fenêtre avec du CSS.

Intégrez le CSS de votre blog ou ebook à nvALT pour avoir un aperçu de ce que donnera votre document[^fn-4].

[^fn-4]: vous pouvez également télécharger des thèmes prédéfinis&nbsp;: [Byword](http://bywordapp.com/extras/index.html), [iAwriter](https://github.com/moritzz/iAWriterCSS), [play with Marked](http://www.candlerblog.com/2012/02/29/marked-as-css-playground/)

On peut également visualiser le document dans [Marked](http://markedapp.com/) avec `SHIFT+CMD+E` à condition d'avoir choisi Marked comme application à la place de l'éditeur externe dans les préférences de nvALT.

## Export

Un des grands avantages de prendre ses notes en Markdown est que la mise en forme est séparée de la structure.

Le document Markdown existant, il est facile ensuite de lui appliquer des styles différents et de l'exporter dans un grand nombre de formats.

Bien sûr le format d'exportation de base est le HTML, mais nvALT excelle à l'export de PDF et permet également de sortir ses notes en DOC (format MS Word), RTF (Rich text format) et TXT (simple texte).

De plus, en choisissant [Marked](http://markedapp.com/) comme éditeur externe dans les préférences, vous bénéficiez de la grande richesse en options d'exportation que possède cette app.

## Tri et archivage

### Automatismes

Comme vous avez installé Open Meta, vos tags sont partageables par toutes les applications qui reconnaissent ce format ouvert : aujourd'hui, c'est [Hazel](http://www.noodlesoft.com/hazel.php) qui nous intéresse.

Nous pouvons par exemple décider qu'une note peut devenir obsolète, mais que l'on ne veut pas l'effacer pour autant : on pourra alors lui ajouter un tag "archive".

Avec Hazel, je peux créer une action qui va archiver cette note dans un dossier de backup dès que j'entre le mot-clé&nbsp;:

![Hazel : déplace vers archive](https://www.evernote.com/shard/s89/sh/0edf1d29-517b-41a5-a17a-f44a43c33225/5fbd6103db5a16dd50f806cfe1e333c6/deep/0/Capture%20d'%C3%A9cran%2006/04/13%2004:22.jpg)

Autre cas typique : j'ai souvent dans nvALT une note qui a évolué et qui rassemble dorénavant assez d'éléments pour pouvoir commencer à rédiger un texte à part entière. 

Elle passe alors de *note* à *brouillon* dans mon esprit : aussitôt je la tagge avec `SHIFT+CMD+T` avec le mot-clé de mon choix, ici `post` ou `brouillon` par exemple.

Grâce à Hazel, je peux faire une action automatique qui, lors du changement de mot-clé, va déplacer le document dans mon dossier Brouillons et immédiatement l'ouvrir dans un autre éditeur, [Mou](http://mouapp.com/) par exemple&nbsp;:

![Hazel : déplace vers autre éditeur](https://www.evernote.com/shard/s89/sh/a47c7b15-6953-4ccd-861f-95644bb996b9/8366339e4e308f0c804e381f18e2e9c4/deep/0/Capture%20d%E2%80%99e%CC%81cran%202013-04-06%20a%CC%80%2003.53.39.jpg)

## Mode auteur

On peut configurer nvALT pour le mettre dans un état que j'appelle le mode *auteur*, c'est-à-dire sans distractions et concentré sur le texte.

Avec `SHIFT+CMD+C` on cache la liste des notes, puis avec `SHIFT+CMD+F`on passe en contraste faible, on cache la preview si elle est affichée avec `CTRL+CMD+P` et enfin avec `CTRL+CMD+F` on entre en plein écran.

Cependant, même si ça marche bien dans nvALT, je préfère l'utiliser uniquement pour des petits documents, des notes. 

Pour écrire des articles longs, des textes complets, je préfère utiliser un éditeur dédié. 

Par exemple [Scrivener](http://www.literatureandlatte.com/scrivener.php) pour un scénario, des dialogues, un roman ; [Sublime Text 2](http://www.sublimetext.com) pour du code ; [Mou](http://mouapp.com/) pour un article de blog ou un éditorial, etc.

![Mou](https://www.evernote.com/shard/s89/sh/0a7daf5c-fd65-4be3-8887-760b0ae1f7f9/d28a1cc19f784ad1c48b71e19ae0af40/deep/0/nvalt-prise-de-notes.jpg)

Il est également facile d'utiliser [Marked](http://markedapp.com/) avec ces apps.

## Astuces

### Astuces Markdown

#### Rappel/fondamentaux

- Deux fois `Entrée` = nouveau paragraphe

- `>` ou `tab` puis votre texte = citation

- `#`= titre

- `##` = sous-titre

- `###` = section

- `[texte](lien)` = lien vers URL

- `*texte*` ou `_texte_` = texte en *italique*

- `**texte**` ou `__texte__` = texte en **gras**


#### Insérer une image

Pour faire un lien vers une image il suffit d'ajouter un `!` devant la formule habituelle servant à créer un lien&nbsp;:

```
![texte](lien)
```

On peut également faire un **drag-n-drop** (glisser-déplacer) du Finder (ou de PathFinder) vers le corps de la note, un lien sera automatiquement créé.

Lien&nbsp;: [explications](http://brettterpstra.com/2012/09/27/quick-tip-images-in-nvalt/) (en anglais) pour bénéficier des liens relatifs dans les notes.

#### Markdown service tools

Brett Terpstra a créé les [markdown service tools](http://brettterpstra.com/projects/markdown-service-tools/), un ensemble de services pour OSX accessibles par toutes les applications.

Vous sélectionnez une partie de votre texte, et un service se charge d'y appliquer une action.

Par exemple : avec "Auto search link", vous sélectionnez un ou plusieurs mots, actionnez ce service, et nvALT transforme le mot en lien avec le résultat de la recherche de Google.

### Mode todo list

Même si je gère mes tâches et toutes mes TODO list dans [Wunderlist](http://www.6wunderkinder.com/wunderlist), j'aime bien de temps en temps me laisser des reminder dans mes notes.

Dans ce cas j'ai un système tout simple&nbsp;: je tagge avec `todo` toutes les notes qui contiennent une tâche à effectuer mais qui ne sont pas urgentes (la plupart du temps ce sont des références à chercher).

Chaque week-end je mets de l'ordre dans mes documents, et j'en profite pour afficher toutes les notes contenant `todo` et je change le tag en `done` ou `archive` pour celles qui sont accomplies.

Une action Hazel se charge de déplacer les notes concernées dans un dossier d'archive.

## Apps iOS et Android

La plupart des apps mobiles de prise de notes qui fonctionnent avec Dropbox vous obligent à utiliser leur propre dossier prédéfini pour stocker vos notes. Ce n'est pas acceptable.

Parmi les rares apps qui permettent de choisir un dossier personnel, la seule qui soit vraiment de qualité sur iOS est [Drafts](http://agiletortoise.com/drafts).

Et la seule sur Android, pour les mêmes raisons, est… [Draft](https://play.google.com/store/apps/details?id=com.mvilla.draft).

## Aller plus loin

- On peut approfondir les automatismes avec [Keyboard Maestro](http://www.keyboardmaestro.com/main/) ou tout simplement ses propres AppleScripts.
- nvALT n'existe que sur OSX, mais il y a des outils basés sur la même philosophie sur chaque plateforme. De plus, [Notational Velocity](http://notational.net), l'ancêtre de nvALT, est disponible pour Linux et Windows.
- On peut étendre sa gestion des notes à [Omnifocus](https://www.omnigroup.com/applications/omnifocus/), [DayOne](http://dayoneapp.com/), etc.
- Hazel copie mes notes vers [Google Drive](https://drive.google.com/) pour un backup supplémentaire.
- Des automatismes avec [ifttt](http://www.ifttt.com) ou [zapier](https://zapier.com/) permettent d'uploader automatiquement ses notes à partir de Dropbox vers un autre service[^fn-5].

[^fn-5]: [if this then that](http://aya.io/blog/if-this-then-that/) sur Aya

## Liens en vrac

- [How to tag](http://macpowerusers.com/tag/merlin-mann/)
- [Tagging](http://bettermess.com/naming-files-and-avoiding-folders/)
- [nvALT author](http://elasticthreads.tumblr.com/)
- [nvALT NerdQuery](http://nerdquery.com/?media_only=0&query=nvalt&search=1&category=23&catid=23&type=and&results=50&db=0&prefix=0)
- [Patrick Welker's setup](http://shawnblanc.net/2013/03/patrick-welker-sweet-mac-setup/)
- [Michael Schechter's workflow](http://www.macdrifter.com/2012/04/michael-schechters-writer-workflow.html)
- [Using Marked](http://www.macdrifter.com/2012/04/a-panegyric-to-marked.html)
- [Brett Terpstra's links](http://www.macdrifter.com/2012/07/terpstra-day.html)
- [Organize notes](http://www.macworld.com/article/1168148/how_i_organize_everything_with_plain_text_notes.html)
- [MultiMarkdown](http://fletcherpenney.net/multimarkdown/)
- [Why Markdown ?](http://brettterpstra.com/2011/08/31/why-markdown-a-two-minute-explanation/)
- [Why plain text is best](http://www.macworld.com/article/1161549/forget_fancy_formatting_why_plain_text_is_best.html)

## Crédits

Merci à [Brett Terpstra](http://brettterpstra.com/), [Macdrifter](http://www.macdrifter.com/), [Rocket Ink](http://www.rocket-ink.com/), [Bettermess](http://bettermess.com/) et [Tuts+](https://tutsplus.com/).

---

© [Eric DEJONCKHEERE](mailto:eric@aya.io) 2013