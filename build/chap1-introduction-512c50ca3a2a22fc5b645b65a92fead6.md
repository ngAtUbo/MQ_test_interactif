Ã¯Â»Â¿---
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
# Origine de la mÃƒÆ’Ã‚Â©canique quantique

A la fin du 19ÃƒÆ’Ã‚Â¨me siÃƒÆ’Ã‚Â¨cle, la physique dite classique formait un tout
cohÃƒÆ’Ã‚Â©rent qui suffisait ÃƒÆ’Ã‚Â  expliquer la plupart des phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes physiques
observÃƒÆ’Ã‚Â©s notamment de l'ÃƒÆ’Ã‚Â©chelle macroscopique ÃƒÆ’Ã‚Â  l'ÃƒÆ’Ã‚Â©chelle cÃƒÆ’Ã‚Â©leste. Les
lois de [Newton](wiki:Isaac_Newton) [1] rÃƒÆ’Ã‚Â©gissent le mouvement des corps tandis que le
rayonnement est dÃƒÆ’Ã‚Â©crit par la thÃƒÆ’Ã‚Â©orie de Maxwell de l\'ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tisme
(dÃƒÆ’Ã‚Â¨s 1865) intÃƒÆ’Ã‚Â©grant la notion de champs introduite par Faraday. La
thermodynamique formalisÃƒÆ’Ã‚Â©e par [Clausius](wiki:Rudolf_Clausius) (1850) puis la physique
statistique introduite par la thÃƒÆ’Ã‚Â©orie cinÃƒÆ’Ã‚Â©tique des gaz de Maxwell [2]
et Botzmann [3] explique le comportement et l'ÃƒÆ’Ã‚Â©volution de systÃƒÆ’Ã‚Â¨mes
physiques composÃƒÆ’Ã‚Â©s d'un trÃƒÆ’Ã‚Â¨s grand nombre de particules.

L\'idÃƒÆ’Ã‚Â©e selon laquelle la matiÃƒÆ’Ã‚Â¨re est composÃƒÆ’Ã‚Â©e de constituants premiers
de trÃƒÆ’Ã‚Â¨s petite taille appelÃƒÆ’Ã‚Â©s atome (*a* exprime la nÃƒÆ’Ã‚Â©gation en grec et
*tomos* sÃƒÆ’Ã‚Â©cable) au regard de la matiÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â  son ÃƒÆ’Ã‚Â©chelle macroscopique
remonte ÃƒÆ’Ã‚Â  l\'antiquitÃƒÆ’Ã‚Â© grecque (DÃƒÆ’Ã‚Â©mocrite [4]). Cependant cette
hypothÃƒÆ’Ã‚Â¨se n'avait aucun fondement expÃƒÆ’Ã‚Â©rimental et correspondait ÃƒÆ’Ã‚Â  une
maniÃƒÆ’Ã‚Â¨re conceptuelle d'apprÃƒÆ’Ã‚Â©hender la matiÃƒÆ’Ã‚Â¨re en constituants premiers.
L'hypothÃƒÆ’Ã‚Â¨se atomique chemine du 18ÃƒÆ’Ã‚Â¨me au 19ÃƒÆ’Ã‚Â¨me siÃƒÆ’Ã‚Â¨cle notamment par
les travaux de la chimie pour ÃƒÆ’Ã‚Âªtre confortÃƒÆ’Ã‚Â©e par la thÃƒÆ’Ã‚Â©orie cinÃƒÆ’Ã‚Â©tique
des gaz dans laquelle des grandeurs physiques macroscopiques en nombre
limitÃƒÆ’Ã‚Â© telles que la pression, la tempÃƒÆ’Ã‚Â©rature et le volume sont le
reflet des caractÃƒÆ’Ã‚Â©ristiques des mouvements chaotiques des particules
individualisÃƒÆ’Ã‚Â©es (atomes, molÃƒÆ’Ã‚Â©cules) qui composent le gaz. Ces particules
ÃƒÆ’Ã‚Â©taient trop petites pour ÃƒÆ’Ã‚Âªtre vues. C'est bien les grands nombres
(chocs par seconde) relatifs ÃƒÆ’Ã‚Â  ces particules qui produisent des effets
macroscopiques mesurables tout en masquant le caractÃƒÆ’Ã‚Â¨re fondamental
individuel d'une particule constituant le gaz.

