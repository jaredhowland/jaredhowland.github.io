---
title: Publications
permalink: /publications/
---

# Publications #

{% for publication in site.data.publications %}

{% if publication.slug %}

<h2><a href="{{ publication.slug }}/">{{ publication.title }}</a></h2>

{% else %}

<h2>{{ publication.title }}</h2>

{% endif %}

**Abstract:** {{ publication.abstract }}

**Citation Information:** {% include citation.html %}

{%- endfor -%}