---
layout: page
title: Demo Contenu
subtitle: Demonstration du contenu des pages et des articles
navbar: Demo
tags: StudioJekyll-StarterKit Bootstrap4 exemple
comments: true
---

Le thème **starter** a été développé avec [**Bootstrap 4**](https://v4-alpha.getbootstrap.com/). Vous trouverez dans cette page les principaux exemples des possibilités de contenu des pages et des articles, combinant à la fois une syntaxe `markdown`, une syntaxe `HTML` et l'utilisation de composants Bootstrap 4.

Pour une vue exhaustive des possibilités, je vous invite à parcourir la [**documentation de Boostrap 4**](https://v4-alpha.getbootstrap.com/components/alerts/).



---

<h2 class="display-1 pb-5">Typographie</h2>


# Titres

## titre 2

### titre 3

#### titre 4

##### titre 5

###### titre 6

---

## Lignes

Vous pouvez utiliser le tag `<mark>` pour mettre en <mark>surbrillance</mark> un texte.

<del>Cette ligne de texte est à considérer comme supprimée.</del>

<u>Celle-ci est soulignée</u>

<small>Cette ligne est écrite en petits caractères</small>

**Cette ligne utilise des caractères gras.**

_Cette ligne est écrite en italique._

---

## Citations

###### Citation simple

> Les opportunités sont comme les autobus, il y en a toujours un autre qui arrive. **Richard Branson**.

###### Un peu plus sophistiqué, mais quand même très facile à faire

<blockquote class="blockquote">
  <span class="fa fa-quote-left"></span> ne le gâchez pas en menant une existence qui n’est pas la vôtre. Ne soyez pas prisonnier des dogmes qui obligent à vivre en obéissant à la pensée d’autrui. Ne laissez pas le brouhaha extérieur étouffer votre voix intérieure. Ayez le courage de suivre votre cœur et votre intuition. L’un et l’autre savent ce que vous voulez réellement devenir. Le reste est secondaire.
  <span class="blockquote-footer">**Steve Jobs** - 2005</span>
</blockquote>

---

## Listes

* liste
* liste
* liste
  * sous-liste
  * sous-liste
* liste

1. liste numérotée
1. liste numérotée
1. liste numérotée

---

<h2 class="display-1 pb-5">Code</h2>

Par example `<section>` peut être integré au sein même d'une ligne.

Ou alors il est encore possible d'écrire un block de code

```html
/* my code block */
<div class="myclass">
  this is ok  ok   ok
</div>
```

A noter que nous utilisons la syntaxe markdown beaucoup plus pratique que Bootstrap dans ce cas là.

Vous pouvez aussi utiliser le raccourci clavier <kbd>CTRL + P</kbd> pour avoir accès aux commandes de visual studio code.

Enfin voici un exemple de résultat de sortie

<div class="samp">
```
file1.txt   16.8 kb  
file2.txt    5.0 kb *  
...  
file3.txt 1024.0 kb  
-------
```
</div>

---

<h2 class="display-1 pb-5">Images</h2>

###### Standard

![sailing](http://wiki.maggire.net/assets/img/sjsailing.jpg)

###### Avec ombre

<img class="img-shadow" alt="" src="http://wiki.maggire.net/assets/img/sjsailing.jpg">

###### En lettrine en debut de paragraphe

<img class="rounded float-left pt-2 mr-3" width="200px" alt="" src="http://wiki.maggire.net/assets/img/sjsailing.jpg">

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est labor

---

<h2 class="display-1 pb-5">Tables</h2>

###### Tableau markdown par defaut

|**colonne1**|**colonne2**|**colonne3**|**colonne4**|
|1A|2A|3A|4A|
|1B|2B|3B|4B|


<h2 class="display-1 pb-5">Alertes</h2>

###### Messages et alertes standards Bootstrap4

<p class="alert alert-success" role="alert">
  :+1: **Super** You successfully read this important alert message.
</p>
<p class="alert alert-info" role="alert">
  **Information** Message d'information !
</p>
<p class="alert alert-warning" role="alert">
  :warning: **Attention** Message d'avertissement à lire.
</p>
<p class="alert alert-danger" role="alert">
  :exclamation: **Alerte** Information très importante.
</p>
