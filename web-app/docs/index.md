---
title: " "
hide:
  - navigation
  - toc  # Oculta la barra de navegación
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

  /* Barra de navegación superior con imagen de fondo */
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
    margin-top: 40px;
    font-size: 2.5em;
    font-weight: bold;
    color: #333;
  }

  /* Contenedor del título y descripción */
  .text-container {
    text-align: center;
    background: #f8f9fa;
    padding: 20px 40px;
    max-width: 80%;
    margin: 20px auto;
  }

  .text-container h1 {
    font-size: 2em;
    margin-bottom: 10px;
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
    padding: 10px 2%;
  }

  .summary {
    flex: 1;
    min-width: 50%;
    padding-right: 20px;
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

  /* Cinta naranja con logos de empresas */
  .partner-logos {
    width: 100vw;
    max-width: 100vw;
    background-color: #ea812d;
    margin: 0;
    padding: 20px 0;
    box-sizing: border-box;
    overflow: hidden;
    text-align: center;
  }

  .partner-logos h3 {
    color: #fff;
    font-size: 1.5em;
    margin-bottom: 15px;
  }

  .logo-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
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

  /* Sección de línea de tiempo */
  .timeline-section {
    text-align: center;
    padding: 40px 20px;
    background: #f8f9fa;
  }

  .timeline-section h2 {
    font-size: 2em;
    margin-bottom: 20px;
    color: #333;
  }

  .timeline-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .timeline-image {
    max-width: 80%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
  }
</style>

<!-- Sección Principal -->
<div class="hero">
  <div class="hero-text">
    <h2>Towards cultural preservation</h2>
    <h1>Machine Translation for Indigenous Language Preservation</h1>
    <p>
      Indigenous languages in Colombia face the risk of extinction due to the decline in native speakers and lack of digital resources. This project leverages AI-driven machine translation models tailored for low-resource languages, aiming to create digital tools that support linguistic preservation. Additionally, we are actively working on translations to expand the available datasets for Indigenous language machine translation, ensuring better model performance and broader linguistic coverage.
    </p>
  </div>
  <div style="margin-right: 80px;"></div>
  <div class="hero-image">
    <img src="images/logoGPT2.webp" alt="Logo">
  </div>
</div>

------------

<!-- Sección de la Historia del Proyecto -->
<div class="timeline-section">
  <h2>Project Timeline</h2>
  <div class="timeline-container">
    <img src="images/timeline.png" alt="Project Timeline" class="timeline-image">
  </div>
</div>

-----
