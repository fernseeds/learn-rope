---
layout: default
---
<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h1><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title | escape }}</a></h1>
    </li>
  {% endfor %}
</ul>