MalgrÃƒÆ’Ã‚Â© la conviction de l'existence des atomes, il a fallu attendre le
dÃƒÆ’Ã‚Â©but du 20ÃƒÆ’Ã‚Â¨me siÃƒÆ’Ã‚Â¨cle pour voir publier les premiÃƒÆ’Ã‚Â¨res propositions de
modÃƒÆ’Ã‚Â¨le d'atomes par Joseph John Thomson [5] (dÃƒÆ’Ã‚Â©couverte de l'ÃƒÆ’Ã‚Â©lectron en
1897 et prix Nobel en 1906) Jean Perrin [6] (modÃƒÆ’Ã‚Â¨le planÃƒÆ’Ã‚Â©taire de
l'atome et prix Nobel en 1926).

A la fin du 19ÃƒÆ’Ã‚Â¨me siÃƒÆ’Ã‚Â¨cle, l'ÃƒÆ’Ã‚Â©tude des ÃƒÆ’Ã‚Â©changes d'ÃƒÆ’Ã‚Â©nergie entre la
matiÃƒÆ’Ã‚Â¨re et le rayonnement produit l'hypothÃƒÆ’Ã‚Â¨se de la quantification des
ÃƒÆ’Ã‚Â©changes d'ÃƒÆ’Ã‚Â©nergie produit par Planck en 1900.

Les travaux d'[Einstein](wiki:Albert_Einstein) (quantification de l'ÃƒÆ’Ã‚Â©nergie ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tique et
prix Nobel en 1921) notamment sur l'effet photoÃƒÆ’Ã‚Â©lectrique, de Niels Bohr
(quantification de Bohr et prix Nobel en 1922) puis de Louis de Broglie
(longueur d'onde de la matiÃƒÆ’Ã‚Â¨re et prix Nobel en 1929), d'Erwin
SchrÃƒÆ’Ã‚Â¶dinger (ÃƒÆ’Ã‚Â©quation d'ÃƒÆ’Ã‚Â©volution temporelle et prix Nobel en 1933), de
Wolfgang Pauli (principe d'exclusion de Pauli et prix Nobel en 1945) et
de Max Born (interprÃƒÆ’Ã‚Â©tation probabiliste du module au carrÃƒÆ’Ã‚Â© de la
fonction d'onde et prix Nobel en 1954) ÃƒÆ’Ã‚Â©tablirent les bases d\'une
thÃƒÆ’Ã‚Â©orie nouvelle connue aujourd\'hui sous le nom de **mÃƒÆ’Ã‚Â©canique
quantique** (ou physique quantique).

L\'ÃƒÆ’Ã‚Â©chelle des expÃƒÆ’Ã‚Â©riences et phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes dÃƒÆ’Ã‚Â©crit par la physique
quantique est celle de l\'atome, de la molÃƒÆ’Ã‚Â©cule ou plus petit (ÃƒÆ’Ã‚Â©chelle
sub-atomique). La matiÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â©tant constituÃƒÆ’Ã‚Â©e d\'atomes, toute la physique
fondamentale dÃƒÆ’Ã‚Â©coule plus ou moins directement des concepts fondamentaux
de la physique quantique.

Le terme ***quantique*** se dit de ce qui se rapporte aux quanta [7]
pluriel du mot {index}`quantum` exprimant ÃƒÆ’Ã‚Â  la fois
une quantitÃƒÆ’Ã‚Â© dÃƒÆ’Ã‚Â©terminÃƒÆ’Ã‚Â©e et ÃƒÆ’Ã‚Â©galement la plus petite quantitÃƒÆ’Ã‚Â© physique
susceptible d\'ÃƒÆ’Ã‚Âªtre ÃƒÆ’Ã‚Â©changÃƒÆ’Ã‚Â©e.

Il est parfois tentant d\'assimiler la thÃƒÆ’Ã‚Â©orie classique ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©tude des
objets de l\'infiniment grand ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©chelle macroscopique et de limiter
la nÃƒÆ’Ã‚Â©cessitÃƒÆ’Ã‚Â© de la thÃƒÆ’Ã‚Â©orie quantique ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©tude de phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes
\"exotiques\" ayant lieu ÃƒÆ’Ã‚Â  l\'ÃƒÆ’Ã‚Â©chelle microscopique. Cette idÃƒÆ’Ã‚Â©e
abusivement simplificatrice irait ÃƒÆ’Ã‚Â  l\'encontre de ce qu\'est la place
de la physique quantique dans notre monde moderne aussi bien au travers
d\'objets et de technologies courantes (lasers, transistors,
supraconducteur) qu\'au travers d\'instruments de diagnostic et
d\'investigation modernes (RMN [8], RPE [9], IRM [10], microscope ÃƒÆ’Ã‚Â 
effet Tunnel pour ne citer que les plus connus).


 [1]: Isaac Newton (1643-1727) : philosophe, mathÃƒÆ’Ã‚Â©maticien, physicien et
    astronome connu pour ses travaux relatant tous les fondements
    principaux de la mÃƒÆ’Ã‚Â©canique classique : ÃƒÆ’Ã‚Â©galitÃƒÆ’Ã‚Â© de l\'action et de la
    rÃƒÆ’Ã‚Â©action, principe d\'inertie, et surtout loi de gravitation
    universelle.

 [2]: James Clerk Maxwell (1831-1879) : physicien ÃƒÆ’Ã‚Â©cossais nÃƒÆ’Ã‚Â© ÃƒÆ’Ã‚Â 
    Edimbourg connu pour l\'ÃƒÆ’Ã‚Â©dification de l\'ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tisme. Il fut
    un pionnier de la ThÃƒÆ’Ã‚Â©orie cinÃƒÆ’Ã‚Â©tique des gaz.

 [3]: Ludwig Botzmann (1844-1906) : physicien autrichien nÃƒÆ’Ã‚Â© ÃƒÆ’Ã‚Â  Vienne
    prÃƒÆ’Ã‚Â©curseur de la physique moderne. Il est le pÃƒÆ’Ã‚Â¨re fondateur de la
    physique statistique. On lui doit le principe de l\'irrÃƒÆ’Ã‚Â©versibilitÃƒÆ’Ã‚Â©
    du monde rÃƒÆ’Ã‚Â©el et sa formulation en termes d\'entropie et de second
    principe.

 [4]: DÃƒÆ’Ã‚Â©mocrite (460-370 av JC) : philosophe grec nÃƒÆ’Ã‚Â© ÃƒÆ’Ã‚Â  AbdÃƒÆ’Ã‚Â¨re.

 [5]: Joseph John Thomson (1856-1940) : physicien anglais ÃƒÆ’Ã‚Â  l'origine de
    la dÃƒÆ’Ã‚Â©couverte de l'ÃƒÆ’Ã‚Â©lectron (1897), des isotopes et de la
    spectromÃƒÆ’Ã‚Â©trie de masse. Il reÃƒÆ’Ã‚Â§oit le prix Nobel de Physique en 1906
    pour ses travaux sur la conductivitÃƒÆ’Ã‚Â© ÃƒÆ’Ã‚Â©lectrique dans les gaz.

 [6]: Jean Baptiste Perrin (1870-1942) a reÃƒÆ’Ã‚Â§u le prix Nobel en 1926 pour
    ses travaux sur le mouvement brownien (ÃƒÆ’Ã‚Â©tude du mouvement dÃƒÆ’Ã‚Â©sordonnÃƒÆ’Ã‚Â©
    du grosse particule dont le diamÃƒÆ’Ã‚Â¨tre est de l'ordre du micron
    immergÃƒÆ’Ã‚Â© dans un fluide rÃƒÆ’Ã‚Â©vÃƒÆ’Ã‚Â©lant l'agitation molÃƒÆ’Ã‚Â©culaire rÃƒÆ’Ã‚Â©gnant dans
    un fluide) conduisant ÃƒÆ’Ã‚Â  la premiÃƒÆ’Ã‚Â¨re dÃƒÆ’Ã‚Â©termination prÃƒÆ’Ã‚Â©cise du nombre
    d'Avogadro $N_A$.

 [7]: pluriel du mot quantum

 [8]: RÃƒÆ’Ã‚Â©sonance magnÃƒÆ’Ã‚Â©tique nuclÃƒÆ’Ã‚Â©aire.

 [9]: RÃƒÆ’Ã‚Â©sonance ParamagnÃƒÆ’Ã‚Â©tique ÃƒÆ’Ã‚Â©lectronique.

 [10]: Imagerie par rÃƒÆ’Ã‚Â©sonance magnÃƒÆ’Ã‚Â©tique.

