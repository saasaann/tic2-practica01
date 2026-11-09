# Mis opciones después del Bachillerato

**Práctica 01 de TIC II · 2.º Bachillerato · Curso 2026-2027**

---

## ¿Qué es?

Es una web en la que comparo mis tres opciones para cuando acabe el Bachillerato. Son tres grados de la Facultad de Informática de la Universidade da Coruña:

- Ingeniería Informática.
- Inteligencia Artificial.
- Ciencia e Ingeniería de Datos.

La web tiene tres páginas:

- `index.html`: la portada, con una presentación, un carrusel de fotos y una tarjeta por cada grado.
- `opciones.html`: una tabla que compara los tres grados y una ficha de cada uno.
- `salidas.html`: los trabajos a los que lleva cada grado, cómo llegar a ellos y mi conclusión.

Los estilos están en `css/estilos.css`, las fotos en `img/`, el vídeo de fondo en `videos/` y las capturas de las pruebas en `evidencias/`.

Para verla hay que abrir `index.html` en el navegador con conexión a internet, porque Bootstrap se carga por CDN.

---

## ¿Cómo la hice?

Empecé con la página de inicio, creando el carrusel y las tres tarjetas (*cards*). Después creé el menú desplegable que se pedía, añadí la página de opciones y construí la tabla comparativa.

Para resolver algunas dudas que tenía sobre el formato, me apoyé en las herramientas de IA que menciono más abajo.

Luego creé la página de salidas profesionales y probé varios formatos de diseño para organizar la información, hasta que me decanté por uno de Bootstrap: las pestañas (*tabs*). Después añadí la lista ordenada que explica cómo llegar a cada profesión y, finalmente, la conclusión.

Entre medias fui incorporando las imágenes y el vídeo de fondo `.mp4` de Pexels. Por último, añadí el pie de página y la ficha de cada grado, en cuya elaboración también me apoyé en IA para dejar constancia clara del origen de las fuentes.

---

## Pruebas y errores

Probé las tres páginas a **390, 768 y 1280 píxeles** y guardé las capturas en `evidencias/`.

Comprobé que:

- El menú se abre y permite navegar entre las páginas.
- Las pestañas cambian de grado.
- Se ve el foco al navegar con la tecla `Tab`.
- La tabla se mueve dentro de su propio recuadro en el móvil sin que se mueva toda la página.

Al pasar las páginas por el validador del W3C me salieron varios errores:

- El menú estaba dentro del `head`.
- Había dos elementos `h1` en cada página.
- El menú lateral que copié de Bootstrap tenía un problema con el atributo `aria-labelledby`.

Lo corregí y ahora las tres páginas y la hoja de estilos pasan los validadores sin errores.

---

## Fuentes

### Información de los grados

**Ingeniería Informática**

- https://estudos.udc.es/es/study/start/614G01V01
- https://estudos.udc.es/es/study/admission/614G01V01
- https://estudos.udc.es/es/study/detail/614G01V01
- https://fic.udc.es/sites/default/files/documentos/24137fichagradoei.pdf
- https://www.boe.es/boe/dias/2009/08/04/pdfs/BOE-A-2009-12977.pdf

**Inteligencia Artificial**

- https://estudos.udc.es/es/study/start/614G03V01
- https://estudos.udc.es/es/study/admission/614G03V01
- https://estudos.udc.es/es/study/detail/614G03V01

**Ciencia e Ingeniería de Datos**

- https://estudos.udc.es/es/study/start/614G02V01
- https://estudos.udc.es/es/study/admission/614G02V01
- https://estudos.udc.es/es/study/detail/614G02V01

**Otras universidades**

- https://www.usc.gal/
- https://www.uvigo.gal/

### Acceso a la universidad

- https://www.ciug.gal/uploads/PDF/2026/Acceso/6a4e059db8812978315901primeiroprazo2026.pdf
- https://www.ciug.gal/uploads/PDF/2026/Acceso/6ac8e4b64852e473654100derradeiroprazo.pdf
- https://www.ciug.gal/uploads/PDF/2027/pau/6ace226094f14765933894ponderacions-2027.pdf
- https://www.ciug.gal/

### Universidades y facultades

- https://www.udc.es/
- https://estudos.udc.es/es/
- https://www.fic.udc.es/

### Bootstrap 5.3

- https://getbootstrap.com/docs/5.3/components/navbar/
- https://getbootstrap.com/docs/5.3/components/offcanvas/
- https://getbootstrap.com/docs/5.3/components/carousel/
- https://getbootstrap.com/docs/5.3/components/card/
- https://getbootstrap.com/docs/5.3/components/accordion/
- https://getbootstrap.com/docs/5.3/components/navs-tabs/
- https://getbootstrap.com/docs/5.3/layout/grid/
- https://getbootstrap.com/docs/5.3/content/tables/
- https://getbootstrap.com/docs/5.3/content/images/

### HTML y CSS

- https://developer.mozilla.org/es/docs/Web/HTML
- https://developer.mozilla.org/es/docs/Web/CSS
- https://www.w3schools.com/html/
- https://www.w3schools.com/css/

