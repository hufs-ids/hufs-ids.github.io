---
title: "IDS Lab - Research"
layout: textlay
excerpt: "IDS Lab -- Research"
sitemap: false
permalink: /research/
---

# Publications

## International Conference

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

## International Journal

{% for ij in site.data.intl_journal %}

  {{ ij.title }} <br />
  <em>{{ ij.authors }} </em><br /><a href="{{ ij.link.url }}">{{ ij.link.display }}</a>

{% endfor %}

## Domestic Conference

{% for dc in site.data.domestic_conf %}

  {{ dc.title }} <br />
  <em>{{ dc.authors }} </em><br /><a href="{{ dc.link.url }}">{{ dc.link.display }}</a>

{% endfor %}

# Projects

{% for proj in site.data.projects %}

  {{ proj.title }} <br />
  <em>{{ proj.department }} </em><br />{{ proj.date }}

{% endfor %}

