Ã¯Â»Â¿---
title: "ProbabilitÃƒÆ’Ã‚Â©s et amplitudes quantiques"
description: "Amplitudes de probabilitÃƒÆ’Ã‚Â©, probabilitÃƒÆ’Ã‚Â©s et principes."
authors:
  - name: Gilles Nguyen Vien
    affiliation: DÃƒÆ’Ã‚Â©partement de Physique, UniversitÃƒÆ’Ã‚Â© de Bretagne Occidentale
license:
  id: "CC-BY-NC-ND-4.0"

date: 2026-01-19
---

# ProbabilitÃƒÆ’Ã‚Â©s et amplitudes quantiques

## Introduction


Nous avons vu que le concept de photon s\'est imposÃƒÆ’Ã‚Â© pour expliquer
certains phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes impliquant des ondes ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tiques. Einstein a
ÃƒÆ’Ã‚Â©mis en 1905 l\'idÃƒÆ’Ã‚Â©e selon laquelle la thÃƒÆ’Ã‚Â©orie ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tique de
Maxwell n\'est correcte que statistiquement, c\'est-ÃƒÆ’Ã‚Â -dire dans des
situations faisant intervenir un grand nombre de photons. L\'expÃƒÆ’Ã‚Â©rience
confirme cette hypothÃƒÆ’Ã‚Â¨se aujourd\'hui.

Les objets \"quantiques\" qui sont caractÃƒÆ’Ã‚Â©risÃƒÆ’Ã‚Â©s par la dualitÃƒÆ’Ã‚Â©
onde/corpuscule sont appelÃƒÆ’Ã‚Â©s \"quantons\" pour ne pas favoriser un
aspect par rapport ÃƒÆ’Ã‚Â  l\'autre.

Nous commencerons l\'ÃƒÆ’Ã‚Â©laboration d\'un schÃƒÆ’Ã‚Â©ma thÃƒÆ’Ã‚Â©orique qui vise ÃƒÆ’Ã‚Â 
interprÃƒÆ’Ã‚Â©ter les phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes impliquant des quantons. Les lois ÃƒÆ’Ã‚Â©noncÃƒÆ’Ã‚Â©es
s\'appliqueront ÃƒÆ’Ã‚Â  tous les quantons mais nous attacherons une importance
particuliÃƒÆ’Ã‚Â¨re au photon.

Nous verrons que la notion de probabilitÃƒÆ’Ã‚Â© est indispensable. En effet
les lois de la physique quantique sont fondamentalement probabilistes.
La notion de probabilitÃƒÆ’Ã‚Â© est cependant insuffisante : le concept
**d'{index}`amplitude de probabilitÃƒÆ’Ã‚Â©`** est nÃƒÆ’Ã‚Â©cessaire pour expliquer
l\'interfÃƒÆ’Ã‚Â©rence quantique. Les rÃƒÆ’Ã‚Â¨gles relatives au calcul des amplitudes
et des probabilitÃƒÆ’Ã‚Â©s jouent le rÃƒÆ’Ã‚Â´le de postulats de la thÃƒÆ’Ã‚Â©orie quantique.

## La notion de probabilitÃƒÆ’Ã‚Â© en physique quantique

Montrons que la notion de probabilitÃƒÆ’Ã‚Â© est indispensable ÃƒÆ’Ã‚Â 
l\'interprÃƒÆ’Ã‚Â©tation des phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes lumineux mais pas insuffisante.

### Loi de Malus

ConsidÃƒÆ’Ã‚Â©rons une onde plane polarisÃƒÆ’Ã‚Â©e rectilignement (lumiÃƒÆ’Ã‚Â¨re
monochromatique) incidente sur un polariseur rectiligne dont l\'axe est
selon la direction du vecteur unitaire $\overrightarrow{a}$.
L\'amplitude du champ ÃƒÆ’Ã‚Â©lectrique est $E_{0}$ et l\'intensitÃƒÆ’Ã‚Â© est $I_{0}$
aprÃƒÆ’Ã‚Â¨s la traversÃƒÆ’Ã‚Â©e du polariseur. Un second polariseur, identique au
premier mais dont l\'axe est suivant le vecteur unitaire
$\overrightarrow{b}$ est placÃƒÆ’Ã‚Â© sur le chemin du faisceau transmis par le
premier polariseur. L\'amplitude transmise par le second polariseur
est :

$E_{t} = E_{0}\overrightarrow{a}.\overrightarrow{b} = E_{0}\cos\theta$
| oÃƒÆ’Ã‚Â¹ $\theta$ est l\'angle entre les axes des

```{figure} media/imagePol19.png
:name: fig-anglesPolar
:alt: Angles de polarisation
:width: 60%
Angles de polarisation.
```

L\'intensitÃƒÆ’Ã‚Â© mesurÃƒÆ’Ã‚Â©e aprÃƒÆ’Ã‚Â¨s le second  polariseur est donnÃƒÆ’Ã‚Â©e par :

$$I_{t} = I_{0}\cos^{2}\theta$$

Cette relation est appelÃƒÆ’Ã‚Â©e loi de Malus. 

Elle est en accord avec les prÃƒÆ’Ã‚Â©visions de la thÃƒÆ’Ã‚Â©orie de Maxwell. Ainsi
si l\'intensitÃƒÆ’Ã‚Â© [^41] varie comme $\cos^{2}\theta$ lorsqu\'on tourne le
deuxiÃƒÆ’Ã‚Â¨me polariseur [^42], la frÃƒÆ’Ã‚Â©quence de la lumiÃƒÆ’Ã‚Â¨re (et donc sa
couleur) ne change pas.

Nous allons chercher une interprÃƒÆ’Ã‚Â©tation de la loi de Malus ÃƒÆ’Ã‚Â  l\'aide du
concept de photon. Chaque photon est porteur de l\'ÃƒÆ’Ã‚Â©nergie
$\hslash\omega$.

Soit $N$ le flux de photons (nombre de photons transportÃƒÆ’Ã‚Â©s par unitÃƒÆ’Ã‚Â© de
temps et par unitÃƒÆ’Ã‚Â© de section du faisceau). L\'intensitÃƒÆ’Ã‚Â© du faisceau
incident c\'est ÃƒÆ’Ã‚Â  dire le flux en ÃƒÆ’Ã‚Â©nergie est :

$$I = N\hslash\omega$$

Puisque la proportion $\cos^{2}\theta$ de l\'ÃƒÆ’Ã‚Â©nergie incidente sur le
second polariseur est transmise on peut envisager deux hypothÃƒÆ’Ã‚Â¨ses :

1Ãƒâ€šÃ‚Â° une proportion $\cos^{2}\theta$ de chaque photon traverse le
polariseur,

2Ãƒâ€šÃ‚Â° une proportion $\cos^{2}\theta$ des photons est transmise
intÃƒÆ’Ã‚Â©gralement.

