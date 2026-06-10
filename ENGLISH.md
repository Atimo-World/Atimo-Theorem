# Atimo-Theorem v3.0 — Generally Covariant Model Framework with Disformal Jordan-Frame Coupling, Post-Newtonian Screening Approach, and Open Phenomenological Boundary Closure

**Author:** Roberto Weinhold (Atimo)
**Version:** 3.0 (Consolidated Major Release)
**Date:** June 10, 2026
**Status:** Heuristic, Covariant Model Framework / Preprint Research Program
**Conceptual Basis:** Disformal scalar-tensor relation in the Jordan frame with explicit field scaling, Post-Newtonian limit evaluation, and kinetic screening infrastructure
**License:** CC BY 4.0

---

## Abstract

Version 3.0 of the Atimo Theorem formulates the first consolidated, generally covariant model framework for investigating information-field-based metric emergence. The dimensionless scalar field $I$ is embedded within an Einstein-frame action via an explicit field scale $M_I$, while matter and radiation couple to a disformally coupled Jordan-frame metric $\tilde{g}_{\mu\nu}$. By transitioning to a disformal relation, the purely conformal invariance of null geodesics is lifted, providing a formal mechanism for the quantitative study of gravitational lensing effects.

Through a parameterized weak-field expansion, a mathematical limiting regime is identified in which the disformal sector is locally suppressed, allowing the general-relativistic value $\gamma_{\text{PPN}} = 1$ to be recovered as a required consistency condition within the context of experimental Cassini bounds. A k-essence-inspired kinetic screening ansatz is proposed as a candidate mechanism for suppressing scalar gradients near massive sources. Galactic-scale deviations are treated as an asymptotic phenomenological target limit, the exact nonlinear closure of which remains open for future work.

---

## 1. Complete Action and Covariant Dynamics

In order to determine the dynamics of spacetime geometry and the dimensionless scalar information field $I$ in a mathematically consistent and dimensionally sound manner, the model is defined via an action integral in the Einstein frame using the Lorentz signature $(-, +, +, +)$. To preserve scale consistency, the characteristic field scale $M_I$ is introduced:

$$S = \int d^4x \sqrt{-g} \left[ \frac{M_{\text{Pl}}^2}{2} R - \frac{M_I^2}{2} g^{\mu\nu} \nabla_\mu I \nabla_\nu I - V(I) \right] + S_m[\psi, \tilde{g}_{\mu\nu}]$$

Here, $M_{\text{Pl}}$ is the reduced Planck mass, $R$ is the Ricci scalar of the gravitational metric $g_{\mu\nu}$, $\nabla_\mu$ denotes the covariant derivative, and $g = \det(g_{\mu\nu})$, such that $\sqrt{-g}d^4x$ forms the covariant spacetime volume element. In natural units ($c = \hbar = 1$), the stability parameter $\lambda$ has mass dimension 4 (energy density), while the field scale $M_I$ carries mass dimension 1. $S_m$ represents the action of standard matter (fields $\psi$), which couples exclusively to the physical metric $\tilde{g}_{\mu\nu}$ (Jordan frame).

Variation of the total action with respect to the information field $I$, taking into account the disformal matter coupling, yields the consistent generally covariant field equation:

$$\Box_g I - \frac{1}{M_I^2}\frac{dV}{dI} = Q_m$$

where $\Box_g = g^{\mu\nu} \nabla_\mu \nabla_\nu$ represents the d'Alembert operator. The effective matter source term $Q_m$ is defined via the variational derivative of the Jordan-frame matter action with respect to the scalar field:

$$Q_m := -\frac{1}{M_I^2 \sqrt{-g}} \frac{\delta S_m[\psi, \tilde{g}_{\mu\nu}]}{\delta I}$$

The nonlinear stability potential is given by:

$$V(I) = \lambda (I^2 - I)^2$$

with stationary points at $I=0$, $I=1/2$, and the stabilized metric fixed point at $I=1$.

---

## 2. Disformal Frame Separation and Consistency Conditions (Jordan Frame)

To model physical light deflection and lift the purely conformal invariance of null geodesics, we strictly separate the gravitational geometry ($g_{\mu\nu}$) from the physical geometry ($\tilde{g}_{\mu\nu}$) to which matter and radiation fields couple. We define the physical metric via a disformal relation in the Jordan frame:

$$\tilde{g}_{\mu\nu} = g_{\mu\nu} + \gamma \cdot f(I) \nabla_\mu I \nabla_\nu I$$

where $\gamma$ is a dimensionful coupling constant (dimension $L^2$). For the regime of the metric fixed point ($I \rightarrow 1$), we specify the smooth function via the convergent even power ansatz $f(I) = (I^2 - 1)^{2n}$ with $n \in \mathbb{N}_{>0}$, ensuring that $f(I)$ vanishes at the fixed point and remains strictly non-negative in the local neighborhood.

For the fundamental invertibility of the Jordan-frame metric, it is required that $1 - 2\gamma f(I)X \neq 0$ holds. To preserve the physical Lorentz signature, invertibility, and causal structure in the physical sector, the structural disformal consistency conditions are assumed:

$$1 - 2\gamma \cdot f(I) X > 0$$

where $X = -\frac{1}{2} g^{\mu\nu} \nabla_\mu I \nabla_\nu I$ describes the kinetic component of the field. The null geodesics of the physical metric $\tilde{g}_{\mu\nu}$ differ in general from those of the gravitational metric $g_{\mu\nu}$, since the disformal term is not reducible to a pure conformal scale factor. This establishes a formal model framework through which astrophysical effects such as gravitational lensing become quantitatively investigable in further stages.

---

## 3. Post-Newtonian Solar System Expansion and Disformal Boundary Analysis

