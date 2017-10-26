# CSS

CSS es un lenguaje que describe el estilo de una página HTML.

CSS significa Hoja de estilos en cascada.

## Sintaxis

Consiste en un conjunto de reglas CSS que tiene un selector y un bloque de declaraciones:

```css
h1{
    color: red;
}

h1 -> selector

color -> propiedad
blue  -> valor

```

## Selectores

Los selectores se usan para "encontrar" un elemento por nombre, id, clase, atributo.

### Basado en el nombre
```css
p{
    color:red;
}
```
```html
<p>Ejemplo de usar selector para un parrafo</p>
```

### Basado en el id
```css
#pId{
    color:blue;
}
```
```html
<p id="pId">Ejemplo de usar selector basado en ID</p>
```

### Basado en una clase
```css
.pClass{
    color:gree;
}
```
```html
<p class="pClass">Ejemplo de usar selector basado en Class</p>
```

## Maneras de insertar CSS

Hay 3 maneras de insertar css:
1. Archivo externo

```html
<head>
    <link rel="stylesheet" type="text/css" href="estilos.css">
</head>
```

2. Dentro de la página
```html
<head>
    <style>
        body{
            background-color: blue;
        }
    </style>
</head>
```

3. En línea
```html
<h1 style="color:orange;">Encabezado</h1>
```

## Orden de cascada

1. Estilo en línea (dentro de un elemento HTML)
2. Hojas de estilo externas e internas (en la sección de la cabeza)
3. Navegador predeterminado

## Colores

Los colores se definen:
* RGB
* HEX
* HSL
* RGBA
* HSLA 
* nombres

__background-color__
```css
background-color: tomato;
```


