---
layout: page
title: Musiciens membres
excerpt: "Musiciens membres de l'harmonie"
search_omit: true
---

<figure>
	<img src="/images/top_img_big.jpg">
</figure>

<ul class="post-list">
  {% for post in site.categories.membre %}
  <li>
    <h3>{{post.title}}</h3>
    <figure class="half">
      <img src="{{post.image.feature}}"/>
      <span>
        {{post.excerpt}}
      </span>
    </figure>
  </li>
  {% endfor %}
</ul>
