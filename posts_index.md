---
layout: default
title: posts_index
---

# ALL Posts

<nav>
<ul>
<li><a href="">All Posts</a>
<a href="">Bike News&nbsp;&nbsp;</a>s
<a href="">Bike Rides&nbsp;&nbsp;</a>
<a href="">Bike Storie&nbsp;&nbsp;</a>s</li>
</ul>
</nav>
<ul>
{% for post in site.posts %}
<li>
<a href="">{{ post.title }}</a>
<p>{{post.meta}}</p>
</li>
{% endfor %}
</ul>

 
