---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  name: python3
  display_name: Python 3
---

# Les fondements de la mécanique quantique

## Evidence expérimentale de l\'incompatibilité de certaines grandeurs

On peut montrer qu\'il est impossible de mesurer avec précision pour un
corpuscule tel que l\'électron à la fois sa position et son impulsion.
Cherchons à mesurer simultanément $y = 0$ et $p_{y} = 0$.

```{figure} media/image20.png
:name: fig-diffElecFente
:alt: Diffraction des électrons par une fente
:width: 80%
Diffraction des électrons par une fente
```

On interpose sur le trajet d\'un faisceau d\'électrons une fente afin de
sélectionner les électrons ayant une ordonnée $y$ nulle. La précision
est liée à la largeur de la fente $\delta y$. Les électrons triés ont
donc une ordonnée comprise entre $- \delta y/2$ et $\delta y/2$.

Cependant si on observe le faisceau d\'électrons qui a traversé la
fente, nous mesurons que l\'homogénéité de la direction des vitesses
($v_{y} = 0$ avant la fente) a été détruite par le fait d\'obliger les
électrons à passer par la fente. Le faisceau issu de la fente a subi un
étalement de la distribution angulaire des trajectoires dans un angle
$\alpha$ **<u>dont la mesure expérimentale donne</u>**
$\lambda/\delta y$ à la condition d'associer à l'électron une longueur
d'onde</u> $\lambda$ que l\'expérience montre égale à :

$$\lambda = \frac{h}{p}$$

où $p$ est le module de la quantité de mouvement de l\'électron
$\overrightarrow{p}$ et $h$ la constante de Planck.

Ce phénomène est appelé un phénomène de **diffraction** {index}`Diffraction` auquel la physique classique n\'apporte aucune
réponse.

L'hypothèse que cette diffraction serait inhérente à l'action des bords
de la fente sur la trajectoire des électrons pourrait être examinée si
cette diffraction demeurait la même quel que soit la largeur de la
fente. Tel n'est pas le cas. En effet, on observe que la diffraction
devient plus faible lorsque l'on augmente la largeur de la fente.

Ainsi, la fixation de $y$ à $\delta y$ près introduit donc
nécessairement une incertitude $\delta p_{y}$ sur la composante $p_{y}$
de sa quantité de mouvement après traversée de la fente :

$$\delta p_{y} = p\sin{\alpha \cong p\alpha \cong p\frac{\lambda}{\delta y}} = \frac{h}{\delta y}$$

L\'incertitude $\delta p_{y}$ étant inversement proportionnelle à
$\delta y$, il est impossible de fixer simultanément avec une parfaite
précision des valeurs aux grandeurs $y$ et $p_{y}$.

## Dualité onde-corpuscule

Les interprétations des expériences de Compton et de l\'effet
photoélectrique suffisent-elles pour rejeter définitivement la théorie
ondulatoire électromagnétique de la lumière ?

Faut-il rejeter définitivement la théorie ondulatoire et en revenir à la
théorie corpusculaire aux prix de raffinements tentant d\'expliquer la
diffraction des électrons par une fente ?

La réponse est bien évidemment non. On verra que les aspects
ondulatoires et corpusculaires sont indissolublement liés pour rendre
compte de nombreux faits expérimentaux. On parle alors de dualité onde
corpuscule afin d\'exprimer que les objets microscopiques possèdent de
façon intrinsèque des propriétés qui les assimilent à la fois à des
ondes et à des corpuscules matériels.

En 1924 De Broglie a émis l\'hypothèse que cette dualité est une
caractéristique de tous les objets microscopiques considérés comme des
particules.

La formule donnant la longueur d\'onde dite de de Broglie fonction de
l\'impulsion :

```{math}
:label: eq-longdeBroglie

\lambda = \frac{h}{p}
```

<u>est supposée être applicable selon De Broglie pour toute particule quel
que soit leur masse à condition de prendre</u>
$\overrightarrow{p} = \gamma m\overrightarrow{v}$ si la particule est
relativiste où $\gamma$ est le facteur de Lorentz
$\gamma = \frac{1}{\sqrt{1 - v^{2}/c^{2}}}$.

{eq}`eq-longdeBroglie` est donnée souvent sous une forme équivalente :

$$p = \frac{h}{2\pi}\frac{2\pi}{\lambda} = \hslash k$$

L\'énergie cinétique d\'une particule non relativiste étant donnée par :
$E_{cin} = \frac{p^{2}}{2m}$

$$\lambda = \frac{h}{p}$$

conduit :

$$\lambda = \frac{h}{\sqrt{2mE_{cin}}}$$

## Annexe : dualité onde-corpuscule

Nous verrons, par un cheminement simplifié, comment il a pu associer une
longueur d\'onde à toute particule.

Revenons au cas des photons. Examinons de quelle manière l'hypothèse de
l'existence du corpuscule de lumière par essence de nature relativiste
concilie la relation de Planck-Einstein avec celle obtenue par Einstein
dans son traité sur la relativité restreinte reliant l'énergie totale
$E$ d'une particule à l'impulsion $\overrightarrow{p}$ et sa masse
$m_{0}$ (masse au repos ou propre).