L\'hypothÃƒÆ’Ã‚Â¨se 1Ãƒâ€šÃ‚Â° combinÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  la loi de Planck - Einstein entraÃƒÆ’Ã‚Â®ne que la
frÃƒÆ’Ã‚Â©quence est multipliÃƒÆ’Ã‚Â©e par $\cos^{2}\theta$ ÃƒÆ’Ã‚Â  la sortie du second
polariseur. On devrait donc observer un changement de couleur en
tournant ce polariseur. Au-delÃƒÆ’Ã‚Â  d\'une certaine valeur de $\theta$, la
lumiÃƒÆ’Ã‚Â¨re transmise devrait mÃƒÆ’Ã‚Âªme ÃƒÆ’Ã‚Âªtre invisible. La frÃƒÆ’Ã‚Â©quence ne changeant
pas lors de la traversÃƒÆ’Ã‚Â©e d\'un polariseur, l\'hypothÃƒÆ’Ã‚Â¨se doit ÃƒÆ’Ã‚Âªtre
rejetÃƒÆ’Ã‚Â©e.

Selon l\'hypothÃƒÆ’Ã‚Â¨se 2Ãƒâ€šÃ‚Â° il y a une certaine fraction $\cos^{2}\theta$ des
photons qui sont transmis intÃƒÆ’Ã‚Â©gralement. On peut dire ainsi que la
probabilitÃƒÆ’Ã‚Â© pour qu\'un photon soit transmis est $\cos^{2}\theta$. Tous
les photons sont identiques et pourtant certains sont transmis alors que
d\'autres sont absorbÃƒÆ’Ã‚Â©s. MalgrÃƒÆ’Ã‚Â© de nombreuses tentatives personne n\'a
pu imaginer un mÃƒÆ’Ã‚Â©canisme qui permettrait de prÃƒÆ’Ã‚Â©dire avec certitude ce
qui arriverait ÃƒÆ’Ã‚Â  un photon donnÃƒÆ’Ã‚Â©. <u>La thÃƒÆ’Ã‚Â©orie quantique ne peut que
calculer la probabilitÃƒÆ’Ã‚Â© pour qu\'un photon soit transmis</u>.
Il est ÃƒÆ’Ã‚Â©videmment impossible de prÃƒÆ’Ã‚Â©dire ce qui arrivera ÃƒÆ’Ã‚Â  un photon
particulier : c\'est la **statistique se rapportant ÃƒÆ’Ã‚Â  un grand nombre
d\'ÃƒÆ’Ã‚Â©vÃƒÆ’Ã‚Â©nements qui permet de vÃƒÆ’Ã‚Â©rifier la thÃƒÆ’Ã‚Â©orie**.

### RÃƒÆ’Ã‚Â©flexion partielle de la lumiÃƒÆ’Ã‚Â¨re

ConsidÃƒÆ’Ã‚Â©rons le phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne familier de la rÃƒÆ’Ã‚Â©flexion partielle de la
lumiÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â  l\'interface entre deux milieux transparents. C\'est un
phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne qui est trÃƒÆ’Ã‚Â¨s bien expliquÃƒÆ’Ã‚Â© par la thÃƒÆ’Ã‚Â©orie ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tique de
Maxwell. Dans le cas d\'une incidence normale, le\
l\'expÃƒÆ’Ã‚Â©rience montre que 4 % de l\'ÃƒÆ’Ã‚Â©nergie incidente est rÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chie ; il
y a donc 96 % de l\'ÃƒÆ’Ã‚Â©nergie qui est transmise dans le second milieu.

Dans l'hypothÃƒÆ’Ã‚Â¨se de l'existence des photons et puisque tous les photons
sont identiques on peut se demander pourquoi certains sont rÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chis et
d\'autres sont transmis. On pourrait formuler l\'hypothÃƒÆ’Ã‚Â¨se que le verre
comporte un certain nombre de trous (cylindriques) et que les photons
arrivant dans un trou sont transmis alors que ceux qui arrivent entre
les trous sont rÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chis. Cette hypothÃƒÆ’Ã‚Â¨se est peu crÃƒÆ’Ã‚Â©dible car le mÃƒÆ’Ã‚Âªme
phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne s\'observe ÃƒÆ’Ã‚Â  la surface de l\'eau. Or les molÃƒÆ’Ã‚Â©cules sont
mobiles dans un liquide. Il n\'y a donc aucune raison de supposer qu\'il
existe des canaux vides qui permettent le passage des photons.

En outre, la quantitÃƒÆ’Ã‚Â© d\'ÃƒÆ’Ã‚Â©nergie rÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chie par une couche mince dÃƒÆ’Ã‚Â©pend
de son ÃƒÆ’Ã‚Â©paisseur. Dans le cas d\'un verre d\'indice de rÃƒÆ’Ã‚Â©fraction $1,5$
elle peut varier de $0$ ÃƒÆ’Ã‚Â  $16$ %. La quantitÃƒÆ’Ã‚Â© rÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chie tend ÃƒÆ’Ã‚Â  diminuer
avec l'augmentation de l'ÃƒÆ’Ã‚Â©paisseur de la lame. Ce fait montre qu\'il est
impossible d\'interprÃƒÆ’Ã‚Â©ter la rÃƒÆ’Ã‚Â©flexion partielle ÃƒÆ’Ã‚Â  partir d\'un modÃƒÆ’Ã‚Â¨le
gÃƒÆ’Ã‚Â©omÃƒÆ’Ã‚Â©trique simple de la lame mais il montre ÃƒÆ’Ã‚Â©galement l\'insuffisance
de la notion de probabilitÃƒÆ’Ã‚Â©. Si $4$ % des photons sont rÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chis sur la
premiÃƒÆ’Ã‚Â¨re face de la lame on ne peut pas expliquer comment l\'ÃƒÆ’Ã‚Â©nergie
rÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chie diminue avec l'augmentation de l'ÃƒÆ’Ã‚Â©paisseur de la lame.

### Nature granulaire de la lumiÃƒÆ’Ã‚Â¨re

On peut montrer expÃƒÆ’Ã‚Â©rimentalement la nature granulaire de la lumiÃƒÆ’Ã‚Â¨re en
utilisant un ÃƒÆ’Ã‚Â©clairage de trÃƒÆ’Ã‚Â¨s faible intensitÃƒÆ’Ã‚Â©. Si la thÃƒÆ’Ã‚Â©orie de
Maxwell ÃƒÆ’Ã‚Â©tait exacte l\'ÃƒÆ’Ã‚Â©nergie reÃƒÆ’Ã‚Â§ue varierait de la mÃƒÆ’Ã‚Âªme faÃƒÆ’Ã‚Â§on en tout
point de la surface ÃƒÆ’Ã‚Â©clairÃƒÆ’Ã‚Â©e. L\'expÃƒÆ’Ã‚Â©rience montre que ce n\'est pas ce
qui se produit (Figure 2). Au contraire, on voit apparaÃƒÆ’Ã‚Â®tre des taches
localisÃƒÆ’Ã‚Â©es produites par les impacts des photons. L\'existence de ces
derniers n\'est plus ÃƒÆ’Ã‚Â©vidente lorsque l\'ÃƒÆ’Ã‚Â©clairage est fort : les
fluctuations statistiques deviennent relativement moins importantes
lorsque le nombre de photons est grand.

