[Atimo-Theorem_v4.0_release_clean.md](https://github.com/user-attachments/files/29797136/Atimo-Theorem_v4.0_release_clean.md)
# Multilingual Release Package: Atimo-Theorem v4.0

**Hinweis zur Dokumentenstruktur / Structural Notice:** Die deutsche Fassung ist die technische Master-Version und enthält die ausführlichere mathematische Modellformulierung. Die englische und spanische Fassung sind gekürzte internationale Zusammenfassungen.  
*The German version is the technical master version. The English and Spanish sections are condensed international summaries.*

---

## 🇩🇪 DEUTSCH / GERMAN — TECHNICAL MASTER VERSION

# Atimo-Theorem v4.0  
## Dimensionsvariables Informationsdichte-Skalengesetz und kovarianter Testmodellrahmen

**Autor:** Roberto Weinhold (Atimo)  
**Version:** 4.0  
**Datum:** Juli 2026  
**Status:** Mathematisch-physikalischer Modellansatz / falsifizierbares Preprint-Forschungsprogramm  
**Vorgängerversion:** Atimo-Theorem v3.0  
**Kernverallgemeinerung:** Von $x=i^2$ zu einem normierten Skalengesetz $\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}$  

---

## Abstract

Version 4.0 des Atimo-Theorem-Forschungsprogramms formuliert die bisherige quadratische Informationsrelation

$$x=i^2$$

als Spezialfall eines allgemeineren dimensionslosen Skalengesetzes. Dazu wird eine normierte Informationsdichte

$$\hat{\iota}:=\frac{\iota}{\iota_\ast}$$

eingeführt. Eine testfallspezifische physikalische Antwortgröße $y$ wird ebenfalls normiert:

$$\chi:=\frac{y}{y_\ast}.$$

Der v4.0-Ansatz definiert dann:

$$\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}.$$

Der effektive Skalenparameter wird über die logarithmische Antwortfunktion bestimmt:

$$n_{\mathrm{eff}} := \frac{d\ln\chi}{d\ln\hat{\iota}}.$$

Damit ist der ursprüngliche Ausdruck $x=i^2$ als quadratisches Antwortregime mit $n_{\mathrm{eff}}=2$ enthalten. Der lokale vierdimensionale Raumzeit-Grenzfall wird im Modell durch

$$n_{\mathrm{eff}}\to4$$

parametrisiert.

Version 4.0 versteht diese Struktur nicht als abgeschlossene Naturgleichung, sondern als falsifizierbaren mathematisch-physikalischen Modellansatz. Seine Tragfähigkeit ist anhand definierter Testbereiche zu prüfen: Dimensionsanalyse, lokaler Fixpunkt, PPN/Cassini-Grenzen, Gravitationswellengeschwindigkeit, SPARC-Rotationskurven, Lensing, Bullet-Cluster-artige Systeme, Stabilitätsanalyse und kosmologische Konsistenz.

---

## 1. Zielsetzung und Abgrenzung

Ziel von Version 4.0 ist die wissenschaftlich strengere Formulierung des Atimo-Ansatzes.

Nicht behauptet wird:

1. dass Gravitation bereits vollständig aus $\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}$ abgeleitet sei,
2. dass die Allgemeine Relativitätstheorie ersetzt sei,
3. dass Dunkle Materie empirisch widerlegt sei,
4. dass $n_{\mathrm{eff}}$ ohne weitere Dynamik physikalische Dimensionen direkt verändert.

Behauptet wird lediglich:

1. Es wird ein dimensionsloses Informationsdichte-Skalengesetz definiert.
2. Dieses Skalengesetz enthält $x=i^2$ als quadratischen Spezialfall.
3. Es kann in einen kovarianten lokalen Feldrahmen eingebettet werden.
4. Es erzeugt konkrete mathematische Konsistenzbedingungen.
5. Es führt zu überprüfbaren und falsifizierbaren Testbereichen.

---

## 2. Notation

Zur Vermeidung von Mehrdeutigkeiten wird folgende Notation verwendet:

| Symbol | Bedeutung |
|---|---|
| $i$ | Imaginäre Einheit der komplexen Zahlen; im v4.0-Formalismus keine Informationsvariable |
| $I$ | Informationsfeldnotation früherer Versionen |
| $\iota$ | Informationsdichtevariable in v4.0 |
| $\iota_\ast$ | Referenzwert der Informationsdichte |
| $\hat{\iota}$ | Normierte Informationsdichte, $\hat{\iota}=\iota/\iota_\ast$ |
| $y$ | Testfallspezifische physikalische Wirkungs- oder Antwortgröße |
| $y_\ast$ | Referenzskala der Wirkungs- bzw. Antwortgröße |
| $\chi$ | Dimensionslose physikalische Antwort, $\chi=y/y_\ast$ |
| $n_{\mathrm{eff}}$ | Effektiver logarithmischer Skalenparameter |
| $g_{\mu\nu}$ | Gravitative Einstein-Frame-Metrik |
| $\tilde{g}_{\mu\nu}$ | Physikalische Jordan-Frame-Metrik |
| $M_\iota$ | Feldskala der Informationsdichte |
| $\mathcal{X}$ | Skalierte kinetische Dichte des Informationsfeldes |
| $\mathcal{Y}$ | Positive kinetische Screening-Amplitude, $\mathcal{Y}:=|\mathcal{X}|$ |
| $\Lambda_\iota$ | Kinetische Screening-Skala |
| $\Lambda_D$ | Disformale Kopplungsskala |

