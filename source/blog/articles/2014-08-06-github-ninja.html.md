---
date: 2014-08-06
slug: github-ninja
title: Astuce raccourcis GitHub
description: "Voici ma méthode de travail pour être plus efficace avec git et GitHub en utilisant les raccourcis claviers"
image: https://octodex.github.com/images/dojocat.jpg
page_title: Devenir un ninja sur GitHub
page_emphasis: Configurer git comme un pro
changefreq: monthly
priority: 0.8
---

Si je ne devais choisir qu'un seul outil [dans tous ceux que j'utilise](/uses.html), je choisirais sans hésiter le terminal. Concernant le site web se serait [GitHub](http://github.com). Je passe beaucoups de temps à utiliser ces solutions, autant essayer d'être efficace.
Créer / connaitre différents raccourcis vous fera gagner de précieuses secondes. Vous êtes plus productif, votre travail est plus efficace et vous libère du temps pour régler de vrais problèmes.

<div class="row align-center">
<div class="medium-4 columns">
<img src="https://octodex.github.com/images/dojocat.jpg" alt="Github ninja octocat">
</div>
</div>

## Des alias git

À mon avis la première chose à faire, sur vous utilisez git, est de pimper votre fichier `.gitconfig`.


~~~ json
    [user]
      name = Bruce Wayne
      email = bruce@wayne.com
    [push]
      default = current
    [alias]
      poule = pull --rebase
      co = checkout
      br = branch
      today = log --since=midnight --author='Bruce Wayne' --oneline
    [color]
      ui = auto
~~~

- __git poule__ - Récupérer la dernière version du projet.
- __git br__ - Afficher la liste de vos branches.
- __git co__ - Changer de branche.
- __git push__ - Pousser vos modifications "dans le cloud" (dans mon cas la branche courante)
- __git today__ - Qu'est ce que j'ai fait aujourd'hui ?

Cette liste est simple et peut être grandement améliorée mais c'est ce que j'utilise 80% du temps.

## Raccourcis claviers


Les logiciels traditionnels et les application web ne sont pas si différentes. Gardez cela à l'esprit et essayez d'utiliser les raccourcis aussi souvent que possible sur [GitHub](http://github.com) pour aider à réduire le temps passé sur le site.

<iframe width="560" height="315" src="//www.youtube.com/embed/3PsVvjWy21Q?rel=0" frameborder="0" allowfullscreen></iframe>

Liste des raccourcis claviers:

- __g c__ – Afficher le code du projet.
- __g i__ – Voir les issues.
- __t__ – Lors de l'affichage du code source, avoir le comportement d'un explorateur de fichier.
- __c__ – Ouvrir une nouvelle issue.
- __r__ – Répondre à une issue + _bonus_ Sélectionne le texte pour faire une citation.
- __?__ – Voir le menu d'aide avec les raccourcis.

Si vous avez d'autres idées / astuces n'hésitez pas à me les envoyer !
