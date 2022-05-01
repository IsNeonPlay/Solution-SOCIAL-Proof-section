# Solution SOCIAL Proof section
Front-end Mentor Basic challenge solved By IsNeonPlay

[![desktop-preview.jpg](https://i.postimg.cc/L4tp8qL9/desktop-preview.jpg)](https://postimg.cc/Sjx5Zxg3)

# // ESPAÑOL // 🇪🇸 

Otro reto básico de Front-end Mentor resuelto por IsNeonPlay. 
Ultimamente me estoy dando cuenta que me cuesta bastante centrar los objetos o el main en la version de escritorio, hice el intento y al parecer quedó un poco corrido hacia la izquerda, pero lo intenté. 

No hay mucho que explicar del proyecto, eso si, usé bastante `flex` y `grid` para alinear de cierta forma los objetos.

El background no fue tan complicado, solo hice lo siguiente: 

- Agregué estos contenedores con todos los fondos (movil y escritorio) y los separé en dos contenedores para tener la versión de cada uno en el documento html.

```html
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
```

-Luego , en la hoja de estilos (style.css) edité los contenedores de la version movil y a la version de escritorio le agregué `display: none;` para que desapareciera.

-Con el mediaQuerie de la version de escritorio, hice lo contrario a la hoja de estilos principal, a la version movil le agregué `display: none;`, y la version de escritorio le puse un `display: block;` para que sea visible y poder trabajar con esa versión.


# // ENGLISH // 🇬🇧 

Another basic Front-end Mentor challenge solved by IsNeonPlay.
Lately I am realizing that it is quite difficult for me to center the objects or the main in the desktop version, I tried and it seems that it was a little shifted to the left, but I tried.

There is not much to explain about the project, though, I used a lot of `flex` and `grid` to align the objects in a certain way.

The background was not that complicated, I just did the following:

- I added these containers with all the backgrounds (mobile and desktop) and separated them into two containers to have the version of each one in the html document.

```html
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
```

-Then, in the style sheet (style.css) I edited the containers of the mobile version and added `display: none;` to the desktop version so that it would disappear.

-With the mediaQuerie of the desktop version, I did the opposite of the main style sheet, to the mobile version I added `display: none;`, and the desktop version I put a `display: block;` to make it visible and be able to work with that version.
