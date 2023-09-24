<div align="center">
  <img  align="center" src="https://github.com/Brayan-Hc11/devicon/blob/master/icons/html5/html5-original-wordmark.svg" width=80px">

  # Ruta de aprendizaje para HTML

</div>



<details>
  <summary>
    INICIO en HTML
  </summary>

***
- HTML es el lenguaje de marcado para las paginas web.
- Con HTML puedes crear tu propio sitio web.
- HTML es fácil de aprender 
***
</details>

<details>
  <summary>
    Introducción a HTML
  </summary>

***
HTML es el lenguaje de marcado estándar para crear páginas web.

***
## ¿Qué es HTML?

- HTML quiere decir Hipertext Markout Languje o por su traducción a lenguaje de marcado de hipertexto.
- HTML es el lenguaje de marcado estándar para crear páginas web.
- HTML describe la estructura de una páguina web.
- HTML consta de una serie de elementos.
- Los elementos de HTML le indican al navegador como mostrar el contenido.
- Los elementos de HTML etiqutan piezas de contenido como "este es un encad¿bezado", "este es un párrafo","esto es un enlace", etc.

***
## Un documento HTML simple

_Ejemplo:_

~~~
<!DOCTYPE html>
  <html>
    <head>
      <title>Page Title</title>
    </head>

  <body>

  <h1>My First Heading</h1>
    <p>My first paragraph.</p>

  </body>
</html>
~~~

_Proceso de ejecución:_
~~~
1. La etiqueta semantica __("<!DOCTYPE html>")__ define que este documento es un documento HTML.
2. El elemento __<html>__ es el elemento raiza de al pagina HTML.
3. El elemento __<head>__ es el elemento que contiene la metainformación de la página HTML.
4. El elemento __<title>__ es el elemento que especifica un título para la página HTML(este se muestra en la barra del título del navegador o en la pestaña de la página).
5. El elemento __<body>__ es el elemento que define el cuerpo del documento y es un contenedor de todos los coneidos visibles, como encabezados, párrafos, imagenes, hipervinculos, tablas, listas, etc.
6. El elemento __<h1>__ es el elmento que define un encadezado grande.
7. El elemento __<p>__ es el elemento que define un párrafo.
~~~
***

## ¿Qué es un elemento HTML 
Un elemento se define mediante una etiqueta de inicio, algo de contenido y una etiqueta de finalización. El elemento HTML es todo, desde la etiqueta de inicio hasta la etiqueta final.

|Inicio|Contenido         |Final|
|------|------------------|-----|
|h1    |My first heading  |/h1  |
|p     |My first paragraph|/p   |
|br    |none              |none |

__Nota:__ Algunos elementos HTML no tienen contenido (como el elemento br). Estos elementos se denominan elemntos vacíos. Los elementos vacíos no tienen etiqueta final.

***
## Navegadores web
El propósito de un navegador web (Chrome, Edge, Firefox, Safari) es leer documentos HTML y mostrarlos correctamente. Un navegador no muestra las etiquetas HTML, pero las usa para determinar cómo mostrar el documento:

