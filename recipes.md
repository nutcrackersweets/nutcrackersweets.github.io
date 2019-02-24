---
layout: page
title: Recipes
permalink: /recipes/
---

You could host a bunch of recipes you've made or that you've prefected.

They would get collected and displayed on this page.


<ul>
{% for recipe in site.recipes %}
  <li><a href="{{ recipe.permalink }}">{{ recipe.title }}</a></li>
{% endfor %}
</ul>



