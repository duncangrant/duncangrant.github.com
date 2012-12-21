---
layout: page
title: Hello World!

---
{% include JB/setup %}

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><div><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    <span>{{ post.date | date_to_string }}</span>
    <p>{{ post.content }}</p></div></li>
  {% endfor %}
</ul>



