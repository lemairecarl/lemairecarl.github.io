---
layout: post
title: "L'univers fascinant de<br>l'apprentissage profond"
permalink: /apprentissage-profond/
excerpt_separator: "<!--more-->"
---

Il y a trois semaines, j'ai commencé une maîtrise en apprentissage profond appliqué à la vision. J'ai commencé à m'intéresser au _"deep learning"_ il y a quelques mois. Je trouve ce sujet fascinant! J'ai découvert une quantité de choses qui méritent d'être partagées. Voici donc la raison de la naissance de ce blog.

En quoi l'apprentissage profond est-il _profond_? Avant de pouvoir répondre à cette question qui vous réveille la nuit, il faut d'abord dévoiler quelques concepts importants : **intelligence artificielle**, **apprentissage automatique**, et **réseaux de neurones artificiels**.

<!--more-->

## L'intelligence artificielle

>L'intelligence artificielle est une discipline scientifique recherchant des méthodes de résolution de problèmes à forte complexité logique ou algorithmique. ([Wikipédia](https://fr.wikipedia.org/wiki/Intelligence_artificielle))

Ce domaine ne cherche pas à répliquer le fonctionnement d'un cerveau animal comme le nôtre. L'intelligence artificielle cherche à résoudre des problèmes qui nécessitent de l'intelligence. Par exemple : faire des calculs mathématiques ou jouer aux échecs. Pour ces deux exemples, il est possible de concevoir des "recettes" que l'ordinateur pourra exécuter, étape par étape.

La force de l'ordinateur est qu'il exécute des millions d'étapes par seconde sans se tromper. Suivant cette définition, l'intelligence artificielle ne devrait pas vous faire plus peur qu'un cuisinier hyperactif et rigoureux. (Notons qu'en ajoutant l'adjectif _violent_, on obtient la définition de Gordon Ramsay. Heureusement, un microprocesseur n'est pas violent.)

## L'apprentissage automatique

L'apprentissage automatique (_Machine Learning_, "ML") est un champ d'étude de l'intelligence artificielle. Le _Machine Learning_ permet de créer un système qui se forme une "compréhension" d'un problème en étant exposé à des exemples.

Un programme informatique typique est une "recette" spécifiée entièrement par le programmeur. Avec le ML, une partie importante du programme n'est pas donnée par le programmeur : elle est "apprise" automatiquement.

Voyons un usage du ML qui a beaucoup de succès : la reconnaissance d'images. Le défi ici est de faire un système qui prend une photo et donne une description de ce qui se trouve dans cette photo. Une belle motivation à relever ce défi est de permettre aux malvoyants d'utiliser des applications qui contiennent beaucoup d'images.

### La classification

Typiquement, lorsqu'on parle de reconnaissance d'images, on parle de classification. D'abord, on fixe un certain nombre de classes, par exemple : chat, chien, auto, avion, camion, etc. Ensuite, on constitue une base de données d'exemples, où on associe des images avec leur classe respective. Enfin, on conçoit l'algorithme d'apprentissage qui va nous permettre d'obtenir une "compréhension abstraite" du problème.

Grâce à cette "compréhension abstraite", le **classificateur** dira "chat!" en voyant une photo de chat, ou "grenouille!" en voyant une photo de grenouille. Si on ne lui a pas montré d'exemples de cuisinier, il ne sera pas capable de reconnaître cette classe. L'apprentissage se déroule comme suit :

1. On initialise la "compréhension abstraite" (concrètement : un tas de nombres) avec du n'importe quoi. Le classificateur se trompera donc très souvent au départ.
2. Le classificateur prend une image et tente de déterminer sa classe.
3. Le classificateur donne une probabilité pour chaque classe. S'il voit une photo de chat, il va éventuellement donner quelque chose dans ce genre : `chat = 60%, chien = 35%, cheval = 5%`. Cependant, au début de l'apprentissage, ça risque plutôt de ressembler à ceci : `chat = 1%, chien = 4%, cheval = 95%` (n'importe quoi!).
4. On calcule la _perte_, un nombre qui indique à quel point le classificateur se trompe. La magie du [mathématiques][diff] nous permet d'obtenir la [dérivée][deriv] de la _perte_.
5. Grâce à la dérivée de la _perte_, on sait exactement comment modifier la "compréhension abstraite" afin que le classificateur ait appris de son erreur.
6. On retourne à l'étape 2 et on continue jusqu'à avoir vu tous les exemples (idéalement plusieurs fois).

Ouf! Toute une aventure! À ce moment, la "compréhension abstraite" accumulée permet au classificateur de deviner le contenu d'une image sans trop se tromper. En fait, pour 10 classes, il se trompera environ  7 fois sur 10. **"Quoi??? C'est pathétique!"** me direz-vous. Vous avez raison, mais...

Ce qu'il faut garder en tête, c'est qu'en pigeant une classe au hasard, on se tromperait 9 fois sur 10. On réussirait une fois sur dix, par la chance. Puisque le classificateur réussit trois fois sur dix, il est trois fois meilleur! Évidemment, on ne se satisfera pas de cette performance très ordinaire. C'est là que **l'apprentissage profond** entre en jeu!

Avant de passer au prochain sujet, récapitulons. Grâce à l'apprentissage automatique, on peut apprendre à un ordinateur comment deviner le contenu d'une photo. L'ordinateur ne suivra pas une liste d'étapes : il va utiliser une "compréhension abstraite" obtenue par un processus d'apprentissage.

Je vais conclure cette section en avec une touche historique. Étonnamment, beaucoup de connaissances du ML existent depuis les années 80! C'est seulement récemment qu'on en récolte les fruits. Le succès de l'apprentissage automatique dépend principalement de deux choses:

- La **quantité de données** dont on dispose;
- La **puissance de calcul** dont on dispose.

À notre époque, ce ne sont pas des ressources qui manquent.

[diff]: https://fr.wikipedia.org/wiki/Différentielle
[deriv]: https://fr.wikiversity.org/wiki/Fonction_dérivée

## L'apprentissage profond

_À venir..._