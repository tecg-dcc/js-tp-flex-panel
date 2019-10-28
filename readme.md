# Flex Panel Gallery
> JS exercise given at HEPL

* * *

**js-tp-flex-panel-gallery** is an educational project, which will be used for `JS` courses.

**Note:** the school where the course is given, the [HEPL](http://www.provincedeliege.be/hauteecole) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

> Lors de vos cours de *web*, vous allez découvrir le langage *JavaScript* et le mettre en pratique pour apprendre à rendre vos pages web interactives.  

* * *
Dans le cadre de cet exercice, nous vous demandons de provoquer des animations *css* par *Javascript*. 

![](readme.gif)

## Énoncé
Votre mission est de contrôler l’ouverture du panneau, en deux temps :
1. au clic, JavaScript déclenche l’animation qui élargit le panneau ; 
2. quand celle-ci se termine, JavaScript déclenche l’apparition du texte.

## Aides

1. Sur chacun des `.panel` vous devrez ajouter une classe `open` au clic pour provoquer l'ouverture de ce panel. 
2. Quand la _transition_ **css** de cette ouverture se termine (voir l'écouteur d'événement [transitionend](https://developer.mozilla.org/fr/docs/Web/Events/transitionend), vous devez ajouter la classe `open-active` qui fait apparaître le texte.
2. Quand on clique une seconde fois sur un `.panel` alors qu'il est déjà ouvert, les classes `open` et `open-active` doivent être retirées.

## Bonus

1. Éviter que 2 `.panel` soit ouvert en même temps. Concrètement quand un `.panel` est déjà ouvert et qu'on essaye d'ouvrir un autre, l'ancien panel doit d'abord être refermé de sorte qu'il n'y ait qu'un seul panel qui soit ouvert à la fois. 

## Source

[JavaScript30](https://javascript30.com) de [Wes Bos](https://wesbos.com)
