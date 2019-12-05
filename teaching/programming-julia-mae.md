---
layout: page
title: Programación en JULIA (MAE)
exclude: true
permalink: /teaching/programming-julia-mae
---

<div style="text-align: right"> Segundo Semestre 2019 </div>

#### Descripción

Este curso enseña programación en Julia aquellos que tienen muy poca o ninguna experiencia previa en el tema. Julia es usado como programa base porque es fácil de aprender, es versátil, rápido y es muy útil para el análisis numérico. A lo largo del curso se presentarán diversas aplicaciones a problemas económicos. El curso requiere que el alumno acompañe las clases con su computador para replicar los ejercicios y aplicaciones provistas.

#### Contenidos

1. [Motivación](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C1.ipynb)
2. [Primeros Pasos en Julia](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C2.ipynb)
	- Interactuando con Julia.
	- Ayuda.
	- Paquetes.
	- Comentarios.
	- Variables.
	- Operaciones Matemáticas Básicas.
	- Estructura de Datos.
	- Imprimir Resultados en Pantalla.
	- Elementos Básicos para Graficar.
3. [Matrices](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C3.ipynb)
	- Secuencias.
	- Matrices Especiales.
	- Operaciones con Matrices.
	- Referenciación y Submatrices.
	- Concatenar Matrices.
	- Arreglos de Mayor Dimensión.
4. [Funciones de Julia](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C4.ipynb)
	- Funciones Escalares.
	- Funciones Vectoriales.
	- Funciones Matriciales.
5. [Importando y Exportando Datos](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C5.ipynb) ([PIBChile.xlsx](https://github.com/mauriciotejada/programming_julia/blob/master/Notebooks/PIBChile.xlsx))
6. [Aplicaciones I](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C6.ipynb)
	- Modelo Insumo-Producto.
	- Equilibrio de Mercado con Dos Bienes.
	- Mínimos Cuadrados Ordinarios.
7. [Programar en Julia](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C7.ipynb)
	- jl-files.
	- Funciones.
	- Loops.
	- Condicionales y Operadores Lógicos.
8. [Aplicaciones II](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C8.ipynb) ([FBKFChile.xlsx](https://github.com/mauriciotejada/programming_julia/blob/master/Notebooks/FBKFChile.xlsx))
	- Flujos vs. Stocks.
	- Ciclos Económicos.
	- La Curva de Laffer.
	- El Modelo de la Telaraña.
9. [Diferenciación e Integración Numérica](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C9.ipynb)
	- Diferenciación.
	- Integración.
10. [Ecuaciones No Lineales](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C10.ipynb)
	- Métodos Numéricos y Ecuaciones No Lineales: Ideas Básicas.
	- Las Funciones fzero y nlsolve.
11. [Optimización](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C11.ipynb)
	- Métodos Numéricos de Optimización: Ideas Básicas.
	- Paquetes de Optimización de Julia (Optim y JuMP).
12. [Aplicaciones III](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C12.ipynb)  ([DatosMCO.txt](https://github.com/mauriciotejada/programming_julia/blob/master/Notebooks/DatosMCO.txt))
	- Aproximación lineal de una Función
	- Esperanza Matemática.
	- Duopolio de Cournot.
	- Estimación por Máximo Verosimilitud.
	- El Problema de Maximización del Consumidor.
13. [Tipos de Variables en Julia](https://nbviewer.jupyter.org/github/mauriciotejada/programming_julia/blob/master/Notebooks/IntroJULIA_C13.ipynb)
	- Despacho Múltiple
	- Tipos Compuestos

Todos los notebooks pueden ser descargados de [Github](https://github.com/mauriciotejada/programming_julia).

El siguiente [script](https://github.com/mauriciotejada/programming_julia/blob/master/Notebooks/install-packages.jl) contiene todos los paquetes utilizados en este curso (y algunos adicionales bastante útiles).

#### Referencias

- La fuente primaria de referencia es el [manual de Julia](https://docs.julialang.org/en/v1/) y el de sus [paquetes](https://pkg.julialang.org/docs/).
- Petre Caraiani (2019): Introduction to Quantitative Macroeconomics Using Julia. ScienceDirect Press. [[Página Web](https://www.sciencedirect.com/book/9780128122198/introduction-to-quantitative-macroeconomics-using-julia)]

Referencias útiles sobre métodos computacionales en Matlab

- Mario J. Miranda & Paul L. Fackler (2002): Applied Computational Economics and Finance. MIT Press. [[Página Web](http://www4.ncsu.edu/~pfackler/compecon/)] [[CompEcon Toolbox](http://www4.ncsu.edu/~pfackler/compecon/toolbox.html)]
- Abi, Adams, Damian Clarke & Simon Quinn (2015): Microeconometrics and Matlab. Oxford University Press. [[Página Web](http://www.microeconometrics-code.com/)]

Otras referencias o páginas web útiles:

- [Jesús Fernández-Villaverde](https://www.sas.upenn.edu/~jesusfv/index.html), Profesor de la Universidad de Pennsylvania, tiene un curso de economía computacional y le dedica un capítulo a Julia. Adicionalmente, hace disponible un [script](https://www.sas.upenn.edu/~jesusfv/Julia_tutorial_script_April_2019.txt) con diversos ejemplos de procedimientos en Julia. La página con el curso completo puede ser encontrada [aquí](https://www.sas.upenn.edu/~jesusfv/teaching.html) (Computational Methods in Economics).
- [Thomas J. Sargent](http://www.tomsargent.com/) y [John Stachurski](http://johnstachurski.net/) tienen un sin fin de lecturas y ejemplos en Julia y Python en el marco su proyecto [Quantecon](https://lectures.quantecon.org/).
- [Anthony Smith](http://www.econ.yale.edu/smith/), profesor de la Universidad de Yale, tiene unos consejos muy útiles para realizar un buen trabajo computacional. [Ver el PDF aquí](http://www.econ.yale.edu/smith/econ561a/compute6.pdf).
- [JuliaDocs](https://github.com/JuliaDocs) pone a disposición una hoja de consulta rápida, la misma que se puede encontrar [aquí](https://juliadocs.github.io/Julia-Cheat-Sheet/).