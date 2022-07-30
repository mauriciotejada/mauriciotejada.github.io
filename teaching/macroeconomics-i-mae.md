---
layout: page
title: Macroeconomía I (MAE)
exclude: true
permalink: /teaching/macroeconomics-i-mae
---

<div style="text-align: right"> Segundo Semestre 2022 </div>

#### Descripción

Este curso presenta una introducción al modelamiento macroeconómico, enfocándose en la teoría del crecimiento económico y sus aplicaciones. En particular, se introducen una serie de modelos macroeconómicos de equilibrio general, tanto deterministicos como estocásticos, que dan por un lado dan luces sobre el proceso de crecimiento y las fuentes de las diferencias en los ingresos entre países y por el otro sientan las bases de la teoría de los ciclos económicos. El curso tiene varios objetivos. Primero, se busca familiarizar al estudiante con un conjunto de preguntas que son centrales en macroeconomía. Segundo, proveer al alumno de las herramientas de optimización dinámica más importantes y útiles para la macroeconomía. Tercero, proveer al alumno del uno de los caballos de batalla de la macroeconomía moderna, el modelo neoclásico de crecimiento. Finalmente, familiarizar al alumno con el uso del computador para resolver numéricamente modelos dinámicos de equilibrio general.

#### Sílabo

Puedes descargar el sílabo [aquí](https://www.dropbox.com/s/9wsju1jtq0w4v9c/Silabo%20Macro%20I%202022.pdf?raw=1). En la primera clase discutiremos la forma en que organizaremos el curso. [[Slides]](https://www.dropbox.com/s/hi8mp0kb4gh6cdc/0_Temas_Administrativos.pdf?raw=1)]

#### Contenidos

1. La Macroeconomía Moderna [[Slides]](https://www.dropbox.com/s/dt8sr8ahn54zgez/1_La_Macro_Moderna.pdf?raw=1).
   
2. El Modelo Neoclásico de Crecimiento [[Slides]](https://www.dropbox.com/s/7bx1546kbv0aefe/2_El_Modelo_Neoclasico_de_Crecimiento_v2.pdf?raw=1).
   - Notas sobre las propiedades de la función de producción [[pdf](https://www.dropbox.com/s/7sv4735ytsgqaiw/H1_Funcion_Produccion.pdf?raw=1)].
   - Notas sobre las propiedades de la función de utilidad [[pdf](https://www.dropbox.com/s/dgsgt5aq2j6ldev/H2_Funcion_Utilidad.pdf?raw=1)].
   - Notas sobre la formulación general del problema de programación dinámica [[pdf](https://www.dropbox.com/s/ornulzbc9keguor/H3_Programacion_Dinamica.pdf?raw=1)].
   - Notas sobre la senda de crecimiento balanceado generalizada [[pdf](https://www.dropbox.com/s/ew5d7lm3fecrcah/H4_Senda_Crecimiendo_Balanceado_Generalizada.pdf?raw=1)].
   - Implementación del shooting algorithm usando Julia [[notebook](https://mybinder.org/v2/gh/mauriciotejada/macroeconomics_I/master?filepath=El%20Modelo%20Neoclasico%20SA.ipynb)].
   - Implementación del método iteración de la función valor usando Julia [[notebook](https://mybinder.org/v2/gh/mauriciotejada/macroeconomics_I/master?filepath=El%20Modelo%20Neoclasico%20PD.ipynb)].  

3. Modelos de Crecimiento Endógeno de 1era y 2da generación [[Slides](https://www.dropbox.com/s/8vzozof8qsupfu2/3_Modelos_de_Crecimiento_Endogeno_v2.pdf?raw=1)]
   - Notas sobre la estabilidad del modelo AK [[pdf](https://www.dropbox.com/s/irknyc5v1qgp4nb/H5_Estabilidad_Modelo_AK.pdf?raw=1)].
   - Notas sobre el uso del agregador CES [[pdf](https://www.dropbox.com/s/j91b24u4hapbstl/H6_Agregadores_CES.pdf?raw=1)].

4. El Modelo Estocástico de Crecimiento [[Slides](https://www.dropbox.com/s/lmdrey0wghnve1m/4_Modelo_Estocasticos_de_Crecimiento.pdf?raw=1)]
   - Implementación del método iteración de la función valor usando Julia [[notebook](https://mybinder.org/v2/gh/mauriciotejada/macroeconomics_I/HEAD?labpath=El%20Modelo%20Estocastico%20PD.ipynb)]
   - Implementación del método de perturbación usando Julia [[notebook](https://mybinder.org/v2/gh/mauriciotejada/macroeconomics_I/HEAD?labpath=El_Modelo_RBC.ipynb)] [[scripts en Julia](https://www.dropbox.com/s/qg42ty3ple9powo/RBC%20model.zip?dl=1)]
   
5. Modelo de Crecimiento con Agentes Heterogéneos [[Slides](https://www.dropbox.com/s/wst8omc67fkvxg6/5_Modelos_de_Crecimiento_con_Agentes_Heterogeneos.pdf?raw=1)]
   - Implementación del método de perturbación para el modelo RBC con agentes Ricardianos y No Ricardiano usando Julia [[notebook](https://mybinder.org/v2/gh/mauriciotejada/macroeconomics_I/HEAD?labpath=El_Modelo_RBC_Agentes_Ricardianos.ipynb)]
   - Implementación del método iteración de la función valor para el modelo de Ayagari [[scripts en Julia](https://www.dropbox.com/s/a1alt9f7d3cnenx/Modelo_de_Ayagari_Julia.jl?dl=1)]
   - Implementación del método de perturbación para el modelo de Ayagari con riesgo agregado [[notebook](https://mybinder.org/v2/gh/mauriciotejada/macroeconomics_I/HEAD?labpath=Modelo_Neoclasico_AH_Riesgo_Agregado.ipynb)]

#### Software

Las tareas y los módulos prácticos requieren del uso de un software de análisis numérico. En el mercado hay varios: Matlab©, Octave, Julia, Python (con Numpy y Scipy), Scilab, R, etc. El alumno es libre de elegir el de su preferencia. Sin embargo, se sugiere Julia para tomar ventaja de lo aprendido en el curso de métodos cuantitativos.

#### Tareas

- Tarea 1 
- Tarea 2
- Tarea 3
- Tarea 4