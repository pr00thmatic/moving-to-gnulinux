Hola! esta es una presentacion que hice para la semana del gnu y del pinguino, organizada por la Sociedad Cientifica de la Carrera de Informatica de la Universidad Mayor de San Andres en Bolivia :)

Esta hecha en LaTeX, pueden compilar la presentacion, ejecutando el archivo 'compile' de esta forma:

$ ./compile

Si no tienes el programa Evince, para ver archivos pdf, tendras que abrirlo de forma manual, visualizando con tu visor de documentos preferido el archivo gnutux.pdf que se encuentra en la carpeta texfiles...

El script tardara un poco, porque tiene que convertir las imagenes svg a png, esto solo tiene que hacerse la primera vez! una vez que tengas las imagenes en png, puedes correr el script utilizando el argumento '-ni' (no imagenes), asi:

$ ./compile -ni

Gracias a Alejandro Salamanaca Mazuelo por corregir los bugs del documento, y por añadir el inputenc y el babel! :D

Sientete libre de revisar y modificar el codigo fuente con tu editor de texto favorito, y de usar la presentacion como quieras :D

Las imagenes en la carpeta img/ contienen todas las imagenes usadas para hacer la presentacion, las imagenes estan en formato svg, y fueron hechas utilizando Inkscape. Para que la presentacion reconozca las imagenes, primero tienes que convertirlas de svg a png, para esto, solo hay que ejecutar el script que se encuentra en la carpeta de imagenes del proyecto: svg2png. Oh! y cada vez que modifiques las imagenes svg, tienes que volver a ejecutar el script dentro de la carpeta de imagenes, para que se actualicen dentro de la presentacion (escuche que hay una libreria para LaTeX que permite incluir imagenes svg... arreglare esto en cuanto tenga tiempo >__<')

Btw, si te gusto el script, y quieres usarlo como un comando (i.e. cd, ls, mkdir, etc...), copialo en la carpeta /usr/bin/ y voila! 