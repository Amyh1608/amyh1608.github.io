---
layout: page
title: Virtual Reality
permalink: /VR/
---

This is where you'll find blog posts for the graduate class DM-GY 9103 Virtual Reality.

<h3>Posts</h3>
{% for post in site.categories.VR %}
  <ul>
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  </ul>
{% endfor %}