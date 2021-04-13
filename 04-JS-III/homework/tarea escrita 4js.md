<<<<<<< HEAD
# Homework: Javascript III

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Arrays

basicamente podemos ver los array como baules donde podemos acomodar de forma organizada la informacion que nesecitamos la organizacion de dichos datos se les dice matriz, en ella podemos agregar diferentes tipós de datos como numeros, booleanos o cadenas de datos (siempre separados por comas) la forma de contruir dichas matrices es declarar una variable y luego establecerla en [] y luego agregar los datos 

Const  nombredeVehiculos [renaul, chevrolet, mazda, ford ]

y luego podemos acceder a esos datos cuando lo deseemos 

para acceder a estos datos solo se debe llamar al elemento por el lugar que ocupa en la matriz, estos puestos se asignan con un numero que comiensa en el cero a esto se le llama indice, por ejemplo si tomamos el ejemplo anterio de los carros se hara de la siguente manera 

Const  nombredeVehiculos [renaul, chevrolet, mazda, ford] 
                             0       1         2      3

el indice 0 se asigna a la primera posicion que en este caso es renault, el inidce 1 a chevrolet y asi consecutivamente, cuando debemos acceder al elemento lo que debes hacer es escribir el nombre de la variable o matriz en parentecis (nombredeVehiculos) y luego entree corchetes el indice o asignacion numerica dentro de la matriz [3]. 

console.log(nombredeVehiculos)[3];

alli nos mostrara el nombre asignado al indice 3 es este caso ford 

'ford' 

otro caracteristica importante del array es que se puede agregar o quitar elementos nuevos, al principio o al final de la matriz.
para agregar y quitar al final de la declaracion usamos el metodo de .push y .pop el primero agrega un elemento al final de la matriz y el segundo elimina el ultimo elemento de la matriz 

.unshif y .shift realizan una accion igual a la de .push y . pop pero al inicio de la matriz es decir  . unshif (mas el nombre del item ) agregaran un nuevo elemento y el .shift elimina el primer elemento de la matriz.