L\'expÃƒÆ’Ã‚Â©rience d\'Young rÃƒÆ’Ã‚Â©alisÃƒÆ’Ã‚Â©e avec une source de trÃƒÆ’Ã‚Â¨s faible intensitÃƒÆ’Ã‚Â©
permet de mettre en ÃƒÆ’Ã‚Â©vidence les impacts localisÃƒÆ’Ã‚Â©s des photons sur la
plaque photographique {numref}`fig-clichÃƒÆ’Ã‚Â©s` :

**Photographie prise avec :**

```{figure} media/image24.png
:name: fig-clichÃƒÆ’Ã‚Â©s
:alt: ClichÃƒÆ’Ã‚Â©s sous diffÃƒÆ’Ã‚Â©rentes intensitÃƒÆ’Ã‚Â©s
:width: 90%
ClichÃƒÆ’Ã‚Â©s pris avec : a) $10^3$ photons b) $1,2 \times 10^4$ photons c) $9,3 \times 10^4$ photons d) $7,4 \times ^5$ photons e) $3,6 \times 10^6$ photons f) $2,8 \times 10^7$ photons
```

```{figure} media/image25.png
:name: fig-frangesY
:alt: Franges d\'Young ÃƒÆ’Ã‚Â  diffÃƒÆ’Ã‚Â©rentes intensitÃƒÆ’Ã‚Â©s
:width: 100%
Franges d\'Young ÃƒÆ’Ã‚Â  diffÃƒÆ’Ã‚Â©rentes intensitÃƒÆ’Ã‚Â©s : a) $28$ photons b) $1 000$ photons c) $10 000$ photons**
```

Les franges sombres et les franges brillantes dont l\'existence est
expliquÃƒÆ’Ã‚Â©e par la thÃƒÆ’Ã‚Â©orie ondulatoire apparaissent lorsque le nombre de
photons est assez grand.

Ici encore la notion de probabilitÃƒÆ’Ã‚Â© est insuffisante pour expliquer
l\'existence de franges sombres. En effet, la probabilitÃƒÆ’Ã‚Â© ÃƒÆ’Ã‚Â©tant un
nombre non nÃƒÆ’Ã‚Â©gatif, on ne peut pas obtenir une probabilitÃƒÆ’Ã‚Â© nulle de
recevoir un photon ÃƒÆ’Ã‚Â  certains endroits lorsque les deux fentes sont
ouvertes sans que la probabilitÃƒÆ’Ã‚Â© pour que le photon passe par chacune
des fentes soit nulle.

## Le comportement quantique

Avant d\'introduire le formalisme de la thÃƒÆ’Ã‚Â©orie quantique nous allons
prÃƒÆ’Ã‚Â©senter une expÃƒÆ’Ã‚Â©rience de pensÃƒÆ’Ã‚Â©e imaginÃƒÆ’Ã‚Â©e par R.P. Feynman qui dÃƒÆ’Ã‚Â©crit
bien les caractÃƒÆ’Ã‚Â©ristiques essentielles du comportement quantique. Ce
comportement quantique se rÃƒÆ’Ã‚Â©fÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â  l'ÃƒÆ’Ã‚Â©volution dans l'espace-temps d'un
systÃƒÆ’Ã‚Â¨me physique rÃƒÆ’Ã‚Â©alisÃƒÆ’Ã‚Â© au moyen d'une expÃƒÆ’Ã‚Â©rience. Une telle expÃƒÆ’Ã‚Â©rience
sera dÃƒÆ’Ã‚Â©crite par l'ÃƒÆ’Ã‚Â©tat initial du systÃƒÆ’Ã‚Â¨me ÃƒÆ’Ã‚Â©tudiÃƒÆ’Ã‚Â© et par ce mÃƒÆ’Ã‚Âªme ÃƒÆ’Ã‚Â©tat
dans un ÃƒÆ’Ã‚Â©tat final.

ConsidÃƒÆ’Ã‚Â©rons le dispositif de Young mais avec une source produisant des
corpuscules classiques des balles de fusils (indestructibles) comme le montre la {numref}`fig-corpClass` par
exemple .


```{figure} media/image22.png
:name: fig-corpClass
:alt: Corpuscules classiques
:width: 90%
Corpuscules classiques
```

Un ensemble de dÃƒÆ’Ã‚Â©tecteurs
permet de mesurer le nombre de balles reÃƒÆ’Ã‚Â§ues sur l\'ÃƒÆ’Ã‚Â©cran en fonction de
la position. Lorsque seul le trou 1 est ouvert cette distribution est
donnÃƒÆ’Ã‚Â©e par la courbe $N_1(y)$ et lorsque seul le trou 2 est ouvert elle
est donnÃƒÆ’Ã‚Â©e par $N_2(y)$. Pour la mÃƒÆ’Ã‚Âªme durÃƒÆ’Ã‚Â©e de fonctionnement, lorsque
les deux trous sont ouverts on obtient une distribution qui en chaque
point est la somme des prÃƒÆ’Ã‚Â©cÃƒÆ’Ã‚Â©dentes :

$$N_{12}(y) = N_{1}(y) + N_{2}(y)$$

De plus la dÃƒÆ’Ã‚Â©tection des balles donne lieu ÃƒÆ’Ã‚Â  des impacts bien dÃƒÆ’Ã‚Â©finis
dans l\'espace et dans le temps.

Gardons le mÃƒÆ’Ã‚Âªme dispositif mais remplaÃƒÆ’Ã‚Â§ons la source de particules
classiques par une source d\'ondes classiques. Lorsque seul le trou 1
est ouvert l\'intensitÃƒÆ’Ã‚Â© est donnÃƒÆ’Ã‚Â©e par $I_{1}(y)$ et lorsque seul le
trou 2 est ouvert, elle est donnÃƒÆ’Ã‚Â©e par la courbe $I_{2}(y)$ ({numref}`fig-interOndesClass`).

```{figure} media/image26.jpg
:name: fig-interOndesClass
:alt: Ondes classiques
:width: 90%
Ondes classiques
```

Par contre lorsque les deux trous sont ouverts l\'intensitÃƒÆ’Ã‚Â© mesurÃƒÆ’Ã‚Â©e sur
l\'ÃƒÆ’Ã‚Â©cran $I_{12}(y)$ ne ressemble en rien ÃƒÆ’Ã‚Â  celle qui est obtenue avec
des corpuscules classiques, c\'est-ÃƒÆ’Ã‚Â -dire qu\'elle est trÃƒÆ’Ã‚Â¨s diffÃƒÆ’Ã‚Â©rente
de la somme des intensitÃƒÆ’Ã‚Â©s mesurÃƒÆ’Ã‚Â©es avec un seul trou ouvert :

$$I_{12}(y) \neq I_{1}(y) + I_{2}(y)$$

A certains endroits on dÃƒÆ’Ã‚Â©tecte moins d\'ÃƒÆ’Ã‚Â©nergie avec deux trous ouverts
qu\'avec un seul trou. L\'interfÃƒÆ’Ã‚Â©rence est alors destructive. La
dÃƒÆ’Ã‚Â©tection de l\'ÃƒÆ’Ã‚Â©nergie se fait de maniÃƒÆ’Ã‚Â¨re continue dans le temps et
ÃƒÆ’Ã‚Â©talÃƒÆ’Ã‚Â©e dans l\'espace.

