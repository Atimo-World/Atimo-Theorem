# Théorème d'Atimo v3.0 — Cadre de modèle généralement covariant avec couplage disformal dans le cadre de Jordan, approche d'écrantage post-newtonienne et fermeture phénoménologique ouverte

**Auteur:** Roberto Weinhold (Atimo)
**Version:** 3.0 (Version majeure consolidée)
**Date:** 10 juin 2026
**Statut:** Cadre de modèle heuristique et covariant / Programme de recherche de preprints
**Base conceptuelle:** Relation scalaire-tensorielle disformale dans le cadre de Jordan avec mise à l'échelle explicite du champ, évaluation de la limite post-newtonienne et infrastructure d'écrantage cinétique
**Licence:** CC BY 4.0

---

## Résumé

La version 3.0 du Théorème d'Atimo formule le premier cadre de modèle consolidé et généralement covariant pour étudier l'émergence métrique basée sur des champs d'information. Le champ scalaire sans dimension $I$ est intégré dans une action du cadre d'Einstein via une échelle de champ explicite $M_I$, tandis que la matière et le rayonnement se couplent à une métrique du cadre de Jordan couplée disformalement $\tilde{g}_{\mu\nu}$. En passant à une relation disformale, l'invariance purement conforme des géodésiques nulles est levée, fournissant un mécanisme formel pour l'étude quantitative des effets de lentille gravitationnelle.

À travers une expansion paramétrée en champ faible, un régime limite mathématique est identifié dans lequel le secteur disformal est localement supprimé, permettant de récupérer la valeur de la relativité générale $\gamma_{\text{PPN}} = 1$ comme une condition de cohérence requise dans le contexte des limites expérimentales de Cassini. Une approche d'écrantage cinétique inspirée de la k-essence est proposée comme un mécanisme candidat pour supprimer les gradients scalaires près des sources massives. Les écarts à l'échelle galactique sont traités comme une limite cible phénoménologique asymptotique, dont la fermeture non linéaire exacte reste ouverte pour des travaux futurs.

---

## 1. Action complète et dynamique covariante

Pour déterminer la dynamique de la géométrie de l'espace-temps et du champ d'information scalaire sans dimension $I$ d'une manière mathématiquement cohérente et dimensionnellement saine, le modèle est défini par une intégrale d'action dans le cadre d'Einstein en utilisant la signature de Lorentz $(-, +, +, +)$. Pour préserver la cohérence d'échelle, l'échelle de champ caractéristique $M_I$ est introduite :

$$S = \int d^4x \sqrt{-g} \left[ \frac{M_{\text{Pl}}^2}{2} R - \frac{M_I^2}{2} g^{\mu\nu} \nabla_\mu I \nabla_\nu I - V(I) \right] + S_m[\psi, \tilde{g}_{\mu\nu}]$$

Ici, $M_{\text{Pl}}$ est la masse de Planck réduite, $R$ est le scalaire de Ricci de la métrique gravitationnelle $g_{\mu\nu}$, $\nabla_\mu$ dénote la dérivée covariante et $g = \det(g_{\mu\nu})$, de sorte que $\sqrt{-g}d^4x$ forme l'élément de volume espace-temps covariant. En unités naturelles ($c = \hbar = 1$), le paramètre de stabilité $\lambda$ a une dimension de masse 4 (densité d'énergie), tandis que l'échelle de champ $M_I$ a une dimension de masse 1. $S_m$ représente l'action de la matière standard (champs $\psi$), qui se couple exclusivement à la métrique physique $\tilde{g}_{\mu\nu}$ (cadre de Jordan).

La variation de l'action totale par rapport au champ d'information $I$, en tenant compte du couplage disformal de la matière, produit l'équation de champ généralement covariante et cohérente :

$$\Box_g I - \frac{1}{M_I^2}\frac{dV}{dI} = Q_m$$

où $\Box_g = g^{\mu\nu} \nabla_\mu \nabla_\nu$ représente l'opérateur de d'Alembert. Le terme de source de matière effective $Q_m$ est défini via la dérivée variationnelle de l'action de la matière dans le cadre de Jordan par rapport au champ scalaire :

$$Q_m := -\frac{1}{M_I^2 \sqrt{-g}} \frac{\delta S_m[\psi, \tilde{g}_{\mu\nu}]}{\delta I}$$

Le potentiel de stabilité non linéaire est donné par :

$$V(I) = \lambda (I^2 - I)^2$$

