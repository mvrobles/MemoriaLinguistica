---
title: " "
hide:
  - navigation
  - toc  # Oculta la barra de navegación
  - edit
  - path
  - header
  - footer
---
<style>
  /* Ajustes generales */
  html, body {
    margin: 0 !important;
    padding: 0 !important;
    width: 100vw;
    max-width: 100vw;
    overflow-x: hidden !important;
  }

  Barra de navegación superior con imagen de fondo
  .md-header {
    background: url('images/tejido.png') no-repeat center center;
    background-size: cover;
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white !important;
  }

  .md-header__title {
    display: none !important;
  }

  .header-image {
    display: none;
  }

  .md-content__title {
    display: none;
  }

  /* Contenedor del título principal */
  .page-title {
    text-align: center;
    margin-top: 20px;
    font-size: 2.5em;
    font-weight: bold;
    color: #333;
  }

  /* Contenedor del título y descripción */
  .text-container {
    text-align: center;
    background: #f8f9fa;
    padding: 10px 20px;
    max-width: 80%;
    margin: 10px auto;
  }

  .text-container h1 {
    font-size: 2em;
    margin-bottom: 5px;
  }

  .text-container h2 { 
  font-size: 2em;
  font-weight: bold;
  color: #333;
  text-align: center;
}

  .text-container p {
    font-size: 1.2em;
  }

  /* Sección de resumen y metodología */
  .content-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    padding: 5px 1%;
  }

  .a {
    color:rgb(45, 234, 218) !important; /* Orange color */
    text-decoration: none; /* Optional: removes underline */
  }

  .summary {
    flex: 1;
    min-width: 50%;
    padding-right: 10px;
  }

  .methodology-image {
    flex: 1;
    min-width: 40%;
    text-align: center;
  }

  .methodology-image img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow:  #ea812d;
  }

.resource-container {
  display: flex;
  flex-direction: column; /* Stack elements vertically */
  align-items: center; /* Center the boxes */
  gap: 10px; /* Add some spacing between the boxes */
}

.resource-box {
  width: 85%; /* Adjust width as needed */
  padding: 15px;
  border-radius: 4px;
  text-align: left;
  list-style: none;
}

