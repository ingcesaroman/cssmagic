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
 
 ## Formatos (Fonts)
 * Random text [Text Generators for Web Designers](https://theultralinx.com/2013/08/10-hilarious-lorem-ipsum-generators-web-designers/)
 * Default Font Styles [CSS Fonts](https://www.cssfontstack.com/)
 * font-family\
 `selector {font-family: Arial}` 
 * font-siza px or em(dinamico en % con base elemento padre entre 0.1 - 5.0em)
 `selector {font-size: 10px or 2.0em;}`
 * font-weight (grosor de letras)
`selector {font-weight: 100 or bold/normal}`
 * font-height (estacio entre lineas)
`selector {line-height: 1.5}`
 * text-align (alineacion de texto)
`selctor {text-align: right}`
 * text-decoration (subrayado o tachado)
`selector {text-decoration: underline}`

## Google fonts
* font de google [font](https://fonts.google.com/)\
solo agrega
`<link href="url" rel="style"`

## Box model
* Content - Width / Height
`selector {width: 50%;}`\
`selector {height: 100px;}`
* Border
`selector {border: 2px solid blue }`
* Padding (espacio de elemento al borde)\
sub propiedades Padding-top, padding-right
`selector {padding: 10px;}`
* Margin (espacio entre el borde y afuera)\
sub propiedades para las 4 lados magin:\
 T(top) R(right) B(Button) L(Left)
`selector {margin: 50px 10px 40px 30px;}`