¿Te acordas cómo resaltar una porción de texto? Vimos la etiqueta `<strong>` que también es un _agrupador en línea_. Pero esto también es posible delegarlo en el CSS de la siguiente forma: `font-weight: bold;`

¿Y si lo que buscamos es enfatizar alguna palabra o frase? Tenemos la etiqueta `<em>`, también un _agrupador en línea_. Y así como ocurrió con `<strong>` también es posible delegarlo en el CSS de la siguiente forma: `font-style: italic;`

:warning: ¡Ojo! aunque podemos reemplazar las etiquetas `strong` y `em` por reglas de CSS porque producen el mismo efecto visual, el uso de estas etiquetas también dan un sentido semántico a nuestro texto y proporcionan algo más importante: *accesibilidad*. Los _[screen readers](https://es.wikipedia.org/wiki/Lector_de_pantalla)_ pueden distinguir y pronunciar distinto al detectar una etiqueta `strong` o `em`.

> Ejercicio: Agregar cursiva al elemento `h2` y negrita a la clase `importante`