---

## 3. Normiertes Informationsdichte-Skalengesetz

Die physikalisch dimensionskonsistente Grundform lautet:

$$\chi:=\frac{y}{y_\ast}, \qquad \hat{\iota}:=\frac{\iota}{\iota_\ast}.$$

Damit wird das v4.0-Skalengesetz definiert als:

$$\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}.$$

Diese Gleichung ist nur sinnvoll, wenn sowohl $\chi$ als auch $\hat{\iota}$ dimensionslos sind. Die Größe $y$ ist nicht universell festgelegt, sondern muss für jeden Testfall operational definiert werden, zum Beispiel als:

1. effektiver Beschleunigungsfaktor,
2. Lensing-Potential,
3. metrischer Korrekturfaktor,
4. dimensionslose Antwortfunktion,
5. skalenabhängiger Kopplungsfaktor.

Die dimensionsbehaftete Größe ergibt sich durch Rückskalierung:

$$y=y_\ast\hat{\iota}^{\,n_{\mathrm{eff}}}.$$

---

## 4. Mathematische Herleitung als lokales Potenzgesetz

Ein allgemeiner Zusammenhang zwischen dimensionsloser Antwort $\chi$ und normierter Informationsdichte $\hat{\iota}$ kann als allgemeine Antwortfunktion geschrieben werden:

$$\chi=F(\hat{\iota}).$$

Für positive $\chi$ und positive $\hat{\iota}$ wird die logarithmische Steigung definiert als:

$$n_{\mathrm{eff}}(\hat{\iota}) := \frac{d\ln F(\hat{\iota})}{d\ln\hat{\iota}}.$$

Daraus folgt allgemein das totale Differential:

$$d\ln\chi = n_{\mathrm{eff}}(\hat{\iota})\,d\ln\hat{\iota}.$$

Integration unter der Normierungsbedingung

$$\chi(1)=1$$

liefert:

$$\chi(\hat{\iota}) = \exp \left[ \int_1^{\hat{\iota}} n_{\mathrm{eff}}(u)\,d\ln u \right].$$

Für den Spezialfall eines konstanten effektiven Skalenparameters

$$n_{\mathrm{eff}}=n_0$$

folgt unmittelbar das exakte Potenzgesetz:

$$\chi = \exp \left[ n_0 \int_1^{\hat{\iota}} d\ln u \right] = \exp \left[ n_0\ln\hat{\iota} \right] = \hat{\iota}^{\,n_0}.$$

Damit ist das normierte Potenzgesetz als Spezialfall einer logarithmischen lokalen Antwortfunktion mathematisch herleitbar.

---

## 5. Einordnung des ursprünglichen Ausdrucks $x=i^2$

Der ursprüngliche Atimo-Ausdruck

$$x=i^2$$

wird in Version 4.0 als nichtlinearer, quadratischer Spezialfall interpretiert.

In normierter Schreibweise entspricht er:

$$\chi=\hat{\iota}^{\,2}.$$

Damit gilt:

$$n_{\mathrm{eff}}=2.$$

Version 4.0 verallgemeinert diesen Fall auf skalenabhängige kontinuierliche Übergänge:

$$n_{\mathrm{eff}} = n_{\mathrm{eff}} ( \hat{\iota}, \rho, r, \nabla\hat{\iota}, \mathcal{X} ).$$

---

## 6. Effektiver Skalenparameter $n_{\mathrm{eff}}$

Der Parameter $n_{\mathrm{eff}}$ beschreibt keine direkte Änderung realer makroskopischer Raumzeitdimensionen. Er fungiert zunächst als effektiver Skalenparameter der Systemantwort.

Interpretation:

- $n_{\mathrm{eff}}=1$: lineares Antwortregime,
- $n_{\mathrm{eff}}=2$: quadratisches Antwortregime,
- $n_{\mathrm{eff}}\approx4$: lokaler vierdimensional parametrisierter Grenzfall,
- $n_{\mathrm{eff}}<4$: effektive Abschwächung gegenüber dem vierdimensionalen Referenzregime,
- $n_{\mathrm{eff}}>4$: effektive Verstärkung gegenüber dem vierdimensionalen Referenzregime.

Für astrophysikalische Testfälle wird $n_{\mathrm{eff}}$ als radiale Funktionsgröße behandelt:

$$n_{\mathrm{eff}}(r) = 4-\Delta n\cdot S(r),$$

mit der glatten Übergangsfunktion

$$S(r) = \frac{1} {1+\left(\frac{r_c}{r}\right)^p}.$$

Damit gelten die Grenzfälle:

$$\lim_{r\ll r_c}n_{\mathrm{eff}}(r)=4,$$

$$\lim_{r\gg r_c}n_{\mathrm{eff}}(r)=4-\Delta n.$$

Die Parameter $\Delta n$, $r_c$ und $p$ sind nicht frei beliebig zu wählen, sondern müssen durch numerische Fits, Stabilitätsbedingungen und externe Beobachtungsgrenzen eingeschränkt werden.

---

## 7. Lokaler kovarianter Modellrahmen

Der allgemein-kovariante Modellrahmen bettet das normierte Skalarfeld in eine Einstein-Frame-Action ein:

$$S = \int d^4x\sqrt{-g} \left[ \frac{M_{\mathrm{Pl}}^2}{2}R - \frac{M_\iota^2}{2} g^{\mu\nu} \nabla_\mu\hat{\iota} \nabla_\nu\hat{\iota} - V(\hat{\iota}) \right] + S_m[\psi,\tilde{g}_{\mu\nu}].$$

