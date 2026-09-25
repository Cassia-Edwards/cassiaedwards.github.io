---
title: "Blog"
layout: page
sitemap: false
permalink: /blogs/
---
This might see some use, this might not! Watch this space! (Maybe) 
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_string }}: <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title}}</a>
    </li>
  {% endfor %}
</ul>
