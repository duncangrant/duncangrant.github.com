---
layout: page
title: Hello World!

---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><div class="row"><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    <span>{{ post.date | date_to_string }}</span>
    <p>{{ post.content }}</p></div></li>
  {% endfor %}
</ul>



