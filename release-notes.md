---
title: Index of Release Notes
layout: sub
permalink: release-notes
---

{%- for version in site.data.version_lst.versions -%}
* [DOSBox-X {{ version }} Release Notes](release-{{ version }}.html){%- if version == site.data.latest_version.version %} **(latest version)**{%- endif %}
{% endfor -%}
