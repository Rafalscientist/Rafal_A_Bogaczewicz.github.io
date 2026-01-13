---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<style>
  /* --- PANICZNY FIX DLA MENU GÓRNEGO --- */
  
  /* Tryb Jasny - Aktywna zakładka i Hover */
  .masthead__menu-item--active a,
  .masthead__menu-item.active a,
  .masthead__menu-item a:hover {
    color: #0e7a3a !important;
    font-weight: bold !important;
    border-bottom: 2px solid #0e7a3a !important;
  }

  /* Tryb Ciemny - Aktywna zakładka i Hover */
  @media (prefers-color-scheme: dark) {
    .masthead__menu-item--active a,
    .masthead__menu-item.active a,
    .masthead__menu-item a:hover {
      color: #11ee4a !important;
      border-bottom-color: #11ee4a !important;
    }
  }

  /* Dodatkowe wymuszenie dla ciemnych motywów Jekylla 2026 */
  html.dark .masthead__menu-item--active a,
  [data-theme='dark'] .masthead__menu-item--active a {
    color: #11ee4a !important;
    border-bottom-color: #11ee4a !important;
  }
</style>

{% include base_path %}

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
