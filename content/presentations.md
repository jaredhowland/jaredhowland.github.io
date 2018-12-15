---
title: Presentations
permalink: /presentations/
---
# Presentations #

<ul>
{% for presentation in site.data.presentations %}
<li>
    {% include presentation.html webpage="presentations" %}
</li>
{%- endfor -%}
</ul>