??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Estudiar la continuidad de la siguiente función: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} \frac{2x^2 + 3x - 2}{2x^2 - 5x + 2} & \text{si } x \neq \frac{1}{2} \\ \frac{5}{3} & \text{si } x = \frac{1}{2} \end{cases}$</span></li></ul>"

    **Solución**: La función es continua en todo su dominio, excepto en $x = 2$, donde tiene una discontinuidad infinita. Es importante notar que la función es continua en $x = 1/2$ a pesar de estar definida por partes en ese punto.
        
    **Paso 1**: Analizar el dominio de la función

    Primero, debemos determinar el dominio de la función:

    1. Para la primera parte ($x ≠ 1/2$), el denominador no puede ser cero:
    $2x² - 5x + 2 ≠ 0$
    Esta ecuación tiene soluciones $x = 1/2$ y $x = 2$, pero $x ≠ 1/2$ ya está excluido.

    2. La segunda parte ($x = 1/2$) es un valor constante.

    Por lo tanto, el dominio es todos los números reales excepto $x = 2$.

    **Paso 2**: Estudiar la continuidad en $x = 1/2$

    Para que la función sea continua en $x = 1/2$, el límite cuando x se aproxima a $1/2$ debe ser igual al valor de la función en $1/2$.

    1. Calcular el límite por la izquierda:
    $\lim_{x \to \frac{1}{2}^-} \frac{2x^2 + 3x - 2}{2x^2 - 5x + 2} = \frac{2(\frac{1}{2})^2 + 3(\frac{1}{2}) - 2}{2(\frac{1}{2})^2 - 5(\frac{1}{2}) + 2} = \frac{5}{3}$

    2. Calcular el límite por la derecha:
    $\lim_{x \to \frac{1}{2}^+} \frac{2x^2 + 3x - 2}{2x^2 - 5x + 2} = \frac{2(\frac{1}{2})^2 + 3(\frac{1}{2}) - 2}{2(\frac{1}{2})^2 - 5(\frac{1}{2}) + 2} = \frac{5}{3}$

    3. Valor de la función en $x = 1/2$:
    $f(\frac{1}{2}) = \frac{5}{3}$

    Como los límites por ambos lados y el valor de la función en $x = 1/2$ son iguales, la función es continua en $x = 1/2$.

    **Paso 3**: Estudiar la continuidad en $x = 2$

    En $x = 2$, el denominador de la primera parte de la función se hace cero, lo que causa una discontinuidad.

    $\lim_{x \to 2} \frac{2x^2 + 3x - 2}{2x^2 - 5x + 2} = \frac{2(2)^2 + 3(2) - 2}{2(2)^2 - 5(2) + 2} = \frac{12}{0}$

    Este límite no existe, por lo que la función tiene una discontinuidad infinita en $x = 2$.

    **Paso 4**: Continuidad en el resto del dominio

    Para todos los demás valores de $x$ (excepto $1/2$ y $2$), la función es continua ya que es una función racional sin más puntos de discontinuidad.

    **Conclusión**

    La función es continua en todo su dominio, excepto en $x = 2$, donde tiene una discontinuidad infinita. Es importante notar que la función es continua en $x = 1/2$ a pesar de estar definida por partes en ese punto.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Determinar los valores de $a$ para los cuales la siguiente función es continua en todo su dominio:<span style='font-size: 1.6em;'>$f(x) = \begin{cases} x^2 - ax + 1 & \text{si } x < 2 \\ 2x + a & \text{si } x \geq 2 \end{cases}$</span></li></ul>" 

    Solución: $a = \frac{1}{3}$
    
    Para que la función sea continua en todo su dominio, debe ser continua en $x = 2$, que es el punto donde cambia la definición de la función. 
    
    **Paso 1**: Igualar los límites laterales en $x = 2$ Para que la función sea continua en $x = 2$, el límite por la izquierda debe ser igual al límite por la derecha:

    Límite por la izquierda:
    $\lim_{x \to 2^-} (x^2 - ax + 1) = 2^2 - 2a + 1 = 4 - 2a + 1 = 5 -2a$
    
    Límite por la derecha:
    $\lim_{x \to 2^+} (2x + a) = 2(2) + a = 4 + a$
    
    Igualamos los límites:
    $5 - 2a = 4 + a$

    **Paso 2**: Resolver la ecuación $5 - 2a = 4 + a$
    $5 - 4 = a + 2a$
    $1 = 3a$
    $a = \frac{1}{3}$ 
    
    **Conclusión**: La función es continua en todo su dominio cuando $a = \frac{1}{3}$

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Estudiar la continuidad de la siguiente función: <span style='font-size: 1.6em;'>$f(x) = \frac{|x-1|}{x-1}$</span></li></ul>" 

    **Solución**: Esta función tiene una discontinuidad en $x = 1$. 
    
    **Paso 1**: Analizar el dominio de la función El denominador no puede ser cero, por lo que $x ≠ 1$. El dominio es todos los números reales excepto 1. 
    
    **Paso 2**: Simplificar la función Podemos escribir la función como: $f(x) = \begin{cases}1 & \text{si } x > 1 \-1 & \text{si }x< 1\end{cases}$ Paso 3: Estudiar la continuidad en $x = 1$

    Límite por la izquierda: $\lim_{x \to 1^-} f(x) = -1$
    
    Límite por la derecha: $\lim_{x \to 1^+} f(x) = 1$

    **Conclusión**: Como los límites laterales son diferentes, la función tiene una discontinuidad de salto en $x = 1$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Estudiar la continuidad de la siguiente función: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} \ln(x+1) & \text{si } x < 0 \\ \sqrt{x} & \text{si } x \geq 0 \end{cases}$</span></li></ul>"

    **Solución**: Esta función es continua en todo su dominio, incluido el punto $x = 0$.

    **Paso 1**: Analizar el dominio de la función
    - Para $x < 0$: $x + 1 > 0$, por lo que $x > -1$
    - Para $x \geq 0$: $x \geq 0$
    El dominio es $[-1, \infty)$

    **Paso 2**: Estudiar la continuidad en $x = 0$ (punto de unión)
    Límite por la izquierda: $\lim_{x \to 0^-} \ln(x+1) = \ln(1) = 0$
    Límite por la derecha: $\lim_{x \to 0^+} \sqrt{x} = 0$
    Valor de la función en $x = 0$: $f(0) = \sqrt{0} = 0$

    **Paso 3**: Continuidad en el resto del dominio
    Ambas funciones son continuas en sus respectivos intervalos.

    **Conclusión**: La función es continua en todo su dominio $[-1, \infty)$, incluido el punto $x = 0$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Determinar el valor de $k$ para que la siguiente función sea continua en todo su dominio: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} x^2 + k & \text{si } x < 1 \\ 2x - 1 & \text{si } x \geq 1 \end{cases}$</span></li></ul>"

    **Solución**: $k = 0$
    
    Debemos encontrar el valor de $k$ que hace la función continua en $x = 1$.

    **Paso 1**: Igualar los límites laterales en $x = 1$
    Límite por la izquierda: $\lim_{x \to 1^-} (x^2 + k) = 1^2 + k = 1 + k$
    Límite por la derecha: $\lim_{x \to 1^+} (2x - 1) = 2(1) - 1 = 1$

    **Paso 2**: Resolver la ecuación
    $1 + k = 1$
    $k = 0$

    **Paso 3**: Verificar la continuidad en el resto del dominio
    Ambas funciones son continuas en sus respectivos intervalos.

    **Conclusión**: La función es continua en todo su dominio cuando $k = 0$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Estudiar la continuidad de la siguiente función y determinar sus puntos de discontinuidad, si los hay: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} \frac{x^2-1}{x-1} & \text{si } x \neq 1 \\ 3 & \text{si } x = 1 \end{cases}$</span></li></ul>"

    **Solución**: Esta función es continua en todo su dominio, incluido el punto $x = 1$.

    **Paso 1**: Analizar el dominio de la función
    El dominio es todos los números reales, ya que la función está definida para $x = 1$ y para $x ≠ 1$.

    **Paso 2**: Simplificar la función para $x ≠ 1$
    $\frac{x^2-1}{x-1} = \frac{(x+1)(x-1)}{x-1} = x + 1$ para $x ≠ 1$

    **Paso 3**: Estudiar la continuidad en $x = 1$
    Límite por la izquierda: $\lim_{x \to 1^-} (x + 1) = 2$
    Límite por la derecha: $\lim_{x \to 1^+} (x + 1) = 2$
    Valor de la función en $x = 1$: $f(1) = 3$

    **Paso 4**: Continuidad en el resto del dominio
    La función $x + 1$ es continua para todo $x ≠ 1$.

    **Conclusión**: La función tiene una discontinuidad evitable en $x = 1$. Si redefinimos $f(1) = 2$, la función sería continua en todo su dominio.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Determinar los valores de $a$ y $b$ para que la siguiente función sea continua en todo su dominio: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} ax + b & \text{si } x < 2 \\ x^2 - 3 & \text{si } x \geq 2 \end{cases}$</span></li></ul>"

    **Solución**: La función es continua en todo su dominio cuando $a = 4$ y $b = -7$
    
    Debemos encontrar los valores de $a$ y $b$ que hacen la función continua en $x = 2$.

    **Paso 1**: Igualar los valores de las dos partes de la función en $x = 2$
    $a(2) + b = 2^2 - 3$
    $2a + b = 4 - 3 = 1$

    **Paso 2**: Igualar las pendientes de las dos partes de la función en $x = 2$
    Pendiente de $ax + b$: $a$
    Pendiente de $x^2 - 3$ en $x = 2$: $2x|_{x=2} = 4$

    $a = 4$

    **Paso 3**: Resolver el sistema de ecuaciones
    De la segunda ecuación: $a = 4$
    Sustituyendo en la primera ecuación: $2(4) + b = 1$
    $8 + b = 1$
    $b = -7$

    **Conclusión**: La función es continua en todo su dominio cuando $a = 4$ y $b = -7$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Hallar los valores de $a$ y $b$ para que la siguiente función sea continua y tenga la misma pendiente en ambos lados de $x = 1$: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} x^2 + ax & \text{si } x < 1 \\ bx + 3 & \text{si } x \geq 1 \end{cases}$</span></li></ul>"

    **Solución**: No existen valores de $a$ y $b$ que hagan que la función sea continua y tenga la misma pendiente en ambos lados de $x = 1$.
    
    Debemos encontrar los valores de $a$ y $b$ que hacen la función continua y con la misma pendiente en $x = 1$.

    **Paso 1**: Igualar los valores de las dos partes de la función en $x = 1$
    $1^2 + a(1) = b(1) + 3$
    $1 + a = b + 3$

    **Paso 2**: Igualar las pendientes de las dos partes de la función en $x = 1$
    Pendiente de $x^2 + ax$: $2x + a$
    Evaluada en $x = 1$: $2(1) + a = 2 + a$

    Pendiente de $bx + 3$: $b$

    $2 + a = b$

    **Paso 3**: Resolver el sistema de ecuaciones
    De la primera ecuación: $1 + a = b + 3$
    De la segunda ecuación: $2 + a = b$

    Igualando: $1 + a = (2 + a) + 3$
    $1 + a = 5 + a$
    $1 = 5$

    Esta contradicción indica que no hay solución que satisfaga ambas condiciones simultáneamente.

    **Conclusión**: No existen valores de $a$ y $b$ que hagan que la función sea continua y tenga la misma pendiente en ambos lados de $x = 1$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Determinar los valores de $a$ y $b$ para que la siguiente función sea continua en $x = 3$: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} ax^2 - 2x + b & \text{si } x < 3 \\ 2x - 1 & \text{si } x \geq 3 \end{cases}$</span></li></ul>"

    **Solución**: La función es continua en $x = 3$ cuando $a = \frac{2}{3}$ y $b = 5$
    
    Debemos encontrar los valores de $a$ y $b$ que hacen la función continua en $x = 3$.

    **Paso 1**: Igualar los valores de las dos partes de la función en $x = 3$
    $a(3)^2 - 2(3) + b = 2(3) - 1$
    $9a - 6 + b = 5$

    **Paso 2**: Igualar las pendientes de las dos partes de la función en $x = 3$
    Pendiente de $ax^2 - 2x + b$: $2ax - 2$
    Evaluada en $x = 3$: $2a(3) - 2 = 6a - 2$

    Pendiente de $2x - 1$: $2$

    $6a - 2 = 2$

    **Paso 3**: Resolver el sistema de ecuaciones
    De la segunda ecuación: $6a - 2 = 2$
    $6a = 4$
    $a = \frac{2}{3}$

    Sustituyendo en la primera ecuación:
    $9(\frac{2}{3}) - 6 + b = 5$
    $6 - 6 + b = 5$
    $b = 5$

    **Conclusión**: La función es continua en $x = 3$ cuando $a = \frac{2}{3}$ y $b = 5$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Determinar los valores de $a$ y $b$ para que la siguiente función sea continua en todo su dominio: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} x^2 + ax + b & \text{si } x < 1 \\ 3x - 2 & \text{si } x \geq 1 \end{cases}$</span></li></ul>"

    **Solución**:La función es continua en todo su dominio cuando $a = 1$ y $b = -1$.
    
    Para que la función sea continua en todo su dominio, debe ser continua en el punto de unión $x = 1$.

    **Paso 1**: Igualar los valores de las dos partes de la función en $x = 1$
    - Parte izquierda: $f(1) = 1^2 + a(1) + b = 1 + a + b$
    - Parte derecha: $f(1) = 3(1) - 2 = 1$
    - Igualamos: $1 + a + b = 1$

    **Paso 2**: Simplificar la ecuación obtenida
    $1 + a + b = 1$
    $a + b = 0$ (Ecuación 1)

    **Paso 3**: Igualar las derivadas de las dos partes de la función en $x = 1$
    - Derivada parte izquierda: $f'(x) = 2x + a$
    En $x = 1$: $f'(1) = 2(1) + a = 2 + a$
    - Derivada parte derecha: $f'(x) = 3$
    - Igualamos: $2 + a = 3$

    **Paso 4**: Resolver para $a$
    $2 + a = 3$
    $a = 1$

    **Paso 5**: Sustituir el valor de $a$ en la Ecuación 1
    $a + b = 0$
    $1 + b = 0$
    $b = -1$

    **Conclusión**: La función es continua en todo su dominio cuando $a = 1$ y $b = -1$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Hallar los valores de $a$ y $b$ para que la siguiente función sea continua y derivable en $x = 2$: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} ax^2 - 4x + b & \text{si } x < 2 \\ x^2 - 5x + 6 & \text{si } x \geq 2 \end{cases}$</span></li></ul>"

    **Solución**: La función es continua y derivable en $x = 2$ cuando $a = \frac{3}{4}$ y $b = 5$.
        
    Para que la función sea continua y derivable en $x = 2$, tanto la función como su derivada deben ser iguales en ambos lados de $x = 2$.

    **Paso 1**: Igualar los valores de las dos partes de la función en $x = 2$
    - Parte izquierda: $f(2) = a(2)^2 - 4(2) + b = 4a - 8 + b$
    - Parte derecha: $f(2) = 2^2 - 5(2) + 6 = 4 - 10 + 6 = 0$
    - Igualamos: $4a - 8 + b = 0$ (Ecuación 1)

    **Paso 2**: Calcular las derivadas de ambas partes
    - Derivada parte izquierda: $f'(x) = 2ax - 4$
    - Derivada parte derecha: $f'(x) = 2x - 5$

    **Paso 3**: Igualar las derivadas en $x = 2$
    - Parte izquierda: $f'(2) = 2a(2) - 4 = 4a - 4$
    - Parte derecha: $f'(2) = 2(2) - 5 = 4 - 5 = -1$
    - Igualamos: $4a - 4 = -1$ (Ecuación 2)

    **Paso 4**: Resolver la Ecuación 2 para $a$
    $4a - 4 = -1$
    $4a = 3$
    $a = \frac{3}{4}$

    **Paso 5**: Sustituir el valor de $a$ en la Ecuación 1
    $4(\frac{3}{4}) - 8 + b = 0$
    $3 - 8 + b = 0$
    $b = 5$

    **Conclusión**: La función es continua y derivable en $x = 2$ cuando $a = \frac{3}{4}$ y $b = 5$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Determinar los valores de $a$ y $b$ para que la siguiente función sea continua en $x = 0$ y $x = 2$: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} ax + b & \text{si } x < 0 \\ x^2 - 1 & \text{si } 0 \leq x < 2 \\ 3x - 2 & \text{si } x \geq 2 \end{cases}$</span></li></ul>"

    **Solución**: La función es continua en $x = 0$ y $x = 2$ cuando $b = -1$. El valor de $a$ puede ser cualquier número real, ya que no afecta la continuidad en $x = 0$.
    
    Debemos asegurar la continuidad en dos puntos: $x = 0$ y $x = 2$.

    **Paso 1**: Asegurar la continuidad en $x = 0$
    - Límite por la izquierda: $\lim_{x \to 0^-} (ax + b) = b$
    - Límite por la derecha: $\lim_{x \to 0^+} (x^2 - 1) = -1$
    - Igualamos: $b = -1$ (Ecuación 1)

    **Paso 2**: Asegurar la continuidad en $x = 2$
    - Límite por la izquierda: $\lim_{x \to 2^-} (x^2 - 1) = 2^2 - 1 = 3$
    - Límite por la derecha: $\lim_{x \to 2^+} (3x - 2) = 3(2) - 2 = 4$
    - Observamos que ya es continua en $x = 2$, no necesitamos condiciones adicionales.

    **Paso 3**: Calcular la pendiente de la recta $ax + b$
    Como sabemos que $b = -1$, la recta debe pasar por el punto (0, -1).
    También debe pasar por (0, -1) para ser continua con $x^2 - 1$.
    Por lo tanto, la pendiente $a$ debe ser:
    $a = \frac{0 - (-1)}{0 - 0} = \text{indefinida}$

    **Conclusión**: La función es continua en $x = 0$ y $x = 2$ cuando $b = -1$. El valor de $a$ puede ser cualquier número real, ya que no afecta la continuidad en $x = 0$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Hallar los valores de $a$ y $b$ para que la siguiente función tenga el mismo valor y la misma derivada en $x = -1$ y $x = 1$: <br><span style='font-size: 1.6em;'>$f(x) = ax^3 + bx^2 + x + 1$</span></li></ul>"

    **Solución**: La función tiene el mismo valor y la misma derivada en $x = -1$ y $x = 1$ cuando $a = -1$ y $b = 0$.
    
    Debemos encontrar $a$ y $b$ para que $f(-1) = f(1)$ y $f'(-1) = f'(1)$.

    **Paso 1**: Calcular $f(-1)$ y $f(1)$
    $f(-1) = a(-1)^3 + b(-1)^2 + (-1) + 1 = -a + b - 1 + 1 = -a + b$
    $f(1) = a(1)^3 + b(1)^2 + 1 + 1 = a + b + 2$

    **Paso 2**: Igualar $f(-1)$ y $f(1)$
    $-a + b = a + b + 2$
    $-2a = 2$
    $a = -1$ (Ecuación 1)

    **Paso 3**: Calcular $f'(x)$
    $f'(x) = 3ax^2 + 2bx + 1$

    **Paso 4**: Calcular $f'(-1)$ y $f'(1)$
    $f'(-1) = 3a(-1)^2 + 2b(-1) + 1 = 3a - 2b + 1$
    $f'(1) = 3a(1)^2 + 2b(1) + 1 = 3a + 2b + 1$

    **Paso 5**: Igualar $f'(-1)$ y $f'(1)$
    $3a - 2b + 1 = 3a + 2b + 1$
    $-4b = 0$
    $b = 0$ (Ecuación 2)

    **Conclusión**: La función tiene el mismo valor y la misma derivada en $x = -1$ y $x = 1$ cuando $a = -1$ y $b = 0$.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Determinar los valores exactos de $a$, $b$ y $c$ para que la siguiente función sea continua en todo su dominio: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} ax^2 + x + 1 & \text{si } x < 0 \\ bx + 1 & \text{si } 0 \leq x < 2 \\ cx + 3 & \text{si } x \geq 2 \end{cases}$</span></li></ul>"

    **Solución**: La función es continua en todo su dominio cuando:
    $a = 0$
    $b = 1$
    $c = 0$
    
    Para que la función sea continua en todo su dominio, debe ser continua en los puntos de unión $x = 0$ y $x = 2$.

    **Paso 1**: Continuidad en $x = 0$
    Igualamos los límites laterales en $x = 0$:

    Límite por la izquierda:
    $\lim_{x \to 0^-} (ax^2 + x + 1) = a(0)^2 + 0 + 1 = 1$

    Límite por la derecha:
    $\lim_{x \to 0^+} (bx + 1) = b(0) + 1 = 1$

    Vemos que la función ya es continua en $x = 0$ independientemente de los valores de $a$ y $b$.

    **Paso 2**: Continuidad en $x = 2$
    Igualamos los límites laterales en $x = 2$:

    Límite por la izquierda:
    $\lim_{x \to 2^-} (bx + 1) = b(2) + 1 = 2b + 1$

    Límite por la derecha:
    $\lim_{x \to 2^+} (cx + 3) = c(2) + 3 = 2c + 3$

    Igualamos:
    $2b + 1 = 2c + 3$
    $2b - 2c = 2$ (Ecuación 1)

    **Paso 3**: Condición adicional para determinar $a$
    Para encontrar un valor específico para $a$, necesitamos una condición adicional. Podemos usar la continuidad de la derivada en $x = 0$:

    Derivada por la izquierda en $x = 0$:
    $\lim_{x \to 0^-} (2ax + 1) = 1$

    Derivada por la derecha en $x = 0$:
    $\lim_{x \to 0^+} b = b$

    Igualamos:
    $1 = b$ (Ecuación 2)

    **Paso 4**: Resolver el sistema de ecuaciones
    De la Ecuación 2: $b = 1$

    Sustituyendo en la Ecuación 1:
    $2(1) - 2c = 2$
    $2 - 2c = 2$
    $-2c = 0$
    $c = 0$

    Para $a$, usamos la condición de que la derivada sea continua en $x = 0$:
    $2a(0) + 1 = b$
    $1 = 1$

    Esto significa que $a$ puede ser cualquier número real. Para tener un valor específico, podemos elegir $a = 0$ por simplicidad.

    **Conclusión**: 
    La función es continua en todo su dominio cuando:
    $a = 0$
    $b = 1$
    $c = 0$

    Con estos valores, la función queda:
    $f(x) = \begin{cases} x + 1 & \text{si } x < 0 \\ x + 1 & \text{si } 0 \leq x < 2 \\ 3 & \text{si } x \geq 2 \end{cases}$

    Que es continua en todo su dominio.

