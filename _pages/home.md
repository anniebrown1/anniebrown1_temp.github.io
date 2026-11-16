---
title: "Home"
layout: homelay
permalink: /
---

<h1 class="home-hero">{{ site.name }}</h1>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>

## Selected publications

<div class="section-card selected-pubs" markdown="0">
{{ selected }}
<p style="margin: var(--space-4) 0 0;"><a href="{{ '/publications' | relative_url }}">All publications &rarr;</a></p>
</div>
{% endif %}

## About me

I am a student completing the final year of my combined BS/MS program in mathematics at Loyola University Chicago. My research focuses on high level abstract algebra and combinatorics. I have worked as a Course Assistant for a Linear Algebra course and tutored independently. Outside of my studies, I enjoy playing the harp professionally and playing lacrosse. 
