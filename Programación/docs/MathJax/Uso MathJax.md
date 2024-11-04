<style>
.md-header__button.md-logo img{
    fill: currentcolor;
    display: block;
    height: 3rem;
    width: auto;
}
</style>

# 1. MathJax

MathJax es una librería JavaScript que muestra notación matemática en navegadores web.

## 1.1. ¿Cómo importarla?
Introduciendo en el body de tu página la siguiente etiqueta: ```<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>```



``` HTML hl_lines="9 10" title="HTML" linenums="1"
<!DOCTYPE html>
<html>
<head>
    <title>Tu página con MathJax</title>
    <!-- Otros elementos del head -->
</head>
<body>
    <!-- Contenido de tu página -->
    <!-- Importación de MathJax -->
    <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</body>
</html>
```

## 1.2. ¿Cómo escribir?

Se escribe el caracter $ para abrir y cerrar la simbología matemática.

<center>

| Título                     | Fórmula                                | Código en Markdown                                      |
|:---------------------------:|:----------------------------------------:|:-----------------------------------------------:|
| Variables                 | <span style="font-size:140%">$x_1$, $y_1$, $z_{3,4}$</span>                         | `$x_1$, $y_1$, $z_{3,4}$`                    |
| Cuadrado                  | <span style="font-size:140%">$a^2$, $x^y$, $2^{n-1}$</span>               | `$a^2$, $x^y$, $2^{n-1}$`                    |
| Raíz cuadrada             | <span style="font-size:140%">$\sqrt{9}$, $\sqrt{x}$, $\sqrt[n]{x}$</span>      | `$\sqrt{9}$, $\sqrt{x}$, $\sqrt[n]{x}$`    |
| Logaritmo                 | <span style="font-size:140%">$\log{}x$, $\log_{2}x$</span>                | `$\log{}x$, $\log_{2}x$`                     |
| Fracción                  | <span style="font-size:140%">$\frac{1}{2}$, $\left(-\frac{1}{2}\right)^n$</span>| `$\frac{1}{2}$, $\left(-\frac{1}{2}\right)^n$` |
| Infinito                  | <span style="font-size:140%">$\infty$</span>                              | `$\infty$`                                   |
| Valor absoluto            | <span style="font-size:140%">$\vert{x}\vert$, $\vert\frac{x}{2}\vert$, $\lfloor{x}\rfloor$, $\lceil{x}\rceil$</span>  | `$\vert{x}\vert$, $\vert\frac{x}{2}\vert$, $\lfloor{x}\rfloor$, $\lceil{x}\rceil$` |
| Operación aritmética      | <span style="font-size:140%">$2\times 3$, $6\div 3$</span>                     | `$2\times 3$, $6\div 3$`                     |
| Factorial                 | <span style="font-size:140%">$n!$</span>                          | `$n!$`                                       |
| Funciones trigonométricas | <span style="font-size:140%">$\sin\theta$, $\cos\theta$, $\tan\theta$</span>                | `$\sin\theta$, $\cos\theta$, $\tan\theta$`  |
| Mayor o menor             | <span style="font-size:140%">$a\gt b$, $a\geq b$, $a\lt b$, $a\leq b$</span>               | `$a\gt b$, $a\geq b$, $a\lt b$, $a\leq b$`  |
| Ecuación                  | <span style="font-size:140%">$a=b$, $a\neq b$, $a\approx b$</span>                      | `$a=b$, $a\neq b$, $a\approx b$`            |
| Punto de multiplicación    | <span style="font-size:140%">$a\cdot b=ab$</span>                | `$a\cdot b=ab$`                             |
| División como fracción    | <span style="font-size:140%">$a/b=\frac{a}{b}$</span>                  | `$a/b=\frac{a}{b}$`                          |
| Ecuación trinomial        | <span style="font-size:140%">$a^2 + b^2 = c^2$</span>                             | `$a^2 + b^2 = c^2$`                         |
| Matriz con paréntesis     | <span style="font-size:140%">$\begin{pmatrix} a & b \\ c & d \end{pmatrix}$</span>                          | `$\begin{pmatrix} a & b \\ c & d \end{pmatrix}$` |
| Matriz con corchetes      | <span style="font-size:140%">$\begin{bmatrix} a & b \\ c & d \end{bmatrix}$</span>                          | `$\begin{bmatrix} a & b \\ c & d \end{bmatrix}$` |
| Ecuación matricial        | <span style="font-size:140%">$\begin{vmatrix} a & b \\ c & d \end{vmatrix}=ad-bc$</span>                     | `$\begin{vmatrix} a & b \\ c & d \end{vmatrix}=ad-bc$` |
| Conjunto                  | <span style="font-size:140%">$x\in A$, $A\ni x$, $x\notin A$</span>                      | `$x\in A$, $A\ni x$, $x\notin A$`           |
| Subconjunto               | <span style="font-size:140%">$A\subset B$, $A\subseteq B$, $A \not \subset B$</span>                       | `$A\subset B$, $A\subseteq B$, $A \not \subset B$` |
| Intersección y unión      | <span style="font-size:140%">$A\cap B$, $A\cup B$, $\overline{A}$</span>                           | `$A\cap B$, $A\cup B$, $\overline{A}$`      |
| Fórmula cuadrática        | <span style="font-size:140%">$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$</span>              | `$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$`  |
| Binomio                   | <span style="font-size:140%">$\sqrt{3x-1}+(1+x)^2$</span>                     | `$\sqrt{3x-1}+(1+x)^2$`                      |
| Diferenciación            | <span style="font-size:140%">$f'$, $f^{(n)}$, $D_x f$</span>                    | `$f'$, `$f^{(n)}$', `$D_x f$`                   |
| Integral                  | <span style="font-size:140%">$\int_0^1 f(x) dx$</span>                  | `$\int_0^1 f(x) dx$`                         |
| Integral grande           | <span style="font-size:140%">$\displaystyle \int_{-\infty }^{\infty}f(x)dx$</span>                | `$\displaystyle \int_{-\infty }^{\infty}f(x)dx$`|
| Ejemplo de máximo         | <span style="font-size:140%">$\max(a,b)=\begin{cases}a&(a\geqq b)\\b&(a< b)\end{cases}$</span>          | `$\max(a,b)=\begin{cases}a&(a\geqq b)\\b&(a< b)\end{cases}$`|

</center>

## 1.3. Letras o Simbolos Especiales

<center>

| Name                | Notation | Markdown |
|:-------------------:|:--------:|:--------:|
| Pi     | <span style="font-size:140%">$\pi$</span>        | `$\pi$` |
| O mayúscula      |  <span style="font-size:140%">$\mathcal{O}$ or $O$</span>   | `$\mathcal{O}$ or $O$` |
| Omega mayúscula           | <span style="font-size:140%">$\Omega$</span>        | `$\Omega$` |
| Theta mayúscula          | <span style="font-size:140%">$\Theta$</span>        | `$\Theta$` |
| O minúscula    | <span style="font-size:140%">$o$</span>        | `$o$` |
| Omega minúscula        | <span style="font-size:140%">$\omega$</span>        | `$\omega$` |

</center>