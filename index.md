---
layout: default
---


## Show notes for the latest episode

<h2>
  <ul>
    {% for post in site.posts limit:1 %}
    <li>
      <a id="first-post" href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
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
We can add content via client-side code when we are ready using this ....


<div id="defn-container"/>

<pre class="hidden"><code class="klipse">
(require '[reagent.core :as r])
(set!
  (.-innerHTML (js/document.getElementById "defn-container"))
  "<div style='color: red;'>Code also <strong>coming</strong> soon!</div>")
</code></pre> 

-->

<pre><code class="klipse">
(-> js/document
    (.getElementById "first-post")
    (.-innerHTML))
</code></pre> 




