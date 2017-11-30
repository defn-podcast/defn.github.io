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

<div id="defn-container"/>

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

### A little bit of interactive, boostrapped ClojureScript for you

<pre><code class="klipse" data-preamble="(require '[reagent.core :as r])">
(let [anchor (-> js/document (.getElementById "first-post"))]
  (r/render-component 
  [:a {:href (.-href anchor)} (.-text anchor)] 
  js/klipse-container))
</code></pre> 





