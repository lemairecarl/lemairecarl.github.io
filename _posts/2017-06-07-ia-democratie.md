---
layout: post
title: "La démocratie directe grâce à l'intelligence artificielle"
permalink: /ia-democratie/
sorte: Essai
excerpt_separator: "<!--more-->"
---

On nous dit qu'on vit dans une société plus démocratique que jamais. Pourtant, notre système politique est très loin de la démocratie directe. Il semble même que [les démocraties occidentales modernes aient été fondées par une élite qui méprisait le peuple](https://www.youtube.com/watch?v=KVW5ogGDlts).[^1] Le pouvoir n'est pas dans les mains du peuple, qui ne s'exprime qu'une fois tous les quatre ans. Le pouvoir s'accumule dans les mains des propriétaires d'entreprises, et l'accumulation est effrénée dans le cas des entreprises technologiques.

Les élites technologiques accumulent à une vitesse fulgurante des données en tous genres et la puissance de calcul pour pouvoir les traiter et ainsi avoir une compréhension détaillée de la vie des gens. Cette compréhension leur permet proposer aux gens une myriade de produits et services, correspondant parfaitement au profil de chacun. C'est l'intelligence artificielle (IA) qui leur donne ces pouvoirs, et le peuple est tenu loin de ceux-ci. Serait-il possible de renverser la vapeur et d'utiliser l'IA pour redonner du pouvoir au peuple?

<!--more-->

À mon avis, oui, c'est possible. Ce ne se fera pas du jour au lendemain, mais je crois que l'IA aura un rôle important à jouer dans la transition vers une démocratie plus directe. J'ai un exemple concret à vous montrer, un outil. Ce projet s'appelle « Une mappe d'idées pour le Québec ». Je vous propose d'aller essayer l'outil en question, et de revenir ici pour mieux le comprendre.

