<!doctype html>
<html>

  <head>
    <meta charset="utf-8">
    <meta name="author" content="Nombre Principal">
    <meta name="description" content="Mi primera página web">
    <meta name="keywords" content="Palabras clave que deben aparecer">
    <title>NOMBRE PESTAÑA</title>
    <link rel="icon" href="direccionimagenenordenador">
  </head>

  <body>
    <header>
    <!--cabecera de la página web-->
    </header>

    <nav>
    <!-- Barra de navegación-->
    </nav>

    <section>
    <!-- Secciones-->
    </section>

    <aside>
    <!-- Columnas-->
    </aside>

    <article>
    <!-- Artículo-->
    </article>

    <h1>
    <!-- Título (se ve más grande o pequeño según el número que acompaña la h h1, h2, h3, h4, h5 y h6-->
    </h1>

    <p>
    <!-- Párrafo-->
    </p>

    <b>
    <!-- Negrita-->
    </b>

    <br> <!-- Es un salto de línea o un intro (no necesita fin)-->

    <hr> <!-- Línea que separa la página-->

    <a href="Hacia donde va el link - botón">
    Nombre de vínculo
    <!-- Link - botón-->
    </a>
    
    <img src="rutadelaimagen">
    <!-- Imagenes sueltas-->
    
    <figure>
    <img src="rutadelaimagen">
    </figure>

    <figcaption>
    Pie de página
    </figcaption>

   
    <ol>
    <!-- Lista numérica-->
      <li> Opción lista 1</li>
      <li> Opción lista 2</li>   
    </ol>
   
    <ul>
    <!-- Lista con puntos o otros iconos-->
      <li> Opción lista 1</li>
      <li> Opción lista 2</li>   
    </ul>

    <table border="l">
    <!-- Tablas-->
    <thead> 
    <!-- Cabezera de la tabla - Van en negrita-->
      <tr> 
      <!-- tr - Filas de la tabla-->
          <th> Titulo 1 </th>  
          <!-- th - Columnas de la tabla-->
          <th> Titulo 2 </th> 
      </tr> 
    </thead>
    <tbody>
    <!-- Cuerpo de la tabla-->
      <tr> 
          <td> Columna 1 </td>
          <!-- Dentro del cuerpo las columnas van con td-->  
          <td> Columna 2 </td> 
      </tr> 
      <tr> 
          <td> Columna 1 </td>  
          <td> Columna 2 </td> 
      </tr> 
    </tbody>
    </table>

    <meter value="94" min="0" max="100" high="90">
    <!-- Barras de porcentaje de mínimo a máximo y si pasa la media (high) aparece en otro color -->
    </meter>

    <progress value="94" min="0" max="100">
    <!-- Barras de porcentaje de mínimo a máximo diseño muy sencillo -->
    <!-- Safari y app no se lee etiqueta meter -->
    </progress value="94" min="0" max="100">

    <audio autoplay controls loop preload="auto">
    <!-- Autoplay - reproductor automático -->
    <!-- Controls - se puede controlar y pausar -->
    <!-- loop - se va reproduciendo continuamente -->
    <!-- preload - auto (carga automáticamente) - metadata (descarga para reproducir) - none (solo empieza si el usuario quiere) -->
    <!-- Ogg VORBIS .ogg / para navegadores firefox, chrome y opera -->
    <!-- Mp3 .mp3 / para navegadores safari, chrome, explorer y iOS -->
    <!-- WAV NO COMPRIMIDOS .wav / No es recomendado para navegadores -->
    <!-- ACC parecido a MP3 .m4a .m4b .m4p .mp4 .acc -->
    <!-- .m4a .mp3 .ogg / Recomendable uno de cada para que por defecto se lea el que toca segun navegador -->
    <source src="rutadesonido" type="audio/mp4">
    </audio>

    <video autoplay controls loop width="500" height="200">
    <!-- THEORA .ogv / para navegadores firefox, chrome y opera -->
    <!-- Mp4 .mp4 / para navegadores safari, chrome, explorer, iOS y Android -->
    <!-- WEBM .webm / para TODOS navegadores menos safari y iOS -->
    <!-- .ogv .mp4 .webm / Recomendable uno de cada para que por defecto se lea el que toca segun navegador -->
    <source src="rutadevideo" type="video/mp4">
    </video>

    <iframe width="500" height="200" src="https://www.youtube.com/embed/códigodevideo" frameborder="0" allowfullscreen>
    <!-- En algunas páginas podemos copiar el iframe de el source / embed que aparece con la flechita-->
    <!-- También hay vínculos de sonido, revistas, mapas o otras páginas que podemos poner como embed-->
    <!-- scrolled="auto" links o revistas que queramos poder mover porque ocupen mucho espacio-->
    </iframe>

    <div>
    Logotipo
    <!-- Divisiones en cualquier espacio-->
    </div>
    
    <div class="noticias" id="division1"> Division 1 </div>
    <div class="noticias" id="division2"> Division 2 </div>
    <div class="noticias" id="division3"> Division 3 </div>
    
    <center>
    <h2>
    Título centrado
    </h2>
    </center>

    <form>
      <label for="texto"> Entrada de texto </label>
      <input id="texto" type="text" placeholder="Escribir nombre y apellidos" value="" required> 
      <!-- Dentro de la cajita de texto lo que se debe poner -->
      <!-- readonly etiqueta que indica solo de lectura -->
      
      <label for="mail"> Entrada de e-mail </label>
      <input id="mail" type="email" placeholder="Escribir e-mail" value="" required> 
      
      <label for="pass"> Contraseña </label>
      <input id="pass" type="password" placeholder="Contraseña" value="" required> 
  
      <label for="tlf"> Número de teléfono </label>
      <input id="tlf" type="number" placeholder="Teléfono" value="" required> 

      <input type="number" value="1" min="0" max="10">
   
      <select>
        <option> Opción 1 </opcion>
        <option> Opción 2 </opcion>
        <option> Opción 3 </opcion>
      </select>
     
      <input id="rojo" type="checkbox"> <label for="rojo"> Rojo </label>
      <input id="azul" type="checkbox"> <label for="azul"> Azul </label>
      <input id="verde" type="checkbox"> <label for="verde"> Verde </label>
      <!-- Cajitas para seleccionar - multiple seleccion -->
  
      <input id="hombre" type="radio" name="circulo"> <label for="hombre"> Hombre </label> 
      <input id="mujer" type="radio" name="circulo" checked> <label for="mujer"> Mujer </label> 
      <!-- Círculos - name es para seleccion unica / checked ya sale seleccionado -->

      <input type="sumbit" value="Enviar Formulario">
      
    </form>

    <footer>
    Este es el pie de página
    </footer>

  </body>

</html>
