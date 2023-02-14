# Tipos de lenguajes de programación

En el siguiente módulo, se abordará la definición de un lenguaje de programación, sus principales características, los diferentes paradigmas y los conceptos claves para entender la diferencia entre un lenguaje fuertemente tipado ante uno que no lo es.

## Módulo 2

* Lenguaje de programación
* Paradigmas
* Depuración de programas
* Lenguajes tipados vs. no tipados


> ### Lenguaje de Programación

Es un lenguaje formal o artificial que le proporciona a una persona, en este caso al programador, la capacidad de escribir una `serie de instrucciones o secuencias` de órdenes en forma de algoritmos con el fin de controlar el comportamiento físico o lógico de un sistema informático.


> ### Paradigmas

Formas de clasificar en múltiples paradigmas y los más comunes son:
* Procedural
* Orientado a Objetos
* Orientado a Eventos

> ### Depuración de programas

Es el proceso de `identificar y corregir errores de programación`.

Es conocido también por el término inglés *debugging*, cuyo significado de es la eliminación de *bugs* (bichos), que es la manera en que se conoce informalmente a los errores de programación.


> ### Lenguajes tipados vs. no tipados

Un lenguaje de programación es `fuertemente tipado` si no se permiten violaciones de los tipos de datos, es decir, dado el valor de una variable de un tipo concreto, no se puede usar como si fuera de otro tipo distinto a menos que se haga una conversión. No hay una única definición de este término.

Un lenguaje que se dice que `no está tipado`, se refiere a que no está fuertemente tipado.

~~~ js
public void processData () {
  do {
    int data = getData();
    
    if (data < 0)
    performOperation1(data);
    else
    performOperation2(data);
    while (hasMoreData());
  }
}
~~~

### Actividades:

> #### **Todos los lenguajes de programación son tipados**

* Falso.


> #### **Los lenguajes de programación tienen distintas sintaxis**

* Verdadero

> #### **Los paradigmas de programación más populares son:**

* Procedural y Orientado a objetos.


> #### **Un compilador...**

* Transforma el lenguaje de programación de alto nivel en lenguaje de máquina.


> #### **Todos los lenguajes son multiplataforma**

* Falso