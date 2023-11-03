---
layout: page
title: Projects
permalink: projects
---

<div>
  {% for post in site.posts %}
    <div class="py-1">
      <h3><a href="{{site.baseurl}}{{ post.url }}">{{ post.title}}</a></h3>
    </div>
  {% endfor %}
</div>


