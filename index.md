---
title: "Max Williams, PhD Candidate"
layout: "default"
page_heading: "Max Williams"
---
<h1>{{ page.page_heading }}</h1>
Under construction...
<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%F" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

