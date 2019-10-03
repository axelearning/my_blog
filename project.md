---
layout: page
title: Projects
permalink: /project/
---
[Click Here]({{site.github_page}}) to find on on my github page the projects I am working on. You can also  find bellow papers with description for each project.

<ul>
	{% assign project = site.posts | where: "categories","project" %}
	{% for post in project %}
	    <li>
	      <a href="/my_blog{{ post.url }}">{{ post.title }}</a>
	    </li>
	{% endfor %}
</ul>



