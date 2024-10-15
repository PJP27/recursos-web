# Límites, continuidad y asíntotas

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin x}{x}$</span></li></ul>"

    **Solución**: El límite es **1**.

    **Pasos para resolver**:

    1. Este es un límite fundamental que se puede resolver usando la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin x}{x} = \lim_{x \to 0} \frac{(\sin x)'}{(x)'} = \lim_{x \to 0} \frac{\cos x}{1} = 1$

    3. Este límite es importante en muchas aplicaciones de cálculo y física.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x$</span></li></ul>"

    **Solución**: El límite es **e** (número de Euler, aproximadamente 2.71828).

    **Pasos para resolver**:

    1. Este es otro límite fundamental que define el número e.

    2. No se puede resolver directamente con L'Hôpital, pero se puede demostrar que converge a e.

    3. Este límite aparece en problemas de interés compuesto y crecimiento exponencial.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0^+} x^x$</span></li></ul>"

    **Solución**: El límite es **1**.

    **Pasos para resolver**:

    1. Tomamos el logaritmo natural de ambos lados:
      <span style='font-size: 1.6em;'>$\ln(y) = \ln(x^x) = x \ln(x)$

    2. Ahora calculamos el límite de x ln(x) cuando x tiende a 0+:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0^+} x \ln(x) = \lim_{x \to 0^+} \frac{\ln(x)}{1/x}$

    3. Aplicamos L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0^+} \frac{1/x}{-1/x^2} = \lim_{x \to 0^+} -x = 0$

    4. Por lo tanto,<span style='font-size: 1.6em;'>$\ln(y) = 0$, lo que implica que $y = e^0 = 1$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} (x^2 - x) - (x^2 + 2x)$</span></li></ul>"

    **Solución**: El límite es **-∞**.

    **Pasos para resolver**:

    1. Simplificamos la expresión:
       $(x^2 - x) - (x^2 + 2x) = -3x$

    2. Cuando x tiende a infinito, -3x tiende a -∞.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{x^3 - 1}{x - 1}$</span></li></ul>"

    **Solución**: El límite es **3**.

    **Pasos para resolver**:

    1. Este es un límite de la forma 0/0, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{x^3 - 1}{x - 1} = \lim_{x \to 1} \frac{3x^2}{1} = 3$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{\ln(x)}{x}$</span></li></ul>"

    **Solución**: El límite es **0**.

    **Pasos para resolver**:

    1. Este es un límite de la forma ∞/∞, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{\ln(x)}{x} = \lim_{x \to \infty} \frac{1/x}{1} = \lim_{x \to \infty} \frac{1}{x} = 0$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{e^x - 1}{x}$</span></li></ul>"

    **Solución**: El límite es **1**.

    **Pasos para resolver**:

    1. Este es un límite de la forma 0/0, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{e^x - 1}{x} = \lim_{x \to 0} \frac{e^x}{1} = e^0 = 1$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \left(\sqrt{x^2 + x} - x\right)$</span></li></ul>"

    **Solución**: El límite es **1/2**.

    **Pasos para resolver**:

    1. Multiplicamos y dividimos por el conjugado:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} (\sqrt{x^2 + x} - x) \cdot \frac{\sqrt{x^2 + x} + x}{\sqrt{x^2 + x} + x}$

    2. Simplificamos:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{x}{\sqrt{x^2 + x} + x}$

    3. Dividimos numerador y denominador por x:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{1}{\sqrt{1 + \frac{1}{x}} + 1} = \frac{1}{2}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\tan x}{x}$</span></li></ul>"

    **Solución**: El límite es **1**.

    **Pasos para resolver**:

    1. Este es otro límite fundamental similar al de (sin x)/x.

    2. Podemos usar la identidad trigonométrica: tan x = sin x / cos x
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\tan x}{x} = \lim_{x \to 0} \frac{\sin x}{x \cos x}$

    3. Separamos el límite:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin x}{x} \cdot \lim_{x \to 0} \frac{1}{\cos x} = 1 \cdot 1 = 1$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \left(1 + \frac{2}{x}\right)^x$</span></li></ul>"

    **Solución**: El límite es **e^2**.

    **Pasos para resolver**:

    1. Este límite es una variación del límite que define e.

    2. Podemos reescribirlo como:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \left(\left(1 + \frac{2}{x}\right)^{\frac{x}{2}}\right)^2$

    3. El límite interno es e, por lo que el resultado es $e^2$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(3x)}{x}$</span></li></ul>"

    **Solución**: El límite es **3**.

    **Pasos para resolver**:

    1. Este límite es similar al límite fundamental<span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin x}{x} = 1$.

    2. Reescribimos el límite:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(3x)}{3x} \cdot 3$

    3. El primer término es el límite fundamental, por lo que el resultado es 3.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{x^3 + 2x^2}{3x^3 - x}$</span></li></ul>"

    **Solución**: El límite es **1/3**.

    **Pasos para resolver**:

    1. Dividimos numerador y denominador por x^3:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{1 + \frac{2}{x}}{3 - \frac{1}{x^2}}$

    2. Cuando x tiende a infinito, los términos con x en el denominador tienden a cero:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{1 + 0}{3 - 0} = \frac{1}{3}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{e^x - e^{-x}}{2x}$</span></li></ul>"

    **Solución**: El límite es **1**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{e^x - e^{-x}}{2x} = \lim_{x \to 0} \frac{e^x + e^{-x}}{2} = \frac{e^0 + e^0}{2} = 1$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{\ln(x)}{x - 1}$</span></li></ul>"

    **Solución**: El límite es **1**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{\ln(x)}{x - 1} = \lim_{x \to 1} \frac{1/x}{1} = 1$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sqrt{1+x} - 1}{x}$</span></li></ul>"

    **Solución**: El límite es **1/2**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sqrt{1+x} - 1}{x} = \lim_{x \to 0} \frac{1}{2\sqrt{1+x}} = \frac{1}{2}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} (1 - \cos\frac{1}{x})x^2$</span></li></ul>"

    **Solución**: El límite es **1/2**.

    **Pasos para resolver**:

    1. Hacemos el cambio de variable u = 1/x, entonces x → ∞ implica u → 0:
      <span style='font-size: 1.6em;'>$\lim_{u \to 0} \frac{1 - \cos u}{u^2}$

    2. Aplicamos L'Hôpital dos veces:
       Primera vez:<span style='font-size: 1.6em;'>$\lim_{u \to 0} \frac{\sin u}{2u}$
       Segunda vez:<span style='font-size: 1.6em;'>$\lim_{u \to 0} \frac{\cos u}{2} = \frac{1}{2}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(5x)}{\sin(3x)}$</span></li></ul>"

    **Solución**: El límite es **5/3**.

    **Pasos para resolver**:

    1. Reescribimos el límite:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(5x)}{5x} \cdot \frac{3x}{\sin(3x)} \cdot \frac{5}{3}$

    2. Reconocemos los límites fundamentales:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(5x)}{5x} = 1$</span>y<span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{3x}{\sin(3x)} = 1$

    3. Por lo tanto, el límite se reduce a:
       $1 \cdot 1 \cdot \frac{5}{3} = \frac{5}{3}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\ln(1+2x) - 2x}{x^2}$</span></li></ul>"

    **Solución**: El límite es **-2**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0, lo que sugiere usar la regla de L'Hôpital dos veces.

    2. Primera aplicación de L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\frac{2}{1+2x} - 2}{2x} = \lim_{x \to 0} \frac{2-2-4x}{2x(1+2x)}$

    3. Segunda aplicación de L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{-4}{2(1+2x) + 4x(1+2x)} = -2$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \left(x\sin\frac{1}{x}\right)$</span></li></ul>"

    **Solución**: El límite es **1**.

    **Pasos para resolver**:

    1. Este límite involucra una función trigonométrica con un argumento que tiende a 0.

    2. Hacemos el cambio de variable u = 1/x, entonces x → ∞ implica u → 0:
      <span style='font-size: 1.6em;'>$\lim_{u \to 0} \frac{\sin u}{u}$

    3. Reconocemos el límite fundamental:
      <span style='font-size: 1.6em;'>$\lim_{u \to 0} \frac{\sin u}{u} = 1$

    4. Por lo tanto, el límite original es 1.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{(1+x)^{\frac{1}{x}} - e}{x}$</span></li></ul>"

    **Solución**: El límite es **e/2**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0, lo que sugiere usar la regla de L'Hôpital.

    2. Antes de aplicar L'Hôpital, notamos que $(1+x)^{\frac{1}{x}}$</span>es una forma del número e.

    3. Aplicamos L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{d}{dx}[(1+x)^{\frac{1}{x}} - e]$

    4. Derivamos usando la regla de la cadena y la regla del logaritmo:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} (1+x)^{\frac{1}{x}} \cdot \left(\frac{1}{(1+x)x} - \frac{\ln(1+x)}{x^2}\right)$

    5. Cuando x → 0, $(1+x)^{\frac{1}{x}} \to e$, y podemos usar la expansión de Taylor de ln(1+x):
       $e \cdot \lim_{x \to 0} \left(\frac{1}{x} - \frac{1}{x^2}(x - \frac{x^2}{2} + ...)\right)$

    6. Simplificamos:
       $e \cdot \lim_{x \to 0} \frac{1}{2x} = \frac{e}{2}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 3} \frac{x^2 - 9}{x - 3}$</span></li></ul>"

    **Solución**: El límite es **6**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 3, lo que sugiere usar factorización o la regla de L'Hôpital.

    2. Factorizamos el numerador:
      <span style='font-size: 1.6em;'>$\lim_{x \to 3} \frac{(x+3)(x-3)}{x - 3}$

    3. Cancelamos (x-3):
      <span style='font-size: 1.6em;'>$\lim_{x \to 3} (x+3) = 3 + 3 = 6$

    4. Este límite representa la derivada de x^2 en x = 3.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 2} \frac{\sqrt{x+2} - 2}{x - 2}$</span></li></ul>"

    **Solución**: El límite es **1/4**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 2, lo que sugiere usar racionalización o la regla de L'Hôpital.

    2. Racionalizamos multiplicando numerador y denominador por<span style='font-size: 1.6em;'>$\sqrt{x+2} + 2$:
      <span style='font-size: 1.6em;'>$\lim_{x \to 2} \frac{(\sqrt{x+2} - 2)(\sqrt{x+2} + 2)}{(x - 2)(\sqrt{x+2} + 2)}$

    3. Simplificamos:
      <span style='font-size: 1.6em;'>$\lim_{x \to 2} \frac{x+2 - 4}{(x - 2)(\sqrt{x+2} + 2)} = \lim_{x \to 2} \frac{1}{\sqrt{x+2} + 2}$

    4. Evaluamos directamente:
      <span style='font-size: 1.6em;'>$\frac{1}{\sqrt{2+2} + 2} = \frac{1}{4}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{x^3 - 1}{x^2 - 1}$</span></li></ul>"

    **Solución**: El límite es **3/2**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 1, lo que sugiere usar factorización.

    2. Factorizamos numerador y denominador:
      <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{(x-1)(x^2+x+1)}{(x-1)(x+1)}$

    3. Cancelamos (x-1):
      <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{x^2+x+1}{x+1}$

    4. Evaluamos directamente:
      <span style='font-size: 1.6em;'>$\frac{1^2+1+1}{1+1} = \frac{3}{2}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 4} \frac{\sqrt{x} - 2}{x - 4}$</span></li></ul>"

    **Solución**: El límite es **1/4**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 4, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 4} \frac{\frac{1}{2\sqrt{x}}}{1} = \frac{1}{2\sqrt{4}} = \frac{1}{4}$

    3. Este límite representa la derivada de<span style='font-size: 1.6em;'>$\sqrt{x}$</span>en x = 4.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to -1} \frac{|x+1|}{x+1}$</span></li></ul>"

    **Solución**: El límite no existe.

    **Pasos para resolver**:

    1. Este límite involucra un valor absoluto, lo que sugiere considerar los límites laterales.

    2. Límite por la derecha (x > -1):
      <span style='font-size: 1.6em;'>$\lim_{x \to -1^+} \frac{|x+1|}{x+1} = \lim_{x \to -1^+} \frac{x+1}{x+1} = 1$

    3. Límite por la izquierda (x < -1):
      <span style='font-size: 1.6em;'>$\lim_{x \to -1^-} \frac{|x+1|}{x+1} = \lim_{x \to -1^-} \frac{-(x+1)}{x+1} = -1$

    4. Como los límites laterales son diferentes, el límite no existe.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(5x)}{\sin(2x)}$</span></li></ul>"

    **Solución**: El límite es **5/2**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 0, pero podemos usar los límites fundamentales de funciones trigonométricas.

    2. Reescribimos el límite:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(5x)}{5x} \cdot \frac{2x}{\sin(2x)} \cdot \frac{5}{2}$

    3. Reconocemos los límites fundamentales:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(5x)}{5x} = 1$</span>y<span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{2x}{\sin(2x)} = 1$

    4. Por lo tanto, el límite se reduce a:
       $1 \cdot 1 \cdot \frac{5}{2} = \frac{5}{2}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \pi} \frac{\sin(x)}{x - \pi}$</span></li></ul>"

    **Solución**: El límite es **-1**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = π, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to \pi} \frac{\cos(x)}{1} = \cos(\pi) = -1$

    3. Este límite está relacionado con la derivada de sin(x) en x = π.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 2} \frac{x^2 - 4}{x - 2}$</span></li></ul>"

    **Solución**: El límite es **4**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 2, lo que sugiere usar factorización o la regla de L'Hôpital.

    2. Factorizamos el numerador:
      <span style='font-size: 1.6em;'>$\lim_{x \to 2} \frac{(x+2)(x-2)}{x - 2}$

    3. Cancelamos (x-2):
      <span style='font-size: 1.6em;'>$\lim_{x \to 2} (x+2) = 2 + 2 = 4$

    4. Este límite representa la derivada de x^2 en x = 2.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{x^3 - 1}{x - 1}$</span></li></ul>"

    **Solución**: El límite es **3**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 1, lo que sugiere usar factorización o la regla de L'Hôpital.

    2. Factorizamos el numerador:
      <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{(x-1)(x^2+x+1)}{x - 1}$

    3. Cancelamos (x-1):
      <span style='font-size: 1.6em;'>$\lim_{x \to 1} (x^2+x+1) = 1^2 + 1 + 1 = 3$

    4. Este límite representa la derivada de x^3 en x = 1.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(3x)}{\sin(2x)}$</span></li></ul>"

    **Solución**: El límite es **3/2**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 0, pero podemos usar los límites fundamentales de funciones trigonométricas.

    2. Reescribimos el límite:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(3x)}{3x} \cdot \frac{2x}{\sin(2x)} \cdot \frac{3}{2}$

    3. Reconocemos los límites fundamentales:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{\sin(3x)}{3x} = 1$</span>y<span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{2x}{\sin(2x)} = 1$

    4. Por lo tanto, el límite se reduce a:
       $1 \cdot 1 \cdot \frac{3}{2} = \frac{3}{2}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \infty} (\sqrt{x^2 + 1} - x)$</span></li></ul>"

    **Solución**: El límite es **0**.

    **Pasos para resolver**:

    1. Este límite es una indeterminación del tipo ∞ - ∞.

    2. Multiplicamos y dividimos por el conjugado:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} (\sqrt{x^2 + 1} - x) \cdot \frac{\sqrt{x^2 + 1} + x}{\sqrt{x^2 + 1} + x}$

    3. Simplificamos:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{x^2 + 1 - x^2}{\sqrt{x^2 + 1} + x} = \lim_{x \to \infty} \frac{1}{\sqrt{x^2 + 1} + x}$

    4. Dividimos numerador y denominador por x:
      <span style='font-size: 1.6em;'>$\lim_{x \to \infty} \frac{1/x}{\sqrt{1 + 1/x^2} + 1} = 0$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{e^x - 1 - x}{x^2}$</span></li></ul>"

    **Solución**: El límite es **1/2**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = 0, lo que sugiere usar la regla de L'Hôpital dos veces.

    2. Primera aplicación de L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{e^x - 1}{2x} = \frac{0}{0}$

    3. Segunda aplicación de L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 0} \frac{e^x}{2} = \frac{1}{2}$

    4. Este límite está relacionado con la segunda derivada de e^x en x = 0.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to \pi/2} \frac{\cos x}{x - \pi/2}$</span></li></ul>"

    **Solución**: El límite es **-1**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0/0 cuando x = π/2, lo que sugiere usar la regla de L'Hôpital.

    2. Aplicando L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to \pi/2} \frac{-\sin x}{1} = -\sin(\pi/2) = -1$

    3. Este límite está relacionado con la derivada de cos(x) en x = π/2.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Calcula el límite: <span style='font-size: 1.6em;'>$\lim_{x \to 1} (1-x)^{\tan(\pi x/2)}$</span></li></ul>"

    **Solución**: El límite es **e^{-\pi/2}**.

    **Pasos para resolver**:

    1. Este límite tiene la forma 0^∞ cuando x = 1, lo que sugiere usar logaritmos.

    2. Tomamos el logaritmo natural:
      <span style='font-size: 1.6em;'>$\ln(y) = \tan(\pi x/2) \ln(1-x)$

    3. Aplicamos la regla de L'Hôpital:
      <span style='font-size: 1.6em;'>$\lim_{x \to 1} \frac{\ln(1-x)}{\cot(\pi x/2)} = \lim_{x \to 1} \frac{-1/(1-x)}{-\pi/2 \csc^2(\pi x/2)} = -\frac{2}{\pi}$

    4. Por lo tanto,<span style='font-size: 1.6em;'>$\ln(y) = -\pi/2$, lo que implica $y = e^{-\pi/2}$.
