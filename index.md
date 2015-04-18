---
layout: page
title: OR WebSite
tagline: Do what you love, love what you do!
---
{% include JB/setup %}

## OpenSource List


####JS

  - **js-circle-progress**, which is a pure javascript canvas implementation


## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &raquo;
      <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
