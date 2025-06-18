---
layout: archive
title: "<span>Publications</span>"
permalink: /publications/
author_profile: true
---

<div style="border: 2px solid grey; padding: 10px;">
Explore my full academic journey and discover my collection of scholarly works, including books, chapters, papers, reviews, and more, accessible <a href="https://www.researchgate.net/profile/Cristhian-Jaramillo-2/research"><strong>here</strong></a>.
</div>

## <span>Articles</span>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign publications = site.publications | where_exp: "item", "item.type == 'article'" %}
{% for post in publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## <span>Book chapters</span>

{% if author.googlescholar %}
  You can also find my book chapters on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign publications = site.publications | where_exp: "item", "item.type == 'book_chapter'" %}
{% for post in publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## <span>Books</span>

{% if author.googlescholar %}
  You can also find my books on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign publications = site.publications | where_exp: "item", "item.type == 'book'" %}
{% for post in publications reversed %}
  {% include archive-single.html %}
{% endfor %}