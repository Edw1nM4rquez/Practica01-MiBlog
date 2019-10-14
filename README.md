# Practica01-MiBlog
Creación de sitio web usando HTML5

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
enlaces telefónicos y correos electrónicos para verificar que abren la aplicación correcta y validamos en la 
siguiente pagina el documento index.html W3C Validator.

8.Nos dirigimos al documento pr_herramienta.html y copiamos el encabezado y pie de pagina del anterior documento ya echo.

	<!Doctype html>
	<html lang="es" xml:lang="es" xmlns="http://www.w3.org/1999/xhtml">
	<head>
	<meta charset="utf-8" />
	<meta name="keywords" content="Ciberseguridad, Black, Hat, Defcon, Seguridad ,Informatica" /> 
	<title>Seguridad Informatica</title>
	<link href="../../css/pr_base.css" rel="stylesheet" /> 
	<link href="../../css/pr_layout.css" rel="stylesheet" />
	</head>
	<body>
	<header>
	<a href="../../pr_index.html"><img src="../../imgs/pr_logo.png" alt="Ciberseguridad" /></a>
    	  <nav>
	<ul>
    	<li><a href="../../pr_index.html">Inicio</a></li>
		<li><a href="pr_menu.html">Herramientas</a></li>
		<li><a href="../general/pr_eventos.html">Eventos</a></li>
		<li><a href="../categoria/pr_categoria.html">Categoria</a></li>
	</ul>
	</nav>
	</header>
	<article>

	</article>
	<footer>
	Edwin Fernando Marquez Lozado &nbsp; Universidad Politecnica Salesiana &#128274; <a href="mail:emarquezl@est.ups.edu.ec">emarquezl@est.ups.edu.ec</a> 
	&nbsp; <a href="tel:+0983364721">(593) 0983364721</a>  &#128274; <br> &nbsp;
	&#169; Todos los derechos reservados
	</footer>
	</body>
	</html>
8.1 Tomemos encuenta que estamso implementando rutas alternativas para llegar hacia los otros documentos.
	
	<link href="../../css/pr_base.css" rel="stylesheet" /> 
	<link href="../../css/pr_layout.css" rel="stylesheet" />


9.Ahora en el cuerpo del documento vamos a poner un Titulo secundario </h2> y utilizaremos la etiqueta <aside>.

<h2>Herramientas para aumentar la seguridad</h2>
<aside>Te recordamos algunas medidas b&aacute;sicas de protecci&oacute;n para navegar por la red de redes,
mitigar el riesgo y proteger datos personales hacia posibles vulnerabilidades:</aside>

10.Ahora vamos a crear una lista ordenada para utilizar las etiquetas ids 
   	
	 <nav>
	<ul>
    	<li><a href="../../pr_index.html">Inicio</a></li>
		<li><a href="pr_menu.html">Herramientas</a></li>
		<li><a href="../general/pr_eventos.html">Eventos</a></li>
		<li><a href="../categoria/pr_categoria.html">Categoria</a></li>
	</ul>
	</nav>

11.Creamos dos secciones con su respectivo ids en las etiquetas <header> ademas de cada articulo tendra una foto como minimo.
 
	<section >
	<article>
	<header id="concept4"><h2>4.-Protege los navegadores</h2></header>
	<img src="../../imgs/pr_photo6.png" alt=" " />
	Todos los navegadores web incluyen caracter&iacute;sticas avanzadas de 
	seguridad cuya activaci&oacute;n debemos revisar y configurar porque son 
	las aplicaciones con las que accedemos a Internet y sus servicios.
	Adem&aacute;s del cifrado de extremo a extremo en la sincronizaci&oacute;n o el 
	aislamiento de procesos (sandbox), debemos prestar atenci&oacute;n a los 
	avisos sobre sitios inseguros que muestran los navegadores. Tambi&eacute;n 
	revisar las extensiones instaladas porque algunas son fuente frecuente
	de introducci&Oacute;n de malware. Otra posibilidad interesante para mejorar
	la privacidad es utilizar una sesi&oacute;n en "Modo Invitado" el cual est&aacute; 
	totalmente desligado del perfil original del usuario, incluyendo configuraci$oacute;n
	o historial.
	</article>
	</section>

12.Nos dirigimos hacia el documento pr_eventos.html copiamos el encabezado y pie de pagina de los documentos enteriores.
 
	<!Doctype html>
	<html lang="es" xml:lang="es" xmlns="http://www.w3.org/1999/xhtml">
	<head>
	<meta charset="utf-8" />
	<meta name="keywords" content="Ciberseguridad, Black, Hat, Defcon, Seguridad ,Informatica" /> 
	<title>Seguridad Informatica</title>
	<link href="../../css/pr_base.css" rel="stylesheet" /> 
	<link href="../../css/pr_layout.css" rel="stylesheet" />
	</head>
	<body>
	<header>
	<a href="../../pr_index.html"><img src="../../imgs/pr_logo.png" alt="Ciberseguridad" /></a>
  	<nav>
	<ul>
    	<li><a href="../../pr_index.html">Inicio</a></li>
		<li><a href="../categoria/pr_herramienta.html">Herramientas</a></li>
		<li><a href="pr_eventos.html">Eventos</a></li>
		<li><a href="../categoria/pr_categoria.html">Categoria</a></li>
	</ul>
	</nav>
	</header>
	<article>

	</article>
	<footer>
	Edwin Fernando Marquez Lozado &nbsp; Universidad Politecnica Salesiana &#128274; <a href="mail:emarquezl@est.ups.edu.ec">emarquezl@est.ups.edu.ec</a> 
	&nbsp; <a href="tel:+0983364721">(593) 0983364721</a>  &#128274; <br> &nbsp;
	&#169; Todos los derechos reservados
	</footer>
	</body>
	</html>

