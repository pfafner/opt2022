# Métodos Numéricos II 2022

Este curso es continuación de los temas estudiados en Métodos Numéricos 1. En esta materia, se estudian o revisan temas no introductorios de algoritmos para cálculo científico y aplicado y su implementación computacional. Se estudian tres grandes temas: (1) Álgebra lineal computacional, (2) Optimización numérica continua, y (3) Optimización discreta. La primera parte el curso se enfoca en temas sobre cálculo de autovalores y autovectores, y la solución eficiente de sistemas lineales. En el segundo bloque, el bloque principal del curso, introduce los temas de optimización numérica, principalmente los métodos de gradiente y punto interior, así como métodos de la familia de gradiente conjugado y métodos quasi-Newton. El tema culmina haciendo un estudio de la teoría de optimización restricta, particularmente programación lineal y programación cuadrática. Finalmente, en el tercer bloque, hacemos una introducción a algunos métodos de optimización combinatoria y discreta. 

**Importante!!** El curso cuenta con una parte práctica extensiva, en la que el estudiante implementará en código computacional cada uno de los algoritmos estudiados. Parte fundamental del curso es utilizar las herramientas aprendidas en varios proyectos aplicados donde se trabajará con datos reales y comunicar los resultados mediante reportes técnicos y seminarios.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los temas:
* Cálculo vectorial
* Álgebra lineal (teoría)
* Algunos elementos de análisis (convergencia de secuencias y series, análisis en Rn)
* Métodos numéricos para una variable (*root finding*, *fitting*, *numerical differentiation and integration*)
* Programación en Python.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-opt2022.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Martes y jueves de 18:10 a 19:45.

### Office Hours
<div id='id-office'/>

* Viernes de 19:00 a 20:00.


# Material del curso
<div id='id-material'/>

  **No.**  | **Fecha**    | **Tópicos**                                                                   | **Recursos**
  -------- | ------------ | ----------------------------------------------------------------------------- |  -------------------------------------
  01       | 05.07.2022   | Introducción al curso. Normas matriciales. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} | Libro de Trefethen, Lecture 3.
  02       | 07.07.2022   | Ejemplos de normas matriciales. Descomposición espectral. <br/> [Aula 02](aulas/Aula02.pdf){:target="_blank"} | Libro de Trefethen, Lecture 4.
  03       | 12.07.2022   | Descomposición SVD. Propiedades. <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"} | Libro de Trefethen, Lecture 5.
  04       | 14.07.2022   | Ejemplo de SVD. Descomposición de Schur. Estabilidad. <br/> [Aula 04](aulas/Aula04.pdf){:target="_blank"} | Libro de Trefethen, Lecture 12.
  05       | 19.07.2022   | Número de condición. Aritmética de punto flotante. <br/> [Aula 05](aulas/Aula05.pdf){:target="_blank"} | Libro de Trefethen, Lectures 13-15.
  06       | 21.07.2022   | Eliminación gaussiana. Factoracón LU y PA = LU.  <br/> [Aula 06](aulas/Aula06.pdf){:target="_blank"} | Libro de Trefethen, Lecture 6.
  07       | 26.07.2022   | Gauss-Jordan. Estrategias de pivoteo.  <br/> [Aula 07](aulas/Aula07.pdf){:target="_blank"} | Libro de Trefethen, Lecture 6. <br/> Burden y Faires, Cap. 6.
  08       | 26.07.2022   | Descomposición LL^T y LDL^T. <br/> [Aula 08](aulas/Aula08.pdf){:target="_blank"} | Libro de Trefethen, Lecture 23.
  L1       | 28.07.2022   |                 | [Lista 1](listas/Lista01.pdf){:target="_blank"} <br/> **Fecha de entrega: martes 16 de agosto.**
  09       | 02.08.2022   | Métodos iterativos para sistemas lineales. <br/> [Aula 09](aulas/Aula09.pdf){:target="_blank"} | Libro de Quarteroni *et al.*, Cap. 4.
  10       | 04.08.2022   | Proyectores. Factoración QR. <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | Libro de Trefethen, Lectures 6-8 y 10.
  11       | 16.08.2022   | Cálculo de autovalores. Método de las Potencias. [Aula 11](aulas/Aula11.pdf){:target="_blank"} | Libro de Trefethen, Lecture ??.
  12       | 18.08.2022   | El método QR. <br/> [Aula 12](aulas/Aula12.pdf){:target="_blank"} | 
  13       | 23.08.2022   | Matrices dispersas. <br/> [Aula 13](aulas/Aula13.pdf){:target="_blank"} | 
  14       | 25.08.2022   | Derivadas vectoriales y Cálculo matricial. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"} |  
  L2       | 01.09.2022   |                 | [Lista 2](listas/Lista02.pdf){:target="_blank"} <br/> **Fecha de entrega: martes 20 de septiembre.**
  16       | 01.09.2022   | Fundamentos de optimización. <br/> [Aula 15](aulas/Aula15.pdf){:target="_blank"} |  
  17       | 06.09.2022   | Condiciones de Optimalidad. <br/> [Aula 16](aulas/Aula16.pdf){:target="_blank"} |  
  18       | 08.09.2022   | Optimización Convexa. <br/> [Aula 17](aulas/Aula17.pdf){:target="_blank"} | Boyd y Vandenberghe. Caps 1 y 2. 
  19       | 20.09.2022   | Descenso gradiente. <br/> [Aula 18](aulas/Aula18.pdf){:target="_blank"} | Nocedal y Wright.
  20       | 22.09.2022   | Algoritmos de optimización 1-dimensional. <br/> [Aula 19](aulas/Aula19.pdf){:target="_blank"} | Nocedal y Wright.
  21       | 27.09.2022   | Búsqueda en línea. Condiciones de Wolfe y de Goldstein. *Backtracking*. <br/>  | Nocedal y Wright.
  22       | 29.09.2022   | Convergencia. <br/>  | Nocedal y Wright.
  L3       | 29.09.2022   |                 | [Lista 3](listas/Lista03.pdf){:target="_blank"} <br/> **Fecha de entrega: jueves 13 de octubre.**
  23       | 06.10.2022   | Estimación de la tasa de convergencia. <br/>  | Nocedal y Wright.
  24       | 11.10.2022   | Descenso Coordenado. Gradiente Proyectado. <br/>  | Nocedal y Wright.
  25       | 13.10.2022   | Aplicaciones: Bases radiales gaussianas. <br/>  | 
  27       | 25.10.2022   | Métodos Cuasi-Newton: SR1, DFP, BFGS. <br/>  | 
  28       | 27.10.2022   | Optimización sin derivadas. Método de Nelder-Mead. <br/>  | 
  29       | 03.11.2022   | Optimización discreta. Representaciones.     | 
  30       | 08.11.2022   | Búsqueda local. BFS, DFS, *Backgracking*. | 
  31       | 10.11.2022   | Hill-Climbing. Estrategias para problemas discretos. | 
  32       | 15.11.2022   | Enfriamiento simulado.                               | 
  33       | 17.11.2022   | Algoritmos genéticos.  | 
  34       | 18.11.2022   | Operadores de selección, cruce y mutación. Ejemplos. | 
  35       | 22.11.2022   | Presentación de seminarios.  | 
  

