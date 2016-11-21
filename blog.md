---
layout: default
title: Blog
navigation: 5
---

{% assign post = site.posts.first %}

<section class="post">
  <h1><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h1>
  <p class="post-meta">{{ post.date | date_to_string }}</p>
  {{ post.content | markdownify }}
</section>

{% include pagination.html %}


<br>
<hr>
<br>

<p><a href="{{ '/archives.html' | prepend: site.baseurl }}">Blog archive</a></p>