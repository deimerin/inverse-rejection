# Generación de variables aleatorias - Transformada inversa y Método del rechazo

## Actividad grupal

En un notebook (formato RMD) realice la implementación de algoritmos para la generación de variables aleatorias continuas. Recuerde que de la libreria R para generación de números aleatorios solo pueden utilizar la función **runif**. Recuerde corroborar de forma gráfica que efectivamente los valores generados siguen la distribución de probabilidad deseada. En el archivo RMD, señale en secciones diferentes cada uno de los problemas:

1) Un par de dados balanceados serán lanzados de forma continua hasta que todos los posibles resultados 2,3, ... 12 hayan ocurrido al menos una vez. Desarrolle un estudio de simulación para estimar el número esperado de lanzamientos que es necesario realizar para que se cumpla la condición.

2) Implemente dos métodos diferentes para generar la variable aleatoria X que tiene la probabilidad de masa $p_j, j=5,6,..., 14$ donde:

 


3) Implemente un método para generar valores aleatorios que siguen la distribución descrita por la función de densidad de probabilidad $f(x)=e^x/(e−1)$
para 0≤x≤1

4) Implemente el método descrito en el ejemplo 5F del libro de Ross, que está basado en el método del rechazo, para generar una variable aleatoria con distribución normal a partir de una distribución exponencial

5) Use el método del rechazo para encontrar una forma eficiente de generar una variable aleatoria que tenga función de densidad de probabilidad f(x)=12(1+x)e−x,0<x<inf. Observe que la función esta definida entre 0 e infinito

Agregue también el archivo html resultante de la renderización del notebook.

