---
title: "Max Williams, PhD Candidate"
layout: "default"
---
<img src="{{ "assets/banner2.jpg" | relative_url }}" alt="diamond {100} surface" style="width:40vw;float:center">
<p>I am a PhD Candiate in Computational Modelling at the University of Bristol. I am currently writing up and expecting to submit my thesis in June 2021.</p>

<p>When I'm not developing my model or doing data analysis for my PhD, you can find me:</p>
<ul>
<li>Training for a marathon</li>
<li>Playing chess online</li>
<li>Learning Norwegian</li>
<li>Contributing to <a href="https://github.com/AlexBuccheri/mpilib20" target="_blank">mpilib20</a> (Open MPI library)</li>
</ul>

<h3>Books I'm currently reading:</h3>
<ul class="book-list">
<li><i>The Wheel of Time: 3. The Shadow Rising</i> - Robert Jordan</li>
<li><i>The New Turing Omnibus</i> - Alexander Dewdney</li>
<li><i>Beginning C - Ivor Horton</i></li>
<li><i>Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow</i> - Aurélien Géron</li>
<li><i>The Special One</i> - Diego Torres</li>
</ul>

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%F" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

