---
title: "Opérateur d'évolution et équation de Schrödinger"
description: "Évolution temporelle dans l'espace des états."
authors:
  - name: Gilles Nguyen Vien
    affiliation: Département de Physique, Université de Bretagne Occidentale
license:
  id: "CC-BY-NC-ND-4.0"

date: 2026-01-19
---

#  Opérateur d'évolution et équation de Schrödinger

L'opérateur d'évolution $\widehat{U}\left( t_{2},t_{1} \right)$ associe
au ket
$\left. \left| \Psi\left( t_{1} \right) \right. \right\rangle$
représentant l'état d'un système au temps $t_{1}$ un autre ket, noté
$\left. \left| \Psi\left( t_{2} \right) \right. \right\rangle$,
représentant l'état du même système au temps $t_{2}$. On peut donc
écrire :

$$\left. \left| \Psi\left( t_{2} \right) \right. \right\rangle = \widehat{U}\left. \left( t_{2},t_{1} \right)\left| \Psi\left( t_{1} \right) \right. \right\rangle$$

Dans l'espace dual s'écrit :

$$\left\langle \left. \Psi\left( t_{2} \right) \right| \right. = \left\langle \left. \Psi\left( t_{1} \right) \right| \right.{\widehat{U}}^{\dagger}\left( t_{2},t_{1} \right)$$

Pour que la norme du vecteur d'état se conserve au cours du temps il
faut que l'opérateur d'évolution soit unitaire. En effet, on a :

$$\left\langle \Psi\left( t_{2} \right) \middle| \Psi\left( t_{2} \right) \right\rangle = \left\langle \left. \Psi\left( t_{1} \right) \right| \right.{\widehat{U}}^{\dagger}\left( t_{2},t_{1} \right)\widehat{U}\left. \left( t_{2},t_{1} \right)\left| \Psi\left( t_{1} \right) \right. \right\rangle$$

Si $\widehat{U}$ est unitaire on a bien :

$$\left\langle \Psi\left( t_{2} \right) \middle| \Psi\left( t_{2} \right) \right\rangle = \left\langle \Psi\left( t_{1} \right) \middle| \Psi\left( t_{1} \right) \right\rangle$$

Il est évident que $\widehat{U}(t,t)$ est l'opérateur identité. En
conséquence $\widehat{U}(t + dt,t)$ pour un $dt$ infinitésimal est un
opérateur peu différent de l'identité qu'on peut écrire sous la forme :

$$\widehat{U}(t + dt,t) = \widehat{1} + \widehat{K}(t)dt$$

L'unitarité de l'opérateur d'évolution implique la condition :

$$\widehat{1} = \left( \widehat{1} + \widehat{K}dt \right)\left( \widehat{1} + {\widehat{K}}^{\dagger}dt \right) = \widehat{1} + \left( \widehat{K} + {\widehat{K}}^{\dagger} \right)dt + O(dt)$$

Le terme de second ordre étant négligeable et $\widehat{U}$ étant
unitaire, cela conduit à :

$$\left( \widehat{K} + {\widehat{K}}^{\dagger} \right) = \widehat{0}$$

L'opérateur $\widehat{K}$ est donc anti-hermitique et homogène à
l'inverse d'un temps. Il est plus commode de faire intervenir un
opérateur hermitique $\widehat{H}$ car il possède des propriétés plus
intéressantes.

Posons : $\widehat{K} = \widehat{H}/(i\hbar)$

L'adjoint est donné par :

$${\widehat{K}}^{\dagger} = \frac{{\widehat{H}}^{\dagger}}{( - i\hbar)} = \frac{\widehat{H}}{( - i\hbar)} = - \widehat{K}$$

L'opérateur $\widehat{H}$ est homogène à une énergie. On l'appelle
{index}`opérateur hamiltonien`.

Nous allons maintenant obtenir l'équation différentielle vérifiée par le
vecteur d'état. L'application de l'opérateur d'évolution au vecteur
d'état donne la relation :

$$\widehat{U}(t + dt,t)\left. \left| \Psi(t) \right. \right\rangle = \left. \left| \Psi(t + dt) \right. \right\rangle$$

