# Grid layout Desktop a mobile con Flexbox

Por qué Flexbox? Por el soporte de IE

## Breakpoints

* md: 1280px,
* sm: 1024px,
* xs: 768px

Para uso de @media:
~~~
 @include screen(md) { 
   // => @media screen and (max-width: 1280px) { ... }
 }
 @include screen(sm) {
   // => @media screen and (max-width: 1024px) { ... }
 }
 @include screen(xs) { 
   // => @media screen and (max-width: 768px) { ... }
 }
~~~

## Layout

Para el uso definir `grid` como contenedor, tener en cuenta `# de columns = 12`

Y para dividir en columnas considerar :

| desktop  | laptop ( < 1280px) | tablet ( < 1024px) | mobile (768px) | 
| :------- | :------            | :------            | :-----         |
| .col-    | .col-md-           | .col-sm-           | .col-xl-       |
