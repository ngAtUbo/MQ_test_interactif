Ã¯Â»Â¿---
title: "Origine de la mÃƒÆ’Ã‚Â©canique quantique"
description: "Contexte historique et limites de la physique classique ÃƒÆ’Ã‚Â  la fin du XIXe siÃƒÆ’Ã‚Â¨cle."
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
# Origine de la mÃƒÆ’Ã‚Â©canique quantique

A la fin du 19ÃƒÆ’Ã‚Â¨me siÃƒÆ’Ã‚Â¨cle, la physique dite classique formait un tout
cohÃƒÆ’Ã‚Â©rent qui suffisait ÃƒÆ’Ã‚Â  expliquer la plupart des phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes physiques
observÃƒÆ’Ã‚Â©s notamment de l'ÃƒÆ’Ã‚Â©chelle macroscopique ÃƒÆ’Ã‚Â  l'ÃƒÆ’Ã‚Â©chelle cÃƒÆ’Ã‚Â©leste. Les
lois de [Newton](wiki:Isaac_Newton)  rÃƒÆ’Ã‚Â©gissent le mouvement des corps tandis que le
rayonnement est dÃƒÆ’Ã‚Â©crit par la thÃƒÆ’Ã‚Â©orie de Maxwell de l\'ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tisme
(dÃƒÆ’Ã‚Â¨s 1865) intÃƒÆ’Ã‚Â©grant la notion de champs introduite par [Faraday](wiki:Michael_Faraday). La
thermodynamique formalisÃƒÆ’Ã‚Â©e par [Clausius](wiki:Rudolf_Clausius) (1850) puis la physique
statistique introduite par la thÃƒÆ’Ã‚Â©orie cinÃƒÆ’Ã‚Â©tique des gaz de [Maxwell](wiki:James_Clerk_Maxwell) 
et [Botzmann](wiki:Ludwig_Boltzmann)  explique le comportement et l'ÃƒÆ’Ã‚Â©volution de systÃƒÆ’Ã‚Â¨mes
physiques composÃƒÆ’Ã‚Â©s d'un trÃƒÆ’Ã‚Â¨s grand nombre de particules.

L\'idÃƒÆ’Ã‚Â©e selon laquelle la matiÃƒÆ’Ã‚Â¨re est composÃƒÆ’Ã‚Â©e de constituants premiers
de trÃƒÆ’Ã‚Â¨s petite taille appelÃƒÆ’Ã‚Â©s atome (*a* exprime la nÃƒÆ’Ã‚Â©gation en grec et
*tomos* sÃƒÆ’Ã‚Â©cable) au regard de la matiÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â  son ÃƒÆ’Ã‚Â©chelle macroscopique
remonte ÃƒÆ’Ã‚Â  l\'antiquitÃƒÆ’Ã‚Â© grecque ([DÃƒÆ’Ã‚Â©mocrite](wiki:DÃƒÆ’Ã‚Â©mocrite)). Cependant cette
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
modÃƒÆ’Ã‚Â¨le d'atomes par [Joseph John Thomson](wiki:Joseph_John_Thomson) (dÃƒÆ’Ã‚Â©couverte de l'ÃƒÆ’Ã‚Â©lectron en
1897 et prix Nobel en 1906) [Jean Perrin](wiki:Jean_Perrin)  (modÃƒÆ’Ã‚Â¨le planÃƒÆ’Ã‚Â©taire de
l'atome et prix Nobel en 1926).

A la fin du 19ÃƒÆ’Ã‚Â¨me siÃƒÆ’Ã‚Â¨cle, l'ÃƒÆ’Ã‚Â©tude des ÃƒÆ’Ã‚Â©changes d'ÃƒÆ’Ã‚Â©nergie entre la
matiÃƒÆ’Ã‚Â¨re et le rayonnement produit l'hypothÃƒÆ’Ã‚Â¨se de la quantification des
ÃƒÆ’Ã‚Â©changes d'ÃƒÆ’Ã‚Â©nergie produit par Planck en 1900.

Les travaux d'[Einstein](wiki:Albert_Einstein) (quantification de l'ÃƒÆ’Ã‚Â©nergie ÃƒÆ’Ã‚Â©lectromagnÃƒÆ’Ã‚Â©tique et
prix Nobel en 1921) notamment sur l'effet photoÃƒÆ’Ã‚Â©lectrique, de [Niels Bohr](wiki:Niels_Bohr)
(quantification de Bohr et prix Nobel en 1922) puis de [Louis de Broglie](wiki:Louis_de_Broglie)
(longueur d'onde de la matiÃƒÆ’Ã‚Â¨re et prix Nobel en 1929), d'[Erwin
SchrÃƒÆ’Ã‚Â¶dinger](wiki:Erwin_SchrÃƒÆ’Ã‚Â¶dinger) (ÃƒÆ’Ã‚Â©quation d'ÃƒÆ’Ã‚Â©volution temporelle et prix Nobel en 1933), de
[Wolfgang Pauli](wiki:Wolfgang_Pauli) (principe d'exclusion de Pauli et prix Nobel en 1945) et
de [Max Born](wiki:Max_Born) (interprÃƒÆ’Ã‚Â©tation probabiliste du module au carrÃƒÆ’Ã‚Â© de la
fonction d'onde et prix Nobel en 1954) ÃƒÆ’Ã‚Â©tablirent les bases d\'une
thÃƒÆ’Ã‚Â©orie nouvelle connue aujourd\'hui sous le nom de **mÃƒÆ’Ã‚Â©canique
quantique** (ou physique quantique).

L'ÃƒÆ’Ã‚Â©chelle des expÃƒÆ’Ã‚Â©riences et phÃƒÆ’Ã‚Â©nomÃƒÆ’Ã‚Â¨nes dÃƒÆ’Ã‚Â©crit par la physique
quantique est celle de l'atome, de la molÃƒÆ’Ã‚Â©cule ou plus petit (ÃƒÆ’Ã‚Â©chelle
sub-atomique). La matiÃƒÆ’Ã‚Â¨re ÃƒÆ’Ã‚Â©tant constituÃƒÆ’Ã‚Â©e d'atomes, toute la physique
fondamentale dÃƒÆ’Ã‚Â©coule plus ou moins directement des concepts fondamentaux
de la physique quantique.

Le terme ***quantique*** se dit de ce qui se rapporte aux quanta [^1]
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
d\'investigation modernes (RMN [^2], RPE [^3], IRM [4], microscope ÃƒÆ’Ã‚Â 
effet Tunnel pour ne citer que les plus connus).


 [^1]: pluriel du mot quantum

 [^2]: RÃƒÆ’Ã‚Â©sonance magnÃƒÆ’Ã‚Â©tique nuclÃƒÆ’Ã‚Â©aire.

 [^3]: RÃƒÆ’Ã‚Â©sonance ParamagnÃƒÆ’Ã‚Â©tique ÃƒÆ’Ã‚Â©lectronique.

 [^4]: Imagerie par rÃƒÆ’Ã‚Â©sonance magnÃƒÆ’Ã‚Â©tique.

