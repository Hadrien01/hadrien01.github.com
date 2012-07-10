---
layout: default
title: Blog
---
{% for post in site.posts %}
<article>
	<h2><a href="{{ post.url }}">{{ post.title }}</a><time> - {{ post.date | date: "%B %e, %Y" }}</time></h2>
	{{ post.summary }}
</article>
{% endfor %}