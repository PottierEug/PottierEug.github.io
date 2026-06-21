---
layout: default
title: Accueil
---

# Bienvenue sur le portfolio de Mathias Martinez
{: .fade-in-up}
## À propos

Diplômé de l'École Nationale Supérieure d'Arts et Métiers et titulaire d'un Master 2 en Sciences de la Décision et
Management des Risques (SDMR) à l'IAE Paris-Sorbonne. Je m'intéresse à la maîtrise des risques industriels, organisationnels, et des problématiques liées à la santé-sécurité-performance au travail. Cet espace rassemble mes projets académiques, professionnels et personnels.

## Projets

<div class="projects">
{% for projet in site.projects %}
  <a class="card" href="{{ projet.url | relative_url }}">
    <span class="card-tag">{{ projet.category }}</span>
    <h3>{{ projet.title }}</h3>
    <p>{{ projet.summary }}</p>
  </a>
{% endfor %}
</div>
