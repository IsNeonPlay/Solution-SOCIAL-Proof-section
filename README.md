# Solution SOCIAL Proof section
Front-end Mentor Basic challenge solved By IsNeonPlay

[![desktop-preview.jpg](https://i.postimg.cc/L4tp8qL9/desktop-preview.jpg)](https://postimg.cc/Sjx5Zxg3)

# // ESPAÑOL // 🇪🇸 

Otro reto básico de Front-end Mentor resuelto por IsNeonPlay. 
Ultimamente me estoy dando cuenta que me cuesta bastante centrar los objetos o el main en la version de escritorio, hice el intento y al parecer quedó un poco corrido hacia la izquerda, pero lo intenté. 

No hay mucho que explicar del proyecto, eso si, usé bastante `flex` y `grid` para alinear de cierta forma los objetos.

El background no fue tan complicado, solo hice lo siguiente: 

- Agregué estos contenedores con todos los fondos (movil y escritorio) y los separé en dos contenedores para tener la versión de cada uno en el documento html.

`
	<div class="bg-mobile">
  	<div class="bg-mobile__top">
    	<img src="images/bg-pattern-top-mobile.svg" alt="bg mobile">
    </div>
  	<div class="bg-mobile__bottom">
      <img src="images/bg-pattern-bottom-mobile.svg" alt="bg mobile">
   	</div>
  </div>

  <div class="bg-desktop">
  	<div class="bg-desktop__top">
    	<img src="images/bg-pattern-top-desktop.svg" alt="bg desktop">
    </div>
    <div class="bg-desktop__bottom">
      <img src="images/bg-pattern-bottom-desktop.svg" alt="bg desktop">
    </div>
  </div>
`

-Luego , en la hoja de estilos (style.css) edité los contenedores de la version movil y a la version de escritorio le agregué `display: none;` para que desapareciera.

-Con el mediaQuerie de la version de escritorio, hice lo contrario a la hoja de estilos principal, a la version movil le agregué `display: none;`, y la version de escritorio le puse un `display: block;` para que sea visible y poder trabajar con esa versión.


# // ENGLISH // 🇬🇧 

