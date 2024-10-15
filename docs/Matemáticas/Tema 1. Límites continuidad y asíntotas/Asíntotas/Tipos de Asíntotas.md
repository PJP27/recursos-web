# TIPOS DE ASÍNTOTAS

## Asíntotas Verticales $x = a$

### Identificarlas

* Siendo $x = a$ la Asíntota Vertical
* Para adivinar a donde haya una A.V. Se busca un valor de $x$ donde se cancele el denominador. $denominador = 0$
* Para saber si en un punto de $x$ existe una Asíntota Vertical, se usa el siguiente límite: $\lim_{x \to a} f(x) = \pm\infty$. Si en el límite: $\lim_{x \to a} f(x) = \pm\infty$, no sale infinito, no existe una Asíntota Vertical en ese punto.


!!! Warning "Atención"

    Para los polinomios $P(x)$, no existen Asíntotas Verticales.

!!! Info 

    Las divisiones de polinomios $\frac{P(x)}{Q(x)}$ sí pueden tener A.V.

### Comportamiento

- Por la Derecha: $\lim_{x \to a^+}  f(x) = \pm\infty$
    * Siendo $\pm\infty$ lo que determinará si va hacia arriba o hacia abajo por la derecha.

- Por la Derecha: $\lim_{x \to a^-}  f(x) = \pm\infty$
    * Siendo $\pm\infty$ lo que determinará si va hacia arriba o hacia abajo por la izquierda.

## Asíntotas Horizontal $y = a$

### Identificarlas

* Siendo $y = a$ la Asíntota Vertical
* Para saber si en un punto de $x$ existe una Asíntota Vertical, se usa el siguiente límite: $\lim_{x \to +\infty} f(x) = a$ y $\lim_{x \to -\infty} f(x) = a$. Si en el límite: $\lim_{x \to \pm\infty} f(x) = a$, no sale un número , no existe una Asíntota Horizontal.

!!! Info 

    Ambos límites hacia $+\infty$ y $-\infty$ suelen coincidir.

### Comportamiento

- Por la Derecha: $\lim_{x \to  +\infty} f(x) - a = 0^\pm$
    * Siendo $0^\pm$ lo que determinará si va por arriba o por abajo por la derecha.

- Por la Derecha: $\lim_{x \to  -\infty} f(x) - a = 0^\pm$
    * Siendo $0^\pm$ lo que determinará si va por arriba o por abajo por la izquierda.

## Asíntotas Oblicua $f(x) = mx + b$

!!! info "Consejo"
    
    Normalmente las A.O. se dan en funciones como: $\frac{P(x)}{Q(x)}$ Donde $P(x)$ tiene un gardo más que $Q(x)$

=== "1.er Forma (larga)"
    ### 1.er Forma (larga)
    #### Identificarlas

    * Siendo $y = mx + b$ la Asíntota Vertical
    * Para encontrar $m$ se usa la siguiente expresión: $\lim_{x \to  \pm\infty} \frac{f(x)}{x} = m$ 
    * Para encontrar $b$ se usa la siguiente expresión: $\lim_{x \to  \pm\infty} (f(x) - mx) =b$ 

    #### Comportamiento

    - Por la Derecha: $\lim_{x \to  +\infty} f(x) - mx + b = 0^\pm$ 
        * Siendo $0^\pm$ lo que determinará si va por arriba o por abajo por la derecha.

    - Por la Derecha: $\lim_{x \to  -\infty} f(x) - mx + b = 0^\pm$ 
        * Siendo $0^\pm$ lo que determinará si va por arriba o por abajo por la izquierda.

=== "2.da Forma (corta)"
    ### 2.da Forma (corta)
    #### Identificarlas

    * Se dividen ambos polinomios

    !!! example "Ejemplo"

        $f(x) = \frac{x^2 - 3x + 4}{2x + 2}$; $C=\frac{1}{2}x + 2$;  $R= 8$.

    * El cociente ($C$) será la Asíntota Oblicua.
    * Usando el resto ($R$) podremos ver el comportamiento.

    #### Comportamiento

    - Por la Derecha: $\lim_{x \to  +\infty} \frac{R}{Q(x)} = 0^\pm$; siendo $R$ el resto y $Q(x)$ el divisor.
        * Siendo $0^\pm$ lo que determinará si va por arriba o por abajo por la derecha.

    - Por la Derecha: $\lim_{x \to  +\infty} \frac{R}{Q(x)} = 0^\pm$; siendo $R$ el resto y $Q(x)$ el divisor.
        * Siendo $0^\pm$ lo que determinará si va por arriba o por abajo por la izquierda.