soit :

$$\left( \widehat{1} + \frac{\widehat{H}}{i\hbar}dt \right)\left. \left| \Psi(t) \right. \right\rangle = \left. \left| \Psi(t + dt) \right. \right\rangle$$

$$\left. \widehat{H}dt\left| \Psi(t) \right. \right\rangle = i\hbar\left\lbrack \left. \left| \Psi(t + dt) \right. \right\rangle - \left. \left| \Psi(t) \right. \right\rangle \right\rbrack$$

et finalement l'équation différentielle :

$$\left. \widehat{H}\left| \Psi(t) \right. \right\rangle = i\hbar\frac{d}{dt}\left. \left| \Psi(t) \right. \right\rangle$$

C'est l'équation de Schrödinger (dépendante du temps). Elle est écrite
ici sous une forme abstraite mais très générale.

On postule donc :


:::{tip} Postulat 6
<u>L\'évolution temporelle de</u>
 $\left| \Psi(t) \right\rangle$ décrivant l\'état du système au temps t
 est régie par :

 $$\left. \widehat{H}\left| \Psi(t) \right. \right\rangle = i\hbar\frac{d}{dt}\left. \left| \Psi(t) \right. \right\rangle$$

 où $\widehat{H}(t)$ est l\'observable associée à l\'énergie totale du
 système.
 :::

## Equation de Schrödinger dans une base donnée

On choisit des états de base dont le choix arbitraire nous permet
d\'appréhender le comportement du système.

Supposons que l'ensemble des vecteurs $\left\{ \left. \left| u_{k}  \right.\right\rangle \right\}$ forme
une base orthonormée de l'espace des états. En projetant l'équation de
Schrödinger sur un vecteur de base donné il vient :

$$\left. \left\langle \left. u_{k} \right| \right.\widehat{H}\left| \Psi(t) \right. \right\rangle = i\hbar\frac{d}{dt}\left\langle u_{k} \middle| \Psi(t) \right\rangle$$

En utilisant la relation de fermeture :

$$\sum_{l = 1}^{N}\left. \left\langle \left. u_{k} \right| \right.\widehat{H}\left| u_{l} \right. \right\rangle\left\langle u_{l} \middle| \Psi(t) \right\rangle = i\hbar\frac{d}{dt}\left\langle u_{k} \middle| \Psi(t) \right\rangle$$

soit :

$$\sum_{l = 1}^{N}{\widehat{H}}_{kl}c_{l}(t) = i\hbar\frac{d}{dt}c_{k}(t)$$

Les amplitudes d'état vérifient donc un système d'équations
différentielles couplées du premier ordre par rapport à $t$. La donnée
des amplitudes à $t = 0$ permet donc de les déterminer à tout instant
ultérieur. Ainsi lorsque l'état est connu à un instant donné l'équation
de Schrödinger permet de le connaître à tout instant ultérieur.

## Etats stationnaires

Soit $\left\{ \left. \left| \Phi_{k} \right. \right\rangle \right\}$
une base orthonormée de kets propres du l'hamiltonien. Nous supposerons
que toutes les valeurs propres de $\widehat{H}$ sont non dégénérées. On
a donc :

$\widehat{H}\left. \left| \Phi_{k} \right. \right\rangle = E_{k}\left. \left| \Phi_{k} \right. \right\rangle$
$E_{k}$ et $\left. \left| \Phi_{k} \right. \right\rangle$ ne
dépendent pas du temps.

$\widehat{H}$ étant une observable et ses valeurs propres étant non
dégénérées, on développe
$\left. \left| \Psi(t) \right. \right\rangle$ sur la base des
vecteurs propres de $\widehat{H}$ :

$$\left. \left| \Psi(t) \right. \right\rangle = \sum_{k}^{}{c_{k}(t)}\left. \left| \Phi_{k} \right. \right\rangle$$

Toute la dépendance temporelle de
$\left. \left| \Psi(t) \right. \right\rangle$ est contenue dans les
amplitudes d\'états $c_{k}(t)$. L\'équation de Schrödinger donne :