To mathematically evaluate the fundamental compatibility of the model with precise observational data within the solar system, we consider a static, spherically symmetric point mass $M$ (the Sun) at the center. The gravitational background metric $g_{\mu\nu}$ is parameterized as a weakly perturbed Minkowski metric ($g_{\mu\nu} = \eta_{\mu\nu} + h_{\mu\nu}$ with $|h_{\mu\nu}| \ll 1$).

We consider the behavior of the information field as a small fluctuation around the stable fixed point: $I(r) = 1 + \delta I(r)$. Using the hardened disformal ansatz, the linearized limit yields:

$$f(1 + \delta I) \approx (2\delta I)^{2n} \implies \lim_{\delta I \rightarrow 0} f(I) = 0$$

Substituting this into the fundamental disformal relation of the Jordan frame gives:

$$\tilde{g}_{\mu\nu} = g_{\mu\nu} + \gamma \cdot (2\delta I)^{2n} \nabla_\mu (\delta I) \nabla_\nu (\delta I) \approx g_{\mu\nu}$$

In the parameterized Post-Newtonian (PPN) formalism, the spatial component of the physical metric in the weak-field limit is defined as $\tilde{g}_{ij} = \left(1 + 2\gamma_{\text{PPN}}\frac{GM}{c^2 r}\right)\delta_{ij}$. Since the disformal addition term in the local density regime of the solar system is mathematically suppressed by the factor $(2\delta I)^{2n} \rightarrow 0$, a direct comparison of coefficients yields:

$$2\gamma_{\text{PPN}}\frac{GM}{c^2 r} = 2\frac{GM}{c^2 r} \implies \gamma_{\text{PPN}} = 1$$

The model thus identifies a mathematical limiting case in which the general-relativistic PPN value $\gamma_{\text{PPN}} = 1$ is recovered as a fundamental consistency condition. This demonstrates theoretical compatibility with the experimental Cassini bound ($\gamma_{\text{PPN}} - 1 < 10^{-5}$) on an asymptotic level, while a complete PPN verification is reserved for subsequent numerical analyses.

---

## 4. Kinetic Screening Approach and Phenomenological Boundary Analysis

In a static, spherically symmetric vacuum ($T = 0$ or $\rho = 0$ in the non-relativistic limit) near the fixed point ($I = 1$), linearization of the field equation for the potential $V(I)$ yields an inherently short-ranged Yukawa solution of the form:

$$\delta I(r) \propto \frac{e^{-mr}}{r}$$

where the effective mass of the field is given by $m^2 = \frac{V''(1)}{M_I^2} = \frac{2\lambda}{M_I^2}$. A purely linear coupling in the weak-field limit asymptotically generates a classical, quadratically decaying Newtonian acceleration profile ($a \propto 1/r^2$).

As a potential candidate mechanism for dampening field gradients near massive sources, a nonlinear kinetic structure (k-essence type) is proposed: $K_{\mathcal{X}}(\mathcal{X}) = 1 + \left(\frac{\mathcal{X}}{\Lambda_I^4}\right)^k$, where $\mathcal{X} := M_I^2 X$ denotes the scaled kinetic density. In the hypothetical regime of high acceleration ($\mathcal{X} \gg \Lambda_I^4$), the nonlinear term dominates the radial field equation for the test case $k=1$:

$$r^2 \cdot \left[ \frac{M_I^2 \cdot \frac{1}{2} \left(\frac{d(\delta I)}{dr}\right)^2}{\Lambda_I^4} \right] \frac{d(\delta I)}{dr} = C_{\text{Integration}} \implies \frac{d(\delta I)}{dr} \propto \frac{1}{r^{2/3}}$$

This mathematical scaling serves as a theoretical basis for local isolation of modified gravitational effects in high-density regions, while disformal dynamics may remain relevant on cosmological scales.

For galactic scales ($r \gg r_c$), the phenomenological target profile requires an effective logarithmic geometry to explain flat rotation curves without an additional dark matter component in the effective model:

$$\Phi_{\text{gal}}(r) = \alpha \ln\left(1 + \frac{r}{r_c}\right) \implies a(r) = -\frac{\alpha}{r + r_c}$$

This transition is explicitly declared as an **asymptotic phenomenological target limit** in Version 3.0. The complete mathematical closure of this gap requires in future iterations either a nonlinear modification of the field kinetics via a dimensionless interpolation function $\mu(\mathcal{X}/\Lambda_I^4)$ in the form:

$$\nabla_\mu \left[ K_{\mathcal{X}}(\mathcal{X}) \nabla^\mu I \right] - \frac{1}{M_I^2}\frac{dV}{dI} = Q_m$$

or the specification of a nonlinear, logarithmic integration structure within the coupling functions of the Jordan frame.

---

## 5. Parameter Constraints and Empirical Checklist

Since modifications of gravitational physics are extremely heavily constrained by precise astrophysical observational data, Version 3.0 defines a strict integrative checklist for subsequent numerical simulations:

1. **Propagation Speed of Gravitational Waves:** The disformal coupling matrix must be constrained such that, within the applicable parameter space, the propagation speed of gravitational waves compared to the speed of light in vacuum remains compatible with the tight experimental bounds of GW170817/GRB170817A ($\Delta c_g/c \approx -3\times10^{-15}$ to $+7\times10^{-16}$).
2. **Screening Efficiency:** The scales $\Lambda_I$ and $M_I$ must be numerically constrained such that local precision tests (Shapiro delay, perihelion precession) are not violated.
3. **Astrophysical Observables:** The coupling via the constant $\gamma$ must be tested in the intergalactic limit ($\mathcal{X} \ll \Lambda_I^4$) for its quantitative viability regarding complex lensing data (e.g., Bullet Cluster).

---