<a href="https://lemairecarl.github.io/fautquonseparle/mappe">
![Mappe d'idées pour le Québec]({{ site.url }}/assets/mappe2.gif)
</a>

[Accéder à _Une mappe d'idées pour le Québec_](https://lemairecarl.github.io/fautquonseparle/mappe)

### Faut qu'on se parle

« Faut qu'on se parle » est une initiative politique non partisane lancée par Jean-Martin Aussant, Claire Bolduc, Véronique Côté, Maïtée Labrecque-Saganash, Aurélie Lanctôt, Karel Mayrand, Gabriel Nadeau-Dubois, Will Prosper et Alain Vadeboncoeur.

>« À l’automne 2016, quand nous avons lancé la tournée "Faut qu’on se parle", nous l’avons fait pour ranimer un espace public pâlot, hyperactif mais anémique [...]. Nous avons intitulé notre initiative en faisant référence à cette injonction douce mais sérieuse qu’on adresse à nos aimés quand la situation mérite une vraie grosse mise au point. Nous avons ainsi lancé au Québec entier dix questions liées à dix grands thèmes: démocratie, économie, régions, indépendance, éducation, Premiers Peuples, diversité, culture, santé, climat. Nous voulions entendre ce que les gens avaient à proposer comme solutions. Les Québécois ont des bonnes idées. On s’est dit: allons les écouter. »[^2]

Il s'agit d'un projet qui a donné la parole à des communautés qui n'ont pas souvent été écoutées.

>« D’abord, nous avons orchestré dix grandes consultations publiques dans des petites et grandes villes aux quatre coins du Québec. [...] Ensuite, parallèlement à ces grands rassemblements, nous nous sommes laissés inviter chez vous pour des assemblées de cuisine organisées par vos bons soins. Lors de cette vaste expédition qui nous a menés partout sur le territoire – de Matane à Kuujjuaq, de Joliette à Val-d’Or, de Natashquan à Saint-Lambert –, nous sommes littéralement allés à votre rencontre. [...] Nous avons été reçus par une variété impressionnante de groupes, des gens de toutes les générations, des sourds, des nouveaux arrivants, des communautés autochtones, diverses communautés culturelles, et 60 % des assemblées de cuisine se sont déroulées hors de la grande région montréalaise. »[^2]

Pendant le projet, tout le monde était invité à inscrire, sur le site web du projet, leurs solutions aux dix enjeux susmentionnés (démocratie, économie, régions, indépendance, éducation, Premiers Peuples, diversité, culture, santé, climat). 5357 réponses ont été amassées, et ont été lancées dans l'espace publique. Un fichier _Excel_ avec 5357 lignes, chaque ligne dans le format « question : réponse ». Une base de données contenant des idées de Québécois et Québecoises pour faire progresser le Québec.

### La force du nombre

J'ai vu dans cette base de données une opportunité : l'opportunité de faire une expérience sur la démocratie directe. Quel est le lien entre 5357 opinions et la démocratie directe? La démocratie existe lorsque les citoyens ont un impact sur la direction que prend leur nation. Pour avoir un impact, il faut pouvoir s'exprimer. Malheureusement, il y a trop de gens et trop d'idées au Québec, et ces dernières ne peuvent pas toutes êtres entendues par le gouvernement.

Normalement, pour qu'une idée se rende au gouvernement, elle doit être formulée à un représentant, un député, qui lui se chargera d'amener l'idée plus haut. Maintenant, imaginons un instant que les citoyens puissent formuler leurs idées directement au gouvernement. Le problème, c'est que les décisions qui sont prises touchent des milliers de personnes. Une idée doit concerner un grande nombre de personnes pour être considérée. C'est la force du nombre.

![Hall of Shame]({{ site.url }}/assets/paquet.png)
_Un paquet d'idées similaires (vraies données de Faut qu'on se parle)._

Mais comment peut-on avoir la force du nombre lorsque tous formulent leur propre opinion librement? Il faut tenter de regrouper les idées en paquets. Une opinion va probablement être partagée par des centaines, voire des milliers de personnes. Si on pouvait prendre la mer d'opinion et la regrouper en paquets, où chaque paquet contient différentes formulations de la même idée, on trouverait la force du nombre tant désirée! Voilà l'objectif que je me suis donné.

### Diamant brut

J'ai utilisé des techniques de la science des données pour permettre ces regroupements. Mais la tâche n'a pas été facile : les données de _Faut qu'on se parle_ sont... disons « organiques ». Organiques dans le sens où les gens ont écrit ce qui leur passait par la tête, avec leur propres capacités d'écriture. Cela implique que la base de données contient énormément de fautes de français! Certaines réponses demandaient d'être déchiffrées, et d'autres étaient simplement incompréhensibles.

![Hall of Shame]({{ site.url }}/assets/retroconstruire.png){:style="border: 1px solid #aaa"}
_Un aperçu des mots mal orthographiés (ou inexistants) que j'ai trouvés._

J'ai donc passé la majorité de mon temps sur ce projet à préparer les données pour qu'elles soient utilisables. J'ai corrigé des centaines de fautes d'orthographe. Comment quelqu'un peut-il trouver la motivation à corriger des centaines de fautes dans son temps libre? Caféine. Beaucoup. Évidemment, avec une plus grande base de données, il faudrait utiliser un autre moyen, comme par exemple de forcer l'utilisation d'un système de correction (à la Antidote) avant l'envoi du texte.

### Espace à 64 dimensions

Une fois que les données ont été prêtes, je les ai transformées. Avec un algorithme, j'ai converti chaque réponse textuelle en une suite de 64 nombres — un vecteur de taille 64. Une fois qu'on a un tas de vecteurs, on peut faire toutes sortes de belles choses! Par exemple, on peut entraîner un réseau de neurones à prédire quelle est la question qui est à l'origine de la réponse! Je l'ai fait, et mon classificateur a un taux de réussite de 99% !

Mais ce n'est pas le but de l'exercice. Le but est de pouvoir regrouper les réponses par similarité. Voyons comment c'est possible. Supposons que les réponses sont encodées sous forme de vecteur en trois dimensions (trois nombres). On peut alors imaginer que les textes ont une position dans l'espace (x, y, z). Si le vecteur représente bien son texte correspondant, alors on peut s'attendre à ce que deux textes similaires soient situés à proximité dans l'espace 3D !

Bien sûr, il faut que la méthode d'encodage des textes en vecteurs soit fiable. En pratique, une taille 3 est largement insuffisante pour représenter un texte. Dans mon cas, j'ai utilisé un espace à 64 dimensions ! Mais à quoi ça sert des vecteurs à 64 dimensions ! Comment fait-on pour visualiser un tel espace qui sort du cadre de notre réalité physique ? J'ai utilisé une technique nommée « t-SNE », qui permet de visualiser des données à haute dimensionnalité en les projetant dans un espace à deux ou trois dimensions.

Cette conversion est un compromis : on perd certaines informations, mais on peut facilement visualiser les relations entre les données. S'il existe un regroupement de textes similaires, ils seront placés à proximité ! Exactement ce dont on avait besoin ! Et les 5357 réponses sont traitées en moins de 15 minutes sur un _laptop_.

![Mappe d'idées pour le Québec]({{ site.url }}/assets/mappe2.gif)

Le résultat de cette méthode est [la mappe d'idées pour le Québec](https://lemairecarl.github.io/fautquonseparle/mappe) dont j'ai parlé plus haut. Je n'entrerai pas ici dans les détails d'implémentation ; j'expliquerai la méthode étape par étape dans un article de vulgarisation.

### Conclusion

Bref, voici un exemple de projet qui met l'intelligence artificielle et la science des données au service de la démocratie. Le projet est une preuve de concept ; malheureusement, la quantité et la fiabilité des données ne sont pas suffisantes pour justifier des actions de la part des élus. Malgré tout, on peut imaginer que ce genre de projet puisse un jour amplifier la force du nombre et aider à porter la voix du citoyen.

Merci de m'avoir lu! N'hésitez pas à donner votre point de vue dans les commentaires.

---

## Notes et références

[^1]: [Dupuis-Déri, Francis](https://politique.uqam.ca/corps-professoral/professeurs/162-dupuis-deri-francis.html). _Démocratie : histoire politique d'un mot - aux États-Unis et en France_. Montréal, Lux, 2013.

[^2]: Jean-Martin Aussant, Claire Bolduc, Véronique Côté, Maïtée Labrecque-Saganash, Aurélie Lanctôt, Karel Mayrand, Gabriel Nadeau-Dubois, Will Prosper, Alain Vadeboncoeur. _Ne renonçons à rien_. Montréal, Lux, 2017.