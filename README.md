from pathlib import Path

# HTML content for the basic CV
cv_html = """
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Currículum Vitae</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      padding: 40px;
      max-width: 800px;
      margin: auto;
      color: #333;
    }
    h1, h2 {
      color: #004080;
    }
    .section {
      margin-bottom: 30px;
    }
    .section p {
      margin: 5px 0;
    }
    ul {
      margin: 0;
      padding-left: 20px;
    }
  </style>
</head>
<body>

  <h1>Currículum Vitae</h1>

  <div class="section">
    <h2>📌 Datos Personales</h2>
    <p><strong>Nombre completo:</strong> lily tamayo</p>
    <p><strong>Fecha de nacimiento:</strong> 24/03/2005</p>
    <p><strong>Dirección:</strong> Av. Santa clara, malvinas</p>
    <p><strong>Teléfono:</strong> 0968677289</p>
    <p><strong>Correo electrónico:</strong> nahomytamayo20@gmail.com</p>
    <p><strong>DNI:</strong> 0943706028</p>
  </div>

  <div class="section">
    <h2>🎓 Formación Académica</h2>
    <p><strong>Colegio Nacional ABC</strong></p>
    <p>Nivel: Secundaria completa</p>
    <p>Años cursados: 2014 – 2019</p>
    <br>
    <p><strong>Curso de Excel Básico - Instituto XYZ</strong></p>
    <p>Estado: Completado</p>
  </div>

  <div class="section">
    <h2>🖥️ Conocimientos y habilidades</h2>
    <ul>
      <li>Manejo básico de computación</li>
      <li>Conocimientos de Microsoft Excel y Word</li>
      <li>Buena disposición para aprender</li>
      <li>Trabajo en equipo</li>
      <li>Puntualidad y responsabilidad</li>
    </ul>
  </div>

  <div class="section">
    <h2>🧰 Experiencia Laboral</h2>
    <p>Actualmente sin experiencia laboral formal.</p>
    <p>Dispuesto a aprender y adaptarme rápidamente al entorno de trabajo.</p>
  </div>

  <div class="section">
    <h2>🗣️ Idiomas</h2>
    <p>Español (nativo)</p>
    <p>Inglés básico</p>
  </div>

  <div class="section">
    <h2>📄 Referencias</h2>
    <p>Disponibles a solicitud.</p>
  </div>

</body>
</html>
"""

# Save the HTML content to a file
file_path = Path("/mnt/data/CV_Juan_Perez.html")
file_path.write_text(cv_html, encoding="utf-8")

file_path.name