La formule relativiste reliant l\'énergie et l\'impulsion d\'une
particule s\'écrit :

$$E^{2} = p^{2}c^{2} + {m_{0}}^{2}c^{4}$$

où $m_{0}$ est la masse de la particule au repos,
$\overrightarrow{p} = \gamma m\overrightarrow{v}$ avec
$\gamma = \frac{1}{\sqrt{1 - \beta^{2}}}$ et $ \beta = \frac{v}{c}$

On a donc :

$${E = h\nu = \sqrt{{p^{2}c}^{2} + {m_{0}}^{2}c^{4}}}$$

La fréquence de l'onde pouvant être rendue arbitrairement aussi petite
qu'on le souhaite, on obtient à la limite de la fréquence nulle :

$${0 \approx \left( \sqrt{{p^{2}c}^{2} + {m_{0}}^{2}c^{4}} \right)_{\nu \approx 0}}$$

La formule ci-dessus est vérifiée si et seulement si les deux termes
sous la racine sont nuls, ceci entraînant que la masse du photon est
nulle : $m_{0} = 0$. Cette propriété est vraie quel que soit la
fréquence.

Dans ce cas, on a alors

$$E = pc$$

En utilisant la relation de Planck-Einstein $E = h\nu$, on peut ainsi
lier l\'aspect ondulatoire (la fréquence) et l\'aspect corpusculaire
(quantité de mouvement) :

$$\frac{c}{\nu} = \frac{h}{p}$$

c\'est-à-dire :

$$\lambda = \frac{h}{p}$$

On retrouve la relation expérimentale obtenue dans l'expérience de
diffraction des électrons.

Cette relation a été vérifiée dans le cas des photons par l\'effet
Compton. **<u>De Broglie a supposé qu\'elle était vraie pour toute
particule quel que soit leur masse à condition de prendre</u>**
$\overrightarrow{p} = \gamma m\overrightarrow{v}$. On l\'écrit souvent
sous la forme équivalente :

$$p = \frac{h}{2\pi}\frac{2\pi}{\lambda}$$

c\'est-à-dire :

$p = \hslash k$ et plus généralement
$\overrightarrow{p} = \hslash\overrightarrow{k}$

où $\hslash = \frac{h}{2\pi}$. L\'impulsion est donc proportionnelle au
vecteur d\'onde.

Nous allons chercher à exprimer la longueur d\'onde en fonction de
l\'énergie cinétique de la particule. Lorsque la particule est au repos
son impulsion est nulle et son énergie est :

$$E_{0} = mc^{2}$$

Lorsqu\'elle est en mouvement son énergie est augmentée d\'une quantité
qui est par définition son énergie cinétique $E_{cin}$.

On a donc :

$$E = E_{0} + E_{cin}$$

En élevant au carré il vient :

$$E^{2} = {E_{0}}^{2} + {E_{cin}}^{2} + 2E_{0}E_{cin}$$

D\'après la formulation relativiste de l'énergie
$E^{2} = p^{2}c^{2} + {m_{0}}^{2}c^{4}$, on a :

$${p^{2}c}^{2} = {E_{cin}}^{2} + 2E_{0}E_{cin}$$

soit :

$$p = \frac{1}{c}\sqrt{{E_{cin}}^{2} + 2E_{0}E_{cin}}$$

ou encore :

$$p = \frac{E_{0}}{c}\sqrt{\left( \frac{E_{cin}}{E_{0}} \right)^{2} + 2\left( \frac{E_{cin}}{E_{0}} \right)}$$

La longueur d\'onde s\'écrit donc :

$$\lambda = \frac{hc}{E_{0}}\frac{1}{\sqrt{\left( \frac{E_{cin}}{E_{0}} \right)^{2} + 2\left( \frac{E_{cin}}{E_{0}} \right)}} = \frac{\lambda_{c}}{\sqrt{\left( \frac{E_{cin}}{E_{0}} \right)^{2} + 2\left( \frac{E_{cin}}{E_{0}} \right)}}$$

où $\lambda_{c} = \frac{h}{mc}$ est la longueur d\'onde Compton de la
particule.

Dans l\'approximation non relativiste, on a $E_{cin} \ll E_{0}$ et on
peut écrire :

$$\lambda = \frac{\lambda_{c}}{\sqrt{2\left( \frac{E_{cin}}{E_{0}} \right)}}$$

L\'énergie cinétique étant donnée par : $E_{cin} = \frac{p^{2}}{2m}$

et on retrouve bien :

$$\lambda = \frac{h}{p}$$

ou :

$$\lambda = \frac{h}{\sqrt{2mE_{cin}}}$$

## Vérifications expérimentales

### Diffraction des électrons

De Broglie a prédit qu\'il était possible de mettre en évidence l\'onde
associée à des électrons en mettant en évidence leur diffraction par un
cristal à la manière de l\'expérience de diffraction des rayons X [^38]
par un cristal de Friedrich [^39] et Knipping [^40].

