---
layout: default
permalink: /blog/
---

[TheNoviceProspect]({{ site.url  }}).

[About TheNoviceProspect's Blog](/about/).

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
