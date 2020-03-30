# Magia de los formatos CCS
* Using <__link__> tag\
justo despues del tag del titulo <_title_> \
`<link rel="stalesheet" type="text/css" href="app.css">` 
    
 ## Colores en CSS
 * consultar colours.neilorangepeel.com\
 se pueden escribir alradedor 140 colores\
 * formato Hexadecimal\
 negro -> #000000;\
 rojo -> #FF0000;\ 
       R00 G00 B00 \
 R -> Red (cuanto rojo queremos de 00 a FF)\
 G -> Green (cuanto verde queremos de 00 a FF)\
 B -> Blue (cuanto azul queremos de 00 a FF)    
 * Formato RGB\
 Con 3 canles para cada color en el rango de 0 a 255\
 * Formato con transparencia RGBA\
 con 4 canales, siendo los 3 primeros para RGB\
 y el cuarto para la tranparencia 
 
 ## Backgound tag
 * backgrounf: rgb(0,0,0)
 * Imagen `backgound: url(www.image.com)`\
 con diferentes propiedades como: \
 background-repeat: no-repeat; \
 background-size: cover;
 
 ## Bordes de colores (solo funcionan juntos)
 * border-color: red;
 * border-witdth: 1px;
 * border-style: solid;
 * unidos:\
 border: 1px solid red;
 
 ## Selectores CCS 
 * Ariculos de Selectores:\
  [specificity](https://specificity.keegan.st/)\
  [30 CSS Selectors](https://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)
 * Elements (se refirer a todos los tags div,p,)\
 `p { \ }`
 * ID (id="special" __html__ -> #special __css__)\
 `#name { \ }`
 * Tags (class="special" __html__ -> .special __css__)\
 `.special { \ }`
 * Start\
 `* { \ }`
 * Descendent\
 `li a { \ }`
 * Acendent\
 `h2 + ul { \ }`
 * Attribute\
 `input[type=radio]:checked { \ }`
 * nth-of-type\
 `ul:nth-of-type(3) { \ }`
 * inheritas