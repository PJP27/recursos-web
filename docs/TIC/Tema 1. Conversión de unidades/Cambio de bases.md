

### Decimal a Binario

Para convertir un número decimal n a binario:

1. Divide n por 2 repetidamente.
2. Anota los restos en orden inverso.

Ejemplo: 53₁₀ a binario

53 ÷ 2 = 26 resto 1
26 ÷ 2 = 13 resto 0
13 ÷ 2 = 6 resto 1
6 ÷ 2 = 3 resto 0
3 ÷ 2 = 1 resto 1
1 ÷ 2 = 0 resto 1

Resultado: 53₁₀ = 110101₂

### Binario a Decimal

Para convertir un número binario a decimal, multiplica cada dígito por la potencia de 2 correspondiente y suma los resultados:

n₁₀ = Σ(dᵢ · 2ⁱ)

Donde dᵢ es el dígito en la posición i (de derecha a izquierda) y k es la longitud del número binario menos 1.

Ejemplo: 110101₂ a decimal

110101₂ = 1·2⁵ + 1·2⁴ + 0·2³ + 1·2² + 0·2¹ + 1·2⁰ = 32 + 16 + 0 + 4 + 0 + 1 = 53₁₀

### Decimal a Hexadecimal

Similar al proceso de decimal a binario, pero dividiendo por 16:

1. Divide n por 16 repetidamente.
2. Anota los restos en orden inverso, usando A-F para valores 10-15.

Ejemplo: 2748₁₀ a hexadecimal

2748 ÷ 16 = 171 resto 12 (C)
171 ÷ 16 = 10 resto 11 (B)
10 ÷ 16 = 0 resto 10 (A)

Resultado: 2748₁₀ = ABC₁₆

### Hexadecimal a Decimal

Similar a binario a decimal, pero usando potencias de 16:

n₁₀ = Σ(dᵢ · 16ⁱ)

Ejemplo: ABC₁₆ a decimal

ABC₁₆ = 10·16² + 11·16¹ + 12·16⁰ = 2560 + 176 + 12 = 2748₁₀

### Binario a Hexadecimal

Agrupa los dígitos binarios en grupos de 4 (de derecha a izquierda) y conviértelos a sus equivalentes hexadecimales:

0000 = 0, 0001 = 1, ..., 1111 = F

Ejemplo: 110101011100₂ a hexadecimal

110101011100₂ = 1101 0101 1100₂ = D5C₁₆

### Hexadecimal a Binario

Convierte cada dígito hexadecimal a su equivalente binario de 4 bits:

Ejemplo: D5C₁₆ a binario

D5C₁₆ = 1101 0101 1100₂ = 110101011100₂

### Conversión entre Bases Arbitrarias

Para convertir un número n de base a a base b:

1. Convierte n de base a a decimal.
2. Convierte el resultado decimal a base b.

La fórmula general para convertir de base a a decimal es:

n₁₀ = Σ(dᵢ · aⁱ)

Y para convertir de decimal a base b, divide repetidamente por b y anota los restos en orden inverso.