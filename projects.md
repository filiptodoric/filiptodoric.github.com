---
layout: page
title: My Projects
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

<!---
[markdown](http://en.wikipedia.org/wiki/Markdown)
-->
