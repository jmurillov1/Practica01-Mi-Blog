# Practica01-Mi-Blog

 	FORMATO DE INFORME DE PRÁCTICA DE LABORATORIO / TALLERES / CENTROS DE SIMULACIÓN – PARA ESTUDIANTES

CARRERA:  INGENIERÍA DE SISTEMAS
	ASIGNATURA:  HYPERMEDIAL 

NRO. PRÁCTICA:	1	TÍTULO PRÁCTICA:  Resolución de problemas sobre HTML5 

OBJETIVO ALCANZADO:
Entender y organizar de una mejor manera los sitios de web en Internet. 
Crear sitios web aplicando estándares actuales. 
Desarrollar aplicaciones web interactivas y amigables al usuario. 

ACTIVIDADES DESARROLLADAS
1. Crear un repositorio en GitHub con el nombre “Practica01 – Mi Blog”
Para realizar este paso previamente creamos una cuenta en GitHub, ahora conectado a la cuenta en línea procedemos a crear el repositorio donde guardaremos la práctica.
 
Luego tendremos la siguiente pantalla:
 
Con esto ya hemos creado nuestro repositorio. En este lugar nos dará la url del repositorio que es necesaria para configurar la forma de subir los archivos.
2. Realizar un commit y push por cada requerimiento de los puntos antes descritos. 
Para esto debemos abrir el cmd y colocar los siguientes comandos, en el caso de Windows:
-	git init
-	git add .
-	git commit -m "Nombre-Proyecto"
-	git remote add origin “url del respositorio”
-	git push -u origin master
Estos para la primera vez que se vaya a trabajar con el proyecto, después solo es necesario correr:
-	git add .
-	git commit -m "Nombre-Proyecto"
-	git push -u origin master
Y para que esto funcione previamente debes haber instalado y configurado “Git for Windows”.
Ahora luego de correr los comandos tendremos:
 
Con el init iniciamos el repositorio vacio.
Con el add los añadimos.
Con el commit creamos los datos dentro del repositorio.
Con el remote le damos la dirección de donde subir los archivos.
Y con el push guardamos los datos en el repositorio.
Si todo corre bien deberíamos obtener lo siguiente:
 
Como pueden darse cuenta la pagina web en GitHub se actualiza con los nuevos datos subidos, con esto hemos cargado en la pagina el primer punto de la práctica.
Funciones de las etiquetas utilizadas:
<! Doctype html>: etiqueta que se usa en HTML5.
<html> </html>: etiqueta usada para abrir y cerrar el documento html. Aquí se puede dar el idioma que utilizara el archivo.
<head> </head>: etiqueta usada para describir la cabecera general del archivo.
<meta />: configurar datos en lo referente al documento.
<title> </title>: Para configurar el titulo de la página. 
<body> </body>: como su nombre lo dice aquí se configurará el contenido del archivo.
<header> </header>: para la cabecera según los datos de la página.
<img />: etiqueta usada para la inserción de imágenes.
<ul> </ul>: etiqueta usada para realizar una lista desordenada
<nav> </nav>: contenedor para enlaces de navegación.
<li> </li>: etiqueta usada para poner los ítems de la lista.
<a> </a>: etiqueta usada para hacer hipervínculos, con ayuda de la palabra href.
<section> </section>: para crear una sección del documento.
<article> </article>: representa una composición del documento.
<h1> </h1>: para títulos de nivel 1.
<p> </p>: etiqueta usada para colocar párrafos.
<aside> </aside>: etiqueta usada para poner anuncios, citas de documentos, notas, entre otros.
<br />: para crear un santo de línea.
<footer> </footer>: Para colocar el pie de página. 

Para el primer punto de la practica tenemos:
“Estructurar un sitio web estático usando HTML5. El sitio web será informativo sobre un tema que será autoría del estudiante. El sitio web deberá contar con una página principal denominada index.html y debe contener al menos cinco páginas *.html más. Todas las páginas contaran con un menú de navegación que permitirá al usuario moverse entre todas las páginas HTML.” 
Ahora en nuestra carpeta creada tenemos los archivos de las páginas web a utilizar: 

 










