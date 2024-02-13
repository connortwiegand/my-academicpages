---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
pg_link: "https://catalog.uoregon.edu/courses/crs-ec/"
---

In addition to standard grading/TA positions completed through a PhD program, I have taught university-level economics courses as a full instructor. A course catalog from the U of O's economics department can be found [here]({{ page.pg_link }}). Course materials are available upon request. 


## As an Instructor of Record

---

{% for course in site.data.teaching.IOR %} 
   - ### {{ course.title }} ([{{ course.number }}]({{ page.pg_link }}){:target="_blank"}{:rel="noopener noreferrer"}) <br> &nbsp;&nbsp;<span class = "small" style="font-weight: normal;">\-- _{{ course.terms }}_ </span>

*[{{ course.number }}]: {{ course.info }}

{% endfor %}

## TA Positions

---

{% for course in site.data.teaching.TA reversed %}
### {{ course.number }}: {{ course.title }} <span style="font-weight: normal;">({% if course.pos == "G" %}Grader{% else %}TA{% endif %}) {% if course.times %} (x{{ course.times }}) {% endif %} </span>
{% endfor %}
