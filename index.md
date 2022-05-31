---
title: "Max Williams, PhD"
layout: "default"
---
<img src="{{ "assets/banner2.jpg" | relative_url }}" alt="diamond {100} surface" style="width:40vw;float:center">
<p>After completing my PhD in Computational Chemistry in March 2022, I am currently working as a Python Engineer at mthree, on-site at Nomura Holdings.</p>

<p>Interests</p>
<ul>
<li>Gym</li>
<li>Running</li>
<li>Online chess </li>
<li>Speaking/Learning Norwegian</li>
<li>Learning..</li>
</ul>

<h3>Books I'm currently reading:</h3>
<ul class="book-list">
<li><i>The Wheel of Time: 5. The Fires of Heaven</i> - Robert Jordan</li>
<li><i>The Phoenix Project</i> - G. Kim, K. Behr, G. Spafford</li>
<li><i>The Mystery of Nils</i> - Werner Skalla</li>
<li><i>A Philosophy of Software Design</i> - John Ousterhout</li>
<li><i>Introduction to Algorithms</i> - T. H. Cormen, C. E. Leiserson, R. L. Rivest, C. Stein</li>
<!--<li><i>Beginning C - Ivor Horton</i></li> -->
<!--<li><i>Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow</i> - Aurélien Géron</li>-->
</ul>

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%F" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
