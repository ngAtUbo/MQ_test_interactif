# Probabilités et amplitudes quantiques

## Introduction


Nous avons vu que le concept de photon s\'est imposé pour expliquer
certains phénomènes impliquant des ondes électromagnétiques. Einstein a
émis en 1905 l\'idée selon laquelle la théorie électromagnétique de
Maxwell n\'est correcte que statistiquement, c\'est-à-dire dans des
situations faisant intervenir un grand nombre de photons. L\'expérience
confirme cette hypothèse aujourd\'hui.

Les objets \"quantiques\" qui sont caractérisés par la dualité
onde/corpuscule sont appelés \"quantons\" pour ne pas favoriser un
aspect par rapport à l\'autre.

Nous commencerons l\'élaboration d\'un schéma théorique qui vise à
interpréter les phénomènes impliquant des quantons. Les lois énoncées
s\'appliqueront à tous les quantons mais nous attacherons une importance
particulière au photon.

Nous verrons que la notion de probabilité est indispensable. En effet
les lois de la physique quantique sont fondamentalement probabilistes.
La notion de probabilité est cependant insuffisante : le concept
**d\'amplitude de probabilité** {index}`Amplitude de probabilité` est nécessaire pour expliquer
l\'interférence quantique. Les règles relatives au calcul des amplitudes
et des probabilités jouent le rôle de postulats de la théorie quantique.

## La notion de probabilité en physique quantique

Montrons que la notion de probabilité est indispensable à
l\'interprétation des phénomènes lumineux mais pas insuffisante.

### Loi de Malus

Considérons une onde plane polarisée rectilignement (lumière
monochromatique) incidente sur un polariseur rectiligne dont l\'axe est
selon la direction du vecteur unitaire $\overrightarrow{a}$.
L\'amplitude du champ électrique est $E_{0}$ et l\'intensité est $I_{0}$
après la traversée du polariseur. Un second polariseur, identique au
premier mais dont l\'axe est suivant le vecteur unitaire
$\overrightarrow{b}$ est placé sur le chemin du faisceau transmis par le
premier polariseur. L\'amplitude transmise par le second polariseur
est :

$E_{t} = E_{0}\overrightarrow{a}.\overrightarrow{b} = E_{0}\cos\theta$
| où $\theta$ est l\'angle entre les axes des

```{figure} media/imagePol19.png
:name: fig-anglesPolar
:alt: Angles de polarisation
:width: 60%
Angles de polarisation.
```

L\'intensité mesurée après le second  polariseur est donnée par :

$$I_{t} = I_{0}\cos^{2}\theta$$

Cette relation est appelée loi de Malus. 

Elle est en accord avec les prévisions de la théorie de Maxwell. Ainsi
si l\'intensité [41] varie comme $\cos^{2}\theta$ lorsqu\'on tourne le
deuxième polariseur [42], la fréquence de la lumière (et donc sa
couleur) ne change pas.

Nous allons chercher une interprétation de la loi de Malus à l\'aide du
concept de photon. Chaque photon est porteur de l\'énergie
$\hslash\omega$.

Soit $N$ le flux de photons (nombre de photons transportés par unité de
temps et par unité de section du faisceau). L\'intensité du faisceau
incident c\'est à dire le flux en énergie est :

$$I = N\hslash\omega$$

Puisque la proportion $\cos^{2}\theta$ de l\'énergie incidente sur le
second polariseur est transmise on peut envisager deux hypothèses :

1° une proportion $\cos^{2}\theta$ de chaque photon traverse le
polariseur,

2° une proportion $\cos^{2}\theta$ des photons est transmise
intégralement.

L\'hypothèse 1° combinée à la loi de Planck - Einstein entraîne que la
fréquence est multipliée par $\cos^{2}\theta$ à la sortie du second
polariseur. On devrait donc observer un changement de couleur en
tournant ce polariseur. Au-delà d\'une certaine valeur de $\theta$, la
lumière transmise devrait même être invisible. La fréquence ne changeant
pas lors de la traversée d\'un polariseur, l\'hypothèse doit être
rejetée.

