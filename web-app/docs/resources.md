---
title: " "
hide:
  - navigation
  - toc
  - edit
  - path
  - header
  - footer
---
<style>

  .resources-section {
    text-align: center;
    padding: 20px;
  }

  .resources-section h2 {
  font-size: 2em;
    margin-bottom: 5px;
}

  .download-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    margin-bottom: 40px;
  }

  .download-box, .paper-box {
    width: 85%;
    background-color: #ffffff; /* Fondo más limpio */
    padding: 20px;
    border-radius: 12px; /* Bordes más redondeados */
    text-align: left;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1); /* sombra más difusa */
    border: 1px solid #e0e0e0; /* borde gris muy clarito */
    transition: transform 0.3s, box-shadow 0.3s;
}

  .download-box a {
    color: rgb(45, 234, 218);
    text-decoration: none;
    font-weight: bold;
  }

  .citation-box {
    background-color: #d8f3dc;
    padding: 15px;
    margin-top: 40px;
    width: 80%;
    margin-left: auto;
    margin-right: auto;
    border-radius: 8px;
    font-size: 1.1em;
  }

  .paper-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    margin-top: 20px;
  }

/* Estilo de la tarjeta */
.paper-box {
  width: 85%;
  background-color: #f8f9fa;
  padding: 20px;
  border-radius: 8px;
  text-align: left;
  box-shadow: 0px 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  cursor: pointer; /* Hacer que el cursor cambie al pasar sobre la tarjeta */
}

/* Cuando pasas el ratón, el borde de la tarjeta y sombra se suavizan */
.paper-box:hover {
  transform: translateY(-5px); /* Subir un poco la tarjeta */
  box-shadow: 0px 6px 10px rgba(0,0,0,0.15);
}

/* Enlace dentro de la tarjeta */
.paper-box a {
  text-decoration: none; /* Eliminar subrayado */
  color: #333; /* Color estándar del texto (evitar el rojo) */
  display: block; /* Hace que el enlace ocupe toda la tarjeta */
  height: 100%;
}

/* Estilo para los títulos */
.paper-box h3 {
  font-size: 1.5em;
  font-weight: bold;
  color: #333; /* Aseguramos que el título tenga un color oscuro */
  margin-bottom: 10px;
}

/* Estilo para los resúmenes */
.paper-box p {
  color: #555; /* Texto más suave para los resúmenes */
  margin-bottom: 10px;
}

/* Efecto hover solo para el enlace: cambiar color sin subrayado */
.paper-box a:hover {
  color: #45b8b0; /* Cambiar a un color suave cuando pase el ratón */
  text-decoration: none; /* Aseguramos que no haya subrayado al pasar el mouse */
}


  body {
    margin: 0;
    padding: 0;
    min-height: 100vh; /* Asegura que la página tome toda la altura de la pantalla */
    display: flex;
    flex-direction: column;
  }

  .download-box:hover, .paper-box:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
}


  header.md-header {
    display: none;
  }

</style>

<!-- Barra de navegación fija con logo DISC (alineado con margen izquierdo de sección especial) -->
<div class="custom-navbar">
  <div class="navbar-container">
    <a href="https://sistemas.uniandes.edu.co/" class="navbar-logo">
      <img src="/images/logos/logo_disc.png" alt="Logo DISC">
    </a>
  </div>
</div>

