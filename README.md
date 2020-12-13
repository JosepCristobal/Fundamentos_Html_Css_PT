# Fundamentos Web: HTML5 y CSS3

Entrega de la práctica de este módulo del Bootcamp Web X

## Creación de un sitio web para una plataforma online de contenido digital.

### Consideraciones generales

* No se permite el uso de librerías y frameworks externos.
* Se crearán una o más hojas de estilo para aplicar el diseño deseado a la web.
* La página web debe visualizarse correctamente en los navegadores más populares.
* No se requiere interactuación mediante JavaScript.


### Descripción de la práctica
El objetivo de esta práctica es construir la estructura web de una plataforma de streaming de contenido digital al estilo de Netfix, HBO, etc. para distribuir series y películas a cualquier dispositivo que disponga de un navegador moderno. El público es de diferentes edades y condiciones y queremos que dispongan de la mejor experiencia de usuario, independientemente del tamaño de su pantalla.

Como se está buscando un producto mínimo viable, nos centraremos en tres pantallas.

#### Pantalla 1ª
Al llegar a la plataforma se debe mostrar un formulario de login para acceder al contenido. En este formulario deberemos implementar:

1. Un campo para el email, que servirá como nombre de usuario.
	* En este apartado, hemos creado un campo input tipo email y de tipo obligatorio.
	
2. Un campo para la contraseña.
	* Para la contraseña, hemos creado un input de este tipo para que sólo se muestren **** cuando se escribe. También es de tipo obligatorio.
	
3. Un botón para realizar el login y acceder al contenido.
	* En este caso, hemos creado un botón para acceder a la página principal de nuesta web.
	* Hemos añadido un check para que nos recuerde el usuario y la contraseña para futuras entradas. 
	
4. Un enlace para iniciar el proceso de recordar una contraseña olvidada.
	* Para este paso, hemos creado una pantalla modal, donde se nos requerirá que introduzcamos dos veces nuestra cuenta de correo para posteriormente enviarnos la nueva contraseña por email.
	* Se han creado dos botones, uno para enviar la petición y otro para cerrar sin efecto alguno.
	
También hemos añadido el logo de nuestra plataforma, llamada FILMS.
  
Adjuntamos una capturas de la pantalla login:
<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/login00.png?raw=true" alt="Formato móvil" width="500"/>
</p>

<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/login_recordar.png?raw=true" alt="Formato móvil" width="500"/>
</p>

#### Pantalla 2ª
Esta será la pantalla principal del contenido que contendrá, como mínimo, los siguientes elementos:

1. Un menú superior que deberá incluir el logotipo de la plataforma, opciones para acceder a las diferentes secciones, según las clasifiquemos, un formulario de búsqueda y la opción para poder cerrar la sesión.
	* Se ha creado una barra de menú que contiene todos los enlaces a las diferentes secciones y páginas.
	* Hemos añadido nuestro logo en formato imágen en la parte superior izquierda de la barra.
	* Se ha añadido un formulario de búsqueda con el input tipo type="search" y a continuación un botón en forma de imágen (lupa), para poder ejecutar la búsqueda.
	* A continuación, hemos situado un botón en formato imàgen (exit), que nos llevará a la página de login.
	* Todas estas opciones y la propia barra, las hemos adaptado para que se comporten de distinta forma cuando la visualización se realiza en pantallas pequeñas o bien en un dispositivo móvil.
	
2. Una rejilla de películas o series de forma que en cada elemento se muestre una miniatura de esta. Además, al situar el ratón encima se mostrará, sobre la miniatura, información adicional sobre la película o serie.
	* En este punto, hemos creado cuatro secciones para agrupar las diferentes clasificaciones de películas y en cada sección hemos añadido cinco carátulas de película.
	* Al situarnos con el ratón encima de cada carátula, se mostrará toda la infomación referente a la película. Todas las informaciones son reales y corresponden a cada una de las películas.
	* Para esta visualización de información hemos utilizado transiciones, así conseguimos mas suavidad a la hora de hacerlas visibles.
	* La información mostrada ocupa el espacio de la imagen y para poder dar toda la información se ha activado el scroll para moverse sobre ella y no perderse detalle.
	* Se ha hecho una adaptación, a través de "Media Query", sobre la visualización de esta página para dispositivos móviles.
		- El carrusel de imágenes de películas hacemos que se visualice en vertical y cada imágen ocupa el ancho de la pantalla.
		- El detalle/información de cada película se muestra al final de cada imágen de forma fija y en fondo negro.
