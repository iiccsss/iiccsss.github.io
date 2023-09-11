---
layout: page
title: speakers
permalink: /speakers/
description: Our 2023 speakers
nav: true
nav_order: 3
display_categories: [speakers, panelists]
horizontal: false
---

<!-- pages/speakers.md -->
<div class="projects">
{%- if site.enable_speaker_categories and page.display_categories %}
  <!-- Display speakers grouped by topic -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_speakers = site.speakers | where: "category", category -%}
  {%- assign sorted_speakers = categorized_speakers | sort: "importance" %}
  <!-- Generate cards for each speaker -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for speaker in sorted_speakers -%}
      {% include speaker_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for speaker in sorted_speakers -%}
      {% include speaker.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display speakers without categories -->
  {%- assign sorted_speakers = site.speakers | sort: "importance" -%}
  <!-- Generate cards for each speaker -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for speaker in sorted_speakers -%}
      {% include speaker_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for speaker in sorted_speakers -%}
      {% include speaker.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
