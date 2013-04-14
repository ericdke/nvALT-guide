---
title: Installation et configuration
---

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

## Configuration

- Dans les préférences, choisissez la gestion par fichiers texte et indiquez où se trouve votre dossier de notes dans Dropbox 

![Fichiers, Dropbox, extensions](https://www.evernote.com/shard/s89/sh/1d1dce8a-1db6-4abe-8cf2-ed289dd742d3/1f192c6cc9f7d5e9fa185960e9a7567e/deep/0/Notes.jpg)

- [Ajoutez](http://faceofgeoff.com/post/9665888623/nvalt-quick-tip-making-markdown-readable-and-your) les bons types d'extensions de fichier (nvALT ne met pas d'extension à ses fichiers textes, mais effectuer cette opération lui permet de lire tous les fichiers markdown que l'on copie dans son dossier notes à partir de l'extérieur)

- Réglez quelques options

![Options d'édition](https://www.evernote.com/shard/s89/sh/82ccea41-1213-49cc-b27a-560e5597123a/e2f9e19ce8a78478b039bc865e25fe7c/deep/0/Editer.jpg)

- Choisissez une présentation horizontale ou verticale
- Choisissez vos thèmes et couleurs

![Polices et couleurs](https://www.evernote.com/shard/s89/sh/47065da6-a7b9-455d-bbe9-e374ce58dcdc/224e495255f8b9ba9a33f3cb6010a48f/deep/0/Polices/Couleurs.jpg)

## Importer ses notes

Si vous preniez vos notes dans un autre format ou logiciel et que vous faites le grand saut vers le mode hacker, vous pourrez trouver quelques utilitaires et scripts intéressants pour récupérer vos notes et les exporter en Markdown.

- pour [Simplenote](http://simple-backup.appspot.com/)
- pour [Evernote](https://fr.support.evernote.com/link/portal/16051/16135/Article/3149/Exporter-des-notes-et-des-carnets-de-notes-dans-Evernote-pour-Mac)
- pour [Springpad](http://springpad.com/#!/_mak_/explore/sharedapplications/blocks/note/springpaddataextractor)

On trouve également quelques scripts sh/python/ruby sur [github](https://github.com/) pour exporter et transformer quelques formats de notes particuliers.