3. Cada película o serie contendrá un icono que permitirá marcarla como favorita. Si está marcada como favorita, el icono se mostrará de forma distinta, de manera que se distinga fácilmente el contenido favorito del resto.
	* En este punto hemos añadido una estrella amarilla en la parte superior derecha de cada película favorita. Las no favoritas no tinen nada.
	* Para jugar un poco, hemos provocado que cuando te situas con el ratón encima de cada estrella, esta se desvanece.
4. Opcionalmente, se pide un carrusel de gran tamaño con el contenido destacado.
	* En este punto, hemos situado una imagen fija que ocupa todo el ancho de la pantalla y además hemos incluido un texto. La encontraremos en el inicio y el final de la página.

Para acceder al detalle de cada película, según el siguiente punto, lo haremos haciendo click sobe cada una de las carátulas de nuestra página. Esto funciona igual para móviles.

Detalle en imágenes de lo comentado

Imágenes de ordenador:
<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/Pantalla_ppal00.png?raw=true" alt="Formato móvil" width="500"/>
</p>
<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/Pantalla_ppal01.png?raw=true" alt="Formato móvil" width="200"/>
</p>

Imágenes de móvil:
<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/IMG_4413.PNG?raw=true" alt="Formato móvil" width="200"/>
</p>
<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/IMG_4414.PNG?raw=true" alt="Formato móvil" width="200"/>
</p>
<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/IMG_4415.PNG?raw=true" alt="Formato móvil" width="200"/>
</p>

#### Pantalla 3ª
Una ficha detalle de la película/serie. Deberá contener al menos:

1. El mismo menú superior de la pantalla principal.
	* En esta pantalla detalle he decidido suprimir el formulario de búsqueda, quedado el resto igual. Lo mismo hemos aplicado a la versión móvil.
2. información básica de la película/serie.
	* La información básica de la película la hemos situado debajo del trailer en un fondo negro y hemos hecho una adaptación para móvil.
3. Carátula o trailer. El trailer debe poder reproducirse en la propia página. En el caso de ser un video no se acepta la inclusión mediante marcos iframe.
	* Tal y como se pide en la práctica, el video está en local y se reproduce en la propia página sin incrustar iframes ni objects.
	* En nuestro caso hemos jugado con carátula a primera vista y video al pulsar sobre ella. ("poster").  
4. Rejilla con contenido relacionado, que se usará para los episodios en el caso de una serie o para películas similares.
	* A continuación de la información básica de la película, hemos situado una rejilla con las películas relacionadas, aplicando el mismo estilo y funcionalidad que en la página principal, incluido el enlace al detalle donde se muestra el trailer.
	* Esto también se ha hecho para la versión de móvil.

Incluimos capturas de pantalla de la página detalle.

<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/Pantalla_detalle00.png?raw=true" alt="Formato pantalla" width="500">
</p>

<p align="center">
<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/Pantalla_detalle01.png?raw=true" alt="Formato pantalla" width="500"/>
</p>

#### Pantalla 4ª (Opcional)
Crear una página de error 404 y la facilidad para el usuario de poder regresar a nuestra web.

* Hemos creado una página de error 404 que se puede acceder a través de la oción "Extras" de la barra de menú de la página principal y la de detalle.
* Se ha incluido un botón para que el usuario pueda volver a la página principal de nuestra web.
* En el color de fondo de la página hemos aplicado un degradado.

Adjuntamos captura de pantalla:

<p align="center">
	<img src="https://github.com/JosepCristobal/Fundamentos_Html_Css_PT/blob/master/src/WebX_PT/img/Error_404.png?raw=true" alt="Formato pantalla" width="500"/>
</p>

#### Pantalla 5ª (Opcional)
Página de Coming Soon que incluya un contador de días, horas, minutos y segundos, la fecha de lanzamiento y un formulario para inscribirse a las novedades. 

* A este punto ya no he podido llegar.


## Conclusión final

Esperamos que con este MVP convenzamos a algún inversor para que apueste por nuestro proyecto.

Muchas gracias Tony por todo.



