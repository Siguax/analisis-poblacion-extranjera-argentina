# Análisis de la estructura de población de origen extranjero con residencia en Argentina

Análisis exploratorio de datos sobre la población de origen extranjero residente en Argentina, a partir de la base oficial publicada por **Datos.gob.ar** (agosto 2024).

## 📌 Pregunta central

¿Cómo se estructura la población de origen extranjero con residencia en Argentina según provincia de residencia, sexo, grupo quinquenal, país de nacimiento y nacionalidad?

## 📂 Fuente de datos

- **Origen:** [Datos.gob.ar](https://datos.gob.ar)
- **Organismo responsable:** Dirección Nacional de Población — RENAPER
- **Período:** Agosto 2024
- **Variables incluidas:** provincia de residencia, sexo, grupo quinquenal, país de nacimiento y nacionalidad.

## 🎯 Objetivos

- Describir la distribución de la población extranjera por provincia de residencia.
- Analizar la composición por sexo y grupo quinquenal.
- Identificar los principales países de nacimiento y nacionalidades.
- Visualizar los patrones más relevantes de la estructura poblacional.

## 🛠️ Herramientas y técnicas utilizadas

- **Lenguaje:** R
- **Data wrangling:** limpieza, cruce y transformación de grandes conjuntos de datos con `Tidyverse` (`dplyr`, `tidyr`, `readr`, etc.).
- **Visualización:** `ggplot2` con `geom_histogram()` y `geom_col()`.
- **Documento:** R Markdown con salida en HTML.

## 📁 Estructura del repositorio

```
.
├── README.md
├── Trabajo_Practico_Final.Rmd # Código fuente del análisis
└── Trabajo_Practico_Final.html # Documento renderizado (abrir en el navegador)
```

## 🛠️ Cómo visualizar el proyecto

1. Descargá o cloná este repositorio:
   ```bash
   git clone https://github.com/Siguax/analisis-poblacion-extranjera-argentina.git
   ```
2. Abrí el archivo **`Trabajo_Practico_Final.html`** en cualquier navegador web (Chrome, Firefox, Edge).
   - No necesitás instalar R para ver los resultados.
3. Si querés reproducir el análisis, abrí el archivo `.Rmd` en RStudio y ejecutá **Knit**.

## ▶️ Ver el análisis completo

👉 [Hacé clic acá para ver el trabajo renderizado](https://siguax.github.io/analisis-poblacion-extranjera-argentina/Trabajo_Practico_Final.html)

## 📊 Principales Hallazgos

- La mayor concentración de población extranjera se observa en la provincia de **Buenos Aires, CABA y Córdoba**.
- La mayor parte de la población de origen extranjero está conformada por habitantes provenientes de **Paraguay, Bolivia y Perú**.
- El grupo quinquenal con mayor peso relativo es el de **30 a 39 años**.

## 👩‍💻 Autora

**Silvia Prevettoni**
- GitHub: [@Siguax](https://github.com/Siguax)
- LinkedIn: [silvia-prevettoni](https://www.linkedin.com/in/silvia-prevettoni)
- Email: [silvia.prevettoni@gmail.com](mailto:silvia.prevettoni@gmail.com)
