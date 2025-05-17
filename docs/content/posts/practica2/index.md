+++
date = '2025-02-21T08:43:55-08:00'
draft = false
title = 'Practica2: POO en Python'
+++

## Introduccion 

La práctica realizada en el lenguaje de python consta del uso de bibliotecas propias y su implementación para definir clases y sus operaciones al igual que su aplicación web. Esto se lleva a cabo en 3 archivos .py los cuales se analizaran para así desglosar sus funciones y funcionamiento.

## Desarrollo

### biblioteca.py

En el siguiente bloque de código se importa el módulo nombrado “*json*” el cual se utilizara para dar formato *JSON* a objetos creados. Además en la línea 4 del documento memory_management.py se importa su clase definida la cual tiene el mismo nombre.

![Foto 1](/images/p2_png1.png)

Posteriormente se define la primera clase llamada “*Genre*” la cual define los géneros de los libros que en este caso son los atributos de la clase. Al final por medio del *return* regresa la lista de todos los géneros creados.

![Foto 2](/images/p2_png2.png)

Aquí se crea otra clase llamada *Book*, este objeto se inicia por medio de un constructor en la línea 24 definiendo sus argumentos. Y por medio de la clase *memory_management* se aumenta el heap cada que se crea un libro o en caso de eliminarse se realiza con un destructor.  

![Foto 3](/images/p2_png3.png)

Esta clase *Digital Book* hereda de la clase *Book*, lo cual significa que los objetos creados de esta clase tendrá los atributos de la clase *Book* añadiendo información para libros digitales, al igual formas de cargar y guardar.

![Foto 4](/images/p2_png4.png)

Aquí en *Member* se definen los atributos de un miembro como su *ID, Nombre y Libros Prestados*. También registra cuando se crea o elimina para crear o borrar un espacio de memoria.

![Foto 5](/images/p2_png5.png)

En esta clase de *Library* se definen la mayoría de funciones las cuales son los métodos / acciones que se realizan en el código como lo son:
* Agregar libros y miembros
* Encontrar libros y miembros
* Mostrar libros y miembros
* Prestar libros
* Devolucion de libros
* Guardar datos de libros
* Cargar datos de libros
* Crear o eliminar espacio de memoria

![Foto 6](/images/p2_png6.png)

Por último en el *main()* es donde empieza el programa y engloba todas las funciones y clases en el cual por medio de un menú se accede a las opciones seleccionadas.

![Foto 7](/images/p2_png7.png)

### biblioteca_web.py

Al inicio de código se importa el módulo de flask para la creación de la página web al igual que las clases de *biblioteca* y sobre el manejo de memoria de *memory_management*. Luego se crea la página web con flask, crea una instancia de Library para manejar datos y carga los datos de miembros y libros en formato JSON.

![Foto 8](/images/p2_png8.png)

El resto del código genera rutas para aplicar las funciones con la aplicación web, todo esto en formato JSON para que sea compatible y así implementarlo.

![Foto 9](/images/p2_png9.png)

Al final se crea el servidor de Flask para así lanzar la web.

![Foto 10](/images/p2_png10.png)

### memory_management.py

En este código corto simplemente crea una clase llamada *MemoryManagement* en la cual contiene un constructor, incrementa el número de espacios ocupados en el heap al igual que lleva el conteo de espacios removidos, además de mostrar el conteo.


![Foto 11](/images/p2_png11.png)

## Conclusion

La práctica fue de mucho aprendizaje al ver aplicaciones web y al mismo tiempo programación orientada a objetos en Python. Conformado por 3 archivos .py los cuales definían clase, implementan aplicaciones web y se encargaban del manejo de memoria.

