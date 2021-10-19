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



## ¿Qué es Frontend?<a name="Qué-es-Frontend"></a>

Frontend es la parte de un programa o dispositivo a la que un usuario puede acceder directamente. Son todas las tecnologías de diseño y desarrollo web que corren en el navegador y que se encargan de la interactividad con los usuarios y el frontend developer es el que va a manejar las cosas del lado del cliente, las interacción que tienes en una página web, las animaciones y los estilos.

<figure align="center">
    <img src="https://i.imgur.com/uWJngOH.png" width="100%">
</figure>

Para convertirse en Frontend Developer principalmente se debe entender y dominar perfectamente estos tres estándares Web:
 
- HTML Y CSS: los lenguajes de maquetación que permiten definir la estructura y estilos de una página web.
-  JavaScript: el lenguaje de programación que servirá para  definir la lógica de nuestra aplicación, recibir las solicitudes de los usuarios y enviárselos al backend.

Dominando estas tecnologías ya se puede escalar a algunos frameworks, librerías o preprocesadores los cuales expanden las capacidades para crear todo tipo de interfaces de usuario. Algunos de ellos son:

<strong>Frameworks de CSS</strong>
- Bootstrap https://getbootstrap.com/
- Foundation CSS https://get.foundation/
- Materialize CSS https://materializecss.com/

<strong>Frameworks y Librerías de JS</strong>
- React JS https://es.reactjs.org/
- Angular JS https://angular.io/
- Vue JS https://vuejs.org/

<strong>Preprocesadores de CSS:</strong>
- stylus https://stylus-lang.com/
- SASS https://sass-lang.com/
- less https://lesscss.org/

<strong>Compiladores / empaquetadores de JS</strong>
- BABEL https://babeljs.io/
- Webpack https://webpack.js.org/


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>

## ¿Qué es Backend?<a name="¿Qué-es-Backend?"></a>

Backend es la capa de acceso a datos de un software o cualquier dispositivo,  no es directamente accesible por los usuarios, además contiene la lógica de la aplicación que maneja dichos datos. El Backend también accede al servidor, que es una aplicación especializada que entiende la forma como el navegador solicita cosas.

<figure align="center">
    <img src="https://i.imgur.com/s9Iia0t.png" width="100%">
</figure>

Un Backend Developer es lo opuesto a lo que hace un frontend, pues este es aquel que trabaja del lado del servidor manejando toda la lógica que hay detrás de una petición dada por el navegador.

Para Backend Developer no hay un estándar definido, ya que tiene varios lenguajes de programación y varias tecnologías con las que se puede trabajar.

Algunos de los lenguajes de programación para Backend son:
 
- Python https://www.python.org/
- Node.js https://nodejs.org/en/
- PHP https://www.php.net/
- java https://www.java.com/es/
- Ruby https://www.ruby-lang.org/en/
- Go https://golang.org/
- C# https://docs.microsoft.com/en-us/dotnet/csharp/


Y así como en el frontend, todos estos lenguajes tienen diferentes frameworks que  permiten trabajar mejor según el proyecto que se este desarrollando, como:
 
- Django https://www.djangoproject.com/
- express https://expressjs.com/es/
- laravel https://laravel.com/
- spring https://spring.io/
- RAILS https://rubyonrails.org/

El Backend Developer también tiene que tener en cuenta la infraestructura, donde va a generar el deploy de su aplicación (esto también puede ser tarea de un DevOps, un perfil dedicado a la infraestructura). Con tecnologías como:

- Google Cloud https://cloud.google.com/
- DigitalOcean https://www.digitalocean.com/
- amazon aws https://aws.amazon.com/es/
- HEROKU https://www.heroku.com/

Por último, debe conocer de bases de datos relacionales y bases de datos no relacionales, generar la arquitectura y conectarla según el lenguaje que este trabajando, algunas de estas bases de datos son:
 
- mongo DB https://www.mongodb.com/es
- MySQL https://www.mysql.com/
- PostgreSQL https://www.postgresql.org/


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>

## ¿Qué es Full Stack Developer?<a name="¿Qué-es-Full-Stack-Developer?"></a>


Un  Full Stack Developer es la fusión de un  Frontend Developer y todas las cosas que hace un Backend Developer  en una sola persona, un full stack Developer no maneja por completo todas las tecnologías de ambas partes, de hecho no es recomendado y no es sano, ya que el desarrollo web evoluciona muy rápido y cada dos o tres meses tenemos algo nuevo.
 
<figure align="center">
    <img src="https://2.bp.blogspot.com/-ysM3KQvoT6M/WpSGL0Ho3yI/AAAAAAAAbsg/ca2Oof_vW0osVFHU6ratej9xpz94V7YHwCLcBGAs/s1600/frontend%2Bbackend.jpg" width="100%">
</figure>

