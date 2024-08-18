# LECTURA Y NOTAS
## Lectura
### Listas Ordenadas y No Ordenadas en HTML

1. **¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?**
   - Se utiliza cuando el orden de los elementos en la lista no es importante, como en una lista de ingredientes para una receta.

2. **¿Cómo cambias el estilo de bullet de la lista de elementos no ordenados?**
   - Cambias el estilo de los bullets usando la propiedad CSS `list-style-type` en el selector `ul`.

3. **¿Cuándo debes usar una lista ordenada o una lista no ordenada en tu documento HTML?**
   - Usa una lista ordenada (`<ol>`) cuando el orden de los elementos es importante, como en los pasos de una receta. Usa una lista no ordenada (`<ul>`) para listas donde el orden no importa.

4. **Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada.**
   - Cambia el estilo de numeración usando `list-style-type` (ejemplo: `decimal`, `lower-alpha`, `upper-roman`) y comienza desde un número específico usando el atributo `start` en `<ol>`.

### The Box Model - CSS

1. **Describe las propiedades de `margin` y `padding` en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: "El Box Model"?**
   - `Margin` es el espacio personal alrededor de una persona, y `Padding` es como la ropa, proporcionando espacio entre el contenido (la piel) y su ropa (el borde).

2. **Enumera y describe las cuatro partes de un box del elementos HTML según el box model.**
   - **Contenido (Content):** El área donde reside el texto o imágenes.
   - **Relleno (Padding):** Espacio entre el contenido y el borde.
   - **Borde (Border):** Línea que rodea el padding y el contenido.
   - **Margen (Margin):** Espacio fuera del borde.

### Arrays, Operadores y Expresiones - JS

1. **¿Qué tipos de datos puedes almacenar en un Array?**
   - Puedes almacenar números, cadenas de texto, objetos, funciones, y otros Arrays.

2. **¿El array `people` es un array de JavaScript válido?**
   - Sí, es válido. Accedes a los valores usando índices, como `people[0]`. Sin embargo, la entrada `'fishing.hiking'` debería ser dos entradas separadas si son distintas actividades.

3. **Enumera cinco operadores abreviados de asignación en javascript y describe lo que hacen.**
   - `+=` suma y asigna.
   - `-=` resta y asigna.
   - `*=` multiplica y asigna.
   - `/=` divide y asigna.
   - `%=` asigna el módulo.

4. **Evalúa la siguiente expresión en JavaScript y explica el resultado.**
   ```javascript
   let a = 10;
   let b = 'dog';
   let c = false;
   (a + c) + b;  // Resultado: '10dog'
   false se convierte en 0, sumando 10 + 0 que resulta en 10, luego se concatena con 'dog', resultando en '10dog'.

5. **Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.**
   Verificar la edad en un formulario de registro y proporcionar acceso a contenido basado en la edad del usuario.
6. **Da un ejemplo de por qué bucle es útil en JavaScript.**
   Para sumar todos los elementos en un array sin tener que repetir manualmente las instrucciones para cada elemento.

## NOTAS
### Importancia del Tema
Este tema es crucial ya que proporciona la base fundamental para el desarrollo y diseño web. En este módulo, estamos explorando cómo construir y estilizar páginas web de manera efectiva, lo cual es esencial para cualquier desarrollador web o diseñador. HTML define la estructura, CSS maneja la presentación y el diseño, y JavaScript agrega interactividad, lo cual, combinado, permite crear experiencias web ricas y dinámicas.
### HTML
- **Listas ordenadas y no ordenadas:** Utilizamos listas ordenadas cuando el orden de los elementos importa, como en recetas o instrucciones. Las listas no ordenadas son útiles para listados donde el orden no es relevante, como características de un producto.
- **Estilos de listas:** Cambiamos los estilos de bullet o numeración usando CSS para mejorar la comprensión visual del contenido.
### CSS
- **El modelo de caja:** El modelo de caja en CSS incluye margen, borde, relleno y contenido. Estos componentes trabajan juntos para formar la estructura de cada elemento en una página web.
- **Margin y Padding:** Son esenciales para dar espacio y estructura visual al contenido, permitiendo que el diseño sea más legible y estéticamente agradable.
### JavaScript
- **Arrays y Tipos de Datos:** Los arrays en JavaScript pueden contener múltiples tipos de datos y son esenciales para manejar colecciones de datos.
- **Operadores de Asignación:** Facilitan la modificación de valores de una manera concisa y legible.
### Analogía
Imagina que estás construyendo una casa:
- **HTML** es el plano que define la estructura y la disposición de la casa.
- **CSS** es la decoración y el estilo de la casa que afecta cómo se ve y se siente.
- **JavaScript** es el sistema eléctrico que añade funcionalidad, como luces que se encienden al pulsar un interruptor.
## Cosas de las que quiero saber más
Mis intereses se centran en explorar cómo las tecnologías web tradicionalmente asociadas con el desarrollo de interfaces, como CSS y JavaScript, pueden aplicarse dentro de entornos de desarrollo de juegos como Unity. Aquí están las áreas específicas que deseo profundizar:
### CSS en Unity
**Estilización de Letreros y Mensajes:** Aunque Unity no utiliza directamente CSS para estilos, me interesa aprender cómo los principios de CSS pueden aplicarse para controlar la estética de textos y paneles dentro de Unity. ¿Existen herramientas o métodos dentro de Unity que permitan una manipulación del estilo similar a lo que ofrece CSS en el desarrollo web? Busco comprender mejor cómo puedo trasladar mi conocimiento de CSS para mejorar la interfaz de usuario en los juegos.
### JavaScript en Unity
**Generación de Bucles:** Unity script utiliza principalmente C#, pero mi interés radica en entender cómo los conceptos de programación en JavaScript, especialmente la creación de bucles y operaciones repetitivas, pueden ser implementados en Unity. ¿Cómo se comparan los bucles en JavaScript con las estructuras de control en C#, y qué herramientas ofrece Unity para facilitar operaciones repetitivas que podrían necesitar una lógica de bucle?
   
