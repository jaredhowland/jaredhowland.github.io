---
title: Publications
permalink: /publications/
---

# Publications #

{% for publication in site.data.publications %}

{% if publication.slug and publication.draft != true %}

<h2><a href="{{ publication.slug }}/">{{ publication.title }}</a></h2>

{% else %}

<h2>{{ publication.title }}</h2>

{% endif %}

**Citation Information:** {% include citation.html webpage="publications" %}

**Abstract:** {{ publication.abstract }}

{%- endfor -%}