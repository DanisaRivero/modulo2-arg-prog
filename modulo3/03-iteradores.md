# Iteradores

>## While
__*Se utiliza cuando no sabemos el valor inicial como para el incremento o decremento de la sentencia.*__
~~~js
while (condicion){
  // código que se va a ejecutar
}
// Se ejecutará el bloque de código mientras la condición sea verdadera
~~~

>## Do-While
__*Funciona como el while, pero al revés, primero ejecuta el código, después cumple la condición, al menos una sola vez se ejecutará.*__

~~~ js
let x = 10;
do{
  console.log('Mi variable vale ' + x);
}while(x > 10);
~~~

>## For
 __*Este iterador se utiliza cuando sabemos la cantidad de iteraciones que hará ese ciclo*__
~~~ js
  //inicioContador  //condicion   //incremento contador
for (let i = 0; i < frutas.lenght; i++) {
  document.write (frutas[i] + "y");
}
// for (inicialización; condición; incremento/decremento de la variable)
~~~

>## Break

__*Esta sentencia sirve para cortar o salir de la ejecución por el motivo que fuese de cualquier iterador y anidado con un condicional*__

~~~ js
let x = 10;

for(x; x > 0; x--){
  if(x==5){
    break;
  }
 console.log(`El valor de x es: ${x}`); //Sentencia
}
~~~