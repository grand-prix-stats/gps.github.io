---
title: Circuit de Spa-Francorchamps
layout: page
circuitRef: spa
---

{% assign circuit = site.data.circuits[page.circuitRef].profile } %}

| **Circuit Name** | {{ circuit.name }}     |
| **Location**     | {{ circuit.location }} |
| **Country**      | {{ circuit.country }}  |

<ul>
{% for collection in site.data.circuits[page.circuitRef].collections %}
    <li><a href="{{ collection.url }}">{{ collection.title }}</a></li>
{% endfor %}
</ul>