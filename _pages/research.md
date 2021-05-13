---
permalink: /Research/
title: "Research"
excerpt: "Research"
author_profile: true
redirect_from: 
  - /research-and-interests/
  - /research.html
---


My research lies in theoretical and computational fluid dynamics, focusing on lubrication layer theory. Specifically, I'm currently researching the formation and evolution of the air lubrication layer that arises from impacting droplets, motivated by the pilot-wave 'bouncing droplet' phenomena. I'm supervised by [Prof. Paul Milewski](https://researchportal.bath.ac.uk/en/persons/paul-milewski/) (50%), [Prof Jonathan Evans](https://people.bath.ac.uk/masjde) (25%) and [Dr. Phil Trinh](https://http://www.ptrinh.com/) (25%).
 

Talks
=====
find a list of talks below

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}



Publications
=====
Find a list of publications below

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



---

