# PROYECTO IMA SALUD

## DESCRIPCIÓN

El proyecto **IMA SALUD** consiste en el desarrollo de un sitio web responsive para una institución médica como parte del proyecto final a presentar para el curso de *Desarrollo web* de **CODERHOUSE**.

## TECNOLOGÍA APLICADA

El sitio web está desarrollado en **HTML5** para el armado de la estructura, miestras que para la aplicación de estilo de cada una de las páginas se utilizó el framework **BOOTSTRAP V.5.0** (aplicando al mismo tiempo elementos de *GRIDs, FLEXBOX Y BOX MODELLING*) y **NODE.js** para instalar Node-sass y compilar **SASS** a **CSS**.

## ESTRUCTURA DEL SITIO WEB

Las páginas que componen el sitio web son:

- **HOME** [GitHub Pages](https://julianrius.github.io/proyectoimasalud/index.html)
- **ESPECIALIDADES** [GitHub Pages](https://julianrius.github.io/proyectoimasalud/especialidades.html)
- **STAFF** [GitHub Pages](https://julianrius.github.io/proyectoimasalud/staff.html)
- **TIPSS** [GitHub Pages](https://julianrius.github.io/proyectoimasalud/tipss.html)
- **CONTACTO** [GitHub Pages](https://julianrius.github.io/proyectoimasalud/contacto.html)

Adicionalmente, se creó una página de *error 404* [GitHub Pages](https://julianrius.github.io/proyectoimasalud/404.html).

### LAYOUT DE PÁGINAS



### HEADER está compuesto por un NAVBAR, LOGO y H1. Es similar en todas las páginas. 



### FOOTER consta de un mapa de ubicación de Google MAP, una tabla de datos y los enlaces correspondientes a redes sociales. Es similar en todas las páginas.

### MAIN

- **HOME** contiene un carrousel con dos imágenes y dos textos animados de bienvenida y presentación.
- **ESPECIALIDADES** contiene un carrousel con 6 imágenes de cada especialidad sobre las cuales se detallan las prácticas vinculadas a la mismas.
- **STAFF** contiene un conjunto de CARDS en la que se presentan los profesionales de la institución.
- **TIPSS** contiene una grilla de iframes con TIPS saludables por especialidad.
- **CONTACTO** contiene un formulario de contacto.

# DIAGRAMA DE ARCHIVOS

##proyectoimasalud

Carpeta raíz.

- ### Archivos de enlace y .gitignore

- .gitignore aplicado a nodemodules y package-lock.json
- index.html
- especialidades.html
- staff.html
- tipss.html
- contacto.html
- 404.html

- ### assets

Contiene todos los archivos de imágen empleados en el sitio.

- ### css

Contiene todos los archivos de estilos de **BOOTSTRAP V.5.0** y el en el que se descarga la compilación de SASS **main.css**.

- ### js

Contiene todos los archivos Javascript de **BOOTSTRAP V.5.0**

- ### scss

Contiene los archivos de estilos personalizados y los archivos principales de estilos *estilos.scss*, *estilos.scss* y *estilos.css.map* .

- #### abstracts

Contiene los archivos **_variables.scss** donde están parametrizados los diferentes colores aplicados a fuentes y elementos. Por otro lado, **_mixins.scss** donde se encuentran los mixins empleados en el sitio web.

- #### base

Contiene los archivos **_reset.scss** donde están reseteados los valores por defecto. Por otro lado, **tipografías.scss** donde se encuentran las variables y mapas aplicados a las fuentes.

- #### componentes      

Contiene los archivos  **_carousel.scss** correspondiente a los parámetros aplicados a dicho componente en lás página index.html y especialidades.html; **_formulariodecontacto.scss** de la página contacto.html; **_tarjeta.scss** de la página staff.html  y **_iframes.scss** de la página tipss.html
.
- #### layout

Contiene los archivos con los parámetros de estilo aplicados al HEADER **_header.scss**, FOOTER **_footer.scss**, BODY **_bbody.scss** y los aplicados a la página de erro 404 **_error404.scss**


