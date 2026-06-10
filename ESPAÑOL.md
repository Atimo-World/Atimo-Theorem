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
