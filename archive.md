---
layout: page
title: Archives
---
{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }}) - <span class="fb-like" data-href="{{ post.url }}" data-layout="button_count" data-action="like" data-show-faces="true" data-share="true"></span>
{% endfor %}
