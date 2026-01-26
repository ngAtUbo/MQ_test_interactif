---
title: "Etats quantiques"
description: "Notions d'espace des états et formalisme de Dirac."
authors:
  - name: Gilles Nguyen Vien
    affiliation: Département de Physique, Université de Bretagne Occidentale
license:
  id: "CC-BY-NC-ND-4.0"

date: 2026-01-19
---

# Etats quantiques


## Notion d\'états quantiques

Jusqu\'à présent les lois de la physique quantique ont été formulées à
l\'aide du concept d\'amplitude de probabilité de transition. Une
transition implique toujours une paire d\'états. Nous allons voir qu\'il
est possible de donner une signification physique à chaque état. Il en
résultera une grande simplification formelle.

Nous pouvons faire l\'analogie avec l\'espace ordinaire $\mathbb{R}^3$. La
position d\'un point dans l\'espace peut être donnée par un ensemble de
3 nombres qui sont les coordonnées par rapport à un système d\'axes
défini au préalable. Le changement de repère associera au point un
ensemble de nouvelles coordonnées. Cependant l\'utilisation de
la notion de vecteur géométrique et les règles de calcul vectoriel
permettent de s\'affranchir de la référence à un système d\'axe ce qui
simplifie considérablement les formulations et les raisonnements.

Nous présentons une démarche de ce type dans ce chapitre.

Nous postulons donc que l\'**{index}`état quantique`** d\'un système physique quelconque est
caractérisé par un vecteur d\'état appartenant à un espace vectoriel
linéaire complexe appelé **{index}`espace des états` du système**.

Cet espace est un sous-espace d'un espace de Hilbert  [^43]. <u>Cet état est
défini indépendamment de grandeurs physiques observables comme
pourraient l'être les positions et les impulsions mécaniques décrivant
l'état d'un système décrit selon la mécanique classique</u>.
Ceci étant l'état quantique d'un système à instant donné décrit les
mesures antérieures que l'on a opérées sur le système et les résultats
obtenus lors des mesures car la mesure d'un système perturbe le système
et donc modifie son état, l'état étant directement relié aux résultats
obtenus lors de la mesure.

<u>La notion d\'état d\'un système ne peut être disjointe de la façon de
le produire ou le préparer</u>. Par exemple, un photon sera dit
dans un état de polarisation circulaire gauche s\'il vient de traverser
un polariseur circulaire gauche.

## Espace des états

### Notation

Nous avons utilisé une notation selon laquelle l\'amplitude de
probabilité de transition d\'un état $\Psi$ à un état $\Phi$ est notée
$\left\langle \Phi \middle| \Psi \right\rangle$. Nous montrons que
chaque partie de cette formulation possède une signification.

Un vecteur quelconque de l\'espace des états noté $\varepsilon$ est
appelé **{index}`vecteur ket`** ou ket. On le
note $\left| \right\rangle$ en faisant figurer à l\'intérieur un
caractère distinctif permettant de différencier cet état des autres :

$\left| \Psi \right\rangle$ ket de l\'espace des états $\varepsilon$

Remarque

Insistons sur le fait qu\'il n\'existe dans $\left| \Psi \right\rangle$
aucune dépendance à une grandeur telle que $\overrightarrow{r}$ ou
$\overrightarrow{p}$ (ou leurs composantes) caractéristiques du système
physique dont l\'état quantique est représenté par
$\left| \Psi \right\rangle$.

### Produit scalaire hermitien

