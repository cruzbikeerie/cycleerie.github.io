---
layout: default
title: posts_index
---

# ALL Posts
{% include post_navs %}

<ul>
{% for post in site.posts %}
<li>
<a href="">{{ post.title }}</a>
<p>{{post.meta}}</p>
</li>
{% endfor %}
</ul>

 
