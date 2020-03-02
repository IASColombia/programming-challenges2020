# Números cuadrados y justos

## Problema
Al pequeño John le gustan los palíndromos, y piensa que son justos (que es una palabra elegante para agradable). Un palíndromo es solo un número entero que lee lo mismo hacia atrás y hacia adelante, por lo que 6, 11 y 121 son palíndromos, mientras que 10, 12, 223 y 2244 no lo son (aunque 010 = 10, no consideramos ceros a la izquierda al determinar si un número es un palíndromo).

Recientemente se interesó también en los cuadrados y formó la definición de un número justo y cuadrado: es un número que es un palíndromo y el cuadrado de un palíndromo al mismo tiempo. Por ejemplo, 1, 9 y 121 son justos y cuadrados (siendo palíndromos y cuadrados, respectivamente, de 1, 3 y 11), mientras que 16, 22 y 676 no son justos y cuadrados: 16 no es un palíndromo, 22 no es un cuadrado, y mientras 676 es un palíndromo y un número cuadrado, es el cuadrado de 26, que no es un palíndromo.

Ahora quiere buscar números justos y cuadrados más grandes. Su tarea es, dado un intervalo que el pequeño John está buscando, decirle cuántos números justos y cuadrados hay en el intervalo, para que sepa cuándo los ha encontrado todos.

## Resolviendo este problema

Por lo general, los problemas de Google Code Jam tienen 1 entrada pequeña y 1 entrada grande. Este problema tiene 1 entrada pequeña y 2 entradas grandes. Una vez que haya resuelto la entrada Pequeña, podrá descargar cualquiera de las dos entradas Grandes. Como de costumbre, podrá volver a intentar la entrada Pequeña (con una penalización de tiempo), mientras que solo tendrá una oportunidad en cada una de las entradas Grandes.

## Entrada

La primera línea de la entrada da el número de casos de prueba, las líneas **T**. **T** siguen. Cada línea contiene dos enteros, **A** y **B**, los puntos finales del intervalo que el pequeño John está mirando.

## Salida

Para cada caso de prueba, envíe una línea que contenga "Case #x: y", donde "x" es el número de caso (a partir de 1) y "y" es el número de números cuadrados y justos mayor o igual que **A** y menor o igual que **B**.

## Límites

### Conjunto de datos pequeño
1 ≤ T ≤ 100.
1 ≤ A ≤ B ≤ 1000.

### Primer conjunto de datos grande
1 ≤ T ≤ 10000.
1 ≤ A ≤ B ≤ 1014.

### Segundo conjunto de datos grande
1 ≤ T ≤ 1000.
1 ≤ A ≤ B ≤ 10100.

Muestra

```
Entrada
 
3
1 4
10 120
100 1000
 	
Salida

Case #1: 2
Case #2: 0
Case #3: 2


```
