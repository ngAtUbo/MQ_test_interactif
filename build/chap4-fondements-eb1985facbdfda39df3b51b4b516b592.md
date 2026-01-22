Ã¯Â»Â¿---
title: "Les fondements de la mÃƒÆ’Ã‚Â©canique quantique"
description: "IdÃƒÆ’Ã‚Â©es fondatrices de l'approche quantique."
authors:
  - name: Gilles Nguyen Vien
    affiliation: DÃƒÆ’Ã‚Â©partement de Physique, UniversitÃƒÆ’Ã‚Â© de Bretagne Occidentale
license:
  id: "CC-BY-NC-ND-4.0"

date: 2026-01-19
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Les fondements de la mÃƒÆ’Ã‚Â©canique quantique

## Evidence expÃƒÆ’Ã‚Â©rimentale de l\'incompatibilitÃƒÆ’Ã‚Â© de certaines grandeurs

On peut montrer qu\'il est impossible de mesurer avec prÃƒÆ’Ã‚Â©cision pour un
corpuscule tel que l\'ÃƒÆ’Ã‚Â©lectron ÃƒÆ’Ã‚Â  la fois sa position et son impulsion.
Cherchons ÃƒÆ’Ã‚Â  mesurer simultanÃƒÆ’Ã‚Â©ment $y = 0$ et $p_{y} = 0$.

```{figure} media/image20.png
:name: fig-diffElecFente
:alt: Diffraction des ÃƒÆ’Ã‚Â©lectrons par une fente
:width: 80%
Diffraction des ÃƒÆ’Ã‚Â©lectrons par une fente
```

On interpose sur le trajet d\'un faisceau d\'ÃƒÆ’Ã‚Â©lectrons une fente afin de
sÃƒÆ’Ã‚Â©lectionner les ÃƒÆ’Ã‚Â©lectrons ayant une ordonnÃƒÆ’Ã‚Â©e $y$ nulle. La prÃƒÆ’Ã‚Â©cision
est liÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  la largeur de la fente $\delta y$. Les ÃƒÆ’Ã‚Â©lectrons triÃƒÆ’Ã‚Â©s ont
donc une ordonnÃƒÆ’Ã‚Â©e comprise entre $- \delta y/2$ et $\delta y/2$.

Cependant nous observons que l\'homogÃƒÆ’Ã‚Â©nÃƒÆ’Ã‚Â©itÃƒÆ’Ã‚Â© de la direction des vitesses
($v_{y} = 0$ avant la fente) du faisceau d\'ÃƒÆ’Ã‚Â©lectrons a ÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â© dÃƒÆ’Ã‚Â©truite du fait du passage des
ÃƒÆ’Ã‚Â©lectrons par la fente.

En effet, le faisceau issu de la fente a subi un
ÃƒÆ’Ã‚Â©talement de la distribution angulaire des trajectoires dans un angle
$\alpha$.

```{important}
$\alpha$ est donnÃƒÆ’Ã‚Â© par la loi empirique :

$$\alpha = \lambda/\delta y$$

ÃƒÆ’Ã‚Â  la condition **d'associer ÃƒÆ’Ã‚Â  l'ÃƒÆ’Ã‚Â©lectron une longueur
d'onde** $\lambda$ que l\'expÃƒÆ’Ã‚Â©rience montre ÃƒÆ’Ã‚Â©gale ÃƒÆ’Ã‚Â  :

$$\lambda = \frac{h}{p}$$
```
oÃƒÆ’Ã‚Â¹ $p$ est le module de la quantitÃƒÆ’Ã‚Â© de mouvement de l\'ÃƒÆ’Ã‚Â©lectron
$\overrightarrow{p}$ et $h$ la constante de Planck.

Ce phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne est appelÃƒÆ’Ã‚Â© un phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne de **{index}`diffraction`**  auquel la physique classique n\'apporte aucune
rÃƒÆ’Ã‚Â©ponse.


L'hypothÃƒÆ’Ã‚Â¨se que cette diffraction serait inhÃƒÆ’Ã‚Â©rente ÃƒÆ’Ã‚Â  l'action des bords
de la fente sur la trajectoire des ÃƒÆ’Ã‚Â©lectrons pourrait ÃƒÆ’Ã‚Âªtre examinÃƒÆ’Ã‚Â©e si
cette diffraction demeurait la mÃƒÆ’Ã‚Âªme quel que soit la largeur de la
fente. Tel n'est pas le cas. En effet, on observe que la diffraction
devient plus faible lorsque l'on augmente la largeur de la fente.

Ainsi, la fixation de $y$ ÃƒÆ’Ã‚Â  $\delta y$ prÃƒÆ’Ã‚Â¨s introduit donc
nÃƒÆ’Ã‚Â©cessairement une incertitude $\delta p_{y}$ sur la composante $p_{y}$
de sa quantitÃƒÆ’Ã‚Â© de mouvement aprÃƒÆ’Ã‚Â¨s traversÃƒÆ’Ã‚Â©e de la fente :

$$\delta p_{y} = p\sin{\alpha \cong p\alpha \cong p\frac{\lambda}{\delta y}} = \frac{h}{\delta y}$$

L\'incertitude $\delta p_{y}$ ÃƒÆ’Ã‚Â©tant inversement proportionnelle ÃƒÆ’Ã‚Â 
$\delta y$, il est impossible de fixer simultanÃƒÆ’Ã‚Â©ment avec une parfaite
prÃƒÆ’Ã‚Â©cision des valeurs aux grandeurs $y$ et $p_{y}$.

## DualitÃƒÆ’Ã‚Â© onde-corpuscule

Les interprÃƒÆ’Ã‚Â©tations des expÃƒÆ’Ã‚Â©riences de Compton et de l\'effet
photoÃƒÆ’Ã‚Â©lectrique suffisent-elles pour rejeter dÃƒÆ’Ã‚Â©finitivement la thÃƒÆ’Ã‚Â©orie
ondulatoire ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tique de la lumiÃƒÆ’Ã‚Â¨re ?

Faut-il rejeter dÃƒÆ’Ã‚Â©finitivement la thÃƒÆ’Ã‚Â©orie ondulatoire et en revenir ÃƒÆ’Ã‚Â  la
thÃƒÆ’Ã‚Â©orie corpusculaire aux prix de raffinements tentant d\'expliquer la
diffraction des ÃƒÆ’Ã‚Â©lectrons par une fente ?

La rÃƒÆ’Ã‚Â©ponse est bien ÃƒÆ’Ã‚Â©videmment non. On verra que les aspects
ondulatoires et corpusculaires sont indissolublement liÃƒÆ’Ã‚Â©s pour rendre
compte de nombreux faits expÃƒÆ’Ã‚Â©rimentaux. On parle alors de dualitÃƒÆ’Ã‚Â© onde
corpuscule afin d\'exprimer que les objets microscopiques possÃƒÆ’Ã‚Â¨dent de
faÃƒÆ’Ã‚Â§on intrinsÃƒÆ’Ã‚Â¨que des propriÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â©s qui les assimilent ÃƒÆ’Ã‚Â  la fois ÃƒÆ’Ã‚Â  des
ondes et ÃƒÆ’Ã‚Â  des corpuscules matÃƒÆ’Ã‚Â©riels.

En 192ÃƒÆ’Ã‚Â§ De Broglie {cite}`de1929wave` a ÃƒÆ’Ã‚Â©mis l\'hypothÃƒÆ’Ã‚Â¨se que cette dualitÃƒÆ’Ã‚Â© est une
caractÃƒÆ’Ã‚Â©ristique de tous les objets microscopiques considÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©s comme des
particules.

La formule donnant la longueur d\'onde dite de de Broglie fonction de
l\'impulsion :

```{math}
:label: eq-longdeBroglie

\lambda = \frac{h}{p}
```

<u>est supposÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Âªtre applicable selon De Broglie pour toute particule quel
que soit leur masse ÃƒÆ’Ã‚Â  condition de prendre</uÃƒÂ¢Ã…Â¸Ã‚Â©$\overrightarrow{p} = \gamma m\overrightarrow{v}$ si la particule est
relativiste oÃƒÆ’Ã‚Â¹ $\gamma$ est le facteur de Lorentz
$\gamma = \frac{1}{\sqrt{1 - v^{2}/c^{2}}}$.

{eq}`eq-longdeBroglie` est donnÃƒÆ’Ã‚Â©e souvent sous une forme ÃƒÆ’Ã‚Â©quivalente :

