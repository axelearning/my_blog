---
layout: page
title: Teaching
permalink: /teaching/
---
Even if I am a beginner a good exercise when you learn is to teach the subject. In that section, you can find articles where I explain what I have learned.

<ul>
	{% assign project = site.posts | where: "categories","teaching" %}
	{% for post in project %}
	    <li>
	      <a href="/my_blog{{ post.url }}">{{ post.title }}</a>
	    </li>
	{% endfor %}
</ul>



