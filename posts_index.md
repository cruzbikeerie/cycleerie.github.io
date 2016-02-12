---
layout: default
title: posts_index
---

# ALL Posts
{% include post_navs.html %}

<ul>
{% for pages in site.pages %}
 {% if pages.type == 'posts' %}
   <li>
    {{ pages.title }}
   </li>
 {% endif %}
{% endfor %}
</ul>
  

<ul>
{% for post in site.posts %}
<li>
<a href="">{{ post.title }}</a>
<p>{{post.meta}}</p>
</li>
{% endfor %}
</ul>

 
