---
language: html
contributors:
    - ["Christophe THOMAS", "https://github.com/WinChris"]
translators:
    - ["Dennis Keller", "https://github.com/denniskeller"]
filename: learnhtml-de.html
lang: de-de
---

HTML significa HyperText Markup Language (lenguaje de marcado de hipertexto).
Es un lenguaje para escribir las páginas de la World Wide Web ..
Es un Auszeichnugssprache que nos permite escribir páginas web con código que características tales como texto y datos a visualizar. En realidad, los archivos HTML son archivos de texto sin formato.
¿Cuáles son los premios? Es un método para organizar los datos del sitio mediante el uso de etiquetas de inicio y fin.
Este premio está destinado a dar el significado del texto, al que rodea.
Al igual que muchos otros lenguajes de programación también, HTML tiene muchas versiones. Estamos hablando de HTML5.

**NOTE :**  Puede ver las diferentes etiquetas y elementos a prueba durante los tutoriales en sitios como [codepen] (http://codepen.io/pen/) para ver sus efectos y cómo funcionan. También se puede hacer más familiarizados con el lenguaje que con ella.
En este artículo se cuida de dar solamente la sintaxis HTML y consejos útiles.
`` `HTML
<! - son comentarios escritos en esta línea ->

<! - #################### #################### en las etiquetas ->

<! - Aquí está un ejemplo de archivo HTML analizaremos ->

<! DOCTYPE html>
<Html>
<Head>
<Title> Mi sitio </ title>
</ Head>
<Body>
<H1> Hello World! </ H1>
<a "http://codepen.io/anon/pen/xwjLbZ"> Vamos a ver lo que se muestra aquí </a>
<P> Este es un párrafo. </ P>
<P> Este es otro párrafo. </ P>
<Ul>
<Li> Este es un elemento con una lista no numerada (lista con viñetas) </ li>
<Li> Este es otro elemento </ li>
<Li> Y este es el último elemento de la lista </ ​​li>
</ Ul>
</ Body>
</ Html>

<! - Cada archivo HTML con el fin de iniciar el navegador para decir que la página es HTML. ->
<! DOCTYPE html>

<! - Luego se inicia con una Öffnungtag <html>. ->
<Html>

<! - Esto está cerrada al final del archivo con </ html>. ->
</ Html>

<! - Nada debe aparecer después de este último día. ->

<- Between (Entre la apertura y cerrado <html> </ html>), encontramos: ->

<! - Una cabeza se define con las etiquetas <head> (que debe estar cerrado con </ head>). ->
<! - La cabecera contiene descripciones e información adicional, que no se muestra. Estos son los metadatos. ->

<Head>
<Title> Mi página </ title> <! - La <title> identifica el navegador el título en la ventana del navegador y mostrar el nombre de la misma. ->
</ Head>

<! - Después de la> sección de la cabeza <, el <cuerpo encuentra> tag ->
<! - Hasta este punto, no se muestra nada en Browerfenster. ->
<! - Necesitamos el cuerpo al dar contenido a ser visualizado. ->

<Body>
<H1> Hola, mundo </ h1> <! -! La etiqueta h1 crea un título. ->
<! - También hay subtítulos para <h1> de la principal <h2> a los menos importantes (h6). ->
<a "http://codepen.io/anon/pen/xwjLbZ"> Ven, mira lo que muestra este código <! - Un URL es el enlace, si ese atributo href = "" - >
<P> Este es un párrafo </ p> <-.! La etiqueta <p> nos permite añadir texto a la página HTML. ->
<P> Este es otro párrafo. </ P>
<Ul> <! - La etiqueta <ul> crea una lista con viñetas. ->
<! - Para una lista numerada, debemos utilizar en su lugar <ol>. El primer elemento recibe el primer, segundo, etc. 2. ->
<Li> Este es un elemento de una lista desordenada </ li>
<Li> Este es otro elemento </ li>
<Li> Y este es el último elemento de la lista </ ​​li>
</ Ul>
</ Body>

<! - Y eso fue todo. Un archivo HTML puede ser tan simple. ->

<! - Pero es posible añadir muchos más etiquetas HTML adicionales. ->

<- Para añadir una imagen !. ->
<Img src = "http://i.imgur.com/XWG0O.gif" /> <! - La fuente de la imagen mostrada por el atributo src = "" ->
<! - La fuente puede ser una URL o una ruta de acceso a su computadora. ->

<! - También es posible una mesa para crear. ->

<Table> <! - Abrimos un> elemento de la tabla <. ->
<Tr> <! - <tr> nos permite crear series. ->
<TH> Primera cabecera de la tabla </ th> <! - <th> le permite introducir un título nos la mesa. ->
<TH> Segundo Tabllenkopf </ th>
</ Tr>
<Tr>
<Td> Primera fila, primera columna </ td> <! - <td> le permite crear una celda de tabla. ->
<Td> Primera línea, segunda columna </ td>
</ Tr>
<Tr>
<Td> Segunda fila, primera columna </ td>
<Td> Segunda fila, segunda columna </ td>
</ Tr>
</ Table>

`` `

## uso

Los archivos HTML terminan con `.html`.

## Para conocer más

* [Wikipedia (ES)] (https://en.wikipedia.org/wiki/HTML)
* [Tutorial HTML (ES)] (https://developer.mozilla.org/en-US/docs/Web/HTML)
* [W3school (EN)] (http://www.w3schools.com/html/html_intro.asp)