---
title: "Rappel comportement ondulatoire classique"
description: "Notions d'ondes classiques."
authors:
  - name: Gilles Nguyen Vien
    affiliation: Département de Physique, Université de Bretagne Occidentale
license:
  id: "CC-BY-NC-ND-4.0"

date: 2026-01-19
---

# Rappel comportement ondulatoire classique

Avant d\'aborder la lumière, il est utile pour la suite de présenter
brièvement des généralités sur les ondes classiques.

## Généralités sur les ondes

Une onde est une {index}`vibration` se propageant de proche en
proche. La grandeur qui vibre peut être de différentes
natures :

- une pression,

- une déformation,

- un champ électrique,

- un champ magnétique...

Les ondes ont besoin d\'un support matériel (gaz, solide, liquide)
hormis les ondes électromagnétiques. Ces dernières peuvent se propager
dans le vide. La lumière, les ondes \"radios\", les rayons X sont des
ondes électromagnétiques, qui comme leur nom l\'indique, sont formées
par la combinaison de deux champs oscillants l'un électrique et l'autre
magnétique. Lorsque ces ondes se propagent dans un milieu, elles
perturbent l\'ordonnancement des charges électriques élémentaires
(électrons, noyaux...).


La **vibration** est caractérisée par une
direction portée par $\overrightarrow{u}$, une amplitude $a$ et une
{index}`pulsation` $\omega$ imposée par la source.

Un point $M$ de l\'espace (ou du milieu) sera le siège d\'une
modification temporaire de même nature que celle provoquée au point
source $S$ mais avec un certain retard $\theta$ dans le temps. Si $d$
sépare $S$ de $M$, ce retard est tel que :

$$\theta = \frac{d}{c}$$

La **propagation** est caractérisée par la vitesse $\overrightarrow{c}$ de l\'onde dont la norme $c$, appelée {index}`vitesse de phase`, <u>dépend du milieu
traversé</u>. La célérité est constante pour une onde donnée et
pour un milieu homogène donné. Si le milieu est **{index}`isotrope`** 
, la célérité est la même dans toutes les
directions issues de $S$. A titre d'exemple, la {index}`propagation` d'une onde
sinusoïdale dans une direction donnée se traduit par une translation de
la sinusoïde à la vitesse qui est précisément la célérité.

Une **{index}`onde longitudinale`** est
telle que la vibration et la propagation ont la même direction. A titre
d\'exemple, citons les ondes acoustiques dans les gaz ainsi que les
ondes de pression dans les liquides et les solides.

Une **{index}`onde transversale`**
 est
telle que les directions de vibration et de propagation sont
perpendiculaires. La corde vibrante, les ondes de déformations dans les
solides et les ondes électromagnétiques dans le vide illustrent ce type
d\'onde.

Hormis pour les ondes longitudinales, les directions de propagation et
de vibrations définissent un plan appelé **{index}`plan de polarisation`** .

### Onde plane

Une onde monochromatique (1 seule {index}`fréquence`) est l'onde progressive
périodique la plus simple. Elle possède par définition une double
{index}`périodicité`
 spatiale et temporelle. Une
sinusoïde possédant de telles propriétés, on peut représenter une
vibration monochromatique sous la forme {eq}`eq-OP3D`:

```{math}
:label: eq-OP3D
f\left( \overrightarrow{r},t \right) = a\cos\left( \overrightarrow{k}.\overrightarrow{r} - \omega t \right)
```

où $a$ est l\'amplitude maximum de vibration, $\overrightarrow{k}$ le
vecteur d\'onde, $\overrightarrow{r}$ le vecteur position où la
vibration est observée et $\omega$ la pulsation.
$\left( \overrightarrow{k}.\overrightarrow{r} - \omega t \right)$ la
phase de l\'onde.

L\'ensemble des points de l\'espace pour lesquels la phase est
constante à un instant donné forme une **{index}`surface d'onde`**  ou **{index}`front d'onde`** . On peut déterminer
une surface d\'onde en cherchant l\'ensemble des points $M$ pour
lesquels $\overrightarrow{k}.\overrightarrow{r}$ a une valeur constante
à $t$ donné.

Prenons un point $M_{1}$ de l'espace dont la position est telle que :

$$\overrightarrow{k}.\overrightarrow{r_{1}} = \overrightarrow{k}.\overrightarrow{{OM}_{1}}$$

$$\overrightarrow{k}.\overrightarrow{r_{1}} = \overrightarrow{k}.\left( \overrightarrow{OM} + \overrightarrow{{MM}_{1}} \right) = \overrightarrow{k}.\overrightarrow{OM} + \overrightarrow{k}.\overrightarrow{MM_{1}}$$

Si on impose $M_{1}$ de telle manière que la phase soit la même que pour
le point $M$, on obtient :

```{math}
:label: eq-plan
\overrightarrow{k}\cdot \overrightarrow{MM_{1}} = 0
```

Les points $M$ et $M_{1}$ emplissant la condition {eq}`eq-plan`
se trouvent dans un plan perpendiculaire à $\vec{k}$.


```{figure} media/image2.png
:name: fig-frontDOnde
:alt: Front d'onde
:width: 70%
Front d'onde
```

Si on fait coïncider l\'axe $Ox$ avec la direction de
$\overrightarrow{k}$, on a $k_{y} = k_{z} = 0$ et $k_{x} = k$. La
fonction {eq}`eq-OP3D` s\'écrit alors :

