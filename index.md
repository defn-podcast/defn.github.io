---
layout: default
---

## Show notes for the latest episode

<h3>
  <ul>
    {% for post in site.posts limit:1 %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
    <br>
    {% endfor %}
  </ul>
</h3>

## Show notes for all episodes

<h3>
  <ul>
    {% for post in site.posts offset:1 %}
      <li>
          <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      </li>
      <br>
    {% endfor %}
  </ul>
</h3>

##### content being ported .... more soon...