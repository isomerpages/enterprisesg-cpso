---
title: test
permalink: /consumers/use-products-safely/test
show_in_nav: false
<ul>
{% for p in pages %}
    {% unless show_in_nav == false %}
    <li><a href="{{ site.baseurl }}{{ p.url }}">{{ p.title }}</a></li>
    {% endunless %}
{% endfor %}
</ul>
---

test
