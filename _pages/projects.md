---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

# Research Interests
I have research interests. 

<div style="margin-bottom: -0.75em;">
<h1> Academic Research </h1>
</div>

{% for p in site.projects reversed %}
  {% if p.categories contains page.categories %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

# Other Projects
Here are some other projects I am working on. 
