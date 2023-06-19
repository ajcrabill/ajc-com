---
layout: post
title: Recent Posts 
toplevel: Blog
---


{{ site.posts[3].title }}<br/>
{{ site.posts[3].date }} • {{ site.posts[3].author }}<br/><br/>

{{ site.posts[3].excerpt }}<br/><br/>

{{ site.posts[3].content }}<br/><br/>


<ul>
  {% for post in site.posts %}
  <li>
    <h5><a href="/ajc-com{{post.url}}">{{post.title}}</a></h5>
  </li>
  {% endfor %}
</ul>
 
