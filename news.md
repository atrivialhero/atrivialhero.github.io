---
layout: default
title: News
sitemap:
   priority: 1
   changefreq: weekly
   lastmod: 2014-05-10T12:00:00-08:00
---

{% for post in site.posts %}
   <h3>{{ post.title }}<br />
      <small>{{ post.date | date: "%B %-d, %Y" }}</small></h3>
   {{ post.content }}
   <hr />
{% endfor %}