Dabei ist $M_{\mathrm{Pl}}$ die reduzierte Planck-Masse, $R$ der Ricci-Skalar, $M_\iota$ die charakteristische Feldskala der Informationsdichte und $S_m$ die Materiewirkung, welche an die physikalische Jordan-Frame-Metrik $\tilde{g}_{\mu\nu}$ koppelt.

Das mathematische Sättigungspotential lautet:

$$V(\hat{\iota}) = \lambda(\hat{\iota}^2-\hat{\iota})^2.$$

Die erste Ableitung ist:

$$\frac{dV}{d\hat{\iota}} = 2\lambda \hat{\iota} (\hat{\iota}-1) (2\hat{\iota}-1).$$

Die Extremalpunkte liegen daher bei:

$$\hat{\iota}=0, \qquad \hat{\iota}=\frac{1}{2}, \qquad \hat{\iota}=1.$$

Die zweite Ableitung lautet:

$$\frac{d^2V}{d\hat{\iota}^2} = \lambda(12\hat{\iota}^2-12\hat{\iota}+2).$$

Am Punkt $\hat{\iota}=1$ gilt:

$$V''(1)=2\lambda.$$

Für

$$\lambda>0$$

stellt $\hat{\iota}=1$ einen mathematisch stabilen lokalen Vakuum-Fixpunkt dar.

---

## 8. Feldgleichung

Variation der Action nach $\hat{\iota}$ ergibt die lokale d’Alembert-Feldgleichung:

$$\Box_g\hat{\iota} - \frac{1}{M_\iota^2} \frac{dV}{d\hat{\iota}} = Q_m,$$

mit

$$Q_m := - \frac{1}{M_\iota^2\sqrt{-g}} \frac{ \delta S_m[\psi,\tilde{g}_{\mu\nu}] } { \delta\hat{\iota} }.$$

Für kleine Fluktuationen um den lokalen Fixpunkt

$$\hat{\iota}=1+\delta\iota$$

ergibt sich linearisiert:

$$\Box_g\delta\iota - m_\iota^2\delta\iota = Q_m,$$

mit

$$m_\iota^2 = \frac{2\lambda}{M_\iota^2}.$$

Im statischen, radialsymmetrischen Vakuum folgt daraus eine Yukawa-artige, kurzreichweitige Lösung:

$$\delta\iota(r) \propto \frac{e^{-m_\iota r}}{r}.$$

Diese Lösung unterstützt den lokalen Abschirmungscharakter des Feldes, sofern $m_\iota$ und die Screening-Parameter so gewählt werden, dass lokale Präzisionstests nicht verletzt werden. Die konkrete Amplitude einer nichttrivialen Lösung muss aus dem vollständigen Materiequellterm $Q_m$ bestimmt werden und ist Gegenstand der numerischen Testphase.

---

## 9. Disformale Jordan-Frame-Metrik

Materie und Strahlung koppeln an die physikalische Jordan-Frame-Metrik:

$$\tilde{g}_{\mu\nu} = C(\hat{\iota})g_{\mu\nu} + \frac{B(\hat{\iota})}{\Lambda_D^4} \nabla_\mu\phi \nabla_\nu\phi,$$

mit

$$\phi:=M_\iota\hat{\iota}.$$

Für den lokalen Grenzfall wird zunächst gesetzt:

$$C(\hat{\iota})=1$$

und

$$B(\hat{\iota}) = (\hat{\iota}^2-1)^{2m}, \qquad m\in\mathbb{N}_{>0}.$$

Am Fixpunkt gilt:

$$B(1)=0.$$

Dadurch wird der disformale Zusatzsektor am lokalen Fixpunkt unterdrückt:

$$\tilde{g}_{\mu\nu} \approx g_{\mu\nu} \qquad \text{für} \qquad \hat{\iota}\to1.$$

Diese lokale Unterdrückung ist notwendig, aber nicht allein hinreichend. Zusätzlich müssen PPN-, Lensing-, Stabilitäts- und Tensorwellenbedingungen explizit geprüft werden.

---

## 10. Konsistenzbedingungen

Für die mathematische Zulässigkeit der disformalen Metrik müssen folgende Bedingungen im relevanten Phasenraum erfüllt sein.

### 10.1 Invertierbarkeit

$$1 - 2 \frac{B(\hat{\iota})}{\Lambda_D^4} X_\phi > 0,$$

mit

$$X_\phi = -\frac{1}{2} g^{\mu\nu} \nabla_\mu\phi \nabla_\nu\phi.$$

### 10.2 Lorentz-Signatur

Die physikalische Metrik $\tilde{g}_{\mu\nu}$ muss die Lorentz-Signatur erhalten:

$$(-,+,+,+).$$

### 10.3 Lokaler GR-Grenzfall

Im Hochpräzisionsbereich muss gelten:

$$\tilde{g}_{\mu\nu} \to g_{\mu\nu}.$$

### 10.4 Signalstruktur

Es dürfen keine beobachtbar kausalitätsverletzenden oder experimentell ausgeschlossenen superluminalen Effekte auftreten.

### 10.5 Stabilität

Ghost- und Gradienteninstabilitäten müssen ausgeschlossen sein. In einer effektiven linearen Störungsanalyse müssen daher mindestens gelten:

$$K_{\mathrm{eff}}>0, \qquad c_s^2>0.$$

---