En 1924, Davisson et Germer réalisèrent une expérience de diffraction
d\'électrons par un cristal de Nickel :


```{figure} media/image21.png
:name: fig-davisson
:alt: Expérience de Davisson et Germer
:width: 90%
Expérience de Davisson et Germer
```


La relation de Bragg démontrée dans le cas de la diffraction des rayons X est :

```{figure} media/image22.jpg
:name: fig-bragg
:alt: Relation de Bragg
:width: 60%
Relation de Bragg
```

$$2d \sin{\theta} = n \lambda$$

En déplaçant l\'électrode collectrice, Davisson et Germer mesure que les
intensités maximales du courant mesuré avaient lieu pour des angles
$\theta$ vérifiant la relation de Bragg à la condition de prendre pour
longueur d\'onde $\lambda$ la longueur d\'onde de De Broglie associée
aux électrons :

$$\lambda = \frac{h}{p} = \frac{h}{\sqrt{2meV}}$$

### Propriétés ondulatoires de la matière : autres aspects

La diffraction des électrons par un métal requiert pour être observée
que la longueur d\'onde de De Broglie soit de l\'ordre de grandeur des
distances entre les atomes dans le cristal.

Le microscope électronique constitue une application intéressante des
caractéristiques ondulatoires de l\'électron. On sait que le pouvoir
séparateur est lié à la longueur d\'onde. En accélérant les électrons à
quelques dizaines de *keV* leur longueur d\'onde devient très courte
(*10^-11^* à *10^-12^* m) ce qui permet d\'atteindre un très bon pouvoir
séparateur.

Le neutron possédant une masse de l\'ordre de 1800 fois celle des
électrons peut-il manifester une propriété ondulatoire comme l\'a
supposé De Broglie ?