Con respecto a la página inicial “index.html” tenemos lo siguiente: 
 
 
Aquí tenemos el archivo index.html que tiene la configuración de la pagina inicial de sitio web con HTML5.
Usamos la etiqueta <! doctype html> para especificar que es HTML5. Luego abrimos la etiqueta html para inicar el documento, donde definimos el idioma del archivo con lang=”es” para el idioma español.
Después abrimos la etiqueta head donde colocamos la información del documento como comentario, el tipo de formato de caracteres a usar con la etiqueta <meta />, en nuestro caso usamos charset= utf-8 que es nuestro formato de caracteres para español. Y ahí mismo debajo colocamos el título de la página con la etiqueta <title>.
Cerramos la etiqueta head y abrimos la etiqueta body para colocar el contenido de la página. Dentro de esta abrimos la etiqueta header para colocar el encabezado de la página. En nuestro caso usaremos una imagen como encabezado. Insertamos la imagen con la etiqueta <img />. Luego abrimos la etiqueta nav para crear la lista de navegación de la página con ayuda de las etiquetas ul para crear la lista y li para colocar los ítems, y dentro de la etiqueta li colocamos la etiqueta a para hacer un enlace a la página con esa información.
Luego cerramos la etiqueta ul y seguido la etiqueta nav y header.
Después abrimos la etiqueta section, seguido de la etiqueta article para colocar la información, luego abrimos la etiqueta h2 para hacer referencia que es un título de nivel 2 y cerramos, seguido de la etiqueta <img /> de nuevo para ingresar la segunda imagen de la página. Ahora abrimos la etiqueta p para colocar un párrafo, lo colocamos y cerramos la etiqueta, seguido cerramos la etiqueta article y section.
Luego abrimos la etiqueta aside donde colocamos los datos de donde obtuvimos información para crear la página, colocamos y cerramos.
Por último, abrimos la etiqueta footer, donde colocaremos información relevante acerca de nuestros datos personales, donde tenemos nuestro nombre, institución de estudio, celular como hipervínculo con cel y el correo como hipervínculo con mailto y al final el típico uso de la frase de copyright (Todos los derechos reservados con la C encerrada en un círculo.) Cerramos la etiqueta footer.
Al final cerramos la etiqueta body y html.

Ahora procedemos a actualizar esto en GitHub, con la ayuda del commit y push.

 

 
Luego todas las paginas a usar con el menú para acceder hacia las otras.
Página 2
 





Página 3
 
Página 4

 
Página 5
 
	Página 6	

 
Para el segundo punto de la practica tenemos:
“Todas las páginas *.html deben estar estructuradas según el siguiente formato. 
En donde, la etiqueta <header> deberá contener una imagen (logo) relacionada al tema elegido.” 
 
 
Página 1 o index.html

 
 
Desde la pagina 2 a 6 es lo misma es la misma estructura.

 




Ahora procedemos a actualizar esto en GitHub, con la ayuda del commit y push.

 
 

Para el tercer punto de la practica tenemos:
“Además, la etiqueta <footer> deberá tener la información del estudiante como nombres completos, organización, correo (usar hipervínculo, mailto), teléfono (usar hipervínculo, tel), además deberá tener el símbolo de copyright junto a la leyenda de “Todos los derechos reservados”. Por ejemplo, © Todos los derechos reservados.” 












Esto funciona para todos los archivos de la práctica.

 
Abrimos la etiqueta footer, donde colocaremos información relevante acerca de nuestros datos personales, donde tenemos nuestro nombre, institución de estudio, celular como hipervínculo con cel y el correo como hipervínculo con mailto y al final el típico uso de la frase de copyright (Todos los derechos reservados con la C encerrada en un círculo.) Cerramos la etiqueta footer.
Al final cerramos la etiqueta body y html.

Ahora procedemos a actualizar esto en GitHub, con la ayuda del commit y push.

 

 

Para el cuarto punto tenemos:
“Las páginas *.html deberán tener al menos una etiqueta <section>, <article> y <aside>.”

