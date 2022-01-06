Puedes usar el bloque `unir`{:class="block3operators"} del Menú de bloques `Operadores`{:class="block3operators"} para unir texto y variables para hacer cadenas más largas.

Arrastra un bloque `unir`{:class="block3operators"} hacia el bloque donde quieras usarlo:

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

Reemplaza el texto con el texto que quieras usar o arrastra una variable:

```blocks3
set [name v] to [Scratch]
say (join [Hi, I'm ] (name)) for [2] seconds
```

**Sugerencia:** El bloque `unir`{:class="block3operators"} no agrega espacios, por lo que tendrás que escribirlos.

Puedes arrastrar un bloque `unir`{:class="block3operators"} dentro de otro bloque `unir`{:class="block3operators"} para crear cadenas de texto más largas:

```blocks3
say (join [Hi, I'm ] (join (name) [ the cat])) for [2] seconds
```

Fíjate en el 'espacio' al final de `Hola, soy` y al comienzo de `el gato`.



