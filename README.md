# Índice de Déficit Comunal respecto a Servicios Urbanos y Hogares Vulnerables

Este proyecto desarrolla un Índice de Déficit Comunal (IDC) para la comuna de Puente Alto en la Región Metropolitana de Chile. La herramienta tiene como objetivo identificar zonas prioritarias para la inversión pública basándose en la accesibilidad a bienes urbanos y la vulnerabilidad socioeconómica de los hogares, destacando áreas necesitadas para mejorar la calidad de vida de sus residentes.

## Introducción
El acceso equitativo a los servicios urbanos es crucial para el desarrollo de las ciudades y la mejora de la calidad de vida de sus habitantes. En este contexto, se ha desarrollado una herramienta que identifica zonas que requieren una alta prioridad de inversión pública en la comuna de Puente Alto. Este índice se basa en la combinación de información sobre la accesibilidad a bienes urbanos y la condición socioeconómica de los hogares, resaltando las áreas más vulnerables y necesitadas.

## Problemática
Puente Alto, una de las comunas más grandes y pobladas de Chile, presenta disparidades en la distribución y accesibilidad a servicios básicos como educación, salud y áreas recreativas. Este proyecto busca abordar estas desigualdades a través de un índice que focaliza la inversión pública en las áreas más necesitadas.

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
## Previsualización del Modelo de Datos
[![GDB.png](https://i.postimg.cc/PfP0kjyb/GDB.png)](https://postimg.cc/8sgZhxqs)
Para una visualización detallada y de alta calidad de los componentes, consulte el [modelo de datos en formato PDF](Modelo%20de%20Datos.pdf) disponible en el repositorio.

## Manual de Usuario
Para más detalles sobre el uso de la herramienta, consulte el [Manual de Usuario](ruta/al/manual_de_usuario.pdf).

## Copyright y Licencia
Este proyecto está bajo la Licencia MIT. Consulte el archivo [LICENSE](LICENSE) para más detalles.

© 2024 Ignacio Andrés Sandoval Zapata. Todos los derechos reservados.
