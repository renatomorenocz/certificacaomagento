---
layout: page
title: Guia de estudos certificação Magento- MCD, MCDP!
meta-description:
---
{% include JB/setup %}

<ul>
{% for page in site.pages %}
 {% if page.index == true %}
    <li>
        <h2><a href="{{ page.url }}">{{ page.title }}</a></h2>
        <p>{{ page.meta-description %}}
    </li>
{% endif %}
{% endfor %}
</ul>