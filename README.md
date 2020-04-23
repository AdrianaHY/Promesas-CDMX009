# Promesas-CDMX009

## ¿Qué es una promesa?

Según la definición de MDN, una promesa es: El objeto Promise (Promesa) es usado para computaciones asíncronas. Una promesa representa un valor que puede estar disponible ahora, en el futuro, o nunca. O NUNCA!

Se utiliza cuando estamos frente a un código asíncrono, ya que este objeto "nos promete" que devolverá un valor, ya sea en el presente o en el futuro, además recuerda su contexto de ejecución, es decir, sabe en que punto resolverse o lanzar un error (mirar Ejemplo 1). Esto nos permite crear un objeto con el cual podemos trabajar independientemente de lo que suceda con la llamada asíncrona.

## ¿Cómo se hace una promesa?

Para crear una promesa utilizamos la palabra reservada new seguido del constructor Promise, es decir, haremos una instancia de la clase Promise. La nueva instancia va a recibir dos parámetros: resolve y reject. Resolve se utiliza para cuando la promesa se resuelve de manera correcta y reject se utilizará en el caso de que no funcione (mirar ejemplo 2).

## Estados de las promesas

Aunque se dice que las promesas tienen tres estados, lo cierto es que solo pueden estar en dos, dichos estados son:

  ### Pending (Pendiente):
  Es el estado inicial, ni cumplida ni rechazada aún.
  
  ### Fulllfilled (Cumplida):
  Se ha cumplido con éxito.
  
  ### Rejected (Rechazada):
  
  Significa que la operación falló
  
 Una vez que la promesa pasó de pendiente a cumplida o rechazada NO PUEDE cambiar de estado (ver ejemplo 3).
 
 
 
 
