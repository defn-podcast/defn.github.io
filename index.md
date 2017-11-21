---
layout: default
---

## Show notes per episode

<h3>
  <ul>
    {% for post in site.posts %}
      <li>
          <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      </li>
      <br>
    {% endfor %}
  </ul>
</h3>
