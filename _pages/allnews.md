---
title: "Quick Links"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## Quick Links

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.name }}</b>
<p><a href="{{ article.link }}">{{ article.text }}</a></p>
{% endfor %}

</div>
