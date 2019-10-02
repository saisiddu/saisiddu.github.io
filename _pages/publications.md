---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<**[About me](https://saisiddu.github.io)**>   <**[Projects](https://saisiddu.github.io/portfolio/)**>   <**[Research](https://saisiddu.github.io/research/)**>   <**[Presentations](https://saisiddu.github.io/talks/)**>   <**[Teaching](https://saisiddu.github.io/teaching/)**>   <**[CV](https://saisiddu.github.io/cv/)**>   <**[Contact](https://saisiddu.github.io/contact/)**>