## 11. Kinetisches Screening

Um lokale Sonnensystemtests im zulässigen Parameterbereich zu erfüllen, wird die kinetische Dichte phänomenologisch über einen k-Essenz-artigen Screening-Ansatz beschrieben.

Die kovariante kinetische Größe lautet:

$$\mathcal{X} = -\frac{1}{2} M_\iota^2 g^{\mu\nu} \nabla_\mu\hat{\iota} \nabla_\nu\hat{\iota}.$$

Für statische radiale Screening-Testkonfigurationen kann $\mathcal{X}$ je nach Signaturkonvention negativ sein. Daher wird für den phänomenologischen Screening-Test die positive kinetische Amplitude definiert als:

$$\mathcal{Y}:=|\mathcal{X}|.$$

Eine minimale positive Screening-Funktion lautet:

$$K(\mathcal{Y}) = \mathcal{Y} + \frac{\mathcal{Y}^{k+1}}{\Lambda_\iota^{4k}},$$

mit

$$k>0, \qquad \Lambda_\iota>0.$$

Die effektive Feldgleichung kann im Screening-Testbereich formal geschrieben werden als:

$$\nabla_\mu \left[ K_{\mathcal{Y}} \nabla^\mu\hat{\iota} \right] - \frac{1}{M_\iota^2} \frac{dV}{d\hat{\iota}} = Q_m,$$

wobei

$$K_{\mathcal{Y}} = \frac{dK}{d\mathcal{Y}}.$$

Im Hochgradientenbereich massiver Quellen kann

$$K_{\mathcal{Y}}\gg1$$

Feldfluktuationen effektiv unterdrücken. Ob diese Unterdrückung mit PPN-Grenzen, Gravitationswellengrenzen und Stabilitätsbedingungen gleichzeitig vereinbar ist, muss numerisch geprüft werden.

Diese Formulierung ist als phänomenologische Screening-Parametrisierung zu verstehen. Eine vollständig kovariante, analytische und stabilitätsgesicherte $K(\mathcal{X})$-Funktion bleibt Gegenstand der nächsten Arbeitsstufe.

---

## 12. Phänomenologische Schließung der galaktischen Beschleunigung

Um den Zusammenhang zwischen dem kovarianten Jordan-Frame-Modell und beobachtbaren galaktischen Rotationskurven prüfbar zu machen, wird im Folgenden kein abgeschlossener analytischer Beweis flacher Rotationskurven behauptet. Stattdessen wird eine phänomenologische Schließungsbedingung formuliert, die numerisch gegen Rotationskurven- und Lensing-Daten getestet werden muss.

Ziel ist die Konstruktion eines effektiven Beschleunigungsprofils

$$a_{\mathrm{model}}(r)$$

aus der baryonischen Newton-Beschleunigung

$$a_N(r) = \frac{GM_{\mathrm{bar}}(r)}{r^2}$$

und einem informationsdichteabhängigen Korrekturfaktor

$$\mu_A(r).$$

Der Modellansatz lautet:

$$a_{\mathrm{model}}(r) = a_N(r)\mu_A(r).$$

Die dimensionslose Antwortgröße des v4.0-Skalengesetzes wird für diesen Testfall operational definiert als:

$$\chi_A(r) := \frac{a_{\mathrm{model}}(r)}{a_N(r)} = \mu_A(r).$$

Damit erhält das normierte Informationsdichte-Skalengesetz die testfallspezifische Form:

$$\mu_A(r) = \hat{\iota}(r)^{\,n_{\mathrm{eff}}(r)-n_0}.$$

Hierbei bezeichnet $n_0$ den lokalen Referenzwert. Für den lokalen vierdimensional parametrisierten Grenzfall wird gesetzt:

$$n_0=4.$$

Somit gilt:

$$\mu_A(r) = \hat{\iota}(r)^{\,n_{\mathrm{eff}}(r)-4}.$$

Der effektive Skalenparameter wird radial parametrisiert als:

$$n_{\mathrm{eff}}(r) = 4-\Delta n\cdot S(r),$$

mit

$$S(r) = \frac{1} {1+\left(\frac{r_c}{r}\right)^p}.$$

Damit gelten:

$$\lim_{r\ll r_c}n_{\mathrm{eff}}(r)=4,$$

$$\lim_{r\gg r_c}n_{\mathrm{eff}}(r)=4-\Delta n.$$

Für das Informationsdichteprofil wird zunächst eine allgemeine radiale Funktion angenommen:

$$\hat{\iota}(r) = \hat{\iota}_{\mathrm{model}}(r;\Theta_\iota).$$

Eine mögliche minimale phänomenologische Form ist:

$$\hat{\iota}_{\mathrm{model}}(r) = \left[ 1+\eta \ln \left( 1+\frac{r}{r_0} \right) \right]^{-1},$$

mit

$$\eta\ge0, \qquad r_0>0.$$

Diese Form ist nicht als abgeleitete Feldlösung zu verstehen, sondern als testbare Minimalparametrisierung einer radial abnehmenden normierten Informationsdichteantwort.

Damit ergibt sich das testbare Beschleunigungsmodell:

$$a_{\mathrm{model}}(r) = a_N(r) \left[ \hat{\iota}_{\mathrm{model}}(r;\Theta_\iota) \right]^{ n_{\mathrm{eff}}(r)-4 }.$$

Die Rotationsgeschwindigkeit folgt aus:

$$v_{\mathrm{model}}^2(r) = r\,a_{\mathrm{model}}(r).$$

