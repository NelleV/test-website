---
layout: page
title: People (test)
subtitle: More about us …
---

{% for people in site.people %}
    {% include archive-single-people.html %}
{% endfor %}
