---
layout: default
title: posts_index
---

# ALL Posts

<nav>
<ul>
<li><a href=""></a>All Posts
<a href=""></a>Bike News
<a href=""></a>Bike Rides
<a href=""></a>Bike Stories</li>
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

 