```{math}
:label: eq-OP1D
f(x,t) = a \cos(kx - \omega t)
```

et les surfaces d\'onde sont les plans perpendiculaires à $Ox$ :


```{figure} media/image4.png
:name: fig-frontsDOnde
:alt: Fronts d'onde
:width: 90%
Fronts d'onde
```

Les relations {eq}`eq-OP3D` et {eq}`eq-OP1D` définissent une
**{index}`onde plane`**.

La plus petite distance $\lambda$ telle que :

```{math}
:label: eq-periodelambda
f(x + \lambda,t) = f(x,t)
```

à chaque instant s\'appelle la **{index}`longueur d'onde`** . C\'est donc la distance
entre deux fronts d\'onde successifs de même phase. La condition
{eq}`eq-periodelambda` est satisfaite si le remplacement de $x$
par $x + \lambda$ conduit à un changement de phase de $2\pi$.

A partir de {eq}`eq-OP1D`, on trouve :

```{math}
:label: eq-lambda
\lambda = \frac{2\pi}{k}
```

Le plus petit intervalle de temps $Τ$ telle que :

```{math}
:label: eq-periodeT
f(x,t + T) = f(x,t)
```

en chaque point de l\'espace s\'appelle la
**{index}`période`** . La période est bien le temps
au bout duquel l\'état de vibration se reproduit identiquement en un
point de l\'espace. La condition {eq}`eq-periodeT` est satisfaite si
le remplacement de $t$ par $t + T$ conduit à un changement de phase de
$- 2\pi$.

A partir de {eq}`eq-OP1D`, on trouve :

$T = \frac{2\pi}{\omega}$

Ainsi, {eq}`eq-OP1D` conduit à :

$$f(x,t) = a\cos\left( 2\pi\left( \frac{x}{\lambda} - \frac{t}{T} \right) \right)$$

La fréquence est le nombre de fois par
seconde qu'en un point donné de l'espace, l'état de vibration se
reproduit identiquement. C'est donc la valeur inverse de la période :

```{math}
:label: eq-nu
\nu = \frac{1}{T}
```

Si d\'autre part, l'observateur photographie à un instant donné l\'onde,
il observera que les propriétés du milieu varient de manière sinusoïdale
en fonction de la position. Cela met en évidence la périodicité spatiale
qu'est la longueur d\'onde $\lambda$. C'est donc la distance entre deux
fronts d'onde successifs de même phase.

Au fur et à mesure que le temps s\'écoule, la phase de l\'onde varie en
un point donné de l'espace. Si un observateur voulait se trouver à
chaque instant en un point tel que la phase soit constante (sur une
crête par exemple), il devrait se déplacer à une vitesse qui est par
définition la **{index}`vitesse de phase`**
de l\'onde.

Pour obtenir la vitesse de phase ou **{index}`célérité`**, il suffit de mesurer la distance élémentaire
$dx$ séparant deux points de l\'espace présentant la même phase et le
temps nécessaire $dt$ pris par l\'onde pour parcourir cette
distance. La phase étant constante, cela revient à affirmer que
la différentielle de la phase est nulle soit :

$$d(kx - \omega t) = 0$$

soit :

$$kdx - \omega dt = 0$$

d\'où :

```{math}
:label: eq-vphi
\frac{dx}{dt} = \frac{\omega}{k} = v_{\varphi}
```

Ce résultat signifie que l\'onde se déplace dans le sens positif de
l\'axe $Ox$.

La fonction :

```{math}
:label: eq-OPNegatif
f(x,t) = a \cos(kx + \omega t)
```
représente donc une onde se déplaçant dans le sens négatif de l\'axe
$Ox$ à une vitesse :

$$v_{\varphi} = - \frac{\omega}{k}$$

Cette relation donnant la vitesse de phase reste la même quel que soit
le milieu pour l'onde monochromatique {eq}`eq-OP1D`.

Si l'observateur avait pris deux clichés à des instants très rapprochés,
il verrait que la sinusoïde s'est déplacée à la vitesse de phase.

Une onde monochromatique {eq}`eq-OP1D` est donc caractérisée par
une pulsation $\omega$ et par un nombre $k$ module du vecteur d\'onde
que l'on nomme nombre d'onde {index}`nombre d’onde`. D'après
la relation {eq}`eq-lambda`, $k$ est le nombre de longueurs d'onde
contenues dans une distance de $2\pi$ (période de la fonction
sinusoïdale). Son unité est le radian par mètre et sa dimension
l\'inversion d\'une longueur ($L^{- 1}$).

La pulsation $\omega$ et le nombre d'onde $k$ sont liés par une relation
appelé **<u>{index}`relation de dispersion`</u>**. Cette relation est propre à la nature
précise de l'onde et au milieu traversé.

Pour des ondes électromagnétiques (OEM) traversant le vide, il sera
démontré (en électromagnétisme) à partir de l'équation de propagation
que la relation de dispersion est :

```{math}
:label: eq-dispOEM

\omega = ck
```

```{math}
:label: eq-OS1D`

f(x,t) = a \cos(kx + \omega t)
```

où $c$ est la vitesse de phase de l'onde dans le vide connue sous le nom
de vitesse de la lumière (dans le vide) $c \approx 3 10^{8}$ m/s.

La relation de dispersion {eq}`eq-dispOEM` indique que la pulsation
est une fonction linéaire du nombre d'onde.

