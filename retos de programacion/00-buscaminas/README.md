# Buscaminas

## Problema


¿Quién no ha jugado al Buscaminas? Este entretenido juego acompaña a cierto sistema operativo cuyo nombre no logramos recordar. El objetivo del juego es encontrar todas las minas ubicadas en un campo de dimensiones M × N. 
El juego muestra un número en un recuadro que indica la cantidad de minas adyacentes a ese recuadro. Cada recuadro tiene, como mucho, ocho recuadros adyacentes. El campo, de tamaño 4 × 4, de la izquierda contiene dos minas, cada una de ellas representada por el carácter "*". Si representamos el mismo campo con los números descritos anteriormente, tendremos el campo de la derecha: 

````
*...  *100 
....  2210 
.*..  1*10 
....  1110 
````


## Entrada 
La entrada constará de un número arbitrario de campos. La primera línea de cada campo consta de dos números enteros, n y m (0 < n,m ≤ 100), que representan, respectivamente, el número de líneas y columnas del campo. Cada una de las siguientes **n** líneas contiene, exactamente, m caracteres, que describen el campo. 
Los recuadros seguros están representados por "." y los recuadros con minas por "*", en ambos casos sin las comillas. La primera línea descriptiva de un campo en la que n = m = 0 representa el final de la entrada y no debe procesarse. 

## Salida 

Para cada campo, escribir el mensaje "Case #x:" en una línea, donde x corresponde al número del campo, empezando a contar desde 1. Las siguientes **n** líneas deben contener el campo con los caracteres “.” sustituidos por el nu ́mero de minas adyacentes a ese recuadro. Debe haber una l ́ınea en blanco entre los distintos campos mostrados. 

## Muestra
```
Entrada

4 4 
*... 
.... 
.*.. 
.... 
3 5 
**... 
..... 
.*... 
0 0 

Salida 

Case #1:
*100
2210
1*10
1110 

Case #2:
**100
33200
1*100

```
