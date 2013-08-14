---
layout: page
title: The Making of.
tagline: "&quot;un passo avanti rispetto al nulla&quot;"
---
{% include JB/setup %}

Latest posts:

<ul class="posts">
	{% for post in site.posts %}
		<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>
