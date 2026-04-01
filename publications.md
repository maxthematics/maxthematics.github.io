---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my publications sorted by type or in chronological order below. Both lists are generated automatically from my BibTeX database.

<style>
  .pub-tabs input[type="radio"] { display: none; }
  .pub-tabs label {
    display: inline-block;
    padding: 0.5em 1.2em;
    cursor: pointer;
    border-bottom: 3px solid transparent;
    margin-right: 0.5em;
    color: #999;
  }
  .pub-tabs input:checked + label {
    border-bottom-color: #00bcd4;
    color: #fff;
  }
  .pub-tab-content { display: none; margin-top: 1em; }
  #tab-type:checked ~ #content-type,
  #tab-chrono:checked ~ #content-chrono { display: block; }
</style>

<div class="pub-tabs">
  <input type="radio" name="pub-tab" id="tab-type" checked>
  <label for="tab-type">By Type</label>
  <input type="radio" name="pub-tab" id="tab-chrono">
  <label for="tab-chrono">Chronological</label>

  <div class="pub-tab-content" id="content-type">
    <iframe src="{{ '/assets/publications/publicationsHoffmann.pdf' | relative_url }}" width="100%" height="600px" style="border: none;"></iframe>
    <br>
    <a href="{{ '/assets/publications/publicationsHoffmann.pdf' | relative_url }}" class="btn btn--primary" download>Download (by type)</a>
  </div>

  <div class="pub-tab-content" id="content-chrono">
    <iframe src="{{ '/assets/publications/publicationsHoffmann_chrono.pdf' | relative_url }}" width="100%" height="600px" style="border: none;"></iframe>
    <br>
    <a href="{{ '/assets/publications/publicationsHoffmann_chrono.pdf' | relative_url }}" class="btn btn--primary" download>Download (chronological)</a>
  </div>
</div>