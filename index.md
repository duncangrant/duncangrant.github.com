---
layout: page
title: Posts

---

<dl class="posts">
  {% for post in site.posts %}
    <dt><div><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    <span>{{ post.date | date_to_string }}</span>
    </div></dt><dd><p>{{ post.content }}</p>
    <p>
    {% unless post.tags == empty %}
      <ul class="tag_vertical">
      {% assign tags_list = post.tags %}
      </ul>
    {% endunless %}
    </p></dd>
  {% endfor %}
</dl>