avec des points stationnaires à $I=0$, $I=1/2$, et le point fixe métrique stabilisé à $I=1$.

---

## 2. Séparation disformale du cadre et conditions de cohérence (cadre de Jordan)

Pour modéliser la déviation physique de la lumière et lever l'invariance purement conforme des géodésiques nulles, nous séparons strictement la géométrie gravitationnelle ($g_{\mu\nu}$) de la géométrie physique ($\tilde{g}_{\mu\nu}$) à laquelle les champs de matière et de rayonnement se couplent. Nous définissons la métrique physique via une relation disformale dans le cadre de Jordan :

$$\tilde{g}_{\mu\nu} = g_{\mu\nu} + \gamma \cdot f(I) \nabla_\mu I \nabla_\nu I$$

où $\gamma$ est une constante de couplage dimensionnée (dimension $L^2$). Pour le régime du point fixe métrique ($I \rightarrow 1$), nous spécifions la fonction lisse via l'approche de puissance paire convergente $f(I) = (I^2 - 1)^{2n}$ avec $n \in \mathbb{N}_{>0}$, garantissant que $f(I)$ s'annule au point fixe et reste strictement non négative dans l'environnement local.

Pour l'inversibilité fondamentale de la métrique dans le cadre de Jordan, il est nécessaire que $1 - 2\gamma f(I)X \neq 0$ soit vérifié. Pour préserver la signature physique de Lorentz, l'inversibilité et la structure causale dans le secteur physique, les conditions structurelles de cohérence disformale sont supposées :

$$1 - 2\gamma \cdot f(I) X > 0$$

où $X = -\frac{1}{2} g^{\mu\nu} \nabla_\mu I \nabla_\nu I$ décrit la composante cinétique du champ. Les géodésiques nulles de la métrique physique $\tilde{g}_{\mu\nu}$ diffèrent en général de celles de la métrique gravitationnelle $g_{\mu\nu}$, puisque le terme disformal n'est pas réductible à un pur facteur d'échelle conforme. Cela établit un cadre de modèle formel à travers lequel les effets astrophysiques tels que les lentilles gravitationnelles deviennent quantitativement explorables dans les étapes ultérieures.

---

## 3. Expansion post-newtonienne du système solaire et analyse des limites disformales

Pour évaluer mathématiquement la compatibilité fondamentale du modèle avec des données d'observation précises au sein du système solaire, nous considérons une masse ponctuelle statique et sphériquement symétrique $M$ (le Soleil) au centre. La métrique de fond gravitationnelle $g_{\mu\nu}$ est paramétrée comme une métrique de Minkowski faiblement perturbée ($g_{\mu\nu} = \eta_{\mu\nu} + h_{\mu\nu}$ avec $|h_{\mu\nu}| \ll 1$).

Nous considérons le comportement du champ d'information comme une petite fluctuation autour du point fixe stable : $I(r) = 1 + \delta I(r)$. En utilisant l'approche disformale durcie, la limite linéarisée produit :

$$f(1 + \delta I) \approx (2\delta I)^{2n} \implies \lim_{\delta I \rightarrow 0} f(I) = 0$$

En substituant cela dans la relation disformale fondamentale du cadre de Jordan, on obtient :

$$\tilde{g}_{\mu\nu} = g_{\mu\nu} + \gamma \cdot (2\delta I)^{2n} \nabla_\mu (\delta I) \nabla_\nu (\delta I) \approx g_{\mu\nu}$$

Dans le formalisme post-newtonien paramétré (PPN), la composante spatiale de la métrique physique dans la limite de champ faible est définie comme $\tilde{g}_{ij} = \left(1 + 2\gamma_{\text{PPN}}\frac{GM}{c^2 r}\right)\delta_{ij}$. Étant donné que le terme d'addition disformal dans le régime de densité locale du système solaire est mathématiquement supprimé par le facteur $(2\delta I)^{2n} \rightarrow 0$, une comparaison directe des coefficients produit :

$$2\gamma_{\text{PPN}}\frac{GM}{c^2 r} = 2\frac{GM}{c^2 r} \implies \gamma_{\text{PPN}} = 1$$

Le modèle identifie ainsi un cas limite mathématique dans lequel la valeur PPN de la relativité générale $\gamma_{\text{PPN}} = 1$ est récupérée comme une condition de cohérence fondamentale. Cela démontre la compatibilité théorique avec la limite expérimentale de Cassini ($\gamma_{\text{PPN}} - 1 < 10^{-5}$) à un niveau asymptotique, tandis qu'une vérification PPN complète est réservée aux analyses numériques ultérieures.

