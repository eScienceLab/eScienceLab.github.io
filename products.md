---
layout: page
title: Products
permalink: /products/
---

<!--
This is a dynamically generated list of products.
Product pages and metadata live in the `_products/` folder
-->

<h1>Current Products</h1>
These are some of the software products and platforms that have been developed by, and are currently supported by the eScience Lab.

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

<hr/>

<h1>Earlier Products</h1>

These products/platforms were developed by eScience Lab and partners, but are now maintained by other organisations or no longer supported.

<div>
{% for product in site.old_products %}
    <a href="{{ product.url }}" class="product-screenshot old">
        <h3>{{ product.title }}</h3>
        <img src="{{ product.screenshot }}"/>
        <div class="product-description">
            {{ product.description }}
        </div>
    </a>
{% endfor %}
</div>

