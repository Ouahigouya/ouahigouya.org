---
layout: simple
author_profile: false
permalink: /portfolio
classes: wide
title: Ouahigouya Portfolio
---

Each [DDE](./glossary#dignified-data-exchange) is an instance of the
[Ouahigouya Core](./core), managed as an independent legal entity and
supported by independent financial and cloud resources.

{% for cell in site.data.series %}
  ## {{ cell.title }}
{% endfor %}
