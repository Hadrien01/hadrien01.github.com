---
layout: default
title: Hadrien01
---
{% for post in site.posts %}
<article>
	<h2><a href="{{ post.url }}">{{ post.title }}</a><time> - {{ post.bdate }}</time></h2>
	{{ post.summary }}
</article>
{% endfor %}