$$\left. \left\langle \left. \Phi_{k} \right| \right.\widehat{H}\left| \Psi(t) \right. \right\rangle = i\hbar\frac{d}{dt}\left\langle \Phi_{k} \middle| \Psi(t) \right\rangle$$

$\widehat{H}$ étant hermitique :

$$\left\langle \left. \Phi_{k} \right| \right.\widehat{H} = E_{k}\left\langle \left. \Phi_{k} \right| \right.$$

Ainsi on a :

$$i\hbar\frac{d}{dt}c_{k}(t) = {E_{k}c}_{k}(t)$$

Le Hamiltonien est bien diagonal dans la base de ses vecteurs propres
(valeurs propres non dégénérées).

Dans le cas d'un système à deux états de base et en représentation
matricielle dans la base des états solutions de $\widehat{H}$ (états
stationnaires) :

$\begin{pmatrix}
E_{1} & 0 \\
0 & E_{2}
\end{pmatrix}\begin{pmatrix}
c_{1} \\
c_{2}
\end{pmatrix} = i\hbar\frac{d}{dt}\begin{pmatrix}
c_{1} \\
c_{2}
\end{pmatrix}$ avec
$E_{i} = \left. \left\langle \left. \Phi_{i} \right| \right.\widehat{H}\left| \Phi_{i} \right. \right\rangle$

Le Hamiltonien joue cependant un rôle privilégié car c'est le générateur
de l'évolution temporelle. Lorsqu'il est diagonal les équations
d'évolution des amplitudes sont découplées. Dans le cas particulier d'un
système à deux états de base l'équation de Schrödinger s'écrit :

On a donc deux équations différentielles indépendantes :

$${E_{1}c}_{1}(t) = i\hbar\frac{d}{dt}c_{1}(t)$$

$${E_{2}c}_{2}(t) = i\hbar\frac{d}{dt}c_{2}(t)$$

Elles s'intègrent facilement et les solutions sont données par :

$$c_{1}(t) = c_{1}(0)e^{- iE_{1}t/\hbar}$$

$$c_{2}(t) = c_{2}(0)e^{- iE_{2}t/\hbar}$$

Les probabilités pour trouver le système dans les deux états sont
données respectivement par :

$$P_{1} = {c_{1}(t)}^{*}c_{1}(t) = {c_{1}(0)}^{*}c_{1}(0)$$

$$P_{2} = {c_{2}(t)}^{*}c_{2}(t) = {c_{2}(0)}^{*}c_{2}(0)$$

Elles sont indépendantes du temps ce qui justifie l'appellation **d'{index}`états stationnaires`** pour ces états
qui diagonalisent l'opérateur Hamiltonien. En effet, si à $t = 0$ le
système se trouve dans l'état
$\left. \left| \Phi_{1} \right. \right\rangle$ il y reste
indéfiniment.

Lorsqu'un système est dans un état stationnaire, c'est-à-dire un état
propre de son opérateur Hamiltonien, une mesure de son énergie donne
certainement la valeur propre correspondant à ce ket propre. L'énergie
du système est donc bien définie. C'est un cas limite de la relation
d'indétermination temps-énergie : $\Delta E$ tend vers zéro et la durée
tend vers l'infini.

Ainsi dans la base des états propres de $\widehat{H}$ les équations
d'évolution des amplitudes sont découplées et celles-ci ne varient que
par un facteur de phase dans le temps. Le problème à résoudre dans le
cas général est donc la recherche des états propres de $\widehat{H}$.

## Recherche systématique des états stationnaires

Supposons que les N vecteurs
$\left\{ \left. \left| u_{k} \right. \right\rangle,k = 1\;\text{à}\;N \right\}$
forment une base de l'espace des états d'un système. Les états
stationnaires sont notés
$\left. \left| \Phi_{k} \right. \right\rangle$.

Tout état du système peut être développé sur la base choisie :

$$\left. \left| \Psi(t) \right. \right\rangle = \sum_{k}^{}{b_{k}(t)}\left. \left| u_{k} \right. \right\rangle$$

