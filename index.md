---
layout: default
---

The [eScience team][eSt] have produced and continue to develop a suite of [products][prod] designed to “help e-Scientists get on with science and get on with scientists”. The tools support the creation of e-laboratories and have been used in domains as diverse as systems biology, social science, music, astronomy, multimedia and chemistry. The tools have been adopted by a large number of projects and institutions.

Products
===
{% for product in site.products %}
  [![{{ product.title }}][{{product.name}}-logo]=200px](/products/{{ product.name }})
{% endfor %}


[eSt]: /people
[prod]: /products


[service_catalographer-logo]: {{ site.url }}/images/logo/service_catalographer_logo.png "Service Catalogue"
[myexperiment-logo]: {{ site.url }}/images/logo/MyExperiment_logo.png "MyExperiment"
[rightfield-logo]: {{ site.url }}/images/logo/rightfield-logo-with-text.png "RightField"
[taverna-logo]: {{ site.url }}/images/logo/taverna_logo.png "Taverna"
[seek-logo]: {{ site.url }}/images/logo/seek4science-logo.png "Seek"
[methodbox-logo]: {{ site.url }}/images/logo/methodbox.png "Methodbox"
[tess-logo]: {{ site.url }}/images/logo/tess.png=200px "TeSS"