![image](https://github.com/Brayan-Hc11/HTML5/assets/118775234/add05f1b-d67c-412d-b701-1b5fc87e7c5f)

## Estructura de al página HTML

A continuación se muestra una vizualización de la estructura de una página HTML:

![image](https://github.com/Brayan-Hc11/HTML5/assets/118775234/70a99fe6-7f74-4f7d-afcd-0d0b82defff5)

__Nota:__ El contenido al interior de la sección ´body' se mostrará en un navegador. El contenido dentro del elemento 'title' se mostrará en la barra de título del navegador o en la pestaña de la página.
</details>

<details>
  <summary>
    Editores en  HTML
  </summary>

  ***
  Un simple editor de texto es todo lo que se necedita para aprender HMTL.

  ## Aprenda HTML atraves del Bloc de notas o un Editor de texto
  Las páginas web se pueden crear y modificar utilizando editores HTML profesionales. Sin embargo, para apreder HTML recomiendo un editor de texto simple como Notepad para (PC).

  Creeemos que usar un editor de texto simple es una buena manera de aprender HTML.
  ***
</details>

<details>
  <summary>
    HTML básico
  </summary>

  ***
  ## Ejemplos básicos de HTML

  En este apartado mostraremos unos ejemplos básicos de HTML 

  ***
  ## Documentos HTML 

  Todos los documentos HTML deben comenzar con una declaración de tipo documento:
  ~~~
<!DOCTYPE html>
  ~~~

  El documento HTML es sí comienza con la etiqueta de apertura y finaliza con la etiqueta de cierre:
  ~~~
<html>

</html>
  ~~~

El contenido visual del documento HMTL está entre la etiqueta de cuerpo o de body
~~~
<body>

</body>
~~~

***
## Uso de la declaración !DOCTYPE

La declaración representa el tipo de documento y ayuda a los navegadores a mostrar correctamente las páginas web. Solo debe aparecer una vez, en la parte superior de la página (antes de cualquier etiqueta HTML).

La declaración no distingue entre mayúsculas y minúsculas.

_Declaración de la estructura es:_
~~~
<!DOCTYPE html>
~~~

***
## Encabezados en HTML

Los encabezados HTML se defienen con las etiquetas h1 a h6 que representas las diferentes escalas de encabezados en HTML

~~~
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h5></h5>
~~~

***
## párrafos en HMTL

Los párrafos en HTML se definen con la etiqueta p que nos ayuda a contener los párrafos 

~~~
<p>This is a Paragrph.</p>
<p>This is another Paragrph</p>
~~~

***
## Enlaces en HTML 

Los enlaces en HTML se definen con la etiqeuta a 

~~~
<a href="dirección de url">This is a link</a>
~~~
_Nota:_ El destino del enlace se especifica en el atributo href. Los atributos se utilizan para poporcionar infromación adicional sobre los elmentos HTML.

***
## Imagenes en HTML 

Las imagenes en HTML se definen con la eeiqueta de img 

El archivo de origen _scr_, el texto alternativo _alt_, y las propiedades _width_ y height se proporcionan como atibutos en la etiqueta
~~~
<img src="dirección de la imagen" alt="texto alternativo" width="104" height="142">
~~~

***
</details>

<details>
  <summary>
    Elementos en HTML
  </summary>

  ***
  Un elemento HTML se define mediante una etiqueta de inicio, aldo de contenido y una etiqueta de cierre.

  ***

  ## Elementos HTML

  __El elemento HTML__ es todo, desde la etiqueta inicial hasta la etiqueta final:
  
  ~~~
<Nombre de la etiqueta> El contenido va aquí </Nombre de la etiqueta>
  ~~~

***
## Elementos HTML anidados

Los elementos HTML se pueden anidar(esto significa que los elementos pueden contener otros elementos).
Todos los elementos HTML constan de elementos HTML anidados.

El siguiente ejemplo contiene cuatro elementos HTMl

__Ejemplo:__

~~~
<!DOCTYPE html>
<html>
  <body>
    <h1>My First Heading</h1>
    <p>My First Parragraph.</p>
  </body>
</html>
~~~

__Proceso de ejecución:__

El elemento `<html>` es el elemento raiz y define todo el documento HtML.

Tiene una etiqueta de inicio `<html>` y una etiqueta de cierre `</html>`.

Entonces dentrol del elemento `<html>` hay un elemento `<body>`:

~~~
<body>
  <h1>My First Heading</h1>
  <p>My First paragraph.</p>
</body>
~~~

El elemento `<dody>` define el cuerpo del documento.

Tiene una etiqueta de inicio `<doby>` y una etiqueta de cierre `</body>`.

Luego, dentro del elemento `<body>` hay dentro otros dos elementos: `<h1>` y `<p>`:

~~~
<h1>My First Heading</h1>
<p>My First Paragraph.</p>
~~~

El elemento `<h1>` defiene un encabezado.

Tiene una etiqueta de inicio `<h1>` y una etiqueta final `</h1>`:

~~~
<h1>My First Heading</h1>
~~~

El elemento `<p>` define un párrafo.

Tiene una eitiqueta de inicio `<p>` y una etiqueta final `</p>`:

~~~
<p>My First paragraph.</p>
~~~

***
## Nunca te saltes la etiqueta final
Algunos elementos HTML se mostrarán correctamente, incluso si olvida la etiqueta final:

__Ejemplo:__

~~~
<html>
<body>

  <p>This is a Paragraph
  <p>This is a Paragraph

</body>
</html>
~~~

Sin embargo, ¡Nunca confies en esto! ¡Puede ocurrir errores y resultados inesperados si olvida la etiqueta final!
</details>

<details>
  <summary>
   Atributos en  HTML
  </summary>

  ***
</details>

<details>
  <summary>
   Encabezados en HTML
  </summary>

  ***
</details>

<details>
  <summary>
     Párrafos en HTML
  </summary>

  ***
</details>

<details>
  <summary>
    Estilos en HTML
  </summary>

  ***
</details>

<details>
  <summary>
    Formatos en HTML
  </summary>

  ***
</details>

<details>
  <summary>
   Cotizaciones en HTML
  </summary>

  ***
</details>

<details>
  <summary>
    Comentarios en HTML
  </summary>

  ***
</details>

<details>
  <summary>
    Colores en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    CSS en HTML
  </summary>

  ***
</details>

<details>
  <summary>
    Enlaces en HTML
  </summary>

  ***
</details>

<details>
  <summary>
   Imagenes en HTML
  </summary>

  ***
</details>

<details>
  <summary>
    Icono de favoritos en HTML
  </summary>

  ***
</details>

<details>
  <summary>
    Título de la página en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Tablas en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Listas en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
   Bloques en HTML y líneas 
  </summary>

  ***
</details>

<details>
  <summary>
    Clasee en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Identificación en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Marcos flotantes en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    JavaScript en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Rutas de archivo en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
  Encabezados en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Diseño en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Responsive en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Código informático en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Semenaticá en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Guía de estilos en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Entidades en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Símbolos en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Emoticones en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Juego de carácteres en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    Codificación de url en HTML 
  </summary>

  ***
</details>

<details>
  <summary>
    HTML frente a XTHML 
  </summary>

  ***
</details>

<!--
***
### Formularios HTML
- Formularios HTML
- Atributos de formulario HTML
- Elementos de formulario HTML
- Tipos de entrada HTML
- Atributos de entrada HTML
- Atributos de formulario de entrada HTML

***
- Gráficos HTML
- Lienzo HTML
- HTML SVG

***
- Medios HTML
- Medios HTML
- Vídeo HTML
- Audio HTML
- Complementos HTML
- HTML de YouTube

***
- API de HTML
- Geolocalización HTML
- Arrastrar/soltar HTML
- Almacenamiento web HTML
- Trabajadores web HTML
- SSE HTML

***
- Ejemplos HTML
- Ejemplos HTML
- Editor HTML
- Cuestionario HTML
- Ejercicios HTML
- Campamento de entrenamiento HTML
- Certificado HTML
- Resumen HTML
- Accesibilidad HTML

***
- Referencias HTML
- Lista de etiquetas HTML
- Atributos HTML
- Atributos globales HTML
- Compatibilidad con navegador HTML
- Eventos HTML
- Colores HTML
- Lienzo HTML
- Audio/vídeo HTML
- Tipos de documentos HTML
- Conjuntos de caracteres HTML
- Codificación de URL HTML
- Códigos de idioma HTML
- Mensajes HTTP
- Métodos HTTP
- Convertidor PX a EM
- Atajos de teclado
-->
