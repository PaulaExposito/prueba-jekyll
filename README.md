# Handling Events
## DSI-Práctica 4

### 1. Leer capítulo 15 de Eloquent JavaScript y generar unos apuntes asociados

#### Principales eventos

* Eventos de teclado: keypress, keydown, keyup
* Eventos de ratón: mousedown, mouseup, click, dblclick, mousemove
* Eventos touch: touchstart, touchmove, touchend
* Eventos de scroll: scroll
* Eventos de foco: focus, blur
* Eventos de carga: load, beforunload

### 2. Ejercicios

1. Censored keyboard: program a text field (an input tag) where the letters Q, W, and X cannot be typed into.

<img src="./images/ejer1.png">

2. Mouse trail: a series of images that would follow the mouse pointer as you moved it across the page.

<img src="./images/ejer1.png">

3. Tabs: A tabbed interface. It allows you to select an interface panel by choosing from a number of tabs sticking out above an element. 

<img src="./images/ejer3-1.png">
<img src="./images/ejer3-2.png">


### 3. Experiencia usando Jekyll y GitHub Pages

Jekyll me ha parecido bastante sencillo e intuitivo de usar, dando resultados visibles. Lo único de lo que podría quejarme es de que no es fácil encontrar documentación sobre cómo conseguir poner imágenes y que se vean en los fihecros .markdown. En diferentes blogs y discusiones se dan soluciones contradictorias y que no funcionan, y la página oficial donde se encuentra la solución no sale en las primeras opciones del buscador y tampoco está bien señalizado en la página oficial. 

GitHub Pages es un poco más lioso de usar. No se ve como yo esperaba ya que no es interactivo como Jekyll, es sólo un html con el README.md. Pero poder ponerle diferentes temas le da un aspecto mucho mejor. [Tutorial](https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll#creating-your-site).

[GitHub Pages](https://ull-esit-dsi-1920.github.io/p3-t2-handling-events-PaulaExposito/)
[Jekill](https://127.0.0.1:4000)

Para ejecutar Jekill hay que tener corriendo el servidor en el directorio /handlings-events-sites/ con el comando `bundle exec jekyll server`.


### 4. HTML Proofer y Travis CI

Esta herramienta valida la salida de ficheros HTML. Por ejemplo, comprueba que los links que se referencian en el .html son válidos.

<img src="./images/htmlproofer.png">


Travis CI se encarga de la integración continua del proyecto.

<img src="./images/travis.png">





    

