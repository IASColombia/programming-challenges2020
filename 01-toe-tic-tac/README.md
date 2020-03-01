# Toe Tic Tac

## Problema

Tic-Tac-Toe-Tomek es un juego jugado en un tablero cuadrado de 4 x 4. El tablero comienza vacío, excepto que puede aparecer un solo símbolo 'T' en uno de los 16 cuadrados. Hay dos jugadores: X y O. Se turnan para hacer movimientos, con X comenzando. En cada movimiento, un jugador coloca su símbolo en una de las casillas vacías. El símbolo del jugador X es 'X', y el símbolo del jugador O es 'O'.

Después del movimiento de un jugador, si hay una fila, columna o diagonal que contiene 4 de los símbolos de ese jugador, o que contiene 3 de sus símbolos y el símbolo 'T', ella gana y el juego termina. De lo contrario, el juego continúa con el movimiento del otro jugador. Si todos los campos están llenos de símbolos y nadie ganó, el juego termina en empate. Vea la entrada de muestra para ejemplos de varias posiciones ganadoras.

Dada una descripción de tablero de 4 x 4 que contiene 'X', 'O', 'T' y '.' los caracteres (donde '.' representa un cuadrado vacío), que describen el estado actual de un juego, determinan el estado del juego Tic-Tac-Toe-Tomek que se está llevando a cabo. Los estados para elegir son:

"X won" (el juego terminó y X ganó)
"O won" (el juego terminó y O ganó)
"Draw" (el juego terminó y terminó en empate)
"Game has not completed" (el juego aún no ha terminado)
Si hay celdas vacías y el juego no ha terminado, debe mostrar "Game has not completed", incluso si el resultado del juego es inevitable.

## Entrada

La primera línea de la entrada da el número de casos de prueba, los casos de prueba T. T siguen. Cada caso de prueba consta de 4 líneas con 4 caracteres cada una, siendo cada carácter 'X', 'O', '.' o 'T' (citas solo para mayor claridad). Cada caso de prueba es seguido por una línea vacía.

## Salida

Para cada caso de prueba, envíe una línea que contenga "Caso #x: y", donde x es el número de caso (a partir de 1) ey es uno de los estados indicados anteriormente. Asegúrese de obtener los estados exactamente correctos. Cuando ejecuta su código en la entrada de muestra, debe crear la salida de muestra exactamente, incluido el "Caso # 1:", la letra mayúscula "O" en lugar del número "0", y así sucesivamente.

## Límites

El tablero de juego proporcionado representará un estado válido que se alcanzó a través del juego Tic-Tac-Toe-Tomek como se describió anteriormente.

## Pequeño conjunto de datos
1 ≤ T ≤ 10.

## Gran conjunto de datos
1 ≤ T ≤ 1000.

## Muestra

```
Entrada

6
XXXT
....
OO..
....

XOXT
XXOO
OXOX
XXOO

XOX.
OX..
....
....

OOXX
OXXX
OX.T
O..O

XXXO
..O.
.O..
T...

OXXX
XO..
..O.
...O


Salida

Case #1: X won
Case #2: Draw
Case #3: Game has not completed
Case #4: O won
Case #5: O won
Case #6: O won

```
