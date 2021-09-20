# Brown Dwarfs

Authors: Crespo Montes, Cándido, Guzmán-Álvarez, César Augusto 

## Abstract

Clasificación no supervisada sobre una muestra de espectros de enanas marrones de la clase espectral M. 

La muestra incluye enanas de todas las subclases espectrales desde la M0 hasta la M9 y clases de metalicidad; metalicidad solar, subenanas, subenanas extremas y ultrasubenanas. 

Los espectros pertenecen al rango óptico, aproximadamente desde los 3,500 Å hasta los 9000 Å y se han obtenido del Sloan Digital Sky Survey (SDSS). 

## Técnicas de clasificación empleadas 

- Agregación Jerárquica, 
- K-means 
- Modelo de Mezcla de Gaussianas (GMM). 

La selección de los parámetros de las técnicas de clasificación se realiza basándose únicamente en los datos y en los algoritmos, aunque en los análisis de los grupos resultantes sí se usan las clasificaciones existentes basadas en criterios físicos. 

Para la extracción de característica y reducción de la dimensional se usa el Análisis de Componentes Principales. 

Inicialmente se explora el comportamiento de las tres técnicas de clasificación usando 5 y 45 componentes principales con diferentes escalados. 
