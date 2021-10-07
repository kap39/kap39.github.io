---
permalink: /Research/
title: "Research"
excerpt: "Research"
author_profile: true
redirect_from: 
  - /research-and-interests/
  - /research.html
---


My research lies in theoretical and computational fluid dynamics, focusing on lubrication layer theory. Specifically, I'm currently researching the formation and evolution of the air lubrication layer that arises from impacting droplets, motivated by the pilot-wave 'bouncing droplet' phenomena.

 I'm supervised by [Prof. Paul Milewski](https://researchportal.bath.ac.uk/en/persons/paul-milewski/) (50%), [Prof Jonathan Evans](https://people.bath.ac.uk/masjde) (25%) and [Dr. Phil Trinh](https://http://www.ptrinh.com/) (25%).
 

Conferences and Symposia 
=====
  * Represented UoB student chapter at the [SIAM Annual Meeting](https://www.siam.org/conferences/cm/conference/an21) - _Jul '21_
  * Organised 5th annual [SAMBa Summer Conference](https://kap39.github.io/SAMBa-Conference) - _Jul '21'_
  * Attended the Univeristy of Bath [Women in Maths Conference](https://www.bath.ac.uk/events/bath-women-in-maths-conference-2021/) - _Mar '21_
  * Attended SAMBa's virtual [13<sup>th</sup> Integrative think tank](https://people.bath.ac.uk/mtp34/itt13.html) - _Jan '21_
  * Attended SAMBa's virtual [12<sup>th</sup> Integrative think tank](https://www.bath.ac.uk/events/integrative-think-tank-12/) - _Sept '20_
  * Spoke at the virtual [SAMBa Conference](https://people.bath.ac.uk/mk961/SAMBa_Conf.html) - _Jul '20_
  * Helped coordinate, and attended SAMBa's [11<sup>th</sup> Integrative think tank](https://kap39.github.io/ITT11) - _Jan '20_
  * Attended the annual [SAMBa Conference](https://people.bath.ac.uk/wg270/SAMBa_Conf.html) - _Jul '19_
  * Attended Univeristy of Bristol's [Women in Maths Conference](https://www.bristol.ac.uk/maths/events/2018/women-in-maths-2018.html) - _Nov '18_
  * Attended [UKFN PhD/Early Careers Conference](http://www.cardiffmaths.co.uk/ukfn.html) - _Jul '18_



Talks and Publications
=====
Find a list of talks and publications below. There aren't that many yet!

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



---

