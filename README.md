Hola! esta es una presentacion que hice para la semana del gnu y del pinguino, organizada por la Sociedad Cientifica de la Carrera de Informatica de la Universidad Mayor de San Andres en Bolivia :)

Esta hecha en LaTeX, pueden compilar el .tex que se encuentra en la carpeta texfiles/ asi:

$ cd img/

$ ./svg2png #convertir las imagenes de svg a png utilizando la opcion 'convert' del ImageMagick

$ cd ..

$ pdflatex /texfiles/gnutux.tex


Generara algunos errores que necesito corregir. Pero se arreglara con presionar la tecla enter cada vez que la compilacion se pause. (prometo corregir estos errores en cuanto tenga tiempo n.n') 
Esto generara un archivo pdf que podras abrir con Evince o con el visor de documentos que prefieras · w ·

Sientete libre de revisar y modificar el codigo fuente con tu editor de texto favorito, y de usar la presentacion como quieras :D

Las imagenes en la carpeta img/ contienen todas las imagenes usadas para hacer la presentacion, las imagenes estan en formato svg, y fueron hechas utilizando Inkscape. Para que la presentacion reconozca las imagenes, primero tienes que convertirlas de svg a png, para esto, solo hay que ejecutar el script que se encuentra en la carpeta de imagenes del proyecto: svg2png. Oh! y cada vez que modifiques las imagenes svg, tienes que volver a ejecutar el script dentro de la carpeta de imagenes, para que se actualicen dentro de la presentacion (escuche que hay una libreria para LaTeX que permite incluir imagenes svg... arreglare esto en cuanto tenga tiempo >__<')

Btw, si te gusto el script, y quieres usarlo como un comando (i.e. cd, ls, mkdir, etc...), copialo en la carpeta /usr/bin/ y voila! 