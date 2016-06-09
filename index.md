---
layout: default
---

<script src="https://cdnjs.cloudflare.com/ajax/libs/masonry/3.3.2/masonry.pkgd.min.js"></script>

The [eScience Lab](/about/) research group is led by [Professor Carole Goble](http://www.manchester.ac.uk/research/Carole.goble/). The group is based at the [School of Computer Science](http://www.cs.manchester.ac.uk/),  [University of Manchester](http://www.manchester.ac.uk). It's affiliated with the wider [Information Management Group](http://www.cs.manchester.ac.uk/img/).

The [eScience Lab team](/people/) have produced and continue to develop a suite of [products](/products/) designed to aid reseachers with their computationally based needs. The tools support the creation of e-laboratories and have been used in domains as diverse as systems biology, social science, music, astronomy, multimedia and chemistry. The tools have been adopted by a large number of projects and institutions.

Our [research](/publications/) and [projects](/projects/) span a wide array of topics, including eScience, bioinformatics, biodiversity, scholarly communication, reproducible science, linked data, provenance, community building and knowledge representation.

<div class="grid js-masonry"
  data-masonry-options='{ "itemSelector": ".grid-item", "columnWidth": 325 }'>
  {% for product in site.products %}  
    <div class="grid-item product-listing">
      <a href="{{product.url}}"><img src="{{product.logo}}"/></a>
    </div>
  {% endfor %}
</div>
