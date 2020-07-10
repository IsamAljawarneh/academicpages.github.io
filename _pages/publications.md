---
layout: archive
title: "Publications [(Google Scholar)](https://scholar.google.com/citations?user=hv5C-NIAAAAJ&hl=en)"
permalink: /publications/
author_profile: true
---
## Peer-reviewed International Journals and Magazines

<b>[A Pre-Filtering Approach for Incorporating Contextual Information Into Deep Learning Based Recommender Systems]({% include base_path %}IEEE_Access2020)</b><br>
<b>Isam Mashhour Al Jawarneh</b>, Paolo Bellavista, Antonio Corradi, Luca Foschini, Rebecca Montanari, Javier Berrocal, Juan Manuel Murillo. <i>IEEE Access</i>. <b>2020</b>.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
