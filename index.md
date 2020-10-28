---
layout: home
title: Veracruz: privacy-preserving collaborative compute
---

<div class="home">
	<h1 class="heading">Posts</h1>

	<ul class="posts-list">
		{% for post in site.posts %}
		<li>
			<span class="post-meta">{{ post.date | date: "%b %-d, %Y"}}</span>
			<h2>
				<a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{post.title}}</a>
			</h2>
		</li>
		{% endfor %}
	</ul>
</div>
