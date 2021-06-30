---
layout: simple
author_profile: false
permalink: /
classes: wide
title: About the Organization
---

[Ouahigouya LLC](./llc) provides boutique software solutions and custom
partnerships addressing global identity, credential, and trust challenges.  These
solutions are based upon the [Ouahigouya Core](./core) set of technologies.e
The [Core](./core) uses [Iiolonioro Blueprints](./blueprints) to implement
[ToIP](http://trustoverip.org) inspired trust ecosystems, which improve
the operation of small scale, limited scope, and mature, and socially critical
industries.

[Ouahigouya](./llc)'s' implementations leverage multiple
[Partner Platforms](./partner) and
[Open Source Projects](./foss) to provide solutions which enhance the
exchange of information between multiple organizations.
[Ouahigouya](./llc)'s inter-organization
data exchange technology respects the digital data rights,
laws, and obligations of all involved.  All data exchange is governed by the
programmable terms of a governance agreement to which all participants
are [signatories](./glossary#signatory).  Participants include
[institutions](./glossary#institution),
[organizations](./glossary#organization),
[managed popuplations](./glossary#managed-populations),
[property](./glossary#property),
and, most importantly,
[self sovereign individuals](./glossary#self-sovereign-individuals).

[Ouahigouya](./llc)'s projects are solutions for problems based upon the
the following principles and constraints:
* [Minimal Disruption](./disruption)
* [Mature and Quanitifable Industry](./mature)
* [Digital Dignity](./dignity)
  * [Respect for Exisitng Digital Authority](./dignity/respect)
  * [Respect for Digital Human Rights](./dignity/rights)
  * [Respect for Jurisdictional Requirements](./dignity/jurisdiction)
  * [Adherence to a Digital Code of Conduct and Adjucation Process](./dignity/judiciary)
  * [Commitment to Transparent Democratic Governance](./dignity/governance)
* [Effective Trade Association Governance](./trade)
  * [Strong Industry Management Community](./trade/community)
  * [Dedication to Data Harmonization](./trade/harmonization)
  * [Commitment to ESG data integrity](./trade/esg)
  * [Commitment to Auditable Sustainability](./trade/sustainability)
* [Background Use of Blockchain](./blockchain)
* [Commitment to Environmental Sustainability](./sustainability)


[Ouahigouya LLC](./llc)'s current portfolio includes
{% for project in site.data.projects %}
* [{{ project.title }}]({{ project.url }})
{% endfor %}