D'après {eq}`eq-vphi`, la vitesse de phase est donnée par
$v_{\varphi} = \frac{\omega}{k}$, on montre que la vitesse de phase ne
dépend pas de la pulsation pour les OEM. On dit alors que le milieu est
**non {index}`dispersif`**.

Le vide n'est donc pas un milieu dispersif, la vitesse de la lumière ne
dépendant pas de la couleur. De même l'air ambiant peut être assimilé à
un {index}`milieu` non  pour les ondes acoustiques (la note de la
contrebasse parvient à l'auditeur en même temps que le coup de cymbale
pour peu que les instruments aient été sollicités au même instant).

Dans un milieu transparent, la vitesse de phase des ondes
électromagnétiques est diminuée d'une quantité quantifiée par l'indice
de réfraction du milieu dont on
peut montrer qu'il dépend de la pulsation :

$$n(\omega) = \frac{c}{v_{\varphi}}$$

Un milieu est dit **dispersif** si
l'{index}`indice du milieu` dépend de la pulsation de l'onde.

Le verre est un milieu dispersif dont l'indice augmente lorsque la
longueur d'onde diminue. Cette conséquence est une réfraction différente
pour des longueurs d'onde différentes (prisme).

Pour les vagues en eau profonde, la relation de dispersion est donnée
par :

$$\omega = \sqrt{gk}$$

ce qui conduit à une vitesse de phase dépendant du nombre d'onde :

$$v_{\varphi} = \frac{\omega}{k} = \sqrt{\frac{g}{k}}$$

Le milieu est dispersif.

Une onde qui résulte de la somme d'ondes monochromatiques de pulsation
et de longueurs d'onde différentes se propagera dans un milieu dispersif
avec une déformation puisque les composantes monochromatiques se
dispersent.

Plus généralement, tout phénomène **<u>périodique continu non
sinusoïdal</u>** peut être représenté par une somme discrète de
fonctions sinusoïdales (série de Fourier {index}`série de fourier`). En outre, toute fonction continue peut se
décomposer en une somme continue (intégrale) de fonctions sinusoïdales
(transformée de Fourier {index}`transformée de fourier`).

Dans certaines applications, il est commode d\'utiliser la
représentation complexe de l\'onde :

```{math}
:label: eq-OPReel
f(x,t) = a \cos(kx - \omega t + \varphi)
```

(les propriétés des fonctions exponentielles simplifient les calculs)
sous la forme :

```{math}
:label: eq-OPComp
\widetilde{f}(x,t) = a exp(j\varphi)\exp\left( j(kx - \omega t) \right) = \widetilde{a}\exp\left( j(kx - \omega t) \right)
```

où $\widetilde{a}$ est l\'amplitude complexe.

Le phénomène est alors représenté par la partie réelle de la forme {eq}`eq-OPComp`.

### Onde sphérique

Une source ponctuelle située en $r = 0$ produit une onde
sphérique représentée par :

```{math}
:label: eq-OSkr
f(r,t) = \frac{a}{r}\cos(kr - \omega t)
```

Son amplitude décroît lorsque $r$ augmente. La surface d\'onde
correspond à la condition $r = const$ à un instant donné. C\'est donc
une sphère de rayon $r$. Les fronts d'onde sont donc des surfaces
sphériques concentriques à la source de l'onde placée en $r = 0$.

La vitesse de phase est alors donnée par :

$$v = \frac{dr}{dt} = \frac{\omega}{k}$$

De nombreuses grandeurs physiques comme les champs électrique et
magnétique sont des grandeurs vectorielles. On les décrit alors par une
onde vectorielle dont l'expression est donnée :

$$\overrightarrow{f}\left( \overrightarrow{r},t \right) = \overrightarrow{a}cos(\overrightarrow{k}.\overrightarrow{r} - \omega t)$$

où $\overrightarrow{a}$ en plus de l'amplitude de l'onde
$\left| \overrightarrow{a} \right|$ indique la direction de
l'élongation.

## Principe de superposition

Le {index}`principe de superposition` s'applique pour des ondes
linéaires <u>c'est à dire des ondes
de petites amplitudes dont la vitesse de propagation est indépendante de
l'amplitude</u> (les ondes de chocs, les ondes acoustiques à
grandes amplitudes sollicitent des propriétés non linéaires des milieux
et matériaux qu'elles traversent).

**L'amplitude des oscillations en un point** $\overrightarrow{r}$ **à
l'instant t est la somme des amplitudes des ondes individuelles
produites par les sources environnantes.**

D\'après ce principe, lorsque deux sources produisent des vibrations de
petites amplitudes, la vibration résultante reçue en un point de
l\'espace est la somme des vibrations produites par chaque source.

Considérons deux sources identiques synchrones {index}`sources synchrones` (donc corrélées) c\'est à dire <u>vibrant
en phase avec la même pulsation</u>. Un
observateur se trouvant à égales distances des deux sources reçoit à
chaque instant des vibrations en phase. Par contre si les deux sources
ne sont pas à la même distance de l\'observateur, il existe un déphasage
entre les vibrations reçues qui provient du fait qu\'elles n\'ont pas
parcouru la même distance pour atteindre l\'observateur.

Dans le cas d\'ondes longitudinales se propageant selon le même axe, le
principe de superposition revient à additionner algébriquement les deux
vibrations.