$$p = \frac{h}{2\pi}\frac{2\pi}{\lambda} = \hslash k$$

L\'ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique d\'une particule non relativiste ÃƒÆ’Ã‚Â©tant donnÃƒÆ’Ã‚Â©e par :
$E_{cin} = \frac{p^{2}}{2m}$

$$\lambda = \frac{h}{p}$$

conduit :

$$\lambda = \frac{h}{\sqrt{2mE_{cin}}}$$

## Annexe : dualitÃƒÆ’Ã‚Â© onde-corpuscule

Nous verrons, par un cheminement simplifiÃƒÆ’Ã‚Â©, comment il a pu associer une
longueur d\'onde ÃƒÆ’Ã‚Â  toute particule.

Revenons au cas des photons. Examinons de quelle maniÃƒÆ’Ã‚Â¨re l'hypothÃƒÆ’Ã‚Â¨se de
l'existence du corpuscule de lumiÃƒÆ’Ã‚Â¨re par essence de nature relativiste
concilie la relation de Planck-Einstein avec celle obtenue par Einstein
dans son traitÃƒÆ’Ã‚Â© sur la relativitÃƒÆ’Ã‚Â© restreinte reliant l'ÃƒÆ’Ã‚Â©nergie totale
$E$ d'une particule ÃƒÆ’Ã‚Â  l'impulsion $\overrightarrow{p}$ et sa masse
$m_{0}$ (masse au repos ou propre).

La formule relativiste reliant l\'ÃƒÆ’Ã‚Â©nergie et l\'impulsion d\'une
particule s\'ÃƒÆ’Ã‚Â©crit :

$$E^{2} = p^{2}c^{2} + {m_{0}}^{2}c^{4}$$

oÃƒÆ’Ã‚Â¹ $m_{0}$ est la masse de la particule au repos,
$\overrightarrow{p} = \gamma m\overrightarrow{v}$ avec
$\gamma = \frac{1}{\sqrt{1 - \beta^{2}}}$ et $ \beta = \frac{v}{c}$

On a donc :

$${E = h\nu = \sqrt{{p^{2}c}^{2} + {m_{0}}^{2}c^{4}}}$$

La frÃƒÆ’Ã‚Â©quence de l'onde pouvant ÃƒÆ’Ã‚Âªtre rendue arbitrairement aussi petite
qu'on le souhaite, on obtient ÃƒÆ’Ã‚Â  la limite de la frÃƒÆ’Ã‚Â©quence nulle :

$${0 \approx ( \sqrt{{p^{2}c}^{2} + {m_{0}}^{2}c^{4}} )_{\nu \approx 0}}$$

La formule ci-dessus est vÃƒÆ’Ã‚Â©rifiÃƒÆ’Ã‚Â©e si et seulement si les deux termes
sous la racine sont nuls, ceci entraÃƒÆ’Ã‚Â®nant que la masse du photon est
nulle : $m_{0} = 0$. Cette propriÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â© est vraie quel que soit la
frÃƒÆ’Ã‚Â©quence.

Dans ce cas, on a alors

$$E = pc$$

En utilisant la relation de Planck-Einstein $E = h\nu$, on peut ainsi
lier l\'aspect ondulatoire (la frÃƒÆ’Ã‚Â©quence) et l\'aspect corpusculaire
(quantitÃƒÆ’Ã‚Â© de mouvement) :

$$\frac{c}{\nu} = \frac{h}{p}$$

c\'est-ÃƒÆ’Ã‚Â -dire :

$$\lambda = \frac{h}{p}$$

On retrouve la relation expÃƒÆ’Ã‚Â©rimentale obtenue dans l'expÃƒÆ’Ã‚Â©rience de
diffraction des ÃƒÆ’Ã‚Â©lectrons.

Cette relation a ÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â© vÃƒÆ’Ã‚Â©rifiÃƒÆ’Ã‚Â©e dans le cas des photons par l\'effet
Compton. **<u>De Broglie a supposÃƒÆ’Ã‚Â© qu\'elle ÃƒÆ’Ã‚Â©tait vraie pour toute
particule quel que soit leur masse ÃƒÆ’Ã‚Â  condition de prendre</u>**
$\overrightarrow{p} = \gamma m\overrightarrow{v}$. On l\'ÃƒÆ’Ã‚Â©crit souvent
sous la forme ÃƒÆ’Ã‚Â©quivalente :

$$p = \frac{h}{2\pi}\frac{2\pi}{\lambda}$$

c\'est-ÃƒÆ’Ã‚Â -dire :

$p = \hslash k$ et plus gÃƒÆ’Ã‚Â©nÃƒÆ’Ã‚Â©ralement
$\overrightarrow{p} = \hslash\overrightarrow{k}$

oÃƒÆ’Ã‚Â¹ $\hslash = \frac{h}{2\pi}$. L\'impulsion est donc proportionnelle au
vecteur d\'onde.

Nous allons chercher ÃƒÆ’Ã‚Â  exprimer la longueur d\'onde en fonction de
l\'ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique de la particule. Lorsque la particule est au repos
son impulsion est nulle et son ÃƒÆ’Ã‚Â©nergie est :

$$E_{0} = mc^{2}$$

Lorsqu\'elle est en mouvement son ÃƒÆ’Ã‚Â©nergie est augmentÃƒÆ’Ã‚Â©e d\'une quantitÃƒÆ’Ã‚Â©
qui est par dÃƒÆ’Ã‚Â©finition son ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique $E_{cin}$.

On a donc :

$$E = E_{0} + E_{cin}$$

En ÃƒÆ’Ã‚Â©levant au carrÃƒÆ’Ã‚Â© il vient :

$$E^{2} = {E_{0}}^{2} + {E_{cin}}^{2} + 2E_{0}E_{cin}$$

D\'aprÃƒÆ’Ã‚Â¨s la formulation relativiste de l'ÃƒÆ’Ã‚Â©nergie
$E^{2} = p^{2}c^{2} + {m_{0}}^{2}c^{4}$, on a :

$${p^{2}c}^{2} = {E_{cin}}^{2} + 2E_{0}E_{cin}$$

soit :

$$p = \frac{1}{c}\sqrt{{E_{cin}}^{2} + 2E_{0}E_{cin}}$$

ou encore :

$$p = \frac{E_{0}}{c}\sqrt{( \frac{E_{cin}}{E_{0}} )^{2} + 2( \frac{E_{cin}}{E_{0}} )}$$

La longueur d\'onde s\'ÃƒÆ’Ã‚Â©crit donc :

$$\lambda = \frac{hc}{E_{0}}\frac{1}{\sqrt{( \frac{E_{cin}}{E_{0}} )^{2} + 2( \frac{E_{cin}}{E_{0}} )}} = \frac{\lambda_{c}}{\sqrt{( \frac{E_{cin}}{E_{0}} )^{2} + 2( \frac{E_{cin}}{E_{0}} )}}$$

oÃƒÆ’Ã‚Â¹ $\lambda_{c} = \frac{h}{mc}$ est la longueur d\'onde Compton de la
particule.

Dans l\'approximation non relativiste, on a $E_{cin} \ll E_{0}$ et on
peut ÃƒÆ’Ã‚Â©crire :

$$\lambda = \frac{\lambda_{c}}{\sqrt{2( \frac{E_{cin}}{E_{0}} )}}$$

L\'ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique ÃƒÆ’Ã‚Â©tant donnÃƒÆ’Ã‚Â©e par : $E_{cin} = \frac{p^{2}}{2m}$

et on retrouve bien :

$$\lambda = \frac{h}{p}$$

ou :

$$\lambda = \frac{h}{\sqrt{2mE_{cin}}}$$

## VÃƒÆ’Ã‚Â©rifications expÃƒÆ’Ã‚Â©rimentales

### Diffraction des ÃƒÆ’Ã‚Â©lectrons

De Broglie a prÃƒÆ’Ã‚Â©dit qu\'il ÃƒÆ’Ã‚Â©tait possible de mettre en ÃƒÆ’Ã‚Â©vidence l\'onde
associÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  des ÃƒÆ’Ã‚Â©lectrons en mettant en ÃƒÆ’Ã‚Â©vidence leur diffraction par un
cristal ÃƒÆ’Ã‚Â  la maniÃƒÆ’Ã‚Â¨re de l\'expÃƒÆ’Ã‚Â©rience de diffraction {cite}`friedrich1913phenomenes` des rayons X [^38]
par un cristal de [Friedrich](wiki:Walter_Friedrich) et Knipping.

