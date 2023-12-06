---
layout: archive
title: "Publications"
permalink: /publications/
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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Other Projects
Here are some other projects I am working on. 
