# Homework: Javascript II

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `for`
Para empezar a explicar la declaración 'For' debemos tener claro que es un bucle, podemos describir un bucle como una forma rápida y sencilla de repetir una tarea de forma continua y que solo se detiene cuando cumpla unas condiciones hay muchos tipos de bucles, pero todos en esencia hacen lo mismo repetir una acción muchas veces 

Ahora se puede definir a la declaración 'For' como un bucle que solo se detendrá hasta que la condición dada sea falsa, por esta razón la declaración 'For' lleva estas tres partes 
Expresión inicial:  esta expresión inicia el contador del bucle sin entrar en detalles podemos decir que esta expresión puede tener muchas formas e incluso puede declarar una variable 
Expresión condicional: esta es de especial interés ya que es la que nos determina por cuanto tiempo se realizara el bucle, pues es la que la declaración 'For' analiza para determinar si es verdadera o falsa cuando esta expresión se clasifica como falsa la tarea se ve interrumpida 
Expresión de actualización: aquí hay un pequeño truco y es el siguiente, cuando la expresión condicional sigue siendo verdadera o true la instrucción se ejecuta por ejemplo si la idea es sumar 1+1 hasta 3 podemos decir que la instrucción es el resultado hasta antes de tres (es decir 1 y 2)    y esta expresión de actualización entra en acción, diciéndole a 'For' que hay que ir al segundo paso y evaluar nuevamente 
De esta forma vemos que la expresión completa de un bucle for se construye así 

For ([Expresión Inicial]; [Expresión Condicional]; [Expresión de Actualización])
Instrucción 


En este ejemplo crearemos un contador de 1 a 10

     (Expresion Inicial) (Expresion Condicional)    (Expresion de Actualizacion)
For (   var i = 0;               i<10;                         i++             ) { 
      Return  i; 
}    (instruccion)  

## Operadopres logicos 

Un operador lógico es aquel que compara y evalúa si algunas condiciones dadas son true o false y realizara una acción según la tabla de verdad. el priemro es: 

* And “ y “ `&&`,

Lo escribimos de la siguiente manera  && y nos permite evaluar ambas expresiones, en este caso si una de las expresiones dadas es falsa nos dará un resultado falso  podemos decir que para que sea verdadero ambas expresiones deben ser verdaderas 

Ejemplo 

Let hora = 12
Let minuto = 30 
If (hora == 12; && minuto == 30) {
Return ‘son las 12 30 del dia’ ;


* operador:  OR  "o" `||`,


Este operador también evalúa dos expresiones y si valida que una de ellas es true devolverá true sin importar que la otra no lo sea solo devolverá false si ambas expresiones son falsas

Ejemplo 

Let mascota = perro 
Let animal = caballo
 If (mascota == perro || animal == gato 
Return es un ser vivo 



 operador: No "Not" `!`

El operador lógico denominado como ‘No’  e identificado como “Not” y cuya forma de escribir es (!) este nos devolverá un valor contrario u opuesto a el valor booleno (true/false) básicamente este operador es una negación 
Lat (a = true) 
If ( !(a)) devuelve falso 