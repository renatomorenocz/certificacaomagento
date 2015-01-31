---
layout: page
title: Guia de estudos certificação Magento- MCD, MCDP!
---
{% include JB/setup %}

<ul>
{% for page in site.pages %}
    <li>
        <h2><a href="{{ page.url }}">{{ page.title }}</a></h2>
        <p>{{ page.meta-description %}}
    </li>
{% endfor %}
</ul>