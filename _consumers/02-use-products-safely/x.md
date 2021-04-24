---
title: safety of button batteries
permalink: /consumers/use-products-safely/test
third_nav_title: Use products safely

{% for page in site.pages %}
    {% unless page.exclude %}
        <a class="page-link" href="{{ page.url | prepend: site.baseurl }}">
            {{ page.title }}
        </a>
    {% endunless %}
{% endfor %}
exclude: true
---
test
