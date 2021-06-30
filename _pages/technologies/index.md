---
layout: simple
author_profile: false
permalink: /technologies
classes: wide
title: Ouahigouya Technologies in Use
---

{% for technology in site.data.technologies %}
  ## {{ technology.title }}
{% endfor %}