Si le système est initialement dans un état stationnaire particulier,
$\left. \left| \Phi_{1} \right. \right\rangle$ par exemple, on a :

$\left. \left| \Psi(0) \right. \right\rangle = \left. \left| \Phi_{1} \right. \right\rangle$

et

${\left. \left| \Psi(t) \right. \right\rangle = e}^{- iE_{1}t/\hbar}\left. \left| \Phi_{1} \right. \right\rangle$

soit :

$${\left. \left| \Psi(t) \right. \right\rangle = e}^{- iE_{1}t/\hbar}\left. \left| \Psi(0) \right. \right\rangle$$

Ainsi, l'évolution temporelle d'un état stationnaire se traduit
simplement par la multiplication du vecteur d'état par un facteur de
phase.

**<u>Lorsqu'un état stationnaire est développé sur une base donnée il faut
donc que toutes les amplitudes d'état varient de la même manière dans le
temps</u>**. La recherche d'un état stationnaire
$\left. \left| \Phi_{k} \right. \right\rangle$ d'énergie $E_{k}$
équivaut donc à chercher une solution de l'équation de Schrödinger sous
la forme :

$$c_{l}(t) = c_{l}(0)e^{- iE_{k}t/\hbar}l = 1,2\;\text{à}\;N$$

où $E_{k}$ est l'énergie de l'état stationnaire recherché
$\left. \left| \Phi_{k} \right. \right\rangle$.

On a alors :

$$i\hbar\frac{d}{dt}c_{l}(t) = {E_{k}c}_{l}(t)$$

et l'équation de Schrödinger s'écrit :

$$\sum_{m = 1}^{N}{\widehat{H}}_{lm}c_{m}(t) = E_{k}c_{l}(t)$$

ou :

$$\sum_{m = 1}^{N}{\widehat{H}}_{lm}c_{m}(0) = E_{k}c_{l}(0)$$

Les énergies possibles sont donc les valeurs propres de l'opérateur
Hamiltonien et les vecteurs propres ont comme composantes les amplitudes
donnant le développement de l'état stationnaire sur la base des
$\left. \left| u_{l} \right. \right\rangle$. L'équation précédente
est appelée équation de Schrödinger indépendante du temps ou {index}`équation aux valeurs propres`.

Dans le cas particulier d'un système à deux états de base. L'équation de
Schrödinger indépendante du temps s'écrit :

$$\begin{pmatrix}
H_{11} & H_{12} \\
H_{21} & H_{22}
\end{pmatrix}\begin{pmatrix}
c_{1} \\
c_{2}
\end{pmatrix} = E\begin{pmatrix}
c_{1} \\
c_{2}
\end{pmatrix}$$

soit :

$$\begin{pmatrix}
H_{11} - E & H_{12} \\
H_{21} & H_{22} - E
\end{pmatrix}\begin{pmatrix}
c_{1} \\
c_{2}
\end{pmatrix} = \begin{pmatrix}
0 \\
0
\end{pmatrix}$$

Ce système d'équations admet des solutions non triviales à la condition
que le déterminant de la matrice des coefficients s'annule. Il faut donc
avoir :

$$\left| \begin{matrix}
H_{11} - E & H_{12} \\
H_{21} & H_{22} - E
\end{matrix} \right| = 0$$

Les valeurs possibles de $E$ sont solutions de l'équation quadratique :

$$E^{2} - \left( H_{11} + H_{22} \right)E + H_{11}H_{22} - H_{12}H_{21} = 0$$

Le discriminant est donné par :

$\Delta = \left( H_{11} + H_{22} \right)^{2} - 4\; H_{11}H_{22} + 4\; H_{12}H_{21}$
avec $\left( \; H_{12} \right)^{*} = H_{21}$

soit :

$\Delta = \left( H_{11} - H_{22} \right)^{2} + 4\;\left| H_{12} \right|^{2}$
soit $\Delta > 0$

On a donc :

