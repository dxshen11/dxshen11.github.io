---
layout: default
title: Experiences
---

{% for experiences in site.experiences %}

<a href="{{ experiences.url | prepend: site.baseurl }}">
  <h2>{{ experiences.title }}</h2>
</a>

<p class="post-excerpt">{{ experiences.description | truncate: 160 }}</p>

{% endfor %}  