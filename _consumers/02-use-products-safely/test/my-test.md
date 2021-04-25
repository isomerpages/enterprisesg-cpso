---
title: product type 1 
permalink: /consumers/use-products-safely/product-type1
third_nav_title: Use products safely
  {% for page in site.pages %}
    {% if page.menu == 'noshow' %}
      <li><a href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
menu: noshow
---

insert content