Somit:

$$v_{\mathrm{model}}(r) = \sqrt{ r\,a_N(r) \left[ \hat{\iota}_{\mathrm{model}}(r;\Theta_\iota) \right]^{ n_{\mathrm{eff}}(r)-4 } }.$$

Diese Gleichung ist keine abgeschlossene analytische Ableitung flacher Rotationskurven, sondern ein falsifizierbarer phänomenologischer Testansatz. Entscheidend ist, ob dieselbe Parametrisierung $n_{\mathrm{eff}}(r)$ und $\hat{\iota}(r)$ mit wenigen freien Parametern beobachtete Rotationskurven reproduzieren kann, ohne lokale Sonnensystemtests, Lensing-Daten oder Gravitationswellen-Grenzen zu verletzen.

Für einen SPARC-Test kann die Güte über

$$\chi^2 = \sum_i \frac{ \left[ v_{\mathrm{obs}}(r_i) - v_{\mathrm{model}}(r_i;\Theta) \right]^2 } {\sigma_i^2}$$

bestimmt werden.

Die freien Minimalparameter können zunächst gewählt werden als:

$$\Theta_{\mathrm{min}} = \{\Delta n,r_c,p,\eta,r_0\}.$$

Das Modell ist nur dann empirisch konkurrenzfähig, wenn es mit vergleichbarer oder geringerer effektiver Parameterzahl eine Fitqualität erreicht, die mit etablierten Referenzmodellen vergleichbar ist.

Zu vergleichen sind insbesondere:

1. Newtonsche Dynamik ohne Halo,
2. NFW-Halo,
3. Burkert-Halo,
4. MOND-artige Interpolationsfunktionen,
5. baryonische Tully-Fisher-Relation.

Ein Scheitern liegt vor, wenn:

1. die Rotationskurven nur durch stark galaxienspezifische freie Parameter reproduziert werden können,
2. Lensing und Dynamik nicht gleichzeitig konsistent beschrieben werden,
3. der lokale PPN-Grenzfall verletzt wird,
4. die Tensorwellengeschwindigkeit unzulässig von $c$ abweicht,
5. der Fit schlechter ist als etablierte Vergleichsmodelle bei gleicher oder geringerer Parameterzahl.

---

## 13. Empirische Testprozeduren

Der v4.0-Ansatz definiert neun Testbereiche, anhand derer der Modellrahmen eingeschränkt, geprüft oder falsifiziert werden kann.

### 13.1 Dimensionsanalyse

Strenge Dimensionskonsistenz durch Referenzskalen.

Bestehenskriterium:

$$\chi = \frac{y}{y_\ast}, \qquad \hat{\iota} = \frac{\iota}{\iota_\ast}$$

müssen dimensionslos sein.

Die disformale Struktur

$$\frac{B(\hat{\iota})}{\Lambda_D^4} \nabla_\mu\phi\nabla_\nu\phi$$

muss dieselbe dimensionslose Metrikstruktur besitzen wie $g_{\mu\nu}$.

---

### 13.2 Lokaler Fixpunkt

Mathematische Stabilität des Vakuums bei

$$\hat{\iota}=1.$$

Bestehenskriterium:

$$V'(1)=0, \qquad V''(1)=2\lambda>0.$$

Damit muss gelten:

$$\lambda>0.$$

---

### 13.3 Sonnensystem / Cassini

Numerische Lösung der Feldgleichung für die Sonnenmasse $M_\odot$.

Kinetisches Screening soll im zulässigen Parameterbereich

$$\hat{\iota}\to1$$

begünstigen und

$$B(\hat{\iota})$$

unterdrücken, sodass die PPN-Grenze

$$|\gamma_{\mathrm{PPN}}-1| \lesssim 10^{-5}$$

erfüllt wird.

Dieser Punkt ist nicht durch den Grenzwert allein bewiesen, sondern muss durch eine quantitative PPN-Rechnung geprüft werden.

---

### 13.4 Gravitationswellen / GW170817

Die Bedingung

$$B(1)=0$$

ist eine notwendige lokale Konsistenzbedingung.

Zusätzlich muss durch Linearisierung der Tensorstörungen um den FLRW-Hintergrund geprüft werden, ob keine beobachtbar unzulässige Abweichung der Tensorwellengeschwindigkeit vorliegt:

$$\left| \frac{c_T-c}{c} \right| < 10^{-15}.$$

Parameterbereiche, die größere Abweichungen erzeugen, sind ausgeschlossen.

---

### 13.5 SPARC-Rotationskurven

Minimierung von

$$\chi^2 = \sum_i \frac{ \left[ v_{\mathrm{obs}}(r_i) - v_{\mathrm{model}}(r_i;\Theta) \right]^2 } {\sigma_i^2}$$

über die 175 Galaxien der SPARC-Datenbank.

Zu prüfen ist, ob Rotationskurven ohne zusätzliche nichtbaryonische Halo-Komponente innerhalb dieses Modellrahmens beschrieben werden können.

---

### 13.6 Lensing

Untersuchung konsistenter Lichtablenkung durch die physikalische Jordan-Frame-Metrik.

Licht folgt Null-Geodäten der physikalischen Metrik:

$$d\tilde{s}^2=0.$$

Zu prüfen sind Konvergenz, Scherung und Lensing-Potential für gegebene baryonische Massenverteilungen.

---

### 13.7 Bullet-Cluster-artige Systeme

