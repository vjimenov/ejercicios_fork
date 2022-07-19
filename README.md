

#HTML / CSS | Clon de Spotify

## Introducción

A todo el mundo le gusta la música, ¿verdad? Lo más probable es que, si lo hace, haya oído hablar de Spotify. Hoy vamos a copiar una versión más antigua (y más simple) de la página de inicio de Spotify:

![Imagen de Spotify](https://i.imgur.com/xVD0bm6.jpg)

Todos los activos e imágenes necesarios están incluidos en el código de inicio. Si desea una versión completa en PDF del sitio web como referencia, [consulte este enlace](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/spotify-prototype.pdf ).

## Ejercicio

## Requisitos

- [Fork de este repositorio](https://guides.github.com/activities/forking/)
- Clone este repositorio en su `~/web/code/labs`
- Debes usar 1 selector descendiente, y 1 multiselector. Puedes usar más.
- Anime el logotipo verde de Spotify en la esquina superior izquierda para que salte hacia arriba y hacia abajo cuando un usuario pasa el cursor sobre él.

## Instrucciones de envío

Al finalizar, ejecute los siguientes comandos
```
$ git add .
$ git commit -m "done"
$ git push origin master
```
Navegue a su repositorio y cree una solicitud de extracción, desde su rama maestra hasta la rama maestra del repositorio original.

En el nombre del Pull Request, agregue su nombre y apellidos separados por un guión "-"

## Entregables

Recibirá las imágenes y los recursos en el código de inicio. Escriba su CSS y HTML en los archivos provistos. Recuerda seguir las buenas prácticas.

## Pasos

La página está dividida en 4 secciones.

#### Barra de navegación

- La barra de navegación debe ser `posición: fija`.
- Haga flotar la imagen a la izquierda y haga flotar un `ul` con los enlaces a la derecha.

#### Fondo de imagen grande con texto

- Consulta [esta guía](https://css-tricks.com/centering-css-complete-guide/) sobre cómo centrar las cosas.

#### Sección Qué hay en Spotify

- Parece que los `div` ocupan alrededor de un tercio del contenedor cada uno. ¿Cómo puedes representar esto en código?
