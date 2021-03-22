# Versión de curso
Versión actual: v1.2.2

# Cabeceras
# Cabecera h1
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera H6

# Underlines
Underline 1 (h2)
-----------
Underline 2 (h1)
===========

# Formatos de énfasis
- Formato *itálica* de la primera forma
- Formato _itálica_ de la segunda forma
- Formato **bold** o __strong__
- Formato ~~tachado~~
- Aquí podemos usar *formato itálico*, pero también **bold** y ~~tachado~~

# Listas
1. Item 1
2. Item 1
3. Item 1

- Lista desordenada
- Lista desordenada
- Lista desordenada

# Links
- [Esto es un link md](http://www.google.com)
- [Esto es un link md al index](index.html)

# Imagenes
![logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code snippets
MD tiene su propia libreria para enfatizar el código: [libreria de markdown](https://highlightjs.org/static/demo/)

Código en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Código en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellidos | Documento
| ------ | --------- | ---------
| Marcos | Pérez | 52227533F
| Estefanía | Gómez | 30229937W

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita

Para terminar la cita se da doble enter
> Esto vuelve a ser otra cita

# Lineas divisorias
Esto es un texto que será dividido

---
Importante es un enter antes del código

***
Tercera forma de dividir

___

# Saltos de línea
Esto es el primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.