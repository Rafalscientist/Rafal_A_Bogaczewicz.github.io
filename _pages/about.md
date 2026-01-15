---
layout: single
author_profile: true
title: "mgr inż. / MSc. Rafał A. Bogaczewicz"
permalink: /
---

{% include base_path %}

<style>
  /* 1. TYTUŁ GŁÓWNY - MORSKA ZIELEŃ */
  h1.page__title { 
    color: #16a085 !important; 
    margin-bottom: 30px !important;
  }

  /* 2. ADAPTACYJNE NAGŁÓWKI SEKCJI (Czarny/Biały, mniejsza czcionka) */
  .cv-style-header {
    color: var(--global-text-color) !important;
    border-bottom: 1px solid #ccc;
    margin-top: 35px;
    margin-bottom: 15px;
    font-size: 1.1em; 
    font-weight: bold;
    display: block;
    width: 100%;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  /* 3. SIATKA TREŚCI */
  .cv-content-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 25px;
    margin-bottom: 20px;
  }

  /* RWD dla urządzeń mobilnych */
  @media (max-width: 600px) {
    .cv-content-grid { grid-template-columns: 1fr; }
  }

  .lang-pl { text-align: justify; font-size: 0.9em; line-height: 1.5; }
  .lang-en { 
    text-align: justify; 
    font-size: 0.85em; 
    font-style: italic; 
    opacity: 0.7; 
    border-left: 1px solid #eee; 
    padding-left: 15px; 
  }
</style>

<div class="page-home">

  <!-- WSTĘP BEZ NAGŁÓWKA -->
  <div class="cv-content-grid" style="margin-top: 10px;">
    <div class="lang-pl">
      Jestem fizykiem teoretykiem i doktorantem w <b>Instytucie Fizyki Teoretycznej Politechniki Wrocławskiej</b>. Moja praca koncentruje się na poszukiwaniu matematycznego piękna i precyzji w fundamentalnych prawach świata kwantowego.
    </div>
    <div class="lang-en">
      I am a theoretical physicist and a PhD student at the <b>Institute of Theoretical Physics (WUST)</b>. My work focuses on seeking mathematical beauty and precision within the fundamental laws of the quantum world.
    </div>
  </div>

  <!-- SEKCJA: BADANIA -->
  <span class="cv-style-header">Badania / Research</span>
  <div class="cv-content-grid">
    <div class="lang-pl">
      Główne obszary moich zainteresowań naukowych to:
      <ul style="margin-top: 10px; padding-left: 18px;">
        <li>Optyka kwantowa ciała stałego</li>
        <li>Dynamika fononów i emitery kwantowe</li>
        <li>Modelowanie kwantowych układów otwartych</li>
      </ul>
    </div>
    <div class="lang-en">
      My primary research interests include:
      <ul style="margin-top: 10px; padding-left: 18px;">
        <li>Solid-state quantum optics</li>
        <li>Phonon dynamics and quantum emitters</li>
        <li>Open quantum systems modeling</li>
      </ul>
    </div>
  </div>

  <!-- SEKCJA: KONTAKT -->
  <span class="cv-style-header">Kontakt / Contact</span>
  <div class="cv-content-grid">
    <div class="lang-pl">
      Zapraszam do kontaktu w sprawach naukowych i dydaktycznych:
      <p style="margin-top: 10px;">
        <b>E-mail:</b> rafal.bogaczewicz@pwr.edu.pl<br>
        <b>Miejsce:</b> Politechnika Wrocławska, bud. A-1
      </p>
    </div>
    <div class="lang-en">
      Feel free to contact me regarding research or teaching:
      <p style="margin-top: 10px;">
        <b>E-mail:</b> rafal.bogaczewicz@pwr.edu.pl<br>
        <b>Location:</b> Wrocław University of Science and Technology
      </p>
    </div>
  </div>

  <!-- DYSKRETNY PODPIS NA DOLE (HACZYK) -->
  <div style="margin-top: 60px; text-align: center; opacity: 0.6; font-style: italic; font-size: 0.85em;">
    <hr style="width: 25%; margin: 20px auto; border-top: 1px solid #eee;">
    "Pasjonat odkrywania świata, zarówno w równaniach, jak i dosłownie ;)"
  </div>

</div>
