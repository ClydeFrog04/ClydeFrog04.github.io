---
layout: page
title: Photoshop Posts
permalink: /PhotoshopPosts/
---

![RecolorEyes](_posts/2018-03-07-RecolorEyes.markdown)


<div class="home">

<h1 class="page-heading">Progress Updates</h1>

<ul class="post-list">
{% for post in site.posts %}
<li>
<span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

<h2>
<a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
</h2>
</li>
{% endfor %}
</ul>
<!--
 <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
 -->

</div>

<div>

<p>If you have any suggestions for anything I should work on, or anything I can do better, send me an email!</p>

</div>
