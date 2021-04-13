---
layout: page
title:  "Experiences"
---

{% for experiences in site.experiences %}

<h3>{{experiences.title}}</h3>

<p class="post-excerpt">{{ experiences.description | truncate: 300}} <a href="{{ experiences.url }}" style="text-decoration:none"> Read more here.</a></p>

{% endfor %}  
