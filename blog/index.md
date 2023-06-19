---
layout: post
title: Recent Blog Posts
toplevel: Blog
---

<ul>
<li><a href="/ajc-com{{site.posts[3].url}}">{{ site.posts[3].title }}</a>
    <ul>
    <!--<li>{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    {{ site.posts[3].date | date: date_format }} • {{ site.posts[3].author }}</li>-->
    <li>{{ site.posts[3].content | strip_html | truncatewords: 50 }}</li>
    </ul><br/><br/>
</li>

<li><a href="/ajc-com{{site.posts[0].url}}">{{ site.posts[0].title }}</a>
    <ul>
    <!--<li>{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    {{ site.posts[0].date | date: date_format }} • {{ site.posts[0].author }}</li>-->
    <li>{{ site.posts[0].content | strip_html | truncatewords: 50 }}</li>
    </ul><br/><br/>
</li>

<li><a href="/ajc-com{{site.posts[4].url}}">{{ site.posts[4].title }}</a>
    <ul>
    <!--<li>{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    {{ site.posts[4].date | date: date_format }} • {{ site.posts[4].author }}</li>-->
    <li>{{ site.posts[4].content | strip_html | truncatewords: 50 }}</li>
    </ul><br/><br/>
</li>

</ul><br/>

<h1>All Blog Posts</h1>
<ul>
  {% for post in site.posts %}
  <li>
    <h5><a href="/ajc-com{{post.url}}">{{post.title}}</a></h5>
  </li>
  {% endfor %}
</ul>
 
