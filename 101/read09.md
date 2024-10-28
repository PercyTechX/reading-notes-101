# Introducción a JavaScript

1. ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

* Number, String, Boolean, Null, Undefined, Symbol, BigInt, y Object. 
Cada tipo representa datos diferentes. por ejemplo:

| Tipo de Dato |	Descripción	 | Ejemplo |
| --- | --- | --- |
| Number | Representa valores numéricos, incluidos enteros y decimales. |	let age = 25; |
| String	| Cadena de texto; utilizada para representar palabras y frases.	| let name = "Ana"; |
| Boolean	| Representa valores lógicos: true o false. |	let isActive = true; |
| Null	| Valor intencionalmente vacío o desconocido. |	let value = null; |
| Undefined	| Variable declarada sin valor asignado. |	let data; |
| Symbol	| Identificador único, útil en estructuras avanzadas.	| let id = Symbol(); |
| BigInt	| Para números enteros muy grandes.	| let bigNum = 123n; |
| Object	| Estructura compleja que almacena pares clave-valor.	| let user = {name: "Ana"} |


2. ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?
   
* Estructuras condicionales if y else permiten ejecutan condicionales, dependiendo de si una expresión es verdadera o falsa.

3. ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

* Aritméticos: para sumar, restar, multiplicar y dividir (por ejemplo, +, -, *, /).
  De asignación: para establecer valores en las variables (por ejemplo, =, +=).
  De comparación: para verificar si valores son iguales, mayores, menores, etc. (==, ===, !=, <, >).
  Lógicos: para combinar condiciones (como && para "y", || para "o").

4. ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?

* Declaración de variables:  var tiene un alcance de función, lo que significa que solo vive dentro de la función donde se declara.
  let y const tienen un alcance de bloque o sea existen solo dentro de las llaves { } donde se declaran.
  const es inmutable (su valor no se puede cambiar) mientras que let y var si permiten modificar su valor después de la declaración.