### Validación y publicación

- https://validator.w3.org/
- https://jigsaw.w3.org/css-validator/
- https://docs.github.com/es

### Imágenes

- https://commons.wikimedia.org/

---

## Créditos de las imágenes y del vídeo

A todas las imágenes les he cambiado el tamaño o las he recortado un poco, excepto `ia.jpg`, `udc.png` y el vídeo, que están sin modificar.

| Archivo | Autor y título | Licencia |
|---|---|---|
| `informatica.jpg` | Martin Vorel — [Programming code](https://commons.wikimedia.org/wiki/File:Programming_code.jpg) | CC BY-SA 4.0 |
| `ia.jpg` | Jasonprost — [3d-printed-humanoid-robot-manav-mumbai-techfest-2015](https://commons.wikimedia.org/wiki/File:3d-printed-humanoid-robot-manav-mumbai-techfest-2015.jpg) | CC BY-SA 4.0 |
| `datos.jpg` | Victor Grigas — [Wikimedia Foundation Servers-8055 35](https://commons.wikimedia.org/wiki/File:Wikimedia_Foundation_Servers-8055_35.jpg) | CC BY-SA 3.0 |
| `facultad1.jpg` | Fernando Losada Rodríguez — [Facultade de Informática.002 - UDC](https://commons.wikimedia.org/wiki/File:Facultade_de_Inform%C3%A1tica.002_-_UDC.jpg) | CC BY-SA 4.0 |
| `facultad2.jpg` | Fernando Losada Rodríguez — [Facultade de Informática.001 - UDC](https://commons.wikimedia.org/wiki/File:Facultade_de_Inform%C3%A1tica.001_-_UDC.jpg) | CC BY-SA 4.0 |
| `udc-campus.jpg` | Zarateman — [A Coruña - Universidade da Coruña](https://commons.wikimedia.org/wiki/File:A_Coru%C3%B1a_-_Universidade_da_Coru%C3%B1a.JPG) | CC0 |
| `equipo.jpg` | Christina Morillo — [Group of People Using Laptop Computer](https://www.pexels.com/photo/group-of-people-using-laptop-computer-1181370/) | Licencia de Pexels |
| `desarrollador.jpg` | Slashme — [RustCodeOnScreen](https://commons.wikimedia.org/wiki/File:RustCodeOnScreen.jpg) | CC0 |
| `administrador.jpg` | Alexis Lê-Quôc — [3PAR SAN in the server room](https://commons.wikimedia.org/wiki/File:3PAR_SAN_in_the_server_room.jpg) | CC BY-SA 2.0 |
| `analista-sistemas.jpg` | SajmonKajtka — [SCHÉMA](https://commons.wikimedia.org/wiki/File:SCH%C3%89MA.jpg) | CC BY-SA 4.0 |
| `ingeniero-ia.jpg` | Willy Jackson — [Ameca Generation 1](https://commons.wikimedia.org/wiki/File:Ameca_Generation_1.jpg) | CC BY-SA 4.0 |
| `aprendizaje.jpg` | mikemacmarketing — [Artificial Neural Network with Chip](https://commons.wikimedia.org/wiki/File:Artificial_Neural_Network_with_Chip.jpg) | CC BY 2.0 |
| `vision.jpg` | Adrian Rosebrock — [Intersection over Union - object detection bounding boxes](https://commons.wikimedia.org/wiki/File:Intersection_over_Union_-_object_detection_bounding_boxes.jpg) | CC BY-SA 4.0 |
| `analista-datos.jpg` | Growthlakes — [Infruid's Self-Service BI Tool Dashboard](https://commons.wikimedia.org/wiki/File:Infruid%27s_Self-Service_BI_Tool_Dashboard.jpg) | CC BY-SA 4.0 |
| `cientifico-datos.jpg` | Shixart1985 — [Elderly woman sitting at her office table and holding a cup of coffee while working on her laptop](https://commons.wikimedia.org/wiki/File:Elderly_woman_sitting_at_her_office_table_and_holding_a_cup_of_coffee_while_working_on_her_laptop._Croissant_and_a_donut_on_the_trays_next_to_her.jpg) | CC BY 2.0 |
| `ingeniero-datos.jpg` | BalticServers.com — [BalticServers data center](https://commons.wikimedia.org/wiki/File:BalticServers_data_center.jpg) | CC BY-SA 3.0 |
| `udc.png` | Logotipo de la Universidade da Coruña, obtenido de https://www.udc.es/. Lo uso solo para identificar la universidad. | — |
| `video.mp4` | Vídeo de fondo de triángulos blancos, obtenido de https://www.pexels.com/. | Licencia de Pexels |

---

## Uso de IA

Me he apoyado en herramientas de inteligencia artificial (**Claude y ChatGPT**) para:

- Redactar y mejorar los textos de la web.
- Buscar información sobre los grados y las páginas oficiales de donde sacar los datos.
- Desarrollar algunas partes del código que no sabía hacer.

He comprobado todos los datos en las fuentes oficiales.

