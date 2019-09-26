# ¿Qué es HTML y CSS?

- **HTML** (Hypertext Markup Language) es un lenguaje de etiquetas, utilizado para definir la estructura de una página web.

- **CSS** (Cascading Style Sheets) es un lenguaje para definir el estilo de la página web. Refiriendonos a como se va a ver la página (*tamaños, colores, posición, etc...*).

###### Si quieres saber más, puedes visitar la [World Wide Web Consortium (W3C)](https://www.w3.org/standards/webdesign/htmlcss).
&nbsp;
![htmlycss](https://proxy.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.xhtmljunction.com%2Fblog%2Fwp-content%2Fuploads%2F2018%2F02%2Fhtml5-css3.png&f=1&nofb=1)
&nbsp;
# HTML
Podemos ver a **html** como el esqueleto de una página web, es el encargado de establecer que contenido va a tener la página en sí. 

En HTML se usan etiquetas, donde cada una tiene una de inicio y otra de cierre: `<etiqueta> </etiqueta>`. Las etiquetas de inicio se diferencían de las de cierre, por el slash `/` antes del nombre de la misma.

Existen etiquetas base para realizar un documento HTML, tales como `<html>`, `<head>`, `<title>` y `<body>`.

- La etiqueta principal, que envuelve básicamente todo, es la etiqueta `<html>`, dentro de esta etiqueta se debe de escribir todo el documento. 

- Dentro de la etiqueta `<head>` van datos que describen que usará el documento en sí, como un script, un archivo *.css*, el tipo de caracteres que se va a usar, el título de la pestaña, entre otras.

- En la etiqueta `<title>` se encontrará el título de la pestaña.

- La etiqueta `<body>` envuelve toda la página visible.

*Un ejemplo de una estructura html sería algo así:*

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title> Título de la página </title>
    </head>
    <body>
        <h1> Hola Mundo! </h1>
    </body>
</html>
```

Usamos el `<!DOCTYPE html>` para que el navegador sepa que se trata de un archivo **HTML5**, mientras que la etiqueta `<meta charset="utf-8">` especifica que tipo de caracteres (ASCII) vamos a manejar en el documento.

##### Ejemplos de etiquetas en HTML5
Etiqueta | Definición
:---: | ---
`<p>` | Establece un párrafo
`<div>` | Contenedor de elementos genérico
`<ul>` | Genera una lista sin órden
`<ol>` | Genera una lista con órden
`<li>`| Establece un elemento de una lista con o sin órden.
`<a>` | Establece un [link](#).
`<img>` | Inserta una imagen

###### HTML5 tiene muchísimas etiquetas, por ello, si quieres ver más etiquetas puedes visitar la [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) de Mozilla.
***
##### NOTAS:
> **ASCII**, abreviatura para American Standard Code for Information Interchange.