Realmente un full stack es alguien que entiende muy bien cómo funciona un producto web de principio a fin, desde que esta en idea en forma de mockup hasta la liberación de la aplicación a producción. Entiende las tecnologías de que se usan tanto en el Frontend como en el Backend pero se especializa en una  área especifica.
 

<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Páginas Estáticas vs. Dinámicas <a name="Páginas-Estáticas-Dinámicas"></a>

<figure align="center">
    <img src="https://i.imgur.com/WZUTphN.png" width="100%">
</figure>

#### PÁGINAS ESTÁTICAS

La información que contienen, se mantiene constante y estática. No se actualiza con la interacción del usuario y serán siempre iguales para todos los usuarios por lo que no estan conectadas a una base de datos, ya que los cambios solo se generan en el servidor.

Este tipo de paginas es conveniente para Páginas informativas o Blogs.

ejemplos:
 
- https://million-devs.netlify.com
- https://www.imuniapp.com
- https://marvlm.github.io/tdd-infographic/

#### PÁGINAS DINÁMICAS

Dejan de ser paginas y se convierten mas en aplicaciones, actualizan su información con respecto a la interacción del usuario y  serán diferentes dependiendo del usuario que la use y dependen de una base de datos, de donde extrae e ingresa información
	 
- https://www.facebook.com/
- https://platzi.com
- https://twitter.com/


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## ¿Qué es HTML? <a name="que-es-html"></a>

HTML es un lenguaje interpretado, es el código que se utiliza para estructurar el contenido de una web,  darle sentido y propósito. es un estándar, así que no importa desde que navegador, que dispositivo se ejecute, el código sigue siendo el mismo.

HTML son las siglas de Hyper Text Markup Language(Lenguaje de Marcado de Hipertexto). 
- Hyper Text  significa que el texto tiene interactividad, conexión con otros documentos. 

- Markup significa que le pone etiquetas a los elementos.Por eso también se le conoce como un lenguaje de etiquetas. 


## Anatomía de una página web <a name="anatomía-página-web"></a>

Esta es la anatomía que vamos a encontrar en la mayoría de páginas web.

<figure align="center">
    <img src="https://i.imgur.com/Arj4X0j.png" width="100%">
</figure>

- Container:  Contenedor principal
- Header: Cabecera de la página
- Main content: Estructura principal, por ejemplo el post de un red social.
- Sidebar:  Contenido secundario de una página.
- Footer:  Pie de página.

Ejemplo:

<figure align="center">
    <img src="https://i.imgur.com/fuozodm.png" width="100%">
</figure>


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

la primera pagina o archivo HTML debe ser nombrada como index.html ya que va a ser la pagina inicial la cual el servidor va a buscar al momento de abrir un proyecto, si esta pagina no existe debemos especificarle al servidor que pagina debe tomar como inicio.

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

•  <!DOCTYPE html>:  Le indica al navegador que todo el código que contiene este archivo es HTML5.
 
• <html lang="es">: Es la etiqueta "padre" donde vivirá nuestro proyecto. El atributo lang establece el idioma de sitio web. Debemos usarlo para que el navegador pueda traducir nuestra página
 
• <head></head>: En el head van todos los archivos importantes para el correcto funcionamiento de nuestro proyecto, pero que no son visibles por los usuarios. Algunos de estos archivos pueden ser:

	○ Frameworks
	○ Librerías
	○ Estilos
	○ CSS
	○ Fuentes
	○ APIs
 
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


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Index y su estructura básica: body <a name="body"></a>

Existen dos tipos de etiquetas en body:

-  Etiquetas de contenido: Son las encargadas de mostrar texto, imágenes, videos, cualquier cosa que se vaya a renderizar en el proyecto

- Etiquetas contenedoras: Son las que nos van a permitir darle estructura, organizar nuestro contenido, generar la maquetación o layout de nuestro proyecto

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

Mas etiquetas y elementos de HTML  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element" target="_blank">aquí</a>


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>


## Anatomía de una etiqueta HTML  <a name="anatomia-html-tag"></a>

<figure align="center">
    <img src="https://i.imgur.com/wafq4Om.png" width="100%">
</figure>

#### Apertura y cierre

La apertura y el cierre siempre llevan el nombre de la etiqueta HTML que usarás, y son las que sirven para delimitar el contenido de la misma.


#### Atributo y valor

El atributo son distintos ingredientes o modificaciones que puedes hacer a la etiqueta. Como por ejemplo colocarle un ID, especificar algún evento (como los casos de onsubmit y onclick ), o modificar el aspecto visual (como cambiarle el color a un texto).

El valor es la especificación de estas modificaciones. ¿Qué debe suceder después del onsubmit? ¿Qué color debe tener el texto? ¿Qué ID tendrá la etiqueta?


#### Contenido

El contenido de la etiqueta es la información que queremos que sea afectada por la etiqueta con sus modificaciones (atributos).


<div align="right">
  <small><a href="#tabla-de-contenido--">&uarr; volver al inicio</a></small>
</div>