$$E = \frac{H_{11} + H_{22}}{2} \pm \frac{1}{2}\sqrt{\left( H_{11} - H_{22} \right)^{2} + 4\; H_{12}H_{21}}$$

Remarquons enfin que la somme des énergies des états stationnaires est
égale à la trace de H et que leur produit est égal à son déterminant.

```{important}
 Connaissant l'état $\left. \left| \Psi(0) \right. \right\rangle$
 décrivant l\'état du système à l'instant $t = 0$. Pour connaître
 l'état $\left. \left| \Psi(t) \right. \right\rangle$ à l'instant
 $t$, on procède systématiquement de la manière suivante :

 1°) On développe $\left| \Psi(0) \right\rangle$sur la base des états
 propre de $\widehat{H}$ :

 $\left. \left| \Psi(0) \right. \right\rangle = \sum_{l}^{}{c_{l}(0)}\left. \left| \Phi_{l} \right. \right\rangle$
 avec
 $c_{l}(0) = \left\langle \Phi_{l} \middle| \Psi(t0) \right\rangle$ et
 $\widehat{H}\left. \left| \Phi_{l} \right. \right\rangle\left.  = E_{l}\left| \Phi_{l} \right. \right\rangle$

 2°) On calcule alors
 $\left. \left| \Psi(t) \right. \right\rangle$pour tout $t$ en
 multipliant chaque coefficient $c_{l}(0)$ par $e^{- iE_{l}t/\hbar}$
 :
 $\left. \left| \Psi(t) \right. \right\rangle = \sum_{l}^{}{c_{l}(0)}e^{- iE_{l}t/\hbar}\left. \left| \Phi_{l} \right. \right\rangle$
```

##  Constantes du mouvement

La valeur moyenne d'une grandeur physique est donnée par :

$$\left\langle \widehat{A} \right\rangle_{\Psi} = \left\langle \left. \Psi(t) \right| \right.\widehat{A}\left. \left| \Psi(t) \right. \right\rangle$$

Sa dérivée par rapport au temps s'écrit :

$$\frac{d}{dt}\left\langle \widehat{A} \right\rangle_{\Psi} = \left( \frac{d}{dt}\left\langle \Psi(t) \right| \right)\widehat{A}\left| \Psi(t) \right\rangle + \left\langle \Psi(t) \right|\frac{\partial\widehat{A}}{\partial t}\left| \Psi(t) \right\rangle + \left\langle \Psi(t) \right|\widehat{A}\left( \frac{d}{dt}\left| \Psi(t) \right\rangle \right)$$

La variation temporelle de cette grandeur peut être due à une dépendance
explicite sur le temps ainsi qu'à une évolution de l'état du système. A
l'aide de l'équation de Schrödinger :

$$\left. \widehat{H}\left| \Psi(t) \right. \right\rangle = i\hbar\frac{d}{dt}\left. \left| \Psi(t) \right. \right\rangle$$

et de l'équation correspondante dans l'espace dual :

$$\left\langle \left. \Psi(t) \right|\widehat{H} \right. = - i\hbar\frac{d}{dt}\left\langle \left. \Psi(t) \right| \right.$$

On obtient :

$$i\hbar\left\langle \widehat{A} \right\rangle_{\Psi} = - \left\langle \left. \Psi(t) \right| \right.\widehat{H}\widehat{A}\left. \left| \Psi(t) \right. \right\rangle + \left\langle \left. \Psi(t) \right| \right.\widehat{A}\left. \widehat{H}\left| \Psi(t) \right. \right\rangle + i\hbar\left\langle \left. \Psi(t) \right| \right.\frac{\partial\widehat{A}}{\partial t}\left. \left| \Psi(t) \right. \right\rangle$$

soit :

$$i\hbar\left\langle \widehat{A} \right\rangle_{\Psi} = \left\langle \left. \Psi(t) \right| \right.\left\lbrack \widehat{A,}\widehat{H} \right\rbrack\left. \left| \Psi(t) \right. \right\rangle + i\hbar\left\langle \left. \Psi(t) \right| \right.\frac{\partial\widehat{A}}{\partial t}\left. \left| \Psi(t) \right. \right\rangle$$

