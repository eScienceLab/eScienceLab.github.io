---
layout: page
title: Products
permalink: /products/
---

<!--
This is a dynamically generated list of products.
Product pages and metadata live in the `_products/` folder
-->

These are some of the software products that have been developed by
the projects the eScience Lab are involved with.

<div>
{% for product in site.products %}
    <a href="{{ product.url }}" class="product-screenshot">
        <h3>{{ product.title }}</h3>
        <img src="{{ product.screenshot }}"/>
        <div class="product-description">
            {{ product.description }}
        </div>
    </a>
{% endfor %}
</div>