Pour les ondes transverses dont les directions de vibrations sont
$\overrightarrow{\mu_{1}}$ et $\overrightarrow{\mu_{2}}$ , il faut faire
l\'addition vectorielle. Lorsque $\overrightarrow{\mu_{1}}$ et
$\overrightarrow{\mu_{2}}$ ont la même direction, la vibration
résultante est la somme algébrique des vibrations.

## Energie transportée par une onde

Une onde est un phénomène de propagation d'énergie et d'impulsion
produites par la source et non un phénomène de propagation de matière.

Le calcul de l\'énergie dépend de la nature du phénomène ondulatoire.

<u>Prenons comme exemple le cas de la lumière</u>.

La puissance électromagnétique est un flux d'énergie électromagnétique.

Cette puissance peut être répartie selon des surfaces d'onde différente.
Une source lumineuse telle qu'une ampoule va rayonner dans toutes les
directions et la puissance se répartit sur des sphères centrées sur
l'ampoule dont le rayon devient de plus en plus grand au cours de la
propagation. Pour une propagation se faisant suivant un faisceau
parallèle (laser), la puissance est répartie uniformément sur toute
section perpendiculaire du faisceau.

Si le milieu traversé est non dissipatif non dissipatif (pas d'atténuation de l'onde), <u>la
puissance totale est conservée</u>. Ainsi pour une onde
sphérique la puissance par unité de surface diminue au fur et à mesure
que la sphère s'éloigne de la source. Pour le faisceau dont l'étendue
est supposée constante, la puissance moyenne surfacique est la même
partout dans le faisceau.

Pour exprimer cette puissance, on définit un élément de surface orienté
$d\overrightarrow{s} = ds \overrightarrow{n}$ autour du point M.

Par définition <u>la puissance électromagnétique instantanée</u>
$dw$ qui traverse $d\overrightarrow{s}$ est le flux du vecteur de
Poynting $\overrightarrow{P}$ :

$$dw =  \overrightarrow{P}. d\overrightarrow{s}$$

conduisant à l\'intensité [^1] instantanée
ou densité de flux d'énergie surfacique $dw/ds$ électromagnétique.

Les phénomènes lumineux sont observés par le biais d'un récepteur
(écran+œil, œil, photodétecteur...) emmagasinant l\'énergie pendant un
temps donné que l'on nomme {index}`temps de réponse` (typiquement le temps de réponse
de l'œil est de 0.1 s et une photodiode de l'ordre de $10^{-6}$ s. 

La période de l'onde du visible se situe dans la gamme de la femto
seconde : $10^{- 15}$ s). Le temps de réponse quel que soit le récepteur
évoqué ci-dessus est grand par rapport à la période de l'onde. Cela
implique que le récepteur mesure une valeur moyenne sur le temps
d\'acquisition de l\'intensité instantanée.

Ainsi :

$$I(M,t) = \frac{1}{\tau}\int_{0}^{\tau}{\frac{dw}{ds}dt}$$

On peut montrer pour une onde monochromatique :

L'intensité électromagnétique moyennée $I$ est proportionnelle la valeur
moyenne sur une période du carré de l'amplitude lumineuse selon :

```{math}
:label: eq-kI
I = k\left\langle {a(t)}^{2} \right\rangle
```

où $a(t)$ désigne l'amplitude lumineuse à ne pas confondre avec
l'amplitude maximale de l'onde, k un facteur de proportionnalité.

En outre ce récepteur est caractérisé par une surface d'acquisition.
Ainsi la mesure produite par le récepteur est proportionnelle à
l'intensité électromagnétique $I$.

Comme on ne s'intéresse qu'à des intensités relatives, on prend $k = 2$.


```{math}
:label: eq-2I
I = 2\left\langle {a(t)}^{2} \right\rangle
```

Ainsi le calcul des intensités pourra être exprimé simplement sous forme
complexe.

On suppose qu'une source lumineuse monochromatique (1 seule couleur)
produit une onde d'amplitude $a(t) = a_{0}\cos(\omega t + \varphi)$ en
un point $M$ de l'espace. L'intensité moyennée vaut alors :

$$I = {a_{0}}^{2}$$

car la moyenne temporelle de $\cos(\omega t + \varphi)$ vaut $\frac{1}{2}$. On
associe à $a(t)$ sa forme complexe $\widetilde{a}(t)$ telle que :

$$\widetilde{a}(t) = a_{0}e^{j(\omega t + \varphi)}$$

Alors l'intensité peut être calculée **pour une onde progressive plane
monochromatique** en utilisant la représentation complexe de l'amplitude
comme :

$$I = \widetilde{a}(t){\widetilde{a}(t)}^{*}$$

où ${\widetilde{a}(t)}^{*}$ désigne le complexe conjugué de la grandeur
complexe $\widetilde{a}(t)$.

Remarque

```{note}
L'{index}`onde sphérique` se rapproche de plus en plus de l\'{index}`onde plane` lorsque
le rayon de la sphère devient très grand par rapport aux distances
caractéristiques d\'un système.
```

## Interférences

