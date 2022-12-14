# MARKDOWN 

Markdown es un lenguaje de marcado ligero,una forma de agregar formatos como encabezados,negritas,cursivas,listas... a un texto sin formato utilizando un editor de texto simple. Es decir, una forma rápida de coger apuntes con ordenador y pasarlos a limpio en un solo paso.  

  *- Elementos de bloque*  
   *- Párrafos*  
  *- Saltos de línea*  
  *- Encabezados*  
  *- Citas*  
  *- Listas*  
  *- Códigos de bloque*  
  *- Líneas horizontales*  
  *- Elementos de línea*  
  *- Énfasis*  
  *- Links o enlaces*  
  *- Código*  
  *- Imágenes*  
  *- Otros elementos*  
  *- Links automáticos*  
  *- Omitir Markdown*  
  *- Símbolos matemáticos*



# Saltos de bloque (=Párrafos)

Para generar un nuevo parrafo en Markdown simplemente separa el texto mediante una linea en blanco (pulsando dos veces INTRO). `Ejemplo:`  
Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original. Fue popularizado en los 60s con la creación de las hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más recientemente con software de autoedición, como por ejemplo Aldus PageMaker, el cual incluye versiones de Lorem Ipsum.

# Saltos de linea (=lineas de texto)

Para realizar un salto de linea y empezar una frase en una linea sigueinte dentro del mismo parrafo, tendras que pulsar dos veces la barra espaciadora antes de pulsar una vez INTRO.  `Ejemplo:`

Nombre:  
Apellidos:  
Direccion:  




# ENCABEZADOS

Las almohadillas o hastag `#` es el metodo utilizado en markdown para crear encabezados. Debes usarlos añadiendo uno por cada nivel y dejando un espacio en blanco. 



## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5 

###### encabezado 6 

# Enfatizar: negritas y/o cursivas

Para poner cursivas encierra entre 1  asterisco. 
Para poner negritas encierra entre 2 asteriscos.
Para poner negritas en cursiva encierra entre 3 asteriscos. `Ejemplos:`  

"Lorem ipsum dolor sit *amet*, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in *voluptate velit esse cillum dolore* eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum." 

# Líneas horizontales 

Para crearlas, en una linea en blanco deberás incluir `tres` de los siguientes elementos: 3 asteriscos,3 guiones,o tres guiones bajos. `Ejemplo:`

***

# Citas
Las citas se generan utilizando el carácter mayor que `>` al comienzo del bloque de texto. `Ejemplo:`

>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."


# Listas

Para crear listas desordenadas podemos utilizar 3 tipos de simbolos por cada item de la lista:  
Un asterisco `*` , un guion medio `-` o un símbolo más `+` . `Ejemplo:`  
- ítem 1
- ítem 2
- ítem 3  


Para crear listas ordenadas debes utilizar la sintaxis de tipo : `1.` .  
1. ítem 1
2. ítem 2
3. ítem 3

Para generar listas anidadas (desordenadas u ordenadas) dentro de otras, simplemente tendras que añadir `dos (o cuatro) espacios en blanco .` `Ejemplo:`  


 - ítem 1
     - item 12
         - ítem 121
 - ítem 2

1. ítem 1    


# Links o enlaces  
Se crean escribiendo la palabra o texto enlazada entre `[]` corchetes, y el link en cuestión entre `()` paréntesis.  
Sin texto enlazado escribe la URL entre ángulos `< URL >` Enlace de ejemplo como referencia [3con14]() , y al final del texto escribir la etiqueta seguida de dos puntos.  

# Imágenes 

Insertar una imagen con Markdown se realiza de una manera identica al insertar links. En este caso, debes añadir un simbolo de `!` exclamación al principio y el enlace que es la ubicación de la imagen.

![Hola](imagen.png "Imagen")![Hola](imagen.png "Imagen")  

# Tablas

Markdown permite dibujar tablas mediantes plecas `|`. Cada celda esta separada por uno de estos caracteres.  
para crear encabezados que se distingan visualmente del resto de contenido, se subrayan las celdas correspondientes con guiones `-`. `Ejemplo:`  

 
|Columna 1 | Columna 2 |  
|----------|-----------|
|uno       |dos        |  
|tres      |cuatro     |  
|cinco     |seis       |


# Línea de código

Encerrando el código entre acentos graves <html lang="es"> 

# Bloque de Código

Para crear un bloque entero que contenga código lo unico que tiene que hacer es encerrar dicho párrafo entre dos líneas formadas por tres `~` virgulillas o tres acentos graves. La otra manera de añadir código en Markdown es comenzar el párrafo con `cuatro espacios en blanco`. `Ejemplo:`

~~~html
<head> 
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />  
  <title>Document</title>
</head>
~~~

# Omitir Markdown

Cómo escribir ciertos símbolos como `*` o `#`, sin que Markdown los interprete para convertirlos en negritas,....  
Escribiendo justo delante del sìmbolo la barra invertida `\`. `Ejemplo:` Esto es un asterisco \* 

# Escritura matemática

En línea encerrando la fórmula entre signos de `$` en párrafos centrados, encerrando las fórmulas entre dos signos de `$$`.

- Fórmula en línea:  
$$(a + b)² = a² + b² + 2ab$$  
  
- Fórmulas centradas:  
  $$a²-b²=(a+b)*(a-b)$$  

- Radicales:  
  $$\sqrt{a²-b²}$$
- Fracciones:  
  $$ x=\frac{-b \pm \sqrt{b²-4ac}}{2a}$$
- Paréntesis grande:  
  $$
  \left(\sqrt{x²}\right)²
  $$
- Colores:  
 $$
 {\color {yellow}{A}}aBb123
 $$
  