c'est-à-dire :

$$i\hbar\left\langle \widehat{A} \right\rangle_{\Psi} = \left\langle \left\lbrack \widehat{A,}\widehat{H} \right\rbrack \right\rangle_{\Psi} + i\hbar\left\langle \frac{\partial\widehat{A}}{\partial t} \right\rangle_{\Psi}$$

Si une observable ne dépend pas explicitement du temps et si elle
commute avec le Hamiltonien alors sa valeur moyenne ne dépend pas du
temps : on dit qu'elle représente une grandeur physique qui est une
**{index}`constante du mouvement`**.

## Exemple : système à deux états

### L\'ion moléculaire $H_{2}^{+}$

L'ion moléculaire $H_{2}^{+}$ est constitué de deux protons et un
électron. Si l'électron est au voisinage d'un des protons, le système
peut être considéré comme étant la superposition d'un atome d'hydrogène
interagissant avec un proton. Si la distance internucléaire tend vers
l'infini le proton et l'atome d'hydrogène sont supposés isolés. Le
système $H_{2}^{+}$ possède un grand nombre d'états de translation, de
rotation et de vibration. C'est la raison pour laquelle nous supposons
que la molécule est au repos c'est-à-dire que les énergies de
translation, rotation et de vibrations sont aussi basses que possibles
(cas limite : elles sont nulles). Dans ce cas, il reste encore deux
états possibles selon que l'électron se trouve au voisinage du premier
ou du second proton. Nous notons $\left| u_{1} \right\rangle$ et
$\left| u_{2} \right\rangle$ ces deux états et nous supposons

```{figure} media/image28.png
:name: fig-ionH2plus
:alt: Ion moléculaire $H_2^+$
:width: 100%
Ion moléculaire $H_2^+$
```

Examinons la forme de l'énergie potentielle électrostatique au voisinage
de la mi-distance entre les deux protons.

A mi-distance, la somme vectorielle de forces électrostatiques exercées
par les deux $H^{+}$ sur l'électron est nulle car les 2 forces se
compensent exactement donc $\frac{\partial V}{\partial x} = 0$.
L'énergie potentielle $V$ présente un extremum. Afin de déterminer s'il
s'agit d'un maximum ou d'un minimum, on écarte l'électron de cette
position. L'électron est alors attiré par le proton le plus proche. La
mi-distance est donc un maximum local car il ne correspond pas à une
position d'équilibre.

Si $\left| u_{1} \right\rangle$ et $\left| u_{2} \right\rangle$ étaient
stationnaires, c'est à dire si l'amplitude de probabilité que l'électron
passe d'un proton à un autre, il correspondrait à la même énergie compte
tenu de la symétrie du système. On a donc :

$$H_{11} = \left\langle u_{1} \right|H\left| u_{1} \right\rangle = H_{22} = \left\langle u_{2} \right|H\left| u_{2} \right\rangle = E_{0}$$

où $E_{0}$ correspond à l'énergie d'un atome d'hydrogène à laquelle
s'ajoute celle d'un proton.

Il existe une amplitude de probabilité de transition que l'électron
franchisse la barrière d'énergie potentielle par effet tunnel. Par
conséquent $\left| u_{1} \right\rangle$ et $\left| u_{2} \right\rangle$
ne sont pas stationnaires et le Hamiltonien n'est pas diagonal dans
cette base.

Nous posons $H_{12} = H_{21} = - a$. Ainsi :

$$H_{\left\{ \left| u_{1} \right\rangle,\left| u_{2} \right\rangle \right\}} = \begin{pmatrix}
E_{0} & - a \\
 - a & E_{0}
\end{pmatrix}$$
 
 avec $a > 0$

Recherchons les valeurs propres du Hamiltonien $H$ et les états propres
(états stationnaires) :

$$\det|H - \lambda I| = \left| \begin{matrix}
E_{0} - \lambda & - a \\
 - a & E_{0} - \lambda
\end{matrix} \right| = 0$$

