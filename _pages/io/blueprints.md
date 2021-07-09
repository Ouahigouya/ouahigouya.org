---
layout: simple
author_profile: false
permalink: /io/blueprints
classes: wide
title: Ouahigouya Core Components
---

{% for components in site.data.components %}
## {{ components.title }}
<p>
{{ components.description }}
</p>
<a href="{{components.url}}">Learn more</a>
{% endfor %}
