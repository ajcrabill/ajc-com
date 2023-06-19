---
layout: post
title: Recent Posts 
toplevel: Blog
---


<h5>{{ site.posts[3].title }}</h5><br/>
{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
{{ site.posts[3].date | date: date_format }} • {{ site.posts[3].author }}<br/><br/>

{{ site.posts[3].content }}<br/><br/>


<ul>
  {% for post in site.posts %}
  <li>
    <h5><a href="/ajc-com{{post.url}}">{{post.title}}</a></h5>
  </li>
  {% endfor %}
</ul>
 
