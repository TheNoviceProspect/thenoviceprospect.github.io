---
layout: default
permalink: /blog/
---
## Blog Posts

<ul>
{% for post in site.posts %}
  <li><h3>({{ post.date | date_to_string }}) - <a href="{{ post.url }}">{{ post.title }}</a></h3>
  {{ post.excerpt  }}
  </li>
{% endfor %}
</ul>
