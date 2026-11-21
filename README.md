# Optimización Semidefinida | Temas de Optimización Semidefinida

## Repositorio GitHub

Todo el material de la materia, incluyendo el apunte teórico, guías prácticas y slides de las clases se encuentra disponible en el siguiente repositorio GitHub:\
<https://github.com/slap/optimizacion-semidefinida>

## Información en el Campus Virtual

Toda la información actualizada de la materia se publica en el Campus Virtual de la Facultad. Los alumnos y alumnas que cursen la materia, por favor escribir a slaplagn@dm.uba.ar para solicitar la clave de matriculación al Campus.

## Horarios y organización

Se dictará en el 2.º Cuatrimestre 2021. La carga horaria es de 4 horas semanales, distribuidas en una clase teórica de 2 horas y una clase de práctica/laboratorio de 2 horas.

- Martes de 17 a 19h
- Jueves de 17 a 19h

## Docentes

#### Profesor

- Santiago Laplagne - slaplagn@dm.uba.ar

## Correlatividades

Se requiere haber cursado alguna de las siguientes materias: Álgebra lineal / Matemática 2 (F) / Álgebra Lineal Computacional / Métodos Numéricos.\
No se requieren conocimientos previos de programación.

## Breve descripción del curso

La programación semidefinida (SDP) puede considerarse como una extensión de programación lineal a polinomios, donde las restricciones lineales se generalizan a restricciones sobre la positividad de matrices. Es la clase más grande problemas de optimización que podemos resolver eficientemente, con aplicaciones en optimización combinatoria y convexa, teoría de grafos y geometría algebraica.

En este curso comenzaremos estudiando los conceptos básicos de SDP e iremos avanzando hacia desarrollos más actuales, poniendo énfasis especial en la teoría de Parrilo-Lasserre de relajaciones de sumas de cuadrados y aplicaciones. Veremos abundantes ejemplos y cómo resolverlos implementando algoritmos y utilizando bibliotecas de software en Python. En la última parte del curso, nos enfocaremos en un estudio teórico de los conos de polinomios positivos y sumas de cuadrados, siguiendo resultados sorprendentes recientes de G. Blekherman.

## Puntaje y régimen de promoción

- La aprobación de la materia es por entrega de ejercicios durante la cursada y un trabajo final (preparación y exposición de algún tema teórico o práctico).
- Esta materia otorga 3 puntos para la Carrera de Licenciatura en Matemática.
- Esta materia es reconocida como materia optativa de la Licenciatura en Ciencias de Datos (LCD) con 64 horas de duración.
- Esta materia está aprobada como materia de doctorado de la Facultad con un puntaje máximo de 3 puntos. Para averiguar cuántos puntos otorga para un doctorado en particular, consultar con la subcomisión de doctorado correspondiente. Cualquier información será incorporada en esta página.

## Programa

### 1) Preliminares.

Programación lineal. El método simplex. Dualidad en programación lineal. Métodos de punto interior. Aplicaciones. Conjuntos convexos. Descripción implícita de conjuntos convexos. Proyecciones. Hiperplano separador. Hiperplano soporte. Conos convexos. El ortante no-negativo. Matrices definidas y semidefinidas positivas. Teorema espectral. El cono de matrices semidefinidas. Formas cuadráticas y formas bilineales. Diagonalización de formas cuadráticas. Ley de inercia. Python. Introducción a programación en Python. Jupyter Notebook. Anaconda. \

### 2) Programación semidefinida. Conceptos básicos y ejemplos.

Desigualdades matriciales lineales (LMI). Poliedros y espectraedros. Proyección de espectraedros. Problema primal. Conjuntos factibles. Problema dual. Condiciones de optimalidad. Salto de dualidad. Espectraedros como conjuntos factibles de programas semidefinidos. Programación cónica. Dualidad fuerte. Software: Mosek.

### 3) Aplicaciones de optimización semidefinida.

Mayor y menor autovalor. Teoría de control en sistemas dinámicos. Conjuntos estables en grafos. Optimización combinatoria: maxcut. Optimización convexa: volumen mínimo de elipsoide circunscriptp. Datos faltantes en matrices de mínimo rango.

### 4) Optimización polinomial y sumas de cuadrados.

Conjuntos semi-algebraicos. Conos de polinomios no-negativos y sumas de cuadrados. El teorema de Hilbert. Descomposición como suma de cuadrados de polinomios positivos en una variable. Matriz de Gram y criterio de descomposición como suma de cuadrados para polinomios en varias variables. Descomposición racional. Programas de sumas de cuadrados.

