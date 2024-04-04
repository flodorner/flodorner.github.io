---
layout: archive
title: "Publications"
permalink: /Publications/
author_profile: true
---


{% include base_path %}

{% for post in site.Publications reversed %}
  {% include archive-single.html %}
{% endfor %}



[comment]: <>  {% if site.author.googlescholar %}
[comment]: <>   <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
[comment]: <>  {% endif %}