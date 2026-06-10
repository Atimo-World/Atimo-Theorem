[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20622852.svg)](https://doi.org/10.5281/zenodo.20622852)
.
[Atimo-Theorem_v3.0_Multilingual_RELEASE_fixed_2.md](https://github.com/user-attachments/files/28781057/Atimo-Theorem_v3.0_Multilingual_RELEASE_fixed_2.md)
# Multilingual Release Package: Atimo-Theorem v3.0

This document contains the official Major Release v3.0 of the Atimo Theorem in four languages: German, English, Spanish, and French.

---

# DEUTSCH / GERMAN

# Atimo-Theorem v3.0 — Allgemein-kovarianter Modellrahmen mit disformaler Jordan-Frame-Kopplung, Post-Newton-Abschirmungsansatz und offener phänomenologischer Grenzwertschließung

**Autor:** Roberto Weinhold (Atimo)  
**Version:** 3.0 (Konsolidierter Hauptrelease)  
**Datum:** 10. Juni 2026  
**Status:** Heuristischer, kovarianter Modellrahmen / Preprint-Forschungsprogramm  
**Konzeptuelle Basis:** Disformale Skalar-Tensor-Relation im Jordan-Frame mit expliziter Feldskalierung, Post-Newton-Grenzwertevaluierung und kinetischer Screening-Infrastruktur  
**Lizenz:** CC BY 4.0  

---

## Abstract

Die Version 3.0 des Atimo-Theorems formuliert den ersten konsolidierten, allgemein-kovarianten Modellrahmen zur Untersuchung informationsfeldbasierter metrischer Emergenz. Das dimensionslose Skalarfeld $I$ wird über eine explizite Feldskala $M_I$ in eine Einstein-Frame-Action eingebettet, während Materie und Strahlung an eine disformal gekoppelte Jordan-Frame-Metrik $\tilde{g}_{\mu\nu}$ koppeln. Durch den Übergang zu einer disformalen Relation wird die rein konforme Invarianz von Null-Geodäten aufgehoben, wodurch ein formaler Mechanismus zur quantitativen Untersuchung von Gravitationslinseneffekten bereitgestellt wird.

Über eine parametrisierte Schwachfeld-Expansion wird ein mathematischer Grenzbereich identifiziert, in dem der disformale Sektor lokal unterdrückt wird und der allgemein-relativistische Wert $\gamma_{\text{PPN}} = 1$ als notwendige Konsistenzbedingung im Kontext der experimentellen Cassini-Schranken wiedergewonnen werden kann. Ein k-Essenz-inspirierter kinetischer Screening-Ansatz wird als potenzieller Kandidat-Mechanismus vorgeschlagen, um Feldgradienten im Nahbereich massiver Quellen zu dämpfen. Der Übergang auf galaktischen Skalen wird als asymptotischer phänomenologischer Zielgrenzfall deklariert, dessen exakte nichtlineare Schließung Gegenstand zukünftiger Arbeit bleibt.

---

## 1. Vollständige Wirkung (Action) und kovariante Dynamik

Um die Dynamik der Raumzeit-Geometrie und des dimensionslosen skalaren Informationsfeldes $I$ mathematisch konsistent und dimensionssauber zu determinieren, wird das Modell über ein Wirkungsintegral (Action) im Einsteinschen Bezugssystem (Einstein-Frame) unter Verwendung der Lorentz-Signatur $(-, +, +, +)$ definiert. Zur Wahrung der Skalenkonsistenz wird die charakteristische Feldskala $M_I$ eingeführt:

$$S = \int d^4x \sqrt{-g} \left[ \frac{M_{\text{Pl}}^2}{2} R - \frac{M_I^2}{2} g^{\mu\nu} \nabla_\mu I \nabla_\nu I - V(I) \right] + S_m[\psi, \tilde{g}_{\mu\nu}]$$

Hierbei ist $M_{\text{Pl}}$ die reduzierte Planck-Masse, $R$ der Ricci-Skalar der gravitativen Metrik $g_{\mu\nu}$, $\nabla_\mu$ die kovariante Ableitung und $g = \det(g_{\mu\nu})$, sodass $\sqrt{-g}d^4x$ das kovariante Raumzeit-Volumenelement bildet. In natürlichen Einheiten ($c = \hbar = 1$) besitzt der Stabilitätsparameter $\lambda$ die Massendimension 4 (Energiedichte), während die Feldskala $M_I$ die Massendimension 1 trägt. $S_m$ repräsentiert die Wirkung der Standardmaterie (Felder $\psi$), welche ausschließlich an die physikalische Metrik $\tilde{g}_{\mu\nu}$ (Jordan-Frame) koppelt.

Die Variation der Gesamtwirkung nach dem Informationsfeld $I$ liefert unter Berücksichtigung der disformalen Materiekopplung die konsistente allgemein-kovariante Feldgleichung:

$$\Box_g I - \frac{1}{M_I^2}\frac{dV}{dI} = Q_m$$

wobei $\Box_g = g^{\mu\nu} \nabla_\mu \nabla_\nu$ den d'Alembert-Operator darstellt. Der effektive Materie-Quellterm $Q_m$ definiert sich über die Variationsableitung der Jordan-Frame-Matter-Action nach dem Skalarfeld:

$$Q_m := -\frac{1}{M_I^2 \sqrt{-g}} \frac{\delta S_m[\psi, \tilde{g}_{\mu\nu}]}{\delta I}$$

Das nichtlineare Stabilitätspotential lautet:

$$V(I) = \lambda (I^2 - I)^2$$

mit den stationären Punkten bei $I=0$, $I=1/2$ und dem stabilisierten metrischen Fixpunkt bei $I=1$.

---

## 2. Disformale Rahmen-Trennung und Konsistenzbedingungen (Jordan-Frame)

Zur Modellierung der physikalischen Lichtablenkung und zur Aufhebung der rein konformen Invarianz von Null-Geodäten trennen wir die gravitative Geometrie ($g_{\mu\nu}$) strikt von der physikalischen Geometrie ($\tilde{g}_{\mu\nu}$), an welche die Materie- und Strahlungsfelder koppeln. Wir definieren die physikalische Metrik über eine disformale Relation im Jordan-Frame:

$$\tilde{g}_{\mu\nu} = g_{\mu\nu} + \gamma \cdot f(I) \nabla_\mu I \nabla_\nu I$$

wobei $\gamma$ eine dimensionsbehaftete Kopplungskonstante (Dimension $L^2$) darstellt. Für den Bereich des metrischen Fixpunkts ($I \rightarrow 1$) spezifizieren wir die glatte Funktion über den konvergenten geradzahligen Potenzansatz $f(I) = (I^2 - 1)^{2n}$ mit $n \in \mathbb{N}_{>0}$, sodass $f(I)$ am Fixpunkt verschwindet und im lokalen Umfeld strikt nichtnegativ bleibt.

Für die fundamentale Invertierbarkeit der Jordan-Frame-Metrik wird vorausgesetzt, dass $1 - 2\gamma f(I)X \neq 0$ gilt. Zur Erhaltung der physikalischen Lorentz-Signatur, der Invertierbarkeit und der Kausalstruktur im physikalischen Sektor werden die strukturellen disformalen Konsistenzbedingungen vorausgesetzt:

$$1 - 2\gamma \cdot f(I) X > 0$$

wobei $X = -\frac{1}{2} g^{\mu\nu} \nabla_\mu I \nabla_\nu I$ die kinetische Komponente des Feldes beschreibt. Die Null-Geodäten der physikalischen Metrik $\tilde{g}_{\mu\nu}$ unterscheiden sich im Allgemeinen von denen der gravitativen Metrik $g_{\mu\nu}$, da der disformale Term nicht auf einen reinen konformen Skalenfaktor reduzierbar ist. Damit wird ein formaler Modellrahmen etabliert, durch den astrophysikalische Effekte wie Gravitationslinsen im weiteren Verlauf quantitativ untersuchbar werden.

---

## 3. Post-Newton-Sonnensystem-Expansion und disformale Grenzwertanalyse

Um die prinzipielle Kompatibilität des Modells mit den präzisen Messdaten innerhalb des Sonnensystems mathematisch zu evaluieren, betrachten wir eine statische, radialsymmetrische Punktmasse $M$ (die Sonne) im Zentrum. Die gravitative Hintergrundmetrik $g_{\mu\nu}$ wird als schwach gestörte Minkowski-Metrik angesetzt ($g_{\mu\nu} = \eta_{\mu\nu} + h_{\mu\nu}$ mit $|h_{\mu\nu}| \ll 1$).

Wir betrachten das Verhalten des Informationsfeldes als kleine Fluktuation um den stabilen Fixpunkt: $I(r) = 1 + \delta I(r)$. Unter Verwendung des gehärteten disformalen Ansatzes ergibt sich für den linearisierten Limes:

$$f(1 + \delta I) \approx (2\delta I)^{2n} \implies \lim_{\delta I \rightarrow 0} f(I) = 0$$

Eingesetzt in die fundamentale disformale Relation des Jordan-Frames folgt:

$$\tilde{g}_{\mu\nu} = g_{\mu\nu} + \gamma \cdot (2\delta I)^{2n} \nabla_\mu (\delta I) \nabla_\nu (\delta I) \approx g_{\mu\nu}$$

Im parametrisierten Post-Newton-Formalismus (PPN) ist die raumartige Komponente der physikalischen Metrik im schwachen Feldlimes definiert als $\tilde{g}_{ij} = \left(1 + 2\gamma_{\text{PPN}}\frac{GM}{c^2 r}\right)\delta_{ij}$. Da der disformale Zusatzterm im lokalen Dichtebereich des Sonnensystems durch den Faktor $(2\delta I)^{2n} \rightarrow 0$ mathematisch unterdrückt wird, liefert der direkte Koeffizientenvergleich:

$$2\gamma_{\text{PPN}}\frac{GM}{c^2 r} = 2\frac{GM}{c^2 r} \implies \gamma_{\text{PPN}} = 1$$

Das Modell identifiziert somit einen mathematischen Grenzfall, in dem der allgemein-relativistische PPN-Wert $\gamma_{\text{PPN}} = 1$ als fundamentale Konsistenzbedingung wiedergewonnen wird. Dies zeigt die theoretische Vereinbarkeit mit der experimentellen Schranke des Cassini-Experiments ($\gamma_{\text{PPN}} - 1 < 10^{-5}$) auf asymptotischer Ebene auf, während eine vollständige PPN-Überprüfung nachfolgenden numerischen Analysen vorbehalten bleibt.

---

## 4. Kinetischer Screening-Ansatz und phänomenologische Grenzwertanalyse

Im statischen, radialsymmetrischen Vakuum ($T = 0$ beziehungsweise $\rho = 0$ im nichtrelativistischen Grenzfall) nahe dem Fixpunkt ($I = 1$) liefert die Linearisierung der Feldgleichung für das Potential $V(I)$ eine inhärent kurzreichweitige Yukawa-Lösung der Form:

$$\delta I(r) \propto \frac{e^{-mr}}{r}$$

wobei die effektive Masse des Feldes durch $m^2 = \frac{V''(1)}{M_I^2} = \frac{2\lambda}{M_I^2}$ gegeben ist. Eine rein lineare Kopplung im schwachen Feldlimes erzeugt asymptotisch ein klassisches, quadratisch abfallendes Newton-Beschleunigungsprofil ($a \propto 1/r^2$).

Als potenzieller Kandidat-Mechanismus zur Dämpfung von Feldgradienten im Nahbereich massiver Quellen wird eine nichtlineare Kinetik (k-Essenz-Typ) vorgeschlagen: $K_{\mathcal{X}}(\mathcal{X}) = 1 + \left(\frac{\mathcal{X}}{\Lambda_I^4}\right)^k$, wobei $\mathcal{X} := M_I^2 X$ die skalierte kinetische Dichte bezeichnet. Im hypothetischen Regime starker Beschleunigung ($\mathcal{X} \gg \Lambda_I^4$) dominiert für den Testfall $k=1$ der nichtlineare Term in der radialen Feldgleichung:

$$r^2 \cdot \left[ \frac{M_I^2 \cdot \frac{1}{2} \left(\frac{d(\delta I)}{dr}\right)^2}{\Lambda_I^4} \right] \frac{d(\delta I)}{dr} = C_{\text{Integration}} \implies \frac{d(\delta I)}{dr} \propto \frac{1}{r^{2/3}}$$

Diese mathematische Skalierung dient als theoretische Basis für eine lokale Isolation modifizierter Gravitationseffekte in Hochdichtebereichen, während die disformale Dynamik auf kosmologischen Skalen aktivierbar bleibt.

Für galaktische Skalen ($r \gg r_c$) erfordert das phänomenologische Zielprofil zur Erklärung flacher Rotationskurven ohne eine zusätzliche Dunkle-Materie-Komponente im Effektivmodell eine effektive logarithmische Geometrie:

$$\Phi_{\text{gal}}(r) = \alpha \ln\left(1 + \frac{r}{r_c}\right) \implies a(r) = -\frac{\alpha}{r + r_c}$$

Dieser Übergang wird in Version 3.0 explizit als **asymptotischer Zielgrenzfall** deklariert. Die vollständige mathematische Schließung dieser Lücke erfordert in zukünftigen Iterationen entweder eine nichtlineare Modifikation der Feldkinetik über eine dimensionslose Interpolationsfunktion $\mu(\mathcal{X}/\Lambda_I^4)$ in der Form:

$$\nabla_\mu \left[ K_{\mathcal{X}}(\mathcal{X}) \nabla^\mu I \right] - \frac{1}{M_I^2}\frac{dV}{dI} = Q_m$$

oder die Spezifikation einer nichtlinearen, logarithmischen Integrationsstruktur innerhalb der Kopplungsfunktionen des Jordan-Frames.

---

## 5. Parameterbeschränkungen und empirische Prüfliste

Da Modifikationen der Gravitationsphysik durch präzise astrophysikalische Beobachtungsdaten extrem stark reglementiert sind, definiert Version 3.0 ein striktes integratives Prüfprogramm für nachfolgende numerische Simulationen:

1. **Ausbreitungsgeschwindigkeit von Gravitationswellen:** Die disformale Kopplungsmatrix ist im anwendbaren Parameterraum so zu beschränken, dass die Ausbreitungsgeschwindigkeit von Gravitationswellen im Vergleich zur Lichtgeschwindigkeit im Vakuum mit den harten experimentellen Schranken von GW170817/GRB170817A ($\Delta c_g/c \approx -3\times10^{-15}$ bis $+7\times10^{-16}$) kompatibel bleibt.
2. **Screening-Effizienz:** Die Skalen $\Lambda_I$ und $M_I$ sind numerisch so einzuschränken, dass lokale Präzisionstests (Shapiro-Delay, Periheldrehung) nicht verletzt werden.
3. **Astrophysikalische Observablen:** Die Verkopplung über die Konstante $\gamma$ muss im intergalaktischen Limes ($\mathcal{X} \ll \Lambda_I^4$) auf ihre quantitative Tragfähigkeit bezüglich komplexer Linsendaten (z. B. Bullet-Cluster) geprüft werden.

---

# ENGLISH

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

# ESPAÑOL / SPANISH

# Teorema de Atimo v3.0 — Marco de modelo generalmente covariante con acoplamiento disformal en el marco de Jordan, enfoque de apantallamiento post-newtoniano y cierre fenomenológico abierto

**Autor:** Roberto Weinhold (Atimo)
**Versión:** 3.0 (Lanzamiento principal consolidado)
**Fecha:** 10 de junio de 2026
**Estado:** Marco de modelo heurístico y covariante / Programa de investigación de preprints
**Base conceptual:** Relación escalar-tensorial disformal en el marco de Jordan con escalado de campo explícito, evaluación del límite post-newtoniano e infraestructura de apantallamiento cinético
**Licencia:** CC BY 4.0

---

## Resumen

La versión 3.0 del Teorema de Atimo formula el primer marco de modelo consolidado y generalmente covariante para investigar la emergencia métrica basada en campos de información. El campo escalar adimensional $I$ se incrusta en una acción del marco de Einstein a través de una escala de campo explícita $M_I$, mientras que la materia y la radiación se acoplan a una métrica del marco de Jordan acoplada disformalmente $\tilde{g}_{\mu\nu}$. Al hacer la transición a una relación disformal, se levanta la invariancia puramente conforme de las geodésicas nulas, proporcionando un mecanismo formal para el estudio cuantitativo de los efectos de lente gravitacional.

A través de una expansión parametrizada de campo débil, se identifica un régimen límite matemático en el que el sector disformal se suprime localmente, permitiendo recuperar el valor de la relatividad general $\gamma_{\text{PPN}} = 1$ como una condición de consistencia requerida dentro del contexto de los límites experimentales de Cassini. Se propone un enfoque de apantallamiento cinético inspirado en la k-esencia como un mecanismo candidato para suprimir los gradientes escalares cerca de fuentes masivas. Las desviaciones a escala galáctica se tratan como un límite objetivo fenomenológico asintótico, cuyo cierre no lineal exacto permanece abierto para trabajos futuros.

---

## 1. Acción completa y dinámica covariante

Para determinar la dinámica de la geometría del espacio-tiempo y del campo escalar adimensional de información $I$ de una manera matemáticamente consistente y dimensionalmente sólida, el modelo se define mediante una integral de acción en el marco de Einstein utilizando la signatura de Lorentz $(-, +, +, +)$. Para preservar la consistencia de escala, se introduce la escala de campo característica $M_I$:

$$S = \int d^4x \sqrt{-g} \left[ \frac{M_{\text{Pl}}^2}{2} R - \frac{M_I^2}{2} g^{\mu\nu} \nabla_\mu I \nabla_\nu I - V(I) \right] + S_m[\psi, \tilde{g}_{\mu\nu}]$$

Aquí, $M_{\text{Pl}}$ es la masa de Planck reducida, $R$ es el escalar de Ricci de la métrica gravitacional $g_{\mu\nu}$, $\nabla_\mu$ denota la derivada covariante y $g = \det(g_{\mu\nu})$, de modo que $\sqrt{-g}d^4x$ forma el elemento de volumen espacio-temporal covariante. En unidades naturales ($c = \hbar = 1$), el parámetro de estabilidad $\lambda$ tiene una dimensión de masa 4 (densidad de energía), mientras que la escala de campo $M_I$ tiene una dimensión de masa 1. $S_m$ representa la acción de la materia estándar (campos $\psi$), que se acopla exclusivamente a la métrica física $\tilde{g}_{\mu\nu}$ (marco de Jordan).

La variación de la acción total con respecto al campo de información $I$, teniendo en cuenta el acoplamiento disformal de la materia, produce la ecuación de campo generalmente covariante y consistente:

$$\Box_g I - \frac{1}{M_I^2}\frac{dV}{dI} = Q_m$$

donde $\Box_g = g^{\mu\nu} \nabla_\mu \nabla_\nu$ representa el operador de d'Alembert. El término de fuente de materia efectiva $Q_m$ se define a través de la derivada variacional de la acción de la materia en el marco de Jordan con respecto al campo escalar:

$$Q_m := -\frac{1}{M_I^2 \sqrt{-g}} \frac{\delta S_m[\psi, \tilde{g}_{\mu\nu}]}{\delta I}$$

El potencial de estabilidad no lineal viene dado por:

$$V(I) = \lambda (I^2 - I)^2$$

con puntos estacionarios en $I=0$, $I=1/2$, y el punto fijo métrico estabilizado en $I=1$.

---

## 2. Acoplamiento disformal y condiciones de consistencia (marco de Jordan)

Para modelar la desviación física de la luz y levantar la invariancia puramente conforme de las geodésicas nulas, separamos estrictamente la geometría gravitacional ($g_{\mu\nu}$) del espacio métrico físico ($\tilde{g}_{\mu\nu}$) al que se acoplan los campos de materia y radiación. Definimos la métrica física mediante una relación disformal en el marco de Jordan:

$$\tilde{g}_{\mu\nu} = g_{\mu\nu} + \gamma \cdot f(I) \nabla_\mu I \nabla_\nu I$$

donde $\gamma$ es una constante de acoplamiento dimensional (dimensión $L^2$). Para el régimen del punto fijo métrico ($I \rightarrow 1$), especificamos la función suave a través del enfoque de potencia par convergente $f(I) = (I^2 - 1)^{2n}$ con $n \in \mathbb{N}_{>0}$, asegurando que $f(I)$ se anule en el punto fijo y permanezca estrictamente no negativa en el entorno local.

Para la invertibilidad fundamental de la métrica en el marco de Jordan, se requiere que se cumpla $1 - 2\gamma f(I)X \neq 0$. Para preservar la signatura física de Lorentz, la invertibilidad y la estructura causal en el sector físico, se asumen las condiciones estructurales de consistencia disformal:

$$1 - 2\gamma \cdot f(I) X > 0$$

donde $X = -\frac{1}{2} g^{\mu\nu} \nabla_\mu I \nabla_\nu I$ describe la componente cinética del campo. Las geodésicas nulas de la métrica física $\tilde{g}_{\mu\nu}$ difieren en general de las de la métrica gravitacional $g_{\mu\nu}$, ya que el término disformal no es reducible a un factor de escala conforme puro. Esto establece un marco de modelo formal a través del cual los efectos astrofísicos como las lentes gravitacionales se vuelven cuantitativamente investigables en etapas posteriores.

---

## 3. Expansión post-newtoniana del sistema solar y análisis de límites disformales

Para evaluar matemáticamente la compatibilidad fundamental del modelo con datos observacionales precisos dentro del sistema solar, consideramos una masa puntual estática y esféricamente simétrica $M$ (el Sol) en el centro. La métrica de fondo gravitacional $g_{\mu\nu}$ se parametriza como una métrica de Minkowski débilmente perturbada ($g_{\mu\nu} = \eta_{\mu\nu} + h_{\mu\nu}$ con $|h_{\mu\nu}| \ll 1$).

Consideramos el comportamiento del campo de información como una pequeña fluctuación alrededor del punto fijo estable: $I(r) = 1 + \delta I(r)$. Utilizando el enfoque disformal endurecido, el límite linealizado produce:

$$f(1 + \delta I) \approx (2\delta I)^{2n} \implies \lim_{\delta I \rightarrow 0} f(I) = 0$$

Sustituyendo esto en la relación disformal fundamental del marco de Jordan se obtiene:

$$\tilde{g}_{\mu\nu} = g_{\mu\nu} + \gamma \cdot (2\delta I)^{2n} \nabla_\mu (\delta I) \nabla_\nu (\delta I) \approx g_{\mu\nu}$$

En el formalismo post-newtoniano parametrizado (PPN), la componente espacial de la métrica física en el límite de campo débil se define como $\tilde{g}_{ij} = \left(1 + 2\gamma_{\text{PPN}}\frac{GM}{c^2 r}\right)\delta_{ij}$. Dado que el término de adición disformal en el régimen de densidad local del sistema solar se suprime matemáticamente por el factor $(2\delta I)^{2n} \rightarrow 0$, una comparación directa de coeficientes produce:

$$2\gamma_{\text{PPN}}\frac{GM}{c^2 r} = 2\frac{GM}{c^2 r} \implies \gamma_{\text{PPN}} = 1$$

Por lo tanto, el modelo identifica un caso límite matemático en el que el valor PPN de la relatividad general $\gamma_{\text{PPN}} = 1$ se recupera como una condición de consistencia fundamental. Esto demuestra la compatibilidad teórica con el límite experimental de Cassini ($\gamma_{\text{PPN}} - 1 < 10^{-5}$) a un nivel asintótico, mientras que una verificación PPN completa se reserva para análisis numéricos posteriores.

---

## 4. Enfoque de apantallamiento cinético y análisis de límites fenomenológicos

En un vacío estático y esféricamente simétrico ($T = 0$ o $\rho = 0$ en el límite no relativista) cerca del punto fijo ($I = 1$), la linealización de la ecuación de campo para el potencial $V(I)$ produce una solución de Yukawa inherentemente de corto alcance de la forma:

$$\delta I(r) \propto \frac{e^{-mr}}{r}$$

donde la masa efectiva del campo viene dada por $m^2 = \frac{V''(1)}{M_I^2} = \frac{2\lambda}{M_I^2}$. Un acoplamiento puramente lineal en el límite de campo débil genera asintóticamente un perfil de aceleración newtoniano clásico de decaimiento cuadrático ($a \propto 1/r^2$).

Como un posible mecanismo candidato para amortiguar los gradientes de campo cerca de fuentes masivas, se propone una estructura cinética no lineal (tipo k-esencia): $K_{\mathcal{X}}(\mathcal{X}) = 1 + \left(\frac{\mathcal{X}}{\Lambda_I^4}\right)^k$, donde $\mathcal{X} := M_I^2 X$ denota la densidad cinética escalada. En el régimen hipotético de alta aceleración ($\mathcal{X} \gg \Lambda_I^4$), el término no lineal domina la ecuación de campo radial para el caso de prueba $k=1$:

$$r^2 \cdot \left[ \frac{M_I^2 \cdot \frac{1}{2} \left(\frac{d(\delta I)}{dr}\right)^2}{\Lambda_I^4} \right] \frac{d(\delta I)}{dr} = C_{\text{Integration}} \implies \frac{d(\delta I)}{dr} \propto \frac{1}{r^{2/3}}$$

Este escalado matemático sirve como base teórica para el aislamiento local de los efectos de la gravedad modificada en regiones de alta densidad, mientras que la dinámica disformal puede permanecer activa a escalas cosmológicas.

Para escalas galácticas ($r \gg r_c$), el perfil objetivo fenomenológico requiere una geometría logarítmica efectiva para explicar las curvas de rotación planas sin un componente adicional de materia oscura en el modelo efectivo:

$$\Phi_{\text{gal}}(r) = \alpha \ln\left(1 + \frac{r}{r_c}\right) \implies a(r) = -\frac{\alpha}{r + r_c}$$

Esta transición se declara explícitamente como un **límite objetivo fenomenológico asintótico** en la Versión 3.0. El cierre matemático completo de esta brecha requiere en futuras iteraciones una modificación no lineal de la cinética del campo a través de una función de interpolación adimensional $\mu(\mathcal{X}/\Lambda_I^4)$ en la forma:

$$\nabla_\mu \left[ K_{\mathcal{X}}(\mathcal{X}) \nabla^\mu I \right] - \frac{1}{M_I^2}\frac{dV}{dI} = Q_m$$

o la especificación de una estructura de integración logarítmica no lineal dentro de las funciones de acoplamiento del marco de Jordan.

---

## 5. Restricciones de parámetros y lista de verificación empírica

Dado que las modificaciones de la física gravitacional están extremadamente restringidas por datos observacionales astrofísicos precisos, la Versión 3.0 define una estricta lista de verificación integradora para simulaciones numéricas posteriores:

1. **Velocidad de propagación de ondas gravitacionales:** La matriz de acoplamiento disformal debe restringirse de modo que, dentro del espacio de parámetros aplicable, la velocidad de propagación de las ondas gravitacionales en comparación con la velocidad de la luz en el vacío permanezca compatible con los estrictos límites experimentales de GW170817/GRB170817A ($\Delta c_g/c \approx -3\times10^{-15}$ a $+7\times10^{-16}$).
2. **Eficiencia de apantallamiento:** Las escalas $\Lambda_I$ y $M_I$ deben restringirse numéricamente de tal manera que no se violen las pruebas de precisión locales (retraso de Shapiro, precesión del perihelio).
3. **Observables astrofísicos:** El acoplamiento a través de la constante $\gamma$ debe probarse en el límite intergaláctico ($\mathcal{X} \ll \Lambda_I^4$) para determinar su viabilidad cuantitativa con respecto a datos de lentes complejos (por ejemplo, el Cúmulo de la Bala).

---

# FRANÇAIS / FRENCH

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
