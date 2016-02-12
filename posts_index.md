---
layout: default
title: posts_index
---

# ALL Posts

<nav>
<ul>
<li><a href=""></a>All Posts</li>
<li><a href=""></a>Bike News</li>
<li><a href=""></a>Bike Rides</li>
<li><a href=""></a>Bike Stories</li>
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

 
