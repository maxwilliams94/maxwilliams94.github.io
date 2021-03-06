---
title: "Max Williams, PhD Candidate"
layout: "default"
---
<img src="{{ "assets/banner2.jpg" | relative_url }}" alt="diamond {100} surface" style="width:40vw;float:center">
<p>Max is a PhD Candiate in Computational Modelling at the University of Bristol. He is currently writing-up and expecting to submit his thesis in June 2021.</p>

<p>When he isn't writing Fortran or doing data analysis for his PhD, you can find him:</p>
<ul>
<li>Marathon training</li>
<li>Playing chess online</li>
<li>Learning norwegian</li>
<li>Working on Fortran/Python projects</li>
</ul>

<h3>Reading List</h3>
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

