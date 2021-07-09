---
layout: simple
author_profile: false
permalink: /llc
classes: wide
title: Ouahigouya LLC Definition
---

[Ouahigouya LLC](./llc) is a [Delaware Limited Liability Company](http://delcode.delaware.gov/title6/c018/sc01/index.html)

which is formed as a set of elements, or "Series":
  ```
  (16) “Protected series” means a designated series of members, managers, limited liability company interests or assets that is established in accordance with § 18-215(b) of this title.

  (17) “Registered series” means a designated series of members, managers, limited liability company interests or assets that is formed in accordance with § 18-218 of this title.

  (18) “Series” means a designated series of members, managers, limited liability company interests or assets that is a protected series or a registered series, or that is neither a protected series nor a registered series.
  ```

Public records of incorporation are here:
  * link to and provide signed, tamper proof, VC issued evidence of self

The following Series have been established:

|-----------|--------|
| Name      |   Who  |  
{% for cell in site.data.series %}|[{{ cell.title }}]({{ cell.url }})|{% for elt in cell.elements %}  {{elt}}<br />{% endfor %}|
{% endfor %}


Please feel free to suggest a new opportunity, by [begin a quotation](../engage/).
