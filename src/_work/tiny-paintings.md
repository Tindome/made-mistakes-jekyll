---
layout: page
permalink: /tiny-paintings/
category: tiny-paintings
title: "Tiny Paintings"
excerpt: &excerpt "Gallery of mini watercolor portraits painted at really small sizes."
image: 
  cover: /assets/images/tiny-paintings-lq.jpg
  thumbnail: /assets/images/tiny-paintings-th.jpg
  teaser: &image /assets/images/tiny-paintings-teaser.jpg
  path: *image
tags: [watercolor, painting, drawing, portrait, illustration]
ads: false
work: "Illustration"
order: 3
last_modified_at: 2017-04-08T22:46:16-04:00
---

Trying to emulate the look and feel of [watercolor on the iPad]({{ site.url }}/paperfaces/) has inspired me to revisit painting traditionally. I've gone mini in an effort to fit some painting in amongst family and work obligations. 

My plan was to complete a miniature 1.5\" painting a day, but the challenge of painting so small is eating up way too much time. Instead I'm going to keep things casual and let images happen as they happen.

<ul class="th-grid">
{% for post in site.categories.tiny-paintings %}
  <li>
    <a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">
      <noscript>
        <img src="{{ site.url }}{{ post.image.thumbnail }}">
      </noscript>
      <img class="lazyload fade-in" src="{{ site.url }}/assets/images/preload-150.png" data-src="{{ site.url }}{{ post.image.thumbnail }}" alt="">
    </a>
  </li>
{% endfor %}
</ul>