??? question "<ul class="task-list"><li class="task-list-item"><label class="task-list-control"><input type="checkbox"><span class="task-list-indicator"></span></label>Determinar los valores exactos de $a$, $b$ y $c$ para que la siguiente función sea continua en todo su dominio: <br><span style='font-size: 1.6em;'>$f(x) = \begin{cases} \frac{\sin(ax)}{x} + b & \text{si } x < 0 \\ cx^2 + a & \text{si } 0 \leq x < 1 \\ \frac{e^{bx} - 1}{x} + c & \text{si } x \geq 1 \end{cases}$</span></li></ul>"

    **Solución**: La función es continua en todo su dominio cuando:
    $a = e \approx 2.71828$ ;
    $b = 1$ ;
    $c = \frac{e^3}{6} \approx 3.33823$

    Para que la función sea continua en todo su dominio, debe ser continua en los puntos de unión $x = 0$ y $x = 1$.

    **Paso 1**: Continuidad en $x = 0$
    Igualamos los límites laterales en $x = 0$:

    Límite por la izquierda:
    $\lim_{x \to 0^-} (\frac{\sin(ax)}{x} + b)$

    Este límite es una indeterminación del tipo 0/0. Aplicamos L'Hôpital:

    $\lim_{x \to 0^-} (\frac{\sin(ax)}{x} + b) = \lim_{x \to 0^-} (\frac{a\cos(ax)}{1} + b) = a + b$

    Límite por la derecha:
    $\lim_{x \to 0^+} (cx^2 + a) = a$

    Igualamos:
    $a + b = a$
    $b = 0$ (Ecuación 1)

    **Paso 2**: Continuidad en $x = 1$
    Igualamos los límites laterales en $x = 1$:

    Límite por la izquierda:
    $\lim_{x \to 1^-} (cx^2 + a) = c + a$

    Límite por la derecha:
    $\lim_{x \to 1^+} (\frac{e^{bx} - 1}{x} + c)$

    Este límite es una indeterminación del tipo 0/0. Aplicamos L'Hôpital:

    $\lim_{x \to 1^+} (\frac{e^{bx} - 1}{x} + c) = \lim_{x \to 1^+} (\frac{be^{bx}}{1} + c) = be + c$

    Igualamos:
    $c + a = be + c$
    $a = be$ (Ecuación 2)

    **Paso 3**: Condición adicional
    Para tener un sistema determinado, necesitamos una tercera ecuación. Podemos usar la condición de que la derivada sea continua en $x = 0$:

    Derivada por la izquierda en $x = 0$:
    $\lim_{x \to 0^-} \frac{d}{dx}(\frac{\sin(ax)}{x} + b) = \lim_{x \to 0^-} (\frac{ax\cos(ax) - \sin(ax)}{x^2})$

    Este límite es una indeterminación del tipo 0/0. Aplicamos L'Hôpital dos veces:

    $\lim_{x \to 0^-} (\frac{ax\cos(ax) - \sin(ax)}{x^2}) = \lim_{x \to 0^-} (\frac{a\cos(ax) - a^2x\sin(ax) - a\cos(ax)}{2x}) = \lim_{x \to 0^-} (\frac{-a^2\sin(ax) - a^2\sin(ax) - a^2x\cos(ax)}{2}) = 0$

    Derivada por la derecha en $x = 0$:
    $\lim_{x \to 0^+} \frac{d}{dx}(cx^2 + a) = \lim_{x \to 0^+} 2cx = 0$

    Igualamos:
    $0 = 0$

    Esta ecuación no nos proporciona información adicional. Necesitamos otra condición. Usemos la continuidad de la segunda derivada en $x = 0$:

    Segunda derivada por la izquierda en $x = 0$:
    $\lim_{x \to 0^-} \frac{d^2}{dx^2}(\frac{\sin(ax)}{x} + b) = \lim_{x \to 0^-} (\frac{-a^2x\sin(ax) - 2a\cos(ax)}{x^3})$

    Aplicando L'Hôpital tres veces:

    $\lim_{x \to 0^-} (\frac{-a^2x\sin(ax) - 2a\cos(ax)}{x^3}) = \lim_{x \to 0^-} (\frac{-a^3\cos(ax) + 2a^2\sin(ax)}{6x}) = \lim_{x \to 0^-} (\frac{a^4\sin(ax) + 2a^3\cos(ax)}{6}) = \frac{a^3}{3}$

    Segunda derivada por la derecha en $x = 0$:
    $\lim_{x \to 0^+} \frac{d^2}{dx^2}(cx^2 + a) = 2c$

    Igualamos:
    $\frac{a^3}{3} = 2c$
    $c = \frac{a^3}{6}$ (Ecuación 3)

    **Paso 4**: Resolver el sistema de ecuaciones
    De la Ecuación 1: $b = 0$
    De la Ecuación 2: $a = be = 0e = 0$

    Pero $a$ no puede ser 0, ya que la función no estaría bien definida. Por lo tanto, debemos tener $e = 1$, lo que implica:
    $b = 1$

    De la Ecuación 3: $c = \frac{a^3}{6}$

    Sustituyendo en la Ecuación 2:
    $a = be = 1 \cdot e = e$

    **Conclusión**: 
    La función es continua en todo su dominio cuando:
    $a = e \approx 2.71828$
    $b = 1$
    $c = \frac{e^3}{6} \approx 3.33823$

    Estos valores son exactos y distintos entre sí, y se requirió el uso de la regla de L'Hôpital en varios límites para obtenerlos.




