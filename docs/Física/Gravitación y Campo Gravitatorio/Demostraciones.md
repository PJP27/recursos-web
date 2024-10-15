# Demostarciones

## Tercera Ley de Kepler

$T^2 = k * r^3$ 

O también expresada como: 

$T^2 = \frac{4\pi^2}{GM} * r^3$

**Su Demostración es:**

Igualamos la fuerza centrípeta $F_c$ a la fuerza gravitacional $F_g$ , ya que en una órbita estable estas fuerzas deben estar equilibradas.

$$F_c = F_g$$

Sustituimos las fórmulas para $F_c = m*a_c$ y $F_g = G \frac{Mm}{r^2}$. La masa del objeto en órbita $m$ se cancela en ambos lados.

$$\cancel{m} * a_c = G \frac{M\cancel{m}}{r^2}$$

$$a_c = G \frac{M}{r^2}$$

Sustituimos la fórmula de la aceleración centrípeta $a_c = \frac{v^2}{r}$ en el lado izquierdo. Simplificamos r en ambos lados.

$$\frac{v^2}{\cancel{r}} = G \frac{M}{r^{\cancel{2}}}$$

$$v^2 = G \frac{M}{r}$$

Sustituimos $v = \omega * r$, donde $\omega$ es la velocidad angular:

$$\omega^2 * r^2 = G \frac{M}{r}$$

Sustituimos $\omega = \frac{2\pi}{T}$, donde T es el período orbital:

$$(\frac{2\pi}{T})^2 * r^2 = G \frac{M}{r}$$

Simplificamos:

$$\frac{4\pi^2}{T^2} * r^2 = G \frac{M}{r}$$

Reordenamos para obtener la forma final de la Tercera Ley de Kepler:

$$T^2 = \frac{4\pi^2}{GM} * r^3$$

Esta es la forma matemática de la Tercera Ley de Kepler, que establece que el cuadrado del período orbital es proporcional al cubo del semieje mayor de la órbita.

También, damos a $K$ la siguiente fórmula:

$$K = \frac{4\pi^2}{GM}$$

## Velocidad Orbital

$v_{orb} = \sqrt{G\frac{M}{r}}$ ; Expresado en ($m * s^{-1}$)

**Su Demostración es:**

Igualamos la fuerza centrípeta $F_c$ a la fuerza gravitacional $F_g$, ya que en una órbita estable estas fuerzas deben estar equilibradas.

$$F_c = F_g$$

Sustituimos las fórmulas para $F_c = m*a_c$ y $F_g = G \frac{Mm}{r^2}$. La masa del objeto en órbita $m$ se cancela en ambos lados.

$$\cancel{m} * a_c = G \frac{M\cancel{m}}{r^2}$$

$$a_c = G \frac{M}{r^2}$$

Sustituimos la fórmula de la aceleración centrípeta $a_c = \frac{v^2}{r}$ en el lado izquierdo. Simplificamos r en ambos lados.

$$\frac{v^2}{\cancel{r}} = G \frac{M}{r^{\cancel{2}}}$$

$$v^2 = G \frac{M}{r}$$

Finalmente, tomamos la raíz cuadrada en ambos lados para obtener la fórmula de la velocidad orbital.

$$v_{orb} = \sqrt{G\frac{M}{r}}$$


## Velocidad de Escape

$v_{esc} = \sqrt{2G\frac{M}{r}}$ ; Expresado en ($m * s^{-1}$)

**Su Demostración es:**

La energía mecánica total del sistema debe ser cero para que el objeto escape:

$$E_m = 0$$

La energía mecánica es la suma de la energía cinética y potencial:

$$E_c + E_p = 0$$

Reordenamos la ecuación:

$$E_c = -E_p$$

Sustituimos las fórmulas para $E_c = \frac{1}{2}mv^2$ y $E_p = -\frac{GMm}{r}$:

$$\frac{1}{2}\cancel{m}v^2 = G\frac{M\cancel{m}}{r}$$

Simplificamos y despejamos $v^2$:

$$v^2 = 2G\frac{M}{r}$$

