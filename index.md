---
layout: default
---

<script src="https://cdnjs.cloudflare.com/ajax/libs/masonry/3.3.2/masonry.pkgd.min.js"></script>

The [eScience team][eSt] have produced and continue to develop a suite of [products][prod] designed to “help e-Scientists get on with science and get on with scientists”. The tools support the creation of e-laboratories and have been used in domains as diverse as systems biology, social science, music, astronomy, multimedia and chemistry. The tools have been adopted by a large number of projects and institutions.

Products
===
<div class="grid js-masonry"
  data-masonry-options='{ "itemSelector": ".grid-item", "columnWidth": 320 }'>
  {% for product in site.products %}  
    <div class="grid-item product-listing">
      <a href="{{product.url}}"><img src="{{product.logo}}"/></a>
    </div>
  {% endfor %}
</div>


[eSt]: /people
[prod]: /products



