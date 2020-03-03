# Lenguaje alienigena

## Problema

Después de años de estudio, los científicos de Google Labs han descubierto un lenguaje extraño transmitido desde un planeta lejano. El idioma alienígena es muy único en el sentido de que cada palabra consta de exactamente **L** letras minúsculas. Además, hay exactamente palabras **D** en este lenguaje.

Una vez que se construyó el diccionario de todas las palabras en el idioma alienígena, el siguiente avance fue descubrir que los extraterrestres han estado transmitiendo mensajes a la Tierra durante la última década. Desafortunadamente, estas señales se debilitan debido a la distancia entre nuestros dos planetas y algunas de las palabras pueden malinterpretarse. Para ayudarlos a descifrar estos mensajes, los científicos le han pedido que idee un algoritmo que determine el número de posibles interpretaciones para un patrón dado.

Un patrón consta de exactamente L fichas. Cada ficha es una letra minúscula (los científicos están muy seguros de que es la letra) o un grupo de letras minúsculas únicas rodeadas de paréntesis (y). Por ejemplo: (ab) d (dc) significa que la primera letra es a o b, la segunda letra es definitivamente d y la última letra es d o c. Por lo tanto, el patrón (ab) d (dc) puede representar cualquiera de estas 4 posibilidades: add, adc, bdd, bdc.

## Entrada

La primera línea de entrada contiene 3 enteros, L, D y N separados por un espacio. Siguen líneas D, cada una con una palabra de longitud L. Estas son las palabras que se sabe que existen en el idioma extranjero. Luego siguen N casos de prueba, cada uno en su propia línea y cada uno consiste en un patrón como se describió anteriormente. Puede suponer que todas las palabras conocidas proporcionadas son únicas.

## Salida

Para cada caso de prueba, salida

```
Case #X: K
```

donde **X** es el número de caso de prueba, comenzando desde 1, y **K** indica cuántas palabras en el idioma extranjero coinciden con el patrón.

## Límites

### Conjunto de datos pequeño

* 1 ≤ **L** ≤ 10
* 1 ≤ **D** ≤ 25
* 1 ≤ **N** ≤ 10

### Conjunto de datos grande

* 1 ≤ **L** ≤ 15
* 1 ≤ **D** ≤ 5000
* 1 ≤ **N** ≤ 500

Muestra

```
Entrada
 
3 5 4
abc
bca
dac
dbc
cba
(ab)(bc)(ca)
abc
(abc)(abc)(abc)
(zyx)bc

Salida

Case #1: 2
Case #2: 1
Case #3: 3

```
