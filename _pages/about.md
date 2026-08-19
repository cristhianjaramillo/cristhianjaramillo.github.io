---
permalink: /
title: "<span>Welcome to my academic page!</span>"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
👋 I am a **quantitative researcher** working at the intersection of public policy, social research and data analysis. I hold an MSc in Social Research Methods from the London School of Economics and Political Science and a Bachelor's degree in Political Science and Government from the Pontifical Catholic University of Peru.

<div style="float: right; margin: 0px 10px 10px 20px;">
    <img src="images/ivan_theterrible.jpg" width="335" height="240">
    <p style="font-size: 11px; text-align: right;">Painting of the week: <em>Ivan the Terrible and His Son Ivan</em> (1883–85)</p>
</div>

🔍 I am currently a **Research Assistant at the Care Policy and Evaluation Centre (LSE)** and a Researcher at the [Observatorio de Reformas Políticas en América Latina](https://www.reformaspolíticas.org). My research spans health and social care, public policy, political institutions and governance, with a particular interest in applying quantitative methods to understand variation across populations and places.

📊 My work involves statistical analysis, data integration and visualisation, primarily using **R**, alongside SQL, Stata and Python. I have also worked in academic publishing, including as Editor-in-Chief of [Elecciones](https://revistas.onpe.gob.pe/index.php/elecciones) and [Politai](https://revistas.pucp.edu.pe/index.php/politai), and have experience teaching quantitative methods.

✨ Outside research, I have a longstanding interest in art, particularly painting. I occasionally curate works that catch my attention on my [Art Blog](https://artchronicles.tumblr.com/).

<br>
<div style="text-align: left; margin: 0; padding: 0;">
  <!-- Top Border Line -->
  <div style="border-top: 2px solid #333333; margin: 0; padding: 0;"></div>
<br>
<!-- Alert Content -->
<div style="text-align: left; margin: 1; padding: 0;">
  {% assign latest_post = site.posts | first %}
  <h4 style="font-size: 1.4rem; margin: 0;">Last Post:</h4>
  <h5 style="font-size: 1.3rem; margin: 0;">
    <a href="{{ latest_post.url }}" style="text-decoration: underline;">
      {{ latest_post.title }}
    </a>
  </h5>
  <p style="margin: 0.2 rem 0 0 0;">{{ latest_post.excerpt }}</p>
</div>
<div style="text-align: left; margin: 1; padding: 0;">
  {% assign last_article = site.publications | where_exp: "item", "item.type == 'article'" | sort: 'date' | reverse | first %}
  <h4 style="font-size: 1.4rem; margin: 0;">Last Article:</h4>
  <h5 style="font-size: 1.3rem; margin: 0;">
    <a href="{{ last_article.url }}" style="text-decoration: underline;">
      {{ last_article.title }}
    </a>
  </h5>
  <p style="margin: 0.5rem 0 0 0;">{{ last_article.citation }}</p>
  <p style="margin: 0.5rem 0 0 0;">{{ last_article.excerpt }}</p>
</div>
<br>