<div class="resources-section">
  <h2>Available Resources</h2>

  <div class="download-container">
    <div class="download-box">
      <h3>Datasets and models</h3>
      <ul>
        <li><a href="https://www.dropbox.com/scl/fo/bj7ra25nbf0bjed5f6y92/AEoZOR3kt_53Qy9ATWEdCq0/datasets?dl=0&rlkey=ag6dssslslwiqjrtg6kd8a8ym&subfolder_nav_tracking=1">Translation datasets for Wayuunaiki, Arhuaco, Inga, and Nasa</a> – Parallel corpus of Indigenous languages to Spanish.</li>
        <li><a href="https://www.dropbox.com/scl/fo/bj7ra25nbf0bjed5f6y92/AA45b7hSqeVkWDYWmaDyxfA/models?dl=0&rlkey=ag6dssslslwiqjrtg6kd8a8ym&subfolder_nav_tracking=1">Translation models for Wayuunaiki, Arhuaco, Inga, and Nasa</a> – The best models for each language.</li>
        <!-- Agrega más datasets aquí -->
      </ul>
    </div>
    <div class="download-box">
      <h3>Books</h3>
      <ul>
        <li><a href="LINK_TO_BOOK_1"> O'unaa unapümuin sülerru'je tü Maa'kat</a> –  (Journey to the Center of the Earth, Julio Verne) Translation into Wayuunaiki.</li>
        <li><a href="LINK_TO_BOOK_1"> Chaupi alpa ukuma purii </a> –  (Journey to the Center of the Earth, Julio Verne) Translation into Inga.</li>
        <!-- Agrega más libros aquí -->
      </ul>
    </div>
  </div>

  <div class="citation-box">
    <p>
      If you use any of our datasets or models in your work, please cite us as follows:<br><br>
      <em>"Juan Prieto, Cristian Martinez, Melissa Robles, Alberto Moreno, Sara Palacios, and Rubén Manrique. 2024. Translation systems for low-resource Colombian Indigenous languages, a first step towards cultural preservation. In Proceedings of the 4th Workshop on Natural Language Processing for Indigenous Languages of the Americas (AmericasNLP 2024), pages 7–14, Mexico City, Mexico. Association for Computational Linguistics."</em>
    </p>
  </div>

  <h2>Publications</h2>

  <div class="paper-container">
    <div class="paper-box">
      <a href="https://aclanthology.org/2024.americasnlp-1.2/">
        <h3>Translation systems for low-resource Colombian Indigenous languages, a first step towards cultural preservation</h3>
        <p><strong>Summary:</strong> The use of machine learning and Natural Language Processing (NLP) technologies can assist in the preservation and revitalization of indigenous languages, particularly those classified as “low-resource.” Given the increasing digitization of information, the development of translation tools for these languages is of significant importance. These tools not only facilitate better access to digital resources for indigenous communities but also stimulate language preservation efforts and potentially foster more inclusive, equitable societies, as demonstrated by the AmericasNLP workshop since 2021. The focus of this paper is Colombia, a country home to 65 distinct indigenous languages, presenting a vast spectrum of linguistic characteristics. This cultural and linguistic diversity is an inherent pillar of the nation’s identity, and safeguarding it has been increasingly challenging given the dwindling number of native speakers and the communities’ inclination towards oral traditions. Considering this context, scattered initiatives exist to develop translation systems for these languages. However, these endeavors suffer from a lack of consolidated, comparable data. This paper consolidates a dataset of parallel data in four Colombian indigenous languages - Wayuunaiki, Arhuaco, Inga, and Nasa - gathered from existing digital resources. It also presents the creation of baseline models for future translation and comparison, ultimately serving as a catalyst for incorporating more digital resources progressively.</p>
        <p><strong>Cite:</strong> Juan Prieto, Cristian Martinez, Melissa Robles, Alberto Moreno, Sara Palacios, and Rubén Manrique. 2024. Translation systems for low-resource Colombian Indigenous languages, a first step towards cultural preservation. In Proceedings of the 4th Workshop on Natural Language Processing for Indigenous Languages of the Americas (AmericasNLP 2024), pages 7–14, Mexico City, Mexico. Association for Computational Linguistics.</p>
      <a href="https://aclanthology.org/2024.americasnlp-1.2/">Read the full paper</a>
      </a>
    </div>
    <div class="paper-box">
    <a href="https://dl.acm.org/doi/10.1145/3616855.3637828">
      <h3>Preserving Heritage: Developing a Translation Tool for Indigenous Dialects</h3>
      <p><strong>Summary:</strong> The preservation and understanding of indigenous languages emerge as crucial, given their substantial contribution to the cultural and linguistic heritage of communities. Despite their undeniable value, these languages are threatened by extinction due to a dwindling number of native speakers and the predominance of oral traditions over written forms. In this context, this study aims to contribute to the conservation of these languages through the development of a Spanish-indigenous language translator. This research employs neural machine translation technology, investigating three distinct approaches: a translation model based on transformers, finetuning with a Finnish translator, and finetuning with a multilingual translator. The results obtained from these methodologies are promising, demonstrating competitive viability when compared to the limited existing research in this field of study.</p>
      <p><strong>Cite:</strong> Melissa Robles, Cristian A. Martínez, Juan C. Prieto, Sara Palacios, and Rubén Manrique. 2024. Preserving Heritage: Developing a Translation Tool for Indigenous Dialects. In Proceedings of the 17th ACM International Conference on Web Search and Data Mining (WSDM '24). Association for Computing Machinery, New York, NY, USA, 1200–1203. https://doi.org/10.1145/3616855.3637828</strong> </p>
      <a href="https://dl.acm.org/doi/10.1145/3616855.3637828">Read the full paper</a>
    </a>
    </div>
  </div>
</div>

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