---
layout: single
author_profile: true
title: "mgr inż. / MSc. Rafał&nbsp;A.&nbsp;Bogaczewicz"
permalink: /
---

{% include base_path %}

<style>
  /* 1. TYTUŁ GŁÓWNY - MORSKA ZIELEŃ */
  h1.page__title { 
    color: #16a085 !important; 
    margin-bottom: 30px !important;
  }

  /* 2. ADAPTACYJNE NAGŁÓWKI SEKCJI */
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

  /* WYRÓWNANIE DO LEWEJ - NATURALNY RYTM TEKSTU */
  .lang-pl, .lang-en { 
    text-align: left; 
    font-size: 0.95em; 
    line-height: 1.6; 
    overflow-wrap: break-word;
  }

  .lang-en { 
    opacity: 0.7; 
    border-left: 1px solid #eee; 
    padding-left: 15px; 
  }

  /* STYLIZACJA LINKÓW - SPÓJNA Z PUBLICATIONS, BEZ BOLD */
  .pub-link {
    color: #16a085 !important;
    text-decoration: none !important;
    transition: all 0.2s ease-in-out;
    font-weight: normal !important;
  }

  .pub-link:hover {
    color: #2ecc71 !important;
    border-bottom: 1px solid #2ecc71 !important;
  }
</style>

<div class="page-home">

  <!-- WSTĘP Z NOWĄ LINIĄ -->
  <div class="cv-content-grid" style="margin-top: 10px;">
    <div class="lang-pl">
      Cześć, jestem fizykiem teoretykiem, doktorantem w&nbsp;<a href="https://www.kft.pwr.edu.pl" class="pub-link" target="_blank">Instytucie Fizyki Teoretycznej PWr</a>.
      <span style="display: block; margin-top: 12px;">
        Pracuję w&nbsp;grupie naukowej <a href="https://pm.kft.pwr.edu.pl" class="pub-link" target="_blank">prof.&nbsp;Pawła Machnikowskiego</a>.
      </span>
    </div>
    <div class="lang-en">
      Hey, I&nbsp;am a&nbsp;theoretical physicist, a&nbsp;PhD student at&nbsp;the <a href="https://www.kft.pwr.edu.pl" class="pub-link" target="_blank">Institute of&nbsp;Theoretical Physics (WUST)</a>.
      <span style="display: block; margin-top: 12px;">
        I&nbsp;work in&nbsp;the scientific group of&nbsp;<a href="https://pm.kft.pwr.edu.pl" class="pub-link" target="_blank">prof.&nbsp;Paweł Machnikowski</a>.
      </span>
    </div>
  </div>

<!-- SEKCJA: ZAINTERESOWANIA NAUKOWE (UJEDNOLICONY ROZMIAR) -->
  <span class="cv-style-header" style="font-size: 1.15em; border-bottom: 1px solid #ccc; padding-bottom: 5px;">
    Zainteresowania naukowe / Scientific interests
  </span>
  
  <div class="cv-content-grid" style="margin-top: 15px;">
    <div class="lang-pl">
      <ul style="margin: 0; padding-left: 18px; list-style-type: square;">
        <li>Optyka kwantowa ciała stałego</li>
        <li>Dekoherencja i&nbsp;dynamika fononowa w&nbsp;układach kwantowych</li>
        <li>Kwantowe układy otwarte</li>
      </ul>
    </div>
    <div class="lang-en">
      <ul style="margin: 0; padding-left: 18px; list-style-type: square;">
        <li>Solid-state quantum optics</li>
        <li>Decoherence and&nbsp;phonon dynamics in&nbsp;quantum systems</li>
        <li>Open quantum systems</li>
      </ul>
    </div>
  </div>
  
  <!-- SEKCJA: KONTAKT (NAPRAWIONE RWD DLA SMARTFONA) -->
  <!-- SEKCJA KONTAKT - PANCERNE RWD -->
<span class="cv-style-header">Kontakt / Contact</span>
<div style="margin-top: 15px; text-align: left; font-size: 0.95em;">
  <b>e-mail:</b> <a href="mailto:rafal.bogaczewicz@pwr.edu.pl" class="pub-link">rafal.bogaczewicz@pwr.edu.pl</a>
  <div style="margin-top: 15px;">
    <div style="display: block; margin-bottom: 5px;">
      Instytut Fizyki Teoretycznej | Politechnika Wrocławska
    </div>
    <div style="display: block; opacity: 0.7; border-left: 3px solid #16a085; padding-left: 10px; font-style: italic;">
      Institute of Theoretical Physics | Wrocław University of Science and Technology
    </div>
  </div>
</div>

</div>
