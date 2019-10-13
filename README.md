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
		<link href="pr_layout.css" rel="stylesheet" />

3. Vamos al cuerpo del documento e insertamos un elemento de encabezado que contenga lo siguiente:

	a. Insertamos laimagen con el logo referente al tema que escogimos mp_logo.png con el texto alternativo CIBERSEGURIDAD. marcamos la imagen con un enlace de hipertexto que apunta al archivo pr_inicio.html.
		<a href="pr_inicio.html"><img src="imgs/pr_logo.png" alt="Ciberseguridad" /></a>

	b. Creamos una lista de navegación que contiene una lista desordenada con los siguientes elementos de la lista: Inicio, Menú,
	Eventos y Categoria.Enlazamos los elementos .html respectivamente.

		<nav>
		<ul>
    		<li><a href="pr_index.html">Inicio</a></li>
		<li><a href="pr_menu.html">Menu</a></li>
		<li><a href="pr_eventos.html">Eventos</a></li>
		<li><a href="pr_categoria.html">Categoria</a></li>
		</ul>
		</nav>
4.Creamos nuestro pie de pagina con las siguientes caracteristicas : 
	Nombres completos, organización, correo (usar hipervínculo, mailto), teléfono
	(usar hipervínculo, tel), además deberá tener el símbolo de copyright junto a la
	leyenda de “Todos los derechos reservados”. Por ejemplo, © Todos los derechos
	reservados.
	<footer>
	Edwin Fernando Marquez Lozado &nbsp; Universidad Politecnica Salesiana &#128274; <a href="mail:emarquezl@est.ups.edu.ec">emarquezl@est.ups.edu.ec</a> 
	&nbsp; <a href="tel: +0983364721">(593) 0983364721</a>  &#128274; <br>&nbsp;
	&#169 Todos los derechos reservados
	</footer>

5.Agregamos texto en nuestra pagina de inicio con lo referente al tema que escogimos.

6.Dentro del elemento del articulo hacemos lo siguiente:
		a.Marcamos  
		b.
		c.
		d.
		e.
