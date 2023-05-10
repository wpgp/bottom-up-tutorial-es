# Modelización estadística de la población para apoyar los censos

[![DOI](https://zenodo.org/badge/383087930.svg)](https://zenodo.org/badge/latestdoi/383087930)

Este repositorio de github contiene el material didáctico en bruto para el [**Modelización estadística de la población para apoyar los censos**](https://wpgp.github.io/bottom-up-tutorial-es/) financiado por el [Fondo de Población de las Naciones Unidas](<https://www.unfpa.org/>). Ha sido desarrollado por el [WorldPop Researc)h Group](<https://www.worldpop.org/>), Universidad de Southampton y el [Leverhulme Center for Demographic Sciences](https://www.demography.ox.ac.uk/).

Este sitio web ofrece una serie de tutoriales sobre **estadística bayesiana para la modelización de poblaciones** y experiencias prácticas para empezar a desarrollar las habilidades necesarias. Incluye un código de ejemplo y otros recursos diseñados para agilizar al máximo la curva de aprendizaje.

Los conceptos clave que se tratan en la serie de tutoriales incluyen:
1. introducción a los programas informáticos de modelización estadística bayesiana: R y Stan,
2. regresión lineal simple en un contexto bayesiano,
3. efectos aleatorios para tener en cuenta el tipo de asentamiento (por ejemplo, urbano/rural) y otros tipos de estratificación en los datos de la encuesta,
4. cuantificación y mapeo de las incertidumbres en las estimaciones de población y
5. diagnósticos para evaluar el rendimiento del modelo (por ejemplo, validación cruzada).

El material se ha utilizado durante un taller a distancia con el Instituto Brasileño de Geografía y Estadística (IBGE) en octubre de 2021.

# Esquema de los tutoriales

-   [Introduction](https://github.com/wpgp/bottom-up-tutorial-es/tree/main/tutorials/)
-   [Tutorial 1](https://github.com/wpgp/bottom-up-tutorial-es/tree/main/tutorials/tutorial1/): ¿Cómo pensar como un bayesiano y construir un primer modelo de población? 
-   [Tutorial 2](https://github.com/wpgp/bottom-up-tutorial-es/tree/main/tutorials/tutorial2/): ¿Cómo modelizar las variaciones espaciales a gran escala?
-   [Tutorial 3](https://github.com/wpgp/bottom-up-tutorial-es/tree/main/tutorials/tutorial3/): ¿Cómo modelizar las variaciones espaciales a pequeña escala?
-   [Tutorial 4](https://github.com/wpgp/bottom-up-tutorial-es/tree/main/tutorials/tutorial4/): Diagnóstico y predicción avanzados de modelos
-   [Conclusión](https://github.com/wpgp/bottom-up-tutorial-es/tree/main/tutorials/)
-   [Actualización del flujo de trabajo](https://github.com/wpgp/bottom-up-tutorial-es/tree/main/tutorials/workflow/): Construcción de un modelo de población de principio a fin + una historia sobre la parametrización de modelos jerárquicos

# Material

Los materiales pertinentes se encuentran en la carpeta [`tutorials`](https://github.com/wpgp/bottom-up-tutorial-es/tree/main/tutorials).

Cada tutorial tiene su carpeta dedicada que contiene
- Material del tutorial
  - El código `R`
  - El código `stan`
- Archivos de fondo
  - El código `html` para la página web  

La carpeta `data` contiene los resultados del tutorial.

# Agradecimientos

 Este tutorial ha sido redactado por Edith Darin, de WorldPop, Universidad de Southampton, y Douglas Leasure, del Leverhulme Centre for Demographic Science, Universidad de Oxford, con la supervisión de Andrew Tatem, de WorldPop, Universidad de Southampton. Este trabajo ha sido financiado por el Fondo de Población de las Naciones Unidas (UNFPA, por sus siglas en inglés). 

# License

El presente documento puede redistribuirse libremente bajo los términos de una licencia Creative Commons Atribución-SinDerivadas 4.0 Internacional ([CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/)).


# Cita sugerida

Darin E, Leasure DR, Tatem AJ. 2021. Statistical population modelling for census support. United Nations Population Fund (UNFPA) and WorldPop, University of Southampton. https://wpgp.github.io/bottom-up-tutorial/, doi:10.5281/zenodo.5572490

<br>

<br>


![alt](assets/pic/320px-UNFPA_logo.svg.png) ![alt](assets/pic/wp_logo_gray_low.png) ![alt](assets/pic/Ox_LCDS_logo_bw.png)
