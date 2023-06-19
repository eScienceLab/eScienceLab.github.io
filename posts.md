---
layout: page
title: News
permalink: /posts/
---

  <ul class="post-list">
    {% for post in site.posts %}
      {% unless post.draft %}
      <li>
        <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
     {% endunless %}
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
