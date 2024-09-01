# CSS: Layout

## Learn CSS - Flexbox

1. **Flexbox** es crucial para desarrollar layouts responsivos y accesibles, permitiendo un diseño eficiente en una dimensión, ideal para componentes de interfaz de usuario como barras de navegación y galerías de imágenes.

**Ejemplo de Flexbox en una fila:**

```css
.container {
  display: flex;
  flex-direction: row; /* Alinea horizontalmente */
}
```

2. **Main Axis vs. Cross Axis**

- *Main Axis*: Dirección principal de alineación (horizontal por defecto).
- *Cross Axis*: Perpendicular al main axis (vertical por defecto).

```css
.container {
  display: flex;
  justify-content: center; /* Alineación en el main axis */
  align-items: center; /* Alineación en el cross axis */
}
```

3. *Utilizar Flexbox* puede afectar la accesibilidad de las siguientes maneras:

- Orden Visual vs. Orden de Tabulación: Flexbox permite reordenar elementos visualmente sin cambiar su orden en el código, lo que puede confundir a los usuarios que dependen de la navegación secuencial, como aquellos que usan lectores de pantalla.

- Dimensionamiento Rígido: Si no se usan unidades flexibles, como porcentajes o ems, el contenido puede desbordarse o volverse inaccesible al cambiar el tamaño de texto o al visualizar en dispositivos con diferentes dimensiones de pantalla.

## SS Layout - Flexbox

1. Ventajas de Flexbox sobre Float

- Flexbox permite un control más preciso y flexible sobre el espacio y la alineación de los elementos.
- Reduce el uso de hacks y mejora la semántica del código.

2. Dominar Flexbox mejora directamente la calidad del diseño web, contribuyendo a una mejor experiencia de usuario y aumentando la empleabilidad en el desarrollo front-end.

## Cosas de las que quiero saber más

- Aprende sobre diferentes formas de visualizar información, como infografías, dashboards y visualizaciones interactivas, que pueden ayudarte a comprender y presentar mejor los datos y conceptos.
