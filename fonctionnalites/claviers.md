---
layout: single
title: Claviers
permalink: /fonctionnalites/claviers/
toc: true
toc_label: "Claviers"
toc_icon: "grip"
sidebar:
  nav: "fonctionnalites"

---

L'application comprend différents claviers qui ont été créés afin de simplifier la saise de certaines valeurs et donc de limiter la possibilité d'erreur de saisie.

Un clavier est découpé en une zone de réponse et une zone de saisie.

## Zone de réponse

![Zone de réponse]({{ site.baseurl }}/images/fonctionnalites/claviers/zone_reponse.png)

Description des boutons de la zone de réponse :

- ![bouton "Question suivante"]({{ site.baseurl }}/images/fonctionnalites/claviers/comment-arrow-right-outline.png){: width="32" } *Question suivante* qui permet de passer à la question suivante

- ![bouton "Justification"]({{ site.baseurl }}/images/fonctionnalites/claviers/comment-question-outline.png){: width="32" } *Justification* qui permet d'afficher la raison
pour laquelle la question est posée et ce qui sera fait avec la réponse. Cette fonctionnalité est en cours de développement et elle n'est présente que pour certaines questions.
- ![bouton "Agrandir"]({{ site.baseurl }}/images/fonctionnalites/claviers/chevron-double-up.png){: width="32" } *Agrandir* qui permet d'agrandir la zone d'encodage.
- ![bouton "Soumettre"]({{ site.baseurl }}/images/fonctionnalites/claviers/send.png){: width="32" } *Soumettre* qui envoie la réponse à l'application.
Si la réponse fournie n'est pas valide, le bouton n'est pas actif et affiche un symbole d'erreur.
- TODO: mettre symbole d'erreur ici

## Zone de saisie

Cette zone affiche un clavier différent en fonction des données à saisir.

Chaque clavier permet de saisir une valeur qui sera affichée dans la zone de réponse et qui pourra être soumise avec le bouton
![bouton "Soumettre"]({{ site.baseurl }}/images/fonctionnalites/claviers/send.png){: width="32" }.

{% include fonctionnalites/claviers/bassin.md %}

{% include fonctionnalites/claviers/choix.md %}

{% include fonctionnalites/claviers/code_barre.md %}

{% include fonctionnalites/claviers/condition_meteo.md %}

{% include fonctionnalites/claviers/date.md %}

{% include fonctionnalites/claviers/liste.md %}

{% include fonctionnalites/claviers/luminance.md %}

{% include fonctionnalites/claviers/numerique.md %}
