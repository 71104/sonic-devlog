---
layout: page
title: The Making Of
tagline: "&quot;un passo avanti rispetto al nulla&quot;"
---
{% include JB/setup %}

It's [Sonic](http://en.wikipedia.org/wiki/Sonic_the_Hedgehog_%28series%29) we're talkin' about.

![Sonic the Hedgehog](http://upload.wikimedia.org/wikipedia/en/6/6d/Sonic1.png)

We want to see it remastered in 3D.

Latest posts:

<ul class="posts">
	{% for post in site.posts %}
		<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>
