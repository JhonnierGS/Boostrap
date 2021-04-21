# Boostrap
Proyecto practico en boostrap

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
  












