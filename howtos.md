---
layout: posts
title: Arduino for Kids -- How To build cool stuff with an Arduino
---
<section class="description">
<p>Want to learn how to make lights flash, sensors sense, robots move and a whole lot more? Check out our how-tos here. Still need to get up-to-speed? Check out our "getting started" section instead. 
</section>
<section class="articlelist">
<ul id="bloglist">
{% for post in site.posts %} 
<li> <h3><a href="{{ post.url }}"> {{ post.title }}</a></h3>
<p>{{ post.excerpt }} | <span class="posted">posted {{ post.date | date: "%B %e, %Y" }}</span></li> 
{% endfor %} 
</ul>
</section>