Selon l\'hypothèse 2° il y a une certaine fraction $\cos^{2}\theta$ des
photons qui sont transmis intégralement. On peut dire ainsi que la
probabilité pour qu\'un photon soit transmis est $\cos^{2}\theta$. Tous
les photons sont identiques et pourtant certains sont transmis alors que
d\'autres sont absorbés. Malgré de nombreuses tentatives personne n\'a
pu imaginer un mécanisme qui permettrait de prédire avec certitude ce
qui arriverait à un photon donné. <u>La théorie quantique ne peut que
calculer la probabilité pour qu\'un photon soit transmis</u>.
Il est évidemment impossible de prédire ce qui arrivera à un photon
particulier : c\'est la **statistique se rapportant à un grand nombre
d\'événements qui permet de vérifier la théorie**.

### Réflexion partielle de la lumière

Considérons le phénomène familier de la réflexion partielle de la
lumière à l\'interface entre deux milieux transparents. C\'est un
phénomène qui est très bien expliqué par la théorie électromagnétique de
Maxwell. Dans le cas d\'une incidence normale, le\
l\'expérience montre que 4 % de l\'énergie incidente est réfléchie ; il
y a donc 96 % de l\'énergie qui est transmise dans le second milieu.

Dans l'hypothèse de l'existence des photons et puisque tous les photons
sont identiques on peut se demander pourquoi certains sont réfléchis et
d\'autres sont transmis. On pourrait formuler l\'hypothèse que le verre
comporte un certain nombre de trous (cylindriques) et que les photons
arrivant dans un trou sont transmis alors que ceux qui arrivent entre
les trous sont réfléchis. Cette hypothèse est peu crédible car le même
phénomène s\'observe à la surface de l\'eau. Or les molécules sont
mobiles dans un liquide. Il n\'y a donc aucune raison de supposer qu\'il
existe des canaux vides qui permettent le passage des photons.

En outre, la quantité d\'énergie réfléchie par une couche mince dépend
de son épaisseur. Dans le cas d\'un verre d\'indice de réfraction *1,5*
elle peut varier de *0* à *16 %*. La quantité réfléchie tend à diminuer
avec l'augmentation de l'épaisseur de la lame. Ce fait montre qu\'il est
impossible d\'interpréter la réflexion partielle à partir d\'un modèle
géométrique simple de la lame mais il montre également l\'insuffisance
de la notion de probabilité. Si *4%* des photons sont réfléchis sur la
première face de la lame on ne peut pas expliquer comment l\'énergie
réfléchie diminue avec l'augmentation de l'épaisseur de la lame.

### Nature granulaire de la lumière

On peut montrer expérimentalement la nature granulaire de la lumière en
utilisant un éclairage de très faible intensité. Si la théorie de
Maxwell était exacte l\'énergie reçue varierait de la même façon en tout
point de la surface éclairée. L\'expérience montre que ce n\'est pas ce
qui se produit (Figure 2). Au contraire, on voit apparaître des taches
localisées produites par les impacts des photons. L\'existence de ces
derniers n\'est plus évidente lorsque l\'éclairage est fort : les
fluctuations statistiques deviennent relativement moins importantes
lorsque le nombre de photons est grand.

L\'expérience d\'Young réalisée avec une source de très faible intensité
permet de mettre en évidence les impacts localisés des photons sur la
plaque photographique {numref}`fig-clichés` :

**Photographie prise avec :**

```{figure} media/image24.png
:name: fig-clichés
:alt: Clichés sous différentes intensités
:width: 90%
Clichés pris avec : a) $10^3$ photons b) $1,2 \times 10^4$ photons c) $9,3 \times 10^4$ photons d) $7,4 \times ^5$ photons e) $3,6 \times 10^6$ photons f) $2,8 \times 10^7$ photons
```

```{figure} media/image25.png
:name: fig-frangesY
:alt: Franges d\'Young à différentes intensités
:width: 100%
Franges d\'Young à différentes intensités : a) $28$ photons b) $1 000$ photons c) $10 000$ photons**
```

Les franges sombres et les franges brillantes dont l\'existence est
expliquée par la théorie ondulatoire apparaissent lorsque le nombre de
photons est assez grand.

Ici encore la notion de probabilité est insuffisante pour expliquer
l\'existence de franges sombres. En effet, la probabilité étant un
nombre non négatif, on ne peut pas obtenir une probabilité nulle de
recevoir un photon à certains endroits lorsque les deux fentes sont
ouvertes sans que la probabilité pour que le photon passe par chacune
des fentes soit nulle.