A tout couple de kets $\left| \Phi \right\rangle$ et
$\left| \Psi \right\rangle$ de $\varepsilon$ <u>pris dans cet
ordre</u>, on associe un nombre [complexe</u> qui est
leur produit scalaire :

$$\left( \left| \Phi \right\rangle,\left| \Psi \right\rangle \right)$$

Les propriétés de ce produit scalaire sont :

- linéarité par rapport au second ket :

$$\left( \left| \Phi \right\rangle,\lambda_{1}\left| \Psi_{1} \right\rangle + \lambda_{2}\left| \Psi_{2} \right\rangle \right) = \lambda_{1}\left( \left| \Phi \right\rangle,\left| \Psi_{1} \right\rangle \right) + \lambda_{2}\left( \left| \Phi \right\rangle,\left| \Psi_{2} \right\rangle \right)$$

- antilinéarité par rapport au premier ket :

$$\left( \lambda_{1}\left| \Phi_{1} \right\rangle + \lambda_{2}\left| \Phi_{2} \right\rangle \,,\, \left| \Psi \right\rangle \right) = (\lambda_{1})^{*} \left( \left| \Phi_{1} \right\rangle \,,\, \left| \Psi \right\rangle \right) + (\lambda_{2})^{*}\left( \left| \Phi_{2} \right\rangle \,,\, \left| \Psi \right\rangle \right)$$

- $\forall\left| \Psi \right\rangle \in \varepsilon$,$\left( \left| \Psi \right\rangle,\left| \Psi \right\rangle \right)$
  est réel et positif. En outre
  $\left( \left| \Psi \right\rangle,\left| \Psi \right\rangle \right) = 0$
  si et seulement si $\left| \Psi \right\rangle = 0$ (cas non physique)

- symétrie hermitienne

$$\left( \left| \Phi \right\rangle,\left| \Psi \right\rangle \right) = \left( \left| \Psi \right\rangle,\left| \Phi \right\rangle \right)^{*}$$

La norme d'un vecteur $\left| \Psi \right\rangle$ de $\varepsilon$ est
définie :

$$\left\| \left.  \left| \Psi \right.  \right\rangle \right\|^{2} = \left( \left.  \left| \Psi \right.  \right\rangle,\left.  \left| \Psi \right.  \right\rangle \right)$$

## Espace dual

### Définition

:::{prf:definition}
:label: my-fonctionnelle
Une fonctionnelle linéaire $\chi$ est opération linéaire qui à tout ket
$\left| \Psi \right\rangle$ associe un nombre complexe :

$\left| \Psi \right\rangle$ $\in$ $\varepsilon$
$\overset{\chi}{\rightarrow}$ nombre noté :
$\chi\left| \Psi \right\rangle$
:::

La linéarité est définie par :

$$\chi\left( \lambda_{1}\left| \Psi_{1} \right\rangle + \lambda_{2}\left| \Psi_{2} \right\rangle \right) = \lambda_{1}\chi\left( \left| \Psi_{1} \right\rangle \right) + \lambda_{2}\chi\left( \left| \Psi_{2} \right\rangle \right)$$

L\'ensemble des fonctionnelles linéaires définies sur
$\left| \Psi \right\rangle$ $\in$ $\varepsilon$ constitue un espace
vectoriel que l\'on appelle **{index}`espace dual`** de $\varepsilon$ noté $\varepsilon$ ^\*^.

### Notation bra

Un élément quelconque de $\varepsilon{*}$ est appelé **{index}`vecteur bra`** ou bra. On le note
$\left\langle \right|$ muni d\'un signe distinctif permettant de
distinguer une fonctionnelle d\'une autre. Par exemple
$\left\langle \chi \right|$ désigne la fonctionnelle linéaire $\chi$ et
on utilisera la notation $\left\langle \chi \middle| \Psi \right\rangle$
pour désigner le nombre obtenu en faisant agir
$\left\langle \chi \right|$ de $\varepsilon{*}$ sur
$\left| \Psi \right\rangle$ $\in$ $\varepsilon$ :

$$\left\langle \chi \middle| \Psi \right\rangle = \chi\left| \Psi \right\rangle$$

Remarque

En anglais le terme $\left\langle \middle| \right\rangle$ s\'appelle
bracket (crochet) d\'où l\'origine de l\'appellation bra pour la partie
gauche $\left\langle \right|$ et ket pour la partie droite
$\left| \right\rangle$.

### Correspondance entre kets et bras

L\'existence d\'un produit scalaire dans $\varepsilon$ nous permet de
montrer qu\'à tout ket $\left| \Phi \right\rangle$ $\in$ $\varepsilon$,
on peut associer un élément de $\varepsilon^{*}$ c\'est-à-dire un bra
noté $\left\langle \Phi \right|$.

En effet le ket $\left| \Phi \right\rangle$ nous permet de définir une
fonctionnelle linéaire :

Celle qui a tout ket $\left| \Psi \right\rangle$ $\in$ $\varepsilon$
fait correspondre le nombre complexe égal au produit scalaire
$\left( \left| \Phi \right\rangle,\left| \Psi \right\rangle \right)$ de
$\left| \Psi \right\rangle$ par $\left| \Phi \right\rangle$. Soit
$\left\langle \Phi \right|$ cette fonctionnelle linéaire.

On a donc :

$$\left( \left| \Phi \right\rangle,\left| \Psi \right\rangle \right) = \left\langle \Phi \middle| \Psi \right\rangle$$

Ainsi les propriétés du produit scalaire énoncées précédemment sont re
écrites :

- linéarité par rapport au second ket :

$$\left( \left| \left.  \Phi \right\rangle,\lambda_{1}\left.  \left| \Psi_{1} \right.  \right\rangle + \lambda_{2}\left.  \left| \Psi_{2} \right.  \right\rangle \right.  \right) = \lambda_{1}\left( \left| \left.  \Phi \right\rangle,\left.  \left| \Psi_{1} \right.  \right\rangle \right.  \right) + \lambda_{2}\left( \left| \left.  \Phi \right\rangle,\left.  \left| \Psi_{2} \right.  \right\rangle \right.  \right) = \lambda_{1}\left\langle \Phi \middle| \Psi_{1} \right\rangle + \lambda_{2}\left\langle \Phi \middle| \Psi_{2} \right\rangle$$

- anti-linéarité par rapport au premier ket :

$$\left( \lambda_{1}\left| \Phi_{1} \right\rangle + \lambda_{2}\left| \Phi_{2} \right\rangle,\left| \Psi \right\rangle \right) = {\lambda_{1}}^{*}\left( \left| \Phi_{1} \right\rangle,\left| \Psi \right\rangle \right) + {\lambda_{2}}^{*}\left( \left| \Phi_{2} \right\rangle,\left| \Psi \right\rangle \right) = {\lambda_{1}}^{*}\left\langle \Phi_{1} \middle| \Psi \right\rangle + {\lambda_{2}}^{*}\left\langle \Phi_{2} \middle| \Psi \right\rangle = \left( {\lambda_{1}}^{*}\left\langle \Phi_{1} \right| + {\lambda_{2}}^{*}\left\langle \Phi_{2} \right| \right)\left| \Psi \right\rangle$$

- symétrie hermitienne :

$$\left\langle \Phi \middle| \Psi \right\rangle = \left\langle \Psi \middle| \Phi \right\rangle^{*}$$

- $\left\langle \Psi \middle| \Psi \right\rangle$ estréel positif.

L'anti-linéarité du produit scalaire entraîne que le bra associé au ket :
$$\lambda_{1}\left| \Phi_{1} \right\rangle + \lambda_{2}\left| \Phi_{2} \right\rangle$$

est :

$${\lambda_{1}}^{*}\left\langle \Phi_{1} \right| + {\lambda_{2}}^{*}\left\langle \Phi_{2} \right|$$

puisque la relation donnée ci-dessus est vérifiée pour tout ket
$\left| \Psi \right\rangle$ $\in$ $\varepsilon$. La correspondance ket →
bra appelée **conjugaison hermitique** est anti-linéaire.

## Opérateurs linéaires

Un opérateur est un objet mathématique qui à tout vecteur d\'un espace
vectoriel $\varepsilon$ fait correspondre un autre vecteur de cet
espace. C\'est donc une application de $\varepsilon$ sur $\varepsilon$.

:::{attention}À connaître par coeur
:::{prf:definition}
:label: my-operateur
Par définition, à tout ket un opérateur fait correspondre un autre ket
et à tout bra il fait correspondre un autre bra :

$\widehat{A}\left| \left.  v \right\rangle \right.  = \left| \left.  w \right\rangle \right. $
où $\left| \left.  v \right\rangle \right. $ et
$\left| \left.  w \right\rangle \right. $ $\in$ $\varepsilon$
:::
:::

Remarque

La notation $\left| \widehat{A}\left.  v \right\rangle \right. $ (bien
que peu usitée) existe provenant de la notation mathématique du produit
scalaire de deux vecteurs $v$ et $w$ $\in$ $\varepsilon$ espace
vectoriel complexe : $\left( w \middle| A(v) \right)$. Elle est liée à
la notation habituelle :
$\left| \widehat{A}\left.  v \right\rangle \right.  = \widehat{A}\left| \left.  v \right\rangle \right. $

### Linéarité

Soit $\widehat{A}$ un opérateur tel que :

$\widehat{A}\left| u_{1} \right\rangle = \left| v_{1} \right\rangle$ et
$\widehat{A}\left| u_{2} \right\rangle = \left| v_{2} \right\rangle$.

On dit que $\widehat{A}$ est linéaire si :

$$\widehat{A}\left( \lambda_{1}\left| u_{1} \right\rangle + \lambda_{2}\left| u_{2} \right\rangle \right) = \lambda_{1}\widehat{A}\left| u_{1} \right\rangle + \lambda_{2}\widehat{A}\left| u_{2} \right\rangle = \lambda_{1}\left| v_{1} \right\rangle + \lambda_{2}\left| v_{2} \right\rangle$$

Le produit de deux opérateurs est l\'opérateur unique qui les remplace.

Ainsi $\widehat{C}$ est le produit des opérateurs $\widehat{A}$ et
$\widehat{B}$ pris dans cet ordre si pour tout
$\left| \left.  \varphi \right\rangle \right. $ $\in$ $\varepsilon$ :

$\widehat{A}\widehat{B} \left| \left.  \varphi \right\rangle \right.  = \widehat{C} \left| \left.  \varphi \right\rangle \right. $

### Adjoint d\'un opérateur

L\'adjoint d\'un opérateur $\widehat{A}$ est l\'opérateur noté
${\widehat{A}}^{\dagger}$ qui, dans l\'espace dual, établit les mêmes
correspondances que $\widehat{A}$ dans l\'espace des états.

Ainsi l\'expression
$\widehat{A}\left| u_{1} \right\rangle = \left| v_{1} \right\rangle$
implique
$\left\langle u_{1} \right|{\widehat{A}}^{\dagger} = \left\langle v_{1} \right|$.

<u>L\'opérateur se place à gauche du ket ou à droite du bra.</u>

Remarque

La notation $\left\langle \left.  \widehat{A}w \right| \right. $ (bien
que peu usitée) existe également. Mais on sort l\'opérateur du bra à
droite en considérant l\'adjoint de l\'opérateur :
$\left\langle \left.  \widehat{A}w \right| \right.  = \left\langle \left.  w \right| \right. {\widehat{A}}^{\dagger}$

Recherchons qu\'elle est l\'adjoint d\'un produit d\'opérateurs.

Posons :

$$\widehat{B}\widehat{A}\left| u \right\rangle = \widehat{B}\left| v \right\rangle = \left| w \right\rangle$$

soit :

$$\left| v \right\rangle = \widehat{A} \left| u \right\rangle$$

```{math}
:label: eq-38

\left| w \right\rangle = \widehat{B} \left| v \right\rangle
```


On dira que $\widehat{C} = \widehat{B}\widehat{A}$ si pour tout ket de
$\varepsilon$ :

$\widehat{C}\left| u \right\rangle = \left| w \right\rangle$.

L\'adjoint de $\widehat{C}$ est tel que :

$$\left\langle w \right| = \left\langle u \right|{\widehat{C}}^{\dagger}$$

Or on a d\'après {eq}`eq-38` :

$$\left\langle w \right| = \left\langle v \right|{\widehat{B}}^{\dagger}$$

ou encore :

$$\left\langle w \right| = \left\langle u \right|{\widehat{A}}^{\dagger}{\widehat{B}}^{\dagger}$$

soit :

$${\widehat{C}}^{\dagger} = (BA)^{\dagger} = {\widehat{A}}^{\dagger}{\widehat{B}}^{\dagger}$$

L\'adjoint d\'un produit d\'opérateurs est le produit des adjoints pris
dans l\'ordre inverse.

### Opérateur hermitique

:::{attention}À connaître par coeur
:::{prf:definition}
:label: my-hermitique
Par définition un opérateur est dit {index}`hermitique` (ou hermitien ou encore auto-adjoint) s\'il est égal
à son adjoint : $\widehat{A} = \widehat{A}^{\dagger}$
:::
:::

### Opérateur unitaire

Un opérateur est dit unitaire si :
$$\widehat{U}^{\dagger}= \widehat{U}^{\dagger}\widehat{U} = \widehat{1}$$

Dit autrement puisque l'inverse ${\widehat{A}}^{- 1}$ d'un opérateur
$\widehat{A}$ est tel que :

${\widehat{A} \widehat{A}}^{- 1} = {\widehat{A}}^{- 1}\widehat{A} = \widehat{1}$

Un opérateur est dit unitaire si son inverse est égal à son adjoint :

$${ \widehat{U}}^{\dagger} = {\widehat{U}}^{- 1}$$

Une transformation réalisée à l\'aide d\'un tel opérateur est dite
unitaire. [Elle possède la propriété remarquable de laisser invariant le
produit scalaire]. En effet, si on a :

$\left| X' \right\rangle = \widehat{U}\left| X \right\rangle$ et
$\left| Y' \right\rangle = \widehat{U}\left| Y \right\rangle$

alors :

$$\left\langle Y' \middle| X' \right\rangle = \left\langle Y \right|\widehat{U}{\widehat{U}}^{\dagger}\left| X \right\rangle = \left\langle Y \middle| X \right\rangle$$

En particulier, la norme d\'un vecteur ket (racine carrée du produit
scalaire du vecteur avec lui-même) est invariante lors d\'une
transformation unitaire.