En 1928, Davisson et Germer {cite}`davisson1928reflection` rÃƒÆ’Ã‚Â©alisÃƒÆ’Ã‚Â¨rent une expÃƒÆ’Ã‚Â©rience de diffraction
d\'ÃƒÆ’Ã‚Â©lectrons par un cristal de Nickel :


```{figure} media/image21.png
:name: fig-davisson
:alt: ExpÃƒÆ’Ã‚Â©rience de Davisson et Germer
:width: 90%
ExpÃƒÆ’Ã‚Â©rience de Davisson et Germer
```

La relation de [Bragg](wiki:William_Lawrence_Bragg) dÃƒÆ’Ã‚Â©montrÃƒÆ’Ã‚Â©e dans le cas de la diffraction des rayons X est :

```{figure} media/image22.jpg
:name: fig-bragg
:alt: Relation de Bragg
:width: 60%
Relation de Bragg
```

$$2d \sin{\theta} = n \lambda$$

En dÃƒÆ’Ã‚Â©plaÃƒÆ’Ã‚Â§ant l\'ÃƒÆ’Ã‚Â©lectrode collectrice, Davisson et Germer mesure que les
intensitÃƒÆ’Ã‚Â©s maximales du courant mesurÃƒÆ’Ã‚Â© avaient lieu pour des angles
$\theta$ vÃƒÆ’Ã‚Â©rifiant la relation de Bragg ÃƒÆ’Ã‚Â  la condition de prendre pour
longueur d\'onde $\lambda$ la longueur d\'onde de De Broglie associÃƒÆ’Ã‚Â©e
aux ÃƒÆ’Ã‚Â©lectrons :

$$\lambda = \frac{h}{p} = \frac{h}{\sqrt{2meV}}$$

### PropriÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â©s ondulatoires de la matiÃƒÆ’Ã‚Â¨re : autres aspects

La diffraction des ÃƒÆ’Ã‚Â©lectrons par un mÃƒÆ’Ã‚Â©tal requiert pour ÃƒÆ’Ã‚Âªtre observÃƒÆ’Ã‚Â©e
que la longueur d\'onde de De Broglie soit de l\'ordre de grandeur des
distances entre les atomes dans le cristal.

Le microscope ÃƒÆ’Ã‚Â©lectronique constitue une application intÃƒÆ’Ã‚Â©ressante des
caractÃƒÆ’Ã‚Â©ristiques ondulatoires de l\'ÃƒÆ’Ã‚Â©lectron. On sait que le pouvoir
sÃƒÆ’Ã‚Â©parateur est liÃƒÆ’Ã‚Â© ÃƒÆ’Ã‚Â  la longueur d\'onde. En accÃƒÆ’Ã‚Â©lÃƒÆ’Ã‚Â©rant les ÃƒÆ’Ã‚Â©lectrons ÃƒÆ’Ã‚Â 
quelques dizaines de keV leur longueur d\'onde devient trÃƒÆ’Ã‚Â¨s courte
($10^{-11}$ ÃƒÆ’Ã‚Â  $10^{-12}$ m) ce qui permet d\'atteindre un trÃƒÆ’Ã‚Â¨s bon pouvoir
sÃƒÆ’Ã‚Â©parateur.

Le neutron possÃƒÆ’Ã‚Â©dant une masse de l\'ordre de 1800 fois celle des
ÃƒÆ’Ã‚Â©lectrons peut-il manifester une propriÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â© ondulatoire comme l\'a
supposÃƒÆ’Ã‚Â© De Broglie ?

