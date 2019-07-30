En una receta _siempre_ encontramos qué vamos a cocinar :spaghetti:, qué ingredientes vamos a necesitar :tomato: y qué pasos tenemos que seguir para hacerla. :page_facing_up:

Como la nuestra no va a ser un caso diferente, vamos a separarla en esas secciones.
Para hacerlo tenemos la etiqueta `<section>` que nos permite agrupar contenido muy relacionado entre sí, es decir, que tenga una misma **semántica**.

Para crear la sección de descripción podríamos hacer así:

``` html
<section>

</section>
```

Y para la sección de ingredientes, así: 

``` html
<section>

</section>
```

Hmmm un momento… :hand: ¿Cómo diferenciamos cuál es cuál? :scream:
Más allá del contenido, que va a darle el sentido a cada `<section>`, recordá que podemos identificar elementos mediante el atributo `id` de esta forma:

``` html
<section id="descripcion">

</section>

<section id="ingredientes">

</section>
```
> ¡Ahora te toca a vos! Copiá las secciones anteriores debajo del `<header>` y además agregá la sección “pasos”.
