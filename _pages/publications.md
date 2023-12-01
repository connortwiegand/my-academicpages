---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

### Research Interests
I have research interests. 

### Academic Research

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Other Projects
Here are some other porjects I am working on. 
