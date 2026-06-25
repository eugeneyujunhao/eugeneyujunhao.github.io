---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
<!-- TODO: Fill in your education. -->
* Ph.D in [Field], [University], [Year]
* M.S. in [Field], [University], [Year]
* B.S. in [Field], [University], [Year]

Work experience
======
<!-- TODO: Fill in your experience, or delete. -->
* [Year]: [Role]
  * [Institution]
  * Responsibilities: [...]

Skills
======
<!-- TODO: List your skills, or delete. -->
* Skill 1
* Skill 2
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
<!-- TODO: Add service / leadership, or delete. -->
* [...]

