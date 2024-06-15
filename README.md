# Mi-Portafolio

<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portafolio</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <nav id="nav-bar">
      <ul class="ul-nav">
        <li class="nav-li">
          <a href="#bienvenidos" class="a-nav">Bienvenidos</a>
        </li>
        <li class="nav-li"><a href="#Sobre-mi" class="a-nav">Sobre Mi</a></li>
        <li class="nav-li"><a href="#proyectos" class="a-nav">Proyectos</a></li>
        <li class="nav-li"></li>
        <li class="nav-li"><a href="#Contacto" class="a-nav">Contacto</a></li>
      </ul>
    </nav>
    <section id="bienvenidos">
      <h1>Bienvenidos A Mi Portafolio</h1>
      <p>Soy Keidem trainee front-end</p>
    </section>
    <section id="Sobre-mi">
      <h2 class="h2-sobremi">Keidem Pineda</h2>
      <p class="p-sobremi">
        Soy un trainee que esta aprendiendo, estoy en busca de experiencia y
        oportunidades con ganas de ser cada vez mejor y brindar servicios
        excelentes.
      </p>
      <p class="p-sobremi">
        Estoy haciendo una carrera en ingenieria de software, me estoy curtiendo
        en linea aparte de esto buscando informacion de buena calidad para
        aprender mas y desarrollar cada vez mejores proyectos
      </p>
    </section>
    <section id="proyectos">
      <h2>Mis Proyectos</h2>
      <a
        href="https://keidempineda.github.io/El-Phonk/"
        target="_blank"
        title="Enlace Pagina El-Phonk"
        >Pagina Informativa Del Phonk</a
      >
      <img
        src="imagenes/El-Phonk.jpeg"
        alt="Pagina Informativa De El Phonk"
        title="Pagina Informativa De El Phonk"
      />
      <a
        href="https://keidempineda.github.io/Lectores-Sin-Rumbo/"
        target="_blank"
        title="Enlace Pagina Lectores Sin Rumbo"
        >Pagina De Presentacion</a
      >
      <img
        src="Imagenes/lectores.jpeg"
        alt="Pagina De Presentacion"
        title="Pagina De Presentacion"
      />
    </section>
    <form id="Contacto">
      <h2 class="h2-form">Formulario De Contacto</h2>
      <div class="form-input">
        <input type="text" placeholder="Nombre Completo" required />
      </div>
      <div class="form-input">
        <input type="email" rows="7" placeholder="Email" required />
      </div>
      <div class="form-input">
        <textarea placeholder="Deja Tus Comentarios"></textarea>
      </div>
    </form>
  </body>
</html>
