# Train Timetable

# Problema

Una línea de tren tiene dos estaciones, **A** y **B**. Los trenes pueden tomar viajes de **A** a **B** o de **B** a **A** varias veces durante un día. Cuando un tren llega a **B** desde **A** (o llega a **A** desde **B**), necesita una cierta cantidad de tiempo antes de estar listo para tomar el viaje de regreso; este es el tiempo de respuesta. Por ejemplo, si un tren llega a las 12:00 y el tiempo de respuesta es de 0 minutos, puede partir inmediatamente a las 12:00.

Un horario de trenes especifica la hora de salida y llegada de todos los viajes entre **A** y **B**. La compañía de trenes necesita saber cuántos trenes tienen que comenzar el día en **A** y **B** para que el horario funcione: siempre que un tren salga de **A** o **B**, debe haber uno allí listo para funcionar. Hay secciones de paso en la vía, por lo que los trenes no necesariamente llegan en el mismo orden en que salen. Los trenes no pueden viajar en viajes que no aparecen en el horario.

## Entrada

La primera línea de entrada da el número de casos, **N**. A continuación se presentan casos de prueba.
Cada caso contiene una serie de líneas. La primera línea es el tiempo de respuesta, **T**, en minutos. La siguiente línea tiene dos números, **NA** y **NB**. **NA** es el número de viajes de **A** a **B**, y **NB** es el número de viajes de **B** a **A**. Luego hay líneas de **NA** que detallan los viajes de **A** a **B**.

Cada línea contiene dos campos, que dan la hora de salida y llegada de HH:MM para ese viaje. La hora de salida de cada viaje será anterior a la hora de llegada. Todas las llegadas y salidas ocurren el mismo día. Los viajes pueden aparecer en cualquier orden; no están necesariamente ordenados por tiempo. Los valores de hora y minuto son dos dígitos, rellenos con ceros, y están en un reloj de 24 horas (00:00 a 23:59).
Después de estas líneas **NA**, hay líneas **NB** que indican los horarios de salida y llegada para los viajes de **B** a **A**.

## Salida

Para cada caso de prueba, envíe una línea que contenga "Caso #x:" seguido del número de trenes que deben comenzar en A y el número de trenes que deben comenzar en B.

## Límites

* 1 ≤ N ≤ 100

### Conjunto de datos pequeño

* 0 ≤ NA, NB ≤ 20
* 0 ≤ T ≤ 5

### Conjunto de datos grande

* 0 ≤ NA, NB ≤ 100
* 0 ≤ T ≤ 60

Muestra

```
Entrada

2
5
3 2
09:00 12:00
10:00 13:00
11:00 12:30
12:02 15:00
09:00 10:30
2
2 0
09:00 09:01
12:00 12:02

Salida

Case #1: 2 2
Case #2: 2 0

```
