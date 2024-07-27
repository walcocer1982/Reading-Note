## ¿Cuál es el propósito de CSS?

El propósito de CSS (Cascading Style Sheets) es definir y aplicar estilos a un documento HTML, controlando la apariencia y el diseño visual de los elementos en una página web. CSS permite separar la presentación del contenido, facilitando el mantenimiento y la modificación del diseño sin alterar el HTML.

## ¿Cuáles son las tres formas de insertar CSS en tu proyecto?

**CSS en línea**: Se utiliza el atributo `style` directamente en los elementos HTML. Ejemplo:

```html
<p style="color: red;">Texto en rojo</p>
```

**CSS interno**: Se coloca dentro de una etiqueta `<style>` en la sección `<head>` del documento HTML. Ejemplo:

```html
<head>
  <style>
    p {
      color: red;
    }
  </style>
</head>
```

**CSS externo**: Se vincula un archivo CSS externo utilizando la etiqueta `<link>` en la sección `<head>` del documento HTML. Ejemplo:

```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```

## Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos `<p>`.

```css
p {
  color: red;
}
```
