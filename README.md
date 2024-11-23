# Aprendizaje de CSS, mientras practico con GIT HUB.

## Aqui vere algunos avances de mi practica con css.
Todas las propidades del archivo de html, las definen las hojas de estilo en cascada.
Para cada elemento de html. El navegador tienen una propiedad estandard para una pagina 
web.

### Para que sirve CSS
El css permite modificar los elementos del navegador. Con diferentes reglas de estilo.

### Tipografias.
Font-size: sirve para aumentar el tamaño de las letras.

Font-wieght: sirve para poner las letras en negritas, no es necesario ocupar, la etquieta b,
solo con colocar la propiedad bold al font wieght, se cambiara de color.
Cuando se escribe, bold y 700 es exactamente lo mismo. 

<style>
p{
  color: red;
  font-family: sans-serif;
  font-size: 13px;
  font-weight:bolder;
  font-style:oblique 40deg;
  text-align: justify;
  text-decoration: none;
    line-height: 2;
}
</style>
Con Font wiegth puedo definir el tamaño y anuchura de una tipografia.
Con el atributo Font-style, le puedo modiifcar como se vera la letra, ejemplo que se,
pueda persibir el letras <i> cursivas </i>

Con Text align en el valor justify: el valor justify hace que todas las lineas de texto queden alineadas.

Con Text decoration: puedo agregar un subrayado a mi texto en la parte inferior o superior de mis parrafos.
Y con el valor none es para quitarle las lineas de subrayado a mis enlaces.

La propiedad line-height: lo que hace es definirme el espaciado de las letras, entre mayor sea el numero más espacio habra entre las lineas.

### Box model  Contenido, Borde y margen.

la propiedad background sirve para cambiar el color de fondo de la caja div.
la propiedad width y heigth sirven para hacer el ancho y largo de una caja en css.

Padding o relleno: lo que hace es aumentar el tamaño que hay dentro de la caja osea el contenido.

## Formas de dar un color en css

1. Exadecimal, Exadecimal y alpha.
2. RGB , RGBA.
3.HCL, HCLA.

El sistema de base hexadecimal es de 16 en adelante y hay más posibilidad de usar distintos colores.
Es una representación del rgb pero más corta.
#00 el primer numero despues del # es el rojo en este caso el (00).
#00ff las letras representan el color verde en el rgb en este caso el(ff).
#00ff00 los ultimos numeros representan al color azul, en este caso es el (00).
El sistema hexadecimal se maneja asi.
0
1 6 a
2 7 b
3 8 c
4 9 d
5   f

Cuando los datos aparecen con la letra significa que es la saturación del color,
osea que si quiero que se vea más oscuro o más claro.

## Unidades de medidas 

### Pixeles
Los pixeles son el area de medida más pequeña, que se encuentra en la pantalla de,
mi dispositivo. Se usa normalmente para definir el tamaño de algunos elementos. 
Como por ejemplo el alto y el ancho de las imagenes. También el tamño de los textos osea la tipografia. Támbien se usan en los margenes y en los paddings (Rellenos).

Los pixeles son unidades de medida absolutas, son ideales cuando nececitamos tener control y ser presisos. 

### Pt
Es la unidad de medida que se usa para las impresiones. 

### Cm (centimetros), mm(mimilimetros), in(pulgadas) 
Estas son formas de medir para cosas que seran aplicadas a la vida real, digams se usan estas unidades de medida para el diseño de distintas cosas.
Tambien se utiliza para definir pantalas tactiles.

## Unidades Relativas 
Es una unidad que depénde de otro valor.
el valor de la unidad depende de otro valor. 

### Porcentajes
 Cuando se usan % porcentajes, se refiere a que estan ocupando un porcentaje de la caja en la pagina web. 
 Los porcentajes definen algo respecto al tamaño contenedor, en pocas palabras los porcentajes son digamos 400px equivale a mi 100% y 40px equivale a mi 10% de los 400px.
 Los porcentajes son una medida relativa. 
 Normalmente los porcentajes se utilizan para los textos.

 ### em 
 Un em va a valer lo mismo que el font-size del elemento padre.

 Digamos que el elemento padre mide 40px entonces si a mi elemento hijo le coloco un 1em su medida sera la misma que la del padre osea 40px.

 Y si aumento a 2em mi elemento hijo valdra el doble que el elemento padre en este caso valdra 80px. 

 ### rem 
 el elemento rem hace lo mismo que el elemento padre con la unica diferencia que el elemento buscara el elemento de la raiz. Osea el elemento que contenga mi html.