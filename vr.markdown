---
layout: page
title: Virtual Reality
permalink: /VR/
---

This is where you'll find blog posts for the graduate class DM-GY 9103 Virtual Reality.

<h4>Macro Project</h4>
{% for post in site.categories.macroproject %}
  <ul>
      <li><a href="{{post.url}}">{{post.date | date: "%B %d, %Y: " | append: post.title}}</a></li>
  </ul>
{% endfor %}


<h4>Posts</h4>
{% for post in site.categories.VR %}
  <ul>
      <li><a href="{{post.url}}">{{post.date | date: "%B %d, %Y: " | append: post.title}}</a></li>
  </ul>
{% endfor %}