# Proyectos
<div id='id-proj'/>

A continuación se listan algunos temas sugeridos para presentación de sus proyectos de curso. [Temas-proyecto.pdf](proyectos/Temas_proyecto.pdf){:target="_blank"}

### Fechas importantes:

  **No.**  | **Fecha**       |  .
  -------- | --------------- | ---------------------------------------------------
  1        | 21.10.2022      | Elección de tema de proyecto.
  2        | 15.11.2022      | Entrega de presentación y reporte (borrador).
  3        | 21-25.11.2022   | Presentación de Seminarios.
  4        | 27.11.2022      | Entrega de versión final (Presentación, Reporte, Código).

### Temas presentados:

**No.**  | **Fecha**    | **Conferencistas**                 | **Tópico**                                                                    
-------- | ------------ | ---------------------------------- | --------------------------------------------------- 
 1       | 22.11.2021   | José Lucha                         |  El problema TPS
 2       | 22.11.2021   | Juan Lorthiois, Leonel Contreras   |  Un ejemplo de Programación Lineal
 3       | 24.11.2021   | Carlos Martínez, Elder Guzmán      |  Un problema de Asignación de Recursos
 4       | 24.11.2021   | Oscar Godoy, Rafael Dubois         |  El problema Knapsack


# Referencias
<div id='id-ref'/>

### Textos:

* [L. Trefethen, L. Bau III (1997). *Numerical Linear Algebra*.](http://library.lol/main/079EA6C3FD8CDF23B0C2ACD901CA9A26){:target="_blank"}

* [J. Nocedal, S. Wright (2006). *Numerical Optimization*.](http://library.lol/main/7016B74CFE6DC64C75864322EE4AA081){:target="_blank"}


### Referencias adicionales:

* [R. Burden, A. Burden, D. J. Faires (2017). *Análisis numérico.*](http://library.lol/main/87525D7D988D11F87963D6832EAA9493){:target="_blank"}

* [G. Golub, C. Van Loan (2012). *Matrix Computations*.](http://library.lol/main/72562A3A733C2E842BE163CA97D0FA7A){:target="_blank"}

* [A. Quarteroni, R. Sacco, F. Saleri (2000). *Numerical Mathematics*.](http://library.lol/main/7D136BC80ECBF0BA65798EC129FCCAF4){:target="_blank"}

* [J. Stoer, R. Bulirsch (2002). *Introduction to Numerical Analysis*.](http://library.lol/main/04B36CA585EB49F5FDED7479823F2B50){:target="_blank"}

* [D. Luenberger, Y. Ye (2016). *Linear and Nonlinear Programming*.](http://library.lol/main/EB915E0FDCC8D3BA222B37C9A3DD6B4F){:target="_blank"}

* [A. Izmailov, M. Solodov (2014). *Newton-type for Optimization and Variational Problems*.](http://library.lol/main/C8C3ED2461D9C8C2608595B223ABDD91){:target="_blank"}

* [S. Boyd, L. Vandenberghe (2009). *Convex Optimization*.](http://library.lol/main/A9A5D9C3CA105DB0F41AF39A6C89706C){:target="_blank"}

* [C. Meyer (2001). *Matrix Analysis and Applied Linear Algebra*.](http://library.lol/main/7EF368F2EA42EB4E48F09EA438C1822E){:target="_blank"}


### Referencias de Programación:

* [Q. Kong, T. Siauw, A. Bayen (2021). *Python Programming and Numerical Methods - A Guide for Engineers and Scientists*.](http://library.lol/main/C243E02353CAB4D3A26F4DBD0527E133){:target="_blank"} <br/>
  [Web version](https://pythonnumericalmethods.berkeley.edu/notebooks/Index.html){:target="_blank"}

* [A. Gezerlis (2020). *Numerical Methods in Physics with Python*.](http://library.lol/main/16158CCB54986445C6EC84980B58DB7E){:target="_blank"}

* [Jaan Kiusalaas (2013). *Numerical Methods in Engineering with Python 3*.](http://library.lol/main/8F89791F3C9338F2E23EEC2C7BF5403B){:target="_blank"}

---
