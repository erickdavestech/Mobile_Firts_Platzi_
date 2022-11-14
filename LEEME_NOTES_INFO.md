# Mobile_Firts_Maquetacion

## Parte 1: --> Analizando la arquitectura del proyecto

--Arquitectura del Proyecto Mobile Firts
Cuatros secciones,

- Header
- Main
  -- 4 sections- dentro de main
- Footer

## Parte 2: -->

Analizando las imagenes y assets and icons
Main pitures and icons
--assets
--icons
--
--images
--

Section two:
--bitcoin_image_section_2
--Vector_section_2_databit_image
--Vector_section_2_flecha_abajo_naranja
--Vector_section_2_flecha_arriba_verde
--Vector_section_3_icon_check_circle
--Vector_section_3_icon_Dollar_Sign
--Vector_section_3_icon_OJO
--Vector_section_3_icon_reloj

## Parte 3: --> Añadiendo las fuentes del proyecto

-Google Fonts
--Fuente
Dm Sans
700
500
--Fuente
Inter
500 Para el nombre de la moneda section 2
400 para el monto o costo section 2
700

## Parte 4: Agregando los colores al root:{}

--> /_Variables de color_/
--bitcoin-orange: #f7931a;
--soft-orange: #ffe9d4;
--secondary-blue: #1a9af7;
--soft-blue: #e7f5ff;
--warn-black: #201e1c;
--warn-black-secondary: #282623;
--grey: #bababa;
--off-white: #faf8f7;
--just-white: #ffffff;

## parte 5: --> HTML Y CSS RULES

ajustando el la etiqueta html,
para usar rem en ves de pixeles + Agregar la fuente

html {
font-size: 62.5%;
/_Reglas de estilos CSS de google fonts _/
font-family: "DM Sans", sans-serif;
/_en la seccion 3 llevara la fuente Inter_/
/_font-family: "Inter", sans-serif;_/
}

## Parte 6: Trabajar el Header- Estructura del Header

-agregamos la etiqueta de imagen
<img src="" alt="" /> -- Imagen del logo que acampaña al h1
-dentro de un <div></div>
agregamos..

<h1></h1> --Titulo
<p></p>   -- Parrafo
 <a href="#"><span>i</span></a> boton enlace con icono
 en la proxima seccion le añadiremos las clases a ultilizar en css

## Parte 7: Añadir las Clases "CSS"

Div: llevara la clase class="header--tittle-container"
<a href="#"><span>i</span></a> llevara la clase header--buttom

## Parte 8: Aplicamos Estylos al Header

header {
/_ position: relative; puedo posicionar el elemento relativamente, donde quiera_/
position: relative;
/_Mostramos los elementos tanto uno al lado del otro en vertical como en horizontal, siempre tendra dimencion_/
display: flex;
/_Mostramos en columnas la propiedad flex_/
flex-direction: column;
/_Justificamos todo el contenido _/
justify-content: center;
/_Ocupamos el 100% del ancho_/
width: 100%;
/_Ancho minimo_/
min-width: 320px;
/_Altura _/
height: 334px;
/_Texto aliniado_/
text-align: center;
}

## Parte 9: Aplicamos Estylos al Header etiqueta img utilizando especificidad

/_etiqueta de logo, img, utilizaremos especificidad_/
/_ vamos a llamar la etiqueta dentro de header que en este caso es img_/
header img {
/_Que tanto se aleja el elemento de derecha a izquierda_/
width: 150px;
/_que tanto se ealeja de abajo hacia arriba_/
height: 24px;
/_Que marguen tienen de arriba hacia abajo_/
margin-top: 60px;
/_Se utiliza para aliniar si nuestro parent, es display flex_/
align-self: center;
}

## Parte 10: Aplicamos Estylos al div clase header--tittle-container

.header--tittle-container {
/_El porcentaje es proporcional a el with y el height_/
width: 90%;
min-width: 288px;
max-width: 900px;
height: 218px;
margin-top: 40px;
text-align: center;
align-self: center;
}

## Parte 11: 


/_NOTAS_E_INFO_/
/_No utilizar imports en las fuentes de CSS, no son buenas practicas_/

/\_ Posicionamiento
--> static, absolute, relative, fixed,styki/

# Static positioned elements are not affected by the top, bottom, left, and right properties.

An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:

---

/_ Modelo de caja (Box model)
--> margin, border, padding, content_/

/_ Tipografía
--> tipos, tamaños de fuente, etc_/
/_ Estilos visuales
--> box-shadow, border-radius, gradient, etc_/

Uso de div -- Utilizar el div para cuando necesitemos una etiqueta opcional,
por que ya utilizamos toda la semantica de html en nuestro proyecto

-- Uso de clases, usar clases, cuando usemos etiquetas divs o algunas etiquetas
que sabeemos que se repetiran, asi las clasificamos,

--Uso Convencion de nombres BEM, utilizar Bem para las clases es la mejor forma
de clasificarlas
