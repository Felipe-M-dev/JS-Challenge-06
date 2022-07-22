# Desafío 6 - Conversor de monedas

En este desafío validaremos nuestros conocimientos del método fetch.

Lee todo el documento antes de comenzar el desarrollo __individual__, para asegurarte de tener el máximo de puntaje y enfocar bien los esfuerzos.

## Descripción

Aplicando los conceptos y herramientas aprendidas hasta ahora, en este desafío deberás programar un conversor de monedas a partir de un monto en pesos chilenos. Para esto será necesario consultar la api [mindicador.cl](https://mindicador.cl) usando el método fetch.

A continuación te mostramos lo que debes maquetar:

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-06/blob/main/01.png?raw=true?raw=true" alt="Imagen 01"><br>
Imagen 1. Maqueta general del desafío<br>
Fuente: Desafío Latam
</p>

En donde tenemos:

● Un _input_ para tipear la cantidad de pesos chilenos a convertir <br>
● Un _select_ para elegir la moneda a convertir <br>
● Un botón para iniciar el proceso de consulta y renderización de datos

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-06/blob/main/02.png?raw=true?raw=true" alt="Imagen 02"><br>
Imagen 2. Búsqueda realizada con éxito<br>
Fuente: Desafío Latam
</p>

Luego ocupa una librería de JavaScript de gráficas para mostrar un historial del valor de la moneda a convertir de los últimos 10 días.

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-06/blob/main/03.png?raw=true?raw=true" alt="Imagen 03"><br>
Imagen 3. Conversión con historial<br>
Fuente: Desafío Latam
</p>

## Requerimientos

1. Se obtienen los tipos de cambio desde mindicador.cl. (__2 puntos__)

2. Se calcula correctamente el cambio y se muestra en el DOM. (__2 puntos__)

3. El select implementa más de un tipo de moneda (con 2 es suficiente), todos los cambios funcionan correctamente. (__2 puntos__)

4. Se usa try catch para ejecutar el método fetch y capturar los posibles errores mostrando el error en el DOM en caso de que haya problemas. (__2 puntos__)

5. Se Implementa el gráfico pedido (__2 puntos__)

😊¡Mucho éxito!

[Try site](https://felipe-m-dev.github.io/JS-Challenge-06/)
