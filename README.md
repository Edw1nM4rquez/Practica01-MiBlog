# Practica01-MiBlog
Mi Primer Blog en  HTML5

1.Primero creamos los archivos .html . En este caso pr_index.html, pr_menu.html, pr_eventos.html, pr_categoria.hmtl.

2.Abrimos nuestro archivo pr_inicio.html en nuestro editor HTML.Creamos el encabezado :

	a.Usamos el metaelemento para establecer la codificación de caracteres del archivo en utf-8.
		<meta charset="utf-8" />
	
	b. Agregamos las siguientes palabras clave de búsqueda al documento:Ciberseguridad , Red Hat, Defcon.
		<meta name="keywords" content="Ciberseguridad, RedHat, Defcon, Seguridad ,Informatica" />

	c. Agregamos el titulo del documento Seguridad Informatica.
		<title>Seguridad Informatica</title>

	d. Enlazamos el documento a los archivos de hoja de estilo pr_base.css y pr_layout.css (Estos archivos los utilizaremos de las practicas anteriores).
		<link href="css/pr_base.css" rel="stylesheet" /> 
		<link href="css/pr_layout.css" rel="stylesheet" />

3. Vamos al cuerpo del documento e insertamos un elemento de encabezado que contenga lo siguiente:

	a. Insertamos laimagen con el logo referente al tema que escogimos mp_logo.png con el texto alternativo CIBERSEGURIDAD. marcamos la imagen con un enlace de hipertexto que apunta al archivo pr_inicio.html.
		
		<a href="pr_index.html"><img src="imgs/pr_logo.png" alt="Ciberseguridad" /></a>

	b. Creamos una lista de navegación que contiene una lista desordenada con los siguientes elementos de la lista: Inicio, Menú,
	Eventos y Categoria.Enlazamos los elementos .html respectivamente.
    		<nav>
		<ul>
    		<li><a href="pr_index.html">Inicio</a></li>
		<li><a href="docs/categoria/pr_menu.html">Menu</a></li>
		<li><a href="docs/general/pr_eventos.html">Events</a></li>
		<li><a href="docs/categoria/pr_categoria.html">Catering</a></li>
		</ul>
		</nav>

4.Creamos nuestro pie de pagina con las siguientes caracteristicas : 
	Nombres completos, organización, correo (usar hipervínculo, mailto), teléfono
	(usar hipervínculo, tel), además deberá tener el símbolo de copyright junto a la
	leyenda de “Todos los derechos reservados”. Por ejemplo, © Todos los derechos
	reservados.
	<footer>
	Edwin Fernando Marquez Lozado &nbsp; Universidad Politecnica Salesiana &#128274; <a href="mail:emarquezl@est.ups.edu.ec">emarquezl@est.ups.edu.ec</a> 
	&nbsp; <a href="tel:+0983364721">(593) 0983364721</a>  &#128274; <br>&nbsp;
	&#169; Todos los derechos reservados
	</footer>

5.Agregamos texto en nuestra pagina de inicio con lo referente al tema que escogimos.

6.Dentro del elemento del articulo hacemos lo siguiente:

		a.Vamos a crear una seccion en la cual añadimos una imagen y un concepto de ciberseguridad. 
		a.b.Marcamos el titulo con un encabezado de h1.

			<h1>Ciberseguridad</h1>

		a.c.Debajo del elemento h1 insertamos una imagen, con una cadena de texto vacia.
			<img src="imgs/pr_photo1.png" alt=" " />		
	 	
		a.d.Separamos el texto en dos parrafos y utilizamos la etiqueta <strong> para resaltar con negrita la palabra "ciberseguridad"
		    ademas utilizamos la etiqueta <em> para realzar el texto "proteccion de activos de informacion"
			
			<section>
			<h2>Que es la ciberseguridad? </h2>
			<img src="imgs/pr_photo1.png" alt=" " />
			<p>La <strong>ciberseguridad</strong> se define como una capa de protecci&oacute;n para 
			los archivos de informaci&oacute;n, a partir de ella, se trabaja para
			evitar todo tipo de amenazas, las cuales ponen en riesgo la informaci&oacute;n 
			que es procesada, transportada y almacenada en cualquier dispositivo.</p>

			<p>Es la <em>protecci&oacute;n de activos de informaci&oacute;n</em>, a trav&eacute;s del tratamiento de
			amenazas que ponen en riesgo la informaci&oacute;n que es procesada, almacenada
			y transportada por los sistemas de informaci&oacute;n que se encuentran interconectados.</p>
			</section>
			
		b.De la misma manera nos creamos otra seccion para destacar lo mas deseado hoy de la ciberseguridad, siguiendo los pasos anteriores de nuestra seccion.
			
			<section>
			<h2>Lo mas deseado !</h2>
			<p>Las empresas necesitan de estos profesionales ya que saben que la
			prevenci&oacute;n es la clave para proteger la informaci&oacute;n y no verse 
			inmiscuido en situaciones de debilidades con secuelas inmensas
			para dichas empresas.<br>Por tanto, estar formado en ciberseguridad 
			es una muy buena opci&oacute;n para encontrar empleo a d&iacute;a de hoy.</p>
			</section>

7.Guardamos los cambios en el archivo y luego abra el archivo mp_index.html en su navegador. Probamos los
enlaces telefónicos y correos electrónicos para verificar que abren la aplicación correcta y validamos en la siguiente pagina el documento index.html W3C Validator.