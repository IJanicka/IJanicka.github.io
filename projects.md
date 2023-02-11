---
layout: page
title: Peer Press projects
permalink: /projects/
---

<div id="col">
{% for post in site.posts %}
  <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a><br>
{% endfor %}
</div>


