# Índice de Déficit Comunal respecto a Servicios Urbanos y Hogares Vulnerables
## Descripción
<p align="justify">El proyecto tiene como objetivo desarrollar un Índice de Déficit Comunal (IDC). Este índice tiene como finalidad mejorar la calidad de vida de los residentes en áreas más vulnerables, identificando zonas dentro de una comuna que requieran una alta prioridad de inversión pública. La evaluación se basa en el cruce de información sobre la accesibilidad a bienes urbanos y la condición socioeconómica de los hogares.</p>

## Antecedentes Generales

<p align="justify">La accesibilidad y desigualdad en la distribución de bienes urbanos es un problema significativo en Puente Alto. A pesar de ser una de las comunas más grandes y pobladas del país, existe una disparidad en la distribución y accesibilidad a servicios básicos como educación, salud y áreas recreativas. Es por eso que se busca abordar estas disparidades a través de la creación de un índice a modo de herramienta que permita focalizar la inversión pública en las áreas más necesitadas.</p>


### Área de Prueba

<p align="justify">Para la evaluación y validación de la herramienta desarrollada, se seleccionó la comuna de Puente Alto, situada al sureste de Santiago. Esta comuna es caracterizada por una mezcla de áreas urbanas densamente pobladas y zonas más rurales en su periferia, con una población de aproximadamente 568,106 habitantes (Censo 2017). La cartografía a continuación ilustra la ubicación de la comuna dentro de la Región Metropolitana:</p>

[![pa.jpg](https://i.postimg.cc/mrxjHxW9/pa.jpg)](https://postimg.cc/75V0FW6P)


## Metodología
El cálculo del Índice de Déficit Comunal (IDC) se basa en la fórmula que considera el percentil de distancias a bienes urbanos (**$p_d$**) y el percentil de porcentaje de hogares vulnerables (**$p_d$**). La fórmula utilizada es la siguiente:

$$
NP(p_d, p_v) = \left(\frac{1}{4} + \frac{p_d}{2}\right) \cdot p_d + \left(\frac{3}{4} + \frac{p_d}{2}\right) \cdot p_v
$$

Donde:
- **$p_d$** es el percentil de la distancia ponderada a bienes públicos (menor distancia = 1).
- **$p_v$** es el percentil del porcentaje de hogares vulnerables (menor porcentaje de hogares vulnerables = 1).

Este índice permite identificar áreas prioritarias para la inversión pública en la comuna.
## Modelo de Datos

El modelo de datos de la GDB incluye varias clases de entidad y conjuntos de datos, organizados para facilitar el análisis espacial y el cálculo del IDC. A continuación, se presenta una previsualización del modelo de datos:</p>
### Previsualización del Modelo de Datos

[![GDB.png](https://i.postimg.cc/PfP0kjyb/GDB.png)](https://postimg.cc/8sgZhxqs)
Para una visualización detallada y de alta calidad de los componentes, consulte el [Modelo de Datos](Modelo%20de%20Datos.pdf).

## Video Tutorial

A continuación, se presenta un video tutorial que muestra cómo ejecutar correctamente las secuencias de comandos de la herramienta desarrollada:

[![Video Tutorial](https://img.youtube.com/vi/wu4AWYR_E4o/maxresdefault.jpg)](https://www.youtube.com/watch?v=wu4AWYR_E4o)

## Manual de Usuario
Para más detalles sobre el uso de la herramienta, consulte el [Manual de Usuario](Manual%20de%20Usuario.pdf).

## Copyright y Licencia
Este proyecto está bajo la Licencia MIT. Consulte el archivo [LICENSE](LICENSE) para más detalles.

© 2024 Ignacio Andrés Sandoval Zapata. Todos los derechos reservados.
