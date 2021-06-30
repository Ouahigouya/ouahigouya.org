---
layout: simple
author_profile: false
permalink: /
classes: wide
title: About the Organization
---

Ouahigouya provides boutique software solutions for the
global identity, credential, and trust industries.

* [Themes](./themes)
{% for theme in site.data.themes %}
  * {{ theme.title }}
{% endfor %}

* [Technologies](./technologies)
{% for technology in site.data.technologies %}
  * {{ technology.title }}
{% endfor %}
