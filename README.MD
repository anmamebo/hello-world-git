# Version del curso
Version Actual: v1.2.2

# Cabeceras
# CABECERA H1
## CABECERA H2
### CABECERA H3
#### CABECERA H4
##### CABECERA H5
###### CABECERA H6

# Underlines
Underline 1
------------

Underline 2
============

# Formatos de enfasis
- formato *italica* de la primera forma
- formato _italica_ de la segunda forma
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://www.google.es">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://ww.google.es)

# Imagenes
![Logo Github](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

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
            console.log('undefined')
    }

    return (
        <div>
            <web-component>{block}</web-component>
        </div>
    )
}

export $initHighlight
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi   | Burgos   | 352322    |
| Tomas  | Tompson  | 452122    |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita

Esto es otro texto referente a una cita que pondremos debajo:
> Esto es otra cita

# Lineas Divisorias
Esto es un texo dividido por guiones

---
Esto es otro texto dividido por asteriscos

***

Esto es otro texto dividido por guiones bajos

___
