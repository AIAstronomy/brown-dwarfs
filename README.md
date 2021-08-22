# Brown Dwarfs

Authors: Crespo Montes, Cándido, Guzmán-Álvarez, César Augusto 


## Table of Contents

- [Abstract](#abstract)
- [Architecture](#architecture)
- [Code](#code)
- [Publications](#publications)
- [Acknowledgement](#acknowledgement)
- [References](#references)

## Abstract

En este trabajo se aplican tres técnicas de clasificación no supervisada sobre una muestra de espectros de enanas marrones de la clase espectral M. La muestra incluye enanas de todas las subclases espectrales desde la M0 hasta la M9 y clases de metalicidad; metalicidad solar, subenanas, subenanas extremas y ultrasubenanas. Los espectros pertenecen al rango óptico, yendo aproximadamente desde los 3,500 Å hasta los 9000 Å y se han obtenido del Sloan Digital Sky Survey (SDSS). Las técnicas de clasificación empleadas son la Agregación Jerárquica, K-means y el Modelo de Mezcla de Gaussianas (GMM). La selección de los parámetros de las técnicas de clasificación se realiza basándose únicamente en los datos y en los algoritmos, aunque en los análisis de los grupos resultantes sí se usan las clasificaciones existentes basadas en criterios físicos. Para la extracción de característica y reducción de la dimensional se usa el Análisis de Componentes Principales. Inicialmente se explora el comportamiento de las tres técnicas de clasificación usando 5 y 45 componentes principales con diferentes escalados. En ningún caso se consiguen clases que puedan relacionar a la vez con la subclase espectral y la metalicidad. Para la clase espectral se consiguen los mejores resultados usando la Agregación Jerárquica y K-means sobre 5 componentes principales sin escalar, mientras que para la metalicidad es con GMM, covarianza ‘full’ y 45 componentes principales. En vista de esto se explora la posibilidad de encontrar de manera independiente una clasificación que pueda relacionarse con la subclase espectral y otra con la metalicidad. Para la subclase espectral se obtiene un buen resultado aplicando K-means para k igual a 9 sobre únicamente la primera componente principal. Este resultado se confirma como consistente cuando se verifica usando un conjunto de prueba. Para la metalicidad se aplica GMM para diferentes subconjuntos de las componentes principales. La clasificación obtenida se muestra inconsistente cuando se verifica en un conjunto de prueba. El siguiente paso consiste en usar una técnica supervisada de extracción de características como es el Análisis Discriminante Lineal usando como etiquetas la clase de metalicidad. A pesar de que se obtienen buenas clasificaciones tanto para K-means con k igual a 4 y GMM con 5 componentes gaussianas, el resultado no demuestra consistencia cuando se verifica en un conjunto de prueba. Lo máximo que se consigue es cierta segregación de las enanas con metalicidad solar del resto. 
