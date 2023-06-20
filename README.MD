# Cabeceras

# Cabecera H1

## Cabecera H2

### Cabecera H3

#### Cabecera H4

##### Cabecera H5

###### Cabecera H6

## Undeline1

# Underline2

# Formatos de emphasis

- letra _italica_ de la primer forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong**. de la primer firma
- formato **bold o strong**. de la segunda firma
- formato ~~tachado~~, formato normal.
- aqui podemos usar _formato italico_, pero tambien **bolg** y ~~tachado~~.

# Listas

1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es in iten de lista desordenadas.
- Esto es in iten de lista desordenadas.
- Esto es in iten de lista desordenadas.

# Links

- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes

![Logo Github](https://cdn.iconscout.com/icon/free/png-256/free-git-17-1175218.png?f=webp&w=128)

# Code Snippets

Codigo en JSON

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

Codigo en Javascript

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

| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi   | Burgos   | 123432245 |
| Tomas  | Tomsoon  | 54456789  |

# Citas

Esto es un texto referente a una cita que crearemos debajo:

> Esto es una cita.

Esto es otro texto no se relaciona con la cita anterior

> Esto es otra cita.

# Lineas Divisoras

Esto es un texto que sera dividido por guines medios

---

Esto es otro texto dividido por asteriscos

---

Estos es otro texto dividido por guines bajos

---

# Saltos de lineas

Estos es nuestro primer parrafo.

Estos es nuestro segundo parrafo.

Estos es nuestro tercer parrafo.

- lista
