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

Este curso ofrece una introducción práctica a la regresión lineal aplicada a las ciencias sociales. Se abordan desde la formulación de hipótesis y construcción de modelos hasta la evaluación de supuestos. El trabajo se realiza en R, promoviendo análisis reproducibles y visualizaciones claras.

<!--more-->

## Objetivos del curso

-   Comprender los fundamentos de los modelos de regresión lineal simple y múltiple.
-   Evaluar los supuestos de los modelos y aprender técnicas para diagnosticarlos y corregirlos.
-   Aplicar regresión a problemas de ciencia política, economía política y políticas públicas.
-   Familiarizarse con el flujo de trabajo de análisis de datos: importación, limpieza, visualización, modelado e interpretación.
-   Desarrollar habilidades reproducibles usando RMarkdown y buenas prácticas en Git/GitHub.

## Contenido del curso

-   `./scripts/` – Códigos en R de cada sesión (ejemplos y ejercicios).

| Scripts            | Descripción   |
| --------           | ------ |
| [0_wrangling](https://cristhianjaramillo.github.io/files/0_wrangling.R)     |Script para aprender a ordenar, organizar y editar bases de datos|
| [1_regresion](https://cristhianjaramillo.github.io/files/1_regresion.R)    |Script con ejemplos de regresión lineal simple|

-   `./slides/` – Presentación de la sesión teórica.

[![](images/regresion_lineal.png)](https://cristhianjaramillo.github.io/files/regresion_lineal.pdf)

-   `./other/` – Otros materiales.

| Libros y otros recursos            | Descripción   |
| --------           | ------ |
| [Introduction to Data Science](https://rafalab.dfci.harvard.edu/dsbook)     |Libro de introducción a R y métodos estadísticos básicos|
| [Estadística para las Ciencias Sociales](https://cristhianjaramillo.github.io/files/Texto R Sulmont_2015.pdf)    |Libro que abarca estadística descriptiva e inferencial|

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

1. También puedes clonar el repositorio:
   
```
git clone https://github.com/cristhianjaramillo/curso-investigacion.git
```

2. Sigue el orden de los scripts para reproducir los ejemplos vistos en clase.

## Licencia

El contenido de este curso se comparte bajo licencia Creative Commons BY-NC-SA 4.0. Puedes reutilizar el material citando la fuente y sin fines comerciales.

## Citado

El curso Introducción a modelos estadísticos, impartido en el Observatorio de Reformas Políticas en América Latina en 2025, puede citarse correctamente siguiendo los formatos mostrados a continuación. Para mayor comodidad, en este repositorio se incluye un archivo [.ris](https://cristhianjaramillo.github.io/files/modelos_estadisticos_jaramillo.ris) que facilita su incorporación en gestores de referencias bibliográficas. Selecciona el estilo de cita que mejor se ajuste a tus necesidades.

<details>

<summary>Chicago style</summary>

```
Jaramillo, Cristhian. 2025. “Introducción a modelos estadísticos.” Curso de pregrado en el Observatorio de Reformas Políticas en América Latina, London, UK, 27 de julio. https://cristhianjaramillo.github.io/teaching/modelos-estadisticos
```

</details>

---

<details>

<summary>APA 7ma edición</summary>

```
Jaramillo, C. (2025, julio). Introducción a modelos estadísticos [Curso de pregrado]. Observatorio de Reformas Políticas en América Latina. London, UK. Disponible en https://cristhianjaramillo.github.io/teaching/modelos-estadisticos
```

</details>

---

<details>

<summary>Harvard</summary>

```
Jaramillo, C., 2025. Introducción a modelos estadísticos. Observatorio de Reformas Políticas en América Latina, London, UK. Disponible en: https://cristhianjaramillo.github.io/teaching/modelos-estadisticos [Accedido 29 julio 2025].
```

</details>

---

<details>

<summary>IEEE Style</summary>

```
C. Jaramillo, "Introducción a modelos estadísticos," Observatorio de Reformas Políticas en América Latina, London, UK, Jul. 2025. [En línea]. Disponible en: https://cristhianjaramillo.github.io/teaching/modelos-estadisticos
```

</details>
