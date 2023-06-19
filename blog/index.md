---
layout: post
title: 
toplevel: Blog
---

<br/>
<h5>Recent Blog Posts</h5>
<ul>
<li>{{ site.posts[3].title }} • 
{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
{{ site.posts[3].date | date: date_format }} • {{ site.posts[3].author }}<br/>
{{ site.posts[3].content | strip_html | truncatewords: 50 }}<br/></li>

<li>{{ site.posts[0].title }} • 
{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
{{ site.posts[0].date | date: date_format }} • {{ site.posts[0].author }}<br/>
{{ site.posts[0].content | strip_html | truncatewords: 50 }}<br/></li>

<li>{{ site.posts[4].title }} • 
{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
{{ site.posts[4].date | date: date_format }} • {{ site.posts[4].author }}<br/>
{{ site.posts[4].content | strip_html | truncatewords: 50 }}<br/></li>

</ul><br/>

<h5>All Blog Posts</h5>
<ul>
  {% for post in site.posts %}
  <li>
    <h5><a href="/ajc-com{{post.url}}">{{post.title}}</a></h5>
  </li>
  {% endfor %}
</ul>
 