Supposons que la source ÃƒÆ’Ã‚Â©mette des ÃƒÆ’Ã‚Â©lectrons. Lorsqu\'un seul trou est
ouvert, on observe une distribution semblable ÃƒÆ’Ã‚Â  celle des corpuscules et
des ondes classiques. La dÃƒÆ’Ã‚Â©tection se fait cependant par impacts
localisÃƒÆ’Ã‚Â©s dans l\'espace et dans le temps, ce qui porte ÃƒÆ’Ã‚Â  croire que les
ÃƒÆ’Ã‚Â©lectrons sont des corpuscules.

Lorsque les deux trous sont ouverts le nombre d\'ÃƒÆ’Ã‚Â©lectrons dÃƒÆ’Ã‚Â©tectÃƒÆ’Ã‚Â©s
varie trÃƒÆ’Ã‚Â¨s rapidement avec la position manifestant un phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne
d\'interfÃƒÆ’Ã‚Â©rence. En fait la distribution ressemble beaucoup ÃƒÆ’Ã‚Â  la
fonction $I_{12}(y)$ reprÃƒÆ’Ã‚Â©sentant l\'intensitÃƒÆ’Ã‚Â© obtenue avec des ondes
classiques. Cependant la dÃƒÆ’Ã‚Â©tection se fait toujours par impacts
localisÃƒÆ’Ã‚Â©s dans l\'espace et dans le temps comme pour des corpuscules.

Les deux aspects, corpusculaire et ondulatoire, se manifestent dans la
mÃƒÆ’Ã‚Âªme expÃƒÆ’Ã‚Â©rience. On obtient le mÃƒÆ’Ã‚Âªme type de rÃƒÆ’Ã‚Â©sultats avec des photons
({numref}`fig-interOndesClass`), des neutrons ou mÃƒÆ’Ã‚Âªme des atomes.

Une consÃƒÆ’Ã‚Â©quence importante de la distribution des ÃƒÆ’Ã‚Â©lectrons observÃƒÆ’Ã‚Â©e
lorsque les deux trous sont ouverts <u>est qu\'il est impossible
d\'affirmer que chaque ÃƒÆ’Ã‚Â©lectron est passÃƒÆ’Ã‚Â© soit par un trou soit par
l\'autre</u>. En effet, si c\'ÃƒÆ’Ã‚Â©tait le cas on pourrait dire que
le nombre d\'ÃƒÆ’Ã‚Â©lectrons reÃƒÆ’Ã‚Â§us en chaque point est ÃƒÆ’Ã‚Â©gal au nombre
d\'ÃƒÆ’Ã‚Â©lectrons venus par le trou 1 plus le nombre d\'ÃƒÆ’Ã‚Â©lectrons venus par
le trou 2. [<u>Le nombre total d\'ÃƒÆ’Ã‚Â©lectrons reÃƒÆ’Ã‚Â§us en tout point lorsque
les deux trous sont ouverts ne pourrait jamais ÃƒÆ’Ã‚Âªtre infÃƒÆ’Ã‚Â©rieur au nombre
reÃƒÆ’Ã‚Â§us au mÃƒÆ’Ã‚Âªme point lorsqu\'un seul trou est
ouvert</u>]. Il n\'y aurait donc pas d\'interfÃƒÆ’Ã‚Â©rence.

On peut essayer de dÃƒÆ’Ã‚Â©terminer par quel trou passe chaque ÃƒÆ’Ã‚Â©lectron en les
ÃƒÆ’Ã‚Â©clairant ÃƒÆ’Ã‚Â  l\'aide d\'une source de lumiÃƒÆ’Ã‚Â¨re (Figure 6).

```{figure} media/eclairFentes.png
:name: fig-eclairFentes
:alt: Eclairage des fentes
:width: 90%
Eclairage des fentes
```

