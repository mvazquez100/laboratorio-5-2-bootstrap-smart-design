PROYECTO: Laboratorio 5.2 - Creación de una página web responsiva con Bootstrap y CSS
NEGOCIO: Smart Design
AUTOR: Miguel Vazquez Cruz

DESCRIPCIÓN:
Este proyecto consiste en una página web responsiva para Smart Design, un negocio
orientado a servicios de landing pages, diseño de logos y contenido digital.
La página fue desarrollada utilizando HTML5 semántico, CSS3 y Bootstrap 5.3.8.

TECNOLOGÍAS UTILIZADAS:
1. HTML5
2. CSS3
3. Bootstrap 5.3.8
4. Bootstrap CSS mediante CDN de jsDelivr
5. Bootstrap JavaScript Bundle mediante CDN de jsDelivr
6. Visual Studio Code
7. Git
8. GitHub

ESTRUCTURA HTML5:
El documento utiliza etiquetas semánticas para mejorar la organización, accesibilidad
y comprensión del contenido:
- <header>: cabecera principal.
- <nav>: navegación principal.
- <main>: contenido principal.
- <section>: agrupación temática del contenido.
- <article>: tarjetas de servicios y productos.
- <footer>: información final y derechos de autor.

INTEGRACIÓN DE BOOTSTRAP:
Bootstrap se integró mediante CDN de jsDelivr:

CSS:
https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css

JavaScript:
https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js

COMPONENTES Y CLASES DE BOOTSTRAP UTILIZADOS:
- Navbar responsivo
- Navbar Toggler / Collapse
- Container
- Row y Columns
- Grid responsivo
- Cards
- Buttons
- Badges
- Utilities de espaciado
- Background utilities
- Text utilities
- Shadows
- Responsive breakpoints

SELECTORES CSS:
El archivo styles.css contiene diferentes tipos de selectores:
- Selectores de elemento: body, html
- Selectores de clase: .hero-section, .service-card, .product-card
- Selectores de ID: #servicios, #productos
- Selectores combinados: .navbar .nav-link, .card .btn

MODELO DE CAJA:
Se aplican propiedades del Box Model como:
- padding
- margin
- border
- border-radius
- box-sizing
- width
- height

DISEÑO RESPONSIVO:
El proyecto utiliza el sistema Grid de Bootstrap con clases como:
- col-12
- col-md-6
- col-lg-4
- col-lg-5
- col-lg-6
- col-lg-7

Además, se utiliza una media query personalizada para pantallas menores de 768px.

INTERFAZ:
La interfaz incluye:
- Navegación responsiva
- Hero principal
- Tarjetas de servicios
- Tarjetas de productos
- Sección informativa
- Call to Action
- Footer

ARCHIVOS DEL PROYECTO:
Laboratorio_5_2_Bootstrap/
|
|-- index.html
|-- styles.css
|-- readme.txt
|
`-- images/
    `-- smart-design-logo.png

EJECUCIÓN:
1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Abrir index.html en un navegador o utilizar Live Server.
3. Verificar el diseño en diferentes tamaños de pantalla.
4. Utilizar Git para el control de versiones.
5. Subir el proyecto a un repositorio de GitHub.

COMANDOS BÁSICOS DE GIT:
git init
git status
git add .
git commit -m "Laboratorio 5.2 Bootstrap"
git branch -M main
git remote add origin URL_DEL_REPOSITORIO
git push -u origin main

OBJETIVO ACADÉMICO:
Demostrar la integración de Bootstrap con HTML5 y CSS, el uso de selectores,
propiedades, modelo de caja, componentes de framework, diseño responsivo y
control de versiones mediante Git y GitHub.

VERIFICACIÓN FINAL:
La página fue probada en vista de escritorio y dispositivo móvil.
Se verificaron el Navbar responsivo, Grid, Cards, cambio de idioma
ES/EN y la sección semántica aside de comentarios.