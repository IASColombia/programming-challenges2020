# El viejo mago

## Problema

Un mago hace el siguiente truco de magia. Se pone W bolas blancas y B bolas negras en su sombrero y le pide a alguien del público, por ejemplo _César_, que retire pares de bolas en el orden que _César_ desee. Después de quitar un par de bolas, se le pide a _César_ que vuelva a colocar una bola blanca en el sombrero si son del mismo color. De lo contrario, se le pide que coloque una bola negra en el sombrero.

Cuando _César_ se queda con solo una bola en el sombrero, le pregunta al mago de qué color es la última bola. No hace falta decir que el mago no puede ver el orden en que _César_ hace los reemplazos.

El problema es que el mago, como la mayoría de los magos, es viejo y a veces olvida cómo hacer el truco. Siendo la persona amable que eres, vas a ayudar al mago.

Para cada par de números (W, B) se le solicita que envíe uno de los siguientes:

* **WHITE**: si la última bola del sombrero será blanca con seguridad.
* **BLACK**:  si la última bola del sombrero será negra con seguridad.
* **UNKNOWN**: si no puede estar seguro del color de la última bola.

## Entrada

La primera línea del archivo de entrada contiene el número de casos, N. A continuación se presentan casos de prueba.

Cada caso contiene W y B en una línea separada por un espacio.

## Salida

Para cada caso de entrada, debe generar:

**Case # X: Y**
donde **X** es el número del caso de prueba y **Y** es "WHITE", "BLACK" o "UNKNOWN" como se explicó anteriormente. 

## Límites

* 0 < N ≤ 1000
* W + B > 0

## Conjunto grande de datos

* 0 ≤ W ≤ 1000
* 0 ≤ B ≤ 1000

## Conjunto pequeño de datos

* 0 ≤ W ≤ 109
* 0 ≤ B ≤ 109

# Muestra

```
Entrada

2
3 1
3 6


Salida

Case #1: BLACK
Case #2: WHITE
```

