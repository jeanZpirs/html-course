# Curso de HTML y CSS.

Aprenderemos a crear aplicaciones web con html y css.
Este README servirá para tomar apuntes de cada lección.

## Resumen del desarrollo web.

Cuando buscamos una página o navegamos por internet siempre se realiza una petición a un servidor, este servidor según que tipo de página sea la que estés buscando se encargará de darte los archivos HTML, CSS Y JavaScript necesarios para que el navegador te pueda mostrar la página.

Existen dos lados diferentes del desarrollo web, la parte Fron-end y la parte Back-end.

- El Front-end se encarga de la parte visual, la parte del navegador.
- El Back-end es la parte del servidor, la que proporciona y maneja los datos.

En este curso veremos principalmente el Front-end que está conformado por HTML, CSS y JavaScript.

## ¿Qué es HTML?

<p>HTML significa Lenguaje de marcado de Hipertexto.<p>
Este lenguaje se utiliza para describir y estructurar el contenido de una página web. Sus elementos consisten en parrafos, enlaces, titulos, imagenes, videos, etc.

Los navegadores solo entiendo HTML y renderizan código HTML como páginas web.

Anatomía de un elemento HTML.
![Anatomy element](imgs_readme/anatomy-element.png)

## Estructura HTML

Su estructura principal se conforma por los elementos **html**, **head** y **body**.

El `<!DOCTYPE html>`se coloca para indicarle al navegador que utilice HTML5.

En el elemento **head** se pone información que le sirve al navegador o motores de busquedad y algunas configuraciones de la página.

En el elemento **body** se escribe todo lo que se va a ver en la página, es la parte que el navegador renderiza.

![Structure html](imgs_readme/structure-html.png)

## Elementos de tipo texto

Elementos de tipo texto nos permiten agregar contenido como parrafos, títulos, listas, etc:

- `<h1> </h1>`: Sirve para los titulos, teniendo niveles de titulos, `<h1>` sirve para el titulo más importante y hay hasta el `h6`, de más importante a menor.
- `<p> </p>`: Es para el texto simple, parrafos.
- `<strong> </strong>`: Marcar en negrita el contenido con importancia semantica.
- `<em> </em>`: Poner texto en cursiva con importancia semantica.
- `<ul>/<ol>`: Se usa para indicar una lista.
- `<li>`: Item que va dentro de un `<ul>` o `<ol>`.

Nota: Es importante tener el contenido siempre dentro de un elemento html correspondiente, el navegador lo reconocerá y ayudará al SEO.

## Elementos de tipo imagen

Los elementos de tipo imagen se utilizan para mostrar imagenes, mediante sus atributos se configura el path de la imagen, su texto alternativo en caso no cargue la imagen y sus dimensiones.

![Image Element](imgs_readme/img-element.png)

## Enlaces

Los enlaces sirven para poder anclar sitios web a nuestra web, podemos poner cualquier tipo elemento como un ancla donde hacemos click y nos lleva a la página que le hayamos asignado.

Tipos de anclaje:

- `#` -> Nos a una determinada posición de la página en la que estamos.
- `/archivo.html` -> Nos lleva a un archivo externo.
- `https://www.enlace.com` -> Nos dirige a otra web.

![HyperLink](imgs_readme/hyperlinks.png)
