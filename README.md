# 🌎 Población de origen extranjero en Argentina — Análisis descriptivo

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Ver%20an%C3%A1lisis-brightgreen)](https://siguax.github.io/analisis-poblacion-extranjera-argentina/Proyecto_Final_Ciencia_Datos_II.html)
[![R](https://img.shields.io/badge/R-4.x-276DC3?logo=r&logoColor=white)](https://www.r-project.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Análisis exploratorio de la estructura de la población de origen extranjero con residencia en Argentina, a partir de datos abiertos del Renaper (agosto 2024).

## 📌 Contexto y pregunta de investigación

El interrogante central de este trabajo es analizar la **estructura de la población de origen extranjero con residencia en Argentina**, desglosada por:

- Provincia de residencia.
- Sexo.
- Grupo quinquenal de edad.
- País de nacimiento.
- Nacionalidad.

Los datos provienen de **Datos.gob.ar**, cuyo organismo responsable es la **Dirección Nacional de Población del Renaper**, y corresponden a **agosto de 2024**.

## 📂 Fuente de datos

- **Datos.gob.ar** — Población extranjera identificada por provincia (agosto 2024).
- Organismo responsable: **Dirección Nacional de Población — Renaper**.

## 🎯 Objetivos

- Describir la composición de la población extranjera en Argentina.
- Identificar los principales países emisores.
- Analizar la distribución por provincia de residencia.
- Comparar la composición etaria y de género de los tres principales colectivos (Paraguay, Bolivia y Perú).

## 🛠️ Herramientas utilizadas

| Categoría | Herramientas |
|---|---|
| **Lenguaje** | R |
| **Lectura de datos** | `readr` |
| **Manipulación** | `dplyr`, `tidyr`, `tidyverse` |
| **Visualización** | `ggplot2` |
| **Documento** | R Markdown (`knitr`/`rmarkdown`) con salida en HTML |

## 📁 Estructura del repositorio

```text
poblacion-extranjera-argentina/
├── README.md
├── Proyecto_Final_Ciencia_Datos_II.Rmd
├── Proyecto_Final_Ciencia_Datos_II.html
├── Datos/
│   └── poblacion_extranjera_identificada_provincia_agosto_2024.csv
├── LICENSE
└── .gitignore

```

## ▶️ Ver el análisis completo
👉 **[Hacé clic acá para ver el trabajo renderizado](https://siguax.github.io/analisis-poblacion-extranjera-argentina/Proyecto_Final_Ciencia_Datos_II.html)**

## 🛠️ Cómo visualizar el proyecto

1. Cloná el repositorio:

   ```bash
   git clone https://github.com/Siguax/analisis-poblacion-extranjera-argentina.git
   cd analisis-poblacion-extranjera-argentina
   ```

2. Abrí el archivo **`Trabajo_Practico_Final_Ciencia_Datos_I.html`** en cualquier navegador.
3. Para reproducir el análisis, abrí el **`Trabajo_Practico_Final_Ciencia_Datos_I.Rmd`** en RStudio y ejecutá **Knit**.

## 📊 Principales hallazgos

- La mayor parte de la población extranjera proviene de Paraguay, Bolivia y Perú.
- Las provincias con mayor cantidad de población extranjera son Buenos Aires, CABA y Córdoba.
- Paraguay: el rango etario con mayor presencia es 30 a 54 años. De 30 a 39 predomina el sexo masculino; de 40 a 44 se nivela; a partir de los 45 hay más mujeres.
- Bolivia: el rango etario mayoritario es 30 a 44 años, con distribución bastante equilibrada entre sexos.
- Perú: el grupo más numeroso está entre 30 y 54 años, con un patrón similar al de Paraguay (predominio masculino joven, equilibrio en 40-44 y predominio femenino desde los 45).

## 📚 Temas del curso aplicados

- Lectura y exploración de datos abiertos.
- Selección, filtrado y manipulación de variables.
- Recodificación y agrupamiento por regiones geográficas.
- Cálculo de porcentajes y rankings.
- Visualización con ggplot2 (barras, histogramas por sexo).
- Análisis descriptivo de estructura poblacional.

## 📄 Licencia

Distribuido bajo la licencia MIT. Consultá LICENSE para más detalles.

## 👩‍💻 Autora

**Silvia Prevettoni**

- 🐙 GitHub: [@Siguax](https://github.com/Siguax)
- 💼 LinkedIn: [silvia-prevettoni](https://www.linkedin.com/in/silvia-prevettoni)
- 📧 Email: [silvia.prevettoni@gmail.com](mailto:silvia.prevettoni@gmail.com)