Aux énergies thermiques (quelques centièmes d\'*eV*) les neutrons ont
des longueurs d\'onde de l\'ordre de *1 Å* ce qui permet de les utiliser
dans l\'étude de la structure cristalline. Contrairement aux atomes
neutres ils sont très pénétrants car ils n\'interagissent pratiquement
pas avec les électrons. Ils sont essentiellement diffusés par les
noyaux. Ils ne fournissent cependant aucune information sur la structure
nucléaire car la longueur d\'onde associée est beaucoup plus grande que
le rayon nucléaire. Pour étudier la structure nucléaire il faut des
longueurs d\'onde comparables aux dimensions nucléaires. Pour cela
l\'énergie des neutrons doit atteindre quelques *MeV*. Des expériences
de diffraction des neutrons permettent à nouveau de vérifier la relation
de De Broglie.

Les particules possédant cette dualité onde et corpuscule sont souvent
désignées de **quantons</u>** {index}`Quantons` ou
particules quantiques.

## Notions de paquets d\'onde

Dans un milieu homogène et isotrope, le type le plus simple d\'onde est
l\'onde monochromatique dont la représentation complexe est donnée :

$$e^{i(\overrightarrow{k}.\overrightarrow{r} - \omega t)}$$

représentant une vibration de longueur d\'onde
$\lambda = \frac{2\pi}{k}$ se propageant dans la direction de son
vecteur d\'onde $\overrightarrow{k}$ à la vitesse constante. La vitesse
de propagation est la vitesse de phase.

$\omega$ est indépendante de la direction de $\overrightarrow{k}$
(milieu isotrope) mais peut dépendre éventuellement du module de ce
vecteur.

On associe l\'onde ci-dessus à un mouvement rectiligne uniforme
d\'énergie
$E = \hslash\omega$ dirigée parallèlement à $\overrightarrow{k}$.

Comme toute onde peut être considérée comme une superposition d\'ondes
planes monochromatiques, la connaissance de la loi de dispersion
$\omega(k)$ suffit à déterminer le comportement de n\'importe quelle
onde au cours du temps.

Considérons le cas particulier d'une onde plane monochromatique se
propageant dans le sens positif de l\'axe Ox. Elle est représentée par
la fonction :


```{math}
:label: eq-OPPsi0

\Psi_{0}(x,t) = A_{0}\cos{(k_{0}x - \omega_{0}t)}
```

D\'après la formule de De Broglie elle est associée à une particule
d\'impulsion bien définie $p_{0} = \hslash k_{0}$ et d\'énergie bien
définie $E_{0} = \hslash\omega_{0}$.

L'onde plane {eq}`eq-OPPsi0` ne peut pas représenter une
particule localisée dans une région de l\'espace d\'extension
finie car son extension spatiale est infinie comme toute
fonction sinusoïdale.

C\'est la raison pour laquelle, il est nécessaire <u>pour représenter le
comportement ondulatoire d'une particule localisée à un instant dans une
portion de l'espace</u> de construire une superposition
d\'ondes planes qui interfèrent de manière constructive dans une région
limitée de l\'espace (où se trouve la particule) et de façon destructive
ailleurs. Cette idée est le fondement de la notion de **paquet
d\'ondes** {index}`Paquet d'ondes`.

Pour une particule libre non relativiste l\'énergie purement cinétique
est donnée par :

$$E_{0} = \frac{{p_{0}}^{2}}{2m}$$

On en déduit la relation de dispersion :

```{math}
:label: eq-dispOmega0

\omega_{0} = \frac{E_{0}}{\hslash} = \frac{{p_{0}}^{2}}{2m\hslash} = \frac{\hslash{k_{0}}^{2}}{2m}
```

La vitesse de phase est donc :

$$v_{\varphi} = \frac{\omega_{0}}{k_{0}} = \frac{\hslash k_{0}}{2m}$$

Pour construire une fonction qui ne possède de valeurs appréciables que
dans une région limitée de l\'espace, il faut superposer des ondes ayant
différentes valeurs de k et de ω.

Considérons une fonction de la forme :

$$\Psi(x,t) = \sum_{S}^{}{{A_{S}\cos}{(k_{S}x - \omega_{S}t)}}$$

où les amplitudes $A_{S}$ mesurent l\'importance relative des
différentes ondes superposées. On peut en principe choisir les $A_{S}$
de manière à produire une fonction $\Psi(x,t)$ qui n\'a des valeurs
importantes que dans une région localisée de l\'espace.

Supposons qu\'à $ t = 0$, $\Psi(x,0)$ est la superposition de trois
ondes telles que :

$k_{1} = k_{0} - \frac{\Delta k}{2}$, $k_{2} = k_{0}$,
$k_{3} = k_{0} + \frac{\Delta k}{2}$, $A_{1} = A_{3} = \frac{A_{0}}{2}$
et $A_{2} = A_{0}$

De plus, nous supposerons que $ \Delta k \ll k_{0}$, c\'est-à-dire que
la dispersion des valeurs de $k$ est petite par rapport à la moyenne
$k_{0}$.

On a donc :

$$\Psi(x,0) = A_{0}\left\lbrack \frac{1}{2}\cos\left( x(k_{0} - \frac{\Delta k}{2}) \right) + \cos\left( k_{0}x \right) + \frac{1}{2}\cos\left( x(k_{0} + \frac{\Delta k}{2}) \right) \right\rbrack$$

d\'où :

$$\Psi(x,0) = A_{0}\left\lbrack 1 + \cos\left( \frac{\Delta k}{2}x \right) \right\rbrack\cos\left( k_{0}x \right)$$

soit :

$$\Psi(x,0) = {2A}_{0}\cos^{2}\left( \frac{\Delta k}{4}x \right)\cos\left( k_{0}x \right)$$

On a donc une fonction qui oscille très rapidement
$\cos\left( k_{0}x \right)$ et dont l\'amplitude est modulée par une
autre fonction dont l\'oscillation est beaucoup plus lente. L\'amplitude
oscille entre les valeurs $0$ et ${2A}_{0}$et elle atteint son maximum
en $x = 0$ à $t = 0$.

```{code-cell} ipython3
# -*- coding: utf-8 -*-
import numpy as np
import math
import matplotlib
import matplotlib.pyplot as plt


def paquet(x, k0, delta_k, A0):
    """
    paquet d'ondes
    """
    return (2 * A0 * np.cos(k0 * x) * np.cos(delta_k * x / 4.)**2)

# script principal

# donnees
A0 = 10.
deltak = 3
k0 = 30.
nbPeriodes = 4
npPointsParPeriode = 100

#dicretisation abscisses
nbPointsDiscrt = int(nbPeriodes * npPointsParPeriode * 4 * math.pi /deltak)

x = np.linspace(- nbPeriodes * 4 * math.pi / deltak / 2, nbPeriodes *4 * math.pi / deltak / 2, nbPointsDiscrt + 1)

y = paquet(x, k0, deltak, A0)

# Premieres annulations du cos()**2 pour phase = +/- pi / 2

xnulNeg = - 2 * math.pi / deltak
xnulPos = 2 * math.pi / deltak

plt.figure()

plt.plot(x,y,label = 'paquet d\'ondes')

plt.axvline(xnulNeg,color='gray',linestyle='--',label =
'-2pi/deltak') # tracer droite verticale

plt.axvline(xnulPos,color='red',linestyle='--',label =
'+2pi/deltak')

plt.xlabel('x')

plt.ylabel('y')

plt.legend()
```

```{figure} media/image23.jpg
:name: fig-paquetOnde
:alt: Paquet d'ondes périodique
:width: 90%
Paquet d'ondes périodique
```

A $t = 0$, la fonction $\cos^{2}\left( \frac{\Delta k}{4}x \right)$
s\'annule en :

$$x = \pm \frac{2\pi}{\Delta k}$$

La largeur spatiale de l\'enveloppe est :

$$\Delta x = \frac{4\pi}{\Delta k}$$

alors que la largeur en impulsion est :

$$\Delta p = \hslash\Delta k$$

Le mouvement étant unidimensionnel selon l'axe $Ox$, le produit de ces
deux grandeurs est donné par :

```{math}
:label: eq-deltaxdeltap

\Delta x\Delta p = \Delta x\Delta p_{x} = 4\pi\hslash
```

C\'est donc une grandeur fondamentale indépendante des caractéristiques
des ondes superposées. Ainsi pour construire une fonction bien localisée
dans l\'espace il faut superposer des ondes correspondant à une grande
dispersion des impulsions. **<u>Il est donc impossible de représenter une
particule ayant une impulsion et une position bien définies
simultanément.</u>**

Le calcul simple effectué ici avec seulement trois ondes planes donne en
fait une fonction périodique de $x$ ; la particule possède donc une
infinité d\'images du lobe centrale comme le montre la {numref}`fig-paquetOnde`. En réalité il est possible de construire une
fonction qui ne possède qu\'une seule image (ou lobe de l'enveloppe) ou
qui interfère de manière constructive dans une seule région de l'espace
d'extension finie. Pour cela il est nécessaire de superposer un très
grand nombre d'onde de valeurs de $k$ très proches.

A la limite, la superposition forme un continuum de telle manière que la
somme sur les différentes valeurs de $k$ devient une intégrale. En
représentation complexe on a :

$$\Psi(x,t) = \int_{- \infty}^{+ \infty}{A(k)e^{i(kx - \omega t)}dk}$$

où l\'amplitude $A(k)$ peut être complexe.

On écrit, de manière équivalente :

```{math}
:label: eq-paquetInt1D

\Psi(x,t) = \int_{- \infty}^{+ \infty}{\left| A(k) \right|{e^{i\alpha(k)}e}^{i(kx - \omega t)}dk}
```

On suppose que $\left| A(k) \right|$ possède des valeurs appréciables
dans un intervalle $\Delta k$ centré autour d\'une valeur $k_{0}$.
L\'intégrale {eq}`eq-paquetInt1D` sera maximale en module à chaque
instant lorsque les ondes d\'amplitudes les plus grandes c\'est-à-dire
celles qui correspondent à $k$ voisin de $k_{0}$ interfèreront de
manière constructive. Ceci se produit lorsque la phase de ces ondes qui
dépend de $k$ ne varie pratiquement pas autour de
$k = k_{0}$. On écrit donc la condition de phase stationnaire :

$$\frac{d}{dk} (\alpha + kx - \omega t) = 0$$

c\'est-à-dire :

$$\frac{d\alpha}{dk} + x - \frac{d\omega}{dk}t = 0$$

soit :

$$x = \frac{d\omega}{dk}t - \frac{d\alpha}{dk}$$

La relation ci-dessus est l\'équation d\'un mouvement uniforme à la
vitesse :

$$v_{g} = \frac{d\omega}{dk}$$

Cette grandeur est appelée vitesse de groupe {index}`Vitesse de groupe`. Elle correspond précisément à la vitesse de
déplacement du centre du paquet d\'onde.

La quantité $- \frac{d\alpha}{dk}$ est indépendante du temps et joue le
rôle de position initiale.

En utilisant la relation de dispersion {eq}`eq-dispOmega0`, on trouve
:

$$v_{g} = \frac{\hslash k}{m}$$

c\'est-à-dire :

$$v_{g} = \frac{p}{m} = v$$

C\'est donc la vitesse de groupe qui est associée à la vitesse de la
particule.

Remarque

Chaque onde composant le paquet d\'onde se déplace avec sa propre
vitesse qui est la vitesse de phase puisque cette dernière dépend de la
valeur de $k$. Ainsi l\'évolution temporelle d\'un paquet d\'onde montre
une propagation du paquet subissant une déformation de la forme du
paquet. C\'est la raison pour laquelle la relation qui donne $\omega$ en
fonction de $k$ s\'appelle la relation de dispersion.

Il est donc possible de construire une fonction localisée dans l\'espace
mais <u>à la condition d\'accepter une certaine dispersion des vecteurs
d\'onde</u> c'est-à-dire des impulsions. Or pour qu\'une
particule possède une trajectoire bien définie il faut qu\'elle possède
à chaque instant une position et une impulsion bien définies. Il semble
donc impossible d'attribuer de telles grandeurs à une particule si on la
représente à l\'aide d\'un paquet d\'ondes.

On retrouve le constat fait dans le cas de la diffraction des électrons
par une fente quant à l\'incompatibilité de la grandeur position et
impulsion.

## Mesures de la position et l\'impulsion

Nous venons de voir, dans une tentative de réduire la réalité du monde
physique à celle des ondes (paquet d\'ondes) ou à celle des particules
(diffraction des électrons par une fente), qu'il est impossible
d'attribuer une position et une impulsion bien définies à une particule,
et donc de lui attribuer une trajectoire.

Cette limitation constitue-elle un échec fatal pour cette démarche ?

<u>Est-il possible de connaître la position et l'impulsion d'une particule
avec une précision illimitée ?</u> L\'utilisation d\'un
diaphragme est sans doute la méthode la plus directe pour mesurer la
position d\'un électron. Cependant, on peut également éclairer cet
objet et observer sa position au travers d\'un microscope.

Heisenberg a fait une analyse critique de ce processus de mesure
(*observer effect*) en s'intéressant à la mesure précise de la position
d'un électron. L'expérience de pensée qu'il a proposée est connue sous
le nom de microscope de Heisenberg {index}`Microscope de Heisenberg`. Nous allons la décrire ici.

Lorsqu\'un objet macroscopique est éclairé, il n\'est pas perturbé par
l\'impact des photons et on peut l\'observer sans le déranger. Il n\'en
va pas de même d\'un objet microscopique comme un électron par exemple

Ainsi si on éclaire un électron et que l'on observe les photons
défléchis dans une lentille, on remonte à la connaissance de la position
de l'électron. L\'expérience de Compton a montré qu\'il subit un recul
sous l\'impact du photon. <u>On perturbe donc l'électron en lui imposant
un changement d\'impulsion</u>. Or pour obtenir une bonne
résolution spatiale il faut utiliser une longueur d\'onde courte
c\'est-à-dire des photons de grande impulsion. La perturbation que subit
l\'électron est alors plus grande. Si l'on souhaitait mesurer de manière
subséquente l'impulsion de l'électron, il faudrait évaluer la
perturbation provoquée par la mesure qui relève du processus de mesure.
On peut évaluer une telle perturbation en mesurant le changement
d\'impulsion du photon. On mesure donc l'impulsion finale du
photon en supposant que la seule source d\'imprécision provient de cette
mesure.

Considérons un électron éclairé par un faisceau de lumière (pas
nécessairement visible pour l\'œil humain). L\'observation, à l\'aide
d\'un microscope, d\'un photon diffusé par l\'électron permet d\'obtenir
une information sur sa position {numref}`fig-micHeisen`. Or la
précision obtenue sur la mesure de la position est limitée par le
pouvoir séparateur du microscope. Puisque celui-ci ne peut pas donner
des images distinctes de deux points dont la différence d\'ordonnées est
inférieure à :

$$\delta = \frac{\lambda}{2\sin(\theta/2)}$$

l\'incertitude sur l\'ordonnée de l\'électron est de l\'ordre de
$\Delta y = \delta$.

```{figure} media/image17.png
:name: fig-micHeisen
:alt: Principe du microscope d\'Heisenberg
:width: 90%
Principe du microscope d\'Heisenberg
```

On suppose que l\'impulsion initiale du photon $\overrightarrow{p}$ est
connue avec une précision illimitée. L\'observateur ou instrument qui
reçoit le photon sait uniquement que celui-ci a traversé la lentille
mais il ignore par quel endroit il est passé.

Evaluons l\'impulsion transférée par le photon à l\'électron. Avant la
collision, nous supposons que l\'électron est au repos
$\overrightarrow{p^{e}} = \overrightarrow{0}$ en $y = 0$. L\'impulsion
du photon est supposée connue avec une précision illimitée. Sa direction
est le long $Oy$ est son module est $p = \frac{h}{\lambda}$. Après la
collision, l\'impulsion transférée à l\'électron sur Oy est
$mv_{y}^{e}$. Cette dernière est maximale lorsque la composante selon
$Oy$ de l'impulsion du photon est négative et que la direction de
diffusion correspond à l'angle maximal autorisé par l'ouverture
angulaire de la lentille (chemin **<u>2</u>**). On a alors
d\'après la relation de conservation de l\'impulsion totale pour le
chemin **<u>2</u>**:

$$\overrightarrow{p} + \overrightarrow{0} = \overrightarrow{p'} + \overrightarrow{p'^{e}}$$

On projette sur $Oy$ en multipliant scalairement par le vecteur
unitaire $\overrightarrow{e_{y}}$:

$$\frac{h}{\lambda} + 0 = - \frac{h}{\lambda{}'}\sin\frac{\theta}{2} + mv^{e}_{y}{}'$$

L\'impulsion transférée est minimale lorsque la composante selon $Oy$ du
photon est positive (chemin **<u>1</u>**) :

$$\frac{h}{\lambda} + 0 = \frac{h}{\lambda"}\sin\frac{\theta}{2} + mv_{y}^{e}{}"$$

Des équations précédentes, on peut tirer que l\'impulsion suivant $Oy$
de l\'électron est comprise entre
${p_{y}^{e}{}"} = \frac{h}{\lambda} - \frac{h}{\lambda"}\sin\frac{\theta}{2}$
et
${p_{y}{}'^{e}} = \frac{h}{\lambda} + \frac{h}{\lambda'}\sin\frac{\theta}{2}$

En supposant que $\lambda' \simeq \lambda$ et que
$\lambda" \simeq \lambda$, on en déduit que l\'incertitude sur la
composante suivant $Oy$ de l\'électron après la collision est :

$${\Delta p}_{y}^{e} = \frac{h}{\lambda}\sin\frac{\theta}{2} = p\sin\frac{\theta}{2}$$

L\'utilisation d\'une courte longueur d\'onde et d\'une grande ouverture
angulaire pour la lentille conduit à une petite incertitude sur la
position mais à une grande incertitude sur l\'impulsion. Le produit des
incertitudes est indépendant de la longueur d\'onde et de l\'ouverture
de la lentille.

En effet, on a :

$$\Delta y{\Delta p}_{y}^{e} = \frac{h}{2}$$

Ce produit ne peut pas être rendu arbitrairement petit car il est
proportionnel à une constante fondamentale de la physique. Nous avons
obtenu en fait une limite inférieure pour le produit des incertitudes.

On peut donc écrire :

$$\Delta y{\Delta p}_{y}^{e} \geq \frac{h}{2}$$

La détermination de la trajectoire d\'une particule implique la mesure
simultanée de sa position et de sa vitesse (ou de son impulsion).

La relation précédente implique donc que la trajectoire des objets
**microscopiques n\'est pas mesurable**.

Ceci contredit le modèle de Bohr dans lequel le mouvement de l\'électron
décrit une orbite bien définie. Si ces trajectoires existaient vraiment,
pour les observer, il faudrait utiliser des photons dont la longueur
d\'onde soit inférieure à 10^-10^ m (diamètre de l\'atome d\'hydrogène
dans son état fondamental). De tels photons se trouvent dans la gamme
des rayons X et leur énergie est supérieure à 12500 eV. Cette énergie
est considérable par rapport à l\'énergie de liaison de l\'électron
(13,6 eV). L\'électron risquerait donc d\'être éjecté de l\'atome. Ces
considérations montrent qu\'il est impossible d\'observer la trajectoire
d\'un électron dans un atome.

La trajectoire n\'étant pas observable à l\'échelle atomique d\'après
Heisenberg, il n'est pas nécessaire de construire une théorie dans
laquelle cette notion est définie. En effet la physique doit fournir une
réponse uniquement aux questions qui se posent en termes d\'expériences.

## Interprétation des inégalités de Heisenberg

La position et l\'impulsion d\'une particule ne peuvent pas être connues
simultanément avec une précision illimitée. En effet nous avons vu
formule {eq}`eq-deltaxdeltap` que le produit $\Delta x\Delta p_{x}$ ne
peut pas être rendu arbitrairement petit car il est proportionnel à une
constante fondamentale de la physique. Nous avons obtenu en fait une
limite inférieure pour le produit des incertitudes dont on peut donner
une formulation plus générale appelé inégalité d'Heisenberg {index}`Inégalité d’Heisenberg` :

$$\Delta x\Delta p_{x} \geq \hslash$$

La valeur précise de la limite n\'a pas de sens tant qu\'une définition
précise de $\Delta x$ et de $\Delta p_{x}$ n\'a pas été donnée. Cette
limite est cependant toujours liée à la constante de Planck.

***Question*** : l\'inégalité de Heisenberg traduit-elle une incertitude
(liée au processus de mesure) ou une indétermination ?

<u>La première hypothèse</u> suppose que la position et
l\'impulsion ont des valeurs bien définies dans la nature mais que les
limitations liées au processus de mesure (*observer effect* {index}`observer effect`) ou aux appareils de mesure nous empêchent de
les connaître avec une précision illimitée.

<u>La seconde hypothèse</u> suppose au contraire que ces
grandeurs ne sont pas bien définies dans la nature et qu\'en conséquence
il est impossible de les mesurer avec une précision illimitée. Nous
allons adopter ce second point de vue et nous allons voir que les
inégalités de Heisenberg nous permettent d\'apprendre quelque chose sur
le comportement des systèmes physiques.

La quantité $\Delta x$ représente l\'extension spatiale d\'un objet
microscopique tandis que $\Delta p_{x}$ représente son extension en
impulsion. Du point de vue d\'une répartition statistique des résultats
d\'une mesure, ces valeurs sont assimilables à l\'écart type ou écart
quadratique moyen.

On aura donc :
$\Delta x = \sqrt{\left\langle x^{2} \right\rangle - \left\langle x \right\rangle^{2}}$
et
$\Delta p_{x} = \sqrt{\left\langle {p_{x}}^{2} \right\rangle - \left\langle p_{x} \right\rangle^{2}}$

Si la valeur moyenne est nulle il vient :

$\Delta x = \sqrt{\left\langle x^{2} \right\rangle}$ et $\Delta p_{x} = \sqrt{\left\langle {p_{x}}^{2} \right\rangle}$

Ainsi les quantités $\Delta x$ et $\Delta p_{x}$ fournissent un ordre de
grandeur ou une estimation de $|x|$ et de $\left| p_{x} \right|$. Si on
note *a* l\'extension spatiale, l\'extension en impulsion s\'écrit
d'après la limite inférieure de l'inégalité d'Heisenberg :

$$\Delta p_{x} \simeq \frac{\hslash}{\Delta x} = \frac{\hslash}{a}$$

C\'est une valeur représentative de $\left| p_{x} \right|$.

### Effet tunnel

Nous allons terminer par un exemple qui présente un immense intérêt
aussi bien pratique que théorique : l\'effet tunnel {index}`Effet tunnel`.

Considérons le mouvement unidimensionnel d\'une particule soumise à une
interaction qui lui donne une énergie potentielle V(x) ({numref}`fig-effetTunnel`).

```{figure} media/tunnel.png
:name: fig-effetTunnel
:alt: Angles de polarisationEffet tunnel
:width: 90%
Effet tunnel
```

Supposons que son énergie totale soit inférieure
à la valeur maximale de V(x). En chaque point son énergie cinétique est
donnée par :

$$E_{cin} = E - V(x)$$

D\'après la théorie classique la particule ralentit lorsque l\'énergie
potentielle augmente et la région où $E < V_{0}$ est interdite car
l\'énergie cinétique ne peut pas être négative.

D\'après la théorie classique, si la particule se trouve d\'un côté de
la barrière à un instant donné elle y reste. En effet pour aller de A en
B elle devrait passer par toutes les positions intermédiaires
d'abscisses pour lesquelles l'énergie cinétique serait négative car la
particule possède une trajectoire bien définie.

La relation d\'indétermination de Heisenberg implique que la particule
ne possède pas de trajectoire. Il ne lui serait donc pas interdit de
faire la transition de A à B. En effet considérer cette transition
n'implique pas que **<u>son énergie cinétique puisse être considérée comme
négative à un instant donné !</u>** Pour pouvoir faire une
telle affirmation, il faudrait mesurer sa position avec une précision
nettement meilleure que la largeur de la barrière. Nous
trouverions alors que la limitation de l\'extension spatiale
$\Delta x = a$ produirait une augmentation de l\'impulsion (et donc de
l\'énergie cinétique) tellement grande qu\'on ne pourrait pas affirmer
que l\'énergie totale serait inférieure à la hauteur de la barrière. En
fait, il n\'y a pas de contradiction entre la traversée de la barrière
et la conservation de l\'énergie parce que le concept de trajectoire
(évolution continue dans l\'espace-temps) n\'a pas de sens.

Ce genre de phénomène se produit couramment dans les atomes, les
molécules, les solides et les noyaux. Il a reçu le nom d\'effet tunnel.

## Limite de validité de la physique classique

Si les électrons passent à travers une fente de largeur $d$,
l'expérience montre que les effets quantiques sont négligeables si
$\lambda \ll d$. Il suffit de quelques dizaines d\'*eV* pour qu\'un
électron ait une longueur d\'onde de l\'ordre de l\'Angström,
c\'est-à-dire une distance très courte à l\'échelle macroscopique.
Cependant, lorsqu\'il atteint un cristal ou une poudre c\'est la
distance inter atomique qui joue le rôle de distance caractéristique.
Comme elle est de l\'ordre de 1 Å, des effets quantiques se manifestent.

Reprenons en guise d\'illustration l\'expérience de diffraction des
électrons par un diaphragme. La diffraction est négligeable si :

$$\frac{\delta p_{y}}{p_{x}} \ll 1$$

soit :

$$\delta p_{y} \ll p_{x} \simeq p$$

ou encore :

$$\frac{h}{\delta y} \ll \frac{h}{\lambda}$$

ce qui est toujours le cas si $\lambda \ll d$.

Pour conclure, on peut formuler le critère de validité de la mécanique
classique à l\'aide des inégalités de Heisenberg. Tant que la précision
des mesures est telle que :

$\Delta x\Delta p_{x} \gg \hslash$, $\Delta y\Delta p_{y} \gg \hslash$
et $\Delta z\Delta p_{z} \gg \hslash$

les effets quantiques ne se manifestent pas dans l'expérience.

 [^37]: La force électrostatique est une force conservative. Agissant sur
    une particule, une force $\overrightarrow{F}$ produit un travail
    lorsque la particule se déplace d\'un point $a$ à un point $b$ :
    $W_{a > b} = \int_{a}^{b}{ \overrightarrow{F}.\overrightarrow{dl}}$
    où $\overrightarrow{dl}$ est le déplacement élémentaire. La force
    étant conservative on a $W_{a > b} = - (U_{b} - U_{a})$ où $U$ est
    l\'énergie potentielle associée à $\overrightarrow{F}$. Le calcul du
    travail de la force électrostatique s\'exerçant sur une charge test
    $q_{b}$ du fait du champ électrique produit par une charge $q_{a}$
    lors d\'un déplacement radial conduit à l\'énergie potentielle
    électrostatique
    $U = \frac{1}{4\pi\varepsilon_{0}}\frac{q_{a}q_{b}}{r}$
    d\'interaction électrostatique entre deux charges ponctuelles
    $q_{a}$ et $q_{b}$ séparée de $r$.

 [^38]: Les rayons X sont des radiations électromagnétiques très
    énergétiques (0.5 à 30 KeV). Ils peuvent être produits par
    ionisation en couche interne d\'un atome. Le trou est comblé par un
    électron provenant d\'une couche externe avec émission d\'un photon
    X. Ils peuvent être également produit par l\'accélération (freinage)
    des électrons sur une cible dans un tube à rayons X : les électrons
    sont extraits d\'une cathode
    de tungstène chauffée, accélérés par une tension électrique dans un
    tube sous vide, ce faisceau sert à bombarder une cible métallique
    (appelée anode ou anti-cathode) ; le ralentissement des électrons
    par les atomes de la cible provoque un rayonnement continu de
    freinage

 [^39]: Walter Friedrich ()

 [^40]: Paul Knipping ()
