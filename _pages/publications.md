---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

# <span style='color:#800080'>Articles</span>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign publications = site.publications | where_exp: "item", "item.type == 'article'" %}
{% for post in publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# <span style='color:#800080'>Book chapters</span>

{% if author.googlescholar %}
  You can also find my book chapters on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign publications = site.publications | where_exp: "item", "item.type == 'book_chapter'" %}
{% for post in publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# <span style='color:#800080'>Books</span>

{% if author.googlescholar %}
  You can also find my books on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign publications = site.publications | where_exp: "item", "item.type == 'book'" %}
{% for post in publications reversed %}
  {% include archive-single.html %}
{% endfor %}