---
layout: page
title: Products
permalink: /products/
---

<!--
This is a dynamically generated list of products.
Product pages and metadata live in the `_products/` folder
-->

These are some of the software products that has been developed by
the projects the eScience Lab are involved with.

{% for product in site.products %}
* [{{ product.title }}]({{ product.url }}) - {{ product.description }}
{% endfor %}
