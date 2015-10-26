---
layout: page
title: My Projects
---
<ul>
  {% for post in site.posts %}
    <div>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    <hr>
    </div>
  {% endfor %}
</ul>

<!---
[markdown](http://en.wikipedia.org/wiki/Markdown)
-->
