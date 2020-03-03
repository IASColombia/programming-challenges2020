# Campos cuadrados

## Problema

Te dan **n** puntos en el plano. Se le pide que cubra estos puntos con k cuadrados.

Todos los cuadrados deben ser del mismo tamaño y sus bordes deben ser paralelos a los ejes de coordenadas.

Un punto está cubierto por un cuadrado si se encuentra dentro del cuadrado o en un borde del cuadrado.

Los cuadrados pueden superponerse.

Encuentre la longitud mínima para los bordes de los cuadrados de modo que pueda cubrir los **n** puntos con **k** cuadrados.

## Entrada

La primera línea de entrada da el número de casos, **N**. 
A continuación se presentan casos de prueba. La primera línea de cada prueba contiene dos enteros positivos **n** y **k**. Cada una de las siguientes **n** líneas contiene un punto como dos enteros separados por exactamente un espacio. Ningún punto ocurrirá más de una vez dentro de un caso de prueba.

## Salida

Para cada caso de prueba, debe generar una línea que contenga "Caso #X: Y" (comillas para mayor claridad), donde X es el número del caso de prueba, comenzando desde 1, e Y es la longitud mínima para los bordes de los cuadrados para Ese caso de prueba.

## Límites

* Las coordenadas de los puntos son enteros no negativos menores de 64000.
* 1 ≤ N ≤ 10

## Conjunto de datos pequeño

1 ≤ k <n ≤ 7

## Conjunto de datos grande

1 ≤ k <n ≤ 15

Muestra

```
Entrada
 
2
5 2
1 1
2 2
3 3
6 6
7 8
3 2
3 3
3 6
6 9

Salida

Case #1: 2
Case #2: 3

```
