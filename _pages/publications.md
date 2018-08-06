---
title: "Choi Lab - Publications"
layout: gridlay
excerpt: "Choi Lab -- Publications."
sitemap: false
permalink: /publications/
---

(For a full list see [below](#full-list) or go to [Google Scholar](https://scholar.google.com/citations?user=UY9qarUAAAAJ&hl=en)

## Full List

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
