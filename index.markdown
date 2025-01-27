---
layout: default
title: GXC.INFO's Corner
---

Hi there, I am Mason Guo, an Open Source enthusiast. This site is dedicated to providing information about me and my works.

<p><br /><b>My Blog:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

<p><b>Find me on:</b></p>

<ul>
  <li><a href="http://github.com/Mason-Guo/">Github</a></li>
</ul>
<p><br /><b>What's Up:</b></p>
<blockquote>
贵有恒，何必三更起五更睡；最无益，只怕一日曝十日寒。
</blockquote>