### Transformation d\'un opérateur

Soit :

```{math}
:label: eq-39

\left| Y \right\rangle = \widehat{A}\left| X \right\rangle
```


Cherchons $\widehat{A}'$ tel que :

$$\left| Y' \right\rangle = \widehat{A}'\left| X' \right\rangle$$

D\'après l\'égalité {eq}`eq-39` on a :

$$\widehat{U}\left| Y \right\rangle = \widehat{U}\widehat{A}\left| X \right\rangle = \widehat{U}\widehat{A}{\widehat{U}}^{\dagger}\widehat{U}\left| X \right\rangle$$

soit :

$$\left| Y' \right\rangle = \widehat{U}\widehat{A}{\widehat{U}}^{\dagger}\left| X' \right\rangle$$

⇒ $\widehat{A}' = \widehat{U}\widehat{A}{\widehat{U}}^{\dagger}$

### Elément de matrice d\'un opérateur

$\left\langle Y \right|\widehat{A}\left| X \right\rangle$ est un nombre
appelé élément de matrice de l\'opérateur $\widehat{A}$.

Dans le cas général on a :

$$\left\langle Y \right|\widehat{A}\left| X \right\rangle = \left\langle Y \middle| X' \right\rangle = \left\langle X' \middle| Y \right\rangle^{*}$$

soit :

$$\left\langle Y \right|\widehat{A}\left| X \right\rangle =
(\left\langle X \right|\widehat{A}^{\dagger}\left| Y \right\rangle)^{*}$$

Si $\widehat{A}$ est hermitique on a :

$$\left\langle Y \right|\widehat{A}\left| X \right\rangle = \left( \left\langle X \right|\widehat{A}\left| Y \right\rangle \right)^{*}$$

Tout élément de matrice d\'un opérateur hermitique est le conjugué
complexe de son transposé. En particulier le nombre
$\left\langle X \right|\widehat{A}\left| X \right\rangle$ est réel si
$\widehat{A}$ est hermitique.

Nous verrons plus loin l\'importance des opérateurs hermitiques en
physique quantique.

## Vecteurs propres et valeurs propres

