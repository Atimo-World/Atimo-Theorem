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

----
