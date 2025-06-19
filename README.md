<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Explorando los Géneros Literarios - Cobaev 68</title>
  <style>
    body {
      background-color: #f3f0e4;
      font-family: 'Georgia', serif;
      margin: 0;
      padding: 0;
      display: flex;
    }
    nav {
      width: 220px;
      background-color: #d6c6a7;
      padding: 20px;
      box-shadow: 2px 0 5px rgba(0,0,0,0.2);
      height: 100vh;
      position: fixed;
      overflow-y: auto;
    }
    nav a, nav button {
      display: block;
      color: #4b3d2d;
      text-decoration: none;
      margin: 10px 0;
      font-size: 18px;
      background: none;
      border: none;
      width: 100%;
      text-align: left;
      cursor: pointer;
      padding: 0;
      font-family: inherit;
    }
    nav a:hover, nav button:hover {
      color: #6f4e37;
      font-weight: bold;
    }
    .submenu {
      display: none;
      margin-left: 15px;
      margin-top: 5px;
    }
    .submenu a {
      font-size: 16px;
      margin: 5px 0;
      color: #3b2f20;
    }
    .submenu a:hover {
      color: #5a462e;
      font-weight: normal;
    }
    .contenido {
      margin-left: 240px;
      padding: 30px;
      flex-grow: 1;
      max-width: 900px;
    }
    h1 {
      font-size: 45px;
      color: #3e2f1c;
      text-align: center;
      margin-bottom: 40px;
    }
    section {
      margin-bottom: 50px;
      padding: 20px;
      background-color: #fffdf6;
      border-left: 10px solid #ccb089;
      border-radius: 8px;
      box-shadow: 1px 1px 6px #ddd;
    }
    h2 {
      color: #6f4e37;
      border-bottom: 2px solid #ccc;
      padding-bottom: 8px;
      margin-bottom: 20px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 20px;
      font-size: 16px;
    }
    table, th, td {
      border: 1px solid #ccb089;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    th {
      background-color: #d6c6a7;
      color: #4b3d2d;
    }
    img {
      display: block;
      margin: 15px auto;
      max-width: 250px;
      border-radius: 8px;
      box-shadow: 0 0 5px #bbb;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #d6c6a7;
      color: #4b3d2d;
      font-family: Georgia, serif;
      position: fixed;
      bottom: 0;
      width: 100%;
      box-shadow: 0 -2px 5px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>

  <!-- MENÚ LATERAL -->
  <nav>
    <a href="#inicio">📚 Inicio</a>
    <a href="#aventura">🗺️ Aventura</a>
    <a href="#terror">👻 Terror</a>
    <a href="#romance">❤️ Romance</a>
    <a href="#ficcion">🚀 Ciencia Ficción</a>
    <a href="#fantasia">🧙 Fantasía</a>

    <button id="btnAutores">🖋️ Autores Famosos ▼</button>
    <div class="submenu" id="submenuAutores">
      <a href="#autor-gabriel">Gabriel García Márquez</a>
      <a href="#autor-rowling">J.K. Rowling</a>
      <a href="#autor-shakespeare">William Shakespeare</a>
      <a href="#autor-verne">Julio Verne</a>
    </div>

    <a href="#recomendaciones">🏆 Recomendaciones</a>
  </nav>

  <!-- CONTENIDO PRINCIPAL -->
  <div class="contenido">
    <h1>EXPLORANDO LOS GÉNEROS LITERARIOS</h1>

    <!-- INICIO -->
    <section id="inicio">
      <h2>¿Qué es un género literario?</h2>
      <p>Los géneros literarios son las categorías en las que se agrupan las obras literarias, según sus características temáticas, narrativas y emocionales. Nos ayudan a identificar qué tipo de historia vamos a leer: si es emocionante, romántica, de miedo o mágica.</p>
      <p>Existen muchos géneros, pero a continuación te presentamos los más populares y leídos por estudiantes y amantes de la literatura.</p>
    </section>

    <!-- AVENTURA -->
    <section id="aventura">
      <h2>Aventura</h2>
      <table>
        <tr>
          <th>Características</th>
          <th>Ejemplos famosos</th>
          <th>Autores destacados</th>
        </tr>
        <tr>
          <td>
            <ul>
              <li>Viajes a lugares desconocidos</li>
              <li>Riesgos y obstáculos constantes</li>
              <li>Ritmo ágil y escenas emocionantes</li>
            </ul>
          </td>
          <td>
            <ul>
              <li><i>La Isla del Tesoro</i> - Robert Louis Stevenson</li>
              <li><i>Las aventuras de Tom Sawyer</i> - Mark Twain</li>
              <li><i>El Hobbit</i> - J.R.R. Tolkien</li>
            </ul>
          </td>
          <td>Jules Verne, Emilio Salgari, Rick Riordan</td>
        </tr>
      </table>
    </section>

    <!-- TERROR -->
    <section id="terror">
      <h2>Terror</h2>
      <table>
        <tr>
          <th>Características</th>
          <th>Ejemplos famosos</th>
          <th>Autores destacados</th>
        </tr>
        <tr>
          <td>
            <ul>
              <li>Ambientes tenebrosos o misteriosos</li>
              <li>Elementos sobrenaturales (fantasmas, monstruos, maldiciones)</li>
              <li>Suspenso, tensión o miedo psicológico</li>
            </ul>
          </td>
          <td>
            <ul>
              <li><i>Drácula</i> - Bram Stoker</li>
              <li><i>Frankenstein</i> - Mary Shelley</li>
              <li><i>It</i> - Stephen King</li>
            </ul>
          </td>
          <td>Stephen King, H.P. Lovecraft, Edgar Allan Poe</td>
        </tr>
      </table>
    </section>

    <!-- ROMANCE -->
    <section id="romance">
      <h2>Romance</h2>
      <table>
        <tr>
          <th>Características</th>
          <th>Ejemplos famosos</th>
          <th>Autores destacados</th>
        </tr>
        <tr>
          <td>
            <ul>
              <li>Conflictos emocionales y relaciones intensas</li>
              <li>Temas como el amor imposible, el desamor o el reencuentro</li>
              <li>Final feliz o dramático</li>
            </ul>
          </td>
          <td>
            <ul>
              <li><i>Romeo y Julieta</i> - William Shakespeare</li>
              <li><i>Orgullo y prejuicio</i> - Jane Austen</li>
              <li><i>Bajo la misma estrella</i> - John Green</li>
            </ul>
          </td>
          <td>Jane Austen, Nicholas Sparks, Federico Moccia</td>
        </tr>
      </table>
    </section>

    <!-- CIENCIA FICCIÓN -->
    <section id="ficcion">
      <h2>Ciencia Ficción</h2>
      <table>
        <tr>
          <th>Características</th>
          <th>Ejemplos famosos</th>
          <th>Autores destacados</th>
        </tr>
        <tr>
          <td>
            <ul>
              <li>Ambientes futuristas o tecnológicos</li>
              <li>Robots, naves espaciales, inteligencia artificial</li>
              <li>Reflexiones sobre el impacto de la ciencia</li>
            </ul>
          </td>
          <td>
            <ul>
              <li><i>1984</i> - George Orwell</li>
              <li><i>Fahrenheit 451</i> - Ray Bradbury</li>
              <li><i>Un mundo feliz</i> - Aldous Huxley</li>
            </ul>
          </td>
          <td>Isaac Asimov, Philip K. Dick, Ursula K. Le Guin</td>
        </tr>
      </table>
    </section>

    <!-- FANTASÍA -->
    <section id="fantasia">
      <h2>Fantasía</h2>
      <table>
        <tr>
          <th>Características</th>
          <th>Ejemplos famosos</th>
          <th>Autores destacados</th>
        </tr>
        <tr>
          <td>
            <ul>
              <li>Presencia de magia, hechiceros, criaturas fantásticas</li>
              <li>Mundos imaginarios o alternativos</li>
              <li>Viajes épicos, batallas entre el bien y el mal</li>
            </ul>
          </td>
          <td>
            <ul>
              <li><i>Harry Potter</i> - J.K. Rowling</li>
              <li><i>El Señor de los Anillos</i> - J.R.R. Tolkien</li>
              <li><i>Las Crónicas de Narnia</i> - C.S. Lewis</li>
            </ul>
          </td>
          <td>J.K. Rowling, C.S. Lewis, Brandon Sanderson</td>
        </tr>
      </table>
    </section>

   <!-- AUTORES FAMOSOS -->
<section id="autores">
  <h2>Autores Famosos</h2>

  <div id="autor-gabriel">
    <h3>Gabriel García Márquez</h3>
    <p>Gabriel García Márquez fue un escritor, periodista y novelista colombiano, nacido en 1927 y fallecido en 2014. Es conocido como uno de los grandes exponentes del realismo mágico, un estilo que mezcla lo fantástico con lo cotidiano. Su obra más famosa es <i>Cien años de soledad</i>, una saga familiar que ha cautivado a lectores de todo el mundo.</p>
    <p>Ganó el Premio Nobel de Literatura en 1982 por sus novelas y cuentos, donde combinó la política, la historia y la cultura latinoamericana con una narrativa única y mágica.</p>
    <img src="D:\pagina web\gabriel.jpeg" alt="Gabriel García Márquez" />
  </div>

  <div id="autor-rowling">
    <h3>J.K. Rowling</h3>
    <p>Joanne Rowling, mejor conocida como J.K. Rowling, es una escritora británica nacida en 1965. Su fama mundial llegó con la saga de <i>Harry Potter</i>, una serie de siete libros que cuentan las aventuras de un joven mago y sus amigos en un colegio de magia.</p>
    <p>Los libros han sido traducidos a más de 80 idiomas y adaptados a una exitosa serie de películas. Rowling también ha escrito novelas para adultos y trabaja en obras benéficas y proyectos educativos.</p>
    <img src="D:\pagina web\j.k. rowling.jpeg" alt="J.K. Rowling" />
  </div>

  <div id="autor-shakespeare">
    <h3>William Shakespeare</h3>
    <p>William Shakespeare (1564-1616) fue un dramaturgo, poeta y actor inglés considerado uno de los escritores más importantes de la literatura universal. Sus obras incluyen tragedias, comedias y sonetos que exploran temas universales como el amor, el poder, la traición y la humanidad.</p>
    <p>Entre sus obras más conocidas están <i>Romeo y Julieta</i>, <i>Hamlet</i>, <i>Macbeth</i> y <i>El sueño de una noche de verano</i>. Su influencia sigue vigente en la cultura, el teatro y la literatura moderna.</p>
    <img src="D:\pagina web\william shakespeare.jpeg" alt="William Shakespeare" />
  </div>

  <div id="autor-verne">
    <h3>Julio Verne</h3>
    <p>Julio Verne (1828-1905) fue un escritor francés, pionero del género de ciencia ficción y aventura. Sus historias se caracterizan por sus descripciones detalladas de tecnologías futuristas y exploraciones extraordinarias.</p>
    <p>Entre sus obras más famosas están <i>Viaje al centro de la Tierra</i>, <i>20.000 leguas de viaje submarino</i> y <i>La vuelta al mundo en 80 días</i>. Sus relatos inspiraron generaciones de lectores y científicos.</p>
    <img src="D:\pagina web\Julio Verne.jpeg" alt="Julio Verne" />
  </div>
</section>


    <!-- RECOMENDACIONES POR AUTOR -->
<section id="recomendaciones">
  <h2>🏆 Recomendaciones de Libros por Autor</h2>
  <p>Explora algunos de los libros más famosos escritos por grandes autores de la literatura.</p>

  <ul>
    <li>
      <b>Gabriel García Márquez:</b>
      <ul>
        <li><i>Cien años de soledad</i></li>
        <li><i>El amor en los tiempos del cólera</i></li>
        <li><i>Crónica de una muerte anunciada</i></li>
      </ul>
    </li>

    <li>
      <b> J.K. Rowling:</b>
      <ul>
        <li><i>Harry Potter y la piedra filosofal</i></li>
        <li><i>Harry Potter y el prisionero de Azkaban</i></li>
        <li><i>Harry Potter y las Reliquias de la Muerte</i></li>
      </ul>
    </li>

    <li>
      <b> William Shakespeare:</b>
      <ul>
        <li><i>Romeo y Julieta</i></li>
        <li><i>Hamlet</i></li>
        <li><i>Otelo</i></li>
      </ul>
    </li>

    <li>
      <b> Julio Verne:</b>
      <ul>
        <li><i>Viaje al centro de la Tierra</i></li>
        <li><i>20.000 leguas de viaje submarino</i></li>
        <li><i>La vuelta al mundo en 80 días</i></li>
      </ul>
    </li>

    <li>
      <b> Jane Austen:</b>
      <ul>
        <li><i>Orgullo y prejuicio</i></li>
        <li><i>Emma</i></li>
        <li><i>Sentido y sensibilidad</i></li>
      </ul>
    </li>

    <li>
      <b> Stephen King:</b>
      <ul>
        <li><i>It</i></li>
        <li><i>El resplandor</i></li>
        <li><i>Cementerio de animales</i></li>
      </ul>
    </li>

    <li>
      <b>George Orwell:</b>
      <ul>
        <li><i>1984</i></li>
        <li><i>Rebelión en la granja</i></li>
      </ul>
    </li>

    <li>
      <b> Pablo Neruda:</b>
      <ul>
        <li><i>Veinte poemas de amor y una canción desesperada</i></li>
        <li><i>Canto general</i></li>
      </ul>
    </li>
  </ul>
</section>
  </div>
<section id="galeria-libros">
  <h2>📚 Galería de Libros Recomendados</h2>
  <p>Estos libros han cautivado a millones de lectores. ¿Cuál te gustaría leer?</p>
  
  <div style="display: flex; flex-wrap: wrap; gap: 20px;">
    <div>
      <img src="D:\pagina web\boulevard.jpeg" alt="Boulevard - Flor M. Salvador" width="150">
      <p><b>Boulevard</b><br>Flor M. Salvador</p>
    </div>

    <div>
      <img src="D:\pagina web\Bajo la misma estrella libro.jpg" alt="Bajo la misma estrella - John Green" width="150">
      <p><b>Bajo la misma estrella</b><br>John Green</p>
    </div>

    <div>
      <img src="D:\pagina web\romeo y julieta.jpeg" alt="Romeo y Julieta - Shakespeare" width="150">
      <p><b>Romeo y Julieta</b><br>William Shakespeare</p>
    </div>

    <div>
      <img src="D:\pagina web\a dos metros de ti.jpeg" alt="A dos metros de ti - Rachael Lippincott" width="150">
      <p><b>A dos metros de ti</b><br>Rachael Lippincott</p>
    </div>

    <div>
      <img src="D:\pagina web\despues de ti.jpeg" alt="Después de ti - Jojo Moyes" width="150">
      <p><b>Después de ti</b><br>Jojo Moyes</p>
    </div>

    <div>
      <img src="D:\pagina web\coraline.jpeg" alt="Coraline - Neil Gaiman" width="150">
      <p><b>Coraline</b><br>Neil Gaiman</p>
    </div>

    <div>
      <img src="D:\pagina web\principito.jpeg" alt="El Principito - Antoine de Saint-Exupéry" width="150">
      <p><b>El Principito</b><br>Antoine de Saint-Exupéry</p>
    </div>

    <div>
      <img src="D:\pagina web\it.jpeg" alt="It - Stephen King" width="150">
      <p><b>It (Eso)</b><br>Stephen King</p>
    </div>
  </div>
</section>
     <footer>
    <p>© 2025 Nuestros autores: Yamileth Vazquez y Ángeles Esteban Hernandez</p>
  </footer>

  <script>
    const btnAutores = document.getElementById('btnAutores');
    const submenuAutores = document.getElementById('submenuAutores');

    btnAutores.addEventListener('click', () => {
      if (submenuAutores.style.display === 'block') {
        submenuAutores.style.display = 'none';
        btnAutores.textContent = ' Autores Famosos ▼';
      } else {
        submenuAutores.style.display = 'block';
        btnAutores.textContent = ' Autores Famosos ▲';
      }
    });
  </script>
  <button onclick="reproducir()">Reproducir música</button>
  <script>
    const audio = new Audio('dance-of-the-sugar-plum-fairy.mp3');

    function reproducir() {
      audio.play().catch(error => {
        console.error("Error al reproducir:", error);
      });
    }
  </script>
</body>
</html>
