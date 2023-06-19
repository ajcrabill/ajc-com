---
layout: post
title: Recent Posts 
toplevel: Blog
---

{{ post[1].title }}<br/><br/>

{{ site.posts[1].title }}<br/><br/>


<ul>
  {% for post in site.posts %}
  <li>
    <h5><a href="/ajc-com{{post.url}}">{{post.title}}</a></h5>
  </li>
  {% endfor %}
</ul>
 
