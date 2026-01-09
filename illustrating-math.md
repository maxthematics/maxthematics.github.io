---
layout: single
title: "#illustratingMath"
permalink: /illustrating-math/
author_profile: true
---

<div class="illustration-gallery">
  {% for item in site.illustrations %}
  <a href="{{ item.url }}" class="illustration-card">
    <div class="illustration-card__image">
      <img src="{{ item.thumbnail }}" alt="{{ item.title }}" loading="lazy">
    </div>
    <div class="illustration-card__info">
      <h3 class="illustration-card__title">{{ item.title }}</h3>
      <span class="illustration-card__tool">{{ item.tool }}</span>
    </div>
  </a>
  {% endfor %}
</div>
