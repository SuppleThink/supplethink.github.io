---
layout: page
title: Supple Think
tagline: A Blog.
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li>
    	<span>{{ post.date | date_to_string }}</span> &raquo; <br>
	<h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
    	<p>
   		{{ post.content }} 
	</p>
	<i class="fa fa-laptop fa-3x"></i><br><br>
    </li>
  {% endfor %}
</ul>

<br>
<br>