## Le comportement quantique

Avant d\'introduire le formalisme de la théorie quantique nous allons
présenter une expérience de pensée imaginée par R.P. Feynman qui décrit
bien les caractéristiques essentielles du comportement quantique. Ce
comportement quantique se réfère à l'évolution dans l'espace-temps d'un
système physique réalisé au moyen d'une expérience. Une telle expérience
sera décrite par l'état initial du système étudié et par ce même état
dans un état final.

Considérons le dispositif de Young mais avec une source produisant des
corpuscules classiques des balles de fusils (indestructibles) comme le montre la {numref}`fig-corpClass` par
exemple .


```{figure} media/image22.png
:name: fig-corpClass
:alt: Corpuscules classiques
:width: 90%
Corpuscules classiques
```

Un ensemble de détecteurs
permet de mesurer le nombre de balles reçues sur l\'écran en fonction de
la position. Lorsque seul le trou 1 est ouvert cette distribution est
donnée par la courbe $N_1(y)$ et lorsque seul le trou 2 est ouvert elle
est donnée par $N_2(y)$. Pour la même durée de fonctionnement, lorsque
les deux trous sont ouverts on obtient une distribution qui en chaque
point est la somme des précédentes :

$$N_{12}(y) = N_{1}(y) + N_{2}(y)$$

De plus la détection des balles donne lieu à des impacts bien définis
dans l\'espace et dans le temps.

Gardons le même dispositif mais remplaçons la source de particules
classiques par une source d\'ondes classiques. Lorsque seul le trou 1
est ouvert l\'intensité est donnée par $I_{1}(y)$ et lorsque seul le
trou 2 est ouvert, elle est donnée par la courbe $I_{2}(y)$ ({numref}`fig-interOndesClass`).

```{figure} media/image26.jpg
:name: fig-interOndesClass
:alt: Ondes classiques
:width: 90%
Ondes classiques
```

Par contre lorsque les deux trous sont ouverts l\'intensité mesurée sur
l\'écran $I_{12}(y)$ ne ressemble en rien à celle qui est obtenue avec
des corpuscules classiques, c\'est-à-dire qu\'elle est très différente
de la somme des intensités mesurées avec un seul trou ouvert :

$$I_{12}(y) \neq I_{1}(y) + I_{2}(y)$$

A certains endroits on détecte moins d\'énergie avec deux trous ouverts
qu\'avec un seul trou. L\'interférence est alors destructive. La
détection de l\'énergie se fait de manière continue dans le temps et
étalée dans l\'espace.

Supposons que la source émette des électrons. Lorsqu\'un seul trou est
ouvert, on observe une distribution semblable à celle des corpuscules et
des ondes classiques. La détection se fait cependant par impacts
localisés dans l\'espace et dans le temps, ce qui porte à croire que les
électrons sont des corpuscules.

Lorsque les deux trous sont ouverts le nombre d\'électrons détectés
varie très rapidement avec la position manifestant un phénomène
d\'interférence. En fait la distribution ressemble beaucoup à la
fonction $I_{12}(y)$ représentant l\'intensité obtenue avec des ondes
classiques. Cependant la détection se fait toujours par impacts
localisés dans l\'espace et dans le temps comme pour des corpuscules.

Les deux aspects, corpusculaire et ondulatoire, se manifestent dans la
même expérience. On obtient le même type de résultats avec des photons
({numref}`fig-interOndesClass`), des neutrons ou même des atomes.

Une conséquence importante de la distribution des électrons observée
lorsque les deux trous sont ouverts <u>est qu\'il est impossible
d\'affirmer que chaque électron est passé soit par un trou soit par
l\'autre</u>. En effet, si c\'était le cas on pourrait dire que
le nombre d\'électrons reçus en chaque point est égal au nombre
d\'électrons venus par le trou 1 plus le nombre d\'électrons venus par
le trou 2. [<u>Le nombre total d\'électrons reçus en tout point lorsque
les deux trous sont ouverts ne pourrait jamais être inférieur au nombre
reçus au même point lorsqu\'un seul trou est
ouvert</u>]. Il n\'y aurait donc pas d\'interférence.

On peut essayer de déterminer par quel trou passe chaque électron en les
éclairant à l\'aide d\'une source de lumière (Figure 6).

