# Practica01-MiBlog
Mi Primer Blog en  HTML5

1.Primero creamos los archivos .html . En este caso pr_inicio, pr_menu, pr_eventos, pr_categoria.

2.Abrimos nuestro archivo pr_inicio.html en nuestro editor HTML.Creamos el encabezado :

	a.Usamos el metaelemento para establecer la codificación de caracteres del archivo en utf-8.
		<meta charset="utf-8" />
	
	b. Agregamos las siguientes palabras clave de búsqueda al documento:Ciberseguridad , Red Hat, Defcon.
		<meta name="keywords" content="Ciberseguridad, RedHat, Defcon, Seguridad ,Informatica" />

	c. Agregamos el titulo del documento Seguridad Informatica.
		<title>Seguridad Informatica</title>

	d. Enlazamos el documento a los archivos de hoja de estilo pr_base.css y pr_layout.css (Estos archivos los utilizaremos de las practicas anteriores).
		<link href="pr_base.css" rel="stylesheet" /> 
		<link href="pr_layout2.css" rel="stylesheet" />

3. Vamos al cuerpo del documento e insertamos un elemento de encabezado que contenga lo siguiente:

	a. Insertamos laimagen con el logo referente al tema que escogimos mp_logo.png con el texto alternativo CIBERSEGURIDAD. marcamos la imagen con un enlace de hipertexto que apunta al archivo pr_inicio.html.
		<a href="mp_index_txt.html"><img src="mp_logo.png" alt="Mobile Panini" /></a>

	b. Creamos una lista de navegación que contiene una lista desordenada con los siguientes elementos de la lista: Inicio, Menú,
	Eventos y Categoria.Enlazamos los elementos .html respectivamente.

		<nav>
		<ul>
    		<li><a href="pr_inicio_txt.html">Index</a></li>
		<li><a href="pr_menu_txt.html">Menu</a></li>
		<li><a href="pr_eventos_txt.html">Events</a></li>
		<li><a href="pr_categoria_txt.html">Catering</a></li>
		</ul>
		</nav>