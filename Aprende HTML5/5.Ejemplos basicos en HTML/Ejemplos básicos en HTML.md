# Ejemplos básicos en HTML 
En este capítulo mostraremos algunos ejemplos básicos de __HTML__.

No se preocupe si utilizamos etiquetas que aún no conoce.

## Documentos HTML
Todos los documentos __HTML__ deben de comenzar con una declaración de tipo documento `<!DOCTYPE html>`.

El documento __HTML__ en sí comienza `<html>` y termina con `</html>`. La parte visible del documento __HTML__ está entre `<body>` y `</body>`.

_Ejemplo:_
`
~~~
<!DOCTYPE html>
    <html lang="es">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
        <title>Document</title>
    </head>
    
    <body>
        <h1>My first heading</h1>
        <p>My first paragraph.</p>
    </body>
</html>
~~~

## La declaración `<!DOCTYPE >`
La declaración `<!DOCTYPE>` representa el tipo de documento y ayuda a los navegadores a mostrar las páginas web correctamente. Sólo debe aprarecer una vez , en la parte superior de la página (antes de cualquier etiqueta __HTML__).

La declaración `<!DOCTYPE>` no distingue entre mayúsculas y minúculas.

La declaración `<!DOCTYPE>` para __HTML5__ es :
~~~
<!DOCTYPE html>
~~~

***
## Encabezados en HTML 
Los encabezados HTML se definen con las etiquetas `<h1>` a `<h6>`

`<h1>` define el título más importante. `<h6>` define el encabezado menos importante.

~~~
<h1> This is heading 1 </h1>
<h2> This is heading 2 </h2>
<h3> This is heading 3 </h3>
<h4> This is heading 4 </h4>
<h5> This is heading 5 </h5>
<h6> This is heading 6 </h6>
~~~

***
## Párrafos en HTML 
Los párrafos en __HTML__ se definen mediante la etiqueta `<p>`:

_Ejemplo:_
~~~
<p> This is a paragraph.</p>
<p> This is another paragraph.</p>
~~~

***
## Enlaces en HTML
Los enlaces en __HTML__ se definen con la etiqueta `<a>` 

~~~
<a href='www.Google.com'>This is a link</a>
~~~
-   El destino del enlace se especifica en el atributo `href`
-   Los atributos se utiliza para proporcionar información adicional sobre los elementos __HTML__.
-   Aprendá más sobre los atributos en el capítulo posterior.

***
## Imagenes en HTML
Las imagenes __HTML__ se definen con la etiqueta `<img>`. El archivo fuente (`scr`), el texto alternativo (`alt`),(`width`) y (`height`) se proporcionan como atributos:

~~~
<img src='Logo.jpg' alt='Logo empresa ' width='104' heigth='142'>
~~~

***
## Cómo ver el código fuente HTML
¿Alguna vez has visto una página web y te has preguntado: "¡Oye! ¿Cómo hicieron eso?"

### Ver código fuente HTML:
Haga clic en CRTL + U en una página __HTML__, o haga clic derecho en la página y seleccione "Ver código fuente de la página". Esto abrirá una nueva pestaña que contiene el código fuente __HTML__ de la página.

### Inspeccionar un elemento HTML 
Haga clic derecho en un elemento( o en un aréa en blanco) y elija "Inspeccionar" para ver qué elementos están compuestos (verá tanto el __HTML__ como el __CSS__). También puede editar __HTML__ o __CSS__ sobre la marcha en el panel "Elementos" o Estilos que se abre.   
