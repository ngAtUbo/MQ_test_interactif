(chap-corrections)=
# Corrections des exercices


* chapitre {ref}`chap-intro`
* chapitre {ref}`chap-ondesClass`

    :::{solution} exo-propag-xpositif
    :label: solExo-propag-xpositif
    :class: dropdown
    1. $x'=x -\frac{w}{k}dt$
    1. sens : vers les $x$ positifs
    :::


* chapitre {ref}`chap-lumiere`

    :::{solution} exo-absorption
    :label: solexo-absorption
    :class: dropdown
    $h\nu$ étant une quantité positive, $+\left(E_f-E_i\right)$ est par voie de conséquence positive. Les énergies étant négatives, cela implique que l'énergie $|E_i|>|E_f|$ est donc que l'énergie finale du fait de l'absorption du photon est plus grande que l'énergie intiale.
    :::

    :::{solution} exo-dim-hbar
    :label: solexo-dim-hbar
    :class: dropdown
    $\left[ \hbar \right] = M L^2 T^{-1}$
    :::

    :::{solution} exo-rapport-gravCoul
    :label: solexo-rapport-gravCoul
    :class: dropdown
    :::

    :::{solution} exo-const-rydb
    :label: solexo-const-rydb
    :class: dropdown
    $\frac{m_e e^{4}}{8\epsilon_{0}^{2}h^{3}c}$
    :::

* chapitre {ref}`chap-fondements`

    :::{solution} exo-gaussienne
    :label: solexo-gaussienne
    :class: dropdown

    1. $\left\langle|x| \right\rangle = \int_{-\infty}^{+-\infty}|x|\rho(x)dx = \frac{2}{\sigma\sqrt{2\pi}}\int_{0}^{+-\infty}x\exp \left(\frac{-x^{2}}{2\sigma^2}\right) dx$  
    soit (après changement de variable) :  
    $\left\langle|x| \right\rangle = \sigma\sqrt{\frac{2}{\pi}}$

    1. $\sqrt{\frac{2}{\pi}} \approx 0,8$

    :::

* chapitre {ref}`chap-APetP`


    :::{solution} exo-Ap-P
    :label: solexo-Ap-P
    :class: dropdown

    1. $\left| \alpha \right|^{2} = 5$

    1. $\left| \alpha \right|^{2} = 5$ n'est pas une probabilité qui doit être comprise entre $0$ et $1$.

    1. Si on prend $\left| N \alpha \right|^{2} = 1$ alors $\left| N \alpha \right|^{2} = \left| N \right|^{2} \left|\alpha \right|^{2} = 1$ donne $\left| N \alpha \right| = \frac{1}{\sqrt{5}}$

    :::


    :::{solution} exo-2-Ap
    :label: solexo-2-Ap
    :class: dropdown

    1. $\alpha^{*} \beta = -1 -5i$ 

    1. Interprétation : $\alpha^{*} \beta$ peut correspondre au produit scalaire de deux états de l'espace des états $\epsilon$ de dimension $1$.

    1. $\left| \alpha^{*} \beta \alpha \right| = 26$. L'angle de référence est $\arctan{5/1}$ et le l'argument est dans le troisième quadrant donc $\arg(\alpha^{*} \beta) = \pi +\arctan{5/1}$.
    :::

    :::{solution} exo-Ap-composee
    :label: solexo-Ap-composee
    :class: dropdown

    1. $\Re (A)= 2 \cos{\pi} - \sin{\pi} +1$ et $\Im (A)= 2 \sin{\pi} + \cos{\pi} - 1$

    1. $\left| A \right|^{2} = 9$ pour $\phi = 0$.

    1. $\left| A \right|^{2} = 1$ pour $\phi = \pi /2$. 
    1. $\left| A \right|^{2} = 5$ pour $\phi = \pi$.

    1. Pour $\phi = 0$ les contributions s’ajoutent fortement (probabilité relative maximale). Pour $\phi = \pi /2$, l’interférence est moins constructive, la probabilité est plus faible.
    :::


