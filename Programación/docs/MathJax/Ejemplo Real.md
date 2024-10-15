<style>
.md-header__button.md-logo img{
    fill: currentcolor;
    display: block;
    height: 3rem;
    width: auto;
}
</style>

## Aplicación para ejercicios de matemáticas

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Analiza y grafica la función racional: <span style='font-size: 1.6em;'>$f(x) = \frac{2x^2 + 3x + 1}{x^2 - 4}$</span></li></ul>"

     Asíntotas Verticales

    Las asíntotas verticales ocurren cuando el denominador es igual a cero:
    $x^2 - 4 = 0$
    $x = \pm 2$
    Por lo tanto, las asíntotas verticales están en x = 2 y x = -2.

     Comportamiento de las Asíntotas Verticales

    Para x = 2:

    $\lim_{x \to 2^-} f(x) = -\infty$

    $\lim_{x \to 2^+} f(x) = +\infty$

    Para x = -2:

    $\lim_{x \to -2^-} f(x) = +\infty$

    $\lim_{x \to -2^+} f(x) = -\infty$

     Asíntota Horizontal

    Para encontrar la asíntota horizontal, calculamos el límite cuando x tiende a infinito:

    $\lim_{x \to \pm \infty} \frac{2x^2 + 3x + 1}{x^2 - 4} = \lim_{x \to \pm \infty} \frac{2 + \frac{3}{x} + \frac{1}{x^2}}{1 - \frac{4}{x^2}} = 2$

    La asíntota horizontal está en y = 2.

     Comportamiento de la Asíntota Horizontal

    $\lim_{x \to +\infty} (f(x) - 2) = 0^+$

    $\lim_{x \to -\infty} (f(x) - 2) = 0^-$

    La función se acerca a la asíntota horizontal y = 2 por arriba tanto cuando x tiende a +∞ como a -∞.

     Gráfica de la función

    <iframe src="https://www.desmos.com/calculator/zzqpznlbtl?embed" width="100%" height="500" style="border: 1px solid ccc" frameborder=0></iframe>

    Esta gráfica muestra claramente el comportamiento de la función cerca de las asíntotas verticales y cómo se aproxima a la asíntota horizontal a medida que x se aleja del origen.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Analiza y grafica la función racional: <span style='font-size: 1.6em;'>$f(x) = \frac{x^2 + 3x - 2}{x^2 - 4}$</span></li></ul>"

     Asíntotas Verticales

    Para encontrar las asíntotas verticales, igualamos el denominador a cero:
    $x^2 - 4 = 0$
    $(x+2)(x-2) = 0$
    $x = -2$ o $x = 2$

    Por lo tanto, las asíntotas verticales están en $x = -2$ y $x = 2$.

     Comportamiento

    Para $x = -2$:

    $\lim_{x \to -2^-} f(x) = -\infty$

    $\lim_{x \to -2^+} f(x) = +\infty$

    Para $x = 2$:

    $\lim_{x \to 2^-} f(x) = -\infty$

    $\lim_{x \to 2^+} f(x) = +\infty$

     Asíntota Horizontal

    Para encontrar la asíntota horizontal, calculamos:

    $\lim_{x \to \pm\infty} \frac{x^2 + 3x - 2}{x^2 - 4} = \lim_{x \to \pm\infty} \frac{1 + \frac{3}{x} - \frac{2}{x^2}}{1 - \frac{4}{x^2}} = 1$

    La asíntota horizontal está en $y = 1$.

     Comportamiento

    $\lim_{x \to +\infty} (f(x) - 1) = 0^+$

    $\lim_{x \to -\infty} (f(x) - 1) = 0^+$

    La función se acerca a la asíntota horizontal $y = 1$ por arriba tanto cuando $x$ tiende a $+\infty$ como a $-\infty$.

     Gráfica de la función

    <iframe src="https://www.desmos.com/calculator/cntdwuvroq?embed" width="100%" height="500" style="border: 1px solid ccc" frameborder=0></iframe>

    Esta gráfica muestra el comportamiento de la función cerca de las asíntotas verticales y cómo se aproxima a la asíntota horizontal.

## Aplicación para Demostraciones Físicas

**Tercera Ley de Kepler**

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