Abrimos la etiqueta section, seguido de la etiqueta article para colocar la información, luego abrimos la etiqueta h1 para hacer referencia que es un título de nivel 1 y cerramos, seguido de la etiqueta <img /> de nuevo para ingresar la segunda imagen de la página. Ahora abrimos la etiqueta p para colocar un párrafo, lo colocamos y cerramos la etiqueta, seguido cerramos la etiqueta article y section.
Luego abrimos la etiqueta aside donde colocamos los datos de donde obtuvimos información para crear la página, colocamos y cerramos. Ejemplo en index.html

 
En las otras páginas se puede hacer uso de más etiquetas para un mejor desarrollo de la práctica, que luego explicare.
Página 3
 
 
 
Como también se puede notar en esta página, si están los requerimientos pedidos de las etiquetas.
Procedemos a actualizar el GitHub.
 
 

Para el quinto punto tenemos:
De igual manera, se pide que al menos una de las páginas dentro del contenido de la etiqueta <article>, tengan los siguientes requisitos: 
•	Una tabla con la siguiente estructura: 
•	
 
•	Un video de YouTube (ver, etiqueta <iframe>). 
•	Manejar listas ordenadas o desordenadas con al menos cinco ítems. 
•	Tener al menos cinco etiquetas de texto que se encuentran en la figura 1- 16 del texto guía de la asignatura. 












Página en cuestión para estas condiciones:

 
 
  
 
En lo referente al encabezado y el logo se mantienen igual que en las demás páginas, así como también el header con el menú, solo cambiamos el título de la página. 
Lo nuevo es que usamos la etiqueta h2 para titulo de segundo nivel, abrimos etiqueta article, insertamos una imagen, luego abrimos la etiqueta table para crear la tabla requerida. Con esta hacemos uso de las siguientes etiquetas:
-	<table> </table>: crear la tabla, junto con la opción border y style.
-	<caption> </caption>: donde guardamos el título de la tabla.
-	<colgroup> </colgroup>: donde ponemos el estilo de las columnas.
-	<thead> </thead>: donde con la etiqueta <tr> </tr> con <th> </th> colocamos tanto los títulos de las filas(rowspan) y los títulos de las columnas, como también los títulos individuales de las columnas(colspan).
-	<tfoot> </tfoot>: con tr, para el pie de página de la tabla.
-	<tbody> </tbody>: para el cuerpo de la tabla, de nuevo tr con th para colocar los nombres de las filas y luego <td> </td> para los valores de las celdas.
De ahí continuamos con el siguiente parte, que es insertar un vídeo de YouTube en la página con la ayuda de la etiqueta <iframe> </iframe>, quedando el comando así:
<iframe width="560" height="315" src=https://www.youtube.com/embed/4jU_gNkIiFA
frameborder="0" allowfullscreen>
</iframe>

Aquí se debe colocar la altura y anchura del video, la url pero de una forma especial añadiendo la palabra “embed” a la url, la configuración del borde y la pantalla completa, después cerramos la etiqueta.

También hacemos uso de la etiqueta <h3> </h3> para títulos de tercer nivel.
Luego hacemos uso de la etiqueta ul para crear la lista desordenada que pide el trabajo. En la página utilize dos listas desordenadas.
<ul>
    <li><i>Extinto</i></li>
    <li><i>Extinto en Estado Silvestre</i></li>
    <li><i>Peligro Crítico</i></li>
    <li><i>Peligro de Extinción</i></li>
    <li><i>Vulnerable</i></li>
    <li><i>Casi amenazada</i></li>
    <li><i>Preocupación Menor</i></li>
    <li><i>Datos insuficientes</i></li>
</ul>

<ul>
    <li>LEÓN 90% - 17.000 ejemplares</li>
    <li>ELEFANTE AFRICANO 60% - 100.000 ejemplares</li>
    <li>DELFÍN DE CABEZA BLANCA 90% - 7.400 ejemplares</li>
    <li>RORCUAL NORTEÑO 50% - 47 ejemplares</li>
    <li>TORTUGA MARINA 95% - 10.000 ejemplares</li>
</ul>

Y por último el uso de las etiquetas de texto:
 
