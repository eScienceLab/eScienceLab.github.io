---
layout: page
title: Products
permalink: /products/
---

This is a dynamically generated list of products.

Product pages and metadata live in the `_products/` folder

{% for product in site.products %}
* [{{ product.title }}]({{ product.url }}) - {{ product.description }}
{% endfor %}
