---
title: "IDS Lab - Research"
layout: textlay
excerpt: "IDS Lab -- Research"
sitemap: false
permalink: /research/
---

# Publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

# Projects

{% for proj in site.data.projects %}

  {{ proj.title }} <br />
  <em>{{ proj.department }} </em><br />{{ proj.link.date }}

{% endfor %}