Zu prüfen ist, ob das Modell Systeme mit räumlicher Trennung zwischen baryonischer Materie und Lensing-Maxima beschreiben kann.

Ein tragfähiges Modell muss erklären können, warum Lensing-Maxima von der dominanten baryonischen Gasverteilung getrennt erscheinen können.

---

### 13.8 Stabilitätsanalyse

Kleine Störungen werden angesetzt als:

$$\hat{\iota} = \hat{\iota}_0+\delta\iota.$$

Die effektive quadratische Störungswirkung muss mindestens die Stabilitätsbedingungen erfüllen:

$$A(t,r)>0, \qquad B_s(t,r)>0.$$

Damit werden Ghost- und Gradienteninstabilitäten ausgeschlossen.

---

### 13.9 Kosmologische Konsistenz

Zu prüfen ist ein FLRW-Grenzfall mit

$$ds^2 = -dt^2 + a^2(t)d\vec{x}^2$$

und

$$\hat{\iota} = \hat{\iota}(t).$$

Das Modell darf frühe Nukleosynthese, CMB-Anisotropien, Hintergrundexpansion, Strukturbildung und späte kosmologische Expansion nicht in beobachtbar ausgeschlossener Weise verletzen.

---

## 14. Falsifizierbare Kernvorhersagen und Ausschlusskriterien

Der v4.0-Ansatz ist nur dann wissenschaftlich tragfähig, wenn seine Parametrisierungen falsifizierbar bleiben.

Eine konkrete Modellparametrisierung ist zurückzuweisen oder einzuschränken, wenn:

1. die Dimensionsanalyse der gekoppelten Terme scheitert,
2. der lokale Fixpunkt $\hat{\iota}=1$ instabil ist,
3. der disformale Sektor unzulässige Abweichungen im Shapiro-Delay erzeugt,
4. der disformale Sektor unzulässige Abweichungen in der Tensorwellengeschwindigkeit erzeugt,
5. Rotationskurven und Lensing-Daten nicht gleichzeitig abgebildet werden können,
6. Ghost- oder Gradienteninstabilitäten auftreten,
7. kosmologische Randbedingungen verletzt werden,
8. die Fitqualität schlechter ist als bei etablierten Vergleichsmodellen bei gleicher oder geringerer Parameterzahl,
9. die Parameter nur durch starke galaxienspezifische Feinabstimmung funktionieren.

---

## 15. Verhältnis zu bestehenden Theorien

Der v4.0-Ansatz steht in Beziehung zu folgenden Forschungsfeldern:

1. Allgemeine Relativitätstheorie,
2. Skalar-Tensor-Theorien,
3. disformale Metriken,
4. k-Essenz und kinetisches Screening,
5. modifizierte Gravitation,
6. MOND-Phänomenologie,
7. galaktische Rotationskurven,
8. Gravitationslinsen,
9. holografische und informationstheoretische Gravitation,
10. gauge-theoretische Gravitation.

Diese Beziehungen sind als Vergleichs- und Inspirationsrahmen zu verstehen, nicht als Beweis des Atimo-Ansatzes.

Insbesondere Arbeiten zu $4\times U(1)$-artigen Eichformulierungen der Gravitation können als theoretische Vergleichspunkte diskutiert werden. Eine formale Abbildung zwischen solchen Eichstrukturen und

$$\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}$$

bleibt eine offene mathematische Aufgabe.

---

## 16. Status der Modellbehauptungen

| Aussage | Status in v4.0 |
|---|---|
| $x=i^2$ ist als Spezialfall enthalten | Formal definiert |
| $\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}$ ist dimensionslos normiert | Formal definiert |
| $n_{\mathrm{eff}}$ ist logarithmischer Skalenparameter | Formal definiert |
| Lokaler Fixpunkt $\hat{\iota}=1$ | Mathematisch durch Potentialstruktur motiviert |
| Disformale Jordan-Frame-Kopplung | Modellansatz mit Konsistenzbedingungen |
| Kinetisches Screening | Phänomenologische Parametrisierung, noch stabilitätsanalytisch zu prüfen |
| PPN/Cassini-Kompatibilität | Testbereich, noch numerisch zu prüfen |
| GW170817-Kompatibilität | Testbereich, Tensorstörungsanalyse erforderlich |
| SPARC-Rotationskurven | Phänomenologischer Testansatz, noch zu fitten |
| Lensing-Konsistenz | Offener Testbereich |
| Bullet-Cluster-artige Systeme | Offener Testbereich |
| Kosmologische Konsistenz | Offener Testbereich |
| Ersatz der Allgemeinen Relativitätstheorie | Nicht behauptet |
| Widerlegung der Dunklen Materie | Nicht behauptet |
| Vollständige empirische Bestätigung | Nicht behauptet |

Diese Tabelle dient der klaren Trennung zwischen formal definierten Modellbestandteilen, phänomenologischen Testansätzen und noch offenen empirischen Prüfungen.

---

## 17. Reproduzierbarkeit und Datenverfügbarkeit

Diese Version formuliert einen mathematisch-physikalischen Modellrahmen und noch keine abgeschlossene numerische Auswertung. Zur Sicherung der Reproduzierbarkeit werden für nachfolgende Versionen folgende Artefakte empfohlen:

1. ein öffentliches GitHub-Repository mit versioniertem Quelltext,
2. ein reproduzierbares Notebook für die SPARC-Rotationskurven-Fits,
3. eine dokumentierte Parameterdatei für  
   

