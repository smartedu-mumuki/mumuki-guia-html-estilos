¿Cómo hago para aplicar la misma regla a un grupo de elementos? <br>
¡Ya sé! Le pongo un _id_ a cada elemento, y luego copio y pego la misma regla una y otra vez para cada id. :rage: <br>
¡NO!, <u>por favor, no</u>.
Por suerte en HTML existe un atributo que tienen todos elementos llamado `class`, mediante el cual, dos o más elementos pueden compartir una *misma* clase y así aplicarse las mismas reglas.

Modificamos en el HTML:

```html
<p class='texto-azul'>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
</p>
```
Y en nuestra sección de estilos, para referenciar a una clase usamos el `.` (punto).

```html
<style>
.texto-azul {
  color: blue;
}
</style>
```

> Modifica el código existente de forma tal que los elementos que tienen la clase `texto-rojo`, tengan color rojo de texto.