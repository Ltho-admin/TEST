---
layout: page
title: Aphanomyces astaci
description: Aphanomyces astaci
img: assets/img/peste_1.jpg
importance: 1
category: work
related_publications: true
---

Texte à ajouter pour l'exemple concernant la peste de l'écrevisse
Texte à ajouter pour l'exemple concernant la peste de l'écrevisse
Texte à ajouter pour l'exemple concernant la peste de l'écrevisse
Texte à ajouter pour l'exemple concernant la peste de l'écrevisse

Texte à ajouter pour l'exemple concernant la peste de l'écrevisse
Texte à ajouter pour l'exemple concernant la peste de l'écrevisse

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="exemple d'image à changer" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="exemple d'image à changer" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="exemple d'image à changer" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Exemple de légendes des 3 photos indiquées ci-dessus. Et c'est possible de faire la même avec 1 ou 2 ou X photos.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="exemple d'image en grand format" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Là aussi, la possibilité de mettre une légande, pour une grande photo en mode portrait.
</div>

Bien entendu, il est tout à fait possible d'écrire du texte entre les images, et même d'inclure des citations ! {% cite tan_order_2018 %}.
On peut aussi continuer à décrire le projet avant d'ajouter tout un autre stock d'image + bas.

Bref, c'est assez facile à paramétrer !

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="encore d'autres images d'exemple" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="encore d'autres images d'exemple" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Il est même possible de faire du 2/3 + 1/3 concernant les images affichées, comme dans l'exemple ici !
</div>

A garder pour moi :

Il suffit d’encapsuler vos images dans une balise `<div class="col-sm">` et de les placer à l’intérieur d’une balise `<div class="row">` (voir plus d’informations sur le <a href="https://getbootstrap.com/docs/4.4/layout/grid/">système de grille de Bootstrap</a>).
Pour rendre les images adaptatives, ajoutez la classe `img-fluid` à chacune d’elles ;
pour obtenir des bords arrondis et des ombres, utilisez les classes `rounded` et `z-depth-1`.
Voici le code correspondant à la dernière rangée d’images ci-dessus :

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
