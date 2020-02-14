
# Tipos de Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Tipos de UnderLine
Under line 1
--
Under line 2
==

# Formatos de énfasis
Formato de letras 1 forma
- *italica* 
- **bold o strong**
- ~~tachado~~

Ejemplo:
- Esto va a ser *italica*, despues usamos **bold** y texto ~~tachado~~

Formato de letras 2 forma
- _italica_
- __bold o strong__

 Ejemplo:
- Esto va a ser _italica_, despues usamos __bold__ 

# Tipos de Listas

## Ordenadas
1. Esto es un item (1)
2. Esto es un item (2)
3. Esto es un item (3)
4. Esto es un item (4)

## Desordenadas
- Esto es un item
- Esto es un item
- Esto es un item
- Esto es un item

# Links
- <a href="http://www.google.com">Esto es un Link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link a index](index.html)
- Link anchor: ir a [Tipos de Cabeceras](#tipos-de-cabeceras)


# Imagenes
![Imagen Flash](https://i1.pngguru.com/preview/243/350/572/orb-icons-pack-macromedia-flash-png-icon.jpg)

# Code Snippets
Utiliza highlight.js (https://highlightjs.org/static/demo/)

-Esto es codigo en JSON

````JSON
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
````

-Esto es codigo en JavaScript
````Javascript
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

````

# Tablas

| Nombre | Apellido | Documento |
| -----  | -----    | -----     |
| Sofia  | Rivera   | 12345     |
| Claudia| Avila    | 54321     |


# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita

Otro texto relacionado con una cita
> Esto es otra cita

# Linea Divisoras
Texto inical para dividir con guines medios

---
Segundo Texto inical para dividir con asteriscos

***

Tercer Texto inical para dividir con guiones bajos

___

# Saltos de línea ente parrafos
Este es el primer parrafo.

Este es el segundo parrafo.

Este es el tercer parrafo.

Este es el cuarto parrafo.



