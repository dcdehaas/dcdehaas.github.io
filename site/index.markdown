---
layout: default
---

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# Related pages

I am a programmer in the [Wei Lab at Cornell](https://aprilweilab.github.io/).
