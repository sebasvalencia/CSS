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




