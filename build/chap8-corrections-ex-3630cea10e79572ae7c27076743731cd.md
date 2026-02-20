(chap-corrections)=
# Corrections des exercices


* chapitre {ref}`chap-intro`
* chapitre {ref}`ondesClass`
* chapitre {ref}`lumiere`
* chapitre {ref}`fondements`
* chapitre {ref}`APetP`
* chapitre {ref}`etatsQ`

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

1. npn
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

* chapitre {ref}`evolutionT`