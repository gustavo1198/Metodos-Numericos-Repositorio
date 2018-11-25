# Metodos-Numericos-Repositorio

Un método numérico es un procedimiento mediante el cual se obtiene, casi siempre de manera aproximada, 
la solución de ciertos problemas realizando cálculos puramente aritméticos y lógicos (operaciones aritméticas elementales,
cálculo de funciones, consulta de una tabla de valores, cálculo preposicional, etc.). 
Un tal procedimiento consiste de una lista finita de instrucciones precisas que especifican una 
secuencia de operaciones algebraicas y lógicas (algoritmo), 
que producen o bien una aproximación de la solución del problema (solución numérica) o bien un mensaje. 
La eficiencia en el cálculo de dicha aproximación depende, en parte, de la facilidad de implementación del algoritmo y de
las características especiales y limitaciones de los instrumentos de cálculo (los computadores).

Primer 
Parcial

  Bisección
    El método de bisección es un método geométricamente muy intuitivo: partiendo de un intervalo 
[a,b] tal que f(a)f(b)<0 (es decir: la función cambia de signo en el intervalo), se va dividiendo en dos generando una sucesión de intervalos encajados hasta que se converge con la precisión deseada a la raíz de la ecuación que, como asegura el teorema de Bolzano, tiene que existir

  Punto
Fijo
    El método de punto fijo es un método
iterativo
• La idea principal es encontrar las raices de
una ecuación al proponerlas como puntos
fijos de una formulación alternativa.

  Convergencia
    Se entiende por convergencia de un método numérico la garantía de que, al realizar un buen número de repeticiones (iteraciones), las aproximaciones obtenidas terminan por acercarse cada vez más al verdadero valor buscado.

  Gráfico
    Cada una de las ecuaciones que forman un sistema lineal de dos ecuaciones con dos incógnitas es la de una función de primer grado, es decir, una recta. El método gráfico para resolver este tipo de sistemas consiste, por tanto, en representar en unos ejes cartesianos, o sistema de coordenadas, ambas rectas y comprobar si se cortan y, si es así, dónde.

  Falsa
Posición
    El método de la falsa posición pretende conjugar la seguridad del método de la bisección con la rapidez del método de la secante. Este método, como en el método de la bisección, parte de dos puntos que rodean a la raíz f(x) = 0, es decir, dos puntos x0 y x1tales que f(x0)f(x1) < 0. La siguiente aproximación, x2, se calcula como la intersección con el eje X de la recta que une ambos puntos (empleando la ecuación (35) del método de la secante). La asignación del nuevo intervalo de búsqueda se realiza como en el método de la bisección: entre ambos intervalos, [x0,x2] y [x2,x1], se toma aquel que cumpla f(x)f(x2) < 0.

  Bairstow
    Se trata de un proceso iterativo que combina los métodos de Muller y Newton-Rapshon. Para poder realizarlo, debemos de partir de dos polinomios cuadráticos:
Dados los datos anteriores, continuamos.

  Newton-
Raphson
    Este método es uno de los mas utilizados para localizar raíces ya que en general es muy eficiente y siempre converge para una función polinomial.
Se requiere que las funciones sean diferenciables, y por tanto, continuas, para poder aplicar este método.
Se debe partir de  un valor inicial para la raíz: xi , este puede ser cualquier valor, el método convergirá a la raíz mas cercana.
Si se extiende una tangente desde el punto b , el punto donde esta tangente cruza al eje x representa una aproximación mejorada de la raíz.



Segundo 
Parcial

  Matrices
    Las matrices se utilizan para múltiples aplicaciones y sirven, en particular, para representar los coeficientes de los sistemas de ecuaciones lineales o para representar transformaciones lineales dada una base.

  Eliminación
Gaussiana
    En forma general este método propone la eliminación progresiva de variables en el sistema de ecuaciones, hasta tener sólo una ecuación con una incógnita. Una vez resuelta esta, se procede por sustitución regresiva hasta obtener los valores de todas las variables.

  Factorización
LU
    La factorizaci´on LU de una matriz es una factorizaci´on que resume el proceso de eliminaci´on gaussiana
aplicado a la matriz y que es conveniente en terminos del n´umero total de operaciones de punto flotante cuando
se desea calcular la inversa de una matriz o cuando se resolver´a una serie de sistemas de ecuaciones con una
misma matriz de coeficientes.

  Gauss-
Seidel
    El Método de Gauss-Seidel consiste en hacer iteraciones, a partir de un vector inicial, para encontrar los valores de las incógnitas hasta llegar a una tolerancia deseada, la diferencia radica en que cada vez que se desee encontrar un nuevo valor de una xi, además de usar los valores anteriores de las x, también utiliza valores actuales de las x encontradas antes 

  SE
Newton-Rapshon
    Este m´etodo se basa en utilizar el desarrollo de Taylor. Partimos de un
sistema de la forma
f1(x, y) = 0 ,
f2(x, y) = 0 ,
del que se pretende obtener la soluci´on



Tercer 
Parcial

  Regresión
Polinomial
     la regresión polinomial es una forma de regresión lineal en la que la relación entre la variable independiente x y la variable dependiente y es modelada como un polinomio de grado n en x. La regresión polinomial se ajusta a una relación no lineal entre el valor de x y la correspondiente media condicional de y

  Interpolación
Polinomial
    la interpolación polinómica (o polinomial) es una técnica de interpolación de un conjunto de datos o de una función por un polinomio. Es decir, dado cierto número de puntos obtenidos por muestreo o a partir de un experimento se pretende encontrar un polinomio que pase por todos los puntos.



  Método
de Lagrange
    En los problemas de optimización, los multiplicadores de Lagrange, nombrados así en honor a Joseph Louis Lagrange, son un método para trabajar con funciones de varias variables que nos interesa maximizar o minimizar, y está sujeta a ciertas restricciones. Este método reduce el problema restringido en n variables en uno sin restricciones de n + 1 variables cuyas ecuaciones pueden ser resueltas.

  Ecuaciones
Diferenciales
- Euler
    El m´etodo de Euler consiste en encontrar iterativamente la soluci´on de una ecuaci´on diferencial de
primer orden y valores iniciales conocidos para un rango de valores. Partiendo de un valor inicial x0
y avanzando con un paso h, se pueden obtener los valores de la soluci´on de la siguiente manera:
Yk+1 = Yk + h · f(xk, Yk)
Donde Y es soluci´on de la ecuaci´on diferencial y f es la ecuaci´on diferencial en funci´on de las
variables independientes.

  Ecuaciones
Diferenciales
- Runge
- Kutta
    Los métodos de Runge-Kutta (RK) logran una exactitud del procedimiento de una
serie de Taylor, sin requerir el cálculo de derivadas superiores.
Probablemente uno de los procedimientos más difundidos, y a la vez más exactos,
para obtener la solución numérica del problema de valor inicial:
y´ = f(t,y), con y(to) = yo,

  Ecuaciones
Diferenciales
de Orden
Superior
    Una ecuación diferencial ordinaria de orden superior es una expresión que relaciona una
variable dependiente: y y sus derivadas de cualquier orden con respecto a una variable independiente
x. La solucion para estas ecuaciones es diferente.
