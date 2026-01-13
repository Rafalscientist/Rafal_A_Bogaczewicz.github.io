---
layout: archive
title: "Dydaktyka / Teaching"
permalink: /teaching-archive/
author_profile: true
---

{% include base_path %}

<style>
  /* 1. ATOMOWE WYMUSZENIE MENU - POGRUBIENIE I PODKREŚLENIE (RESET KOLORU) */
  
  /* Celujemy w każdy możliwy element linku Dydaktyki w menu */
  .masthead__menu-item a[href*="/teaching"],
  .masthead__menu-item--active a,
  nav.visible a[href*="/teaching"],
  .masthead__menu-item a[href*="/teaching"] span {
    font-weight: 900 !important; /* Ekstremalne wytłuszczenie */
    color: inherit !important;
    border-bottom: 3px solid currentColor !important; /* Grubsza kreska dla pewności */
    opacity: 1 !important;
  }

  /* Wymuszenie koloru podkreślenia zależnie od trybu, by nie było zielone */
  .masthead__menu-item a[href*="/teaching"] {
    border-bottom-color: #333 !important; 
  }

  @media (prefers-color-scheme: dark) {
    html.dark .masthead__menu-item a[href*="/teaching"],
    [data-theme='dark'] .masthead__menu-item a[href*="/teaching"],
    body.dark .masthead__menu-item a[href*="/teaching"] {
      color: #ffffff !important;
      border-bottom-color: #ffffff !important;
      font-weight: 900 !important;
    }
  }

  /* 2. TYTUŁ STRONY (Dydaktyka / Teaching) - ZABEZPIECZONY */
  .page__title, .archive__title, h1, .page-teaching h1 {
    color: #0e7a3a !important;
  }
  @media (prefers-color-scheme: dark) {
    .page__title, .archive__title, h1, .page-teaching h1,
    html.dark h1, [data-theme='dark'] h1 {
      color: #11ee4a !important;
    }
  }
</style>

<div class="page-teaching">
  <!-- Twój cytat JP2 -->
  <div class="values-header" style="font-size: 0.8em; margin-bottom: 35px; border-left: 2px solid var(--global-text-color); padding-left: 15px; line-height: 1.3;">
    <div style="font-style: italic; color: var(--global-text-color);">„Musicie od siebie wymagać, nawet gdyby inni od was nie wymagali”.</div>
    <div style="font-style: italic; margin-top: 2px; color: var(--global-text-color); opacity: 0.75;">"You must demand of yourselves even if others do not demand of you."</div>
    <div style="font-weight: bold; margin-top: 2px; color: var(--global-text-color); opacity: 0.55;">— Jan Paweł II / John Paul II</div>
  </div>

  <div class="teaching-list">
    <h2 style="border-bottom: 1px solid #ccc; padding-bottom: 10px;">Archiwum zajęć / Past Semesters</h2>
    {% for post in site.teaching %}
      {% unless post.title contains "2025/2026" or post.title contains "Archive" %}
        <div style="margin-bottom: 20px;">
          <div style="font-size: 1.2em; font-weight: bold; color: var(--global-text-color);">{{ post.title }}</div>
          <div style="color: var(--global-text-color); opacity: 0.9;">{{ post.content }}</div>
          <a href="{{ post.url }}">Szczegóły przedmiotu / Course details</a>
        </div>
      {% endunless %}
    {% endfor %}
  </div>
</div>
