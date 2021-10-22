# HTML - CSS
<p align="center">
    <img src="https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582748_1280.png" width="30%">
    <img src="https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582747_960_720.png" width="30%">
</p>

HTML y CSS, los lenguajes de maquetación que permiten definir la estructura y estilos de una página web.

## Tabla de Contenido  <a href="#tabla-de-contenido--"></a>

### Web Developer Fundamentals
- [¿Qué es Frontend?](#Qué-es-Frontend)
- [¿Qué es Backend?](#¿Qué-es-Backend?)
- [¿Qué es Full Stack Developer?](#¿Qué-es-Full-Stack-Developer?)
- [Páginas Estáticas vs. Dinámicas](#Páginas-Estáticas-Dinámicas)

### HTML

- [¿Qué es HTML?](#que-es-html)
- [Anatomía de una página web](#anatomía-página-web)
- [Index y su estructura básica: head ](#head)
- [Index y su estructura básica: body](#body)
- [Anatomía de una etiqueta HTML](#anatomia-html-tag)
- [Etiquetas multimedia](#etiquetas-multimedia)
  - [Optimización de imágenes](#opt-imágenes)
  - [Tipos de imágenes](#tipos-imagenes)
  - [Etiqueta img](#img)
  - [Etiqueta figure](#figure)
  - [Etiqueta video](#video)
- [Formularios](#formularios)
  - [Etiqueta form e input](#form-input)
  - [Calendario](#calendario)
  - [Autocomplete y require](#autocomplete-require)
  - [Select](#select)
  - [Input type submit vs Button Tag](#input-button)
- [HTML Cheat Sheet](#HTML-Cheat-Sheet)


## ¿Qué es Frontend?<a name="Qué-es-Frontend"></a>

Frontend es la parte de un programa o dispositivo a la que un usuario puede acceder directamente. Son todas las tecnologías de diseño y desarrollo web que corren en el navegador y que se encargan de la interactividad con los usuarios y el frontend developer es el que va a manejar las cosas del lado del cliente, las interacción que tienes en una página web, las animaciones y los estilos.

<p align="center">
    <img src="https://i.imgur.com/uWJngOH.png" width="100%">
</p>

Para convertirse en Frontend Developer principalmente se debe entender y dominar perfectamente estos tres estándares Web:
 
- <strong>HTML y CSS</strong>: los lenguajes de maquetación que permiten definir la estructura y estilos de una página web.
-  <strong>JavaScript</strong>: el lenguaje de programación que servirá para  definir la lógica de nuestra aplicación, recibir las solicitudes de los usuarios y enviárselos al backend.

Dominando estas tecnologías ya se puede escalar a algunos frameworks, librerías o preprocesadores los cuales expanden las capacidades para crear todo tipo de interfaces de usuario. Algunos de ellos son:

#### Frameworks de CSS
- <a href="https://getbootstrap.com/">Bootstrap </a>
- <a href="https://get.foundation/">Foundation CSS</a>
- <a href="https://materializecss.com/">Materialize CSS</a>

#### Frameworks y Librerías de JS
- <a href="https://es.reactjs.org/">React JS</a>
- <a href="https://angular.io/">Angular JS</a>
- <a href="https://vuejs.org/">Vue JS</a>

#### Preprocesadores de CSS:
- <a href="https://stylus-lang.com/">stylus</a>
- <a href="https://sass-lang.com/">SASS</a>
- <a href="https://lesscss.org/">less</a>

#### Compiladores / empaquetadores de JS
- <a href="https://babeljs.io/">BABEL </a>
- <a href="https://webpack.js.org/">Webpack</a>


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>

## ¿Qué es Backend?<a name="¿Qué-es-Backend?"></a>

Backend es la capa de acceso a datos de un software o cualquier dispositivo,  no es directamente accesible por los usuarios, además contiene la lógica de la aplicación que maneja dichos datos. El Backend también accede al servidor, que es una aplicación especializada que entiende la forma como el navegador solicita cosas.

<p align="center">
    <img src="https://i.imgur.com/s9Iia0t.png" width="100%">
</p>

Un Backend Developer es lo opuesto a lo que hace un frontend, pues este es aquel que trabaja del lado del servidor manejando toda la lógica que hay detrás de una petición dada por el navegador.

Para Backend Developer no hay un estándar definido, ya que tiene varios lenguajes de programación y varias tecnologías con las que se puede trabajar.

Algunos de los lenguajes de programación para Backend son:
 
- <a href="https://www.python.org/">Python</a>
- <a href="https://nodejs.org/en/">Node.js</a>
- <a href="https://www.php.net/">PHP</a>
- <a href="https://www.java.com/es/">Java</a>
- <a href="https://www.ruby-lang.org/en/">Ruby</a>
- <a href="https://golang.org/">Go</a>
- <a href="https://docs.microsoft.com/en-us/dotnet/csharp/">C#</a>


Y así como en el frontend, todos estos lenguajes tienen diferentes frameworks que  permiten trabajar mejor según el proyecto que se este desarrollando, como:
 
- <a href="https://www.djangoproject.com/">Django</a>
- <a href="https://expressjs.com/es/">express</a>
- <a href="https://laravel.com/">laravel</a>
- <a href="https://spring.io/">spring </a>
- <a href="https://rubyonrails.org/">RAILS</a>

El Backend Developer también tiene que tener en cuenta la infraestructura, donde va a generar el deploy de su aplicación (esto también puede ser tarea de un DevOps, un perfil dedicado a la infraestructura). Con tecnologías como:

- <a href="https://cloud.google.com/">Google Cloud</a>
- <a href="https://www.digitalocean.com/">DigitalOcean </a>
- <a href="https://aws.amazon.com/es/">amazon aws</a>
- <a href="https://www.heroku.com/">HEROKU</a>

Por último, debe conocer de bases de datos relacionales y bases de datos no relacionales, generar la arquitectura y conectarla según el lenguaje que este trabajando, algunas de estas bases de datos son:
 
- <a href="https://www.mongodb.com/es">mongo DB</a>
- <a href="https://www.mysql.com/">MySQL</a>
- <a href="https://www.postgresql.org/">PostgreSQL</a>


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>

## ¿Qué es Full Stack Developer?<a name="¿Qué-es-Full-Stack-Developer?"></a>


Un  Full Stack Developer es la fusión de un  Frontend Developer y todas las cosas que hace un Backend Developer  en una sola persona, pero no maneja por completo todas las tecnologías de ambas partes, de hecho no es recomendado y no es sano, ya que el desarrollo web evoluciona muy rápido y cada dos o tres meses tenemos algo nuevo.
 
<p align="center">
    <img src="https://2.bp.blogspot.com/-ysM3KQvoT6M/WpSGL0Ho3yI/AAAAAAAAbsg/ca2Oof_vW0osVFHU6ratej9xpz94V7YHwCLcBGAs/s1600/frontend%2Bbackend.jpg" width="100%">
</p>

Un full stack es alguien que entiende muy bien cómo funciona un producto web de principio a fin, desde que esta en idea en forma de mockup hasta la liberación de la aplicación a producción. Entiende las tecnologías que se usan tanto en el Frontend como en el Backend pero se especializa en una  área especifica.
 

<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Páginas Estáticas vs. Dinámicas <a name="Páginas-Estáticas-Dinámicas"></a>

<p align="center">
    <img src="https://i.imgur.com/WZUTphN.png" width="100%">
</p>

#### Páginas estáticas

La información que contienen, se mantiene constante y estática. No se actualiza con la interacción del usuario y serán siempre iguales para todos los usuarios por lo que no estan conectadas a una base de datos, ya que los cambios solo se generan en el servidor.

Este tipo de paginas es conveniente para Páginas informativas o Blogs.

ejemplos:
 
- <a href="https://million-devs.netlify.com ">netlify</a>
- <a href="https://www.imuniapp.com">iMuni</a>
- <a href="https://marvlm.github.io/tdd-infographic/">TDD</a>

#### Páginas Dinámicas 

Dejan de ser paginas y se convierten mas en aplicaciones, actualizan su información con respecto a la interacción del usuario y  serán diferentes dependiendo del usuario que la use y dependen de una base de datos, de donde extrae e ingresa información
	 
- <a href="https://www.facebook.com/">facebook</a>
- <a href="https://platzi.com">platzi</a>
- <a href="https://twitter.com/">twitter</a>


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## ¿Qué es HTML? <a name="que-es-html"></a>

Es un lenguaje interpretado, es el código que se utiliza para estructurar el contenido de una web,  darle sentido y propósito. es un estándar, así que no importa desde que navegador o dispositivo se ejecute, el código será siendo el mismo.

HTML son las siglas de <b>Hyper Text Markup Language</b>(Lenguaje de Marcado de Hipertexto).

- <strong>Hyper Text</strong> significa que el texto tiene interactividad, conexión con otros documentos. 

- <strong>Markup</strong> significa que le pone etiquetas a los elementos.Por eso también se le conoce como un lenguaje de etiquetas. 


## Anatomía de una página web <a name="anatomía-página-web"></a>

Esta es la anatomía que vamos a encontrar en la mayoría de páginas web.

<p align="center">
    <img src="https://i.imgur.com/Arj4X0j.png" width="100%">
</p>

- <strong>Container</strong>: Contenedor principal
- <strong>Header</strong>: Cabecera de la página
- <strong>Main content</strong>: Estructura principal, por ejemplo el post de un red social.
- <strong>Sidebar</strong>:  Contenido secundario de una página.
- <strong>Footer</strong>:  Pie de página.

Ejemplo:

<p align="center">
    <img src="https://i.imgur.com/fuozodm.png" width="100%">
</p>


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Index y su estructura básica: head <a name="head"></a>

En el head van todos los archivos importantes para el correcto funcionamiento de nuestra plataforma pero que no deben ser visibles por lo usuarios. Algunos de estos archivos pueden ser:

- Frameworks
- Librerías
- Estilos
- Fuentes
- APIs


```HTML
<!DOCTYPE html> 

<html lang="es"> 
  <head> 

    <meta charset="UTF-8"/> 

    <meta name="description"content="Aprendiendo un poco de algunas etiquetas"/>
      
    <meta name="robots"content="index,follow" /> 

    <title>Aprendiendo html</title> 

    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0"> 

    <link rel="stylesheet"href="./style.css"> 
	
  </head>
</html>
```

- `<!DOCTYPE html>`:  Le indica al navegador que todo el código que contiene este archivo es HTML5.
 
- `<html lang="es">`: Es la etiqueta "padre" donde vivirá nuestro proyecto. El atributo lang establece el idioma de sitio web. Debemos usarlo para que el navegador pueda traducir nuestra página
 
- `<head></head>`: En el head van todos los archivos importantes para el correcto funcionamiento de nuestro proyecto, pero que no son visibles por los usuarios. Algunos de estos archivos pueden ser:

  - Frameworks
  - Librerías
  - Estilos
  - CSS
  - Fuentes
  - APIs
 
- `<meta>`: Las etiquetas meta le van a dar cierta información al navegador para que sepa como tratar nuestro proyecto.
 
- `<meta charset="UTF-8" />`:  Este atributo nos ayuda a la hora de incluir caracteres especiales y emojis en nuestro proyecto.
 
 
- `<meta name="description"content="" />`: Muestra una descripción de nuestro sitio en los buscadores.

- `<meta name ="robots"content="index,follow" />`: Le dice a los robots de los navegadores que rastreen nuestra página y la muestran en las búsquedas que tengan relación con nuestro contenido.
 
- `<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">`:Nos ayuda a trabajar en proyectos reponsive.

- `<link rel="stylesheet"href="/LearnHtml/style.css">`: Linkea/Enlaza archivos de estilos u otros archivos que necesitemos en nuestro proyecto en este caso con  rel="stylesheet" le especifica que el documento a enlazar es una hoja de estilo.

- `<title>texto</title>`:  Título de nuestra página, no confundir con los h1-h6. Este título es el que se verá en la pestaña del navegador.
 
 
Hay etiquetas que necesitan de una etiqueta de cierre como es el cado de head, pero hay otras que se cierran solas como la etiqueta meta que puede o no llevar un  slash "/" al final para indicar su cierre.

```HTML 
<a href = "https://platzi.com/">Contenido</a>

<img src="imagen.png"/>

```
Es importante tener en cuenta que la primera pagina o archivo HTML debe ser nombrada como index.html ya que va a ser la pagina inicial la cual el servidor va a buscar al momento de abrir un proyecto, si esta pagina no existe debemos especificarle al servidor que pagina debe tomar como inicio.

<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Index y su estructura básica: body <a name="body"></a>

Existen dos tipos de etiquetas en body:

-  <strong>Etiquetas de contenido</strong>: Son las encargadas de mostrar texto, imágenes, videos, cualquier cosa que se vaya a renderizar en el proyecto

- <strong>Etiquetas contenedoras</strong>: Son las que nos van a permitir darle estructura, organizar nuestro contenido, generar la maquetación o layout de nuestro proyecto

```HTML
<!DOCTYPE html> 

<html lang="es">

  <head> 
  </head> 

  <body> 
        
    <header> 
            <nav></nav> 
    </header>
    
    <main>
    
      <section> 
            
        <article> 
        </article> 
        
        <ul> 
          <li>Elemento uno</li> 
          <li>Elemento dos</li> 
        </ul> 
        
        <ol> 
          <li>Elemento uno</li> 
          <li>Elemento dos</li> 
        </ol>
        
        <hr>
        
        <p>Soy un texto generado con la etique de parrafo</p> 
        
        <pre> 
          Texto representado como 
          esta en el archivo html 
        </pre> 
        
        <p><b>Párrafo en negrita</b></p> 
        
        <p><strong>Párrafo importante</strong></p>
        
        <p><i>Párrafo en itálica</i></p>
        
        <p><em>Párrafo para enfatizar</em></p>
        
        <p><small>Párrafo pequeño</small></p>
        
        <p><mark>Párrafo resaltado</mark></p>
        
        <p><del>Párrafo eliminado</del></p>
        
        <p><ins>Párrafo que se ha insertado</ins></p>
        
        <p>Subíndice: H<sub>2</sub>0</p>
        
        <p>Súper indicé: x<sup>2</sup></p>
        
        <a href="#">Soy un link que no me lleva a ninguna parte</a>
        <a href="https://platzi.com/home" target="_blank">Platzi</a>
                  
      </section>

    </main>

  </body> 

</html>
```

- `<header></header>`: Sección superior de nuestro website.
 
- `<nav></nav>`Sección/barra de navegación de nuestro website, siempre va a ir dentro del header.
 
 
- `<main></main>`: main es el contenido central de nuestro website, "la parte del medio".
 
 
- `<h1></h1>`: Títulos, muestran el texto más grande y con negrilla. Existen desde el h1 al h6.
 
- `<article></article>`:artículos que pueden ir dentro de cada sección, pueden ser utilizados en comentarios.
 
- `<ul></ul>`: Lista desordenada: Sin numerar.
 
- `<ol></ol>`: Lista ordenada: Numerada.

- `<hr>`:  horizontal rule, se utiliza para separar el contenido
 
- `<li></li>`: Item List. Elementos de la lista.
 
- `<p></p>`:  Párrafo, texto.

- `<pre></pre>`: preformatted text, lo que hace esta etiqueta es presentar el texto exactamente como está escrito en el archivo HTML. El texto suele presentarse con una fuente no proporcional o "monoespaciada". Los espacios en blanco dentro de este elemento se muestran tal y como están escritos.

- `<b></b>`: Pone el texto en negrita, se utiliza para llamar la atención del lector sobre el contenido del elemento.

- `<strong></strong>`: Se utiliza para definir un texto de gran importancia. El contenido que contiene suele aparecer en negrita.

- `<i></i>`: Nos permite formatear el texto en cursiva.

- `<em></em>`: Se utiliza para marcar el texto que tiene énfasis, lo que tradicionalmente significa que el texto se muestra en cursiva por el navegador.

- `<small></small>`: Define un texto más pequeño.

- `<mark></mark>`: Se utiliza para representar un texto marcado o resaltado con fines de referencia o anotación.

- `<del></del>`: Representa texto que ha sido borrado de un documento.

- `<ins></ins>`: Sirve para definir texto que ha sido insertado en un documento.

- `<sub></sub>`: Define un subíndice que aparece medio carácter por debajo de la línea normal, y a veces se representa con una fuente más pequeña.

- `<sup></sup>`: Sirve para representar un superíndice, se suelen representar con una línea de base elevada y con un texto más pequeño.
                  
- <`a href="link"></a>`: Enlaces/links que nos permitirán movernos entre páginas.

- `target="_blank"`:  Este atributo hará que nuestro link se abra en una nueva pestaña.

Una buena práctica al escribir código HTML es utilizar HTML5  semántico, que es utilizar las respectivas etiquetas contenedoras para cada sección de nuestro proyecto.

Mas etiquetas y elementos de HTML  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">aquí</a>


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Anatomía de una etiqueta HTML  <a name="anatomia-html-tag"></a>

<p align="center">
    <img src="https://i.imgur.com/wafq4Om.png" width="100%">
</p>

#### Apertura y cierre

La apertura y el cierre siempre llevan el nombre de la etiqueta HTML que se usará, y son las que sirven para delimitar el contenido de la misma.


#### Atributo y valor

El atributo son distintos ingredientes o modificaciones que puedes hacer a la etiqueta. Como por ejemplo colocarle un ID, especificar algún evento (como los casos de onsubmit y onclick ), o modificar el aspecto visual (como cambiarle el color a un texto).Pueden ser opcionales u obligatorios

El valor es la especificación de estas modificaciones. ¿Qué debe suceder después del onsubmit? ¿Qué color debe tener el texto? ¿Qué ID tendrá la etiqueta?


#### Contenido

El contenido de la etiqueta es la información que queremos que sea afectada por la etiqueta con sus modificaciones (atributos).


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Etiquetas multimedia <a name="etiquetas-multimedia"></a>

Son el tipo de etiquetas que usaremos para insertar imágenes vídeos y audio.

<p align="center">
    <img src="https://static.platzi.com/media/user_upload/Carrusel-html-05-d8200501-20bc-434c-b15c-c855d5528393.jpg" width="70%">
</p>


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Optimización de imágenes <a name="opt-imágenes"></a>

Es importante saber que no es óptimo cargar imágenes en nuestro sitio web que pesen mucho porque tardan bastante tiempo en renderizarse y le dan una mala experiencia al usuario.


<p align="center">
    <img src="https://i.imgur.com/mfkaHvx.png" width="20%">
</p>


El tamaño promedio de una imagen debe ser de 70 a 100 kilobytes, con las siguientes herramientas web podremos optimizar nuestras imágenes.

- [TinyPNG](https://tinypng.com/): Mejora y reduce el tamaño de las imágenes png y jpg.

- [Verexif](https://www.verexif.com/): Elimina los metadatos de la imagen. Se usa para imágenes que vienen de una cámara.

- [Compressor](https://compressor.io/): Comprime sin perder calidad 

- [PicResize](https://picresize.com/): Comprime y recorta el tamaño de la imagen

- [Convertio](https://convertio.co/es/): convierte jpg, png a svg, puede convertir diferentes formatos a otros formatos.


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Tipos de imágenes <a name="tipos-imagenes"></a>

Existen 2 tipos de imágenes: <b>Con Perdida (Lossy</b>) y <b>sin Perdida (Lossless)</b>, esto dependerá del formato que manejemos.
 
- <b>Lossy</b>: Este tipo de imágenes se refiere a imágenes pequeñas y que pierden calidad (comparadas con las lossless). Nos ayudan a mejorar el tiempo de carga de nuestro website pero perdemos calidad. Algunos de estos formatos son:

  - <b>JPG (Photographic Experts Group)</b>: Al comprimirla, pierde calidad.

- </b>Lossless</b>: Son imágenes que no pierden calidad,su calidad siempre se mantendrá igual. Son más lentas en cargar y consume más recursos, pero tendremos unas mejores imágenes sin importar que se comprimen. Algunos formatos de estas son:

  - <b>GIF</b> : Graphics Interchange Format
  -  <b>PNG(Portable Network Graphics)</b>: PNG 8 equivale a 258 colores y PNG 24 equivale a más de 256 colores.
  -  <b>SVG (Vector)( Scalable Vector Graphics )</b>: Se usan para pantallas de retina. Nunca pierden calidad.

<p align="center">
    <img src="https://static.platzi.com/media/user_upload/table%20for%20diferent%20images-42fdf349-a492-4ff5-afbd-1f437c804e4a.jpg" width="100%">
</p>

		
Páginas donde encontrarás recursos gráficos gratuitos:


- [FlatIcon](https://www.flaticon.com/)
- [Freepik](https://www.freepik.es/)
- [Unsplash](https://unsplash.com/)
- [Pexels](https://www.pexels.com/es-es/)
  
<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Etiqueta img <a name="img"></a>

La Etiqueta `<img>` nos va a permitir insertar una imagen
```HTML
<img src="" alt="" title="" width="" >

```

- `<img>`: Nos ayuda a renderizar las imágenes
 
-  `src=""`: Indicar donde está la imagen, puede ser desde nuestras carpetas o desde una URL
 
- `alt=""`: Descripción de la imagen que aparecerá cuando la imagen no se logre renderizar(enfocado en temas de accesibilidad)

- `title=""`: No es exclusivo para imágenes, sirve para cualquier elemento HTML, lo que hace es agregar un título que será visible cuando se pose el puntero del mouse sobre el elemento
 
- `width=""`: Representa el ancho de la imagen. También existe el atributo height que representa el alto de la imagen. Los valores de estos atributos se pueden dar en pixeles(px) o porcentaje(%).


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Etiqueta figure <a name="figure"></a>

La etiqueta figure genera un contenedor para la imagen y nos permite agregar varias de estas.

```HTML
<figure> 

  <img src="" alt="" title="" width=""> 
  <figcaption>Descripción de imagen</figcaption> 

  <img src="" alt="" title="" width=""> 
  <figcaption>Descripción de imagen</figcaption> 

</figure>
```
- `<figcaption>`: Agrega una descripción a la imagen que será visible en la parte inferior de esta.

Es importante saber que la etiqueta `<figure> ` no es únicamente para imágenes, representa contenido independiente, a menudo con un título,  en este caso semánticamente no es corrector utilizar o insertar una imagen dentro de un div,  lo correcto es utilizar esta etiqueta contenedora, `<figure> `.


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Etiqueta video <a name="video"></a>

La etiqueta video es la que nos permite subir un video.

```HTML
<video src="" width="" controls preload="auto"></video>

```

- `src=""`: Atributo que tiene como valor la dirección/ubicación del video
                
- `controls`: Es un atributo que no tiene valor, sirve para activar los controles de vídeo.
                
- `preload="auto"`: Permite que el video se empiece a renderizar cuando la página se empiece a crear en el navegador, esto es para que no haya mucho tiempo de espera al reproducir el video.


```HTML
<video width="" controls preload="auto">

	<source src="ejemplo.wmv"> 
	<source src="ejemplo.mp4">
	
</video>
```

- `<source>`:  Va dentro de la etiqueta `<video>` y se usa para especificar varias rutas en caso de que el navegador  no entienda algún formato de vídeo. Se pueden poner varios formatos y el navegador usará el que más le convenga. Para usarlo se elimina el atributo `src=""` de la etiqueta `<video>` y se  pone la etiqueta` <source>` con su respectivo atributo`src=""`. 

```HTML
<video src="ejemplo.mp4#t=14,263" width="" controls preload="auto"></video>
```
- Si queremos que el vídeo inicie y termine en un tiempo específico, debemos usar  `#t=n,n`  al final de la ruta del video:

	- `#t=`: Indica el tiempo en el cual empezará y terminará la reproducción del video.
	
	- `14,263`: Son los valores en segundos. Donde 14 es el segundo en el que inicia y 263 es donde finaliza la reproducción del video. Estos valores deben ir separados solo por una coma.


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Formularios <a name="formularios"></a>

<p align="center">
    <img src="https://static.platzi.com/media/user_upload/Carrusel-html-08-4d0e4b19-5dbc-493d-91d8-0aafc5877571.jpg" width="70%">
</p>


Los formularios son la forma en la cual podemos empezar a generar interacción con los usuarios.

Se dice que <strong>"El mejor formulario, es cuando no lo hay"</strong> esto, ya que para el usuario el llenar o completar un formulario se vuelve tedioso haciendo que en muchas ocasiones termine abandonando nuestra página, es por eso que debemos generar buenos formularios para los usuarios, cortos, fáciles de usar y directos.


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Etiqueta form e input <a name="form-input"></a>

Para crear un formulario haremos uso de la etiqueta `<form>`

```HTML
<form action=""> 
	<label for="nombre-es"> 
    <span>¿Cuál es tu nombre?</span> 
    <input type="text" id="nombre-es" placeholder="Nombre"/> 
	</label> 
              
	<label for="inicio-platzi"> 
    <span>¿Qué día comenzaste en Platzi?</span> 
    <input type="date" id="inicio-platzi"/> 
	</label> 
              
	 <label for="horario"> 
      <span>¿En que horario estudias?</span> 
      <input type="time" id="horario"/> 
	</label> 
</form>
```

- `<form>`: Es semántico, nos permite decirle al navegador que  usaremos  un formulario y que el usuario va a interactuar con él. Es una etiqueta contenedora.
 
- `action=""`: Aquí es donde se colocaría la URL o base de datos a donde se va a enviar la información.
 
- `<label>`: Es una etiqueta contenedora de input. Recibe un atributo importante llamado for que debe ser el mismo que el id del input.
 
- `<span>`: es un contenedor en línea que se utiliza para marcar una parte de un texto, o una parte de un documento.

- `<input>`: se usa para crear controles interactivos para formularios, nos permite recibir datos del usuario.

- `type=""`: Sirve para definir el tipo de nuestro input

- `placeholder=""`: Agrega información dentro del input. Se utiliza para indicarle al usuario un ejemplo sobre lo que debe llenar. 

<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


##  Calendario <a name="calendario"></a>

Para hacer calendarios con la etiqueta `<form>` hay 2 formas:

<b>Forma Compleja</b>: Tenemos el control de que datos queremos recaudar
 
```HTML
<form action="">

  <label for="hora">
    <span>Hora</span>
    <input type="time" id="hora" name="hora"/>
  </label>

  <label for="dia">
    <span>Día</span>
    <input type="date" id="dia" name="dia"/>
  </label>

  <label for="semana">
    <span>semana</span>
    <input type="week" id="semana" name="semana"/>
  </label>

  <label for="mes">
    <span>Mes</span>
    <input type="month" id="mes" name="mes"/>
  </label>

  <input type="submit"/>

</form>

```

- `name=""`: Es el nombre del control, el cual es enviado con los datos del formulario.
-  `<input type="submit"/>`: Es un tipo de input que sirve para envíar el formulario.


<b>Forma sencilla</b>: Datos a recaudar preestablecidos, genera un formato de fecha con día, mes, año y hora

```HTML
<form action=""> 

      <label for="calendario"> 
        <span>Calendario</span> 
        <input type="datetime-local" id="calendario" name="calendario"/> 
      </label> 
       
      <input type="submit"/> 

</form>
```


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Autocomplete y require <a name="autocomplete-require"></a>

```HTML
<form action="">
	<label for="nombre">
		<span>¿Cuál es tu nombre?</span>
		<input type="text" placeholder="Nombre" name="nombre" id="nombre" autocomplete="name" required/>
	</label>
</form>
```
- `autocomplete`: Completa el input con los datos que tenga guardado el navegador del usuario. Recibe valores dependiendo de lo que busquemos autocompletar como por ejemplo name, email, address, <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">entre otros</a>. Es útil para que el usuario no tenga que volver a llenar los datos que ya ha dado en otros formularios  

- `require`: Le indica al usuario que debe rellenar la información de los campos, Si no lo llena, no podrá enviar el formulario o avanzar.

<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Select <a name="select"></a>

Hay 2 formar de crear una lista para seleccionar entre varias opciones. 

<b>Sin Scroll</b>

```HTML
<select name="cursos" id=""> 

	<option value="JavaScript">JavaScript</option> 
	<option value="HTML5">HTML5</option> 
	<option value="CSS3">CSS3</option> 
	<option value="Web Standards">Web Standards</option>
	 
</select>
```
- `<select>`: Sirve de contenedor para la etiqueta `<option>`, la cual muestra los valores de la lista que crea `<select>`.

- `value=""`:  debe ser igual al nombre de la opción, ya que el valor que tenga  es lo que se va a guardar y enviar a la base de datos, sin este atributo la opción seleccionada se enviaría en cero.

<b>Con Scroll</b>

```HTML
<input list="cursos-2.0"/> 
<datalist id="cursos-2.0"> 

	<option value="Java"></option> 
	<option value="Python"></option> 
	<option value="Ruby"></option> 
	<option value="Go"></option> 
	<option value="SQL"></option> 
	<option value="C"></option> 
	<option value="C#"></option> 
	<option value="C++"></option> 
	
</datalist>
```

- `<datalist>` junto a `<input>` le permite al usuario buscar en caso de que la lista sea muy larga o escribir dentro del input, y filtrar los resultados de la lista.

- Con `<datalist>` no hay necesidad de colocar texto(Contenido de la etiqueta `<option>`), ya que lo que haya en `<value>` es lo que se mostrara en pantalla.

<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Input type submit vs Button Tag <a name="input-button"></a>

Podemos crear botones de dos maneras diferentes

1. Usando`<input type="submit"/>`

```HTML
<input type="submit" value="Enviar a base de datos"/>
```

- `value=""`: Nos permite cambiar el mensaje del botón que tiene por defecto.

2. Usando `<button type="submit">`

```HTML
<button type="submit"> 
	Enviar formulario 
</button>
```
- `type="submit"`: Permite que  el botón se pueda utilizar en formularios 

Básicamente, debemos usarlos así:
 
- <b>Input type submit</b>:  Lo utilizaremos solo en los formularios.
 
- <b>Button</b>: Lo utilizaremos en cualquier otro tipo de botón dentro de nuestro proyecto.


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## HTML Cheat Sheet <a name="HTML-Cheat-Sheet"></a>

<p align="center">
    <img src="https://static.platzi.com/media/public/uploads/sheet-html_78e6f04d-2ecb-472a-a36c-582b9fc4fb6f.png" width="100%">
</p>


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>









