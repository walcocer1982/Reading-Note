# Conceptos Básicos de HTML, CSS y JavaScript

## HTML

### ¿Por qué es importante utilizar elementos semánticos en nuestro HTML?
Los elementos semánticos mejoran la accesibilidad, facilitan que los motores de búsqueda comprendan mejor el contenido de la página y ayudan a los desarrolladores a mantener y administrar el código de manera más eficiente.

### ¿Cuántos niveles de encabezado existen en HTML?
Hay seis niveles de encabezado en HTML, desde `<h1>` hasta `<h6>`.

### ¿Cuáles son algunos de los usos para los elementos `<sup>` y `<sub>`?
`<sup>` se utiliza para texto en superíndice, como en las expresiones matemáticas para exponentes. `<sub>` se utiliza para texto en subíndice, como en las fórmulas químicas.

### Al utilizar el elemento `<abbr>`, ¿qué atributo se debe añadir para proporcionar una ampliación del término?
Se debe añadir el atributo `title` para proporcionar la descripción completa del término abreviado.

## CSS

### ¿De qué formas podemos añadir CSS a nuestro HTML?
Podemos añadir CSS mediante tres métodos:
- **Inline**: directamente en los elementos HTML usando el atributo `style`.
- **Interno**: dentro de un bloque `<style>` en el `<head>` del documento.
- **Externo**: enlazando un archivo CSS con el elemento `<link>`.

### ¿Por qué deberíamos evitar utilizar estilos inline?
Se deben evitar los estilos inline porque dificultan la reutilización de los estilos, hacen más difícil mantener y gestionar el código, y rompen la separación entre contenido y presentación.

### Revisa el código a continuación: ¿Qué representa el selector? ¿Qué componentes son declaraciones CSS? ¿Qué componentes se consideran propiedades?
- **Selector**: `h2` representa todos los elementos `<h2>` en el documento.
- **Declaraciones CSS**: `color: black;` y `padding: 5px;` son declaraciones.
- **Propiedades**: `color` y `padding` son propiedades.

## JavaScript

### ¿Qué tipo de dato es una secuencia de texto entre comillas simples?
Una secuencia de texto entre comillas simples es un dato de tipo `string`.

### Enumera 4 tipos de operadores en JavaScript.
- **Operadores aritméticos** (por ejemplo, `+`, `-`, `*`, `/`)
- **Operadores de comparación** (por ejemplo, `==`, `!=`, `<`, `>`)
- **Operadores lógicos** (por ejemplo, `&&`, `||`)
- **Operadores de asignación** (por ejemplo, `=`, `+=`, `*=`)

### Describe un problema práctico que puedes resolver con una función.
Una función puede ser usada para calcular el área de un círculo dado su radio, lo que simplifica la repetición del cálculo en diferentes partes del programa sin necesidad de escribir el código de cálculo cada vez.

### Si una declaración `if` comprueba una condición y si resulta verdadera, entonces el código se ejecutará. ¿Cuál es el uso del `else if`?
`Else if` se usa para proporcionar una condición adicional que se verifica si la condición inicial del `if` no es verdadera.

### Enumera 3 tipos de operadores de comparación.
- `==` (igual a)
- `>` (mayor que)
- `<=` (menor o igual que)

### ¿Cuál es la diferencia entre los operadores lógicos `&&` y `||`?
`&&` opera como un "Y" lógico que solo devuelve `true` si todas las condiciones son verdaderas, mientras que `||` opera como un "O" lógico que devuelve `true` si al menos una de las condiciones es verdadera.
## Analogía
**Chequeos de seguridad en maquinaria minera**
- En la industria minera, los chequeos de seguridad en maquinaria son cruciales para asegurar su funcionamiento y la seguridad operativa, similar a las validaciones de datos en la programación con JavaScript. En la minería, cada máquina podría tener un sistema que registra cada revisión de seguridad exitosa, parecido a un log en programación que monitorea la validación de datos. Si se detectan problemas durante estos chequeos, se generan alertas, que son comparables a los mensajes de error en programación, advirtiendo sobre fallas que deben corregirse antes de proceder. Esta analogía subraya la importancia de la prevención y la detección temprana tanto en la operación de maquinaria pesada como en el desarrollo de software.
## Cosas de las que quiero saber más
- **¿Cómo optimizar el rendimiento de aplicaciones de realidad aumentada en dispositivos móviles?**
- **¿Cómo se gestionan grandes volúmenes de datos de sensores en la industria minera usando programación?**
- **¿Cómo crear una mejor interfaz de usuario (UI) para simulaciones de maquinaria minera utilizando Unity y CSS?**
