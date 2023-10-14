# Ajute de textos

- 1. Correct the line height in all browsers.
- 2. text-size-adjust: Esta propiedad estándar de CSS permite ajustar automáticamente el tamaño del texto cuando se realiza un zoom en la página. 
  - 2.1El valor 100% para -webkit-text-size-adjust indica que el tamaño del texto no debe ser ajustado automáticamente por el navegador cuando se realiza un zoom. Esto significa que el tamaño del texto se mantendrá igual, independientemente del nivel de zoom aplicado por el usuario.
- 3. font-size-adjust: Esta propiedad permite ajustar el tamaño de la fuente en función del tamaño de la fuente genérica predeterminada.

```css
html {
  line-height: 1.15; /* 1 */
  text-size-adjust: 100%; /* 2 */
  -webkit-text-size-adjust: 100%; /* 2 */
  font-size-adjust: 0.5; /* 3 */
}
```


- Es una propiedad CSS que permite que la altura de un elemento se ajuste automáticamente para adaptarse al contenido que contiene.

```css
.elemento {
  height: fit-content;
}
```



- Esta propiedad controla el color del resaltado que aparece cuando se toca un elemento en dispositivos táctiles.

```css
/* Selecciona todos los elementos clicleables */
a, button, input[type="submit"], input[type="button"], input[type="reset"], [role="button"] {
  -webkit-tap-highlight-color: transparent; /* Establece el resaltado en transparente */
  tap-highlight-color: transparent;
}
```


- Altura de textarea segun su contenido

``` css
textarea{
  resize: none;
  min-heigth: 36px;
  width:250px;

  form-sizing: content;
}
```