Soit $\widehat{A}$ un opérateur linéaire. Le ket
$\left| x \right\rangle$ est ket propre de $\widehat{A}$ si le vecteur
$\widehat{A}\left| x \right\rangle$ est proportionnel à
$\left| x \right\rangle$ c\'est-à-dire si :


```{math}
:label: eq-40

\widehat{A}\left| x \right\rangle = \lambda\left| x \right\rangle
```

$\lambda$ est la valeur propre de $\widehat{A}$ associée au vecteur
propre $\left| x \right\rangle$. Si à une valeur propre correspond deux
ou plusieurs vecteurs propres, on dit qu\'elle est dégénérée. Ces
vecteurs engendrent un sous-espace associé à la valeur propre.

```{important}
Dans la suite, par soucis de simplification, nous supposerons que les
valeurs propres sont non dégénérées</u>.
```

Écrivons la relation {eq}`eq-40` dans l\'espace dual :


```{math}
:label: eq-41

\left\langle x \right|{\widehat{A}}^{+} = \lambda^{*}\left\langle x \right|
```
Les relations {eq}`eq-40` et {eq}`eq-41` donnent :

$$\left\langle x \right|\widehat{A}\left| x \right\rangle = \lambda\left\langle x \middle| x \right\rangle$$

$$\left\langle x \right|{\widehat{A}}^{+}\left| x \right\rangle = \lambda^{*}\left\langle x \middle| x \right\rangle$$

Si $\widehat{A}$ est un opérateur hermitique
($\widehat{A} = {\widehat{A}}^{+}$), on a $\lambda = \lambda^{*}$. <u>Les
valeurs propres d\'un opérateur hermitique sont donc
réelles</u>.

Considérons deux kets propres $\left| x_{1} \right\rangle$ et
$\left| x_{2} \right\rangle$ du même opérateur hermitique :


```{math}
:label: eq-42

\widehat{A}\left| x_{1} \right\rangle = \lambda_{1}\left| x_{1} \right\rangle
```

(43) $\widehat{A}\left| x_{2} \right\rangle = \lambda_{2}\left| x_{2} \right\rangle$

Dans l\'espace dual :

$\widehat{A}$ étant un opérateur hermitique
($\widehat{A} = {\widehat{A}}^{+}$), sa valeur propre est réelle, on
peut donc écrire :


```{math}
:label: eq-44

\left\langle x_{2} \right|\widehat{A} = \lambda_{2}\left\langle x_{2} \right|
```
Des relations  {eq}`eq-42` et {eq}`eq-44`, on tire :

$$\left\langle x_{2} \right|\widehat{A}\left| x_{1} \right\rangle = \lambda_{1}\left\langle x_{2} \middle| x_{1} \right\rangle$$

$$\left\langle x_{2} \right|\widehat{A}\left| x_{1} \right\rangle = \lambda_{2}\left\langle x_{2} \middle| x_{1} \right\rangle$$

En soustrayant ces deux équations, on obtient :

$$0 = \left( \lambda_{1} - \lambda_{2} \right)\left\langle x_{2} \middle| x_{1} \right\rangle$$

Si $\lambda_{1} \neq \lambda_{2}$ cela implique
$\left\langle x_{2} \middle| x_{1} \right\rangle = 0$. <u>Ainsi les
vecteurs propres d\'un opérateur hermitique associés à des valeurs
propres différentes sont orthogonaux</u>.

Lors d\'un changement de base réalisé au moyen d\'une transformation
unitaire, l\'équation {eq}`eq-40` devient :

$$\widehat{U}\widehat{A}\left| x \right\rangle = \lambda\widehat{U}\left| x \right\rangle$$

soit :

$$\widehat{U}\widehat{A}{\widehat{U}}^{+}\widehat{U}\left| x \right\rangle = \lambda\widehat{U}\left| x \right\rangle$$

Or :

$\left| x' \right\rangle = \widehat{U}\left| x \right\rangle$ et
$\widehat{A}' = \widehat{U}\widehat{A}{\widehat{U}}^{+}$

Ainsi, l\'équation aux valeurs propres prend la forme :

$$\widehat{A}'\left| x' \right\rangle = \lambda\left| x' \right\rangle$$

En conséquence, <u>lors d\'une transformation unitaire, les opérateurs et
les vecteurs propres sont modifiés mais leurs valeurs propres sont
inchangées</u>.

Un changement de base en physique quantique est analogue à un changement
de repère en physique classique. Il est évident que toute grandeur
physique mesurable doit rester invariante lors d\'un changement de base.
Les produits scalaires (ou amplitude de probabilité de transition) et
les valeurs propres des opérateurs possèdent cette propriété
d\'invariance. Nous avons vu que les probabilités de transition sont des
carrés de modules des produits scalaires. Les valeurs propres
représentent les résultats possibles que l\'on peut obtenir lors de la
mesure d\'une grandeur physique.

## Bases de l\'espace des états

Supposons que l\'ensemble $\left\{ ket{u_{k}} \right\}$
forme une base de l\'espace des états d\'un système. Tout état
$\left| \Psi \right\rangle$ de ce système peut donc être développé sur
cette base, c\'est-à-dire qu\'on peut l\'écrire sous la forme :

```{math}
:label: eq-45

\left| \Psi \right\rangle = \sum_{k = 1}^{N}{C_{k}\left| u_{k} \right\rangle}
```

La donnée des coefficients du développement $c_{k}$ définit complètement
l\'état du système. La dimension de l\'espace $N$ est le nombre maximum
de vecteurs linéairement indépendants qu\'il peut contenir. La dimension
de l\'espace des états dépend du système étudié et elle peut aller de
deux à l\'infini. Le développement {eq}`eq-45` est une
 {index}`superposition linéaire d'états`.

Supposons que les produits scalaires des vecteurs de base vérifient la
condition.

$$\left\langle u_{k} \middle| u_{l} \right\rangle = \delta_{k,l}$$