Les interférences désignent les phénomènes qui se manifestent lors de la
superposition de deux ou plusieurs ondes différentes. Elles sont
observables lorsque les ondes superposées sont
**cohérentes** `.

La {index}`cohérence` revêt deux aspects. On parle de cohérence
spatiale  spatiale et de cohérence temporelle. Elles sont plus
largement présentées en annexe du chapitre ou en optique ondulatoire en
L3.

La cohérence temporelle est caractérisée par l\'aptitude d\'une onde à
interférer avec une partie retardée d\'elle-même. Le temps de
cohérence est la durée
pendant laquelle la phase de l\'onde est prévisible (on peut
dire que l\'onde est sinusoïdale). La longueur de propagation de l\'onde
durant une telle durée est appelée longueur de cohérence.

Une interférence est observable si le retard est inférieur au temps de
cohérence qui une caractéristique de la source lumineuse.

Un laser est une source lumineuse possédant une longueur de cohérence
importante. Cela peut varier de l\'ordre de la dizaine de centimètre
(laser hélium néon) à plusieurs kilomètres pour certaines sources laser.

Une ampoule à filament, la lumière naturelle sont caractérisée par un
temps de cohérence caractéristique de la durée des trains
d\'onde trains d'onde. En effet la lumière est
émise par chaque atome sous forme d\'une succession de trains d\'onde
d\'une durée qui avoisine la dizaine de nanoseconde. Plus
précisément, un atome constituant de la matière lorsqu'il se trouve dans
un état excité [^2], peut revenir dans son état fondamental (état de
plus basse énergie) en émettant un photon dont l'énergie est égale
rigoureusement à la différence d'énergie entre l'état excité et l'état
fondamental de l'atome. Il s'agit de l'émission spontanée `. Ce photon est caractérisé par un train
d\'onde dont la longueur spatiale est liée à la durée mise par l'atome
pour passer d'un état excité à un état désexcité. Chaque émission
atomique est constituée d'un train d'onde quasi monochromatique (mais
pas strictement : effet Doppler notamment) dont on pourrait considérer
qu'il est polarisé rectilignement possédant une amplitude et une phase
initiale donnée. En réalité un train d'onde ne présente pas de
polarisation. En outre, il existe un élargissement spectrale appelé
élargissement de Lorentz qui est la conséquence de la durée de vue
limité d'un état excité produisant une incertitude sur l'énergie de
l'état en vertu de la relation d'incertitude d'Heisenberg.

La cohérence spatiale est caractérisée par la distance entre deux points
d\'une onde pour laquelle l\'onde peut interférer avec une partie
déplacée d\'elle-même.

## L\'expérience de Young

Young émet l\'idée d\'utiliser comme sources deux points d\'une même
surface d\'onde sur la constatation qu\'il est impossible de
synchroniser deux sources indépendantes vibrant à une fréquence aussi
élevée que celle de la lumière visible {cite}`young1804`. **Deux points d\'une même
surface d\'onde peuvent être considérés comme des sources ponctuelles
synchrones** d\'après le principe de Huygens-Fresnel traité en annexe.
Cette expérience, réalisée pour la première fois au début du XIXème
siècle, a mis en évidence un phénomène absolument inexplicable dans le
cadre du modèle géométrique.

L'expérience originelle d'Young fut publiée en 1803. Elle fut réalisée
avec la lumière du soleil. Il perça un trou dans un volet occultant
d'une fenêtre d'une pièce plongée dans le noir. Il disposa une feuille
épaisse opaque derrière le volet et y perça un trou au moyen d'une
aiguille assurant l'obtention d'une aire de cohérence. Le faisceau de lumière de soleil issu de ce
trou fut filtré par réduire sa largeur spectrale (et tendre vers une
lumière monochromatique) réfléchi avec un miroir et séparé en deux au
moyen d'une carte de papier dont l'épaisseur est inférieure à la section
du faisceau. En interposant un écran que l'on pouvait déplacer sur le
trajet du faisceau séparé, Young put observer des images d'interférence.

```{figure} media/image5.png
:name: fig-interference
:alt: Figure d'interférences polychromatiques
:width: 90%
Figure d'interférences polychromatiques.
```

Dans ces figures d'interférences {numref}`fig-interference`, on pouvait observer des franges
claires et sombres manifestant d'un phénomène d'interférences. En outre,
de part et d'autre du maximum d'intensité apparaissait une séparation de
couleur due à la superposition d'image d'interférences dont les
distances interfrange étaient différentes puisque dépendantes de la
fréquence et donc de la couleur.

