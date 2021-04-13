---
layout: page
title:  "Projects"
permalink: "/projects/"
---

![banner](/assets/banner.png)


{% for projects in site.projects %}

<h3>{{projects.title}}</h3>

<p class="post-excerpt">{{ projects.description | truncate: 300}} <a href="{{ projects.url }}" style="text-decoration:none"> Read more here.</a></p>

{% endfor %}  
