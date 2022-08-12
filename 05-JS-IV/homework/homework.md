1.- Objects : 
Los objetos son utilizados para almacenar una n cantidad de datos.
por ejemplo:

let Persona = {
    nombre: "",
    edad: 15,
    pais: "",
};

A lo que podemos llamar Objeto, es al conjunto de datos almacenados en nuestra variable persona.

2.- Propiedades:

Le podemos llamar propiedades a lo que se refiere al conjunto de key value y el valor del mismo. Tomaremos el ejemplo anterior para expresarlo visualmente:

      Valor
        |   
        |
        |
(edad: 15,)  === PROPIEDAD :) 
    |
    |
    v
Key value

3.-Metodos:

Metodos se le denomina a las funciones guardadas en un Objeto. por ejemplo:

var saludo = {
    saludar: function(){
        console.log("Hola, yo soy un metodo");
    }
};

4. for..in loop: 

El bucle no es como el tradicional debido a que no puede llevar numeración. Por el contrario, declararemos una nueva variable y el nombre de nuestro objeto para que nos retorne el valor de la keyword asociada. 

5.-notacion de puntos vs notacion de corchetes:

A pesar de que cumplan la función de asignar nuevos valores o llamarlos. Se considera a la notación de puntos menos especifica a la notacion de corchetes.
