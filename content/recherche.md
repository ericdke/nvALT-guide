---
title: Recherche de notes
---

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