* chapitre {ref}`chap-etatsQ`

    :::{solution} exo-ket-bra
    :label: solExo-ket-bra
    :class: dropdown

    * $\left\langle \Psi \right| = 3 \left\langle 0 \right|+i\left\langle 1\right|$ 

    * $\left\langle \phi \right| = \alpha^{*} \left\langle 0 \right|+ \beta^{*} \left\langle 1\right|$ 

    * $\left\langle \psi \right| = (2+i)\alpha^{*} \left\langle 0 \right|+ (1-3i) \beta^{*} \left\langle 1\right|$ 
    :::

    :::{solution} exo-bra-ket
    :label: solExo-bra-ket
    :class: dropdown

    * $\left| w \right\rangle = (1-i) \left| 0 \right\rangle - 4  \left| 1 \right\rangle$

    * $\left| u \right\rangle = a \left| 0 \right\rangle + ib \left| 1 \right\rangle$
    :::

    :::{solution} exo-repr-adjoint
    :label: solExo-repr-adjoint
    :class: dropdown

    1. ${\widehat{A}}^{\dagger}_{\mathcal{B}} = \begin{pmatrix}
    2 & i & 0 \\
    -i & 0 & -3 \\
    0 & 3 & -1
    \end{pmatrix}$

    1. ${\widehat{B}}^{\dagger}_{\mathcal{B}} = \begin{pmatrix}
    2 & i & 0 \\
    -i & 0 & 3 \\
    0 & 3 & -1
    \end{pmatrix}$

    1. ${\widehat{C}}^{\dagger}_{\mathcal{B}} = \begin{pmatrix}
    2 & i & 0 \\
    -i & a - ib & 3i \\
    0 & -3i & -1
    \end{pmatrix}\; $ où $a, b \in \mathbb{R}$

    1. ${\widehat{D}}^{\dagger}_{\mathcal{B}} = \begin{pmatrix}
    2 & 2 & 0 \\
    2 & a & 3i \\
    0 & -3i & -1
    \end{pmatrix}\; $ où $a, b \in \mathbb{R}$

    1. ${\widehat{E}}^{\dagger}_{\mathcal{B}} = \begin{pmatrix}
    b^{*} & 2 & 0 \\
    2 & a^{*} & 3i \\
    0 & -3i & -1
    \end{pmatrix}\; $ où $a, b \in \mathbb{C}$
    :::

    :::{solution} exo-op-hermi
    :label: solExo-op-hermi
    :class: dropdown

    1. non
    1. non
    1. non
    1. oui
    :::

    :::{solution} exo-prodmat-adjoint
    :label: solExo-prodmat-adjoint
    :class: dropdown

    1. $\widehat{E} \left| \phi \right\rangle =\begin{pmatrix}
    b \alpha + 2\beta  \\
    2 \alpha + a\beta + 3i\gamma\\
    -3i\beta+\gamma
    \end{pmatrix}$

    1. $\begin{pmatrix}
    b^{*} \alpha^{*} + 2\beta^{*} & 2 \alpha^{*} + a^{*}\beta^{*} - 3i\gamma^{*} & 3i\beta^{*}+\gamma^{*}
    \end{pmatrix}$
    1. $\begin{pmatrix}
    b^{*} \alpha^{*} + 2\beta^{*} & 2 \alpha^{*} + a^{*}\beta^{*} - 3i\gamma^{*} & 3i\beta^{*}+\gamma^{*}
    \end{pmatrix}$
    1. identiques
    :::

    :::{solution} exo-decomp-spect
    :label: solExo-decomp-spect
    :class: dropdown

    1. $\mathcal{det}\left( \widehat{A} - \lambda \widehat{I} \right)=\left( 2-\lambda\right)\left(\lambda^2-5\lambda+4\right)=\left( 2-\lambda\right)\left(\lambda-1\right)\left(\lambda-4\right)$

    1. $\lambda_1=4$,  $\lambda_2=2$ et $\lambda_3=1$

    1. $\left| v_{1} \right\rangle_{\left\{ \left| e_{i} \right\rangle \right\}} = \frac{1}{\sqrt{3}} \begin{pmatrix}
    1 \\
    -1 \\
    1
    \end{pmatrix}$, $\left| v_{2} \right\rangle_{\left\{ \left| e_{i} \right\rangle \right\}} = \frac{1}{\sqrt{2}} \begin{pmatrix}
    1 \\
    0 \\
    -1
    \end{pmatrix}$ et $\left| v_{3} \right\rangle_{\left\{ \left| e_{i} \right\rangle \right\}} = \frac{1}{\sqrt{6}} \begin{pmatrix}
    1 \\
    2 \\
    1
    \end{pmatrix}$

    1. ${\widehat{A}}_{\left\{ \left| v_{i} \right\rangle \right\}} = \begin{pmatrix}
    4 & 0 & 0 \\
    0 & 2 & 0 \\
    0 & 0 & 1
    \end{pmatrix}$

    :::

* chapitre {ref}`chap-evolutionT`