où $\delta_{k,l}$ est le delta de Kronecker (sa valeur est 1 si les
indices sont égaux et 0 s\'ils sont différents).

La norme de chaque vecteur de base est donc 1 et ils sont tous
orthogonaux entre eux. On dit alors que la base est orthonormée. Dans la
suite nous supposerons toujours que la base utilisée est orthonormée.

On peut trouver les coefficients du développement en projetant
l\'équation {eq}`eq-45` sur un état de base particulier.

$$\left\langle u_{l} \middle| \Psi \right\rangle = \sum_{k = 1}^{N}{C_{k}\left\langle u_{l} \middle| u_{k} \right\rangle}$$

soit :

$$\left\langle u_{l} \middle| \Psi \right\rangle = \sum_{k = 1}^{N}{C_{k}\delta_{k,l}}$$

soit :

$$\left\langle u_{l} \middle| \Psi \right\rangle = C_{l}$$

Chaque coefficient du développement est donc [une amplitude de
probabilité de transition de l\'état initial à l\'un des états de la
base]. C\'est pourquoi ces coefficients sont appelés <u>{index}`amplitude d'états`</u>. La
probabilité pour trouver le système dans l'état
$\left| u_{l} \right\rangle$ est donc :

$${C_{l}}^{*}C_{l} = \left\langle \Psi \middle| u_{l} \right\rangle\left\langle u_{l} \middle| \Psi \right\rangle$$

Un projecteur $\widehat{P}$ est un opérateur hermitique vérifiant la
condition :

$$\widehat{P}\widehat{P} = {\widehat{P}}^{2} = \widehat{P}$$

Pour illustrer ce type d\'opérateur considérons le cas d\'un vecteur
$\overrightarrow{A}$ de l\'espace ordinaire ($\mathbb{R}^3$). Si
${\widehat{P}}_{x}$ ${\widehat{P}}_{y}$et ${\widehat{P}}_{xy}$ sont
respectivement les projecteurs sur l\'axe des $x$, sur l\'axe des $y$ et
dans le plan $x y$, on doit avoir :

$${\widehat{P}}_{x}\overrightarrow{A} = A_{x}\overrightarrow{i}$$

$${\widehat{P}}_{y}\overrightarrow{A} = A_{y}\overrightarrow{j}$$

$${\widehat{P}}_{xy}\overrightarrow{A} = A_{x}\overrightarrow{i} + A_{y}\overrightarrow{j}$$

Le simple produit scalaire par un vecteur de base ne peut pas
représenter un opérateur car à partir d\'un vecteur il donne un
scalaire. Il faut donc une paire de vecteurs pour représenter un
opérateur
(${{\widehat{P}}_{x} = \overrightarrow{i}\overrightarrow{i},\widehat{P}}_{y} = \overrightarrow{j}\overrightarrow{j}$).
Le second disparaît dans le produit scalaire et le premier permet de
donner un caractère vectoriel au résultat. Par exemple on a :

$$\overrightarrow{i}\overrightarrow{i}.\overrightarrow{A} = \overrightarrow{i}A_{x} = A_{x}\overrightarrow{i}$$

On vérifie facilement que chacun des opérateurs de projection satisfait
à la condition :

$$\widehat{P}\widehat{P} = {\widehat{P}}^{2} = \widehat{P}$$

L'opérateur
$\overrightarrow{i}\overrightarrow{i} + \overrightarrow{j}\overrightarrow{j} + \overrightarrow{k}\overrightarrow{k}$
appliqué à tout vecteur $\overrightarrow{A}$ donne le même vecteur comme
résultat. Il est donc équivalent à l\'opérateur identité :

$$\overrightarrow{i}\overrightarrow{i} + \overrightarrow{j}\overrightarrow{j} + \overrightarrow{k}\overrightarrow{k} = \widehat{1}$$

On dit alors que les vecteurs $\overrightarrow{i}$, $\overrightarrow{j}$
et $\overrightarrow{k}$ vérifient la **{index}`relation de fermeture`**. De
manière générale, chaque fois que des vecteurs forment une base
orthonormée ils vérifient la relation de fermeture et réciproquement.

Dans le cas de l\'espace des états d\'un système physique la projection
du vecteur d\'état $\left| \Psi \right\rangle$ sur un vecteur de base
$\left| u_{j} \right\rangle$ est :

$${\widehat{P}}_{j}\left| \Psi \right\rangle = c_{j}\left| u_{j} \right\rangle$$

avec $c_{j} = \left\langle u_{j} \middle| \Psi \right\rangle$.

On a donc :

${\widehat{P}}_{j}\left| \Psi \right\rangle = \left| u_{j} \right\rangle\left\langle u_{j} \middle| \Psi \right\rangle$
$\forall\;\left| \Psi \right\rangle$

soit :

$${\widehat{P}}_{j} = \left| u_{j} \right\rangle\left\langle u_{j} \right|$$

Une somme de tels projecteurs peut être considérée comme un projecteur
sur le sous-espace engendré par les vecteurs inclus dans la somme. Si
tous les vecteurs de la base sont inclus on obtient l\'opérateur
identité :


:::{attention}À connaître par coeur
$$\sum_{k = 1}^{N}{\left| u_{k} \right\rangle\left\langle u_{k} \right|} = 1$$

Ainsi les vecteurs d'une base orthonormée vérifient la relation de
fermeture.
:::

Réciproquement, tout ensemble de vecteurs orthonormés vérifiant la
relation de fermeture forment une base pour l\'espace des états

Considérons le produit scalaire du vecteur d\'état par lui-même dans le
cas où il serait normé à l'unité
($\left\| \left| \left.  \Psi \right\rangle \right.  \right\|^{2} = \left\langle \Psi \middle| \Psi \right\rangle = 1$).
On a alors :

$$\left\langle \Psi \middle| \Psi \right\rangle = 1$$

En appliquant la relation de fermeture on obtient :

$$\left\langle \Psi \right|1\left| \Psi \right\rangle = \sum_{k = 1}^{N}{\left\langle \Psi \middle| u_{k} \right\rangle\left\langle u_{k} \middle| \Psi \right\rangle}$$

Soit :

$$\left\langle \Psi \middle| \Psi \right\rangle = \sum_{k = 1}^{N}{c_{k}{c_{k}}^{*}}$$

Or le nombre réel $c_{k}^{*}c_{k}$ représente la probabilité de
transition du système de l\'état $\left| \Psi \right\rangle$ vers
l\'état $\left| u_{k} \right\rangle$. Il est donc nécessaire d\'utiliser
un vecteur d\'état de norme 1 pour que la condition de normalisation des
probabilités soit satisfaite.


:::{attention}À connaître par coeur
:::{prf:definition}
:label: my-obervable

On appelle **{index}`observable`** un opérateur hermitique dont les kets propres forment une base de
l\'espace des états. 
:::
:::

Ce type d\'opérateur joue un rôle capital en
théorie quantique.

## Représentation matricielle

En adoptant certaines conventions, tous les calculs de la théorie
quantique se ramènent aux opérations familières de l\'algèbre linéaire.

:::{attention}À connaître par coeur
Dans une base **<u>donnée</u>**
$\left\{ \left| u_{i} \right\rangle\; i = 1,...N \right\}$, on
représente un ket par la matrice colonne :
:::

```{math}
:label: eq-vecteur-coordonnees
\left| \Psi \right\rangle_{\left\{ \left| u_{i} \right\rangle \right\}}
=
\begin{pmatrix}
\left\langle u_{1} \middle| \Psi \right\rangle \\
\left\langle u_{2} \middle| \Psi \right\rangle \\
\vdots \\
\left\langle u_{N} \middle| \Psi \right\rangle
\end{pmatrix}
=
\begin{pmatrix}
c_{1} \\
c_{2} \\
\vdots \\
c_{N}
\end{pmatrix}
```

:::{attention}À connaître par coeur
Par application de la relation de fermeture, on représente le bra $\left\langle \Psi \right|$ sous la forme d'une matrice ligne :
:::

$$\left\langle \Psi \right|_{\left\{ \left\langle u_{i} \right| \right\}} = \begin{pmatrix}
{c_{1}}^{*} & {c_{2}}^{*} & ... & & {c_{N}}^{*}
\end{pmatrix}$$

En appliquant les règles du produit matriciel, on retrouve l'expression
du produit scalaire dans une base donnée.

Si $\widehat{A}$ est un opérateur
$\left\langle u_{j} \right|\widehat{A}\left| u_{k} \right\rangle$ est un
nombre qui dépend de deux indices. On dit que c'est un élément de
matrice :

$$\left\langle u_{j} \right|\widehat{A}\left| u_{k} \right\rangle = A_{j,k}$$

:::{attention}À connaître par coeur
La représentation matricielle de $\widehat{A}$ dans la base $\left\{ \left| u_{i} \right\rangle \right\}$ est :
:::

$${\widehat{A}}_{\left\{ \left| u_{i} \right\rangle \right\}} = \begin{pmatrix}
\left\langle u_{1} \right|\widehat{A}\left| u_{1} \right\rangle & ... & \left\langle u_{1} \right|\widehat{A}\left| u_{N} \right\rangle \\
... & & \\
\left\langle u_{N} \right|\widehat{A}\left| u_{1} \right\rangle & & \left\langle u_{N} \right|\widehat{A}\left| u_{N} \right\rangle
\end{pmatrix}$$

que l'on noteta :

$${\widehat{A}}_{\left\{ \left| u_{i} \right\rangle \right\}} = \begin{pmatrix}
A_{11} & ... & A_{1N} \\
... & & \\
A_{N1} & & A_{NN}
\end{pmatrix}$$


:::{admonition} Exercice
:class: dropdown
# Exercice — Représentation matricielle d’un opérateur dans une base de dimension 3

On considère un espace des états $\epsilon$ de dimension $3$, muni de la base orthonormée :

$$\mathcal{B} = \{\lvert e_1\rangle, \lvert e_2\rangle, \lvert e_3\rangle \}$$


Un opérateur linéaire $\hat{A}$ est défini par son action sur les vecteurs de base :


$$\hat{A}\lvert e_1\rangle = 2\lvert e_1\rangle + \lvert e_2\rangle$$

$$\hat{A}\lvert e_2\rangle = -\lvert e_1\rangle + 3\lvert e_3\rangle$$

$$\hat{A}\lvert e_3\rangle = \lvert e_2\rangle - \lvert e_3\rangle$$
  
Calculer la représantation matricielle de l’opérateur $\hat{A}$ dans la base $\{\lvert e_1\rangle, \lvert e_2\rangle, \lvert e_3\rangle \}$.
:::

Considérons l'équation :

```{math}
:label: eq-46

\left| \Phi \right\rangle = \widehat{A}\left| \Psi \right\rangle
```

On projette {eq}`eq-46` sur un vecteur de base :

$\left\langle u_{j} \middle| \Phi \right\rangle = \left\langle u_{j} \right|\widehat{A}\left| \Psi \right\rangle$
$j = 1,\; 2,...\; N$
$j = 1,\; 2,...\; N$

En appliquant la relation de fermeture :

$$\left\langle u_{j} \middle| \Phi \right\rangle = \sum_{k = 1}^{N}{\left\langle u_{j} \right|\widehat{A}\left| u_{k} \right\rangle\left\langle u_{k} \middle| \Psi \right\rangle}$$

Si le développement de $\left| \Phi \right\rangle$ sur
$\left\{ \left| u_{i} \right\rangle,i = 1...\; N \right\}$
est :

$$\left| \Phi \right\rangle = \sum_{k = 1}^{N}{b_{k}\left| u_{k} \right\rangle}$$

On a :

$$b_{j} = \sum_{k = 1}^{N}{A_{jk}c_{k}}$$

Cela signifie que la matrice colonne représentant
$\left| \Phi \right\rangle$ est obtenue en multipliant la matrice carrée
représentant $\widehat{A}$ par la matrice colonne représentant
$\left| \Psi \right\rangle$.

L'élément de matrice d'un produit de deux opérateurs est :

$$\left\langle u_{j} \right|\widehat{A}\widehat{B}\left| u_{k} \right\rangle = \sum_{i = 1}^{N}{\left\langle u_{j} \right|\widehat{A}\left| u_{i} \right\rangle\left\langle u_{i} \right|\widehat{B}\left| u_{k} \right\rangle}$$

La matrice représentant un produit d'opérateurs est donc le produit des
matrices qui représentent chacun d'eux.

La polarisation du photon est un degré de liberté interne. L'espace des
états de polarisation est de dimension 2. On peut choisir comme états de
base les états de polarisations rectilignes $\left| X \right\rangle$ et
$\left| Y \right\rangle$.

$$\left| \Psi \right\rangle_{\left\{ \left| X \right\rangle,\left| Y \right\rangle \right\}} = \begin{pmatrix}
\left\langle X \middle| \Psi \right\rangle \\
\left\langle Y \middle| \Psi \right\rangle
\end{pmatrix}$$

avec :

$$\left| X \right\rangle_{\left\{ \left| X \right\rangle,\left| Y \right\rangle \right\}} = \begin{pmatrix}
\left\langle X \middle| X \right\rangle \\
\left\langle Y \middle| X \right\rangle
\end{pmatrix} = \begin{pmatrix}
1 \\
0
\end{pmatrix}$$

et :

$$\left| Y \right\rangle_{\left\{ \left| X \right\rangle,\left| Y \right\rangle \right\}} = \begin{pmatrix}
\left\langle X \middle| Y \right\rangle \\
\left\langle Y \middle| Y \right\rangle
\end{pmatrix} = \begin{pmatrix}
1 \\
0
\end{pmatrix}$$

## Amplitudes de localisation

Si à $t$ une particule est « dans l'état
$\left| \Psi(t) \right\rangle$ » (décrit par l'état
$\left| \Psi(t) \right\rangle$) son {index}`amplitude de localisation` à l'abscisse
est :

$$\left\langle x \middle| \Psi(t) \right\rangle = \Psi(x,t)$$

Contrairement au cas où les états pourraient être repérés par un indice
discret, on a besoin d'une infinité d'amplitude pour définir
complètement l'état du système. On peut considérer que l'amplitude de
localisation est une fonction de deux variables et qui s'appelle la
 {index}`fonction d’onde`

Dans le cas d'une variable aléatoire continue, il est impossible
d'attribuer une probabilité finie à chaque valeur précise de celle-ci.
Il faut plutôt attribuer une probabilité à un intervalle de valeurs de
la variable. On définit la densité de probabilité $g(x,t)$ [à
partir de la probabilité infinitésimale de trouver la particule à
l'instant] $t$ entre $x$ et $x + dx$ :

$$dP(x,x + dx,t) = g(x,t)dx$$

La probabilité pour que la variable prenne une valeur comprise entre
$x_{1}$ et $x_{2}$ est :

$$P\left( x_{1},x_{2},t \right) = \int_{x_{1}}^{x_{2}}{g(x,t)dx}$$

La condition de normalisation des probabilités s'écrit donc :

$$\int_{- \infty}^{+ \infty}{g(x,t)dx} = 1$$

Puisque la probabilité est un nombre sans dimension, la densité de
probabilité a la dimension inverse de la variable $x$.

La densité de probabilité est liée à l'amplitude de localisation :

$$g(x,t) = \left| \left\langle x \middle| \Psi(t) \right\rangle \right|^{2} = \Psi^{*}(x,t)\Psi(x,t)$$

La densité de probabilité de présence est donc le module au carré de la
fonction d\'onde.

et la condition de normalisation des probabilités s'écrit :

$$\int_{- \infty}^{+ \infty}{\Psi^{*}(x,t)\Psi(x,t)\; dx} = 1$$

ou bien :

$$\int_{- \infty}^{+ \infty}{\left\langle \Psi(t) \middle| x \right\rangle\left\langle x \middle| \Psi(t) \right\rangle\; dx} = 1$$

Si cette condition est remplie $\Psi(x,t)$ est dite normalisée à
l'unité.

Si :

```{math}
:label: eq-norma

\int_{- \infty}^{+ \infty}{\left| \left\langle x \middle| \Psi(t) \right\rangle \right|^{2}\; dx} = C
```

Lorsque $C$ est finie, $\Psi(x,t)$ est dite de carré
sommable {index}`Fonction d'onde de carré sommable`. On peut
alors la normaliser à l'unité en divisant par $\sqrt{C}$. Pour que
l'intégrale converge, il est nécessaire que le module de $\Psi(x,t)$
tende vers 0 aux grandes distances. La particule est donc localisée dans
une région finie de l'espace. Elle se trouve dans un  {index}`état lié`. Nous verrons que son énergie ne peut
prendre que des valeurs discrètes.

```{note}
Il existe des situations dans lesquelles la fonction d'onde n'est pas de
carré sommable. Tout l'espace est alors accessible à la particule. Les
énergies possibles remplissent un continuum.

En effet une amplitude de localisation de la forme :

$$\Psi(x)=\exp{(jkx)}$$

est telle que :

$$\int_{- \infty}^{+ \infty}{\left| \Psi(x) \right|^{2}dx} \,=\,\int_{- \infty}^{+ \infty}{dx}\,=\,\infty $$

Une telle amplitude de localisation n'est pas normalisable selon la relation {eq}`eq-norma`.
```

## Postulats de la théorie quantiques

Cinq postulats permettent de donner un contenu au formalisme de la
physique quantique.

:::{tip} Postulat 1
L'état du système physique à un instant $t$ est complètement
défini par la donnée de son vecteur d'état
$\left| \Psi(t) \right\rangle$.
:::

:::{tip} Postulat 2
A toute grandeur physique mesurable A, on associe une observable
$\widehat{A}$.
:::
:::{tip} Postulat 3
La mesure d'une grandeur physique A ne peut donner comme résultats que l'une des valeurs propres de l'observable associé $\widehat{A}$.
:::

:::{tip} Postulat 4
Lors de la mesure d\'une grandeur physique A d\'un système dans un
 état $\left| \Psi(t) \right\rangle$ normé à l'unité, la probabilité
d\'obtenir comme résultat une valeur propre a~n~ donnée **<u>non
 dégénérée</u>** est égale à la probabilité de transition de
 l\'état $\left| \Psi(t) \right\rangle$ vers l\'état propre associé
 $\left| \phi_{n} \right\rangle$ :
 $\left| \left\langle \phi_{n} \middle| \Psi(t) \right\rangle \right|^{2}$.
:::

:::{tip} Postulat 5
<u>Si la valeur propre est non dégénérée</u>, l'état du
 immédiatement après la mesure ayant donné la valeur propre est l'état
 propre lui correspondant.
:::

Ainsi le postulat 1°) signifie que la donnée de
$\left| \Psi(t) \right\rangle$ permet de fournir une réponse à toute
question posée expérimentalement.

