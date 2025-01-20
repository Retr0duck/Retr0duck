<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Patricio Villarreal</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>¡Hola, soy <span class="highlight">Patricio Villarreal Jimenez</span>! 👋</h1>
  </header>

  <section class="about">
    <h2>👨‍💻 Acerca de Mí</h2>
    <p>¡Saludos desde <span class="highlight">Jalisco, México</span>! Soy un desarrollador especializado en <span class="highlight">backend con Python</span> y también tengo experiencia en el desarrollo frontend para entregar aplicaciones completas y bien diseñadas.</p>
  </section>

  <section class="skills">
    <h2>🚀 Mis Habilidades</h2>
    <div class="skills-list">
      <div>
        <h3>Backend</h3>
        <ul>
          <li>Python</li>
          <li>Django y Flask</li>
          <li>Bases de datos: PostgreSQL, MySQL, SQLite</li>
          <li>APIs RESTful</li>
        </ul>
      </div>
      <div>
        <h3>Frontend</h3>
        <ul>
          <li>HTML5, CSS3, JavaScript</li>
          <li>React.js y Vue.js</li>
          <li>Bootstrap y TailwindCSS</li>
          <li>Redux</li>
        </ul>
      </div>
      <div>
        <h3>Otras Herramientas</h3>
        <ul>
          <li>Git y GitHub</li>
          <li>pip y NPM</li>
          <li>Webpack</li>
          <li>Pytest y Jest</li>
        </ul>
      </div>
    </div>
  </section>

  <section class="projects">
    <h2>💻 Proyectos Destacados</h2>
    <ul>
      <li><strong>Backend para E-commerce:</strong> API RESTful con Django y autenticación robusta.</li>
      <li><strong>Sistema de Gestión Escolar:</strong> Flask + PostgreSQL para manejo de datos académicos.</li>
      <li><strong>Dashboard Interactivo:</strong> Métricas en tiempo real con React y Python.</li>
    </ul>
  </section>

  <footer>
    <p>🌈 <strong>Contacto:</strong> <a href="mailto:paatoo1909@outlook.com">paatoo1909@outlook.com</a> | <a href="https://www.linkedin.com/in/patricio-villarreal-jimenez-276a412a1/">LinkedIn</a></p>
    <p>💬 <strong>Fun Fact:</strong> ¡Me encanta integrar lo mejor del frontend y backend en un proyecto!</p>
  </footer>
</body>
</html>
/* General Styles */
body {
  background-color: #0f0f0f;
  color: #ffffff;
  font-family: 'Roboto Mono', monospace;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

/* Header */
header {
  background: linear-gradient(90deg, #ff0099, #00ccff);
  text-align: center;
  padding: 20px 10px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
}

header h1 {
  font-size: 2.5rem;
  margin: 0;
}

.highlight {
  color: #ffcc00;
  text-shadow: 0 0 8px #ffcc00, 0 0 15px #ffcc00;
}

/* Section Styles */
section {
  padding: 20px;
  margin: 20px auto;
  max-width: 900px;
  border: 2px solid #222222;
  border-radius: 10px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.6);
}

section h2 {
  color: #00ccff;
  text-shadow: 0 0 8px #00ccff, 0 0 15px #00ccff;
  font-size: 1.8rem;
  margin-bottom: 15px;
}

.skills-list {
  display: flex;
  justify-content: space-between;
}

.skills-list div {
  width: 30%;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin: 5px 0;
  color: #ffffff;
}

/* Footer */
footer {
  text-align: center;
  background: #222222;
  padding: 15px;
  border-top: 2px solid #ff0099;
  color: #888888;
}

footer a {
  color: #00ccff;
  text-decoration: none;
}

footer a:hover {
  color: #ff0099;
}

