---
layout: page
tagline: Christopher Collier on Web
---
{% include JB/setup %}

[resume](resume.html)


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
