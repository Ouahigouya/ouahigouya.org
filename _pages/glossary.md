---
layout: simple
author_profile: false
permalink: /glossary
classes: wide
title: Glossary
---
{% for term in site.data.glossary %}
  ## {{ term.title }}
  insert cool definition here
{% endfor %}
