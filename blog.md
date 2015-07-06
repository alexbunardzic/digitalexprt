---
layout: page
title: Blog
---

<div class="post-link">Posts by Alex Bunardzic</div><p/>

<div class="home">

  <ul class="post-list">
    {% for post in site.posts %}
      <li>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          <div class="post-meta">{{post.content | strip_html | truncatewords:25}}...</div>
          <!--div>{{ post.date | date: "%b %-d, %Y" }}</div-->
        </h2>
      </li>
    {% endfor %}
  </ul>
  <br />
  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>


</div>

