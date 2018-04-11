Utilizamos reglas de CSS para seleccionar elementos de una página web y poder asignarle estilos a esos elementos.

La manera de decirle a nuestra regla de CSS a cuáles elementos de HTML se debe aplicar es mediante indicar el *selector*. Hay muchos tipos de selectores :hushed:, empecemos con el que ya usamos: *selector de elemento*.

El selector de elementos selecciona elementos de HTML de acuerdo a los nombres de las _etiquetas_. Cualquier elemento de HTML (`<h1>`, `<p>`, `<body>`) puede seleccionarse en CSS al usar el nombre de la etiqueta *sin* los `<` y `>`.

Por ejemplo, si quiero que el color del texto de todos los párrafos sean azules, puedo hacer:

```css
p {
  color: blue;
}
```

> ¡Ahora intentalo vos!
> Cambia el color del texto del encabezado `<h2>`, y el color de los textos de los párrafos `<p>` para que sean de color azul (blue).

