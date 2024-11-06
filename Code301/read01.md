### ¿Qué es un componente?

Un componente es como una pieza independiente de software que tiene una función específica. Está diseñado para funcionar con otras piezas, pero sin mostrar cómo trabaja internamente. Imaginemos como si fuese un bloque de Lego: cada pieza tiene un propósito y se conecta con otras sin importar cómo están hechas por dentro, siempre y cuando encajen. Un componente se puede usar varias veces, mover de un lugar a otro y hasta cambiarlo por 
otro similar sin problemas.
### ¿Cuáles son las características de un componente?

1. **Reutilizable**: Se puede usar en diferentes programas y situaciones.
2. **Reemplazable**: Se puede cambiar por otro similar sin afectar el funcionamiento.
3. **Versátil**: Funciona en diferentes entornos y contextos.
4. **Extensible**: Se puede mejorar o ampliar con nuevas funciones.
5. **Encapsulado**: Solo muestra lo que necesitamos ver, ocultando detalles internos.
6. **Independiente**: Funciona por sí mismo, sin depender mucho de otras piezas.

### ¿Cuáles son las ventajas de usar una arquitectura basada en componentes?

1. **Fácil de actualizar**: Se pueden cambiar componentes sin afectar el resto del sistema.
2. **Reduce costos**: Usar componentes ya hechos permite ahorrar en desarrollo y mantenimiento.
3. **Facilita el desarrollo**: Como cada componente tiene su propia función definida, los desarrolladores pueden trabajar en distintas partes sin afectar el resto.
4. **Reutilizable**: Se pueden aprovechar los mismos componentes en varios proyectos, lo que ahorra tiempo y dinero.
5. **Simplifica la complejidad**: La estructura de componentes permite organizar mejor el sistema.
6. **Aumenta la confiabilidad**: Si cada componente funciona bien, el sistema en su conjunto será más confiable.
7. **Fácil de mantener**: Actualizar el sistema o realizar cambios es más fácil sin impactar el resto.
8. **Independencia**: Cada equipo puede trabajar en diferentes componentes al mismo tiempo, lo que hace el desarrollo más rápido y flexible.


### ¿Qué significa “props”?

En React, **"props"** es la abreviatura de "properties" o propiedades. Son una forma de pasar datos o información de un componente "padre" a un componente "hijo". Esto permite que los componentes tengan datos personalizados y puedan mostrar resultados dinámicos y únicos.

### ¿Cómo se utilizan los props en React?

Para usar props, se envían como si fueran atributos en HTML. En el componente "padre", defines los props y sus valores cuando llamas al componente "hijo". Luego, el componente "hijo" recibe esos valores y puede usarlos en su interior.

Ejemplo de cómo se envían props:

```jsx
<Product
  img="https://example.com/product.jpg"
  name="Sneakers"
  desc="Comfortable running sneakers"
  price="$29"
/>
```

### ¿Cuál es el flujo de los props?
El flujo de los props en React es unidireccional, lo que significa que la información va solo en una dirección: del componente "padre" al componente "hijo". El componente "hijo" no puede cambiar los valores de los props que recibe, solo los usa para mostrar o realizar acciones. Esto ayuda a mantener el código organizado y evita que los datos se modifiquen accidentalmente en múltiples lugares.

```jsx
function Product(props) {
    return (
      <div>
        <img src={props.img} alt="product" />
        <h4>{props.name}</h4>
        <p>{props.desc}</p>
        <h4>{props.price}</h4>
      </div>
    );
}
```
Desestructuración de Props
Para hacer el código más claro y evitar repetir props, se puede usar desestructuración en JavaScript. Esto permite extraer las propiedades directamente en variables, haciéndolo más limpio y fácil de leer.

Por ejemplo, en lugar de escribir props.img o props.name, puedes desestructurarlos así:


Aquí tienes la continuación:

markdown
Copiar código
Para que el componente "hijo" use los props, simplemente los recibe como un parámetro en la función del componente. Luego, dentro del componente, puedes usar esos valores para personalizar lo que se muestra o hace.

Ejemplo de cómo se acceden los props en el componente "hijo":

```jsx
function Product(props) {
    return (
      <div>
        <img src={props.img} alt="product" />
        <h4>{props.name}</h4>
        <p>{props.desc}</p>
        <h4>{props.price}</h4>
      </div>
    );
}
Desestructuración de Props
Para hacer el código más claro y evitar repetir props, se puede usar desestructuración en JavaScript. Esto permite extraer las propiedades directamente en variables, haciéndolo más limpio y fácil de leer.

Por ejemplo, en lugar de escribir props.img o props.name, puedes desestructurarlos así:
```
jsx
Copiar código
function Product({ img, name, desc, price }) {
    return (
      <div>
        <img src={img} alt="product" />
        <h4>{name}</h4>
        <p>{desc}</p>
        <h4>{price}</h4>
      </div>
    );
}
```