### 5) Momentos

El problema de momentos en una dimensión. Problema de momentos completo y truncado. El problema de momentos en varias dimensiones. Algoritmos. Relajación semidefinida. Aplicaciones. Optimización global sobre polinomios. Optimización con restricciones.

## Prácticas

- [Práctica 1 - Programación lineal](practica1-programacionLineal.pdf)
- [Práctica 2 - Introducción a programación semidefinida](practica2-introduccionSDP.pdf)
- [Práctica 3 - Aplicaciones](practica3-aplicaciones.pdf)
- [Práctica 4 - Sumas de cuadrados y momentos](practica4-sos.pdf)

## Diapósitivas de las clases

### I - Programación lineal

- [Clase 01 - Introducción a la materia · El método gráfico](clase01-slides.pdf)
- [Clase 02 | Soluciones básicas factibles](clase02-slides.pdf)
- [Clase 03 | El método simplex](clase03-slides.pdf)

### II - Introducción a programación semidefinida

- [Clase 04 | Matrices definidas positivas](clase04-slides.pdf)
- [Clases 05 y 06 | Conos y espectrahedros · Formulación del problema SDP](clase05-slides.pdf)
- [Clase 07 | Dualidad](clase07-slides.pdf)

### III - Aplicaciones

- [Clase 08 | Max-cut](clase08-slides.pdf)
- [Clases 09 y 10 | Teoría de control](clase09-control.pdf)
- [Clase 11 y Clase 12 Parte 1 | Distancia euclídea y rango mínimo](clase11-distanciaEuclidea.pdf)

### IV - Sumas de cuadrados y momentos

- [Clase 12 Parte 2 y Clase 13 | Polinomios positivos · Factibilidad de sumas de cuadrados y programas SOS](clase12-polinomios.pdf)
- [Clase 14 | Relajación SOS para optimización polinomial](clase14-optimizacion.pdf)
- [Clase 15 | El problema de los momentos](clase15-momentos.pdf)

## Bibliografía principal que se seguirá en el curso

### Programación lineal

- D. Bertsimas, J. Tsitsiklis, “Introduction to Linear Optimization”. Athena Scientific, 1997.

### Programación semidefinida

- G. Blekherman, P. Parrilo y R. Thomas (eds.), “Semidefinite Optimization and Convex Algebraic Geometry”. SIAM, 2013.
- M. J. Todd, “Semidefinite optimization”. Acta Numerica 10, 515-560, 2001.
- M. Laurent y F. Vallentin, “Semidefinite optimization”. Lecture notes. 2016.

### Momentos

- J. B. Lasserre, “Moments, Positive Polynomials and Their Applications”. Imperial College Press, 2010.

## Bibliografía adicional

- A. Ben-Tal y A. Nemirovski, “Lectures on Modern Convex Optimization: Analysis, Algorithms, and Engineering Applications (MPS-SIAM Series on Optimization)”. SIAM, 2001.
- G. Blekherman, “Nonnegative polynomials and sums of squares”. Journal of the American Mathematical Society, 2012.
- S. Boyd y L. Vandenberghe, “Semidefinite programming”. SIAM Review 38, 49-95, 1996.
- S. Boyd. y L. Vandenberghe, “Convex Optimization”. Cambridge University Press, 2004.
- B. Gärtner and J. Matousek, “Approximation Algorithms and Semidefinite Programming”.  Springer, 2012.
- R. D. C. Monteiro, “First- and second-order methods for semidefinite programming”. Mathematical Programming B97, 209-244, 2003.
- A. Nemirovskii y Y. Nesterov, “Interior-Point Polynomial Algorithms in Convex Programming (SIAM Studies in Applied Mathematics, Vol. 13)”. SIAM, 1994.
- P. Parrilo, “Structured Semidefinite Programs and Semialgebraic Geometry Methods in Robustness and Optimization”. Tesis de doctorado, 2000.
- J. Renegar, “A Mathematical View of Interior-Point Methods in Convex Optimization (MPS-SIAM Series on Optimization)”. SIAM, 2001.
- R. Saigal, L. Vandenberghe y H. Wolkowicz (eds.), “Handbook on Semidefinite Programming: Theory, Algorithms, and Applications”. Kluwer Academic, 2000.
- M. J. Todd, “Semidefinite optimization”. Acta Numerica 10, 515-560, 2001.
- S. J. Wright, “Primal-Dual Interior-Point Methods”. SIAM, 1997.
