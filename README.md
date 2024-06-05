
# SINIESTROS VIALES

En esta carpeta se asumira el rol de analista de datos, donde se van a analizar los siniestros viales en la ciudad de Buenos Aires, Argentina.

## Introduccion al contenido
En un inicio te encontraras con tres carpetas y tres archivos sueltos en los que se desarrollara todo el contenido.

### Datos 
En esta carpeta te encontraras con los datos sin limpiar, el diccionario de datos y un archivo comunas.geojson el cual se utilizara mas adelante en el archivo.

### ETL 
En esta carpeta se encontrara un archivo llamado "ETL.iptnb" en el cual se realizan transformaciones a los datos del excel tanto de la hoja de hechos como la hoja de victimas en donde se crearon nuevas columnas las cuales van a tener un proposito mas adelante en el desarrollo de los dashboards, Estos archivos en su momento al guardarlos generan la copia en su carpeta pero fueron movidos al inicio para facilitar los vinculos a PowerBi


### EDA 
En esta carpeta se realizara un analisis investigatorio de los datos recopilando multiple informacion como lo puede ser la cantidad de victimas por hecho, la distribucion de edades en los accidentes, el sexo de la victima, entre otras cosas.

A cada titulo dentro de este analisis se le intenta dar una breve conclusion del porque pueden haber ocurrido estos hechos.

Tambien en este archivo se utilizo el archivo de "comunas.geojson" mencionado con anterioridad para generar dos mapas los cuales se podran ver dentro de esta carpeta.

### hechos_actualizado y Victimas_actualizado

Son los archivos principales que se usaron para el archivo dr PowerBi, estos archivos son el resultado de los procesos en ETL.

### SiniestrosViales.pbix
Por ultimo en la carpeta nos toparemos con este archivo, aqui manejaremos cinco hojas.

#### mapa

Es el primer dashboard que veremos al entrar a la carpeta, en esta se vera reflejado 4 filtros:
-años
-meses
-Transporte de la victima
-Transporte del acusado

estos modificaran el mapa y dos tarjetas dandonos precision del lugar donde ocurrieron los accidentes.

#### Graficas 1 y 2

Aca llamamos a 2 de los dashboards donde principalmente se realiza el llamado de informacion que tiene un buen valor dentro de los archivos

#### KPI 1

Dentro de este KPI se verificara la reduccion de homicidios en siniestros viales respecto al semestre anterior, dispondremos de un filtro para ver en que semestre nos encontramos y un conjunto de tarjetas que nos indicaran informacion sobre el KPI.

A la par, nos encontraremos con un grafico de barras que compara el semestre actual del filtro con el semestre anterior a este.

#### KPI 2

Este KPI hace llamado a los accidentes mortales en moto de forma anual, en este KPI tambien podremos encontrar un filtro el cual nos de el año actual y compararemos con el año anterior, aca tambien podremos encontrrar multiples tarjetas dandonos informacion de esto y la comparativa entre el año que se esta revisando y el anterior.


#### KPI 3

En este KPI se realizara la revision de las victimas de menores de edad( llamese menor de edad persona que no ha cumplido los 18 años de edad) donde filtraremos a traves del año comparando con la cantidad de victimas de años anteriores, al igual que con los otros KPI encontraremos tarjetas de ayuda y una grafica que nos da una comparativa con el año anterior.

## conclusiones

-Se desarollo un analisis y limpieza de los datos.
-Se comprobaron los analisis de los datos.
-Se eshibieron los datos.
-Se realizo 3 KPIs con el fin de ver que ha pasado a lo largo del tiempo.
## Support

En caso de querer contactarme lo puede hacer al siguiente correo:

mateoerredic@gmail.com