2°) Une observable est un opérateur hermitique dont les vecteurs propres
forment une base pour l'espace des états.

4°) La probabilité pour trouver une valeur propre particulière se
confond avec la probabilité pour trouver le système dans l'état propre
correspondant.

Supposons que les kets
$\left\{ \left| u_{k} \right\rangle\; k = 1,...N \right\}$
soient kets propres de $\widehat{A}$ avec les valeurs propres de
$a_{k}$ :

$$\left\langle \Psi \right|\widehat{A}\left| \Psi \right\rangle = \sum_{i = 1}^{N}{\left\langle \Psi \right|\widehat{A}\left| u_{k} \right\rangle\left\langle u_{k} \middle| \Psi \right\rangle} = \sum_{i = 1}^{N}{a_{k}\left\langle \Psi \middle| u_{k} \right\rangle\left\langle u_{k} \middle| \Psi \right\rangle}$$

d\'où :
$\left\langle \Psi \right|\widehat{A}\left| \Psi \right\rangle = \sum_{i = 1}^{N}{a_{k}P\left( a_{k} \right)}$

où $P\left( a_{k} \right)$ est la probabilité de trouver la valeur
propre $a_{k}$. Le nombre correspondant est donc la valeur moyenne de la
grandeur physique représentée par l'observable $\widehat{A}$ dans
l\'état $\left| \Psi \right\rangle$.