---

## 4. Approche d'écrantage cinétique et analyse des limites phénoménologiques

Dans un vide statique et sphériquement symétrique ($T = 0$ ou $\rho = 0$ dans la limite non relativiste) près du point fixe ($I = 1$), la linéarisation de l'équation de champ pour le potentiel $V(I)$ produit une solution de Yukawa intrinsèquement de courte portée de la forme :

$$\delta I(r) \propto \frac{e^{-mr}}{r}$$

où la masse effective du champ est donnée par $m^2 = \frac{V''(1)}{M_I^2} = \frac{2\lambda}{M_I^2}$. Un couplage purement linéaire dans la limite de champ faible génère asymptotiquement un profil d'accélération newtonien classique à décroissance quadratique ($a \propto 1/r^2$).

Comme mécanisme candidat potentiel pour amortir les gradients de champ près des sources massives, une structure cinétique non linéaire (type k-essence) est proposée : $K_{\mathcal{X}}(\mathcal{X}) = 1 + \left(\frac{\mathcal{X}}{\Lambda_I^4}\right)^k$, où $\mathcal{X} := M_I^2 X$ dénote la densité cinétique mise à l'échelle. Dans le régime hypothétique de forte accélération ($\mathcal{X} \gg \Lambda_I^4$), le terme non linéaire domine l'équation de champ radiale pour le cas de test $k=1$ :

$$r^2 \cdot \left[ \frac{M_I^2 \cdot \frac{1}{2} \left(\frac{d(\delta I)}{dr}\right)^2}{\Lambda_I^4} \right] \frac{d(\delta I)}{dr} = C_{\text{Integration}} \implies \frac{d(\delta I)}{dr} \propto \frac{1}{r^{2/3}}$$

Cette mise à l'échelle mathématique sert de base théorique pour l'isolement local des effets de gravité modifiée dans les régions à haute densité, tandis que la dynamique disformale peut demeurer pertinente aux échelles cosmologiques.

Pour les échelles galactiques ($r \gg r_c$), le profil cible phénoménologique nécessite une géométrie logarithmique effective pour expliquer les courbes de rotation plates sans composante supplémentaire de matière noire dans le modèle effectif :

$$\Phi_{\text{gal}}(r) = \alpha \ln\left(1 + \frac{r}{r_c}\right) \implies a(r) = -\frac{\alpha}{r + r_c}$$

Cette transition est explicitement déclarée comme une **limite cible phénoménologique asymptotique** dans la Version 3.0. La fermeture mathématique complète de cet écart nécessite dans les futures itérations une modification non linéaire de la cinétique du champ via une fonction d'interpolation sans dimension $\mu(\mathcal{X}/\Lambda_I^4)$ sous la forme :

$$\nabla_\mu \left[ K_{\mathcal{X}}(\mathcal{X}) \nabla^\mu I \right] - \frac{1}{M_I^2}\frac{dV}{dI} = Q_m$$

ou la spécification d'une structure d'intégration logarithmique non linéaire au sein des fonctions de couplage du cadre de Jordan.

---

## 5. Contraintes de paramètres et liste de contrôle empirique

Étant donné que les modifications de la physique gravitationnelle sont extrêmement fortement restreintes par des données d'observation astrophysiques précises, la Version 3.0 définit une liste de contrôle intégrative stricte pour les simulations numériques ultérieures :

1. **Vitesse de propagation des ondes gravitationnelles:** La matrice de couplage disformal doit être contrainte de manière à ce que, dans l'espace de paramètres applicable, la vitesse de propagation des ondes gravitationnelles par rapport à la vitesse de la lumière dans le vide reste compatible avec les limites expérimentales serrées de GW170817/GRB170817A ($\Delta c_g/c \approx -3\times10^{-15}$ à $+7\times10^{-16}$).
2. **Efficacité de l'écrantage:** Les échelles $\Lambda_I$ et $M_I$ doivent être numériquement restreintes de telle sorte que les tests de précision locaux (effet Shapiro, précession du périhélie) ne soient pas violés.
3. **Observables astrophysiques:** Le couplage via la constante $\gamma$ doit être testé dans la limite intergalactique ($\mathcal{X} \ll \Lambda_I^4$) pour sa viabilité quantitative concernant des données de lentilles complexes (par exemple, l'Amas de la Balle).
