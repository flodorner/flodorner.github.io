---
layout: archive
title: "Publications"
permalink: /Publications/
author_profile: true
---
{% include base_path %}

{%- assign pubs = site.Publications | sort: 'date' | reverse -%}

<ul class="pub-list">
{%- for post in pubs -%}
  <li class="pub-entry">
    {%- if post.badge or post.venue_short -%}
      <div class="pub-label">{{ post.badge | default: post.venue_short }}</div>
    {%- endif -%}

    <div class="pub-title"><strong>{{ post.title }}</strong></div>
    <div class="pub-authors">{{ post.authors }}</div>

    <div class="pub-meta">
      {%- if post.venue -%}<em>{{ post.venue }}</em>
      {%- elsif post.booktitle -%}<em>{{ post.booktitle }}</em>
      {%- elsif post.journal -%}<em>{{ post.journal }}</em>
      {%- endif -%}
      {%- if post.year -%}{% if post.venue or post.booktitle or post.journal %}, {% endif %}{{ post.year }}{%- endif -%}
    </div>

    <div class="pub-links">
      {%- if post.paperurl -%}<a href="{{ post.paperurl }}" target="_blank" rel="noopener">PDF</a>{%- endif -%}
      {%- if post.code or post.github -%}<a href="{{ post.code | default: post.github }}" target="_blank" rel="noopener">Code</a>{%- endif -%}
      {%- if post.models -%}<a href="{{ post.models }}" target="_blank" rel="noopener">Models</a>{%- endif -%}
      {%- if post.data -%}<a href="{{ post.data }}" target="_blank" rel="noopener">Data</a>{%- endif -%}
      {%- if post.poster -%}<a href="{{ post.poster }}" target="_blank" rel="noopener">Poster</a>{%- endif -%}
      {%- if post.slidesurl -%}<a href="{{ post.slidesurl }}" target="_blank" rel="noopener">Slides</a>{%- endif -%}
      {%- if post.video -%}<a href="{{ post.video }}" target="_blank" rel="noopener">Video</a>{%- endif -%}
      {%- if post.doi -%}<a href="https://doi.org/{{ post.doi }}" target="_blank" rel="noopener">DOI</a>{%- endif -%}
    </div>
  </li>
{%- endfor -%}
</ul>



