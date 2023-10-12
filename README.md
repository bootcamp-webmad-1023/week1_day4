# week1_day4


## Contenidos

> JS | Data types: strings, numbers, boolens, arrays, objects
>
> JS | Conditionals & loops
>
> JS | Functions

 
## Main points: truthies VS falsies

Los valores _falsies_ (`null, undefined, false, NaN, 0, ''`) son rechazados por defecto en las estructuras condicionales. Todos los demás (_truthys_) son aceptados por defecto.


## Main points: functions
  
A nivel de estructura, existen: 
- **Function statement**: disponen de al palabra reservada `function`, de paréntesis para sus parámetros y de bloque:
  ````javascript
  function getTotals(subtotal, tax){
    return subtotal + tax
  }
  ````
- **Arrow function**: carecen de la palabra reservada `function`, el paréntesis en sus parámetros es omitible frente a un único parámetro, y disponen una flecha previo a la apertura de su bloque (bloque omitible en funciones de una única instrucción).
  ````javascript
  const getTotals = (subtotal, tax) => subtotal + tax
  ````
Las funciones pueden recibir argumentos en forma de parámetros, y retornar datos. A efectos del retorno:
- Sólo pueden retornar un único valor, o `undefined` si carecen de retorno.
- Un retorno en una función supone detener su ejecución.
- Las _arrow function_ carentes de bloque disponen de retorno por defecto.
