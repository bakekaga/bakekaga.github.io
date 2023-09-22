---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

For a summary, please reference my [resume](https://github.com/bakekaga/Resume/blob/main/resume-general/Albert_Shi_Zhu_Resume.pdf).

Education
======
* Rice University, B.S. Computer Science and Mathematics, expected Spring 2026
  * <strong>Coursework</strong> († graduate-level): [Computational Thinking](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202310&p_crn=13531), [Algorithmic Thinking](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202320&p_crn=24218), [Stochastic Models](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202320&p_crn=22029), [Introduction to Program Design](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202410&p_crn=14283), [Reasoning About Algorithms](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202410&p_crn=11155), [Introduction to Machine Learning](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202410&p_crn=16026)†, [Probability and Statistics](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202410&p_crn=10116), [Fundamentals of Computer Engineering](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202310&p_crn=14707), [Honors Linear Algebra](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202320&p_crn=21571), [Honors Calculus III](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202310&p_crn=10058)/[IV](https://courses.rice.edu/courses/courses/!SWKSCAT.cat?p_action=COURSE&p_term=202320&p_crn=24639)
  * <strong>Activities</strong>: [Math Directed Reading Program](https://mathweb.rice.edu/directed-reading-program), [ICPC Club](https://www.cs.rice.edu/~greiner/icpc.html), [Rice Table Tennis Club](https://owlnest.rice.edu/organization/RiceTableTennisClub)

Skills
======

<strong>Proficient:</strong> Python (Pandas, NumPy, Scikit-Learn, Jupyter Notebook), LaTeX, Git/Terminal

<strong>Intermediate:</strong> C/C++, HTML, CSS, React, Java, Adobe InDesign, Adobe Premiere Pro

<strong>Novice:</strong> Express, MongoDB, GraphQL, Adobe PhotoShop

[Experiences](../experiences)
======

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in posts %}
    {% if post.categories contains 'experiences' %}
      {% include archive-single.html type=entries_layout %}
	{% endif %}
  {% endfor %}
</div>

{% include paginator.html %}


<!-- [Projects](../projects)
======

<ul>{% for post in site.projects reversed %}
  {% include archive-single-cv.html%}
{% endfor %}</ul> -->

<!-- [Publications](../publications)
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

Awards
======
  * Febuary 2023: [Rice Datathon](https://rice-datathon-2023.devpost.com/), Best Visualization Award
  * January 2023: Rice [Fall President's Honor Roll](https://registrar.rice.edu/students/academic-honors#PHR)
  * March 2019/2021/2022: [Mathematical Association of America](https://www.maa.org/math-competitions/american-invitational-mathematics-examination-aime), AIME Qualifier
  * March 2020: [Hewlett-Packard CodeWars Competition](https://hpecodewars.org/api/Files/events/2020/2020WinnersHouston.pdf), 3rd Place, Advanced Division