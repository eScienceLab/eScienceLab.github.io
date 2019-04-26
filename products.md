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
These are some of the software products that have been developed by, and are currently supported by the eScience Lab.

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

<h1>Former Products</h1>
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

