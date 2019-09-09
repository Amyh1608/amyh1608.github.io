---
layout: page
title: Ideation & Prototyping
permalink: /IP/
---

This is where you'll find blog posts for the graduate class DM-GY 6053 Ideation & Prototyping. 

<h3>Posts</h3>
{% for post in site.categories.IP %}
  <ul>
      <li><a href="{{post.url}}">{{post.date | date: "%B %d, %Y: " | append: post.title}}</a></li>
  </ul>
{% endfor %}