```{figure} media/eclairFentes.png
:name: fig-eclairFentes
:alt: Eclairage des fentes
:width: 90%
Eclairage des fentes
```

L\'éclairage des trous permet effectivement de savoir par quelle fente
passe chaque électron car la charge électrique diffuse la lumière en
émettant un flash de lumière au voisinage d\'une fente mais
l\'interférence disparaît et la distribution devient identique à celle
des corpuscules classiques. Les électrons sont manifestement perturbés
par la lumière. On peut essayer d\'atténuer cette perturbation en
diminuant l\'intensité de la source de lumière. Dans ce cas elle émet
moins de photons et certains électrons ne sont pas vus. Les électrons
détectés sans qu\'un éclair soit émis possèdent une répartition
caractéristique d\'un phénomène d\'interférence. Par contre, ceux qui
ont été vus (éclair émis au voisinage d\'un des fentes) ont une
répartition semblable à celle des corpuscules classiques.

Une autre façon d\'atténuer la perturbation des électrons consiste à
diminuer l\'énergie et l\'impulsion des photons en augmentant la
longueur d\'onde de la lumière éclairante. Il est possible alors de
diminuer suffisamment la perturbation pour que la distribution des
électrons détectés manifeste à nouveau un phénomène d\'interférence.
Cependant, on trouve alors que la longueur d\'onde est trop grande pour
obtenir un pouvoir séparateur suffisant pour déterminer par quelle fente
l\'électron est passé.

En résumé, on peut dire que chaque fois qu\'une expérience permet de
déterminer par quel trou passe chaque électron, leur répartition sur
l\'écran est semblable à celle des corpuscules classiques. Sinon on
observe des interférences.

Remarquons enfin que l\'interaction entre quantons ne joue aucun rôle
dans ce genre d\'expérience. On obtient les mêmes résultats en leur
faisant traverser le dispositif un à un.

## Notion d\'amplitudes de probabilité pour caractériser l'évolution spatio-temporelle d'un système

La notion de probabilité est insuffisante pour expliquer l\'expérience
précédente car elle ne permet pas de rendre compte du phénomène
d\'interférence. En effet étant un nombre positif elle ne peut pas
diminuer lors de l\'ouverture d\'une voie supplémentaire.

Pour résoudre ce problème la théorie quantique fait appel au concept
d\'**amplitude de probabilité de transition** {index}`Amplitude de probabilité de transition`. Une telle amplitude est
un nombre complexe dont le carré du module représente la probabilité de
cette transition. En présence de deux ou plusieurs voies ou
alternatives possibles pour une transition donnée, il faut une règle
permettant de calculer les amplitudes et les probabilités. La
**superposition des amplitudes** (PSAP) {index}`Principe de superposition des amplitudes` joue un rôle capital
en théorie quantique :

**<u>Il stipule que lorsqu\'une transition peut se faire par deux ou
plusieurs alternatives en principe indiscernables, l\'amplitude totale
est la somme des amplitudes associées à chaque voie.</u>**

**<u>La probabilité est donc le carré du module de la somme des
amplitudes.</u>**

Dans le cas où une source émettrait des électrons comme dans
l\'expérience précédente on note $A_{1}$ ou $A_{2}$ l'amplitude de
probabilité pour que l\'électron aille de la source à un point de
l\'écran lorsque la seule fente $1$ ou $2$ est ouverte respectivement.
La probabilité de transition est donnée par :

$$P_{1} = A_{1}{A_{1}}^{*} = \left| A_{1} \right|^{2}$$

ou

$$P_{2} = A_{2}{A_{2}}^{*} = \left| A_{2} \right|^{2}$$

selon que c\'est la fente $1$ ou la fente $2$ qui est ouvert à
l'exclusion de l'autre.

Lorsque les deux fentes sont ouvertes et aucune expérience n\'est faite
pour déterminer par quel trou passent les électrons, les deux voies sont
indiscernables et d\'après le PSAP il faut additionner les amplitudes :

$$P_{12} = \left( A_{1} + A_{2} \right)\left( {A_{1}}^{*} + {A_{2}}^{*} \right)$$

soit :

$$P_{12} = A_{1}{A_{1}}^{*} + A_{2}{A_{2}}^{*} + {A_{1}}^{*}A_{2} + A_{1}{A_{2}}^{*}$$

ou bien :

$$P_{12} = A_{1}{A_{1}}^{*} + A_{2}{A_{2}}^{*} + 2Re\left\{ {A_{1}}^{*}A_{2} \right\}$$

Les deux premiers termes sont positifs mais le dernier peut être positif
ou négatif. Il représente l\'interférence.

Lorsque les deux voies sont en principe discernables le PSAP ne
s\'applique pas. Il **<u>faut additionner les probabilités associées à
chaque voie</u>**. On a alors :

$$P_{12} = A_{1}{A_{1}}^{*} + A_{2}{A_{2}}^{*}$$

c\'est-à-dire :

$$P_{12} = P_{1} + P_{2}$$

Dans ce cas l\'interférence disparaît.

Seule la probabilité est mesurable par l\'expérience. La phase
de l\'amplitude totale est sans importance car seul le carré de son
module est accessible à la mesure. Les probabilités sont inchangées si
toutes les amplitudes sont multipliées par un facteur $e^{i\alpha}$. Un
tel facteur est appelé **facteur de phase** {index}`Facteur de phase`.

La phase relative des amplitudes (déphasage) est cependant très
importante car c\'est elle qui détermine si l\'interférence est
constructive ou destructive. <u>La somme de deux amplitudes est maximale
(en module) lorsqu\'elles sont en phase c\'est-à-dire lorsque les
vecteurs du plan complexe qui les représentent ont la même
orientation</u>. <u>De même le module de l\'amplitude résultante
est minimal si leur déphasage est π</u> ; elles sont alors
représentées par des vecteurs opposés dans le plan complexe. Dans le
premier cas l'interférence est constructive. Toutes les situations
intermédiaires sont évidemment possibles ({numref}`fig-APPlanComplexes`).

```{figure} media/image26.png
:name: fig-APPlanComplexes
:alt: Représentation des amplitudes dans le plan complexe
:width: 90%
Sommation des AP dans le plan complexe
```

## Calcul des amplitudes et des probabilités

Pour calculer les amplitudes et les probabilités dans des situations
assez réalistes il faut définir des règles précises qui peuvent être
considérées comme les postulats de la théorie quantique.

Avant de les énoncer nous introduirons la notation de Dirac couramment
utilisée pour <u>désigner une amplitude de probabilité.</u>

L\'amplitude de probabilité de transition entre deux états s\'écrit sous
la forme :

$$\left\langle \text{final} \middle| \text{initial} \right\rangle$$

Ainsi l\'amplitude de probabilité pour qu\'un électron aille de la
source au détecteur lorsque la seule fente est ouverte 1 peut s\'écrire
:

$${A_{1} = \left\langle D \middle| S \right\rangle}_{1}$$

Pour la seule fente 2 ouverte :

$${A_{2} = \left\langle D \middle| S \right\rangle}_{2}$$

En plus du PSAP deux autres principes sont nécessaires pour permettre de
calculer les amplitudes et les probabilités.

### Principe d\'addition des probabilités

**<u>Lorsqu\'il existe plusieurs états finaux disjoints ou distincts la
probabilité de transition vers l\'ensemble de ces états est la somme des
probabilités de transition vers chacun de ces états.</u>**

Lorsqu\'une transition peut se faire par des voies intermédiaires en
principe <u>discernables, chacun de ses états peut être considéré comme
final pour une partie de la transition</u>. La règle
d\'addition des probabilités que nous avons déjà énoncée peut être
considérée comme un cas particulier du principe d\'addition des
probabilités de transition vers des états finaux distincts.

### Principe de factorisation séquentielle.

Lorsqu\'une transition s\'effectue en passant par un état intermédiaire
bien défini(s) l\'amplitude de probabilité de transition est le produit
des amplitudes associées à chaque étape de la transition :

$$\left\langle v \middle| u \right\rangle_{s} = \left\langle v \middle| s \right\rangle\left\langle s \middle| u \right\rangle$$

Dans le cas particulier de l\'expérience réalisée avec le dispositif
d\'Young la transition de la source au détecteur peut se faire par
l\'intermédiaire de l\'un ou l\'autre trou. Le principe de factorisation
séquentielle permet d\'écrire :

$${A_{1} = \left\langle D \middle| S \right\rangle}_{1} = \left\langle D \middle| 1 \right\rangle\left\langle 1 \middle| S \right\rangle$$

$${A_{2} = \left\langle D \middle| S \right\rangle}_{2} = \left\langle D \middle| 2 \right\rangle\left\langle 2 \middle| S \right\rangle$$

L\'expression $\left\langle i \middle| S \right\rangle$représente
l\'amplitude de probabilité pour que le quanton quitte la source $S$
pour arriver à la fente $i$ et $\left\langle D \middle| i \right\rangle$
représente l\'amplitude de probabilité pour qu\'il aille de la fente $i$
au détecteur.

Le type de transition intervenant dans les expériences étudiées ici est
en fait une propagation dans l\'espace-temps. Dans le cas des photons
nous pourrons donner une expression très simple. Elle expliquera ainsi
tous les phénomènes déjà expliqués par l\'optique ondulatoire et par
l\'optique géométrique.

## Propagation rectiligne de la lumière

Les photons se déplacent-ils en ligne droite dans le vide ? A première
vue la réponse semblait être positive car l'expérience quotidienne nous
permet d'observer facilement le phénomène de propagation rectiligne de
la lumière (visible). C'est d'ailleurs cette observation qui a conduit
au développement du modèle géométrique. En revanche l'existence d'une
trajectoire bien définie pour le photon est incompatible avec
l'inégalité d'Heisenberg. Comment concilier ces propriétés qui semblent
être en contradiction ?

On peut essayer de résoudre ce dilemme en faisant une expérience
appropriée :

```{figure} media/image26bis.png
:name: fig-rectilLumiere
:alt: Trajet rectiligne de la lumière
:width: 100%
Trajet rectiligne de la lumière
```

Une source de lumière S émet des photons dont certains passent à travers
une fente AB percée dans un écran opaque. Un détecteur $D_1$ est placé de
telle sorte qu'il existe des trajets rectilignes allant de la source à
ce détecteur. Un autre détecteur $D_2$ est placé de telle sorte qu'il
n'existe aucun trajet rectiligne le reliant à la source et passant par
la fente. Si le détecteur $D_1$ reçoit des photons alors que le détecteur
$D_2$ n'en reçoit aucun on dira que les photons se propagent en ligne
droite.

Supposons qu'une expérience conduise effectivement au résultat suivant :
$D_1$ reçoit des photons et $D_2$ n'en reçoit pas. C'est précisément le
critère choisi pour affirmer que les photons ont des trajectoires
rectilignes. Il faut cependant remarquer que la précision de la
trajectoire est limitée par la largeur de la fente. On ne peut pas
exclure a priori la trajectoire pointillée allant de S à $D_1$. Pour le
faire, et du même coup améliorer la précision, il faut rétrécir la
fente. L'expérience montre qu'alors le détecteur $D_2$ commence à
recevoir des photons.

Analysons cette expérience à l'aide du PSAP. Il y a un grand
nombre de chemins allant de la source au détecteur $D_2$ et passant par
la fente (mathématiquement il y en a une infinité).

A chacun de ces chemins, on associe une amplitude de probabilité dont la
phase est déterminée par le temps de parcours. selon {cite}`feynman1979` :

$$A = e^{j\theta}$$

où $\theta$ est la phase caractéristique d'un chemin quelconque qui joint un point à un autre.

```{math}
:label: eq-phiAction
\theta = \frac{S}{\hbar}
```

où $S$ est l'action associée à un chemin.

Pour un photon dans un milieu optique, l'action est proportionnelle au chemin optique qui est lui même la longueur du trajet multipliée par l'indice du milieu.

$$ \Delta = \int{n(s)\;ds}$$

Soit :

$$ \Delta = n L$$

dans un mileu homogène.

Pour un photon, la phase accumulée sur le chemin est :

$$ \Phi = k_0 \Delta$$

où $k_0 = 2\pi/\lambda_0$ est le nombre d'onde dans le vide et $\lambda_0$ la longueur d'onde dans le vide.

Ainsi d'après la formulation {eq}`eq-phiAction` l'action $S$ est :

$$S=\hbar \Phi=\hbar k_0 n L==\hbar k L$$

Les différents chemins étant indiscernables, il faut
additionner les différentes amplitudes associées à chaque trajet pour
obtenir l'amplitude résultante dont le carré du module est proportionnel
à la probabilité de recevoir un photon.

Les chemins ayant une longueur différentes, la phase accumulée n'est pas la même. Il existe donc un déphasage entre les amplitudes associées à chaque chemin.

Si la somme des amplitudes est
nulle dans une direction donnée (θ) de $D_2$, il est clair que $D_2$ ne
reçoit aucun photon. Nous allons essayer d'estimer la plus petite
valeur de θ compatible avec cette condition.

Remarquons d'abord que si la différence de phase entre les amplitudes
associées aux chemins extrêmes ne dépasse pas π , la somme des
amplitudes ne peut pas être nulle {numref}`fig-PSAPPhotons`. Si
d est la largeur de la fente, la différence de marche entre le chemin le
plus court et le chemin le
plus long est $d\;\sin\theta$. Le déphasage entre les deux phases accumulées est donc :

$$\Delta \phi= k d \sin\theta$$


```{figure} media/image27.png
:name: fig-PSAPPhotons
:alt: PSAP de propagation des photons
:width: 70%
PSAP de propagation des photons
```

La condition nécessaire pour que $D_2$ ne reçoive pas de photons est donc que $\mathrm{\Delta}\phi$ dépasse $\pi$

soit :
(36) $d \sin{\theta_{\min}} = \frac{\lambda}{2}$

L'angle $\theta_{\min}$ le plus petit au-delà duquel que $D_2$ ne reçoit
aucun photon est donc :

$$\sin{\theta_{\min}} = \frac{\lambda}{2d}$$

Des photons arrivent donc dans toutes les directions comprises entre
$+ \theta_{\min}$ et $- \theta_{\min}$. Si on diminue la largeur de la
fente pour améliorer la précision sur la trajectoire la dispersion
angulaire augmente. Ce phénomène est connu en optique sous le nom de
diffraction de la lumière. Cette expérience nous montre que la
trajectoire des photons [n'est pas bien définie car le fait de bien
préciser leur position rend leur impulsion indéterminée].

En multipliant par la constante de Planck chaque côté de l'égalité
précédente (1) on a :

$${d\frac{h}{\lambda}\sin}{\theta_{\min} = \frac{h}{2}}$$

soit :

(37) ${dp\sin}{\theta_{\min} = \frac{h}{2}}$

L'extension en impulsion est donnée par :

$${\Delta p_{y} = p\sin}\theta_{\min}$$

et l'extension spatiale par :

$${\Delta y =}d$$

On retrouve donc la valeur inférieure de l'inégalité d'Heisenberg :

$$\Delta y\Delta p_{y} = \frac{h}{2}$$

Cette inégalité découle du PSAP.

Ainsi, si on cherche à déterminer la position du photon avec une grande
précision pour montrer que sa trajectoire est rectiligne on trouve qu'il
a une probabilité non nulle d'arriver dans le détecteur $D_2$, ce qui
montre bien que sa trajectoire n'est pas rectiligne et donc que [des
trajets non rectilignes sont des alternatives dont il faut considérer
l'AP].

On peut également interpréter ce résultat à l'aide du PSAP. La
différence de marche entre les chemins extrêmes devient plus grande
lorsque la fente est élargie. La différence de phase des amplitudes
associées devient assez grande pour que l'amplitude résultante s'annule.
Il est clair que c'est l\'interférence entre les amplitudes de
probabilité qui annule la probabilité pour qu'un photon arrive sur $D_2$.

 [41]: L'intensité se déduit du module de vecteur de Poynting
    $\left( \overrightarrow{E} \land \overrightarrow{B} \right)/\mu_{0}$
    qui correspond à la quantité d'énergie qui traverse pendant une
    seconde une unité de surface perpendiculaire à la direction de
    propagation $\overrightarrow{k}$. En moyennant sur une période,
    cette quantité définit l'intensité du rayonnement.

 [42]: La polarisation peut être obtenue par réflexion sur une surface
    vitreuse (diélectrique) à l'angle de Brewster : la lumière réfléchie
    est totalement polarisée rectilignement dans une direction
    perpendiculaire au plan d'incidence (plan contenant la direction du
    faisceau incident et la normale à la surface vitreuse. Elle peut
    être obtenue par réfraction (biréfringence liée à l'anisotropie
    optique d'un corps) ou au moyen de cristaux optiques uniaxe ou
    biaxes.
