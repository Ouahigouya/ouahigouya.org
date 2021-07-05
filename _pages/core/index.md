---
layout: simple
author_profile: false
permalink: /core
classes: wide
title: Ouahigouya Core
---

The Core is based upon
[Iiolonioro Blueprints](./io/blueprints).

The Blueprints are a process specification
for generating [ToIP](http://trustoverip.org) inspired
[Trust Ecosystems](./glossary#trust-ecosystems).  Our boutique
solutions


{% for components in site.data.components %}
## {{ components.title }}
<p>
{{ components.description }}
</p>
<a href="{{components.url}}">Learn more</a>
{% endfor %}
