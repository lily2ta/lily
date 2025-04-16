from pathlib import Path

# Contenido del archivo HTML personalizado
html_content = """<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Currículum de [Tu Nombre]</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #f0f4c3, #ffffff);
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #558b2f;
      color: white;
      padding: 40px 20px;
      text-align: center;
      border-bottom: 5px solid #33691e;
    }

    h1 {
      margin: 0;
      font-size: 2.5em;
    }

    h2 {
      color: #33691e;
      border-bottom: 2px solid #aed581;
      padding-bottom: 5px;
      margin-top: 30px;
    }

    .container {
      padding: 20px 50px;
    }

    .section {
      margin-bottom: 30px;
    }

    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    .skill {
      background-color: #dcedc8;
      display: inline-block;
      padding: 6px 12px;
      margin: 5px;
      border-radius: 12px;
      font-weight: bold;
      color: #33691e;
    }

    footer {
      background-color: #f1f8e9;
      text-align: center;
      padding: 20px;
      font-style: italic;
      border-top: 2px dashed #aed581;
    }
  </style>
</head>
<body>
  <header>
    <h1>[Tu Nombre]</h1>
    <p>Postulante a Auxiliar de Bodega</p>
  </header>

  <div class="container">
    <div class="section">
      <h2>Perfil</h2>
      <p>Soy una persona responsable, puntual y con muchas ganas de aprender. Estoy dispuesto a asumir nuevos retos y a integrarme a un equipo de trabajo comprometido.</p>
    </div>

    <div class="section">
      <h2>Formación Académica</h2>
      <ul>
        <li>Educación secundaria completa</li>
        <li>Estudios técnicos en curso o incompletos</li>
      </ul>
    </div>

    <div class="section">
      <h2>Habilidades</h2>
      <span class="skill">Microsoft Excel</span>
      <span class="skill">Puntualidad</span>
      <span class="skill">Trabajo en equipo</span>
      <span class="skill">Responsabilidad</span>
    </div>

    <div class="section">
      <h2>Experiencia Laboral</h2>
      <p>Aún no tengo experiencia laboral formal, pero tengo disposición para aprender rápidamente y adaptarme a cualquier función asignada.</p>
    </div>
  </div>

  <footer>
    <p>Estilos utilizados:</p>
    <p>
      Se aplicó un <strong>degradado de fondo suave</strong> para dar una apariencia limpia y profesional.  
      Se usaron <strong>colores verdes</strong> para transmitir frescura, confianza y crecimiento.  
      Los títulos llevan <strong>bordes inferiores decorativos</strong> y las habilidades tienen un diseño tipo etiqueta, con <strong>bordes redondeados</strong> y colores llamativos.  
      Se utilizó una <strong>tipografía moderna y legible</strong> para facilitar la lectura.
    </p>
  </footer>
</body>
</html>
"""

# Guardar como archivo HTML
output_path = Path("/mnt/data/CV_estilizado.html")
output_path.write_text(html_content, encoding="utf-8")

output_path.name  # Mostrar nombre del archivo generado