Aux ÃƒÆ’Ã‚Â©nergies thermiques (quelques centiÃƒÆ’Ã‚Â¨mes d\'eV) les neutrons ont
des longueurs d\'onde de l\'ordre de $1$ ÃƒÆ’Ã¢â‚¬Â¦ ce qui permet de les utiliser
dans l\'ÃƒÆ’Ã‚Â©tude de la structure cristalline. Contrairement aux atomes
neutres ils sont trÃƒÆ’Ã‚Â¨s pÃƒÆ’Ã‚Â©nÃƒÆ’Ã‚Â©trants car ils n\'interagissent pratiquement
pas avec les ÃƒÆ’Ã‚Â©lectrons. Ils sont essentiellement diffusÃƒÆ’Ã‚Â©s par les
noyaux. Ils ne fournissent cependant aucune information sur la structure
nuclÃƒÆ’Ã‚Â©aire car la longueur d\'onde associÃƒÆ’Ã‚Â©e est beaucoup plus grande que
le rayon nuclÃƒÆ’Ã‚Â©aire. Pour ÃƒÆ’Ã‚Â©tudier la structure nuclÃƒÆ’Ã‚Â©aire il faut des
longueurs d\'onde comparables aux dimensions nuclÃƒÆ’Ã‚Â©aires. Pour cela
l\'ÃƒÆ’Ã‚Â©nergie des neutrons doit atteindre quelques *MeV*. Des expÃƒÆ’Ã‚Â©riences
de diffraction des neutrons permettent ÃƒÆ’Ã‚Â  nouveau de vÃƒÆ’Ã‚Â©rifier la relation
de De Broglie.

Les particules possÃƒÆ’Ã‚Â©dant cette dualitÃƒÆ’Ã‚Â© onde et corpuscule sont souvent
dÃƒÆ’Ã‚Â©signÃƒÆ’Ã‚Â©es de **{index}`quantons`** ou
particules quantiques.

## Notions de {index}`paquets d'onde`

Dans un milieu homogÃƒÆ’Ã‚Â¨ne et isotrope, le type le plus simple d\'onde est
l\'onde monochromatique dont la reprÃƒÆ’Ã‚Â©sentation complexe est donnÃƒÆ’Ã‚Â©e :

$$e^{i(\overrightarrow{k}.\overrightarrow{r} - \omega t)}$$

reprÃƒÆ’Ã‚Â©sentant une vibration de longueur d\'onde
$\lambda = \frac{2\pi}{k}$ se propageant dans la direction de son
vecteur d\'onde $\overrightarrow{k}$ ÃƒÆ’Ã‚Â  la vitesse constante. La vitesse
de propagation est la vitesse de phase.

$\omega$ est indÃƒÆ’Ã‚Â©pendante de la direction de $\overrightarrow{k}$
(milieu isotrope) mais peut dÃƒÆ’Ã‚Â©pendre ÃƒÆ’Ã‚Â©ventuellement du module de ce
vecteur.

On associe l\'onde ci-dessus ÃƒÆ’Ã‚Â  un mouvement rectiligne uniforme
d\'ÃƒÆ’Ã‚Â©nergie
$E = \hslash\omega$ dirigÃƒÆ’Ã‚Â©e parallÃƒÆ’Ã‚Â¨lement ÃƒÆ’Ã‚Â  $\overrightarrow{k}$.

Comme toute onde peut ÃƒÆ’Ã‚Âªtre considÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©e comme une superposition d\'ondes
planes monochromatiques, la connaissance de la loi de dispersion
$\omega(k)$ suffit ÃƒÆ’Ã‚Â  dÃƒÆ’Ã‚Â©terminer le comportement de n\'importe quelle
onde au cours du temps.

ConsidÃƒÆ’Ã‚Â©rons le cas particulier d'une onde plane monochromatique se
propageant dans le sens positif de l\'axe Ox. Elle est reprÃƒÆ’Ã‚Â©sentÃƒÆ’Ã‚Â©e par
la fonction :


```{math}
:label: eq-OPPsi0

\Psi_{0}(x,t) = A_{0}\cos{(k_{0}x - \omega_{0}t)}
```

D\'aprÃƒÆ’Ã‚Â¨s la formule de De Broglie elle est associÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  une particule
d\'impulsion bien dÃƒÆ’Ã‚Â©finie $p_{0} = \hslash k_{0}$ et d\'ÃƒÆ’Ã‚Â©nergie bien
dÃƒÆ’Ã‚Â©finie $E_{0} = \hslash\omega_{0}$.

L'onde plane {eq}`eq-OPPsi0` ne peut pas reprÃƒÆ’Ã‚Â©senter une
particule localisÃƒÆ’Ã‚Â©e dans une rÃƒÆ’Ã‚Â©gion de l\'espace d\'extension
finie car son extension spatiale est infinie comme toute
fonction sinusoÃƒÆ’Ã‚Â¯dale.

C\'est la raison pour laquelle, il est nÃƒÆ’Ã‚Â©cessaire <u>pour reprÃƒÆ’Ã‚Â©senter le
comportement ondulatoire d'une particule localisÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  un instant dans une
portion de l'espace</u> de construire une superposition
d\'ondes planes qui interfÃƒÆ’Ã‚Â¨rent de maniÃƒÆ’Ã‚Â¨re constructive dans une rÃƒÆ’Ã‚Â©gion
limitÃƒÆ’Ã‚Â©e de l\'espace (oÃƒÆ’Ã‚Â¹ se trouve la particule) et de faÃƒÆ’Ã‚Â§on destructive
ailleurs. Cette idÃƒÆ’Ã‚Â©e est le fondement de la notion de **paquet
d\'ondes**.

Pour une particule libre non relativiste l\'ÃƒÆ’Ã‚Â©nergie purement cinÃƒÆ’Ã‚Â©tique
est donnÃƒÆ’Ã‚Â©e par :

$$E_{0} = \frac{{p_{0}}^{2}}{2m}$$

On en dÃƒÆ’Ã‚Â©duit la relation de dispersion :

```{math}
:label: eq-dispOmega0

\omega_{0} = \frac{E_{0}}{\hslash} = \frac{{p_{0}}^{2}}{2m\hslash} = \frac{\hslash{k_{0}}^{2}}{2m}
```

La vitesse de phase est donc :

$$v_{\varphi} = \frac{\omega_{0}}{k_{0}} = \frac{\hslash k_{0}}{2m}$$

Pour construire une fonction qui ne possÃƒÆ’Ã‚Â¨de de valeurs apprÃƒÆ’Ã‚Â©ciables que
dans une rÃƒÆ’Ã‚Â©gion limitÃƒÆ’Ã‚Â©e de l\'espace, il faut superposer des ondes ayant
diffÃƒÆ’Ã‚Â©rentes valeurs de k et de ÃƒÂÃ¢â‚¬Â°.

ConsidÃƒÆ’Ã‚Â©rons une fonction de la forme :

$$\Psi(x,t) = \sum_{S}^{}{{A_{S}\cos}{(k_{S}x - \omega_{S}t)}}$$

oÃƒÆ’Ã‚Â¹ les amplitudes $A_{S}$ mesurent l\'importance relative des
diffÃƒÆ’Ã‚Â©rentes ondes superposÃƒÆ’Ã‚Â©es. On peut en principe choisir les $A_{S}$
de maniÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â  produire une fonction $\Psi(x,t)$ qui n\'a des valeurs
importantes que dans une rÃƒÆ’Ã‚Â©gion localisÃƒÆ’Ã‚Â©e de l\'espace.

Supposons qu\'ÃƒÆ’Ã‚Â  $ t = 0$, $\Psi(x,0)$ est la superposition de trois
ondes telles que :

$k_{1} = k_{0} - \frac{\Delta k}{2}$, $k_{2} = k_{0}$,
$k_{3} = k_{0} + \frac{\Delta k}{2}$, $A_{1} = A_{3} = \frac{A_{0}}{2}$
et $A_{2} = A_{0}$

De plus, nous supposerons que $ \Delta k \ll k_{0}$, c\'est-ÃƒÆ’Ã‚Â -dire que
la dispersion des valeurs de $k$ est petite par rapport ÃƒÆ’Ã‚Â  la moyenne
$k_{0}$.

On a donc :

$$\Psi(x,0) = A_{0}[ \frac{1}{2}\cos( x(k_{0} - \frac{\Delta k}{2}) ) + \cos( k_{0}x ) + \frac{1}{2}\cos( x(k_{0} + \frac{\Delta k}{2}) ) ]$$

d\'oÃƒÆ’Ã‚Â¹ :

$$\Psi(x,0) = A_{0}[ 1 + \cos( \frac{\Delta k}{2}x ) ]\cos( k_{0}x )$$

soit :

$$\Psi(x,0) = {2A}_{0}\cos^{2}( \frac{\Delta k}{4}x )\cos( k_{0}x )$$

On a donc une fonction $\cos( k_{0}x )$ qui oscille trÃƒÆ’Ã‚Â¨s rapidement comme le montre la figure tracÃƒÆ’Ã‚Â©e par le [script Python](#markdown-WP). L\'amplitude est modulÃƒÆ’Ã‚Â©e par une
autre fonction dont l\'oscillation est beaucoup plus lente. L\'amplitude
oscille entre les valeurs $0$ et ${2A}_{0}$et elle atteint son maximum
en $x = 0$ ÃƒÆ’Ã‚Â  $t = 0$.

```{code-cell} ipython3
:label: markdown-WP
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

A $t = 0$, la fonction $\cos^{2}( \frac{\Delta k}{4}x )$
s\'annule en :

$$x = \pm \frac{2\pi}{\Delta k}$$

La largeur spatiale de l\'enveloppe est :

$$\Delta x = \frac{4\pi}{\Delta k}$$

alors que la largeur en impulsion est :

$$\Delta p = \hslash\Delta k$$

Le mouvement ÃƒÆ’Ã‚Â©tant unidimensionnel selon l'axe $Ox$, le produit de ces
deux grandeurs est donnÃƒÆ’Ã‚Â© par :

```{math}
:label: eq-deltaxdeltap

\Delta x\Delta p = \Delta x\Delta p_{x} = 4\pi\hslash
```

C\'est donc une grandeur fondamentale indÃƒÆ’Ã‚Â©pendante des caractÃƒÆ’Ã‚Â©ristiques
des ondes superposÃƒÆ’Ã‚Â©es. Ainsi pour construire une fonction bien localisÃƒÆ’Ã‚Â©e
dans l\'espace il faut superposer des ondes correspondant ÃƒÆ’Ã‚Â  une grande
dispersion des impulsions. **<u>Il est donc impossible de reprÃƒÆ’Ã‚Â©senter une
particule ayant une impulsion et une position bien dÃƒÆ’Ã‚Â©finies
simultanÃƒÆ’Ã‚Â©ment.</u>**

Le calcul simple effectuÃƒÆ’Ã‚Â© ici avec seulement trois ondes planes donne en
fait une fonction pÃƒÆ’Ã‚Â©riodique de $x$ ; la particule possÃƒÆ’Ã‚Â¨de donc une
infinitÃƒÆ’Ã‚Â© d\'images du lobe centrale comme le montre la figure ci-dessus. En rÃƒÆ’Ã‚Â©alitÃƒÆ’Ã‚Â© il est possible de construire une
fonction qui ne possÃƒÆ’Ã‚Â¨de qu\'une seule image (ou lobe de l'enveloppe) ou
qui interfÃƒÆ’Ã‚Â¨re de maniÃƒÆ’Ã‚Â¨re constructive dans une seule rÃƒÆ’Ã‚Â©gion de l'espace
d'extension finie. Pour cela il est nÃƒÆ’Ã‚Â©cessaire de superposer un trÃƒÆ’Ã‚Â¨s
grand nombre d'onde de valeurs de $k$ trÃƒÆ’Ã‚Â¨s proches.

A la limite, la superposition forme un continuum de telle maniÃƒÆ’Ã‚Â¨re que la
somme sur les diffÃƒÆ’Ã‚Â©rentes valeurs de $k$ devient une intÃƒÆ’Ã‚Â©grale. En
reprÃƒÆ’Ã‚Â©sentation complexe on a :

$$\Psi(x,t) = \int_{- \infty}^{+ \infty}{A(k)e^{i(kx - \omega t)}dk}$$

oÃƒÆ’Ã‚Â¹ l\'amplitude $A(k)$ peut ÃƒÆ’Ã‚Âªtre complexe.

On ÃƒÆ’Ã‚Â©crit, de maniÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â©quivalente :

```{math}
:label: eq-paquetInt1D

\Psi(x,t) = \int_{- \infty}^{+ \infty}{| A(k) |{e^{i\alpha(k)}e}^{i(kx - \omega t)}dk}
```

On suppose que $| A(k) |$ possÃƒÆ’Ã‚Â¨de des valeurs apprÃƒÆ’Ã‚Â©ciables
dans un intervalle $\Delta k$ centrÃƒÆ’Ã‚Â© autour d\'une valeur $k_{0}$.
L\'intÃƒÆ’Ã‚Â©grale {eq}`eq-paquetInt1D` sera maximale en module ÃƒÆ’Ã‚Â  chaque
instant lorsque les ondes d\'amplitudes les plus grandes c\'est-ÃƒÆ’Ã‚Â -dire
celles qui correspondent ÃƒÆ’Ã‚Â  $k$ voisin de $k_{0}$ interfÃƒÆ’Ã‚Â¨reront de
maniÃƒÆ’Ã‚Â¨re constructive. Ceci se produit lorsque la phase de ces ondes qui
dÃƒÆ’Ã‚Â©pend de $k$ ne varie pratiquement pas autour de
$k = k_{0}$. On ÃƒÆ’Ã‚Â©crit donc la condition de phase stationnaire :

$$\frac{d}{dk} (\alpha + kx - \omega t) = 0$$

c\'est-ÃƒÆ’Ã‚Â -dire :

$$\frac{d\alpha}{dk} + x - \frac{d\omega}{dk}t = 0$$

soit :

$$x = \frac{d\omega}{dk}t - \frac{d\alpha}{dk}$$

La relation ci-dessus est l\'ÃƒÆ’Ã‚Â©quation d\'un mouvement uniforme ÃƒÆ’Ã‚Â  la
vitesse :

$$v_{g} = \frac{d\omega}{dk}$$

Cette grandeur est appelÃƒÆ’Ã‚Â©e {index}`vitesse de groupe`. Elle correspond prÃƒÆ’Ã‚Â©cisÃƒÆ’Ã‚Â©ment ÃƒÆ’Ã‚Â  la vitesse de
dÃƒÆ’Ã‚Â©placement du centre du paquet d\'onde.

La quantitÃƒÆ’Ã‚Â© $- \frac{d\alpha}{dk}$ est indÃƒÆ’Ã‚Â©pendante du temps et joue le
rÃƒÆ’Ã‚Â´le de position initiale.

En utilisant la relation de dispersion {eq}`eq-dispOmega0`, on trouve
:

$$v_{g} = \frac{\hslash k}{m}$$

c\'est-ÃƒÆ’Ã‚Â -dire :

$$v_{g} = \frac{p}{m} = v$$

C\'est donc la vitesse de groupe qui est associÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  la vitesse de la
particule.

Remarque

Chaque onde composant le paquet d\'onde se dÃƒÆ’Ã‚Â©place avec sa propre
vitesse qui est la vitesse de phase puisque cette derniÃƒÆ’Ã‚Â¨re dÃƒÆ’Ã‚Â©pend de la
valeur de $k$. Ainsi l\'ÃƒÆ’Ã‚Â©volution temporelle d\'un paquet d\'onde montre
une propagation du paquet subissant une dÃƒÆ’Ã‚Â©formation de la forme du
paquet. C\'est la raison pour laquelle la relation qui donne $\omega$ en
fonction de $k$ s\'appelle la relation de dispersion.

Il est donc possible de construire une fonction localisÃƒÆ’Ã‚Â©e dans l\'espace
mais <u>ÃƒÆ’Ã‚Â  la condition d\'accepter une certaine dispersion des vecteurs
d\'onde</u> c'est-ÃƒÆ’Ã‚Â -dire des impulsions. Or pour qu\'une
particule possÃƒÆ’Ã‚Â¨de une trajectoire bien dÃƒÆ’Ã‚Â©finie il faut qu\'elle possÃƒÆ’Ã‚Â¨de
ÃƒÆ’Ã‚Â  chaque instant une position et une impulsion bien dÃƒÆ’Ã‚Â©finies. Il semble
donc impossible d'attribuer de telles grandeurs ÃƒÆ’Ã‚Â  une particule si on la
reprÃƒÆ’Ã‚Â©sente ÃƒÆ’Ã‚Â  l\'aide d\'un paquet d\'ondes.

On retrouve le constat fait dans le cas de la diffraction des ÃƒÆ’Ã‚Â©lectrons
par une fente quant ÃƒÆ’Ã‚Â  l\'incompatibilitÃƒÆ’Ã‚Â© de la grandeur position et
impulsion.

## Paquet d'onde gaussien (hors programme L2)

On considÃƒÆ’Ã‚Â¨re en exemple un [paquet d'onde gaussien](#markdown-WPG) oÃƒÆ’Ã‚Â¹ la sommation devient une intÃƒÆ’Ã‚Â©grale. On montre que cette fois-ci la sommation intÃƒÆ’Ã‚Â©grale d'ondes de nombres d'onde "infiniment rapprochÃƒÆ’Ã‚Â©s" conduit ÃƒÆ’Ã‚Â  une intÃƒÆ’Ã‚Â©rfÃƒÆ’Ã‚Â©rence constructive dans une seule rÃƒÆ’Ã‚Â©gion localisÃƒÆ’Ã‚Â©e de l'espace :

$$
f(x,t)=\int_{-\infty}^{+\infty}
\exp[-\frac{a^2(k-k_0)^2}{4}]
e^{i(kx-\omega t)}\, dk
$$



```{code-cell} ipython3
:label: markdown-WPG
import numpy as np
import matplotlib.pyplot as plt

def trapz_local(y, x):
    return np.sum((y[1:] + y[:-1]) * (x[1:] - x[:-1]) / 2)

def f_of_x(x,t, k,a,k0):
    """
    return |psi(x,t)|**2
    intrale sur k calculÃƒÆ’Ã‚Â©e avec mÃƒÆ’Ã‚Â©thode des trapÃƒÆ’Ã‚Â¨zes
    """
    gaussian = np.exp(-(a**2) * (k - k0)**2 / 4)
    phase = np.exp(1j * (k * x-omega(k,hbar,m)*t))
    integrand = gaussian * phase
    return trapz_local(integrand, k)

def omega(k,hbar,m):
    """
    calcule la 
    relation de dispersion d'une particule de masse m
    hbar * k **2 / m
    """
    return hbar*k**2/2/m

# ParamÃƒÆ’Ã‚Â¨tres du paquet dÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢onde (valeur abrbitraires)
a = 1.0
k0 = 5.0
hbar = 1E-34
m = 9.1E-31 # electron
 

# Grille spatiale
x = np.linspace(-10, 10, 400)

#vitesse de groupe
vg = hbar * k0 / m

# estimation du temps pour parcourir 5m
t5m = 5 / vg

# Grille en k
k = np.linspace(k0 - 10, k0 + 10, 3000)
plt.figure(figsize=(8,4))

t_values=[-t5m,0,t5m]

for t in t_values:
    f_vals = np.array([f_of_x(xi, t, k, a, k0) for xi in x])
    prob_density = np.abs(f_vals)**2
    plt.plot(x, prob_density,label = "t = {:f} s".format(t))
    plt.xlabel("x")
    plt.ylabel(r"|f(x,t)|^2")
    plt.title(f"|Paquet dÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢onde gaussien|^2")
    plt.legend()
    plt.grid(True)
    plt.tight_layout()


plt.show()
```

La dispersion du paquet d'onde causant sa dÃƒÆ’Ã‚Â©formation au cours de la propagation est constitutive de la nature du paquet d'onde (nature ondulatoire de l'ÃƒÆ’Ã‚Â©lectron)

## Mesures de la position et l\'impulsion

Nous venons de voir, dans une tentative de rÃƒÆ’Ã‚Â©duire la rÃƒÆ’Ã‚Â©alitÃƒÆ’Ã‚Â© du monde
physique ÃƒÆ’Ã‚Â  celle des ondes (paquet d\'ondes) ou ÃƒÆ’Ã‚Â  celle des particules
(diffraction des ÃƒÆ’Ã‚Â©lectrons par une fente), qu'il est impossible
d'attribuer une position et une impulsion bien dÃƒÆ’Ã‚Â©finies ÃƒÆ’Ã‚Â  une particule,
et donc de lui attribuer une trajectoire.

Cette limitation constitue-elle un ÃƒÆ’Ã‚Â©chec fatal pour cette dÃƒÆ’Ã‚Â©marche ?

<u>Est-il possible de connaÃƒÆ’Ã‚Â®tre la position et l'impulsion d'une particule
avec une prÃƒÆ’Ã‚Â©cision illimitÃƒÆ’Ã‚Â©e ?</u> L\'utilisation d\'un
diaphragme est sans doute la mÃƒÆ’Ã‚Â©thode la plus directe pour mesurer la
position d\'un ÃƒÆ’Ã‚Â©lectron. Cependant, on peut ÃƒÆ’Ã‚Â©galement ÃƒÆ’Ã‚Â©clairer cet
objet et observer sa position au travers d\'un microscope.

Heisenberg a fait une analyse critique de ce processus de mesure
(*observer effect*) en s'intÃƒÆ’Ã‚Â©ressant ÃƒÆ’Ã‚Â  la mesure prÃƒÆ’Ã‚Â©cise de la position
d'un ÃƒÆ’Ã‚Â©lectron. L'expÃƒÆ’Ã‚Â©rience de pensÃƒÆ’Ã‚Â©e qu'il a proposÃƒÆ’Ã‚Â©e est connue sous
le nom de {index}`microscope de Heisenberg`. Nous allons la dÃƒÆ’Ã‚Â©crire ici.

Lorsqu\'un objet macroscopique est ÃƒÆ’Ã‚Â©clairÃƒÆ’Ã‚Â©, il n\'est pas perturbÃƒÆ’Ã‚Â© par
l\'impact des photons et on peut l\'observer sans le dÃƒÆ’Ã‚Â©ranger. Il n\'en
va pas de mÃƒÆ’Ã‚Âªme d\'un objet microscopique comme un ÃƒÆ’Ã‚Â©lectron par exemple

Ainsi si on ÃƒÆ’Ã‚Â©claire un ÃƒÆ’Ã‚Â©lectron et que l'on observe les photons
dÃƒÆ’Ã‚Â©flÃƒÆ’Ã‚Â©chis dans une lentille, on remonte ÃƒÆ’Ã‚Â  la connaissance de la position
de l'ÃƒÆ’Ã‚Â©lectron. L\'expÃƒÆ’Ã‚Â©rience de Compton a montrÃƒÆ’Ã‚Â© qu\'il subit un recul
sous l\'impact du photon. <u>On perturbe donc l'ÃƒÆ’Ã‚Â©lectron en lui imposant
un changement d\'impulsion</u>. Or pour obtenir une bonne
rÃƒÆ’Ã‚Â©solution spatiale il faut utiliser une longueur d\'onde courte
c\'est-ÃƒÆ’Ã‚Â -dire des photons de grande impulsion. La perturbation que subit
l\'ÃƒÆ’Ã‚Â©lectron est alors plus grande. Si l'on souhaitait mesurer de maniÃƒÆ’Ã‚Â¨re
subsÃƒÆ’Ã‚Â©quente l'impulsion de l'ÃƒÆ’Ã‚Â©lectron, il faudrait ÃƒÆ’Ã‚Â©valuer la
perturbation provoquÃƒÆ’Ã‚Â©e par la mesure qui relÃƒÆ’Ã‚Â¨ve du processus de mesure.
On peut ÃƒÆ’Ã‚Â©valuer une telle perturbation en mesurant le changement
d\'impulsion du photon. On mesure donc l'impulsion finale du
photon en supposant que la seule source d\'imprÃƒÆ’Ã‚Â©cision provient de cette
mesure.

ConsidÃƒÆ’Ã‚Â©rons un ÃƒÆ’Ã‚Â©lectron ÃƒÆ’Ã‚Â©clairÃƒÆ’Ã‚Â© par un faisceau de lumiÃƒÆ’Ã‚Â¨re (pas
nÃƒÆ’Ã‚Â©cessairement visible pour l\'Ãƒâ€¦Ã¢â‚¬Å“il humain). L\'observation, ÃƒÆ’Ã‚Â  l\'aide
d\'un microscope, d\'un photon diffusÃƒÆ’Ã‚Â© par l\'ÃƒÆ’Ã‚Â©lectron permet d\'obtenir
une information sur sa position {numref}`fig-micHeisen`. Or la
prÃƒÆ’Ã‚Â©cision obtenue sur la mesure de la position est limitÃƒÆ’Ã‚Â©e par le
pouvoir sÃƒÆ’Ã‚Â©parateur du microscope. Puisque celui-ci ne peut pas donner
des images distinctes de deux points dont la diffÃƒÆ’Ã‚Â©rence d\'ordonnÃƒÆ’Ã‚Â©es est
infÃƒÆ’Ã‚Â©rieure ÃƒÆ’Ã‚Â  :

$$\delta = \frac{\lambda}{2\sin(\theta/2)}$$

l\'incertitude sur l\'ordonnÃƒÆ’Ã‚Â©e de l\'ÃƒÆ’Ã‚Â©lectron est de l\'ordre de
$\Delta y = \delta$.

```{figure} media/image17.png
:name: fig-micHeisen
:alt: Principe du microscope d\'Heisenberg
:width: 90%
Principe du microscope d\'Heisenberg
```

On suppose que l\'impulsion initiale du photon $\overrightarrow{p}$ est
connue avec une prÃƒÆ’Ã‚Â©cision illimitÃƒÆ’Ã‚Â©e. L\'observateur ou instrument qui
reÃƒÆ’Ã‚Â§oit le photon sait uniquement que celui-ci a traversÃƒÆ’Ã‚Â© la lentille
mais il ignore par quel endroit il est passÃƒÆ’Ã‚Â©.

Evaluons l\'impulsion transfÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©e par le photon ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©lectron. Avant la
collision, nous supposons que l\'ÃƒÆ’Ã‚Â©lectron est au repos
$\overrightarrow{p^{e}} = \overrightarrow{0}$ en $y = 0$. L\'impulsion
du photon est supposÃƒÆ’Ã‚Â©e connue avec une prÃƒÆ’Ã‚Â©cision illimitÃƒÆ’Ã‚Â©e. Sa direction
est le long $Oy$ est son module est $p = \frac{h}{\lambda}$. AprÃƒÆ’Ã‚Â¨s la
collision, l\'impulsion transfÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©lectron sur Oy est
$mv_{y}^{e}$. Cette derniÃƒÆ’Ã‚Â¨re est maximale lorsque la composante selon
$Oy$ de l'impulsion du photon est nÃƒÆ’Ã‚Â©gative et que la direction de
diffusion correspond ÃƒÆ’Ã‚Â  l'angle maximal autorisÃƒÆ’Ã‚Â© par l'ouverture
angulaire de la lentille (chemin **<u>2</u>**). On a alors
d\'aprÃƒÆ’Ã‚Â¨s la relation de conservation de l\'impulsion totale pour le
chemin **<u>2</u>**:

$$\overrightarrow{p} + \overrightarrow{0} = \overrightarrow{p'} + \overrightarrow{p'^{e}}$$

On projette sur $Oy$ en multipliant scalairement par le vecteur
unitaire $\overrightarrow{e_{y}}$:

$$\frac{h}{\lambda} + 0 = - \frac{h}{\lambda{}'}\sin\frac{\theta}{2} + mv^{e}_{y}{}'$$

L\'impulsion transfÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©e est minimale lorsque la composante selon $Oy$ du
photon est positive (chemin **<u>1</u>**) :

$$\frac{h}{\lambda} + 0 = \frac{h}{\lambda"}\sin\frac{\theta}{2} + mv_{y}^{e}{}"$$

Des ÃƒÆ’Ã‚Â©quations prÃƒÆ’Ã‚Â©cÃƒÆ’Ã‚Â©dentes, on peut tirer que l\'impulsion suivant $Oy$
de l\'ÃƒÆ’Ã‚Â©lectron est comprise entre
${p_{y}^{e}{}"} = \frac{h}{\lambda} - \frac{h}{\lambda"}\sin\frac{\theta}{2}$
et
${p_{y}{}'^{e}} = \frac{h}{\lambda} + \frac{h}{\lambda'}\sin\frac{\theta}{2}$

En supposant que $\lambda' \simeq \lambda$ et que
$\lambda" \simeq \lambda$, on en dÃƒÆ’Ã‚Â©duit que l\'incertitude sur la
composante suivant $Oy$ de l\'ÃƒÆ’Ã‚Â©lectron aprÃƒÆ’Ã‚Â¨s la collision est :

$${\Delta p}_{y}^{e} = \frac{h}{\lambda}\sin\frac{\theta}{2} = p\sin\frac{\theta}{2}$$

L\'utilisation d\'une courte longueur d\'onde et d\'une grande ouverture
angulaire pour la lentille conduit ÃƒÆ’Ã‚Â  une petite incertitude sur la
position mais ÃƒÆ’Ã‚Â  une grande incertitude sur l\'impulsion. Le produit des
incertitudes est indÃƒÆ’Ã‚Â©pendant de la longueur d\'onde et de l\'ouverture
de la lentille.

En effet, on a :

$$\Delta y{\Delta p}_{y}^{e} = \frac{h}{2}$$

Ce produit ne peut pas ÃƒÆ’Ã‚Âªtre rendu arbitrairement petit car il est
proportionnel ÃƒÆ’Ã‚Â  une constante fondamentale de la physique. Nous avons
obtenu en fait une limite infÃƒÆ’Ã‚Â©rieure pour le produit des incertitudes.

On peut donc ÃƒÆ’Ã‚Â©crire :

$$\Delta y{\Delta p}_{y}^{e} \geq \frac{h}{2}$$

La dÃƒÆ’Ã‚Â©termination de la trajectoire d\'une particule implique la mesure
simultanÃƒÆ’Ã‚Â©e de sa position et de sa vitesse (ou de son impulsion).

La relation prÃƒÆ’Ã‚Â©cÃƒÆ’Ã‚Â©dente implique donc que la trajectoire des objets
**microscopiques n\'est pas mesurable**.

Ceci contredit le modÃƒÆ’Ã‚Â¨le de Bohr dans lequel le mouvement de l\'ÃƒÆ’Ã‚Â©lectron
dÃƒÆ’Ã‚Â©crit une orbite bien dÃƒÆ’Ã‚Â©finie. Si ces trajectoires existaient vraiment,
pour les observer, il faudrait utiliser des photons dont la longueur
d\'onde soit infÃƒÆ’Ã‚Â©rieure ÃƒÆ’Ã‚Â  10^-10^ m (diamÃƒÆ’Ã‚Â¨tre de l\'atome d\'hydrogÃƒÆ’Ã‚Â¨ne
dans son ÃƒÆ’Ã‚Â©tat fondamental). De tels photons se trouvent dans la gamme
des rayons X et leur ÃƒÆ’Ã‚Â©nergie est supÃƒÆ’Ã‚Â©rieure ÃƒÆ’Ã‚Â  12500 eV. Cette ÃƒÆ’Ã‚Â©nergie
est considÃƒÆ’Ã‚Â©rable par rapport ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©nergie de liaison de l\'ÃƒÆ’Ã‚Â©lectron
(13,6 eV). L\'ÃƒÆ’Ã‚Â©lectron risquerait donc d\'ÃƒÆ’Ã‚Âªtre ÃƒÆ’Ã‚Â©jectÃƒÆ’Ã‚Â© de l\'atome. Ces
considÃƒÆ’Ã‚Â©rations montrent qu\'il est impossible d\'observer la trajectoire
d\'un ÃƒÆ’Ã‚Â©lectron dans un atome.

La trajectoire n\'ÃƒÆ’Ã‚Â©tant pas observable ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©chelle atomique d\'aprÃƒÆ’Ã‚Â¨s
Heisenberg, il n'est pas nÃƒÆ’Ã‚Â©cessaire de construire une thÃƒÆ’Ã‚Â©orie dans
laquelle cette notion est dÃƒÆ’Ã‚Â©finie. En effet la physique doit fournir une
rÃƒÆ’Ã‚Â©ponse uniquement aux questions qui se posent en termes d\'expÃƒÆ’Ã‚Â©riences.

## InterprÃƒÆ’Ã‚Â©tation des inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â©s de Heisenberg

La position et l\'impulsion d\'une particule ne peuvent pas ÃƒÆ’Ã‚Âªtre connues
simultanÃƒÆ’Ã‚Â©ment avec une prÃƒÆ’Ã‚Â©cision illimitÃƒÆ’Ã‚Â©e. En effet nous avons vu
formule {eq}`eq-deltaxdeltap` que le produit $\Delta x\Delta p_{x}$ ne
peut pas ÃƒÆ’Ã‚Âªtre rendu arbitrairement petit car il est proportionnel ÃƒÆ’Ã‚Â  une
constante fondamentale de la physique. Nous avons obtenu en fait une
limite infÃƒÆ’Ã‚Â©rieure pour le produit des incertitudes dont on peut donner
une formulation plus gÃƒÆ’Ã‚Â©nÃƒÆ’Ã‚Â©rale appelÃƒÆ’Ã‚Â© {index}`inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â© dÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢Heisenberg` :

$$\Delta x\Delta p_{x} \geq \hslash$$

La valeur prÃƒÆ’Ã‚Â©cise de la limite n\'a pas de sens tant qu\'une dÃƒÆ’Ã‚Â©finition
prÃƒÆ’Ã‚Â©cise de $\Delta x$ et de $\Delta p_{x}$ n\'a pas ÃƒÆ’Ã‚Â©tÃƒÆ’Ã‚Â© donnÃƒÆ’Ã‚Â©e. Cette
limite est cependant toujours liÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  la constante de Planck.

***Question*** : l\'inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â© de Heisenberg traduit-elle une incertitude
(liÃƒÆ’Ã‚Â©e au processus de mesure) ou une indÃƒÆ’Ã‚Â©termination ?

La premiÃƒÆ’Ã‚Â¨re hypothÃƒÆ’Ã‚Â¨se suppose que la position et l\'impulsion ont des valeurs bien dÃƒÆ’Ã‚Â©finies dans la nature mais que les limitations liÃƒÆ’Ã‚Â©es au processus de mesure (**{index}`observer effect`**) ou aux appareils de mesure nous empÃƒÆ’Ã‚Âªchent de
les connaÃƒÆ’Ã‚Â®tre avec une prÃƒÆ’Ã‚Â©cision illimitÃƒÆ’Ã‚Â©e.

<u>La seconde hypothÃƒÆ’Ã‚Â¨se</u> suppose au contraire que ces
grandeurs ne sont pas bien dÃƒÆ’Ã‚Â©finies dans la nature et qu\'en consÃƒÆ’Ã‚Â©quence
il est impossible de les mesurer avec une prÃƒÆ’Ã‚Â©cision illimitÃƒÆ’Ã‚Â©e. Nous
allons adopter ce second point de vue et nous allons voir que les
inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â©s de Heisenberg nous permettent d\'apprendre quelque chose sur
le comportement des systÃƒÆ’Ã‚Â¨mes physiques.

La quantitÃƒÆ’Ã‚Â© $\Delta x$ reprÃƒÆ’Ã‚Â©sente l\'extension spatiale d\'un objet
microscopique tandis que $\Delta p_{x}$ reprÃƒÆ’Ã‚Â©sente son extension en
impulsion. Du point de vue d\'une rÃƒÆ’Ã‚Â©partition statistique des rÃƒÆ’Ã‚Â©sultats
d\'une mesure, ces valeurs sont assimilables ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©cart type ou ÃƒÆ’Ã‚Â©cart
quadratique moyen.

On aura donc :
$\Delta x = \sqrt{ÃƒÂ¢Ã…Â¸Ã‚Â¨x^{2}ÃƒÂ¢Ã…Â¸Ã‚Â© - ÃƒÂ¢Ã…Â¸Ã‚Â¨xÃƒÂ¢Ã…Â¸Ã‚Â©^{2}}$
et
$\Delta p_{x} = \sqrt{ÃƒÂ¢Ã…Â¸Ã‚Â¨{p_{x}}^{2}ÃƒÂ¢Ã…Â¸Ã‚Â© - ÃƒÂ¢Ã…Â¸Ã‚Â¨p_{x}ÃƒÂ¢Ã…Â¸Ã‚Â©^{2}}$

Si la valeur moyenne est nulle il vient :

$\Delta x = \sqrt{ÃƒÂ¢Ã…Â¸Ã‚Â¨x^{2}ÃƒÂ¢Ã…Â¸Ã‚Â©}$ et $\Delta p_{x} = \sqrt{ÃƒÂ¢Ã…Â¸Ã‚Â¨{p_{x}}^{2}ÃƒÂ¢Ã…Â¸Ã‚Â©}$

Ainsi les quantitÃƒÆ’Ã‚Â©s $\Delta x$ et $\Delta p_{x}$ fournissent un ordre de
grandeur ou une estimation de $|x|$ et de $| p_{x} |$. Si on
note $a$ l\'extension spatiale, l\'extension en impulsion s\'ÃƒÆ’Ã‚Â©crit
d'aprÃƒÆ’Ã‚Â¨s la limite infÃƒÆ’Ã‚Â©rieure de l'inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â© d'Heisenberg :

$$\Delta p_{x} \simeq \frac{\hslash}{\Delta x} = \frac{\hslash}{a}$$

C\'est une valeur reprÃƒÆ’Ã‚Â©sentative de $| p_{x} |$.

### Effet tunnel

Nous allons terminer par un exemple qui prÃƒÆ’Ã‚Â©sente un immense intÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Âªt
aussi bien pratique que thÃƒÆ’Ã‚Â©orique : l'{index}`effet tunnel`  dont la dÃƒÆ’Ã‚Â©couverte est largement attribuÃƒÆ’Ã‚Â©e ÃƒÆ’Ã‚Â  Gamow {cite}`gamow1928quantentheorie`.

ConsidÃƒÆ’Ã‚Â©rons le mouvement unidimensionnel d\'une particule soumise ÃƒÆ’Ã‚Â  une
interaction qui lui donne une ÃƒÆ’Ã‚Â©nergie potentielle V(x) ({numref}`fig-effetTunnel`).

```{figure} media/tunnel.png
:name: fig-effetTunnel
:alt: Angles de polarisationEffet tunnel
:width: 90%
Effet tunnel
```

Supposons que son ÃƒÆ’Ã‚Â©nergie totale soit infÃƒÆ’Ã‚Â©rieure
ÃƒÆ’Ã‚Â  la valeur maximale de V(x). En chaque point son ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique est
donnÃƒÆ’Ã‚Â©e par :

$$E_{cin} = E - V(x)$$

D\'aprÃƒÆ’Ã‚Â¨s la thÃƒÆ’Ã‚Â©orie classique la particule ralentit lorsque l\'ÃƒÆ’Ã‚Â©nergie
potentielle augmente et la rÃƒÆ’Ã‚Â©gion oÃƒÆ’Ã‚Â¹ $E < V_{0}$ est interdite car
l\'ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique ne peut pas ÃƒÆ’Ã‚Âªtre nÃƒÆ’Ã‚Â©gative.

D\'aprÃƒÆ’Ã‚Â¨s la thÃƒÆ’Ã‚Â©orie classique, si la particule se trouve d\'un cÃƒÆ’Ã‚Â´tÃƒÆ’Ã‚Â© de
la barriÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â  un instant donnÃƒÆ’Ã‚Â© elle y reste. En effet pour aller de A en
B elle devrait passer par toutes les positions intermÃƒÆ’Ã‚Â©diaires
d'abscisses pour lesquelles l'ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique serait nÃƒÆ’Ã‚Â©gative car la
particule possÃƒÆ’Ã‚Â¨de une trajectoire bien dÃƒÆ’Ã‚Â©finie.

La relation d\'indÃƒÆ’Ã‚Â©termination de Heisenberg implique que la particule
ne possÃƒÆ’Ã‚Â¨de pas de trajectoire. Il ne lui serait donc pas interdit de
faire la transition de A ÃƒÆ’Ã‚Â  B. En effet considÃƒÆ’Ã‚Â©rer cette transition
n'implique pas que **<u>son ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique puisse ÃƒÆ’Ã‚Âªtre considÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©e comme
nÃƒÆ’Ã‚Â©gative ÃƒÆ’Ã‚Â  un instant donnÃƒÆ’Ã‚Â© !</u>** Pour pouvoir faire une
telle affirmation, il faudrait mesurer sa position avec une prÃƒÆ’Ã‚Â©cision
nettement meilleure que la largeur de la barriÃƒÆ’Ã‚Â¨re. Nous
trouverions alors que la limitation de l\'extension spatiale
$\Delta x = a$ produirait une augmentation de l\'impulsion (et donc de
l\'ÃƒÆ’Ã‚Â©nergie cinÃƒÆ’Ã‚Â©tique) tellement grande qu\'on ne pourrait pas affirmer
que l\'ÃƒÆ’Ã‚Â©nergie totale serait infÃƒÆ’Ã‚Â©rieure ÃƒÆ’Ã‚Â  la hauteur de la barriÃƒÆ’Ã‚Â¨re. En
fait, il n\'y a pas de contradiction entre la traversÃƒÆ’Ã‚Â©e de la barriÃƒÆ’Ã‚Â¨re
et la conservation de l\'ÃƒÆ’Ã‚Â©nergie parce que le concept de trajectoire
(ÃƒÆ’Ã‚Â©volution continue dans l\'espace-temps) n\'a pas de sens.

Ce genre de phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨ne se produit couramment dans les atomes, les
molÃƒÆ’Ã‚Â©cules, les solides et les noyaux. Il a reÃƒÆ’Ã‚Â§u le nom d\'effet tunnel.

## Limite de validitÃƒÆ’Ã‚Â© de la physique classique

Si les ÃƒÆ’Ã‚Â©lectrons passent ÃƒÆ’Ã‚Â  travers une fente de largeur $d$,
l'expÃƒÆ’Ã‚Â©rience montre que les effets quantiques sont nÃƒÆ’Ã‚Â©gligeables si
$\lambda \ll d$. Il suffit de quelques dizaines d\'*eV* pour qu\'un
ÃƒÆ’Ã‚Â©lectron ait une longueur d\'onde de l\'ordre de l\'AngstrÃƒÆ’Ã‚Â¶m,
c\'est-ÃƒÆ’Ã‚Â -dire une distance trÃƒÆ’Ã‚Â¨s courte ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©chelle macroscopique.
Cependant, lorsqu\'il atteint un cristal ou une poudre c\'est la
distance inter atomique qui joue le rÃƒÆ’Ã‚Â´le de distance caractÃƒÆ’Ã‚Â©ristique.
Comme elle est de l\'ordre de 1 ÃƒÆ’Ã¢â‚¬Â¦, des effets quantiques se manifestent.

Reprenons en guise d\'illustration l\'expÃƒÆ’Ã‚Â©rience de diffraction des
ÃƒÆ’Ã‚Â©lectrons par un diaphragme. La diffraction est nÃƒÆ’Ã‚Â©gligeable si :

$$\frac{\delta p_{y}}{p_{x}} \ll 1$$

soit :

$$\delta p_{y} \ll p_{x} \simeq p$$

ou encore :

$$\frac{h}{\delta y} \ll \frac{h}{\lambda}$$

ce qui est toujours le cas si $\lambda \ll d$.

Pour conclure, on peut formuler le critÃƒÆ’Ã‚Â¨re de validitÃƒÆ’Ã‚Â© de la mÃƒÆ’Ã‚Â©canique
classique ÃƒÆ’Ã‚Â  l\'aide des inÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â©s de Heisenberg. Tant que la prÃƒÆ’Ã‚Â©cision
des mesures est telle que :

$\Delta x\Delta p_{x} \gg \hslash$, $\Delta y\Delta p_{y} \gg \hslash$
et $\Delta z\Delta p_{z} \gg \hslash$

les effets quantiques ne se manifestent pas dans l'expÃƒÆ’Ã‚Â©rience.

 [^38]: Les rayons X sont des radiations ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tiques trÃƒÆ’Ã‚Â¨s
    ÃƒÆ’Ã‚Â©nergÃƒÆ’Ã‚Â©tiques (0.5 ÃƒÆ’Ã‚Â  30 KeV). Ils peuvent ÃƒÆ’Ã‚Âªtre produits par
    ionisation en couche interne d\'un atome. Le trou est comblÃƒÆ’Ã‚Â© par un
    ÃƒÆ’Ã‚Â©lectron provenant d\'une couche externe avec ÃƒÆ’Ã‚Â©mission d\'un photon
    X. Ils peuvent ÃƒÆ’Ã‚Âªtre ÃƒÆ’Ã‚Â©galement produit par l\'accÃƒÆ’Ã‚Â©lÃƒÆ’Ã‚Â©ration (freinage)
    des ÃƒÆ’Ã‚Â©lectrons sur une cible dans un tube ÃƒÆ’Ã‚Â  rayons X : les ÃƒÆ’Ã‚Â©lectrons
    sont extraits d\'une cathode
    de tungstÃƒÆ’Ã‚Â¨ne chauffÃƒÆ’Ã‚Â©e, accÃƒÆ’Ã‚Â©lÃƒÆ’Ã‚Â©rÃƒÆ’Ã‚Â©s par une tension ÃƒÆ’Ã‚Â©lectrique dans un
    tube sous vide, ce faisceau sert ÃƒÆ’Ã‚Â  bombarder une cible mÃƒÆ’Ã‚Â©tallique
    (appelÃƒÆ’Ã‚Â©e anode ou anti-cathode) ; le ralentissement des ÃƒÆ’Ã‚Â©lectrons
    par les atomes de la cible provoque un rayonnement continu de
    freinage