$$\Theta_{\mathrm{min}} = \{\Delta n,r_c,p,\eta,r_0\},$$
4. ein Skript zur Berechnung von $\chi^2$, AIC und BIC,
5. eine separate Ergebnisdatei für jede getestete Galaxie,
6. eine klare Trennung zwischen Modellannahmen, Fitparametern und empirischen Daten.

Die in diesem Dokument genannten empirischen Testbereiche — insbesondere Cassini/PPN, GW170817, SPARC, Lensing, Bullet-Cluster-artige Systeme und Kosmologie — sind als nachfolgende Validierungsstufen zu verstehen.

Die wissenschaftliche Bewertung des Modells hängt davon ab, ob diese Tests mit nachvollziehbaren numerischen Verfahren reproduzierbar bestanden werden können.

---

## 18. Minimale nächste Arbeitsschritte

Die nächste Arbeitsstufe besteht nicht in einer weiteren sprachlichen Erweiterung des Modells, sondern in der numerischen und analytischen Prüfung der definierten Testbereiche.

Priorisierte Reihenfolge:

1. **Materiequellterm $Q_m$:** Explizite Expansion von  
   

$$Q_m := - \frac{1}{M_\iota^2\sqrt{-g}} \frac{\delta S_m[\psi,\tilde{g}_{\mu\nu}]}{\delta\hat{\iota}}$$
   zur Klärung, ob und in welcher Ordnung Materie ein nichttriviales $\hat{\iota}$-Profil erzeugt.

2. **PPN/Cassini-Test:** Numerische Lösung des lokalen Sonnensystem-Grenzfalls und Extraktion von  
   

$$\gamma_{\mathrm{PPN}}.$$

3. **GW170817-Test:** Linearisierung der Tensorstörungen um einen FLRW-Hintergrund und Berechnung von  
   

$$c_T.$$

4. **SPARC-Test:** Fit von  
   

$$v_{\mathrm{model}}(r) = \sqrt{ r\,a_N(r) \left[ \hat{\iota}_{\mathrm{model}}(r;\Theta_\iota) \right]^{ n_{\mathrm{eff}}(r)-4 } }$$
   gegen SPARC-Rotationskurven.

5. **Lensing-Test:** Berechnung der Lichtablenkung aus der Jordan-Frame-Metrik $\tilde{g}_{\mu\nu}$.

6. **Stabilitätstest:** Prüfung von Ghost- und Gradienteninstabilitäten durch Störungsanalyse.

7. **Kosmologietest:** Prüfung von Hintergrundexpansion, CMB-Anisotropien und frühen kosmologischen Randbedingungen.

---

## 19. Literatur- und Datenreferenzen

1. Bertotti, B., Iess, L., Tortora, P.  
   “A test of general relativity using radio links with the Cassini spacecraft.”  
   *Nature* 425, 374–376 (2003).  
   DOI: 10.1038/nature01997

2. LIGO Scientific Collaboration, Virgo Collaboration, Fermi GBM, INTEGRAL.  
   “Gravitational Waves and Gamma-rays from a Binary Neutron Star Merger: GW170817 and GRB 170817A.”  
   *Astrophysical Journal Letters* 848, L13 (2017).  
   arXiv:1710.05834

3. Lelli, F., McGaugh, S. S., Schombert, J. M.  
   “SPARC: Mass Models for 175 Disk Galaxies with Spitzer Photometry and Accurate Rotation Curves.”  
   *Astronomical Journal* 152, 157 (2016).  
   DOI: 10.3847/0004-6256/152/6/157  
   arXiv:1606.09251

4. Bekenstein, J. D.  
   “The Relation between physical and gravitational geometry.”  
   *Physical Review D* 48, 3641–3647 (1993).

5. Milgrom, M.  
   “A modification of the Newtonian dynamics as a possible alternative to the hidden mass hypothesis.”  
   *Astrophysical Journal* 270, 365–370 (1983).

6. Verlinde, E.  
   “On the Origin of Gravity and the Laws of Newton.”  
   *JHEP* 2011, 29 (2011).  
   arXiv:1001.0785

7. Maldacena, J.  
   “The Large N Limit of Superconformal Field Theories and Supergravity.”  
   *Advances in Theoretical and Mathematical Physics* 2, 231–252 (1998).  
   arXiv:hep-th/9711200

8. Partanen, M., Tulkki, J.  
   “Gravity generated by four one-dimensional unitary gauge symmetries and the Standard Model.”  
   *Reports on Progress in Physics* 88(5), 057802 (2025).  
   DOI: 10.1088/1361-6633/adc82e  
   arXiv:2310.01460

---

## 20. Schlussbemerkung

Dieses Dokument definiert einen mathematisch strukturierten, falsifizierbaren Modellrahmen. Es erhebt nicht den Anspruch, eine empirisch abgeschlossene Alternative zur Allgemeinen Relativitätstheorie, zum Standardmodell der Kosmologie oder zu etablierten Dunkle-Materie-Modellen zu liefern.

Die wissenschaftliche Bewertung hängt von der erfolgreichen Durchführung der beschriebenen Testbereiche und von der numerischen Vergleichbarkeit mit bestehenden Referenzmodellen ab.

Die wissenschaftlich robuste Lesart lautet:

$$\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}$$

als normiertes, dimensionsloses Informationsdichte-Skalengesetz. Es handelt sich nicht um einen abgeschlossenen Beweis einer neuen Gravitationstheorie, sondern um einen testbaren Modellrahmen.

Die nächste notwendige Arbeitsstufe ist analytisch und numerisch:

