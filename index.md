---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
title: 近期文章
---

<div class="home">
	<ul class="posts">
		{% for i in (0..10) %}
		{% if i ==  8 %}
			{% break %}
		{% else %}
			<li> <span class="post-date">{{ site.posts[i].date | date: "%b %-d, %Y" }}</span>
			<a class="post-link" href="{{ site.posts[i].url | prepend: site.baseurl }}">{{ site.posts[i].title }}</a>
			</li>

		{% else %}
			{% break %}
		{% endif %}
    {% endfor %}
	</ul>
<div>
