---
layout: default
---


## Show notes for the latest episode

<h2>
  <ul>
    {% for post in site.posts limit:1 %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
    <br>
    {% endfor %}
  </ul>
</h2>

### Show notes for all previous episodes

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


<!-- 

We can add code when we are ready using this ....

<pre><code class="klipse">
    (+ 1 2 3 4)
</code></pre> 

-->

