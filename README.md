# Índice de Déficit Comunal respecto a Servicios Urbanos y Hogares Vulnerables
## Descripción
El proyecto tiene como objetivo desarrollar un Índice de Déficit Comunal (IDC). Este índice tiene como finalidad mejorar la calidad de vida de los residentes en áreas más vulnerables, identificando zonas dentro de una comuna que requieran una alta prioridad de inversión pública. La evaluación se basa en el cruce de información sobre la accesibilidad a bienes urbanos y la condición socioeconómica de los hogares.

## Antecedentes Generales

La accesibilidad y desigualdad en la distribución de bienes urbanos es un problema significativo en Puente Alto. A pesar de ser una de las comunas más grandes y pobladas del país, existe una disparidad en la distribución y accesibilidad a servicios básicos como educación, salud y áreas recreativas. Es por eso que se busca abordar estas disparidades a través de la creación de un índice a modo de herramienta que permita focalizar la inversión pública en las áreas más necesitadas.

## Área de Prueba

Para la evaluación y validación de la herramienta desarrollada, se seleccionó la comuna de Puente Alto, situada al sureste de Santiago. Esta comuna es caracterizada por una mezcla de áreas urbanas densamente pobladas y zonas más rurales en su periferia, con una población de aproximadamente 568,106 habitantes (Censo 2017). La cartografía a continuación ilustra la ubicación de la comuna dentro de la Región Metropolitana:

![Cartografía de Puente Alto](ruta/a/tu/cartografia.png)

## Área de Estudio
Puente Alto es una comuna situada al sureste de Santiago, caracterizada por una mezcla de áreas urbanas densamente pobladas y zonas más rurales en su periferia. La población es de aproximadamente 568,106 habitantes (Censo 2017).

## Metodología
El cálculo del Índice de Déficit Comunal (IDC) se basa en la fórmula que considera el percentil de distancias a bienes urbanos (pd) y el porcentaje de hogares vulnerables (pv). La fórmula utilizada es la siguiente:


Donde:
- **pd** es el percentil de la distancia ponderada a bienes públicos (menor distancia = 1).
- **pv** es el percentil del porcentaje de hogares vulnerables (menor porcentaje de hogares vulnerables = 1).

Este índice permite identificar áreas prioritarias para la inversión pública en la comuna.

## Modelo de Datos
El modelo de datos de la GDB incluye varias clases de entidad y conjuntos de datos, organizados para facilitar el análisis espacial y el cálculo del IDC. A continuación, se presenta una previsualización del modelo de datos:
### Previsualización del Modelo de Datos
[![GDB.png](https://i.postimg.cc/PfP0kjyb/GDB.png)](https://postimg.cc/8sgZhxqs)
Para una visualización detallada y de alta calidad de los componentes, consulte el [Modelo de Datos](Modelo%20de%20Datos.pdf).

## Manual de Usuario
Para más detalles sobre el uso de la herramienta, consulte el [Manual de Usuario](Manual%20de%20Usuario.docx).

## Copyright y Licencia
Este proyecto está bajo la Licencia MIT. Consulte el archivo [LICENSE](LICENSE) para más detalles.

© 2024 Ignacio Andrés Sandoval Zapata. Todos los derechos reservados.
