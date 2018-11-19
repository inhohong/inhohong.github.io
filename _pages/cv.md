---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

/*## <span style="color:blue"> **[Download CV](https://github.com/inhohong/inhohong.github.io/raw/master/files/CV_ihong_web.pdf)** </span>*/

{% include_relative education.md %}

{% include_relative research-interest.md %}

Publications
------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% include_relative other-content.md %}

Skills and languages
------
* MATLAB, Python, C
* Korean (native), English (advanced)