$$\left\langle \widehat{A} \right\rangle_{\Psi} = \left\langle \Psi \right|\widehat{A}\left| \Psi \right\rangle$$

## Mesure de deux grandeurs physiques

**<u>Le processus de mesure perturbe le système</u>** et peut
provoquer un changement d'état du système étudié. Le seul cas pour
lequel le résultat peut être prédit avec certitude est celui pour lequel
le système est déjà dans un état propre de l'observable correspondant à
la grandeur physique mesurée. En effet si :

$$\left.  \left| \Psi \right.  \right\rangle = \left.  \left| u_{k} \right.  \right\rangle$$

tous les autres coefficients de développement sur les états
$\left.  \left| u_{l} \right.  \right\rangle$ ($l \neq k$) sont nuls.
En conséquence une répétition de la mesure immédiatement après la
première mesure donnera avec certitude le même résultat. L'immédiateté a
une importance car le système pourrait évoluer (s'il n'était pas
parfaitement isolé) et ne pas rester dans l'état
$\left.  \left| u_{k} \right.  \right\rangle$.


:::{attention}À connaître par coeur
:::{prf:definition}
:label: my-commutateru
Soient $\widehat{A}$ et $\widehat{B}$ deux observables associées à des
grandeurs à mesurer. Par définition leur **{index}`commutateur`** est :

