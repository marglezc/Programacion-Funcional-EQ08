# Descripción de la ejecución de cada uno de los problemas
## Ejercicio 1
Defina una función para la evaluación del número combinatorio C(n,k), que utiliza la
definición recursiva.
![Definición recursiva](https://github.com/marglezc/Programacion-Funcional-EQ08/blob/Archivos/Imagenes/e1.1.png)

**Entrada**

* **elemento**: recibe dos números enteros n y k. Estos números representan respectivamente el tamaño del conjunto del que se eligen los elementos (n) y la cantidad de elementos que se van a seleccionar (k).

**Salida**

La salida de la función será un número entero que representa el coeficiente binomial, es decir, el número de formas en que se pueden elegir k elementos de un conjunto de n elementos.

**Ejemplo**

n:15

k:14

Número combinatorio: 
15
## Ejercicio 2
Defina una función recursiva para calcular el Máximo Común Divisor de dos enteros
negativos a y b con a < b usando el hecho de que MCD(a, b) = MCD(a, b-a).

**Entrada**

* a : número entero negativo

* b : número entero negativo

**Salida**

Número entero máximo común divisor de a y b

**Ejemplo**

a:-8

b:-12

El MCD de -8 y -12 es: 4
## Ejercicio 3
Definir una función que devuelva, en una lista, todos los números primos desde un número
inicial hasta un número final, ejemplo: (primos 3 10) este ejemplo devolverá ‘(5 7).

**Entrada**

* inicio : número inicial del intervalo de números que se evaluará

* fin : número final del intervalo de números que se evaluará

**Salida**

Lista de todos los números primos dentro del intervalo

**Ejemplo**

inicio: 3

fin: 7

Lista de primos: (3 5 7)
## Ejercicio 4
Realizar una función para buscar un elemento en una lista, regresar #t si lo encontró y #f si
no lo encontró.

**Entrada**

* elemento : elemento que se buscará en la lista. Puede ser de tipo entero, flotante, cadena de caractéres, booleano o lista.
* lista : lista que puede contener o no el elemento que se buscará. La lista puede contener elementos de distintos tipos. La lista empieza y termina con paréntesis y los elementos de la lista van separados con un espacio. Ejemplo: (2 3 4)
  
**Salida**

Valor booleano que indicará si se encontró el elemento o no.

#t si se encontró el elemento.

#f si no se encontró el elemento.

**Ejemplo**

lista:(2 3 5 7)

elemento: 7

#t
## Ejercicio 5
Realizar una función recursiva que invierta una lista.

**Entrada**

* lista : lista que se quiere invertir. La lista puede contener elementos de distintos tipos. La lista empieza y termina con paréntesis y los elementos de la lista van separados con un espacio. Ejemplo: (2 3 4)

**Salida**
  
Lista invertida.

**Ejemplo**

lista: (2 3 4)

Lista invertida: 
(4 3 2)
## Ejercicio 6
Realizar una función recursiva que elimine un elemento de una lista

**Entrada**

* elemento : elemento que se eliminará en la lista. Puede ser de tipo entero, flotante, cadena de caractéres, booleano o lista.
* lista : lista que puede contener o no el elemento que se eliminará. La lista puede contener elementos de distintos tipos. La lista empieza y termina con paréntesis y los elementos de la lista van separados con un espacio. Ejemplo: (2 3 4)

**Salida**

Lista sin el elemento que se eliminó. En caso de que el elemento que se quiere eliminar no esté en la lista, la lista se mostrará sin cambios.

**Ejemplo** 

lista: (2 5 3)

elemento a eliminar: 5

Lista sin elemento: (2 3)
## Ejercicio 7
Dado un número entero positivo, realizar una función recursiva que devuelva verdadero (#t)
si el número dado es un palíndromo, en caso contrario, retornar falso (#f). Por ejemplo,
12321 es un palíndromo, pero 1451 no es un palíndromo. No use la función reverse de
Racket.

**Entrada**

* num : número entero que se verificará.

**Salida**

Valor booleano que indicará si el número es palíndromo o no.

#t si es palíndromo.

#f si no es palíndromo.

**Ejemplo**
Entero positivo: 789987

Es palindromo?

#t

## Ejercicio 8
Realizar una función recursiva que, dado un número entero, encuentra la suma de sus
dígitos. No use funciones incorporadas de Racket.

**Entrada**

* Recibe un número entero n como entrada.
  
**Salida**

* Si n es igual a 0, devuelve 0.
  
* De lo contrario, suma el último dígito de n (obtenido con remainder n 10) con la suma de los dígitos restantes (obtenida al llamar recursivamente a suma-digitos con quotient n 10).
## Ejercicio 9
Realizar una función recursiva que, dado un número entero decimal retorne el número
binario equivalente. No use funciones incorporadas de Racket.

**Entrada**

* num : número entero mayor o igual a 0. Número decimal que se evaluará.

**Salida**

Cadena con el número binario equivalente al número de entrada.

**Ejemplo**

Entero positivo decimal: 4 

Binario equivalente: 
100
## Ejercicio 10
Utilizando la serie de Leibnitz y mediante una función recursiva, calcule el valor de PI
![Leibnitz](https://github.com/marglezc/Programacion-Funcional-EQ08/blob/Archivos/Imagenes/e10.png)

**Entrada**

* n : número entero mayor a 0. Número de iteraciones que se hará en la serie.

**Salida**

Valor flotante estimado de PI después de n iteraciones.

**Ejemplo**

Iteraciones de la serie: 

Valor aproximado de PI: 
3.1449149035588517