$$\left( E_{0} - \lambda \right)^{2} - a^{2} = 0$$

$$\left( E_{0} - \lambda + a \right)\left( E_{0} - \lambda - a \right) = 0$$

Donc  $\lambda = E_{0} \pm a$sont les énergies des nouveaux états
stationnaires.

Recherchons le développement de l'état propre
$\left| \varphi_{a} \right\rangle$ (resp.
$\left| \varphi_{b} \right\rangle$) associé à la valeur propre
$E_{0} - a$ (resp. $E_{0} + a$) dans la base des états
$\left| u_{1} \right\rangle$ et $\left| u_{2} \right\rangle$.

En notation matricielle dans la base
$\left\{ \left| u_{1} \right\rangle,\left| u_{2} \right\rangle \right\}$,
on cherche donc les composantes $x$ et $y$ telles que :

$$\begin{pmatrix}
E_{0} & - a \\
 - a & E_{0}
\end{pmatrix}\begin{pmatrix}
x \\
y
\end{pmatrix} = \left( E_{0} - a \right)\begin{pmatrix}
x \\
y
\end{pmatrix}$$

avec $\left| \varphi_{a} \right\rangle = x\left| u_{1} \right\rangle + y\left| u_{2} \right\rangle$

On obtient $x = y$. En normalisant l'état
$\left| \varphi_{a} \right\rangle$, on trouve :

```{math}
:label: eq-47

\left| \varphi_{a} \right\rangle = \frac{1}{\sqrt{2}}\left( \left| u_{1} \right\rangle + \left| u_{2} \right\rangle \right)
```

De même, on obtient :

```{math}
:label: eq-48

\left| \varphi_{b} \right\rangle = \frac{1}{\sqrt{2}}\left( \left| u_{1} \right\rangle - \left| u_{2} \right\rangle \right)
```

L'état $\left| \varphi_{a} \right\rangle$ possède une énergie inférieure
à celle d'un proton séparé à l'infini d'un atome d'hydrogène ($E_{0}$)
et l'énergie de liaison est numériquement égale à l'élément non diagonal
du Hamiltonien $H$.

L'amplitude de localisation pour l'état
$\left. \left| \Phi_{a} \right. \right\rangle$ est
$\Phi_{a}\left( \overrightarrow{r} \right)$ avec :

$$\Phi_{a}\left( \overrightarrow{r} \right) = \frac{1}{\sqrt{2}}\left( \left\langle \overrightarrow{r} \middle| u_{1} \right\rangle + \left\langle \overrightarrow{r} \middle| u_{2} \right\rangle \right)$$

Or par hypothèse
$\left\langle \overrightarrow{r} \middle| u_{1} \right\rangle$ (resp.
$\left\langle \overrightarrow{r} \middle| u_{2} \right\rangle$) est une
fonction qui présente des valeurs importantes pour des valeurs de
$\overrightarrow{r}$ correspondant à une localisation de l'électron au
voisinage du premier (resp. second) proton.

Si l'état de l'électron est décrit par
$\left. \left| \varphi_{a} \right. \right\rangle$, l'électron
possède la même AP de se trouver au voisinage du premier ou du second
proton. Puisque l'électron possède une AP non nulle de passer d'un
proton à l'autre, l'électron possède un AP non nulle entre les protons :
son AP de localisation est donc symétrique par rapport au plan $x = 0$.
Comme elle est associée à l'état lié, on dit que l'AP de localisation
est liante. On parle d'orbitale liante.

Si l'électron est dans l'état
$\left. \left| \Phi_{b} \right. \right\rangle$ l'électron possède la
même AP de se trouver au voisinage du premier ou du second proton au
signe près. L'amplitude de localisation est donc une fonction
antisymétrique par rapport au plan $x = 0$. On dit que
$\Phi_{b}\left( \overrightarrow{r} \right)$ est une orbitale antiliante
car son énergie est supérieure à celle d'un proton et d'un atome
d'hydrogène isolé.

Cependant que l'électron soit dans l'état
$\left. \left| \Phi_{a} \right. \right\rangle$ ou
$\left. \left| \Phi_{b} \right. \right\rangle$, il possède la même
probabilité de se trouver au voisinage de l'un ou l'autre des protons.