.resource-box h2 {
    font-size: 2em;
    margin-bottom: 5px;
    color: #333;
    margin-top: 0; /* Remove extra top margin */
    padding-top: 0;
  }
  /* Cinta naranja con logos de empresas */
  .partner-logos {
    width: 100vw;
    max-width: 100vw;
    background-color: #ea812d;
    margin: 0;
    padding: 10px 0;
    box-sizing: border-box;
    overflow: hidden;
    text-align: center;
  }

  .partner-logos h3 {
    color: #fff;
    font-size: 1.5em;
    margin-bottom: 10px;
  }

  .logo-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 15px;
    flex-wrap: wrap;
  }

  .logo-container img {
    max-height: 50px;
    width: auto;
    transition: filter 0.3s ease;
  }

  .logo-container img:hover {
    filter: grayscale(0%);
  }

  .timeline-section {
    text-align: center;
    padding: 10px 10px;
    background: #f8f9fa;
  }

  .timeline-section h2 {
    font-size: 2em;
    margin-bottom: 15px;
    color: #333;
  }

  .timeline-container {
    display: flex;
    justify-content: space-around;
    align-items: stretch;
    gap: 10px;
    flex-wrap: nowrap; /* Mantiene los rectángulos en una fila */
    max-width: 1000px;
    margin: auto;
  }

  .timeline-box {
    background: #ea812d;
    color: black;
    padding: 10px;
    border-radius: 10px;
    width: 30%;
    text-align: center;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
  }

  .timeline-box h3 {
    margin-bottom: 5px;
    font-size: 1.5em;
  }

  .timeline-box p {
    font-size: 1em;
  }

  .footer-section {
      width: 100vw; /* Full width of the viewport */
      position: relative;
      left: 50%;
      right: 50%;
      margin-left: -50vw;
      margin-right: -50vw;
      
      display: flex;
      justify-content: space-between;
      align-items: center;
      
      background:#8bd1c2; 
      color: black;;
      padding: 40px;
      box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.2);
  }

  .footer-left {
      flex: 1;
      padding-left: 10%;
  }

  .footer-left h2 {
      font-size: 1.8em;
      margin-bottom: 10px;
  }

  .footer-left p {
      font-size: 1.2em;
      margin: 5px 0;
  }

  .footer-left a {
      color: white;
      font-weight: bold;
      text-decoration: underline;
  }

  .footer-right {
      flex: 0.5;
      display: flex;
      justify-content: flex-end;
      padding-right: 10%;
  }

  .uniandes-logo {
      width: 200px;
      filter: drop-shadow(2px 2px 5px rgba(0, 0, 0, 0.3));
  }


  /* Container for the team section */
  .team-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    padding: 0px;
  }

  /* Individual team member card */
  .team-member {
    text-align: center;
    max-width: 250px;
  }

  /* Profile image styling */
  .team-member img {
    width: 150px; /* Reduced width */
    height: 150px; /* Reduced height */
    object-fit: cover;
    border-radius: 50%;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
  }

  /* Name and role */
  .team-member h3 {
    margin: 10px 0 5px;
    font-size: 1.4em;
  }

  .team-member p {
    font-size: 1.1em;
    color: #555;
  }



  @media (max-width: 900px) {
    .timeline-container {
      flex-wrap: wrap; /* Permite que los rectángulos se acomoden en varias filas si la pantalla es pequeña */
    }
    .timeline-box {
      width: 100%; /* Hace que los rectángulos ocupen toda la línea en pantallas pequeñas */
    }
</style>

<!-- Barra de navegación fija con logo DISC (alineado con margen izquierdo de sección especial) -->
<div class="custom-navbar">
  <div class="navbar-container">
    <a href="https://sistemas.uniandes.edu.co/" class="navbar-logo">
      <img src="images/logos/logo_disc.png" alt="Logo DISC">
    </a>
  </div>
</div>



<!-- Sección Principal -->
<div class="hero">
  <div class="hero-text">
    <h2>Towards cultural preservation</h2>
    <h1>Machine Translation for Indigenous Language Preservation</h1>
    <p>
      Indigenous languages in Colombia face the risk of extinction due to the decline in native speakers and lack of digital resources. This project leverages AI-driven machine translation models tailored for low-resource languages, aiming to create digital tools that support linguistic preservation. Additionally, we are actively working on translations to expand the available datasets for Indigenous language machine translation, ensuring better model performance and broader linguistic coverage.
    </p>
  </div>
  <div style="margin-right: 40px;"></div>
  <div class="hero-image">
    <img src="images/logoGPT2.webp" alt="Logo">
  </div>
</div>



-------

<!-- Sección de Línea de Tiempo -->
<div style="text-align: center;">
  <h2 style="font-weight: bold;">Project Timeline</h2>

  <div class="timeline-container">
    <div class="timeline-box" style="background: rgba(145,197,177,0.8);">
      <h3>2023</h3>
      <p>The project began as an academic initiative in the NLP course of the Master’s in Systems Engineering at Universidad de los Andes. Our research focused on translation models for low-resource languages, specifically studying Wayuunaiki and Ika. The results were presented at WSDM.</p>
    </div>
    <div class="timeline-box" style="background: rgba(255,148,8,0.8);">
      <h3>2024</h3>
      <p>The project continued with data collection for Wayuunaiki, Ika, Inga, and Nasa Yuwe. The results were presented at the 4th Workshop on NLP for Indigenous Languages of the Americas. We also started working with a translator of Wayuunaiki to increase the quality and accuracy of our datasets.</p>
    </div>
    <div class="timeline-box" style="background: rgba(238,192,82,0.8);">
      <h3>2025</h3>
      <p>Our datasets were included in AmericasNLP 2025, marking the first time that Colombian Indigenous languages were represented in the initiative. Additionally, we have started working with a Nasa Yuwe translator and are actively seeking new collaborations to further expand and improve our work.</p>
    </div>
  </div>
</div>

------------

<div style="display: flex; align-items: center; justify-content: space-between; max-width: 1000px; margin: auto;">
  <img src="images/MT_Finetuning_en.png" alt="Translation Model" style="width: 50%; border-radius: 10px; margin-right: 10px;">
  <div style="width: 45%; text-align: left;">
    <h2 style="font-weight: bold;">Our Methodology</h2>
    <p>We leverage high-resource language models to develop translators for low-resource Indigenous languages.  
       To achieve this, we gather valuable, high-quality translations of short phrases into Spanish,  
       working closely with native speakers and expert translators.</p>
  </div>
</div>



------------

<div style="display: flex; align-items: center; justify-content: space-between; max-width: 1000px; margin: auto;">
  <div style="width: 45%; text-align: left;">
    <h2 style="font-weight: bold;">Our Languages</h2>
    <p>Colombia is home to a rich linguistic heritage, including Wayuunaiki, Nasa Yuwe, Inga, and Arhuaco.  
       We collaborate with native speakers to support these languages:</p>
    <ul>
      <li><strong style="color:rgb(213, 74, 62);">Wayuunaiki</strong> – Spoken by the Wayuu people in La Guajira, it is the most widely spoken Indigenous language in Colombia.</li>
      <li><strong style="color:rgb(32, 117, 145);">Nasa Yuwe</strong> – Used by the Nasa community in Cauca and neighboring regions, it is considered an isolated language with unique grammar.</li>    
      <li><strong style = "color:rgb(38, 133, 49);">Inga</strong> – A Quechuan language spoken in Putumayo and Nariño, preserving Incan linguistic traditions.</li>
      <li><strong  style = "color:rgb(99, 93, 207);">Arhuaco (Ika)</strong> – A Chibchan language spoken in the Sierra Nevada de Santa Marta, known for its complex structure.</li>
    </ul>
    <p>By working with native speakers, we help preserve and strengthen these languages through high-quality translations and language technology.</p>
  </div>
  <img src="images/mapa.jpeg" alt="Translation Model" style="width: 50%; border-radius: 10px; margin-left: 10px;">
</div>
-------

<div style="text-align: center;">
  <h2 style="font-weight: bold;">Resources</h2>

  <div class="resource-container">
    <div class="resource-box" style="background: rgba(145,197,177,0.8);">
      <h3>Datasets</h3>
    </div>
    <div class="resource-box" style="background: rgba(255,148,8,0.8);">
      <h3>Models</h3>
      <li> <a href="https://www.dropbox.com/scl/fo/bj7ra25nbf0bjed5f6y92/ANxU5o3Qc0t1a-91dKbRcv4?rlkey=ag6dssslslwiqjrtg6kd8a8ym&st=ejt0m93b&dl=0" target="_blank">Wayuunaiki, Inga, Nasa Yuwe and Arhuaco models</a></li>
    </div>
    <div class="resource-box" style="background: rgba(238,192,82,0.8);">
      <h3>Publications</h3>
      <ul>
        <li>Preserving Heritage: Developing a Translation Tool for Indigenous Dialects. In Proceedings of the 17th ACM International Conference on Web Search and Data Mining (WSDM '24). <a href="https://doi.org/10.1145/3616855.3637828" target="_blank">https://doi.org/10.1145/3616855.3637828</a></li>
        <li>Translation systems for low-resource Colombian Indigenous languages, a first step towards cultural preservation. In Proceedings of the 4th Workshop on Natural Language Processing for Indigenous Languages of the Americas (AmericasNLP 2024).<a href="https://aclanthology.org/2024.americasnlp-1.2/" target="_blank">https://aclanthology.org/2024.americasnlp-1.2/</a></li>
      </ul>
    </div>
  </div>
</div>
-------

<div style="text-align: center;">
  <h2 style="font-weight: bold;">Our team</h2>
</div>
<div class="team-container">
  
  <!-- Team Member 1 -->
  <div class="team-member">
    <img src="/images/team/ruben.jpg" alt="Rubén Manrique">
    <h3>Rubén Manrique</h3>
    <p>Lead Researcher</p>
    <p>Universidad de Los Andes</p>
  </div>

  <!-- Team Member 2 -->
  <div class="team-member">
    <img src="/images/team/juanca.jpg" alt="Person 2">
    <h3>Juan Camilo Prieto</h3>
    <p>Researcher</p>
    <p>Universidad de Los Andes</p>
  </div>

  <!-- Team Member 3 -->
  <div class="team-member">
    <img src="/images/team/melissa.jpg" alt="Person 3">
    <h3>Melissa Robles</h3>
    <p>Researcher</p>
    <p>Universidad de Los Andes</p>
  </div>

  
  <!-- Team Member 1 -->
  <div class="team-member">
    <img src="/images/team/wayuunaiki.jpg" alt="Antonio José Ipuana">
    <h3>Antonio José Ipuana</h3>
    <p>Wayuunaiki Translator</p>
    <p>Wayuunaiki translation services</p>
  </div>

  <!-- Team Member 2 -->
  <div class="team-member">
    <img src="/images/team/unicauca.png" alt="Manuel Muyuy">
    <h3>Manuel Muyuy</h3>
    <p>Nasa Yuwe Translator</p>
    <p>Universidad de Cauca</p>
  </div>
</div>

<!-- -----
<div class="footer-section">
    <div class="footer-left">
        <h2>Thank You for Visiting</h2>
        <p>If you would like to get in touch, feel free to contact us:</p>
        <p>{rf.manrique, jc.prietoa, mv.robles}@uniandes.edu.co</p>
    </div>
    <div class="footer-right">
        <img src="images/logos/uniandes.png" alt="Universidad de los Andes" class="uniandes-logo">
    </div>
</div> -->

<!-- Nuevo Footer -->
<div class="Site-footer">
  <div class="ui container">
    <div class="ui center aligned container">
      <a href="https://apoyofinanciero.uniandes.edu.co/">Apoyo Financiero</a> |
      <a href="http://registro.uniandes.edu.co/">Admisiones y Registro</a> |
      <a href="http://biblioteca.uniandes.edu.co/">Biblioteca</a> |
      <a href="https://bloqueneon.uniandes.edu.co">Bloque Neon</a> |
      <a href="http://decanaturadeestudiantes.uniandes.edu.co/">Decanatura de Estudiantes</a>
      <br>
      Universidad de los Andes | Vigilada Mineducación <br>
      Reconocimiento como Universidad: Decreto 1297 del 30 de mayo de 1964.<br>
      Reconocimiento personería jurídica: Resolución 28 del 23 de febrero de 1949 Minjusticia<br>
      Edificio Mario Laserna Cra 1Este No 19A - 40 Bogotá (Colombia) | Tel: [571] 3394949 Ext: 2860, 2861, 2862 | Fax: [571] 3324325 <br>
      © 2025 - <a href="https://sistemas.uniandes.edu.co/">Departamento de Ingeniería de Sistemas y Computación</a>
    </div>
  </div>
</div>