Afin de comprendre le principe de calcul d'interférences, on considère
deux sources ponctuelles $S_{1}$ et $S_{2}$ (appartenant à une même
surface d\'onde) séparées d\'une distance $d$ sur l\'axe $Oy$ émettent
chacune une vibration sphérique sinusoïdale se propageant à la vitesse
$c$ dans l\'espace délimité par $x > 0$.


```{figure} media/figInterf.png
:name: fig-calculinterf
:alt: Schéma de principe pour le calcul d'interférence entre deux ondes sphériques
:width: 90%
Schéma de principe pour le calcul d'interférence entre deux ondes sphériques.
```

La vibration notée $f_{M}(t)$ reçue en un point $M$ très éloigné des
sources $S_{1}$ et $S_{2}$ de vecteur de position $\overrightarrow{r}$ à
l\'instant $t$ est la superposition de deux ondes sphériques l'une
produite par la source $S_{1}$ distante de
$r_{1} = \left| \overrightarrow{r} - \frac{d}{2}\overrightarrow{e_{y}} \right|$
du point $M$ à l'instant $\left( t - \frac{r_{1}}{c} \right)$ et l'autre
produite par la $S_{2}$ source distante de
$r_{2} = \left| \overrightarrow{r} + \frac{d}{2}\overrightarrow{e_{y}} \right|$
du point $M$ à l'instant $\left( t - \frac{r_{2}}{c} \right)$. Si les
sources sont synchrones (même fréquence et pas de déphasage), elles sont
cohérentes :

```{math}
:label: eq-add2OS
f_{M}(t) = \frac{b_{1}}{r_{1}}\cos\left( \omega\left( t - \frac{r_{1}}{c} \right) \right) + \frac{b_{2}}{r_{2}}\cos\left( \omega\left( t - \frac{r_{2}}{c} \right) \right)
```

Ce qui équivaut aussi à :


```{math}
:label: eq-add2OSEq
f_{M}(t) = \frac{b_{1}}{r_{1}}\cos\left( kr_{1} - \omega t \right) + \frac{b_{2}}{r_{2}}\cos\left( kr_{2} - \omega t \right)
```

On suppose que les deux sources produisent des vibrations de même
amplitude $b_{1} = b_{2}$ et que la séparation entre les sources est
petite devant l\'éloignement ($r_{1},\; r_{2} > > d$).

La différence d\'éloignement $\left( r_{2} - r_{1} \right)$ appelée
{index}`différence de marche` dépend de la direction d\'observation.
Elle est nulle si $M$ coïncide avec $Ox$ et vaut $d$ si $M$ coïncide
avec $Oy$. Pour toute autre direction d\'observation, la différence de
marche est comprise entre $0$ et $d$.

En raison de la différence d\'éloignement de $S_{1}$ et $S_{2}$, les
amplitudes des vibrations reçues en $M$ ne sont pas rigoureusement
égales en particulier dans le cas le plus défavorable où la différence
d'éloignement est maximale et égale à $d$. Dans ce cas précis,
$r_{2}$ est lié à $r_{1}$ par la relation :

$$r_{2} = r_{1} + d$$

Or la détection se fait au point $M$ à grande distance telles que
$r_{2},r_{1} \gg d$. A l'approximation des grandes distances (d négligé
devant ${r_{1}}^{2}$), on a en utilisant le développement limité de
$1/(1 + x)$ avec $x \rightarrow 0$ :

$$\frac{1}{r_{2}} = \frac{1}{r_{1}\left( 1 + d/r_{1} \right)} = \frac{1}{r_{1}}\left( 1 - \frac{d}{r_{1}} + \left( \frac{d}{r_{1}} \right)^{2} + \ldots \right) \approx \frac{1}{r_{1}}$$

De telle manière que :

$$\frac{b_{1}}{r_{1}} \cong \frac{b_{1}}{r_{2}} = a_{0}$$

Cette conclusion se vérifie à plus forte raison pour toutes les autres
directions d\'observation.

Dans l\'approximation des grandes distances (par rapport à $d$), les
ondes sphériques sont assimilables à des ondes planes et <u>le seul effet
de la différence de marche est de déphaser l\'une par rapport à l\'autre
les vibrations reçues en $M$</u> (addition algébrique des deux
vibrations ayant même direction).

L\'intensité étant la valeur moyenne sur une période du carré de la
vibration résultante :

$$I = 2\left\langle \left\lbrack a_{0}\cos{\omega\left( t - \frac{r_{1}}{c} \right)} + a_{0}\cos{\omega\left( t - \frac{r_{2}}{c} \right)} \right\rbrack^{2} \right\rangle$$

Si on utilise la représentation complexe des amplitudes, l'amplitude
résultante ${\widetilde{f}}_{M}(t)$ d'après le principe de
superposition est la somme des amplitudes complexes
$a_{0}e^{j(\omega t + \varphi_{1})}$
et ${a}_{0}e^{j(\omega t + \varphi_{2})}$ avec
$\varphi_{i} = - \omega\frac{r_{i}}{c}$.

L'intensité au point $M$ étant donnée par
$I = {\widetilde{f}}_{M}(t) {{\widetilde{f}}_{M}(t)}^{*} $, on
calcule :

$$I = \left( a_{0}e^{j(\omega t + \varphi_{1})} + {a}_{0}e^{j(\omega t + \varphi_{2})} \right)\left( a_{0}e^{- j(\omega t + \varphi_{1})} + {a}_{0}e^{- j(\omega t + \varphi_{2})} \right)$$

Soit :

$$I = {a_{0}}^{2}\left| e^{j\omega t} \right|^{2}\left( e^{j\varphi_{1}} + e^{j\varphi_{2}} \right)\left( e^{- j\varphi_{1}} + e^{- j\varphi_{2}} \right)$$

Ou encore :

$$I = {a_{0}}^{2}\left\lbrack 1 + 1 + 2Re\left\{ e^{j\varphi_{1}}e^{- j\varphi_{2}} \right\} \right\rbrack$$

On a donc :

$$I = {{2a}_{0}}^{2}\left\lbrack 1 + \cos{\frac{\omega}{c}\left( r_{2} - r_{1} \right)} \right\rbrack = {{2a}_{0}}^{2}\left\lbrack 1 + \cos{k\left( r_{2} - r_{1} \right)} \right\rbrack$$

$I$ atteint son maximum lorsque $\cos k\left( r_{2} - r_{1} \right) = 1$
c\'est à dire lorsque :

$$k\left| r_{2} - r_{1} \right| = n\; 2\pi$$

avec
$n = 0,\; 1,\; 2,\; 3...$

soit :