On souhaite déterminer la variation temporelle
$\left| u_{1} \right\rangle$ des AP $c_{1}(t)$ et $c_{2}(t)$ de trouver
le système dans l'état $\left| u_{1} \right\rangle$ respectivement
$\left| u_{2} \right\rangle$ sachant qu'à $t = 0$ le système est dans
l'état $\left| \Psi(t = 0) \right\rangle = \left| u_{1} \right\rangle$.

On développe l'état $\left| \Psi(t) \right\rangle$ sur la base des états
stationnaires
$\left\{ \left| \varphi_{a} \right\rangle,\left| \varphi_{b} \right\rangle \right\}$
car on sait comment évoluent les amplitudes des états stationnaires.

On fait donc agir la relation de fermeture
$\left| \varphi_{a} \right\rangle\left\langle \left. \varphi_{a} \right| + \left| \varphi_{b} \right\rangle\left\langle \left. \varphi_{b} \right| = \right.\widehat{1} \right.$
sur l'état $\left| \Psi(t) \right\rangle$.

$$\left| \Psi(t) \right\rangle = \left| \varphi_{a} \right\rangle\left\langle \varphi_{a} \middle| \Psi(t) \right\rangle + \left| \varphi_{b} \right\rangle\left\langle \varphi_{b} \middle| \Psi(t) \right\rangle = c_{a}(t)\left| \varphi_{a} \right\rangle + c_{b}(t)\left| \varphi_{b} \right\rangle$$

On connaît la forme des amplitudes d'états $c_{a}(t)$ et $c_{b}(t)$ :

$$\left| \Psi(t) \right\rangle = c_{a}(0)e^{- iE_{a}t/\hbar}\left| \varphi_{a} \right\rangle + c_{b}(0)e^{- iE_{b}t/\hbar}\left| \varphi_{b} \right\rangle = c_{a}(0)e^{- i\left( E_{0} - a \right)t/\hbar}\left| \varphi_{a} \right\rangle + c_{b}(0)e^{- i\left( E_{0} + a \right)t/\hbar}\left| \varphi_{b} \right\rangle$$


```{math}
:label: eq-49

\left| \Psi(t) \right\rangle = e^{- iE_{0}t/\hbar}\left\lbrack c_{a}(0)e^{iat/\hbar}\left| \varphi_{a} \right\rangle + c_{b}(0)e^{- iat/\hbar}\left| \varphi_{b} \right\rangle \right\rbrack
```

Or à t=0 :

```{math}
:label: eq-50

\left| \Psi(t = 0) \right\rangle = \left| u_{1} \right\rangle
```

En identifiant {eq}`eq-49` et {eq}`eq-50` on
obtient :

$$\left| u_{1} \right\rangle = c_{a}(0)\left| \varphi_{a} \right\rangle + c_{b}(0)\left| \varphi_{b} \right\rangle$$

Développons l'état $\left| u_{1} \right\rangle$ sur les états
stationnaires afin de déterminer par identification les amplitudes
d'état $c_{a}(0)$ et $c_{b}(0)$. D'après {eq}`eq-47` et
{eq}`eq-48`, on a :

$\left| \varphi_{a} \right\rangle + \left| \varphi_{b} \right\rangle = \sqrt{2}\left| u_{1} \right\rangle$
soit
$\left| u_{1} \right\rangle = \frac{1}{\sqrt{2}}\left( \left| \varphi_{a} \right\rangle + \left| \varphi_{b} \right\rangle \right)$

Cela entraîne :

$$c_{a}(0) = c_{b}(0) = \frac{1}{\sqrt{2}}$$

soit  :

$$\left| \Psi(t) \right\rangle = \frac{e^{- iE_{0}t/\hbar}}{\sqrt{2}}\left\lbrack e^{iat/\hbar}\left| \varphi_{a} \right\rangle + e^{- iat/\hbar}\left| \varphi_{b} \right\rangle \right\rbrack$$






