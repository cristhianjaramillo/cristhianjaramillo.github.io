---
title: "<span>Introducción a modelos estadísticos</span>"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/modelos-estadisticos
excerpt_separator: <!--more-->
toc: true
venue: "Observatorio de Reformas Políticas en América Latina"
date: 2025-07-27
location: "London, UK"
---

Introducción del curso
<!--more-->

## Objetivos del curso

-   Comprender los fundamentos de los modelos de regresión lineal simple y múltiple.
-   Evaluar los supuestos de los modelos y aprender técnicas para diagnosticarlos y corregirlos.
-   Aplicar regresión a problemas de ciencia política, economía política y políticas públicas.
-   Familiarizarse con el flujo de trabajo de análisis de datos: importación, limpieza, visualización, modelado e interpretación.
-   Desarrollar habilidades reproducibles usando RMarkdown y buenas prácticas en Git/GitHub.

## Contenido del repositorio

-   `./scripts/` – Códigos en R de cada sesión (ejemplos y ejercicios).
-   `./slides/` – Presentación de las sesiones teóricas.
-   `./other/` – Otros materiales.
-   README.md – Este documento explicativo.

## Requisitos

1. Instalar R y RStudio
   
-   R: https://cran.r-project.org/
-   RStudio: https://posit.co/download/rstudio-desktop/

2. Instalar los paquetes necesarios (desde R):
   
```
install.packages(c(
  "tidyverse", "rio", "stargazer", "car", "lmtest",
  "palmerpenguins", "gapminder", "DescTools"
))
```

## Uso del repositorio

1. Clona o descarga el repositorio:
   
```
git clone https://github.com/usuario/estadistica-politica-2.git
```

2. Sigue el orden de los scripts para reproducir los ejemplos vistos en clase.

## Licencia

El contenido de este curso se comparte bajo licencia Creative Commons BY-NC-SA 4.0. Puedes reutilizar el material citando la fuente y sin fines comerciales.