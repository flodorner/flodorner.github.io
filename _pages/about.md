---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Florian Dorner, a doctoral fellow with the Max Planck ETH Center for Learning Systems advised by Moritz Hardt and Fanny Yang. I hold an MSc. in Mathematics from FU Berlin and an MSc. in Science, Technology and Policy from ETH Zurich.

I am interested in understanding the societal impacts of Artificial Intelligence. These days, most of my work focuses on the role of data quality in various parts of the Machine Learning pipeline, with a particular focus on benchmarking and evaluation. 


<h1>Selected Publications</h1>

{% include base_path %}

{%- assign pubs = site.Publications
  | where: 'selected', true
  | sort: 'date' | reverse -%}

<ul class="pub-list">
{%- for post in pubs -%}
  <li class="pub-entry">
    {%- if post.badge or post.venue_short -%}
      <div class="pub-label">{{ post.badge | default: post.venue_short }}</div>
    {%- endif -%}

    <div class="pub-title"><strong>{{ post.title }}</strong></div>
    <div class="pub-authors">{{ post.authors }}</div>

    <div class="pub-meta">
      {%- if post.venue -%}
        <em>
          {%- if post.paperurl -%}
            <a href="{{ post.paperurl }}" target="_blank" rel="noopener">{{ post.venue }}</a>
          {%- else -%}
            {{ post.venue }}
          {%- endif -%}
        </em>
      {%- elsif post.booktitle -%}
        <em>
          {%- if post.paperurl -%}
            <a href="{{ post.paperurl }}" target="_blank" rel="noopener">{{ post.booktitle }}</a>
          {%- else -%}
            {{ post.booktitle }}
          {%- endif -%}
        </em>
      {%- elsif post.journal -%}
        <em>
          {%- if post.paperurl -%}
            <a href="{{ post.paperurl }}" target="_blank" rel="noopener">{{ post.journal }}</a>
          {%- else -%}
            {{ post.journal }}
          {%- endif -%}
        </em>
      {%- endif -%}
      {%- if post.year -%}{% if post.venue or post.booktitle or post.journal %}, {% endif %}{{ post.year }}{%- endif -%}
    </div>

    <div class="pub-links">
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

