Mis opciones después del Bachillerato

Práctica 01 de TIC II. 2.º Bachillerato, curso 2026-2027.



Qué es

Es una web en la que comparo mis tres opciones para cuando acabe el Bachillerato. Son tres grados de la Facultad de Informática de la Universidade da Coruña: Ingeniería Informática, Inteligencia Artificial y Ciencia e Ingeniería de Datos.

La web tiene tres páginas:

* index.html: la portada, con una presentación, un carrusel de fotos y una tarjeta por cada grado.
* opciones.html: una tabla que compara los tres grados y una ficha de cada uno.
* salidas.html: los trabajos a los que lleva cada grado, cómo llegar a ellos y mi conclusión.

Los estilos están en css/estilos.css, las fotos en img/, el vídeo de fondo en videos/ y las capturas de las pruebas en evidencias/. Para verla hay que abrir index.html en el navegador con internet, porque Bootstrap se carga por CDN.



Cómo la hice

Empecé con una sola página y la tabla de comparación. Después añadí la página de opciones y le fui dando formato.

Luego metí Bootstrap 5.3.8 por el CDN de jsDelivr, el mismo en las tres páginas. Copié de la documentación de Bootstrap el menú (un botón que abre un menú lateral), el carrusel, las tarjetas, el acordeón de las fichas y las pestañas de la página de salidas, y les cambié los textos. Las columnas de las tarjetas (col-12 col-md-6 col-lg-4) hacen que se vea una por fila en el móvil, dos en la tableta y tres en el ordenador.

Mi hoja de estilos va después de la de Bootstrap. Al principio tenía otros colores, pero al final lo dejé en blanco con el texto y los bordes en marrón, y puse el mismo vídeo de fondo en todas las páginas. Cada sección va dentro de una caja blanca con borde (la clase .caja) para que se lea bien encima del vídeo. También hice una clase .button para los botones, un borde cuando un enlace tiene el foco con el teclado y una media query para que en el móvil los títulos sean más pequeños.

En la tabla usé caption, thead, tbody y th con scope para que se sepa a qué grado y a qué dato corresponde cada celda.

Al final busqué los datos oficiales de 2026 (plazas y notas de corte del último plazo de la CiUG) y añadí fotos a cada salida.



Pruebas y errores

Probé las tres páginas a 390, 768 y 1280 px y guardé las capturas en evidencias/. Comprobé que el menú se abre y lleva a cada página, que las pestañas cambian de grado, que se ve el foco con la tecla Tab y que la tabla se mueve dentro de su recuadro en el móvil sin que se mueva la página.

Al pasar las páginas por el validador del W3C me salieron varios errores. El menú estaba dentro del head, había dos h1 en cada página y el menú lateral que copié de Bootstrap tenía un aria-labelledby que no se puede poner en un div. Lo corregí y ahora las tres páginas y la hoja de estilos pasan los validadores sin errores.



Fuentes

https://estudos.udc.es/es/study/start/614G01V01
https://estudos.udc.es/es/study/admission/614G01V01
https://estudos.udc.es/es/study/detail/614G01V01
https://fic.udc.es/sites/default/files/documentos/24137fichagradoei.pdf
https://www.boe.es/boe/dias/2009/08/04/pdfs/BOE-A-2009-12977.pdf
https://estudos.udc.es/es/study/start/614G03V01
https://estudos.udc.es/es/study/admission/614G03V01
https://estudos.udc.es/es/study/detail/614G03V01
https://www.usc.gal/
https://www.uvigo.gal/
https://estudos.udc.es/es/study/start/614G02V01
https://estudos.udc.es/es/study/admission/614G02V01
https://estudos.udc.es/es/study/detail/614G02V01
https://www.ciug.gal/uploads/PDF/2026/Acceso/6a4e059db8812978315901primeiroprazo2026.pdf
https://www.ciug.gal/uploads/PDF/2026/Acceso/6ac8e4b64852e473654100derradeiroprazo.pdf
https://www.ciug.gal/uploads/PDF/2027/pau/6ace226094f14765933894ponderacions-2027.pdf
https://www.ciug.gal/
https://www.udc.es/
https://estudos.udc.es/es/
https://www.fic.udc.es/
https://getbootstrap.com/docs/5.3/components/navbar/
https://getbootstrap.com/docs/5.3/components/offcanvas/
https://getbootstrap.com/docs/5.3/components/carousel/
https://getbootstrap.com/docs/5.3/components/card/
https://getbootstrap.com/docs/5.3/components/accordion/
https://getbootstrap.com/docs/5.3/components/navs-tabs/
https://getbootstrap.com/docs/5.3/layout/grid/
https://getbootstrap.com/docs/5.3/content/tables/
https://getbootstrap.com/docs/5.3/content/images/
https://developer.mozilla.org/es/docs/Web/HTML
https://developer.mozilla.org/es/docs/Web/CSS
https://www.w3schools.com/html/
https://www.w3schools.com/css/
https://validator.w3.org/
https://jigsaw.w3.org/css-validator/
https://docs.github.com/es
https://commons.wikimedia.org/



