# **Doccell** #


## ***Autor*** ##
Jose Santiago Carrillo Calero

## **Tecnologias** ##

* CSS
* JavaScript
* HTML5
* Markdown

## ***Descripción*** ##
El negocio posee una página de Facebook (doccell) la cual  el publico puede observar todos los accesorios que esta ofrece, la página web será un método para difundir mas lo que es este pequeño negocio que se encuentra en desarrollo y con expectativas de seguir creciendo no solo en el ámbito local sino también a un ámbito departamental y nacional, esta página tendrá acceso a la red social para que el que la visite si quiere mayor información se contacte con el propietario del negocio.


``` html
<body>
 

  <div class="navbar-fixed">
    <nav class="water green">
      <div class="nav-wrapper">
        <div class="container">
          <a href="#" class="brand-logo"> Doccell </a>
          <a href="#" data-activates="mobile-menu" class="button-collapse"><i class="material-icons">menu</i></a>
          <ul class="right hide-on-med-and-down">
            <li><a href="#home">Inicio</a></li>
            <li><a href="#buscar">Buscar</a></li>
            <li><a href="#lugares">Servicios</a></li>
            <li><a href="#galeria">Galería</a></li>
            <li><a href="#contacto">Contacto</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
  <ul class="side-nav" id="mobile-menu">
    <li><a href="#home">Inicio</a></li>
    <li><a href="#buscar">Buscar</a></li>
    <li><a href="#lugares">Servicios</a></li>
    <li><a href="#galeria">Galería</a></li>
    <li><a href="#contacto">Contacto</a></li>
  </ul>
 ```
 ## Seguido de un slider con imagenes e informacion  que hacen referencia a la empresa. ##

  ```html
   <section id="home" class="scrollspy">

    <div class="slider">
      <ul class="slides">
        <li>
          <img src="img/enradav.jpg">
          <div class="caption center-align">
            <h3>Encuentral mil soluciones en un mismo lugar</h3>
            <h5 class="light purple-text text-lighten-3"> Nuestro compromiso es tu tranquilidad y satisfaccion ofreciendote los mejres repuestos 
              y accesorios a un precio accesible..!
            </h5>
            <br>
            <a class="waves-effect waves-light btn indigo white-text" target="_blank" href="https://www.facebook.com/Doccell-653010811466568/">Mas informacion</a>
          </div>
        </li>
        <li>
          <img src="img/general.jpeg">
          <div class="caption left-align">
            <h3>Trabajando para tu beneficio</h3>
            <h5 class="light purple-text text-lighten-3">Reparamos todo tipo de accesorios electronicos, como telefonos, televisores
              computadoras y mas!
            </h5>
          </div>
        </li>
        
      </ul>
    </div>
  </section>

  


```
   ## Aca estamos mostrando donde se encuentra ubicada la empresa. ##

``` html
    <section id="buscar" class="caption center-align">
    <div class="center">
      <div class="col s12 m4">
        <i class="material-icons large tender green-text">room</i>
        <h4>Ubicación</h4>
        <p> Estamos ubicados en Santo Tomas Chontales frente al banco la fise bancentro</p>
      </div>
    
    </div>
  </section>


```
## En el siguiente menu se muestra los servicios a los cuales esta dedicado este negocio(Empresa) ##

``` html
 <section id="lugares" class="scrollspy">
    <div class="container">
      <div class="row">
        <br>
        <h4 class="center black-text">Servicios</h4>
        <div class="col s12 m4">
          <div class="card">
            <div class="card-image">
              <img src="img/celular.jpg">
              <span class="card-title black-text" >Reparacion de celulares</span>
            </div>
            <div class="card-content">
              <p> Reparacion y flasheo celulares de todo tipo y marca </p>
            </div>
          </div>
        </div>

        <div class="col s12 m4">
          <div class="card">
            <div class="card-image">
              <img src="img/compu.jpg">
              <span class="card-title black-text">Reparacion de computadoras</span>
            </div>
            <div class="card-content">
              <p>Les ofrecemos repuestos, limpieza y reparacion de su equipo.  </p>
            </div>

          </div>
        </div>

        <div class="col s12 m4">
          <div class="card">
            <div class="card-image">
              <img src="img/tv.jpg">
              <span class="card-title black-text"  >Reparaciòn de televisores</span>
            </div>
            <div class="card-content">
              <p>Reparamos tv para tu beneficio y tu comodidad.</p>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>


```
## Les presentamos parte de la galeria de la tienda como es y lo que ofrece. ##

``` html
<section id="galeria" class="scrollspy">

    <div class="container">
      <h4 class="center black-text">Galería de fotos</h4>
      <div class="row">
        <div class="col s12 m3">
          <img class="materialboxed responsive-img" src="img/protectores.jpeg">
        </div>
        <div class="col s12 m3">
          <img class="materialboxed responsive-img" src="img/glas.jpeg">
        </div>
        <div class="col s12 m3">
          <img class="materialboxed responsive-img" src="img/accesorios.jpeg">
        </div>
        <div class="col s12 m3">
          <img class="materialboxed responsive-img" src="img/glas.jpeg">
        </div>
        <div class="col s12 m3">
          <img class="materialboxed responsive-img" src="img/pocicion2.jpeg">
        </div>
        <div class="col s12 m3">
            <img class="materialboxed responsive-img" src="img/protectores.jpeg">
          </div>
        <div class="col s12 m3">
          <img class="materialboxed responsive-img" src="img/accesorios.jpeg">
        </div>
        <div class="col s12 m3">
            <img class="materialboxed responsive-img" src="img/pocicion2.jpeg">
          </div>
        <div class="col s12 m3">
          <img class="materialboxed responsive-img" src="img/tv.jpg">
        </div>
        <div class="col s12 m3">
            <img class="materialboxed responsive-img" src="img/celular.jpg">
          </div>
          <div class="col s12 m3">
            <img class="materialboxed responsive-img" src="img/compu.jpg">
          </div>
      </div>
    </div>

    
    
 ```
## En este menu le presentamos como se pueden contactar con la empresa o sus propietarios. ##

``` html
 <section id="contacto" class="scrollspy">
    <div class="container">
      <h4 class="center red-text">Contacto con nosotros</h4>
      <div class="row">
        <form>
          <div class="input-field col s12 l6">
            <input type="text" id="primer_nombre" class="validate">
            <label for="primer_nombre">Nombre</label>
          </div>
          <div class="input-field col s12 l6">
            <input type="text" id="segundo_nombre" class="validate">
            <label for="segundo_nombre">Apellido</label>
          </div>
          <div class="input-field col s12">
            <input type="email" id="email" class="validate">
            <label for="email" data-error="Correo Inválido" data-success="Correcto">Email</label>
          </div>
          <div class="input-field col s12">
            <textarea id="mensaje" class="materialize-textarea"></textarea>
            <label for="mensaje">Mensaje</label>
          </div>
          <button class="btn waves-effect waves-light light green" type="submit" name="action">Enviar
            <i class="material-icons right">send</i>
          </button>
        </form>
      </div>
    </div>
  </section>