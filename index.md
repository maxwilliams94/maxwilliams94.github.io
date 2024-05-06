---
title: "Max Williams, PhD"
layout: "default"
---
<img src="{{ "assets/banner2.jpg" | relative_url }}" alt="diamond {100} surface" style="width:40vw;float:center">

 <p>I began my software development career in mid-2021, joining Wiley-Edge while I finished writing my thesis. After completing my PhD in Computational Chemistry in March 2022, I went on to join Nomura permanently as an Associate Software Developer in December 2022. As scrum-master and lead developer within the Trading & Operations team, I analyse, architect and deliver projects for Nomura's Structured Rates division and  global risk platform.</p>

<p>I strive to continuously improve the wider team's development, release and testing methodologies, leveraging new and upcoming technologies when appropriate. As part of the Global Markets Software Modernisation working group, I volunteer my time to make teams in the wider business aware of available containerisation and orchestration technologies, along with newly rolled out CI/CD and IaaC workflows. As part of this role, I provide feedback and work through issues as an early adopter.</p> 

<p>I enjoy going to the gym, climbing, training Brazilian Ju-Jitsu in my spare time.  When not active, I study Norwegian and try to ensure I am continuously improving my software development knowledge and understanding. When I have time, I like to play chess online, often blundering my queen.</p>


<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%F" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
