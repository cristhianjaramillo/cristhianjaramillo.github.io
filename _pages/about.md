---
permalink: /
title: "<span>Welcome to my academic page!</span>"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


👋 I am a quantitative researcher working at the intersection of **public policy, social research and data analysis**. I hold an MSc in Social Research Methods from the London School of Economics and Political Science and a Bachelor's degree in Political Science and Government from the Pontifical Catholic University of Peru.

<div style="float: right; margin: 0px 10px 10px 20px;"> <img src="images/ivan_theterrible.jpg" width="335" height="240"> <p style="font-size: 11px; text-align: right;">Painting of the week: <em>Ivan the Terrible and His Son Ivan</em> (1883–85)</p> </div>

I am currently a **Research Assistant at the Care Policy and Evaluation Centre (LSE)** and a Researcher at the [Observatorio de Reformas Políticas en América Latina](https://www.reformaspolíticas.org). My work combines quantitative methods, administrative and survey data, and policy analysis to study public services, political institutions and governance.

📊 A major part of my work involves **statistical analysis, data integration and reproducible research**, primarily using R, alongside SQL, Stata, Python and data visualisation tools. I am particularly interested in using quantitative methods to understand variation across populations, institutions and geographical areas, and in translating complex evidence into useful insights for policy and research.

🏛️ My research experience spans **health and social care, political reform, electoral behaviour, public-sector governance and the use of artificial intelligence in public policy**. I have worked across academic and governmental institutions in the UK and Latin America and have contributed to research publications, policy reports and methodological outputs.

📚 I have also been involved in academic publishing, including serving as Editor-in-Chief of [Elecciones](https://revistas.onpe.gob.pe/index.php/elecciones) and [Politai](https://revistas.pucp.edu.pe/index.php/politai), where I worked on editorial coordination, publication processes and journal visibility.

🎓 Alongside research, I have experience teaching quantitative methods, including Statistics for Political Analysis at the Pontifical Catholic University of Peru and other institutions.

✨ Outside research, I am particularly interested in art and painting, especially Impressionism and nineteenth-century European art. I occasionally curate and share works that catch my attention on my [Art Blog](https://artchronicles.tumblr.com/).
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