Finalmente, tomamos la raíz cuadrada en ambos lados para obtener la fórmula de la velocidad de escape:

$$v_{esc} = \sqrt{2G\frac{M}{r}}$$


## Energía Cinética en órbita

$E_{c\:orb} = G\frac{Mm}{2r}$ ; Expresado en ($N * m$) que es lo mismo que ($J$)

**Su Demostración es:**

Partimos de la fórmula general de la energía cinética:

$$E_{c\:orb} = \frac{1}{2}m * v_{orb}^2$$

Sustituimos $v_{orb}$ por su fórmula $\sqrt{G\frac{M}{r}}$:

$$E_{c\:orb} = \frac{1}{2}m * (\sqrt{G\frac{M}{r}})^2$$

Simplificamos el cuadrado de la raíz cuadrada:

$$E_{c\:orb} = \frac{1}{2}m * G\frac{M}{r}$$

Reordenamos los términos:

$$E_{c\:orb} = G\frac{Mm}{2r}$$

Esta es la fórmula final para la energía cinética de un objeto en órbita.


## Energía Mecánica en órbita

$E_{m} = -G\frac{Mm}{2r}$ ; Expresado en ($N * m$) que es lo mismo que ($J$)

**Su Demostración es:**

La energía mecánica es la suma de la energía cinética orbital y la energía potencial:

$$E_m = E_{c\:orb} + E_p$$

Sustituimos las fórmulas para $E_{c\:orb} = G\frac{Mm}{2r}$ y $E_p = -G\frac{Mm}{r}$:

$$E_{m} = G\frac{Mm}{2r} + -G\frac{Mm}{r}$$

Factorizamos $GMm$:

$$E_{m} = GMm(\frac{1}{2r} - \frac{2}{2r})$$

Simplificamos la fracción dentro del paréntesis:

$$E_{m} = GMm(-\frac{1}{2r})$$

Simplificamos la expresión final:

$$E_{m} = -G\frac{Mm}{2r}$$

Esta es la fórmula final para la energía mecánica de un objeto en órbita.

## Energía Potencial a Bajas Alturas

$E_{p} = m * g * h$ ; Expresado en ($J$)

**Su Demostración es:**

Partimos de la variación de energía potencial:

$$\Delta{E_p} = E_{p\:f} - E_{p\:0}$$

Sustituimos la fórmula de energía potencial gravitatoria:

$$\Delta{E_p} = -G\frac{Mm}{r_f} - (-G\frac{Mm}{r_0})$$

Simplificamos:

$$\Delta{E_p} = -G\frac{Mm}{r_f} + G\frac{Mm}{r_0}$$

Reordenamos:

$$\Delta{E_p} = G\frac{Mm}{r_0} - G\frac{Mm}{r_f}$$

Factorizamos $GMm$:

$$\Delta{E_p} = GMm(\frac{1}{r_0} - \frac{1}{r_f})$$

Sustituimos $r_0$ por $R_T$ (radio de la Tierra) y $r_f$ por $R_T + h$:

$$\Delta{E_p} = GMm(\frac{1}{R_T} - \frac{1}{R_T + h})$$

Buscamos un denominador común:

$$\Delta{E_p} = GMm(\frac{R_T + h - R_T}{R_T * (R_T + h)})$$

Simplificamos en el numerador:

$$\Delta{E_p} = GMm(\frac{\cancel{R_T} + h - \cancel{R_T}}{R_T * (R_T + h)})$$

$$\Delta{E_p} = GMm(\frac{h}{R_T * (R_T + h)})$$

Para alturas bajas, $h << R_T$, por lo que $R_T + h \approx R_T$:

$$\Delta{E_p} = GMm(\frac{h}{R_T * R_T})$$

$$\Delta{E_p} = GMm(\frac{h}{R_T^2})$$

Reordenamos:

$$\Delta{E_p} = G\frac{Mm * h}{R_T^2}$$

Reconocemos que $g = G\frac{M}{R_T^2}$:

$$\Delta{E_p} = m * g * h$$

Esta es la fórmula final para la energía potencial a bajas alturas.

