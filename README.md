# Bootstrap
Proyecto practico en bootstrap

# ¿Qué es un Framework Front-End?
 - También conocidos como Frameworks CSS
 - Son una base para empezar un proyecto web permitiendo flexibilidad en el diseño
 - Organización y estructura de nuestro HTML, CSS y JavaScript

# ¿qué trae un Framework Fron-End?
 - grilla
 - estilos para fuentes
 - Componentes visuales pre-armados

# ¿Para qué quiero uno?
 - Ahorrar tiempo
 - Componentes visuales
 - Responsive design
 - El codigo anda

# Ejemplos de Frameworks
 - Boostrap
 - Foundation
 - Bulma
 - Flexbox Grid

# Containers
Los containers son el elmento más básico del layout de Boostrap y son necesarios para organizar nuestro contenido dentro de una grilla 
 - container fijo
 ```HTML
  <div class="container">
  <!-- Content here -->
 </div>
  ```
 - container fluido
 ```HTML
  <div class="container-fluid">
  <!-- Content here -->
 </div>
  ```
# The Grid
El sistema de grillas de Boostrap usa contenedores, fijas y columnas para organizar y alinear el contenido de nuestro sitio

tenmos un sistema de grillas de 12 columnas.

Por detras utiliza Felxbox y es 100% responsive 

 - Columnas
 ```HTML
  <div class="container">
   <div class="row">
    <div class="col-sm">Columna 1 de 3</div>
    <div class="col-sm">Columna 2 de 3</div>
    <div class="col-sm">Columna 3 de 3</div>
   </div
 </div>
  ```
  <h3>Explicación</h3>
  
  - El contenedor provee una forma de centrar el contenidode la pagina
  - las filas continen columnas
  - Las columnas tienen un <b>padding</b> hotizontal (gutter) para controlar el espaciado entre ellas
  - Este <b>padding</b> se ve contrarrestado con un margin negavito en las filas
  - En las grillas, el contenido debe estar dentro de las columnas
  - Las filas solo deben tener columnas como hijos
  - Tenemos 12 columnas
  - Columnas que no especifiquen el tamaño ocuparán igual tamaño
  - El temaño de las columnas determina cuántas columnas tendremos
  - Si queremos tres columnas: <b>.col-4 .col-4 .col-4</b>
  
  <h3>Documentacion</h3>
  
   [Boostrap](https://getbootstrap.com/docs/4.1/layout/grid/)

# Navbar
Barra de navegación

 <h3>¿Qué colocar dentro de un Navbar?</h3>

 - <b>.navbar-brand<b>: para el nombre de tú compañia.
 - <b>.navbar-nav<b>: para un menú de navegación (que puede tener submenúes).
 - <b>.navbar-toggler<b>: para usar con el plugin para colapsar contenido.
 - <b>.form-inline<b>: para incluir formularios.
 - <b>.navbar-text<b>: para incuilr texto centrado vertical mente.
 - <b>.collapse .navbar-collapse<b>: para agrupar contenido que se va a colapsar.
 
 ```HTML
  <div class="navbar navbar-dark bg-dark">
     <!--Navbar Content-->
  </div>
 <div class="navbar navbar-dark bg-primary">
     <!--Navbar Content-->
  </div>
 <div class="navbar navbar-light" style="background-color: #e3f2fd">
     <!--Navbar Content-->
  </div>
  ```
 # Carousel
 Un carrusel de imagenes
 
 ```HTML
   <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="...">
    </div>
  </div>
</div>
  ```
  - Hay que agregar la clase <b>.active</b> a algunos slides 
  - Asegurarse que los controles e indicadores tengan un atributo elemnts <b>data-target</b> que coincidad con el id del elemento <b>.coarousel</b>
  
  # Card
  Un contenedor felxible con múltiples variantes y opciones 

  ```HTML
   <div class="card" style="width: 18rem;">
  <img src="..." class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
  ```
# Etiquetas
Para contadores y pequeñas etiquetas
   
   ```HTML
<h1>Example heading <sapn class="badge badge-sacondary">New</sapn></h1>
<h2>Example heading <sapn class="badge badge-sacondary">New</sapn></h2>
<h3>Example heading <sapn class="badge badge-sacondary">New</sapn></h3>
<h4>Example heading <sapn class="badge badge-sacondary">New</sapn></h4>
<h5>Example heading <sapn class="badge badge-sacondary">New</sapn></h5>
  ```
<h3>Dentro de botones</h3>
  
  ```HTML
 <button tyoe="button" class="btn tbn-primary">
   Notification <span class="badge badge.light">4</span>
 </button>
  ```
<h3>Variaciones de contexto</h3>

 ```HTML
<span class="badge badge-primary">Primary</span>
<span class="badge badge-secondary">Secondary</span>
<span class="badge badge-success">Success</span>
<span class="badge badge-danger">Danger</span>
<span class="badge badge-warning">Warning</span>
<span class="badge badge-info">Info</span>
<span class="badge badge-light">Light</span>
<span class="badge badge-dark">Dark</span>
  ```
  
 <h3>Pildoras</h3>
  
   ```HTML
<span class="badge badge-pill badge-primary">Primary</span>
<span class="badge badge-pill badge-secondary">Secondary</span>
<span class="badge badge-pill badge-success">Success</span>
<span class="badge badge-pill badge-danger">Danger</span>
<span class="badge badge-pill badge-warning">Warning</span>
<span class="badge badge-pill badge-info">Info</span>
<span class="badge badge-pill badge-light">Light</span>
<span class="badge badge-pill badge-dark">Dark</span>
  ```
# Formularios
Estilos para controles, opciones de layout y componentes personalizados
  
  <h3>controles</h3>
  
   ```HTML
 <section id="conviertete-en-orador" class="pt-4 pb-4">
            <div class="container">
                <div class="row">
                    <div class="col text-uppercase text-center">
                        <small>Conviertete en un</small>
                        <h2>ORADOR</h2>
                    </div>
                </div>
                <div class="row">
                    <div class="col text-center">
                        Anótate para dar una charla ignite. ¡Cuéntanos de que quieres hablar!
                    </div>
                </div>
                <div class="row">
                    <div class="col col-md-10 offset-md-1 col-lg-8 offset-lg-2 pt-2">
                        <div class="row">
                            <div class="form-label col-12 col-md-6">
                                <input type="text" class="form-control" placeholder="First name" aria-label="Nombre">
                            </div>
                            <div class="form-label col-12 col-md-6">
                                <input type="text" class="form-control" placeholder="Last name" aria-label="Apellido">
                            </div>
                        </div>
                        <div class="row">
                            <div class="form-label col">
                                <textarea name="text" class="form-control form-control-lg" placeholder="¿Sobre quá quieres hablar?"></textarea>
                                <small class="form-text text-muted">
                                    Recuerda incluir un título para tú charla
                                </small>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col">
                                <button type="button" class="btn btn-platzi col-12">Enviar</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
  ```
# Scrollspy
Automáticamente actualiza la navegación de Bootstrap con base en la posición del sroll para iniciar qué link esta activo en el viewport
  
  <h3>Requerimentos<h3>
  
- Se tiene que usar en un .nav o un .item-list
- Scrollspy requiere que el elemento donde se controlará el sroll tenga <b>Position: relative;</b> (generalmente el body)
- Si se usa sobre otro elemneto que no sea el <body, asegúrate de que tenga un <b>height fijo</b> y <b>overflow-y: scroll</b>
- Se requieren anclas (<a>) y deben navegar hacia un elemento con ese <b>id</b>
  
# Modal
Usa este componente para mostrar ventanas emergnentes dentro de tu sitio con notificaciones para usuarios, fotos o el contenido que quieras

- Continen HTML, CSS y JavaScript
- Están posicionados sobre tod o lo demás que esta en la pagina
- Bloquean el scroll en el body (excepto en móviles)
- Si haces click en el fondo, se cierra
- Sólo un modal a la vez
- No ubicarlo dentro de otros elementos 

  
  
  
  
  
  
  
  
  
  
  
  
