
### ¿Qué es una “expresión” en JavaScript?
Una “expresión” en JavaScript es cualquier fragmento de código que produce un valor. Una expresión puede ser un valor literal, como un número o una cadena, una variable o una operación matemática, entre otras. 

**Ejemplos:**
```javascript
3 + 4       // 7 (expresión aritmética)
"hello"     // "hello" (expresión de cadena)
x           // el valor de la variable x (expresión de variable)
myFunction() // el valor devuelto por la función myFunction (expresión de función)
```

### ¿Por qué usaríamos un bucle en nuestro código?
Usaríamos un bucle en nuestro código para repetir una serie de instrucciones múltiples veces de manera eficiente. Los bucles permiten ejecutar el mismo bloque de código varias veces con diferentes valores, lo que es útil para iterar sobre estructuras de datos o realizar operaciones repetitivas.

**Ejemplo:**
```javascript
for (let i = 0; i < 5; i++) {
  console.log("Iteración número " + i);
}
// Esto imprimirá "Iteración número 0" hasta "Iteración número 4"
```

### ¿Cuándo deja de ejecutarse un bucle for?
Un bucle `for` deja de ejecutarse cuando la condición especificada en la declaración del bucle evalúa a `false`. La estructura de un bucle `for` incluye una inicialización, una condición y una expresión de actualización. El bucle se ejecuta mientras la condición sea `true`. Cuando la condición se vuelve `false`, el bucle termina.

**Ejemplo:**
```javascript
for (let i = 0; i < 3; i++) {
  console.log(i);
}
// Esto imprimirá 0, 1 y 2. Deja de ejecutarse cuando i es igual a 3.
```

### ¿Cuántas veces se ejecutará un bucle “while”?
Un bucle `while` se ejecutará tantas veces como la condición especificada en la declaración del bucle evalúe a `true`. Antes de cada iteración, se evalúa la condición. Si la condición es `true`, el bloque de código dentro del bucle se ejecuta. Si la condición es `false`, el bucle termina. En otras palabras, el bucle `while` se ejecutará hasta que la condición se vuelva `false`.

**Ejemplo:**
```javascript
let count = 0;
while (count < 3) {
  console.log(count);
  count++;
}
// Esto imprimirá 0, 1 y 2. Deja de ejecutarse cuando count es igual a 3.
```
