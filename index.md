---
layout: page
title: Posts

---
{% include JB/setup %}

<dl class="posts">
  {% for post in site.posts %}
    <dt><div><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    <span>{{ post.date | date_to_string }}</span>
    </div></dt><dd><p>{{ post.content }}</p>
    <p>
    {% unless post.tags == empty %}
      <ul class="tag_box">
      {% assign tags_list = post.tags %}
      {% include JB/tags_list %}
      </ul>
    {% endunless %}
    </p></dd>
  {% endfor %}
</dl>