13.Ahora un creamos un subtitulo en el documento.
	<h1>Eventos mas grandes de Ciberseguridad</h1>

14.Ahora vamos a insertar el texto en el siguiente documento.

	<h1>Eventos mas grandes de Ciberseguridad</h1>
  	<aside>
 	<p>La conferencia <strong>Blackhat</strong> muestra las &uacute;ltimas 
 	amenazas mundiales de ciberseguridad. Coches y aparatos conectados a
 	Internet est&aacute;n en el punto de mira.</p>
 	</aside>
	
15.Para la creacion de nuestra tabla avanzada que se solicita tenemos ingresar las siguiientes etiquetas.

		<table border="1" style=”width: 100%”>
			<caption><em>Fecha de las conferencias</em></caption>
			<colgroup>
				<col style="width: 20%"/>
				<col style="width: 40%"/>
				<col style="width: 40%"/>
			</colgroup>
			<thead>
				<tr>
					<th rowspan="2">No.</th>
					<th colspan="2">DEFCON Y BLACK HAT</th>
				</tr>
				<tr>
					<th>Nombre</th>
					<th>Fechas</th>
				</tr>
			</thead>
			<tfoot>
				<tr>
					<td colspan="3"><marquee>Su registro esta disponible hasta el 2 de Agosto</marquee></td>
				</tr>
			</tfoot>
			<tbody>
				<tr>
					<th>1.</th>
					<td>DEFCON</td>
					<td>Agosto 8</td>
				</tr>
				<tr>
					<th>2.</th>
					<td>BLACK HAT</td>
					<td>Agosto 3 - Agosto 8</td>
				</tr>
			</tbody>
		</table>

16.Lo que tenemos que hacer ahora es irnos a nuestro navegador para observar si la pagina no tiene algun problema y como tal ser validada en W3C Validator.

17.Vamos a llegar el documento pr_categoria.html, de la misma manera copiamos los encabezado y pies de paginas de los documentos anteriores.
19.Insertamos el texto o imagenes necesarios en este caso ingresaremos el siguiente texto.
	<h1>Fases de la Ciberseguridad</h1>
	<aside>
	<p>Protegerse ante los peligros de la era actual implica llevar a 
	cabo procesos de ciberseguridad que se sustenten sobre su efectividad 
	y para hacerlo, hay que conocer las fases en las que aplicarlos. Podemos 
	dividir el proceso en tres fases concretas que suelen ser temario habitual d
	el m&aacute;ster en seguridad empresarial: prevenci&oacute;n, localizaci&oacute;n y reacci&oacute;n.</p>
	</aside>

20.Acontinuacion vamos a crear uns lista de definiciones sobre tres faces de la Ciberseguridad.
	<dl>
	<dt>Prevenci&oacute;n</dt>
	<dd>Hay que actuar de forma temprana e informarnos de todo lo que 
	puede ocurrirle a nuestro sistema</dd>

	<dt>Localizaci&oacute;n</dt>
	<dd>Despues de prevenir, en el caso de haber sufrido alg&uacute;n 
	tipo de problema, habr&aacute; que localizar d&oacute;nde radica el problema. </dd>

	<dt>Reacci&oacute;n</dt>
	<dd>Una vez que hemos localizado la amenaza, tendremos 
	que dar una respuesta t&eacute;cnica sobre la misma.</dd>
	<a href="../bibliografia/pr_datos.html"><h2><em>Dr. Chema Alonso </em></h2></a>
	</dl>
21.Con la etiqueta <iframe> que nos ayuda a insertar videos de Youtube en nuestro sitio web.
	a.Primero nos dirigimos hacia el video de youtube que queremos utilizar, hacemos 
	  click en compartir, luego nos vamos a insertar y copiamos el texto por defecto y lo pegamos en nuestra 
	  pagina web.

		<iframe width="524" height="315" 
		src="https://www.youtube.com/embed/Nan74Gxl_SY" frameborder="0" 
		allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
		allowfullscreen></iframe>

22.Para finalizar e creado un nuevo documento pr_datos.html en donde vamos a tener una bibliografia, vamos a enlazarlo con la siguiente linia de etiquetas.
	
		<a href="../bibliografia/pr_datos.html"><h2><em>Dr. Chema Alonso </em></h2></a>

23.Creamos nuestro nuevo documento y lo abrimos  en nuestro editor de html.Copiamos el pie depagina y encabezado de los anteriores documentos 
    ahora lo unico que vamos a hacer es con las etiquetas anteriores ingresamos el texto y una imagen, que son las cosas vacicas que ya emos visto 
    en la creacion de los documentos anteriores.
	
	<a href="../bibliografia/pr_datos.html">Bibliografia</a>

24.De la misma manera validamos la pagina web en W3C Validator y si no tenemos errores o de tal manera arreglamos los mismo y hemos terminado esta practica de crear nuestro 
sitio web .