Se hace uso de las siguientes etiquetas:
<Strong> </Strong> y <b> </b>: para hacer negrita.
<a> </a>: para hacer hipervínculos.
<em> </em> y <i> </i>: para hacer cursiva.
<abbr> </abbr>: para hacer abreviaturas.
<u> </u>: para hacer subrayado.
<br />: para hacer salto de línea.
El resto de la página se mantiene igual en todas.

Actualización en GitHub:

 
 
Para el sexto punto tenemos:
“Asimismo, se pide que todos los artículos tengan al menos una imagen cada uno. Se pide que todas las imágenes están almacenadas en una carpeta llamada “images”. Por lo tanto, se debe trabajar con rutas relativas. “
Ejemplo de este punto.

 
Como se puede ver se hace uso de la etiqueta img para insertar la imagen en la etiqueta article y la inserción de la imagen hace uso de una ruta relativa.






Ahora en la ubicación del proyecto tenemos la carpeta images, que tiene las imágenes que usa la práctica.

 
Se procede a actualizar GitHub:

 
 

Para el último punto tenemos:
 
“Finalmente, se pide que una de las páginas tenga al menos dos secciones (<section>) con tres artículos (<article>) cada sección. Luego, cada sección debe tener un encabezado (<header>), en donde, se ubicarán enlaces que permitan navegar entre los artículos usando id’s (ver, página 63 del texto guía). “
Página 2 que hace uso de este punto.

 
 

 
En esta parte tenemos la primera sección (etiqueta section) como pide el punto, con sus tres etiquetas article, la imagen (etiqueta img) por cada etiqueta article y el uso de identificadores. Si se dan cuenta en esta página se hace uso de dos menús el general con la etiqueta ul, pero para el menú secundario hacemos uso de la etiqueta a para hacer un hipervínculo, es aquí donde se coloca la id para saltar al lugar donde se encuentra este tema.
<a href="acerca.html#resu"> Resumen</a> <br />

<h3 id="resu">Resumen</h3>



De esta forma se hace para navegar más rápido por una página, esto se le conoce como “Link to id”.
La siguiente sección funcionara de la misma forma.
 
 

 
Actualización en GitHub:
 
 




Capturas de las otras páginas:
Página 3
 
 
 
 

Página 4
 
 
  










Página 6
 
 
 
 

Estas son las páginas creadas siguiendo los puntos. 



















3. Al finalizar la práctica se debe validar todas las páginas HTML creadas usando el W3C Validator.
Página 1 – index.html
 
Página 2
  











Página 3
 
Página 4
 











Página 5
 
Página 6
 







4. Luego, se debe crear el archivo README del repositorio de GitHub. 
 
5. Información de GitHub (usuario y URL del repositorio de la práctica).
Usuario: jmurillov1
URL del repositorio: https://github.com/jmurillov1/Practica01-Mi-Blog

6. Información de GitHub (usuario y URL del repositorio del Tutorial 01 - Curbside Thai) 
Usuario: jmurillov1
URL del repositorio: https://github.com/jmurillov1/Creaci-n-de-Proyecto

7. En el archivo README del repositorio debe constar la misma información del informe de resultados de la práctica que se indica en el siguiente punto. 

RESULTADO(S) OBTENIDO(S):
•	Tener el conocimiento suficiente para que el estudiante pueda entender y organizar de una mejor manera los sitios de web y de negocios en Internet.
•	Tener el conocimiento sobre nuevas etiquetas y su uso.
•	Aprender a usar HTML5.
Resultados:
Sitio Web Completo: Google Chrome
 
 
 
 
 
 










Sitio Web Completo: Firefox
 
 
 
 
 
 










Sitio Web Completo: Internet Explorer
 
 
 
 
 
 
CONCLUSIONES:
•	Los estudiantes podrán organizar sitios web basados en el lenguaje de etiquetado HTML.
•	Que se debe organizar muy bien las etiquetas y la información para que la estructura sea correcta y lograr los resultados esperados.
•	Que la estructura con HTML5 es más rápida de trabajar, porque resume algunas cosas.
RECOMENDACIONES:
•	Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, Firefox y Safari.
•	Validar las páginas creadas con un software, como es el caso de: W3C Validator.
•	Usar correctamente las etiquetas HTML.

Nombre del estudiante: Jordan Fernando Murillo Valarezo

Firma del estudiante: 
