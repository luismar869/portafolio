+++
date = '2025-02-21T08:43:55-08:00'
draft = false
title = 'Practica1: Elementos Basicos de los Lenguajes de Programacion'
+++

<!-- Esto es un comentario -->

Los elementos básicos de un programa sin importar el lenguaje de programación
son importantes para así comprender su estructura y aún más vital el
funcionamiento y razonamiento lógico que se lleva a cabo en dicho código. Algunos
elementos básicos pueden ser (nombres, objetos, entornos, bloques, alcance,
administración de memoria, expresiones, comandos, secuencia, selección, iteración,
recursión, subprogramas, y tipos de datos).

A continuación se va hacer un análisis acerca de estos elementos en un código de
ejemplo proporcionado por el maestro en el cual se mencionan y ejemplifican el uso
de cada uno:

## Nombres

Para la cuestión de nombres, esto es simplemente la forma de identificar ya sea a
una variable, constante, función etc. En el caso del código proporcionado se pueden
identificar los siguientes nombres:

![Foto 1](/p1_png1.png)

Estos son nombres de funciones como “freeLibrary” y “freeMembers” pero además
en los diferentes bloques del código se crean múltiples variables con diferentes
nombres cada una.

## Objetos

En el caso de objetos, este puede ser algo confuso ya que en sí un código es digital
y no puede llegar a ser un objeto físico, por lo que en este caso se refiere a una
“referencia a su uso”. Por ejemplo la estructura “book_t” hace referencia a un libro
real el cual contiene un id, titulo, autor, año de publicación, género y cantidad de
páginas.

![Foto 2](/p1_png2.png)

## Entornos

A entornos nos podemos referir a bloques de código y como todos sus elementos se
desarrollan en el entorno ya sea local o global. Por ejemplo, la variable “new_book”
declarada en la función “addBook” tiene un alcance local dentro de la función, a
diferencia de la variable “static_var” la cual es declarada al inicio del programa, esta
tiene alcance a todo el programa, ya sea en funciones o en el main.

![Foto 3](/p1_png3.png)

## Bloques

Se puede decir que un bloque de código es aquel que está delimitado por llaves “{}”,
en el caso del código ejemplo se puede observar que cada función es un bloque al
igual que el main. 

![Foto 4](/p1_png4.png)

## Alcance

Alcance se refiere al alcance de las variables, lo que previamente se mencionó en
Entornos, donde “static_var” y armas “bss_var” son variables con alcance a todo el
código, a las cuales nos podemos referir que tienen alcance global. Mientras las
variables declaradas únicamente dentro de las funciones las podemos describir
como variables locales.

![Foto 5](/p1_png5.png)

## Administracion de Memoria

Para asignar un espacio de memoria en C se utiliza el comando “malloc” el cual
asigna un espacio de memoria en el heap a la variable, estructura, arreglo, etc, que
desees almacenar. Esto sirve para poder almacenar datos al momento de ejecución
sin saber su tamaño, por lo que también se le conoce como memoria dinámica.

![Foto 6](/p1_png6.png)

Ya que se haya dejado de utilizar ese espacio de memoria se debe liberar utilizando
el comando “free”. Esto para no ir llenando la memoria de datos innecesarios que a
a la larga va reduciendo la velocidad y capacidad del sistema.

![Foto 7](/p1_png7.png)

## Expresiones

En el caso de expresiones podemos decir que son instrucciones las cuales indican
una acción dentro del código utilizando comandos o operadores. A continuación se
muestran diferentes ejemplos:

![Foto 8](/p1_png8.png)

## Comandos

Los comandos son instrucciones las cuales indican una accion a realizar, estos en la
mayoría de los casos son utilizados en conjunto con variables, funciones,
estructuras, arreglos, etc.

![Foto 9](/p1_png9.png)

En el ejemplo anterior los comandos son aquellos de color amarillo siendo **printf,
getchar, fgets, strcspn**. Cada uno realiza una acción diferente:

* printf = Imprime el texto “Ingresa título del libro: “
* getchar = Lee solo un carácter
* fgets = Recibe como entrada una cadena de texto
* strcspn = Se utiliza para buscar una cadena de texto dentro de otra cadena

## Seleccion

Son estructuras de selección como “if” o “switch” en las cuales se toman decisiones
a partir de ciertas condiciones.

![Foto 10](/images/p1_png10.png)

## Iteracion

Son estructuras de iteración en la cual se utilizan bucles como “while” y “for” para
repetir ciertas instrucciones a partir de ciertas condiciones.

![Foto 11](/images/p1_png11.png)

## Recursion

Un ejemplo de recursividad es en la función “displayBooksRecursive” donde se la
función a si misma para mostrar los libros de manera recursiva. Aunque para que
esta no se repita de manera infinita siempre debe existir una condición que en este
caso es con el comando “if”.

![Foto 12](/images/p1_png12.png)

## Tipos de Datos

Existen múltiples tipos de datos, cada uno con características diferentes a las cuales
se le pueden realizar diferentes funciones, operaciones, instrucciones, etc. Los más
comunes suelen ser int, char, float, double, pero también se pueden realizar tipos de
datos propios por medio de “typedef” el cual crea un tipo de dato en base a un
conjunto de datos. Como es el caso de “book_t”, “member_t” y “genre_t”.

![Foto 13](/images/p1_png13.png)