$$\left\lbrack \widehat{A},\widehat{B} \right\rbrack = \widehat{A}\widehat{B} - \widehat{B}\widehat{A}$$
:::
:::

S'il est nul on a $\widehat{A}\widehat{B} = \widehat{B}\widehat{A}$ et
on dit que les observables commutent.

Soit $\left.  \left| \Phi \right.  \right\rangle$ un ket propre de
$\widehat{A}$ associé à la valeur propre $a$ :

$$\widehat{A}\left| \Phi \right\rangle = a\left| \Phi \right\rangle$$

et :

$$\widehat{B}\widehat{A}\left| \Phi \right\rangle = a\widehat{B}\left| \Phi \right\rangle$$

Si $\widehat{A}$ et $\widehat{B}$ commutent on peut donc écrire :

$$\widehat{A}\widehat{B}\left| \Phi \right\rangle = a\widehat{B}\left| \Phi \right\rangle$$

$\widehat{B}\left| \Phi \right\rangle$ est ket propre de $\widehat{A}$
associé à la valeur propre $a$. Or par hypothèse, il y a un seul ket
propre de $\widehat{A}$ correspondant à cette valeur propre.
$\left| \Phi \right\rangle$ et $\widehat{B}\left| \Phi \right\rangle$
sont proportionnels c'est-à-dire :

$$\widehat{B}\left| \Phi \right\rangle = b\left| \Phi \right\rangle$$

Ainsi le ket propre de $\widehat{A}$ est aussi ket propre de
$\widehat{B}$. La même conclusion s'applique à chacun des kets propres
de $\widehat{A}$ qui par hypothèse forment une base de l'espace des
états. On peut donc conclure que si $\widehat{A}$ et $\widehat{B}$
commutent, <u>ils possèdent une base commune de vecteurs
propres</u>.

Il est facile de montrer que réciproquement si $\widehat{A}$ et
$\widehat{B}$ ont une base de vecteurs propres communs, ils commutent.
On a alors :

$$\widehat{A}\left| u_{k} \right\rangle = a_{k}\left| u_{k} \right\rangle$$

$$\widehat{B}\left| u_{k} \right\rangle = b_{k}\left| u_{k} \right\rangle$$

Soit $\left| \Psi \right\rangle$ un ket quelconque de $\varepsilon$. On
peut dire que $\widehat{A}$ et $\widehat{B}$ commutent si la relation

$$\widehat{A}\widehat{B}\left| \Psi \right\rangle = \widehat{B}\widehat{A}\left| \Psi \right\rangle$$

est toujours vérifiée.

Or par hypothèse :

$$\widehat{A}\widehat{B}\left| u_{k} \right\rangle = \widehat{A}\left( b_{k}\left| u_{k} \right\rangle \right) = a_{k}b_{k}\left| u_{k} \right\rangle$$

$$\widehat{B}\widehat{A}\left| u_{k} \right\rangle = \widehat{B}\left( a_{k}\left| u_{k} \right\rangle \right) = a_{k}b_{k}\left| u_{k} \right\rangle$$

La relation de fermeture permet d\'écrire :

$$\widehat{A}\widehat{B}\left| \Psi \right\rangle = \sum_{k = 1}^{N}{\widehat{A}\widehat{B}\left| u_{k} \right\rangle\left\langle u_{k} \middle| \Psi \right\rangle} = \sum_{k = 1}^{N}{a_{k}b_{k}\left| u_{k} \right\rangle\left\langle u_{k} \middle| \Psi \right\rangle}$$

et

$$\widehat{B}\widehat{A}\left| \Psi \right\rangle = \sum_{k = 1}^{N}{\widehat{B}\widehat{A}\left| u_{k} \right\rangle\left\langle u_{k} \middle| \Psi \right\rangle} = \sum_{k = 1}^{N}{b_{k}a_{k}\left| u_{k} \right\rangle\left\langle u_{k} \middle| \Psi \right\rangle}$$

On peut donc conclure que <u>si les observables</u> $\widehat{A}$
et</u> $\widehat{B}$ <u>ont une base de vecteurs propres communs
ils commutent</u>.

Soient $\widehat{A}$ et $\widehat{B}$ deux observables qui commutent.
Supposons que la mesure de la grandeur physique représentée par
$\widehat{A}$ donne le résultat $a_{k}$. L'état du système immédiatement
après la mesure est $\left| u_{k} \right\rangle$. Or cet état est ket
propre de l'observable $\widehat{B}$ avec comme valeur propre $b_{k}$.
La mesure de la grandeur physique correspondante effectuée immédiatement
après celle qui est représentée par $\widehat{A}$ donne avec certitude
le résultat $b_{k}$ et l'état du système reste
$\left| u_{k} \right\rangle$.

Des nouvelles mesures de ces grandeurs donneront les mêmes résultats. On
dit alors que ces grandeurs physiques sont **{index}`compatibles`**.

Si les observables associées à deux grandeurs physiques ne commutent pas
leurs vecteurs propres sont en général différents et les résultats
obtenus [en mesurant successivement ces deux grandeurs dépendent de
l\'ordre dans lequel on fait la mesure]. Si la grandeur associée
à $\widehat{A}$ est mesurée d\'abord et le résultat obtenu est $a_{k}$,
l\'état du système immédiatement après cette mesure est
$\left| u_{k} \right\rangle$. En général il n\'est pas un état propre de
$\widehat{B}$. Si $\left| v_{j} \right\rangle$ l\'est, il n\'est pas en
général un état propre de $\widehat{A}$. Une nouvelle mesure de cette
grandeur ne donne donc pas nécessairement le même résultat que la
première. <u>Ainsi l\'information obtenue dans une mesure peut être
détruite en mesurant une grandeur incompatible</u>.

 [^43]: Un espace de Hilbert est un espace préhilbertien séparé et
    complet. Un espace préhilbertien est un espace vectoriel sur $\mathbb{C}$
    (ou $\mathbb{R}$) muni d'une forme sesquilinéaire (anti-linéaire par
    rapport au premier vecteur et linéaire par rapport au second)
    auto-adjointe. Lorsque cette forme est définie positive, il s'agit
    d'un produit scalaire hermitien et cet espace devient un espace
    préhilbertien séparé.
