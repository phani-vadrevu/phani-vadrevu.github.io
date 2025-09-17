---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% comment %}
    {% if site.author.googlescholar %}
      You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
    {% endif %}
{% endcomment %}

{% include base_path %}

Our research work is regularly submitted and published at security and measurement conference venues. Our previous works got published at highly selective and top-tier conferences such as S&P ['24x2], USENIX Security ['25x2, '21], NDSS ['18,'17], WWW ['25], and IMC ['22x2,'20,'19] as well as other reputable venues such as EuroS&P ['23], DIMVA ['22], AsiaCCS ['16] and ESORICS ['13].
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
