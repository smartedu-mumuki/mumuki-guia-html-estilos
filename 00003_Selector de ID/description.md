Probablemente hayas notado en el ejercicio anterior que al aplicar la regla de `p` afectamos a todos los párrafos, a los 2. Pero ¿qué pasa si quisiera que la regla sólo aplique a uno de ellos? Una manera de hacerlo es seleccionando por _id_.

El id es un _atributo_ de cualquier elemento HTML y sirve para identificar de manera única a un elemento. 

Al tratarse de un atributo de un elemento HTML, debemos primero modificar el HTML, para luego poder usarlo de selector desde una regla CSS.

Entonces, supongamos que nos interesa que la regla que escribimos antes, solo aplique al segundo párrafo. Veamos como queda:

```html
<h2>Lorem Ipsum</h2>
<p>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit... 
</p>
<p id='segundo_parrafo'>
  Donec aliquet pharetra ex vitae mollis…
</p>
```

Ya con el id establecido, ¡ahora podremos seleccionarlo!
Para ello, nuestro selector deberá usar de prefijo `#` (hashtag). De esta manera:

```html
<style>
  #segundo_parrafo {
     color: green;
  }
</style>
```

> Veamos si se entiende: cambiale el `color` a verde (green) al primer párrafo.