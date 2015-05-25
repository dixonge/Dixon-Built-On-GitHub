---
layout: archive
permalink: /
title: "Latest Posts"
---

<img src="images/bio-photo.jpg">

<div class="home-right">
<h1>Glenn Dixon</h1>
<h2>Front End Web Developer</h2>
<p>I build responsive sites</p>
</div>

<hr>

<div class="tiles">
{% for post in site.categories.portfolio %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->