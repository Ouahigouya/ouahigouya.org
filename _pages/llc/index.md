---
layout: simple
author_profile: false
permalink: /llc
classes: wide
title: Ouahigouya LLC Definition
---

{% for components in site.data.components %}
## {{ components.title }}
<p>
{{ components.description }}
</p>
<a href="{{components.url}}">Learn more</a>
{% endfor %}