$$\left| r_{2} - r_{1} \right| = n\;\frac{2\pi}{k} = n\;\lambda$$

La différence de marche est un multiple entier de la longueur d\'onde.
On dit alors que l\'interférence est constructive.

La puissance reçue est nulle lorsque
$\cos k\left( r_{2} - r_{1} \right) = - 1$ soit :

$$\left| r_{2} - r_{1} \right| = (2n + 1)\;\frac{\lambda}{2}$$

Lorsque la différence de marche est un nombre entier impair de
demi-longueur d\'onde, on dit alors que l\'interférence est destructive.

## Annexe : la cohérence

Les interférences désignent les phénomènes qui se manifestent lors de la
superposition de deux ou plusieurs ondes différentes. Elles sont
observables lorsque les ondes superposées sont
**cohérentes** `.

S'il s'agit de lumière, les ondes émises par la matière possèdent une
nature électromagnétique. Plus précisément, un atome constituant de la
matière lorsqu'il se trouve dans un état excité [^3], peut revenir dans
son état fondamental (état de plus basse énergie) en émettant un photon
dont l'énergie est égale rigoureusement à la différence d'énergie entre
l'état excité et l'état fondamental de l'atome. Il s'agit de l'émission
spontanée `. Cette dernière
possède un caractère temporel aléatoire. Dans un milieu où règne une
grande agitation atomique (soleil, filament d'une ampoule), un atome
réalise ces transitions près de 100 millions de fois par seconde.

Les photons émis par les atomes d'une source lumineuse ordinaire
correspondent à des radiations d'une durée très courte (typiquement
$\tau = 10^{- 10}$ s dans le cas de la lumière naturelle
$\tau = 10^{- 10}$ s) que l'on appelle train d'onde (signal sinusoïdale
d'extension finie dans le temps) {index}`train d’onde` contenant $(\tau \times c)/\lambda$ oscillations.
La longueur spatiale du train d'onde est liée à la durée mise par
l'atome pour passer d'un état excité à un état désexcité. Chaque
émission d'un seul atome est constituée d'un train d'onde quasi
monochromatique polarisé rectilignement possédant une amplitude et une
phase initiale donnée.


```{figure} media/image8.png
:name: fig-trainsDOnde
:alt: Trains d'onde
:width: 60%
Trains d'onde.
```

Dans le cas de la lumière naturelle, les différents atomes constituant
la source émettent une succession ininterrompue de trains d'onde de
durée caractéristique $\tau_{c}$ appelée temps de cohérence temporelle
qui est grand devant la période $\tau_{c} > > T$ (*T* de l'ordre de
quelques femto seconde dans le visible). Ces trains d'onde ne possèdent
pas entre eux de relation de phase, ni d'amplitude ni de direction de
polarisation (variations aléatoires). La direction de polarisation,
l'amplitude et la phase sont des <u>grandeurs qui varient de manière
aléatoire d'un train d'onde à un autre</u>.

Il existe des sources lumineuses à spectres de raies et des sources à
spectre continu. Les premières correspondent à des lampes à décharges.
Une ampoule ou tube contient une vapeur d'un corps pur métallique
(Mercure, sodium). L'application d'une différence de potentiel entre la
cathode et l'anode du tube produit l'ionisation d'atome métallique. Les
électrons libérés sont attirés vers l'électrode positive, l'anode. Ce
flux d'électron induit par collision électron/atome soit une ionisation
amplifiant le flux d'électrons soit une excitation de l'atome métallique
qui peut alors émettre un photon de manière spontanée. Les raies
observées sont caractéristiques du métal vaporisé.

Le soleil ou une ampoule à incandescence (filament de tungstène chauffé
à très haute température) sont des sources à spectre continu.

Ceci nous amène à préciser les conditions d'interférences. Supposons que
l'on superpose deux vibrations scalaires au point $M$ :

$$\left\{ \begin{matrix}
a_{1}(M,t) = A_{1}\cos\left( \omega_{1}t + \varphi_{1} \right) \\
a_{2}(M,t) = A_{2}\cos\left( \omega_{2}t + \varphi_{2} \right)
\end{matrix} \right.$$

La vibration résultante en $M$ à l'instant $t$ est
$a(M,t) = a_{1}(M,t) + a_{2}(M,t)$.

Les deux vibrations <u>n'interféreront pas si</u> :

1.  les deux sources ne sont pas synchrones :
    $\omega_{1} \neq \omega_{2}$ ;

2.  $\omega_{1} = \omega_{2}$ mais les vibrations sont issues de deux
    sources de <u>lumières indépendantes</u> du fait des phases
    aléatoires $\varphi_{1}(M)$ et $\varphi_{2}(M)$ ; même à supposer
    que les amplitudes soit les même $A_{1} = A_{2} = A_{0}$et en
    appliquant le principe de superposition, on montre que le calcul de
    l'intensité en moyennant sur une période vaut :

    $$I(M) = 2\left\langle \left( a_{1}(M,t) + a_{2}(M,t) \right)^{2} \right\rangle = 2{A_{0}}^{2}\left( {1 + cos}\left( \varphi_{1} - \varphi_{2} \right) \right)$$

    La valeur $\left( \varphi_{1} - \varphi_{2} \right)$ variant
    aléatoirement au cours du temps, un calcul de valeur moyenne sur une
    durée grande devant la période (temps de réponse du détecteur)
    conduirait à une somme de termes
    $\cos\left( \varphi_{1} - \varphi_{2} \right)$ nulle en valeur
    moyenne.

    Il est à noter que le calcul à partir de la formulation complexe de
    l'amplitude reste valide lorsque l'amplitude résulte de la
    superposition de deux vibrations. Ainsi, le calcul :

$$I(M) = \widetilde{a}(M,t){\widetilde{a}}^{*}(M,t)$$

avec
$\widetilde{a}(M,t) = {\widetilde{a}}_{1}(M,t) + {\widetilde{a}}_{2}(M,t)$
et ${\widetilde{a}}_{j}(M,t) = A_{o}e^{j\omega t}e^{j\varphi_{j}}$
conduira à un résultat identique.

On a donc en définitive :

$I(M) = {{2A}_{0}}^{2}$

soit <u>la somme des intensités produites par chaque source</u>.

3.  les vibrations provenant d'une même source de lumière sont issues de
    deux trains d'onde différents (phases aléatoires) pour les mêmes
    raisons que ci-haut.

L'interférence est donc plus facilement mise en évidence si une seule
source de lumière est utilisée. L'interférence d'un faisceau de lumière
avec une partie retardée de lui-même (interféromètre de Michelson) est
observable lorsque le retard est plus faible que le temps de cohérence
où lorsque la différence de longueur entre les deux parcours empruntés
par faisceaux est plus faible que la longueur de cohérence. On parle
alors de cohérence temporelle.

Lorsque l'on fait interférer un champ lumineux avec une version déplacée
spatialement de lui-même, la superposition doit s'appliquer à des
vibrations (du champ) cohérentes spatialement (fentes d'Young) pour
donner une figure d'interférence.

<u>Cette cohérence spatiale implique qu'en deux points de la section du
faisceau la phase est la même s'ils sont situés à égale distance de la
source</u>. Bien évidemment une source de lumière
étendue spatialement ne présente pas de cohérence spatiale car les ondes
émises par deux points éloignés de la source ne présentent pas le même
vecteur d'onde.

Il existe une aire dite de cohérence propre à chaque source lumineuse
qui garantit que pour une séparation spatiale contenue dans l'aire de
cohérence, l'interférence est observable. Pour la lumière du soleil
cette aire est l'ordre de $4 10^{-2} \text{mm}^2$ raison pour laquelle les
interférences lumineuses ne sont pas observées dans la vie courante avec
la lumière du soleil.

Un laser est une source de lumière qui offre une cohérence spatiale et
temporelle.

Pour un laser, chaque train d'onde présente une cohérence temporelle
autorisant la manifestation de phénomènes d'interférence.

La lumière naturelle émise par le soleil ou par une source de lumière
blanche possède un spectre continu et est spatialement incohérente en
l'état. C'est la raison pour laquelle il est nécessaire de faire passer
la lumière du soleil dans un collimateur afin de réduire l'étendue
spatiale de la source (assimilée à l'aire du trou) pour garantir une
cohérence spatiale indispensable à l'observation d'interférence. La
lumière possédant un spectre continu les figures d'interférence propres
à chaque fréquence se superposeront comme on le verra dans le chapitre
suivant.

## Annexe : le principe de Huyguens-Fresnel 

La propagation d\'une onde en optique peut être décrite par le principe
de Huygens- Fresnel. Ce dernier est un principe de construction des
fronts d'onde lors de la propagation des ondes : chaque point de
l'espace et donc d'une surface d\'onde au temps peut être considéré
comme une source ponctuelle.


```{figure} media/image9.png
:name: fig-principeHyughens
:alt: Principe de Huyghens-Fresnel dans un milieu homogène et un milieu inhomogène
:width: 40%
Principe de Huyghens-Fresnel dans un milieu homogène et un milieu inhomogène
```

Un point recevant une onde réémet une onde sphérique de même fréquence,
même amplitude et même phase.

Donc toutes les sources d'une surface d\'{index}`onde plane` ∑ sont synchrones et
elles produisent des ondelettes sphériques élémentaires en phase avec
l\'onde incidente.

Supposons qu'à $t = 0$, le maximum de l'onde passe par le plan ∑ :

- chaque point de ∑ émet une onde sphérique. Après une durée $t$ , un
  point situé à une

- distance $ct$ ne recevra qu'une seule onde sphérique, celle émise par
  le point de ∑ le

- plus proche à $t = 0$. Chaque point situé sur ce plan ∑\' parallèle
  aura donc une même

- amplitude.

- Un point situé au-delà de ∑\' possède une amplitude nulle (l'onde ne
  l'a pas atteint).

- Un point situé avant ∑\' reçoit des ondes produites par de nombreux
  points de ∑ mais

- toutes ces ondes interfèrent de manière destructive car elles
  possèdent un déphasage

- différent.

Le plan ∑\' correspond donc à la surface d\'onde ∑ propagée à une vitesse
$c$ durant un intervalle de temps $t$.

 [^1]: L\'intensité instantanée électromagnétique est à distinguer de
    l\'intensité lumineuse qui est définit à partir de la luminance
    cette dernière étant la puissance de la lumière passant par unité de
    surface dans c

 [^2]: Les niveaux d'énergies d'un atome sont quantifiés comme on
    s'attachera à le montrer par la suite.

 [^3]: Les niveaux d'énergies d'un atome sont quantifiés comme on
    s'attachera à le montrer par la suite.


