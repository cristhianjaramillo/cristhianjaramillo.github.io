---
permalink: /
title: "<span>Welcome to my academic page!</span>"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


👋 I am a graduate of the London School of Economics and Political Science, in Social Research Methods. My background includes a Bachelor of Social Science in Political Science and Government from the Pontifical Catholic University of Peru.

<div style="float: right; margin: 0px 10px 0px 10px;">
    <img src="images/ivan_theterrible.jpg" width="335" height="240">
    <p style="font-size: 11px; text-align: right;">Painting of the week: Ivan the Terrible and His Son Ivan (1883-85)</p>
</div>
🔍 Currently, I am a Research Assistant at the Care Policy and Evaluation Centre, LSE, and Researcher at the [Observatorio de Reformas Políticas en América Latina](https://www.reformaspolíticas.org). My research focuses on political reforms, public policy, and governance. 

📚 I have also been involved directing academic journals in Latin America such as [Elecciones](https://revistas.onpe.gob.pe/index.php/elecciones) and [Politai](https://revistas.pucp.edu.pe/index.php/politai), contributing to their visibility in academic circles.

📊 My interests extend to quantitative studies, coding, data visualization using R, and my teaching experience encompasses Statistics for Political Analysis at the Pontifical Catholic University of Peru and other institutions.

✨ Beyond my academic work, I hold a profound fascination for art, particularly paintings stemming from the Impressionist movement. I frequently curate and share artworks that catch my attention on my [Art Blog](https://artchronicles.tumblr.com/).
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
