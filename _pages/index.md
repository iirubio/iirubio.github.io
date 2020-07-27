---
layout: defaults/page
permalink: index.html
narrow: true
title: Iván Rubio Venegas homepage
---

## About me

I am a computer engineer from Chile with experience in industry as software engineer and in academia in the field of cognitive neuroscience.

## About this webpage

Created on may 2020, it has current paper readings, and my github projects.

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


