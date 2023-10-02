# <center> TÍTULOS </center>

```MD
# Titulo

## Titulos 2

### Titulos 3

#### Titulos 4

##### Titulos 5

###### Titulos 6
```

# <center> Título Centrado </center>

```MD
<center> x </center>
```

# Bloque de texto

    Esto es un texto en un bloque de texto

```MD
    usar Identación para activarlo
```


# Colorear Texto
### <span style="color:red">Este texto está en rojo.</span>

```MD
<span style="color:red">Este texto está en rojo.</span>
```



# Espacios
### para crear espacios verticales con un grosor especifico

```MD
<div style="margin-top: 50px;"></div>
```

<div style="margin-top: 50px;"></div>


# Estilo de texto

hola mundo - *hola mundo*

```MD
*x*
```

hola mundo - **Hola mundo** - __Hola mundo__

```MD
**x** - __x__
```

Hola mundo - ***Hola mundo*** - ___Hola mundo___

```MD
***x*** - ___x___
```

hola mundo - ~~Hola Mundo~~

```MD
- ~~x~~
```


# <center> LISTAS </center>
Para crear listas desordenadas:
* apple
* banana
* pineapple

<!-- Para crear listas ordenadas = 1.  -->
1. libro
2. cuaderno
3. lapiz

<!-- lista en lista -->
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item



# <center> QUOTES </center>

> # Esto es un Quote

> # Quotes con título

> # <span style="color:red">Título coloreado en quote.</span>

> # Quotes With list
    > -  a
    > -  b


> # Blockquote in sorted list 

 1. > Parte 1
 2. > Parte 2
 3. > Parte 3


> # Blockquote
>> # In Blockoquote


# Resaltar Texto

``Use `code` in your Markdown file.`

`Use `code` in your Markdown file.`

# <center> LINEAS </center>
### Linea Horizontal
***
---
------------
###  Colorear Linea
<div style="background-color: yellow; height: 1px;"></div>

<div style="margin-top: 50px;"></div>

# <center> LINKS </center>
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

<!-- LINKS With Tooltip>  -->
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy")


<!-- LINKS With Tooltip>  -->
<https://www.markdownguide.org>
<fake@example.com>

<!-- URL LINK >  -->
<https://www.markdownguide.org>
<fake@example.com>

<!-- Agregar simbolos >  -->
\! vale 
\# cosa


# Bloque de Codigo
se usan comillas graves ``` para crear bloques de codigo.

<!-- Escribir Ecuaciónes >  -->
```python
print("a")
```

# Escribir Ecuaciónes
$y=x^2$

$e^{i\pi} + 1 = 0$

$e^x=\sum_{i=0}^\infty \frac{1}{i!}x^i$

$\frac{n!}{k!(n-k)!} = {n \choose k}$

## Matrices
$A_{m,n} =
 \begin{pmatrix}
  a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
  a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
  \vdots  & \vdots  & \ddots & \vdots  \\
  a_{m,1} & a_{m,2} & \cdots & a_{m,n}
 \end{pmatrix}$

# Dibujar Tablas
First column name  | Second column name 
-------------------|------------------
Row 1, Col 1       | Row 1, Col 2 
Row 2, Col 1       | Row 2, Col 2 


# Tabla de Contenidos
Para crear una tabla de contenidos en Markdown, puedes utilizar los encabezados del documento para generar enlaces a las secciones relevantes.

- [Sección 1](#sección-1)
  - [Subsección 1.1](#subsección-11)
  - [Subsección 1.2](#subsección-12)
    - [Subsección 1.2.1](#subsección-121)
    - [Subsección 1.2.2](#subsección-122)
- [Sección 2](#sección-2)
  - [Subsección 2.1](#subsección-21)
  - [Subsección 2.2](#subsección-22)

Asegúrate de que los nombres de tus secciones y subsecciones en los enlaces de anclaje sean idénticos a los encabezados en tu documento, pero en minúsculas y con guiones en lugar de espacios.

Ejemplo
```MD
# Sección 1
## Subsección 1.1

- [Sección 1](#sección-1)
  - [Subsección 1.1](#subsección-11)
```