1. Explizite Expansion des Materiequellterms $Q_m$.
2. Prüfung nichttrivialer Materiesourcing-Profile für $\hat{\iota}$.
3. Quantitative PPN/Cassini-Rechnung.
4. Tensorwellengeschwindigkeit auf FLRW-Hintergrund.
5. Stabilitätsanalyse des kinetischen Screening-Sektors.
6. Ghost-/Degeneracy-Analyse der disformalen Struktur.
7. SPARC-Fits.
8. Lensing-Fits.
9. Bullet-Cluster-artige Tests.
10. Kosmologische Hintergrundprüfung.

Erst nach diesen Tests kann beurteilt werden, ob der v4.0-Ansatz empirische Tragfähigkeit besitzt.

---

# 🇬🇧 ENGLISH / CONDENSED RELEASE ABSTRACT

# Atimo Theorem v4.0  
## Dimension-Variable Information Density Scaling and Covariant Test Framework

**Author:** Roberto Weinhold (Atimo)  
**Version:** 4.0  
**Status:** Mathematical-physical model approach / falsifiable preprint research program  
**Core Generalization:** From $x=i^2$ to a normalized scaling law $\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}$

---

## Abstract

Version 4.0 of the Atimo Theorem formulates the previous quadratic information relation

$$x=i^2$$

as a special case of a more general, dimensionless scaling law. A normalized information density

$$\hat{\iota}:=\frac{\iota}{\iota_\ast}$$

is introduced. A test-case-specific physical response quantity $y$ is also normalized in dimensionless form:

$$\chi:=\frac{y}{y_\ast}.$$

The v4.0 framework defines:

$$\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}.$$

Here, $n_{\mathrm{eff}}$ is an effective scaling parameter derived from the logarithmic response function:

$$n_{\mathrm{eff}} := \frac{d\ln\chi}{d\ln\hat{\iota}}.$$

The local four-dimensional spacetime limit is parameterized in the model by the condition

$$n_{\mathrm{eff}}\to4.$$

Version 4.0 interprets this structure as a mathematically testable framework embedded in a covariant scalar-tensor model. It must be tested and potentially falsified against concrete empirical test cases.

---

## Falsifiable Test Framework

The framework defines structured test areas for validation:

1. Dimensional analysis through normalized reference scales.
2. Mathematical vacuum stability at $\hat{\iota}=1$.
3. Solar-system consistency with Cassini tracking constraints.
4. No observably impermissible deviation of tensor wave speed from $c$.
5. Galactic rotation-curve testing using SPARC data.
6. Gravitational-lensing consistency.
7. Bullet-Cluster-like separation tests.
8. Absence of ghost and gradient instabilities.
9. Compatibility with CMB anisotropies and background expansion limits.

The framework does not claim to replace General Relativity or established dark-matter models. It defines a falsifiable model class whose scientific viability depends on numerical testing, stability analysis, and comparison with established reference models.

Note: The full German master version defines the complete nine-part test structure and the more detailed mathematical model formulation.

---

# 🇪🇸 ESPAÑOL / RESUMEN DE LA VERSIÓN

# Teorema de Atimo v4.0  
## Ley de escala de densidad de información de dimensión variable y marco de prueba covariante

**Autor:** Roberto Weinhold (Atimo)  
**Versión:** 4.0  
**Estado:** Enfoque de modelo matemático-físico / marco de investigación de prepublicación falsable  
**Generalización principal:** De $x=i^2$ a una ley de escala normalizada $\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}$

---

## Resumen

La versión 4.0 del Teorema de Atimo formula la anterior relación cuadrática de información

$$x=i^2$$

como un caso especial de una ley de escala adimensional más general. Se introduce una densidad de información normalizada

$$\hat{\iota}:=\frac{\iota}{\iota_\ast}.$$

La cantidad de respuesta física específica de la prueba $y$ también se normaliza de forma adimensional:

$$\chi:=\frac{y}{y_\ast}.$$

El marco v4.0 define:

$$\chi=\hat{\iota}^{\,n_{\mathrm{eff}}}.$$

Aquí, $n_{\mathrm{eff}}$ es un parámetro de escala efectivo derivado de la función de respuesta logarítmica:

$$n_{\mathrm{eff}} := \frac{d\ln\chi}{d\ln\hat{\iota}}.$$

El límite del espacio-tiempo local de cuatro dimensiones se parametriza en el modelo mediante la condición

$$n_{\mathrm{eff}}\to4.$$

---

## Marco de prueba falsable

El enfoque v4.0 define áreas estructuradas para la evaluación y falsación del modelo:

1. Análisis dimensional.
2. Punto fijo local.
3. Límites del sistema solar, incluidas las restricciones de Cassini.
4. Ondas gravitacionales y velocidad de los modos tensoriales.
5. Curvas de rotación galáctica, incluidas las pruebas con datos SPARC.
6. Lentes gravitacionales, incluida la deflexión de la luz y la separación espacial.
7. Sistemas tipo Bullet Cluster.
8. Análisis de estabilidad.
9. Cosmología y anisotropías del CMB.

El marco no pretende sustituir la Relatividad General ni los modelos establecidos de materia oscura. Define una clase de modelos falsables que debe evaluarse mediante análisis dimensional, estabilidad local, límites de Cassini, velocidad de ondas gravitacionales, curvas de rotación SPARC, lentes gravitacionales, sistemas tipo Bullet Cluster y restricciones cosmológicas.

---