Créditos de las imágenes y del vídeo

A todas les he cambiado el tamaño o las he recortado un poco, menos ia.jpg, udc.png y el vídeo, que están igual.

* informatica.jpg: "Programming code", de Martin Vorel. https://commons.wikimedia.org/wiki/File:Programming\_code.jpg (CC BY-SA 4.0)
* ia.jpg: "3d-printed-humanoid-robot-manav-mumbai-techfest-2015", de Jasonprost. https://commons.wikimedia.org/wiki/File:3d-printed-humanoid-robot-manav-mumbai-techfest-2015.jpg (CC BY-SA 4.0)
* datos.jpg: "Wikimedia Foundation Servers-8055 35", de Victor Grigas. https://commons.wikimedia.org/wiki/File:Wikimedia\_Foundation\_Servers-8055\_35.jpg (CC BY-SA 3.0)
* facultad1.jpg: "Facultade de Informática.002 - UDC", de Fernando Losada Rodríguez. https://commons.wikimedia.org/wiki/File:Facultade\_de\_Inform%C3%A1tica.002\_-\_UDC.jpg (CC BY-SA 4.0)
* facultad2.jpg: "Facultade de Informática.001 - UDC", de Fernando Losada Rodríguez. https://commons.wikimedia.org/wiki/File:Facultade\_de\_Inform%C3%A1tica.001\_-\_UDC.jpg (CC BY-SA 4.0)
* udc-campus.jpg: "A Coruña - Universidade da Coruña", de Zarateman. https://commons.wikimedia.org/wiki/File:A\_Coru%C3%B1a\_-\_Universidade\_da\_Coru%C3%B1a.JPG (CC0)
* equipo.jpg: "Group of People Using Laptop Computer", de Christina Morillo. https://www.pexels.com/photo/group-of-people-using-laptop-computer-1181370/ (Licencia de Pexels)
* desarrollador.jpg: "RustCodeOnScreen", de Slashme. https://commons.wikimedia.org/wiki/File:RustCodeOnScreen.jpg (CC0)
* administrador.jpg: "3PAR SAN in the server room", de Alexis Lê-Quôc. https://commons.wikimedia.org/wiki/File:3PAR\_SAN\_in\_the\_server\_room.jpg (CC BY-SA 2.0)
* analista-sistemas.jpg: "SCHÉMA", de SajmonKajtka. https://commons.wikimedia.org/wiki/File:SCH%C3%89MA.jpg (CC BY-SA 4.0)
* ingeniero-ia.jpg: "Ameca Generation 1", de Willy Jackson. https://commons.wikimedia.org/wiki/File:Ameca\_Generation\_1.jpg (CC BY-SA 4.0)
* aprendizaje.jpg: "Artificial Neural Network with Chip", de mikemacmarketing. https://commons.wikimedia.org/wiki/File:Artificial\_Neural\_Network\_with\_Chip.jpg (CC BY 2.0)
* vision.jpg: "Intersection over Union - object detection bounding boxes", de Adrian Rosebrock. https://commons.wikimedia.org/wiki/File:Intersection\_over\_Union\_-\_object\_detection\_bounding\_boxes.jpg (CC BY-SA 4.0)
* analista-datos.jpg: "Infruid's Self-Service BI Tool Dashboard", de Growthlakes. https://commons.wikimedia.org/wiki/File:Infruid%27s\_Self-Service\_BI\_Tool\_Dashboard.jpg (CC BY-SA 4.0)
* cientifico-datos.jpg: "Elderly woman sitting at her office table and holding a cup of coffee while working on her laptop", de Shixart1985. https://commons.wikimedia.org/wiki/File:Elderly\_woman\_sitting\_at\_her\_office\_table\_and\_holding\_a\_cup\_of\_coffee\_while\_working\_on\_her\_laptop.\_Croissant\_and\_a\_donut\_on\_the\_trays\_next\_to\_her.jpg (CC BY 2.0)
* ingeniero-datos.jpg: "BalticServers data center", de BalticServers.com. https://commons.wikimedia.org/wiki/File:BalticServers\_data\_center.jpg (CC BY-SA 3.0)
* udc.png: logotipo de la Universidade da Coruña, de https://www.udc.es/. Lo uso solo para identificar la universidad.
* video.mp4: vídeo de fondo de triángulos blancos, de https://www.pexels.com/ (Licencia de Pexels). Autor y título: no disponible, porque no guardé el enlace.



Uso de IA

Me he apoyado en herramientas de inteligencia artificial (Claude y ChatGPT) para:

* Redactar y mejorar los textos de la web.
* Buscar información sobre los grados y las páginas oficiales de donde sacar los datos.
* Algunas partes del código que no sabía hacer.

He comprobado todos los datos en las fuentes oficiales.