L\'ÃƒÆ’Ã‚Â©clairage des trous permet effectivement de savoir par quelle fente
passe chaque ÃƒÆ’Ã‚Â©lectron car la charge ÃƒÆ’Ã‚Â©lectrique diffuse la lumiÃƒÆ’Ã‚Â¨re en
ÃƒÆ’Ã‚Â©mettant un flash de lumiÃƒÆ’Ã‚Â¨re au voisinage d\'une fente mais
l\'interfÃƒÆ’Ã‚Â©rence disparaÃƒÆ’Ã‚Â®t et la distribution devient identique ÃƒÆ’Ã‚Â  celle
des corpuscules classiques. Les ÃƒÆ’Ã‚Â©lectrons sont manifestement perturbÃƒÆ’Ã‚Â©s
par la lumiÃƒÆ’Ã‚Â¨re. On peut essayer d\'attÃƒÆ’Ã‚Â©nuer cette perturbation en
diminuant l\'intensitÃƒÆ’Ã‚Â© de la source de lumiÃƒÆ’Ã‚Â¨re. Dans ce cas elle ÃƒÆ’Ã‚Â©met
moins de photons et certains ÃƒÆ’Ã‚Â©lectrons ne sont pas vus. Les ÃƒÆ’Ã‚Â©lectrons
dÃƒÆ’Ã‚Â©tectÃƒÆ’Ã‚Â©s sans qu\'un ÃƒÆ’Ã‚Â©clair soit ÃƒÆ’Ã‚Â©mis possÃƒÆ’Ã‚Â¨dent une rÃƒÆ’Ã‚Â©partition
caractÃƒÆ’Ã‚Â©ristique d\'un phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne d\'interfÃƒÆ’Ã‚Â©rence. Par contre, ceux qui
ont ÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â© vus (ÃƒÆ’Ã‚Â©clair ÃƒÆ’Ã‚Â©mis au voisinage d\'un des fentes) ont une
rÃƒÆ’Ã‚Â©partition semblable ÃƒÆ’Ã‚Â  celle des corpuscules classiques.

Une autre faÃƒÆ’Ã‚Â§on d\'attÃƒÆ’Ã‚Â©nuer la perturbation des ÃƒÆ’Ã‚Â©lectrons consiste ÃƒÆ’Ã‚Â 
diminuer l\'ÃƒÆ’Ã‚Â©nergie et l\'impulsion des photons en augmentant la
longueur d\'onde de la lumiÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â©clairante. Il est possible alors de
diminuer suffisamment la perturbation pour que la distribution des
ÃƒÆ’Ã‚Â©lectrons dÃƒÆ’Ã‚Â©tectÃƒÆ’Ã‚Â©s manifeste ÃƒÆ’Ã‚Â  nouveau un phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne d\'interfÃƒÆ’Ã‚Â©rence.
Cependant, on trouve alors que la longueur d\'onde est trop grande pour
obtenir un pouvoir sÃƒÆ’Ã‚Â©parateur suffisant pour dÃƒÆ’Ã‚Â©terminer par quelle fente
l\'ÃƒÆ’Ã‚Â©lectron est passÃƒÆ’Ã‚Â©.

En rÃƒÆ’Ã‚Â©sumÃƒÆ’Ã‚Â©, on peut dire que chaque fois qu\'une expÃƒÆ’Ã‚Â©rience permet de
dÃƒÆ’Ã‚Â©terminer par quel trou passe chaque ÃƒÆ’Ã‚Â©lectron, leur rÃƒÆ’Ã‚Â©partition sur
l\'ÃƒÆ’Ã‚Â©cran est semblable ÃƒÆ’Ã‚Â  celle des corpuscules classiques. Sinon on
observe des interfÃƒÆ’Ã‚Â©rences.

Remarquons enfin que l\'interaction entre quantons ne joue aucun rÃƒÆ’Ã‚Â´le
dans ce genre d\'expÃƒÆ’Ã‚Â©rience. On obtient les mÃƒÆ’Ã‚Âªmes rÃƒÆ’Ã‚Â©sultats en leur
faisant traverser le dispositif un ÃƒÆ’Ã‚Â  un.

## Notion d\'amplitudes de probabilitÃƒÆ’Ã‚Â© pour caractÃƒÆ’Ã‚Â©riser l'ÃƒÆ’Ã‚Â©volution spatio-temporelle d'un systÃƒÆ’Ã‚Â¨me

La notion de probabilitÃƒÆ’Ã‚Â© est insuffisante pour expliquer l\'expÃƒÆ’Ã‚Â©rience
prÃƒÆ’Ã‚Â©cÃƒÆ’Ã‚Â©dente car elle ne permet pas de rendre compte du phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne
d\'interfÃƒÆ’Ã‚Â©rence. En effet ÃƒÆ’Ã‚Â©tant un nombre positif elle ne peut pas
diminuer lors de l\'ouverture d\'une voie supplÃƒÆ’Ã‚Â©mentaire.

Pour rÃƒÆ’Ã‚Â©soudre ce problÃƒÆ’Ã‚Â¨me la thÃƒÆ’Ã‚Â©orie quantique fait appel au concept
d\'**{index}`amplitude de probabilitÃƒÆ’Ã‚Â© de transition`**. Une telle amplitude est
un nombre complexe dont le carrÃƒÆ’Ã‚Â© du module reprÃƒÆ’Ã‚Â©sente la probabilitÃƒÆ’Ã‚Â© de
cette transition. En prÃƒÆ’Ã‚Â©sence de deux ou plusieurs voies ou
alternatives possibles pour une transition donnÃƒÆ’Ã‚Â©e, il faut une rÃƒÆ’Ã‚Â¨gle
permettant de calculer les amplitudes et les probabilitÃƒÆ’Ã‚Â©s. La
**superposition des amplitudes** ou  {index}`principe de superposition des amplitudes` (PSAP) joue un rÃƒÆ’Ã‚Â´le capital
en thÃƒÆ’Ã‚Â©orie quantique :

**<u>Il stipule que lorsqu\'une transition peut se faire par deux ou
plusieurs alternatives en principe indiscernables, l\'amplitude totale
est la somme des amplitudes associÃƒÆ’Ã‚Â©es ÃƒÆ’Ã‚Â  chaque voie.</u>**

**<u>La probabilitÃƒÆ’Ã‚Â© est donc le carrÃƒÆ’Ã‚Â© du module de la somme des
amplitudes.</u>**

Dans le cas oÃƒÆ’Ã‚Â¹ une source ÃƒÆ’Ã‚Â©mettrait des ÃƒÆ’Ã‚Â©lectrons comme dans
l\'expÃƒÆ’Ã‚Â©rience prÃƒÆ’Ã‚Â©cÃƒÆ’Ã‚Â©dente on note $A_{1}$ ou $A_{2}$ l'amplitude de
probabilitÃƒÆ’Ã‚Â© pour que l\'ÃƒÆ’Ã‚Â©lectron aille de la source ÃƒÆ’Ã‚Â  un point de
l\'ÃƒÆ’Ã‚Â©cran lorsque la seule fente $1$ ou $2$ est ouverte respectivement.
La probabilitÃƒÆ’Ã‚Â© de transition est donnÃƒÆ’Ã‚Â©e par :

$$P_{1} = A_{1}{A_{1}}^{*} = | A_{1} |^{2}$$

ou

$$P_{2} = A_{2}{A_{2}}^{*} = | A_{2} |^{2}$$

selon que c\'est la fente $1$ ou la fente $2$ qui est ouvert ÃƒÆ’Ã‚Â 
l'exclusion de l'autre.

Lorsque les deux fentes sont ouvertes et aucune expÃƒÆ’Ã‚Â©rience n\'est faite
pour dÃƒÆ’Ã‚Â©terminer par quel trou passent les ÃƒÆ’Ã‚Â©lectrons, les deux voies sont
indiscernables et d\'aprÃƒÆ’Ã‚Â¨s le PSAP il faut additionner les amplitudes :

$$P_{12} = ( A_{1} + A_{2} )( {A_{1}}^{*} + {A_{2}}^{*} )$$

soit :

$$P_{12} = A_{1}{A_{1}}^{*} + A_{2}{A_{2}}^{*} + {A_{1}}^{*}A_{2} + A_{1}{A_{2}}^{*}$$

ou bien :

$$P_{12} = A_{1}{A_{1}}^{*} + A_{2}{A_{2}}^{*} + 2Re{ {A_{1}}^{*}A_{2} }$$

Les deux premiers termes sont positifs mais le dernier peut ÃƒÆ’Ã‚Âªtre positif
ou nÃƒÆ’Ã‚Â©gatif. Il reprÃƒÆ’Ã‚Â©sente l\'interfÃƒÆ’Ã‚Â©rence.

Lorsque les deux voies sont en principe discernables le PSAP ne
s\'applique pas. Il **<u>faut additionner les probabilitÃƒÆ’Ã‚Â©s associÃƒÆ’Ã‚Â©es ÃƒÆ’Ã‚Â 
chaque voie</u>**. On a alors :

$$P_{12} = A_{1}{A_{1}}^{*} + A_{2}{A_{2}}^{*}$$

c\'est-ÃƒÆ’Ã‚Â -dire :

$$P_{12} = P_{1} + P_{2}$$

Dans ce cas l\'interfÃƒÆ’Ã‚Â©rence disparaÃƒÆ’Ã‚Â®t.

Seule la probabilitÃƒÆ’Ã‚Â© est mesurable par l\'expÃƒÆ’Ã‚Â©rience. La phase
de l\'amplitude totale est sans importance car seul le carrÃƒÆ’Ã‚Â© de son
module est accessible ÃƒÆ’Ã‚Â  la mesure. Les probabilitÃƒÆ’Ã‚Â©s sont inchangÃƒÆ’Ã‚Â©es si
toutes les amplitudes sont multipliÃƒÆ’Ã‚Â©es par un facteur $e^{i\alpha}$. Un
tel facteur est appelÃƒÆ’Ã‚Â© **{index}`facteur de phase`**.

La phase relative des amplitudes (dÃƒÆ’Ã‚Â©phasage) est cependant trÃƒÆ’Ã‚Â¨s
importante car c\'est elle qui dÃƒÆ’Ã‚Â©termine si l\'interfÃƒÆ’Ã‚Â©rence est
constructive ou destructive. <u>La somme de deux amplitudes est maximale
(en module) lorsqu\'elles sont en phase c\'est-ÃƒÆ’Ã‚Â -dire lorsque les
vecteurs du plan complexe qui les reprÃƒÆ’Ã‚Â©sentent ont la mÃƒÆ’Ã‚Âªme
orientation</u>. <u>De mÃƒÆ’Ã‚Âªme le module de l\'amplitude rÃƒÆ’Ã‚Â©sultante
est minimal si leur dÃƒÆ’Ã‚Â©phasage est ÃƒÂÃ¢â€šÂ¬</u> ; elles sont alors
reprÃƒÆ’Ã‚Â©sentÃƒÆ’Ã‚Â©es par des vecteurs opposÃƒÆ’Ã‚Â©s dans le plan complexe. Dans le
premier cas l'interfÃƒÆ’Ã‚Â©rence est constructive. Toutes les situations
intermÃƒÆ’Ã‚Â©diaires sont ÃƒÆ’Ã‚Â©videmment possibles ({numref}`fig-APPlanComplexes`).

```{figure} media/image26.png
:name: fig-APPlanComplexes
:alt: ReprÃƒÆ’Ã‚Â©sentation des amplitudes dans le plan complexe
:width: 90%
Sommation des AP dans le plan complexe
```

## Calcul des amplitudes et des probabilitÃƒÆ’Ã‚Â©s

Pour calculer les amplitudes et les probabilitÃƒÆ’Ã‚Â©s dans des situations
assez rÃƒÆ’Ã‚Â©alistes il faut dÃƒÆ’Ã‚Â©finir des rÃƒÆ’Ã‚Â¨gles prÃƒÆ’Ã‚Â©cises qui peuvent ÃƒÆ’Ã‚Âªtre
considÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©es comme les postulats de la thÃƒÆ’Ã‚Â©orie quantique.

Avant de les ÃƒÆ’Ã‚Â©noncer nous introduirons la notation de Dirac couramment
utilisÃƒÆ’Ã‚Â©e pour <u>dÃƒÆ’Ã‚Â©signer une amplitude de probabilitÃƒÆ’Ã‚Â©.</u>

L\'amplitude de probabilitÃƒÆ’Ã‚Â© de transition entre deux ÃƒÆ’Ã‚Â©tats s\'ÃƒÆ’Ã‚Â©crit sous
la forme :

$$ÃƒÂ¢Ã…Â¸Ã‚Â¨\text{final} || \text{initial}ÃƒÂ¢Ã…Â¸Ã‚Â©$$

Ainsi l\'amplitude de probabilitÃƒÆ’Ã‚Â© pour qu\'un ÃƒÆ’Ã‚Â©lectron aille de la
source au dÃƒÆ’Ã‚Â©tecteur lorsque la seule fente est ouverte 1 peut s\'ÃƒÆ’Ã‚Â©crire
:

$${A_{1} = < D || S >}_{1}$$

Pour la seule fente 2 ouverte :

$${A_{2} = < D || S >}_{2}$$

En plus du PSAP deux autres principes sont nÃƒÆ’Ã‚Â©cessaires pour permettre de
calculer les amplitudes et les probabilitÃƒÆ’Ã‚Â©s.

### Principe d\'addition des probabilitÃƒÆ’Ã‚Â©s

**<u>Lorsqu\'il existe plusieurs ÃƒÆ’Ã‚Â©tats finaux disjoints ou distincts la
probabilitÃƒÆ’Ã‚Â© de transition vers l\'ensemble de ces ÃƒÆ’Ã‚Â©tats est la somme des
probabilitÃƒÆ’Ã‚Â©s de transition vers chacun de ces ÃƒÆ’Ã‚Â©tats.</u>**

Lorsqu\'une transition peut se faire par des voies intermÃƒÆ’Ã‚Â©diaires en
principe <u>discernables, chacun de ses ÃƒÆ’Ã‚Â©tats peut ÃƒÆ’Ã‚Âªtre considÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â© comme
final pour une partie de la transition</u>. La rÃƒÆ’Ã‚Â¨gle
d\'addition des probabilitÃƒÆ’Ã‚Â©s que nous avons dÃƒÆ’Ã‚Â©jÃƒÆ’Ã‚Â  ÃƒÆ’Ã‚Â©noncÃƒÆ’Ã‚Â©e peut ÃƒÆ’Ã‚Âªtre
considÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©e comme un cas particulier du principe d\'addition des
probabilitÃƒÆ’Ã‚Â©s de transition vers des ÃƒÆ’Ã‚Â©tats finaux distincts.

### Principe de factorisation sÃƒÆ’Ã‚Â©quentielle.

Lorsqu\'une transition s\'effectue en passant par un ÃƒÆ’Ã‚Â©tat intermÃƒÆ’Ã‚Â©diaire
bien dÃƒÆ’Ã‚Â©fini(s) l\'amplitude de probabilitÃƒÆ’Ã‚Â© de transition est le produit
des amplitudes associÃƒÆ’Ã‚Â©es ÃƒÆ’Ã‚Â  chaque ÃƒÆ’Ã‚Â©tape de la transition :

$$ÃƒÂ¢Ã…Â¸Ã‚Â¨v || u >_{s} = < v || s >< s || uÃƒÂ¢Ã…Â¸Ã‚Â©$$

Dans le cas particulier de l\'expÃƒÆ’Ã‚Â©rience rÃƒÆ’Ã‚Â©alisÃƒÆ’Ã‚Â©e avec le dispositif
d\'Young la transition de la source au dÃƒÆ’Ã‚Â©tecteur peut se faire par
l\'intermÃƒÆ’Ã‚Â©diaire de l\'un ou l\'autre trou. Le principe de factorisation
sÃƒÆ’Ã‚Â©quentielle permet d\'ÃƒÆ’Ã‚Â©crire :

$${A_{1} = < D || S >}_{1} = < D || 1 >< 1 || SÃƒÂ¢Ã…Â¸Ã‚Â©$$

$${A_{2} = < D || S >}_{2} = < D || 2 >< 2 || SÃƒÂ¢Ã…Â¸Ã‚Â©$$

L\'expression $ÃƒÂ¢Ã…Â¸Ã‚Â¨i || SÃƒÂ¢Ã…Â¸Ã‚Â©$reprÃƒÆ’Ã‚Â©sente
l\'amplitude de probabilitÃƒÆ’Ã‚Â© pour que le quanton quitte la source $S$
pour arriver ÃƒÆ’Ã‚Â  la fente $i$ et $ÃƒÂ¢Ã…Â¸Ã‚Â¨D || iÃƒÂ¢Ã…Â¸Ã‚Â©$
reprÃƒÆ’Ã‚Â©sente l\'amplitude de probabilitÃƒÆ’Ã‚Â© pour qu\'il aille de la fente $i$
au dÃƒÆ’Ã‚Â©tecteur.

Le type de transition intervenant dans les expÃƒÆ’Ã‚Â©riences ÃƒÆ’Ã‚Â©tudiÃƒÆ’Ã‚Â©es ici est
en fait une propagation dans l\'espace-temps. Dans le cas des photons
nous pourrons donner une expression trÃƒÆ’Ã‚Â¨s simple. Elle expliquera ainsi
tous les phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes dÃƒÆ’Ã‚Â©jÃƒÆ’Ã‚Â  expliquÃƒÆ’Ã‚Â©s par l\'optique ondulatoire et par
l\'optique gÃƒÆ’Ã‚Â©omÃƒÆ’Ã‚Â©trique.

## Propagation rectiligne de la lumiÃƒÆ’Ã‚Â¨re

Les photons se dÃƒÆ’Ã‚Â©placent-ils en ligne droite dans le vide ? A premiÃƒÆ’Ã‚Â¨re
vue la rÃƒÆ’Ã‚Â©ponse semblait ÃƒÆ’Ã‚Âªtre positive car l'expÃƒÆ’Ã‚Â©rience quotidienne nous
permet d'observer facilement le phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne de propagation rectiligne de
la lumiÃƒÆ’Ã‚Â¨re (visible). C'est d'ailleurs cette observation qui a conduit
au dÃƒÆ’Ã‚Â©veloppement du modÃƒÆ’Ã‚Â¨le gÃƒÆ’Ã‚Â©omÃƒÆ’Ã‚Â©trique. En revanche l'existence d'une
trajectoire bien dÃƒÆ’Ã‚Â©finie pour le photon est incompatible avec
l'inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â© d'Heisenberg. Comment concilier ces propriÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â©s qui semblent
ÃƒÆ’Ã‚Âªtre en contradiction ?

On peut essayer de rÃƒÆ’Ã‚Â©soudre ce dilemme en faisant une expÃƒÆ’Ã‚Â©rience
appropriÃƒÆ’Ã‚Â©e :

```{figure} media/image26bis.png
:name: fig-rectilLumiere
:alt: Trajet rectiligne de la lumiÃƒÆ’Ã‚Â¨re
:width: 100%
Trajet rectiligne de la lumiÃƒÆ’Ã‚Â¨re
```

Une source de lumiÃƒÆ’Ã‚Â¨re S ÃƒÆ’Ã‚Â©met des photons dont certains passent ÃƒÆ’Ã‚Â  travers
une fente AB percÃƒÆ’Ã‚Â©e dans un ÃƒÆ’Ã‚Â©cran opaque. Un dÃƒÆ’Ã‚Â©tecteur $D_1$ est placÃƒÆ’Ã‚Â© de
telle sorte qu'il existe des trajets rectilignes allant de la source ÃƒÆ’Ã‚Â 
ce dÃƒÆ’Ã‚Â©tecteur. Un autre dÃƒÆ’Ã‚Â©tecteur $D_2$ est placÃƒÆ’Ã‚Â© de telle sorte qu'il
n'existe aucun trajet rectiligne le reliant ÃƒÆ’Ã‚Â  la source et passant par
la fente. Si le dÃƒÆ’Ã‚Â©tecteur $D_1$ reÃƒÆ’Ã‚Â§oit des photons alors que le dÃƒÆ’Ã‚Â©tecteur
$D_2$ n'en reÃƒÆ’Ã‚Â§oit aucun on dira que les photons se propagent en ligne
droite.

Supposons qu'une expÃƒÆ’Ã‚Â©rience conduise effectivement au rÃƒÆ’Ã‚Â©sultat suivant :
$D_1$ reÃƒÆ’Ã‚Â§oit des photons et $D_2$ n'en reÃƒÆ’Ã‚Â§oit pas. C'est prÃƒÆ’Ã‚Â©cisÃƒÆ’Ã‚Â©ment le
critÃƒÆ’Ã‚Â¨re choisi pour affirmer que les photons ont des trajectoires
rectilignes. Il faut cependant remarquer que la prÃƒÆ’Ã‚Â©cision de la
trajectoire est limitÃƒÆ’Ã‚Â©e par la largeur de la fente. On ne peut pas
exclure a priori la trajectoire pointillÃƒÆ’Ã‚Â©e allant de S ÃƒÆ’Ã‚Â  $D_1$. Pour le
faire, et du mÃƒÆ’Ã‚Âªme coup amÃƒÆ’Ã‚Â©liorer la prÃƒÆ’Ã‚Â©cision, il faut rÃƒÆ’Ã‚Â©trÃƒÆ’Ã‚Â©cir la
fente. L'expÃƒÆ’Ã‚Â©rience montre qu'alors le dÃƒÆ’Ã‚Â©tecteur $D_2$ commence ÃƒÆ’Ã‚Â 
recevoir des photons.

Analysons cette expÃƒÆ’Ã‚Â©rience ÃƒÆ’Ã‚Â  l'aide du PSAP. Il y a un grand
nombre de chemins allant de la source au dÃƒÆ’Ã‚Â©tecteur $D_2$ et passant par
la fente (mathÃƒÆ’Ã‚Â©matiquement il y en a une infinitÃƒÆ’Ã‚Â©).

A chacun de ces chemins, on associe une amplitude de probabilitÃƒÆ’Ã‚Â© dont la
phase est dÃƒÆ’Ã‚Â©terminÃƒÆ’Ã‚Â©e par le temps de parcours. selon {cite}`feynman1979` :

$$A = e^{j\theta}$$

oÃƒÆ’Ã‚Â¹ $\theta$ est la phase caractÃƒÆ’Ã‚Â©ristique d'un chemin quelconque qui joint un point ÃƒÆ’Ã‚Â  un autre.

```{math}
:label: eq-phiAction
\theta = \frac{S}{\hbar}
```

oÃƒÆ’Ã‚Â¹ $S$ est l'action associÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  un chemin.

Pour un photon dans un milieu optique, l'action est proportionnelle au chemin optique qui est lui mÃƒÆ’Ã‚Âªme la longueur du trajet multipliÃƒÆ’Ã‚Â©e par l'indice du milieu.

$$ \Delta = \int{n(s)\;ds}$$

Soit :

$$ \Delta = n L$$

dans un mileu homogÃƒÆ’Ã‚Â¨ne.

Pour un photon, la phase accumulÃƒÆ’Ã‚Â©e sur le chemin est :

$$ \Phi = k_0 \Delta$$

oÃƒÆ’Ã‚Â¹ $k_0 = 2\pi/\lambda_0$ est le nombre d'onde dans le vide et $\lambda_0$ la longueur d'onde dans le vide.

Ainsi d'aprÃƒÆ’Ã‚Â¨s la formulation {eq}`eq-phiAction` l'action $S$ est :

$$S=\hbar \Phi=\hbar k_0 n L==\hbar k L$$

Les diffÃƒÆ’Ã‚Â©rents chemins ÃƒÆ’Ã‚Â©tant indiscernables, il faut
additionner les diffÃƒÆ’Ã‚Â©rentes amplitudes associÃƒÆ’Ã‚Â©es ÃƒÆ’Ã‚Â  chaque trajet pour
obtenir l'amplitude rÃƒÆ’Ã‚Â©sultante dont le carrÃƒÆ’Ã‚Â© du module est proportionnel
ÃƒÆ’Ã‚Â  la probabilitÃƒÆ’Ã‚Â© de recevoir un photon.

Les chemins ayant une longueur diffÃƒÆ’Ã‚Â©rentes, la phase accumulÃƒÆ’Ã‚Â©e n'est pas la mÃƒÆ’Ã‚Âªme. Il existe donc un dÃƒÆ’Ã‚Â©phasage entre les amplitudes associÃƒÆ’Ã‚Â©es ÃƒÆ’Ã‚Â  chaque chemin.

Si la somme des amplitudes est
nulle dans une direction donnÃƒÆ’Ã‚Â©e (ÃƒÅ½Ã‚Â¸) de $D_2$, il est clair que $D_2$ ne
reÃƒÆ’Ã‚Â§oit aucun photon. Nous allons essayer d'estimer la plus petite
valeur de ÃƒÅ½Ã‚Â¸ compatible avec cette condition.

Remarquons d'abord que si la diffÃƒÆ’Ã‚Â©rence de phase entre les amplitudes
associÃƒÆ’Ã‚Â©es aux chemins extrÃƒÆ’Ã‚Âªmes ne dÃƒÆ’Ã‚Â©passe pas ÃƒÂÃ¢â€šÂ¬ , la somme des
amplitudes ne peut pas ÃƒÆ’Ã‚Âªtre nulle {numref}`fig-PSAPPhotons`. Si
d est la largeur de la fente, la diffÃƒÆ’Ã‚Â©rence de marche entre le chemin le
plus court et le chemin le
plus long est $d\;\sin\theta$. Le dÃƒÆ’Ã‚Â©phasage entre les deux phases accumulÃƒÆ’Ã‚Â©es est donc :

$$\Delta \phi= k d \sin\theta$$


```{figure} media/image27.png
:name: fig-PSAPPhotons
:alt: PSAP de propagation des photons
:width: 70%
PSAP de propagation des photons
```

La condition nÃƒÆ’Ã‚Â©cessaire pour que $D_2$ ne reÃƒÆ’Ã‚Â§oive pas de photons est donc que $\mathrm{\Delta}\phi$ dÃƒÆ’Ã‚Â©passe $\pi$

soit :
(36) $d \sin{\theta_{\min}} = \frac{\lambda}{2}$

L'angle $\theta_{\min}$ le plus petit au-delÃƒÆ’Ã‚Â  duquel que $D_2$ ne reÃƒÆ’Ã‚Â§oit
aucun photon est donc :

$$\sin{\theta_{\min}} = \frac{\lambda}{2d}$$

Des photons arrivent donc dans toutes les directions comprises entre
$+ \theta_{\min}$ et $- \theta_{\min}$. Si on diminue la largeur de la
fente pour amÃƒÆ’Ã‚Â©liorer la prÃƒÆ’Ã‚Â©cision sur la trajectoire la dispersion
angulaire augmente. Ce phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne est connu en optique sous le nom de
diffraction de la lumiÃƒÆ’Ã‚Â¨re. Cette expÃƒÆ’Ã‚Â©rience nous montre que la
trajectoire des photons [n'est pas bien dÃƒÆ’Ã‚Â©finie car le fait de bien
prÃƒÆ’Ã‚Â©ciser leur position rend leur impulsion indÃƒÆ’Ã‚Â©terminÃƒÆ’Ã‚Â©e].

En multipliant par la constante de Planck chaque cÃƒÆ’Ã‚Â´tÃƒÆ’Ã‚Â© de l'ÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â©
prÃƒÆ’Ã‚Â©cÃƒÆ’Ã‚Â©dente (1) on a :

$${d\frac{h}{\lambda}\sin}{\theta_{\min} = \frac{h}{2}}$$

soit :

(37) ${dp\sin}{\theta_{\min} = \frac{h}{2}}$

L'extension en impulsion est donnÃƒÆ’Ã‚Â©e par :

$${\Delta p_{y} = p\sin}\theta_{\min}$$

et l'extension spatiale par :

$${\Delta y =}d$$

On retrouve donc la valeur infÃƒÆ’Ã‚Â©rieure de l'inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â© d'Heisenberg :

$$\Delta y\Delta p_{y} = \frac{h}{2}$$

Cette inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â© dÃƒÆ’Ã‚Â©coule du PSAP.

Ainsi, si on cherche ÃƒÆ’Ã‚Â  dÃƒÆ’Ã‚Â©terminer la position du photon avec une grande
prÃƒÆ’Ã‚Â©cision pour montrer que sa trajectoire est rectiligne on trouve qu'il
a une probabilitÃƒÆ’Ã‚Â© non nulle d'arriver dans le dÃƒÆ’Ã‚Â©tecteur $D_2$, ce qui
montre bien que sa trajectoire n'est pas rectiligne et donc que [des
trajets non rectilignes sont des alternatives dont il faut considÃƒÆ’Ã‚Â©rer
l'AP].

On peut ÃƒÆ’Ã‚Â©galement interprÃƒÆ’Ã‚Â©ter ce rÃƒÆ’Ã‚Â©sultat ÃƒÆ’Ã‚Â  l'aide du PSAP. La
diffÃƒÆ’Ã‚Â©rence de marche entre les chemins extrÃƒÆ’Ã‚Âªmes devient plus grande
lorsque la fente est ÃƒÆ’Ã‚Â©largie. La diffÃƒÆ’Ã‚Â©rence de phase des amplitudes
associÃƒÆ’Ã‚Â©es devient assez grande pour que l'amplitude rÃƒÆ’Ã‚Â©sultante s'annule.
Il est clair que c'est l\'interfÃƒÆ’Ã‚Â©rence entre les amplitudes de
probabilitÃƒÆ’Ã‚Â© qui annule la probabilitÃƒÆ’Ã‚Â© pour qu'un photon arrive sur $D_2$.

 [^41]: L'intensitÃƒÆ’Ã‚Â© se dÃƒÆ’Ã‚Â©duit du module de vecteur de Poynting
    $( \overrightarrow{E} \land \overrightarrow{B} )/\mu_{0}$
    qui correspond ÃƒÆ’Ã‚Â  la quantitÃƒÆ’Ã‚Â© d'ÃƒÆ’Ã‚Â©nergie qui traverse pendant une
    seconde une unitÃƒÆ’Ã‚Â© de surface perpendiculaire ÃƒÆ’Ã‚Â  la direction de
    propagation $\overrightarrow{k}$. En moyennant sur une pÃƒÆ’Ã‚Â©riode,
    cette quantitÃƒÆ’Ã‚Â© dÃƒÆ’Ã‚Â©finit l'intensitÃƒÆ’Ã‚Â© du rayonnement.

 [^42]: La polarisation peut ÃƒÆ’Ã‚Âªtre obtenue par rÃƒÆ’Ã‚Â©flexion sur une surface
    vitreuse (diÃƒÆ’Ã‚Â©lectrique) ÃƒÆ’Ã‚Â  l'angle de Brewster : la lumiÃƒÆ’Ã‚Â¨re rÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chie
    est totalement polarisÃƒÆ’Ã‚Â©e rectilignement dans une direction
    perpendiculaire au plan d'incidence, plan contenant la direction du
    faisceau incident et la normale ÃƒÆ’Ã‚Â  la surface vitreuse. Elle peut
    ÃƒÆ’Ã‚Âªtre obtenue par rÃƒÆ’Ã‚Â©fraction (birÃƒÆ’Ã‚Â©fringence liÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  l'anisotropie
    optique d'un corps) ou au moyen de cristaux optiques uniaxe ou
    biaxes.

